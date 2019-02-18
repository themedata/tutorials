+++
date = "2019-01-09T00:00:00Z"
description = "Learn how to create a custom theme and explore the options available."
draft = false
gt_page_builder = true
header_class = "bg-transparent"
icon_mask = "square"
inner_icon = "shapes"
inner_icon_transform = "shrink-6"
iscjklanguage = false
lastmod = "2019-01-09T00:00:00Z"
lightness = 0.0
lightness_dark = 0.0
lightness_light = 0.0
lightness_lighter = 0.0
logo_url = "/images/logos/icon-on-dark.svg"
main_menu_align = "start"
primary_hue = 331.0
publishdate = "2019-01-09T00:00:00Z"
saturation = 42.0
skip_cover_nav = false
skip_slide_animation = false
title = "Designing a Custom Theme"
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
  description = "showcase your creativity"
  intro = "designing Custom"
  title = "Theme"
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
    inner_icon = "font"
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
id = "sc0qh5p8t"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* creative and entrepreneurial\n* keen to explore and learn\n* already familiar with Go and Talk page builder. If you are new, the other tutorials will help you to get up and running quickly.\n* willing to create and share themes with others\n* some knowledge of HTML and CSS, or the courage to read the documentation and explore web design"
  intro = " "
  is_global = false
  title = "Target Audience of This Tutorial"

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "book-reader"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 30.0

[[gmgt_section]]
id = "szw3vd7fg"
partial = "goandtalk/slides/collection-big-icon-circle-mask"

  [gmgt_section.data]
  title = "Themes vs Templates"
  content = ""
  intro = "Clarification of Terms in Tutorials"
  description = "Present content with a theme, and  deliver content with templates."
  column_class = "w-50-l"
  resize_column = "flex-auto"
  horizontal_position = "justify-center"
  data_fa_mask = "circle"
  data_fa_transform = "shrink-8"
  is_global = false

    [[gmgt_section.data.column]]
    icon = "paint-brush"
    title = "Themes for Designing"
    description = "* themes refer to the artistic arrangement of contents and space for particular use cases or industry, for example, a theme for coffee shop\n* all themes share the same basic templates and data structure, so that website owners can switch theme to change the website appearance"

    [[gmgt_section.data.column]]
    icon = "code"
    title = "Templates for Programming"
    description = "* templates refer to block(section) templates and page export templates\n* templates are compiled into functions to generate HTML code for the webpage\n* theme data is rendered with templates\n* templates contain programming logic, and are populated with data"

    [gmgt_section.data.appearance]
    section_background = "bg-white-70"
    card_background = "bg-light-gray"
    slide_animation = "fadeIn"
    text_color = "primary-color-first-letter-h3"

[[gmgt_section]]
id = "sojc50t9h"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* a demo site featuring the theme\n  - for example a demo site hosting with Github Pages\n  - an organization on Github to collaborate with others, using the theme name\n  - a repository named with pattern [theme-name].github.io.  Github Pages automatically enables hosting for a repository named this way. please replace [theme-name] with the actual theme name.\n  - placeholder images\n* a separate repository for theme data\n  - site settings in config.toml file of the theme\n  - sample pages in content folder\n  - see [Toffee and Coffee theme](https://github.com/themedata/toffee-and-coffee)  as a reference \n"
  intro = " "
  is_global = false
  title = "Theme Structure"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "sitemap"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "smg7zd2v1"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* think of a theme name, and create an organization on Github.com with this name\n* create a repository for theme demo site under this organization, and name it [theme-name].github.io\n* [create a new site](/edit/) with Go and Talk page builder\n* assign a unique theme id as site id. this is especially useful if you will create more than one theme.\n* create sample pages as usual, use neutral images and language for placeholder\n* create another repository on Github.com for theme data\n  - export site setting data and save as config.toml file \n  - export data of sample pages and save under content folder \n* export sample pages and publish to the demo site, and let the world know"
  intro = "An overview of"
  is_global = false
  title = "Creating a New Theme"

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "shapes"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "sd2ey2o7h"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* a repository for web pages, images, CSS and JavaScript files to show your work\n* the theme name is also the organization name\n  - organization name on Github.com must be unique. If it is not available, you may try names with more words separated with a dash, for example toffee-and-coffee.\n* create a repository for demo site, under this organization\n  - fork from this repository [Golden](https://github.com/goandtalk/golden). It has all the folder structure and static files\n  - rename the repository to [theme-name].github.io\n  - select a license for your work\n* give meaningful names to images so you may search and select in the media library when you edit pages\n* make sure the images are resized properly\n* upload images to the repository"
  intro = " "
  is_global = false
  title = "Repository for Theme Demo"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "golf-ball"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "syx59ecgs"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* source data for backup, and further editing\n* site settings (config.toml file)\n  + theme author and license information\n  + primary color and shades, and accent colors\n  + placeholder menu items\n  + custom styles \n    - inline CSS declaration\n    - external stylesheets or custom fonts\n  + optional custom block and export templates\n* data of sample pages in content folder\n  + one file for each sample page containing meta data of sections on the page\n  + data can be exported in toml, yaml  or json format"
  intro = " "
  is_global = false
  title = "Repository for Theme Data"

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "font"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "sqdubww5f"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* assume all images on the internet are copyrighted unless explicitly stated otherwise\n* check the copyright statement before using any images. \"Free\" images may have restrictions on how the images can be used. \n* look for creative commons zero licensed images if possible. These images are copyrighted but have very few restrictions.\n* avoid images featuring products or trademarks. \n* portraits of people are subject to additional legal requirements, even if the photographer gives permission to use the image.\n* source of images [unsplash](https://unsplash.com), [pixabay](https://pixabay.com), or your favorite sources\n* you can request and link to custom resized images on Unsplash. this could be useful when you are trying out an image during design."
  intro = " "
  is_global = false
  title = "Images and Copyright"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "images"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "sxva4e7bg"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* when editing a page with the page builder, always navigate to the page by opening the file in file setting window.\n* custom navigation links on your sample page will only work on your demo site when published."
  intro = " "
  is_global = false
  title = "Navigating Sample Pages"

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "bars"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "spbmxe7fu"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/) (CC-BY-NC-4.0) license recommended\n* there are good folks out there working on noble causes for the benefits of others.  Allowing them to use your theme for free is an encouragement  and support to them. \n  - Go and Talk page builder is free for non-commercial use. They can create beautiful websites to raise awareness, get support and make positive impact. \n* you deserve to be paid by people using your theme for commercial activities. \n* fill in your website address in Theme Author tab of site setting, and your website will be included in the credit link automatically.\n* sample credit link at the bottom of the web page\n  - theme-name by theme-author, powered by goandmake.app"
  intro = " "
  is_global = false
  title = "Licensing Your Theme"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "scroll"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "sq5mqcck9"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* Go and Talk page builder is free for non-commercial use (free as in free beer). A license is required for commercial use.\n* if you volunteer to create websites for non-profit organizations, feel free to use the page builder. \n  - \"Freely you have received; freely give.\" Matthew 10:8 New International Version (NIV). \n  - you will be amazed how much faster you can create  a theme or website. Just try defining custom styles in site setting, and watching it taking effect immediately. You are applying styles on the real thing. When you are happy about the result, everything is automatically saved and ready for publishing. Simply export and upload. No more conversions or coding.\n* if you charge money from clients, you will need a license to use the page builder. In addition to the client side page builder, thanks to the power of Hugo, Go and Talk premium theme for Hugo makes it possible to batch process data files, and help you to be more productive. Please contact us for details."
  intro = " "
  is_global = false
  title = "Creating Websites for Clients with Go and Talk Page Builder"

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "balance-scale"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "sg0l21cz4"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* potential benefits of selling your theme instead of providing web design service\n  - reach different market segments and geographical locations\n  - increase revenue\n  - make better use of your idle designs\n  - get leads for your professional web design service\n* benefits of bundling with Go and Talk page builder\n  -  empower beginners to use your theme. Go and Talk page builder has been built with absolute beginners in mind. The editors have been revised time and again after consulting with people who have never built a website before.\n  - add value to your theme, as it saves time for users. Editing HTML code is no fun, and is daunting to some people.\n* contact us for more details of customization and bundling."
  intro = " "
  is_global = false
  title = "Bundling with Page Builder and Selling Your Themes"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "shopping-cart"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

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

Go and Talk page builder is a lightweight web design tool running in the browser. It empowers designers and marketers to create presentable pages quickly without coding. It is tailored for running on mobile devices such as tablets. The generated web pages are responsive, lightweight and optimized for search engines.

Go and Talk page builder helps creative and entrepreneurial people to be more productive in delivering web design service, or providing a user friendly theme product. When the data files grow in volume, Go and Talk premium theme for Hugo can turn texts into beautiful web pages in batch.

Go and Talk page builder supports inline style declaration and external CSS files. The inline styles written in the site settings window take effect immediately, and are saved automatically. Professional designers may find this feature useful in creating custom animations as you can watch the animation taking place while you change the parameters. When you are happy about the result, the parameters are already included in the site setting ready for production.

The external CSS URLs can load custom CSS files, external CSS library, or custom fonts such as Google fonts.  

Go and Talk makes it much easier and faster to design a custom theme. Each theme may have a demo site to show sample pages, and a repository for source data. This tutorial shows the steps to create a repository for hosting demo site with Github Pages.

If you are new to Github Pages , you may create an organization there, fork a repository from [Toffee and Coffee theme](https://github.com/toffee-and-coffee/toffee-and-coffee.github.io), rename the repository and get familiar with the hosting process.  
