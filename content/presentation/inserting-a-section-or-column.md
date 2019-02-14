+++
accent_color = "hsl(165,35%,55%)"
accent_color_light = "hsl(165,35%,65%)"
date = "2019-01-09T00:00:00Z"
description = "Learn how to add new sections and columns"
draft = false
#gt_page_builder = true
header_class = "bg-transparent"
icon_mask = "square"
inner_icon = "plus"
inner_icon_transform = "shrink-6"
iscjklanguage = false
lastmod = "2019-01-09T00:00:00Z"
lightness = 0.0
lightness_dark = 0.0
lightness_light = 0.0
lightness_lighter = 0.0
logo_url = "/images/logos/icon-on-dark.svg"
main_menu_align = "start"
primary_hue = 281.0
publishdate = "2019-01-09T00:00:00Z"
saturation = 0.0
skip_cover_nav = false
skip_slide_animation = false
title = "Inserting New Sections or Columns"
type = "presentation"

[[gmgt_section]]
id = "43714"
partial = "goandtalk/cover/hero-dark-background-with-text-at-center"

  [gmgt_section.data]
  card_font_size = 3.0
  card_font_weight = 1.0
  card_letter_spacing = "tracked"
  card_text_align = "tc"
  content = "with innovation."
  description = "and column"
  intro = "Adding new"
  title = "Section"
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
data = ""
data_key = "finding_toolbar"
id = "swmhqhwg5"
is_global = true
partial = "goandtalk/slides/collection-big-icon-mono"

[[gmgt_section]]
data = ""
data_key = "app_status_on_off"
id = "stt0wvgr9"
is_global = true
partial = "goandtalk/slides/collection-big-icon-circle-mask"

[[gmgt_section]]
data = ""
data_key = "buttons_in_edit_mode"
id = "szk0tjih1"
is_global = true
partial = "goandtalk/slides/collection-text-custom-width"

[[gmgt_section]]
id = "s0k5wzssw"
partial = "goandtalk/slides/collection-big-icon-circle-mask"

  [gmgt_section.data]
  column_class = "w-33-l"
  content = ""
  data_fa_mask = "comment-alt"
  data_fa_transform = "up-2 shrink-10"
  description = "  "
  horizontal_position = "justify-center"
  intro = " "
  is_global = false
  resize_column = "flex-none"
  title = "Ways to Add Sections"

    [gmgt_section.data.appearance]
    card_background = "bg-light-gray"
    section_background = "bg-white-70"
    slide_animation = "fadeIn"
    text_color = "primary-color-first-letter-h3"

    [[gmgt_section.data.column]]
    description = "* replicate section data and setting\n* move it to the place you want\n* change content and customize quickly\n* follow [Copying and Mixing Readymade Blocks](/tutorial/copying-and-mixing-readymade-blocks/) to learn more on basic operations."
    icon = "clone"
    title = "Clone a Section"

    [[gmgt_section.data.column]]
    description = "* share the same data on different pages, for example a site wide call to action section.\n* make changes on one of the pages, and populate the changes on all pages"
    icon = "globe"
    title = "Insert a Global Section"

    [[gmgt_section.data.column]]
    description = "* select from a list of section template\n* minimum placeholder data\n* you can add a section after any section by clicking on the plus icon on that section.\n* the app of the newly added section is turned off by default, if you already have more than 10 apps including cover and footer.\n* you need to turn on the app and switch to editing mode to make changes."
    icon = "plus"
    title = "Adding New Section"

[[gmgt_section]]
id = "sqowvi7v4"
partial = "goandtalk/slides/collection-card"

  [gmgt_section.data]
  column_class = "w-33-l"
  content = ""
  description = "  "
  horizontal_position = "justify-center"
  images_class = "br0"
  intro = " "
  is_global = false
  resize_column = "flex-auto"
  title = "Naming Convention of Section Template"

    [gmgt_section.data.appearance]
    card_background = "hover-primary-color"
    slide_animation = "fadeIn"

    [[gmgt_section.data.column]]
    description = "* The first section with navigation links, and button to trigger presentation mode.\n* A template by the name \"default\" has navigation links only."
    title = "Cover"

    [[gmgt_section.data.column]]
    description = "* The optional content block for the page body text\n* It loads the same text from the page body. \n* it is not necessary to have more than one content block for body text."
    title = "Content"

    [[gmgt_section.data.column]]
    description = "* Footer with navigation links and copyright statement.\n* A global footer is available for centralized customization.\n"
    title = "Footer"

    [[gmgt_section.data.column]]
    description = "* sections to be added anywhere between cover and footer.\n* multiple layout options\n* collection section can have any number of items.   This section for example is a collection. \n* alternate sections have two columns. The image or icon floats to left or right for alternate effect."
    title = "Slides"

[[gmgt_section]]
id = "spkq3466s"
partial = "goandtalk/slides/alternate-two-columns-text-and-image"

  [gmgt_section.data]
  card_background = "bg-black-20"
  card_font_size = 4.0
  card_font_weight = "4"
  card_overlay = 0.0
  card_width = 100.0
  content = "* in this exercise we will insert a new section below this section. It  involves scrolling up to this section for instructions, and operate on the new section.  \n* find the toolbar of this section, and click on the plus icon. You should see a popup window with dropdown lists.\n* click on the dropdown icon for the list labelled \"Select Blank Template\", and choose a template. The window will scroll to the new section added.\n* Click on the toggle icon to turn on the app for the new section.\n* Click on Edit button on the toolbar of the new section to switch to editing mode. \n* You may see different toolbars or options depending on which section template you have chosen.\n* Click around, make some changes, and optionally save the changes.\n* Click on Editing button to switch off editing mode and preview your new section.\n* Optionally delete the section and try a new section."
  cta_display = "dn"
  height_reference = "h"
  image_align_h = "left--35-ns"
  image_align_v_flex = "items-center"
  image_br = "br-100"
  image_column_width = 30.0
  image_height = 50.0
  image_layer = "static"
  image_opacity = 100.0
  image_order = "odd-order-1-ns"
  image_source = "https://source.unsplash.com/K4vHlGVX0Hs/480x640"
  image_under_text = false
  intro = "Exercise"
  is_global = false
  object_fit_class = "of-cover"
  quote_display = "dn"
  section_max_width = "mw8"
  text_column_class = "w-70-ns"
  title = "Insert a New Section From Template"
  title_align = "tc"
  title_font_size = "2"
  title_font_weight = "7"
  title_ph = "0"
  title_pv = "3"
  title_transform = "ttc"

    [gmgt_section.data.appearance]
    icon_color = "gold"
    section_background = "bg-primary-color-dark"
    slide_animation = "fadeIn"

    [gmgt_section.data.cta]
    background_color = "bg-light-gray"
    block_button_width = 50.0
    border_color = "b--light-gray"
    border_radius = "br0"
    button_font_size = "4"
    button_text_color = "mid-gray"
    icon_mask = "circle"
    inner_icon = "info"
    inner_icon_transform = "shrink-4"
    mv = 3.0
    name = " Quick Start "
    ph = 3.0
    pv = 2.0
    url = "#"
    align = "center"

    [gmgt_section.data.image]
    responsive = false

    [gmgt_section.data.base_image]
    responsive = false

    [gmgt_section.data.bg_icon]
    icon_mask = "square"
    inner_icon = "font"
    inner_icon_transform = "shrink-6"
    bg_icon_display = "dn"

[[gmgt_section]]
id = "s62eskw86"
partial = "goandtalk/slides/collection-card"

  [gmgt_section.data]
  column_class = "w-25-l"
  content = ""
  description = "  "
  horizontal_position = "justify-center"
  images_class = "br0"
  intro = "Exercise for Collection"
  is_global = false
  resize_column = "flex-auto"
  title = "Adding, Ordering and Deleting Columns"

    [gmgt_section.data.appearance]
    card_background = "hover-primary-color"
    slide_animation = "fadeIn"

    [[gmgt_section.data.column]]
    description = "* find the toolbar of this section. \n* click on the toggle icon to turn the section app on.\n* click on Edit button to switch to editing mode.\n"
    title = "Preparation"

    [[gmgt_section.data.column]]
    description = "* click on the green plus  button to add a new column\n* hover on the new section to show a small toolbar at the top\n* drag the bar icon to change the order\n"
    title = "Add and Reorder"

    [[gmgt_section.data.column]]
    description = "* hover on a new column to show a mini toolbar\n* click on the trash icon to delete the column\n* click Undo to cancel, or OK button to confirm deleting."
    title = "Delete"

    [[gmgt_section.data.column]]
    description = "* click on the cog settings icon on the section toolbar\n* go to Layout tab, and change the number of columns allowed per row.\n* change the resizing and position options and see the new layout.\n"
    title = "Layout"

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
    icon_color = "gold"
    section_background = "bg-primary-color-light"
    slide_animation = "fadeIn"
    text_color = "gold"

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
  title = "Inserting New Sections or Columns"
  content = "Go and Talk is a lightweight web design tool running in the browser. It empowers designers and marketers to create presentable pages quickly without coding. It is optimized for mobile devices.\n\nThis tutorial provides step to step guide on how to insert new sections and columns.\n\nIf you have completed all the exercises in this tutorial, you should have made the following achievements and know the following:\n\n* where to find section toolbar and global toolbar.\n* how to turn on a section app\n* how to switch editing mode on an off\n* how to insert new sections from a template\n* how to add, reorder, delete columns in a collection.\n\nWell done. You will acquire new skills and explore new features in other tutorials. Stay tuned.\n"

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

This tutorial provides step to step guide on how to insert new sections and columns.

If you have completed all the exercises in this tutorial, you should have made the following achievements and know the following:

* where to find section toolbar and global toolbar.
* how to turn on a section app
* how to switch editing mode on an off
* how to insert new sections from a template
* how to add, reorder, delete columns in a collection.

Well done. You will acquire new skills and explore new features in other tutorials. Stay tuned.
