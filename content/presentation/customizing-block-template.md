+++
date = "2019-01-09T00:00:00Z"
description = "Use custom block template to render sections."
draft = false
#gt_page_builder = true
header_class = "bg-transparent"
icon_mask = "square"
inner_icon = "map"
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
title = "Using Custom Block Template"
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
  description = "to render section content"
  intro = "using Custom"
  title = "Block Template"
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
    inner_icon = "map"
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

[[gmgt_section]]
id = "sc0qh5p8t"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* designers and developers, and advanced users\n* some knowledge of HTML, CSS and JavaScript\n* comfortable with the developer console of the browser. "
  intro = " "
  is_global = false
  title = "Target Audience of This Tutorial"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "code"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 30.0

[[gmgt_section]]
id = "s044rhebx"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* define custom CSS classes to style existing elements\n* use custom export template to load libraries selectively, and insert elements dynamically using JavaScript\n* ask us whether your goal can be achieved by modifying the existing block template. we may make it happen."
  intro = " "
  is_global = false
  title = "Alternatives to Custom Block Template"

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "magic"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 30.0

[[gmgt_section]]
id = "sojc50t9h"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* a block is a section of the page, and is an app in edit mode\n* the content of blocks are stored as meta data of the page\n* block templates (also known as partials) are loaded as JavaScript strings and compiled to functions dynamically\n* in edit mode, the page is rendered using the functions and data stored in the browser\n* the same functions are used to render blocks without editor when the page is exported\n* common blocks: header block, content block, and footer block\n* arbitrary blocks between header and footer: collection blocks, alternate two column blocks, single column blocks\n* each template or partial has a unique name with name space, for example goandtalk/cover/default\n* each block has a unique id to track its position on the page\n* cloned block will have the same content but a different id"
  intro = " "
  is_global = false
  title = "Block Template"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "shapes"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "smg7zd2v1"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* the section element, with app settings. each section is a Mavo app. For details of using Mavo app, please refer to the [official Mavo documentation](https://mavo.io/docs/). \n* the visible part of the section\n* embedded editor form and buttons in some sections\n* section settings window, off canvas by default\n* section toolbar with buttons to toggle Mavo app on and off, switch edit mode and perform other tasks."
  intro = " "
  is_global = false
  title = "Structure of a Block"

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "tape"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 30.0

[[gmgt_section]]
id = "syg2cglze"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* [doT template engine documentation and examples](http://olado.github.io/doT/index.html)\n* custom template delimiters and variable names\n* variable for context data: it\n* variable for context options: o"
  intro = " "
  is_global = false
  title = "Template Engine - doT"

    [gmgt_section.data.appearance]
    section_background = "bg-white-60"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "memory"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 30.0

[[gmgt_section]]
id = "sqdubww5f"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* hover on the left edge of the screen to show the vertical toolbar\n* click on the globe icon to show site settings window\n* go to tab \"New Block\", enter a unique name for the new block, and paste your block template code in the text area. \n* click on \"Save New Block\" button to save the new block in site settings.\n* the saved template is available for further editing in \"Edit Block\" tab.\n"
  intro = " "
  is_global = false
  title = "Creating a Custom Block Template"

    [gmgt_section.data.appearance]
    section_background = "bg-white-90"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "box"
    mini_icon_color = "white"
    outer_icon = "coffee"
    width = 20.0

[[gmgt_section]]
id = "sxva4e7bg"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* once saved, your custom block template will be available in the dropdown list when you add a new section\n* you can add a new section by selecting the custom block template\n* the custom block template will be compiled into a function to render data"
  intro = " "
  is_global = false
  title = "Using Custom Block Template"

    [gmgt_section.data.appearance]
    section_background = "bg-transparent"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-10 up-2 left-1"
    mini_icon = "drafting-compass"
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

In edit mode, Go and Talk page builder uses a template engine called doT to render blocks(sections) using data stored in browser. Each block is a Mavo app rendering user input dynamically. When the page is done, the same templates are used to render the sections without editor. The exported page is slim and loads faster.

Go and Talk page builder supports custom block template. You can define custom block template in site setting, insert new blocks and manage blocks in the same way.

Before creating your own custom block template, you may want to explore alternative solutions, such as styling existing elements with CSS, or inserting elements dynamically using JavaScript. The templates of Go and Talk page builder are generated automatically with Hugo. You may check with us whether your goal can be achieved by modifying the existing block templates. This way, you will be able to use server side rendering when you need it.
