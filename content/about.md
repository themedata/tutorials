+++
accent_color = "hsl(350,35%,45%)"
accent_color_light = "hsl(350,35%,55%)"
date = "2019-01-09T00:00:00Z"
description = "An integrated solution of web publishing"
draft = false
#gt_page_builder = true
header_class = "bg-transparent"
iscjklanguage = false
lastmod = "2019-01-09T00:00:00Z"
lightness = 0.0
lightness_dark = 0.0
lightness_light = 0.0
lightness_lighter = 0.0
logo_url = "/images/logos/icon-on-dark.svg"
main_menu_align = "start"
primary_hue = 183.0
publishdate = "2019-01-09T00:00:00Z"
saturation = 38.0
skip_cover_nav = false
skip_slide_animation = false
title = "About Go and Talk"
type = "presentation"

[[gmgt_section]]
id = "snpjqn9ud"
partial = "goandtalk/cover/default"

  [gmgt_section.data]
  title = "New Section"
  content = ""

    [gmgt_section.data.appearance]
    section_background = "bg-primary-color"
    trigger_class = "slide-trigger"

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
id = "7b698"
partial = "goandtalk/content/text-block"

  [gmgt_section.data]
  card_font_size = 4.0
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

Go and Talk is a suite of templates and applications for web publishing. It consists of

* prebuilt template blocks,
* a page builder to customize the templates, and
* a premium Hugo theme for server side rendering.

## Go and Talk Page Builder

Go and Talk page builder is a lightweight web design app running in the browser. It empowers designers and marketers to create presentable web pages quickly without coding. It is optimized for running on mobile devices such as tablets. The generated pages are responsive.

Some of the key features that set it apart.

* run without installation.
* store data locally in the browser.
* work on its own without a database on server.
* export and import text in three formats (TOML, YAML, JSON),
* export web page for hosting or presentation.
* support global data and global sections shared by all pages
* manage data of multiple sites, each site residing in its own local database in the browser.

Go and Talk page builder uses the same templates for editing and export. It applies or removes predefined CSS classes to achieve the visual effect. You will get what you see when you preview the page in editor. The exported page is static html code and renders faster.

Go and Talk page builder uses features of modern browsers. It runs on latest version of Chrome, Firefox and Safari.

Due to the security policy of browsers, Go and Talk page builder needs to be loaded from a web server. 

## Go and Talk Hugo Theme

Go and Talk Hugo Theme is a premium theme to use with Hugo, a static website generator. It can process data in volume from the page builder together with other content files to update websites, thanks to the power of Hugo.

Go and Talk Hugo Theme and page builder share the same template, and render the same HTML code. In fact the Hugo theme checks a flag to generate normal webpage for production, or template string for the page builder. This ensures consistency of rendered pages.

Go and Talk page builder shines when used together with the Hugo theme. Together with Hugo, they provide a friendly user interface to edit structured data with instant feedback, and a powerful backend for high volume mass production.

## License

The components of Go and Talk are licensed separately.

### Go and Talk Templates
The templates are licensed under Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

A commercial license is available.

### Go and Talk Page Builder
Go and Talk page builder is free for non-commercial use.

A license is required for commercial use or redistribution.

### Go and Talk Hugo Theme
A license is required for commercial use.
