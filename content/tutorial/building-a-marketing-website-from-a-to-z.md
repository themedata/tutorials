+++
date = "2019-01-09T00:00:00Z"
description = "A step to step guide on building a marketing website quickly."
draft = false
gt_page_builder = true
header_class = "bg-transparent"
icon_mask = "square"
inner_icon = "th"
inner_icon_transform = "shrink-6"
iscjklanguage = false
lastmod = "2019-01-09T00:00:00Z"
lightness = 0.0
lightness_dark = 0.0
lightness_light = 0.0
lightness_lighter = 0.0
logo_url = "/images/logos/icon-on-dark.svg"
main_menu_align = "start"
primary_hue = 351.0
publishdate = "2019-01-09T00:00:00Z"
saturation = 32.0
skip_cover_nav = false
skip_slide_animation = false
title = "Building a Website from A to Z"
type = "presentation"

[[gmgt_section]]
id = "898b3"
partial = "goandtalk/cover/hero-dark-background-with-text-at-center"

  [gmgt_section.data]
  card_font_size = 3.0
  card_font_weight = 1.0
  card_letter_spacing = "tracked"
  card_text_align = "tc-ns"
  content = "with innovation."
  description = "a marketing website from a to z"
  intro = "Go and Talk "
  title = "Building"
  title_align = "tc"
  title_class = "gold"
  title_color = "gold"
  title_font_family = "baskerville"
  title_font_size = -5.0
  title_font_weight = 4.0
  title_letter_spacing = "tracked"

    [gmgt_section.data.appearance]
    section_background = "bg-black-90"
    trigger_class = "slide-trigger"

    [gmgt_section.data.base_image]
    overlay_background = "bg-black-05"
    responsive = false

    [gmgt_section.data.bg_icon]
    animation = "slowUp"
    bg_icon_color = "white-10"
    bg_icon_display = "self-center"
    bg_icon_size = "fa-3x"
    icon_mask = "coffee"
    inner_icon = "gift"
    inner_icon_transform = "shrink-10 up-2 left-1"

    [gmgt_section.data.cta]
    background_color = "bg-black-20"
    button_text_color = "white-90"
    name = "Play Slides ->"
    pv = 1.0
    title = "view page as slides. "
    url = "#"

    [gmgt_section.data.cta2]
    name = "Tutorials"
    url = "/tutorial/"

    [gmgt_section.data.image]
    animation = "none"
    flow_end = true
    overlay_background = "bg-transparent"
    responsive = false

    [gmgt_section.data.menu]

      [[gmgt_section.data.menu.global]]
      url = "/tutorial/"
      name = "Tutorials"
      menu = "global"
      identifier = "tutorials"
      pre = ""
      post = ""
      weight = 5.0
      parent = ""

      [[gmgt_section.data.menu.global]]
      url = "/presentation/"
      name = "Talks"
      menu = "global"
      identifier = "talks"
      pre = ""
      post = ""
      weight = 10.0
      parent = ""

      [[gmgt_section.data.menu.global]]
      url = "/about/"
      name = "About"
      menu = "global"
      identifier = "about"
      pre = ""
      post = ""
      weight = 15.0
      parent = ""

      [[gmgt_section.data.menu.iconmenu]]
      url = "#"
      name = "Go Account"
      menu = "iconmenu"
      identifier = ""
      pre = "Go"
      post = ""
      weight = 0.0
      parent = ""

[[gmgt_section]]
id = "abedb"
partial = "goandtalk/slides/collection-big-icon-mono"

  [gmgt_section.data]
  column_class = "w-25-l"
  description = "  "
  horizontal_position = "justify-center"
  intro = " "
  is_global = false
  resize_column = "flex-auto"
  title = "Overview of This Tutorial"

    [gmgt_section.data.appearance]
    animation = "fadeIn"
    card_background = "hover-primary-color"
    icon_color = "black-20 hover-primary-color"
    link_color = "link-gold"
    section_background = "bg-white-90"
    slide_animation = "fadeIn"
    text_color = "primary-color-first-letter-h3"

    [[gmgt_section.data.column]]
    description = "* get familiar with the page builder.\n* create a website for an imaginary shop called Toffee & Coffee\n* load setting and sample pages from remote storage on Github\n* upload images to Github and select these images in media library."
    icon = "paint-roller"
    title = "Hands On"

    [[gmgt_section.data.column]]
    description = "* try different layout\n* change images and content\n* embed a map\n* embed a video\n* enable a contact form"
    icon = "palette"
    title = "Customize"

    [[gmgt_section.data.column]]
    description = "Publish the page online for others to see."
    icon = "globe"
    title = "Publish Online"

[[gmgt_section]]
id = "sc0qh5p8t"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* a computer with internet connection. \n* a free Github account. This is optional if you already have a web hosting account and your domain name.\n* images you want to use on the website. \n* text and the story you want to tell.\n* go through the [page builder overview](/tutorial/an-overview-of-go-and-talk-and-ui/) to get familiar with the toolbars."
  intro = " "
  is_global = false
  title = "Preparation"

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "th"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 30.0

[[gmgt_section]]
id = "sojc50t9h"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* create a new organization in your Github account. The organization name must be unique, but not necessarily a registered business name. This tutorial uses the organization name \"toffee-and-coffee\". You will need to pick a different name.\n* your organization name is referred as [orgname] below. Please replace it with the actual name.\n* go to [https://github.com/toffee-and-coffee/toffee-and-coffee.github.io](https://github.com/toffee-and-coffee/toffee-and-coffee.github.io), and click on the fork button at the top right corner.  Then follow the prompt and select the organization account to fork this repository.\n* click on the settings tab below the repository name, and rename this newly forked repository following the pattern [orgname].github.io.  \n* you need to click on the rename button to confirm the name change. Github will enable site hosting for this repository automatically after the renaming. \n* check and verify you can visit the demo page by entering the address [orgname].github.io. \n* if you can't visit the page yet, try again after a little while. It may take a few seconds for the page to work, but occasionally it takes longer."
  intro = " "
  is_global = false
  title = "Creating an Organization on Github.com"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "briefcase"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "smg7zd2v1"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* Upload your images to the \"images\" folder of the repository  you have forked and renamed, if the images are on your computer.\n* Your images will be available under the link [orgname].github.io/images/[image-name]. \n* Supported image suffix: jpg, jpeg, png, gif, webp, svg. You may give a meaningful name to the images in order to search by name later. \n* Big images are slow to upload and download. You may  resize them before uploading. \n* You can also link to your images online, or search for free images and link directly to custom resized images from [unsplash](https://unsplash.com). "
  intro = " "
  is_global = false
  title = "Uploading Images to Github.com"

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "images"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 30.0

[[gmgt_section]]
id = "sqdubww5f"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* you can open another tab and click this link to [create a new site project](/edit/?site=toffee_and_coffee). You will see a placeholder page without navigation menu links.\n* a database by the name toffee_and_coffee will be created automatically in your browser. \n* hover on the left edge of the screen to show the vertical toolbar, click on the globe icon to show site setting window, click on the grid icon(<i class=\"fas fa-th-large\"></i>) to show extra tabs.\n* go to tab \"Remote Setting\", enter \"themedata\" as data repo owner and \"toffee-and-coffee\" as data repo name, then click on the button \"Load Remote Site Setting\". This will load the theme's default settings, and the navigation menu links.\n* go to tab \"Current\", and update your website information and copyright statement there. The base url must be updated to your new website address, so that the media library knows where to find your uploaded images.\n* hover on the top edge of the screen to show the horizontal app toolbar, and click on \"Save\" button to save the changes."
  intro = " "
  is_global = false
  title = "Loading Theme Setting with Go and Talk Page Builder"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "globe-asia"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "sxva4e7bg"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* hover on the left edge of the screen to show the vertical toolbar, click on the file icon(<i class=\"fas fa-file-alt\"></i>) to show page setting window, click on the grid icon(<i class=\"fas fa-th-large\"></i>) to show extra tabs.\n* go to tab \"Remote Page\", click on the \"Fetch List\" button to refresh article list, then click on the dropdown icon to select \"content/_index.md\". This is the data for the home page.\n* click on the \"Load Remote Page\" button to load the home page of this theme.\n* if you can't see the article list, double check the Remote Setting tab of site setting, and make sure the data repo owner and name are properly filled in. "
  intro = " "
  is_global = false
  title = "Loading Home Page of Theme"

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "home"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "sgnzms1dc"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* hover on the left edge of the screen to show the vertical toolbar, click on the globe icon to show site setting window.\n* go to tab \"Github\", and fill in the name of your Github organization and repository. \n* Click on the \"Fetch List\" button to refresh image list, then click on the dropdown icon to select your logo.\n* by default the images are fetched from the folder \"images\". If you have uploaded your logo to a subfolder, you can fill in the full path of the subfolder, for example \"images/logos\" to list images from the subfolder. When you have selected a logo, you can reset the image folder to \"images\", so as to select images from that folder while you edit a page.\n* if you can't see the file list, verify that repo owner and name are properly filled in above. \n* if you can see the file name but can't see images in the dropdown list, verify that your website address is properly filled in the \"Current\" tab of site setting."
  intro = " "
  is_global = false
  title = "Selecting Uploaded Logo"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "search-plus"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "srizhnebv"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* images are available in some sections. \n* you can click the cog icon (<i class=\"fas fa-cog\"></i>) on the horizontal toolbar to show the section option window, and select images in the following tabs: highlight image, background image, and  base image. \n* images are rendered in layers on screen. The highlight image is closer to you, and the base image is away from you.\n* the image location is set in \"Github\" tab of site settings. you can click on the Fetch List button to update image list after changing image directory.\n* if you know the full address of the image, you can click on any image in edit mode, and paste the image url in the small popup window. "
  intro = " "
  is_global = false
  title = "Selecting Uploaded Image in Page Builder"

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "home"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "svow4nan6"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* click around and make changes as you wish. Your changes are saved in the browser database automatically.\n* select different images. If you can't find any image, check the site settings and make sure the names of your organization and repository are correct.\n* edit menu links and sections. You can specify different source for the embed map and video by toggling on the app, and click on the cog icon (<i class=\"fas fa-cog\"></i>) to open the options window. Go to Iframe tab and embed a new resource, for example a calendar.\n"
  intro = " "
  is_global = false
  title = "Editing Page"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "edit"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
data = ""
data_key = "finding_toolbar"
id = "sagadno57"
is_global = true
partial = "goandtalk/slides/collection-big-icon-mono"

[[gmgt_section]]
id = "s7qpd0kyh"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* hover on the left edge of the screen to show the vertical toolbar, click on the file icon(<i class=\"fas fa-file-alt\"></i>) to show page setting window, click on the grid icon(<i class=\"fas fa-th-large\"></i>) to show extra tabs.\n* go to tab \"Remote Page\", click on the dropdown icon to select \"content/about.md\". This is the data for the about page.\n* click on the \"Load Remote Page\" button to load the about page of this theme.\n* edit this page as you wish. "
  intro = " "
  is_global = false
  title = "Loading About Page"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "globe-asia"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "samy7zwd4"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* hover on the left edge of the screen to show the toolbar\n* click on file icon (<i class=\"fas fa-file-alt\"></i>) to show the page setting options\n* click on the grid icon (<i class=\"fas fa-th-large\"></i>) to show extra tabs. \n* click on tab \"Export Webpage\", and select \"web\" for Webpage Link Format.\n* copy the content of the web page, and paste it to the file index.html under the github repository you have just created. \n* alternatively you may click on the download button at the bottom of the form, save the web page as index.html to your computer, then upload the file and replace the file in your Github repository."
  intro = " "
  is_global = false
  title = "Exporting a Web Page for Hosting with Github Pages"

    [gmgt_section.data.appearance]
    slide_animation = "fadeIn"
    section_background = "bg-transparent"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "file-export"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 30.0

[[gmgt_section]]
id = "scby7eq2i"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* hover on the left edge of the screen to show the toolbar\n* click on file icon (<i class=\"fas fa-file-alt\"></i>) to show the page setting options\n* click on the grid icon (<i class=\"fas fa-th-large\"></i>) to show extra tabs. \n* click on tab \"Export Webpage\", and select \"web\" for Webpage Link Format.\n* copy the content of the web page, and paste it to the file index.html under the __\"about\"__ folder in the Github repository you have just created. \n* alternatively you may click on the download button at the bottom of the form, save the web page as index.html to your computer, then upload the file and replace the file in \"about\" folder."
  intro = " "
  is_global = false
  title = "Exporting About Page for Hosting with Github Pages"

    [gmgt_section.data.appearance]
    slide_animation = "fadeIn"
    section_background = "bg-white-90"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "file-export"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 30.0

[[gmgt_section]]
id = "sx97qa9b6"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* Wait a few seconds and visit your website at [orgname].github.io. Please replace [orgname] with the actual name of the organization you have created.\n* You should be able to see the changes you have made to the home page.\n* Github Pages support custom domain name. If you have your a domain name, you may update the DNS record to point to the [orgname].github.io address. For details please refer to Github Pages documentation."
  intro = " "
  is_global = false
  title = "Visiting Your Website"

    [gmgt_section.data.appearance]
    slide_animation = "fadeIn"
    section_background = "bg-transparent"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "laptop"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 30.0

[[gmgt_section]]
id = "cce58"
partial = "goandtalk/slides/big-bold-quote"

  [gmgt_section.data]
  content = "I know code and web technology. I have used a few page builders and editors. Go and Talk has helped me to create and format content at a speed I could never achieve with other tools, without touching code again. That's why we have built this tool, for designers and content creators. I love it, and I believe you will find it helpful too.\n"
  description = ""
  intro = "What People Say About It"
  is_global = false
  reviewer = "hopeful2"
  role = "Fullstack developer, lead developer of Go and Talk"
  title = "Love It"

    [gmgt_section.data.appearance]
    animation = "fadeIn"
    icon_color = "gold"
    section_background = "bg-accent-color-light"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    mini_icon = "download"

[[gmgt_section]]
id = "7ea43"
partial = "goandtalk/content/text-block"

  [gmgt_section.data]
  card_font_size = 4.0
  card_font_weight = "4"
  card_overlay = 0.0
  card_width = 100.0
  embed_aspect_ratio = "16x9"
  height_reference = "h"
  image_br = "br0"
  image_column_width = 100.0
  image_height = 100.0
  image_layer = "absolute"
  image_opacity = 100.0
  image_order = "even-order-1-ns"
  image_under_text = false
  object_fit_class = "of-scale-down"
  quote_display = "dn"
  title_align = "tc"
  title_font_size = "2"
  title_font_weight = "7"
  title_ph = "0"
  title_pv = "3"
  title_transform = "ttc"
  intro = "From A to Z"
  title = "Building a Marketing Website"
  content = "Go and Talk page builder is a lightweight web design tool running in the browser. It empowers designers and marketers to create presentable pages quickly without coding. It is optimized for running on mobile devices such as tablets. The generated web pages are responsive, lightweight and optimized for search engines.\n\nGo and Talk page builder can load theme setting and data files from remote storage, and fetch image list from your website repository. You can back up work in progress data to a data repository, continue editing from another computer, export and publish to the website repository when done.\n\nWhen your website has grown in size, Go and Talk premium theme for Hugo ( a site generator) can batch process your data files and turn these files into web pages.\n\nThis tutorial gives a step to step guide to build and host your first website. You can add unique marketing pages one by one. You can save the homepage as a new page, add and remove sections as required, and create a new page quickly.\n\nIf you already have a hosting space and domain name, you can save the web pages to your hosting space.\n\nPlease visit other tutorials and find more information on the topic of interest.\n"

    [gmgt_section.data.appearance]
    section_background = "bg-white-60"
    slide_animation = "fadeIn"

    [gmgt_section.data.base_image]
    responsive = false

    [gmgt_section.data.bg_icon]
    bg_icon_display = "dn"
    icon_mask = "square"
    inner_icon = "font"
    inner_icon_transform = "shrink-6"

    [gmgt_section.data.cta]
    align = "center"
    background_color = "bg-primary-color"
    block_button_width = 50.0
    border_color = "b--light-gray"
    border_radius = "br0"
    button_font_size = "4"
    button_text_color = "white-80"
    icon_mask = "circle"
    inner_icon = "info"
    inner_icon_transform = "shrink-4"
    mv = 3.0
    name = "Tutorials"
    ph = 3.0
    pv = 2.0
    url = "/tutorial"

    [gmgt_section.data.image]
    responsive = false

[[gmgt_section]]
data = ""
id = "gt_footer"
is_global = true
partial = "goandtalk/footer/default_footer"
+++

Go and Talk page builder is a lightweight web design tool running in the browser. It empowers designers and marketers to create presentable pages quickly without coding. It is optimized for running on mobile devices such as tablets. The generated web pages are responsive, lightweight and optimized for search engines.

Go and Talk page builder can load theme setting and data files from remote storage, and fetch image list from your website repository. You can back up work in progress data to a data repository, continue editing from another computer, export and publish to the website repository when done.

When your website has grown in size, Go and Talk premium theme for Hugo ( a site generator) can batch process your data files and turn these files into web pages.

This tutorial gives a step to step guide to build and host your first website. You can add unique marketing pages one by one. You can save the homepage as a new page, add and remove sections as required, and create a new page quickly.

If you already have a hosting space and domain name, you can save the web pages to your hosting space.

Please visit other tutorials and find more information on the topic of interest.
