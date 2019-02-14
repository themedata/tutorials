+++
accent_color = "hsl(350,35%,45%)"
accent_color_light = "hsl(350,35%,55%)"
date = "2019-01-09T00:00:00Z"
description = "Learn how to customize section layout.."
draft = false
gt_page_builder = true
header_class = "bg-transparent"
inner_icon = "address-card"
iscjklanguage = false
lastmod = "2019-01-09T00:00:00Z"
lightness = 0.0
lightness_dark = 0.0
lightness_light = 0.0
lightness_lighter = 0.0
logo_url = "/images/logos/icon-on-dark.svg"
main_menu_align = "start"
primary_hue = 67.0
publishdate = "2019-01-09T00:00:00Z"
saturation = 0.0
skip_cover_nav = false
skip_slide_animation = false
title = "Editing Text and Image Layers"
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
  description = "with no hassle"
  intro = "beside or beneath?"
  title = "Free Choices"
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

[[gmgt_section]]
id = "b9412"
partial = "goandtalk/slides/collection-big-icon-mono"

  [gmgt_section.data]
  column_class = "w-25-l"
  description = "Hover or tap to show the toolbars."
  horizontal_position = "justify-center"
  intro = "At Top and Left, Hidden Initially"
  is_global = false
  resize_column = "flex-auto"
  title = "Toolbars"

    [gmgt_section.data.appearance]
    animation = "fadeIn"
    card_background = "hover-primary-color"
    icon_color = "black-20"
    slide_animation = "fadeIn"
    text_color = "primary-color-first-letter-h3"

    [[gmgt_section.data.column]]
    description = "* At the top of each section.\n* Manage current section. \n* Apply to current section.\n* Turn app on and off.\n* Toggle edit mode.\n* Toggle global toolbar."
    icon = "grip-horizontal"
    title = "Application Toolbar"

    [[gmgt_section.data.column]]
    description = "* At the left side of the screen.\n* Manage global settings. \n* Apply to the current page, or all pages.\n* Hide all section tools.\n* Hide itself."
    icon = "grip-vertical"
    title = "Global Toolbar"

    [[gmgt_section.data.column]]
    description = "* Available in some sections. \n* Toggle on to edit.\n* Toggle off when done."
    icon = "keyboard"
    title = "Context Toolbar"

[[gmgt_section]]
id = "s7gjdwy1e"
partial = "goandtalk/slides/collection-big-icon-circle-mask"

  [gmgt_section.data]
  column_class = "w-25-l"
  data_fa_mask = "circle"
  data_fa_transform = "shrink-8"
  description = "  "
  horizontal_position = "justify-center"
  intro = "Toggle On Demand"
  is_global = false
  resize_column = "flex-auto"
  title = "The State of Section Application"

    [gmgt_section.data.appearance]
    card_background = "bg-light-gray"
    icon_color = "black-10"
    section_background = "bg-white-70"
    slide_animation = "fadeIn"
    text_color = "primary-color-first-letter-h3"

    [[gmgt_section.data.column]]
    description = "* The Application is currently off.\n* Click this button to turn it on.\n* Not available for apps that are always on."
    icon = "toggle-off"
    title = "Off"

    [[gmgt_section.data.column]]
    description = "* The application is on.\n* Click this button to turn if off.\n* Not available for apps that are always on."
    icon = "power-off"
    title = "On"

[[gmgt_section]]
id = "slgyvxlka"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  title = "Managing Toolbars"
  content = "*  Hover on the edge of a section to find the section toolbar. You may need to tap to show the toolbar on a mobile device.\n* Hover on the left edge of the screen to  find the global toolbar. \n* Click on the arrow sign < to hide the global toolbar. \n* On the section toolbar, click on the vertical toolbar icon to show the global toolbar again. Make sure you click it ONCE. This button toggles global toolbar, and the number of clicks will decide whether to show or hide the global toolbar.\n* Verify the global toolbar is visible now. \n* Now you know how to hide or show global toolbar."
  intro = "Exercise"
  is_global = false

    [gmgt_section.data.icons]
    mini_icon = "grip-horizontal"
    mini_icon_color = "white"
    outer_icon = "circle"
    width = 20.0

    [gmgt_section.data.appearance]
    section_background = "bg-primary-color"
    slide_animation = "fadeIn"

[[gmgt_section]]
id = "sbqn4rzl6"
partial = "goandtalk/slides/collection-text-custom-width"

  [gmgt_section.data]
  column_class = "w-50-l"
  description = "  "
  horizontal_position = "justify-center"
  images_class = "br0"
  intro = "Buttons and States"
  is_global = false
  resize_column = "flex-auto"
  title = "Buttons Available When the Section App is On"

    [gmgt_section.data.appearance]
    card_background = "hover-primary-color"
    slide_animation = "fadeIn"

    [[gmgt_section.data.column]]
    column_width = 20.0
    description = "* The app is in standby mode. \n* Click on this button to switch to editing mode. \n* The section works like a normal web page.\n* Click on a link will take you to a new resource."
    title = "Edit"

    [[gmgt_section.data.column]]
    column_width = 20.0
    description = "* The app is in editing mode.\n* Click on this button to exit editing.\n* Click on text or image to start editing.\n* The section will behave differently.\n* Click on a link will bring up an editor."
    title = "Editing"

    [[gmgt_section.data.column]]
    column_width = 20.0
    description = "* Click this button to save the current PAGE.\n* Click on \"Save\" button on any section will save the whole page.\n* This button works in standby and editing mode."
    title = "Save"

    [[gmgt_section.data.column]]
    column_width = 20.0
    description = "* Toggles more options of the current section.\n* This button works in standby and editing mode."
    title = "Settings"

[[gmgt_section]]
id = "su6jafft0"
partial = "goandtalk/slides/alternate-two-columns-text-and-image"

  [gmgt_section.data]
  title = "Images at Side"
  content = "* Hide the global toolbar to make room for this exercise.\n* Find the toolbar of this section.\n* Click on the toggle icon <i class=\"fas fa-toggle-off\"></i>  to turn this app on. \n* Click on the Edit button to switch to edit mode. You should see a context toolbar.\n* Click on the button labeled T (t for toggle) at the top corner of the section to switch to another toolbar, or hide them altogether. \n* Click on this button again to show the toolbar.\n* Drag the sliders and see how they affect the layout.\n* Click on the buttons to find out what happens. If you hover on a button, a tooltip will give some clue about itself. \n* You may need to tap a button before clicking it on a mobile device.\n* Switch off the editing mode when done."
  image_source = "https://source.unsplash.com/sK1hW5knKkw/1536x864"
  intro = "Exercise"
  image_column_width = 50.0
  image_opacity = 100.0
  card_overlay = 0.0
  card_width = 100.0
  image_height = 100.0
  text_column_class = "w-50-ns"
  image_layer = "static"
  image_under_text = false
  image_align_h = "left--25-ns"
  cta_display = "dn"
  quote_display = "dn"
  title_ph = "0"
  title_pv = "3"
  title_font_size = 2.0
  title_align = "tc"
  title_transform = "ttc"
  title_font_weight = "7"
  section_max_width = "mw-100"
  card_font_size = 4.0
  card_font_weight = "4"
  image_br = "br0"
  object_fit_class = "of-cover"
  height_reference = "h"
  image_order = "even-order-1-ns"
  is_global = false

    [gmgt_section.data.cta]
    url = "#"
    name = " Quick Start "
    background_color = "bg-light-gray"
    button_text_color = "mid-gray"
    border_color = "b--light-gray"
    border_radius = "br0"
    block_button_width = 50.0
    ph = 3.0
    pv = 2.0
    mv = 3.0
    icon_mask = "circle"
    inner_icon = "info"
    inner_icon_transform = "shrink-4"
    button_font_size = "4"

    [gmgt_section.data.appearance]
    section_background = "bg-primary-color-dark-90"
    icon_color = "gold"
    slide_animation = "fadeIn"

    [gmgt_section.data.image]
    responsive = false

[[gmgt_section]]
id = "sbm6q5c3t"
partial = "goandtalk/slides/alternate-two-columns-text-and-image"

  [gmgt_section.data]
  title = "Alternate Image Layout"
  image_source = "https://source.unsplash.com/sK1hW5knKkw/1536x864"
  image_column_width = 50.0
  image_opacity = 100.0
  card_overlay = 0.0
  card_width = 100.0
  image_height = 100.0
  text_column_class = "w-50-ns"
  image_layer = "static"
  image_under_text = false
  image_align_h = "left--25-ns"
  cta_display = "dn"
  quote_display = "dn"
  title_ph = "0"
  title_pv = "3"
  title_font_size = "2"
  title_align = "tc"
  title_transform = "ttc"
  title_font_weight = "7"
  section_max_width = "mw-100"
  card_font_size = 4.0
  card_font_weight = "4"
  image_br = "br0"
  object_fit_class = "of-cover"
  height_reference = "h"
  image_order = "even-order-1-ns"
  is_global = false
  intro = "Exercise"
  content = "* Hide the global toolbar to make room for this exercise.\n* Find the toolbar of this section.\n* Click on the toggle icon <i class=\"fas fa-toggle-off\"></i>  to turn this app on. \n* Click on the Edit button to switch to edit mode. You should see a context toolbar.\n* Notice the image of this section is on the side opposite to the previous section. If you are on a mobile phone, you may need to view in landscape mode to see this.\n* Click on the image and text icon <i class=\"fas fa-address-card fa-flip-horizontal\"></i> to change the position of this image in the section.\n* Click on the image to show a popup window, and enter the URL to the image you want to use.\n* Drag the slider to allocate different space to image and text. \n* Place the text above the image, drag the text slider to adjust the width of the text within the column.\n* Click on the text alignment button and place text block to somewhere you want.\n* Click on the Editing button to exit editing mode when done. \n\n\n"

    [gmgt_section.data.cta]
    url = "#"
    name = " Quick Start "
    background_color = "bg-light-gray"
    button_text_color = "mid-gray"
    border_color = "b--light-gray"
    border_radius = "br0"
    block_button_width = 50.0
    ph = 3.0
    pv = 2.0
    mv = 3.0
    icon_mask = "circle"
    inner_icon = "info"
    inner_icon_transform = "shrink-4"
    button_font_size = "4"

    [gmgt_section.data.appearance]
    section_background = "bg-primary-color-dark"
    icon_color = "gold"
    slide_animation = "fadeIn"

    [gmgt_section.data.image]
    responsive = false

[[gmgt_section]]
id = "shhsmbcui"
partial = "goandtalk/slides/alternate-two-columns-text-and-image"

  [gmgt_section.data]
  title = "Background and Foreground"
  image_source = "https://source.unsplash.com/sK1hW5knKkw/1536x864"
  image_column_width = 100.0
  image_opacity = 100.0
  card_overlay = 0.0
  card_width = 100.0
  image_height = 100.0
  text_column_class = "w-100-ns"
  image_layer = "absolute"
  image_under_text = true
  image_align_h = "left---ns"
  cta_display = "dn"
  quote_display = "dn"
  title_ph = "0"
  title_pv = "3"
  title_font_size = "2"
  title_align = "tc"
  title_transform = "ttc"
  title_font_weight = "7"
  section_max_width = "mw-100"
  card_font_size = 4.0
  card_font_weight = "4"
  image_br = "br0"
  object_fit_class = "of-cover"
  height_reference = "h"
  image_order = "even-order-1-ns"
  is_global = false
  intro = "Exercise"
  content = "* Hide the global toolbar to make room for this exercise.\n* Find the toolbar of this section.\n* Click on the toggle icon <i class=\"fas fa-toggle-off\"></i>  to turn this app on. \n* Click on the Edit button to switch to edit mode. You should see a context toolbar.\n* Drag the slider to allocate different space to image and text, and bring it to the foreground for editing. \n* Place the text beside the image, and flip to left or right as you want.\n* Click on the Editing button to exit editing mode when done. \n\n\n"
  image_column_height = "h-100"

    [gmgt_section.data.cta]
    url = "#"
    name = " Quick Start "
    background_color = "bg-light-gray"
    button_text_color = "mid-gray"
    border_color = "b--light-gray"
    border_radius = "br0"
    block_button_width = 50.0
    ph = 3.0
    pv = 2.0
    mv = 3.0
    icon_mask = "circle"
    inner_icon = "info"
    inner_icon_transform = "shrink-4"
    button_font_size = "4"

    [gmgt_section.data.appearance]
    section_background = "bg-primary-color-dark"
    icon_color = "gold"
    slide_animation = "fadeIn"

    [gmgt_section.data.image]
    responsive = false
    overlay_background = "bg-black-20"

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
    section_background = "bg-primary-color-dark"
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

You can create sections with images floating to the left or right alternately. You can place text anywhere on the image, or place one image above another to create interesting effect.

If you have completed all the exercises in this tutorial, you should have made the following achievements:

* know where to find section toolbar and global toolbar.
* know how to toggle global toolbar.
* know how to turn section app on, and switch to editing mode.
* change the position of text and image.

Well done. You will acquire new skills and explore new features in other tutorials. Stay tuned.
