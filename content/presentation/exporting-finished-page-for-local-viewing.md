+++
accent_color = "hsl(350,35%,45%)"
accent_color_light = "hsl(350,35%,55%)"
date = "2019-01-09T00:00:00Z"
description = "Learn how to export page for viewing on your computer"
draft = false

header_class = "bg-transparent"
iscjklanguage = false
lastmod = "2019-01-09T00:00:00Z"
lightness = 0.0
lightness_dark = 0.0
lightness_light = 0.0
lightness_lighter = 0.0
logo_url = "/images/logos/icon-on-dark.svg"
main_menu_align = "start"
primary_hue = 221.0
publishdate = "2019-01-09T00:00:00Z"
saturation = 48.0
skip_cover_nav = false
skip_slide_animation = false
title = "Exporting Finished Page for Local Viewing"
type = "presentation"
icon_mask = "network-wired"
inner_icon = "ban"
inner_icon_transform = "shrink-6"

[[gmgt_section]]
id = "43714"
partial = "goandtalk/cover/hero-dark-background-with-text-at-center"

  [gmgt_section.data]
  card_font_size = 3.0
  card_font_weight = 1.0
  card_letter_spacing = "tracked"
  card_text_align = "tc"
  content = "with innovation."
  description = "with local browsing"
  intro = "think big"
  title = "Stay Local"
  title_align = "tc"
  title_class = "gold"
  title_color = "gold"
  title_font_family = "baskerville"
  title_font_size = -5.0
  title_font_weight = 4.0
  title_letter_spacing = "tracked"

    [gmgt_section.data.appearance]
    section_background = "bg-primary-color-dark"
    trigger_class = "slide-trigger"

    [gmgt_section.data.cta]
    background_color = "bg-black-20"
    button_text_color = "white-90"
    name = "Play Slides ->"
    pv = 1.0
    title = "view page as slides. "
    url = "#"

    [gmgt_section.data.cta2]
    name = " Learn More "
    url = "/tutorial"

    [gmgt_section.data.image]
    animation = "slowUp"
    flow_end = true
    overlay_background = "bg-black-70"
    responsive = false
    src = "https://source.unsplash.com/sK1hW5knKkw/1536x864"

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
id = "stq3uazw8"
partial = "goandtalk/slides/collection-big-icon-mono"
is_global = true
data_key = "finding_toolbar"

[[gmgt_section]]
id = "s2iid03or"
partial = "goandtalk/slides/collection-big-icon-circle-mask"
is_global = true
data_key = "data_browser_database"

[[gmgt_section]]
id = "sb1qjozn9"
partial = "goandtalk/slides/collection-big-icon-circle-mask"

  [gmgt_section.data]
  title = "Benefits of Exporting to Local File"
  content = ""
  description = "Optional. You can view pages without exporting."
  column_class = "w-25-l"
  resize_column = "flex-auto"
  horizontal_position = "justify-center"
  data_fa_mask = "circle"
  data_fa_transform = "shrink-8"
  is_global = false
  intro = " "

    [[gmgt_section.data.column]]
    icon = "hourglass-end"
    title = "Speed"
    description = "* page loads faster\n* normal web page without editor\n* can have more sections on the same page if you need to."

    [[gmgt_section.data.column]]
    icon = "images"
    title = "Link to Local Images"
    description = "* can link to images on your computer\n* internal use\n"

    [[gmgt_section.data.column]]
    icon = "compact-disc"
    title = "Portable"
    description = "* self-sufficient package\n* compressed and sent to another user for browsing without server"

    [gmgt_section.data.appearance]
    section_background = "bg-white-70"
    card_background = "bg-light-gray"
    icon_color = "black-20"
    slide_animation = "fadeIn"
    text_color = "primary-color-first-letter-h3"

[[gmgt_section]]
id = "spwek2n5n"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  title = "Preparation for True Local Presentation"
  content = "* Your project folder should have subfolders js, css, images, and should have the static  files (JavaScript, CSS) to view the page locally without internet connection.\n* You can download [static files](https://github.com/goandtalk/golden/archive/master.zip) and unzip to a folder on your computer.\n* The local images used in your presentation should be saved under images folder.\n* The images linked from a server will only work with internet connection. You can open the exported file with internet connection, and then save the page as a complete web page. The browser will download the images and save all the resources required under a subfolder."
  intro = " "
  is_global = false

    [gmgt_section.data.icons]
    mini_icon = "images"
    mini_icon_color = "white"
    outer_icon = "folder"
    width = 20.0

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

[[gmgt_section]]
id = "b94f8"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* Find the global toolbar by hovering on the left edge of the screen. If you are using a mobile device, you may need to tap on the left edge to show the toolbar.\n* Click on the page setting (file) button to show the page setting options.\n* Now click on the grid icon at the top of the option window. You will see a new set of tabs. \n* Click on Export Webpage tab. You should see a big button (Download Webpage)  at the bottom of the form. Click the button and choose where to save your file. \n* Your project folder should have folders js, css, images and have the resources required to view the page.\n* If the exported file is saved under a subfolder of the project folder, you can specify the nesting level before export. For example, if the file will be saved under talk/2019/new-idea.html, you can specify a nesting level of 2 for the links to work properly.\n* The download button is not available on mobile devices. If you are using a mobile device, you can copy and paste the page code to another app, or paste to an online service.\n"
  description = ""
  intro = "Exercise"
  is_global = false
  title = "Export to Local File"

    [gmgt_section.data.appearance]
    animation = "fadeIn"
    icon_color = "primary-color"
    section_background = "bg-primary-color-light"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    mini_icon = "file-download"
    mini_icon_color = "white"
    outer_icon = "circle"
    width = 20.0

[[gmgt_section]]
id = "c9206"
partial = "goandtalk/slides/big-bold-quote"

  [gmgt_section.data]
  content = "I created stunning landing pages with Go and Talk, without writing any code. This is simply amazing!"
  description = ""
  intro = "What People Say About It"
  is_global = false
  reviewer = "Tina"
  role = "Web Designer"
  title = "Simply Amazing!"

    [gmgt_section.data.appearance]
    animation = "fadeIn"
    section_background = "bg-accent-color-light"
    slide_animation = "fadeIn"
    text_color = "gold"
    icon_color = "gold"

    [gmgt_section.data.icons]
    mini_icon = "download"

[[gmgt_section]]
id = "7b698"
partial = "goandtalk/content/text-block"

  [gmgt_section.data]
  card_font_size = "5"
  card_font_weight = "4"
  card_overlay = 0.0
  card_width = 100.0
  height_reference = "h"
  image_br = "br0"
  image_column_width = 100.0
  image_height = 100.0
  image_layer = "absolute"
  image_opacity = 100.0
  image_order = "even-order-1-ns"
  image_under_text = false
  intro = "Creating More With Less"
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

    [gmgt_section.data.cta]
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
    name = "Back to Tutorials"
    ph = 3.0
    pv = 2.0
    url = "/tutorial/"

    [gmgt_section.data.image]
    responsive = false

[[gmgt_section]]
data = ""
id = "gt_footer"
is_global = true
partial = "goandtalk/footer/default_footer"
+++

Go and Talk is a lightweight web design tool running in the browser. It empowers designers and marketers to create presentable pages quickly without coding. It is optimized for mobile devices.

This tutorial provides step to step guide on how to export page for local browsing.

If you have completed all the exercises in this tutorial, you should have made the following achievements:

* know where to find section toolbar and global toolbar.
* understand the folder structure of a web page for local presentation
* know how to export webpage

Well done. You will acquire new skills and explore new features in other tutorials. Stay tuned.
