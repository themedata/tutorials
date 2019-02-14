+++
accent_color = "hsl(350,35%,45%)"
accent_color_light = "hsl(350,35%,55%)"
date = "2019-01-09T00:00:00Z"
description = "Learn how to export and import data"
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
primary_hue = 292.0
publishdate = "2019-01-09T00:00:00Z"
saturation = 0.0
skip_cover_nav = false
skip_slide_animation = false
title = "Data Storage, Exporting and Importing Data"
type = "presentation"
icon_mask = "square"
inner_icon = "exchange-alt"
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
  description = "for backup and integration"
  intro = "import and export"
  title = "Data"
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
id = "sflwpltxe"
partial = "goandtalk/slides/collection-big-icon-mono"
is_global = true
data_key = "finding_toolbar"

[[gmgt_section]]
id = "svbtoqty9"
partial = "goandtalk/slides/collection-big-icon-circle-mask"
is_global = true
data_key = "data_browser_database"

[[gmgt_section]]
id = "sqhmq2vah"
partial = "goandtalk/slides/collection-card"

  [gmgt_section.data]
  title = "Purpose of Exporting Data"
  content = ""
  intro = " "
  description = "  "
  column_class = "w-25-l"
  resize_column = "flex-auto"
  horizontal_position = "justify-center"
  images_class = "br0"
  is_global = false

    [[gmgt_section.data.column]]
    title = "Backup"
    description = "* IndexedDB is managed by browsers\n* data could be accidentally deleted if you clear browsing data.\n* back up is a good practice"

    [[gmgt_section.data.column]]
    title = "Integration"
    description = "* work with external app, for example static website generator\n* load initial data from external app\n* edit data and see changes immediately\n* export data and feed to external app for further processing\n* the tutorials in this section have been written this way."

    [[gmgt_section.data.column]]
    title = "Batch Operation"
    description = "* process the page data as plain text\n* export, search and replace term for example\n* import back to generate a fresh page"

    [gmgt_section.data.appearance]
    card_background = "hover-primary-color"
    slide_animation = "fadeIn"

[[gmgt_section]]
id = "s3a72rg7o"
partial = "goandtalk/slides/collection-card"

  [gmgt_section.data]
  title = "Supported Data Format"
  content = ""
  intro = " "
  description = "  "
  column_class = "w-33-l"
  resize_column = "flex-auto"
  horizontal_position = "justify-center"
  images_class = "br0"
  is_global = false

    [[gmgt_section.data.column]]
    title = "TOML"
    description = "* user friendly\n* flexible about space and indentation\n* can include comments"

    [[gmgt_section.data.column]]
    title = "YAML"
    description = "* user friendly\n* strict about space and indentation\n* can include comments"

    [[gmgt_section.data.column]]
    title = "JSON"
    description = "* intended for machine parsing\n* not user friendly. text is difficult to read with escaped quotes\n* can not include comments"

    [gmgt_section.data.appearance]
    section_background = "bg-white-80"
    card_background = "hover-primary-color"
    slide_animation = "fadeIn"

[[gmgt_section]]
id = "b94f8"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* Find the global toolbar by hovering on the left edge of the screen. If you are using a mobile device, you may need to tap on the left edge to show the toolbar.\n* Click on the page setting (<i class=\"fas fa-file-alt\"></i>) button to show the page setting options.\n* Now click on the grid icon <i class=\"fas fa-th-large\"></i> at the top of the option window. You will see a new set of tabs. \n* Click on Export Data tab. You should see a big button (Download Page Data)  at the bottom of the form.\n* The data format defaults to TOML. Click the radio button to switch to YAML or JSON. \n* If your external app requires data to be provided in certain way, you may define custom delimiters here. Otherwise just leave the delimiter box unchecked.\n* Click the download button and choose where to save your data. \n* The download button is not available on mobile devices. If you are using a mobile device, you can copy and paste the page data to another app.\n* You can import the page data back by going to the Import Data tab. The formats of the data is automatically detected.\n* If you have used custom delimiter, specify the same delimiter here for import."
  description = ""
  intro = "Exercise"
  is_global = false
  title = "Export and Import Page Data"

    [gmgt_section.data.appearance]
    animation = "fadeIn"
    icon_color = "primary-color"
    section_background = "bg-primary-color-light"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    mini_icon = "file-export"
    mini_icon_color = "white"
    outer_icon = "circle"
    width = 20.0

[[gmgt_section]]
id = "srnaskstk"
partial = "goandtalk/slides/collection-big-icon-mono"
is_global = true
data_key = "site_and_page_data"

[[gmgt_section]]
id = "s9xm8gdsf"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* Find the global toolbar by hovering on the left edge of the screen. If you are using a mobile device, you may need to tap on the left edge to show the toolbar.\n* Click on the site setting (<i class=\"fas fa-globe\"></i>) button to show the site setting options.\n* Now click on the grid icon <i class=\"fas fa-th-large\"></i> at the top of the option window. You will see a new set of tabs. \n* Click on Export Data tab. You should see a big button (Download Site Data)  at the bottom of the form.\n* The data format defaults to TOML. Click the radio button to switch to YAML or JSON. \n* Click the download button and choose where to save your data. \n* The download button is not available on mobile devices. If you are using a mobile device, you can copy and paste the site data to another app.\n* You can import the site data back by going to the Import Data tab. The formats of the data is automatically detected.\n* Importing data will replace the data in the database. Make sure to import the right data.\n* Note the site data and page data serves very different purposes. Importing to the wrong place will not work."
  description = ""
  intro = "Exercise"
  is_global = false
  title = "Export and Import Site Data"

    [gmgt_section.data.appearance]
    animation = "fadeIn"
    icon_color = "accent-color"
    section_background = "bg-accent-color-light"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    mini_icon = "file-export"
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

Mixing and copying existing blocks is a great way to get start quickly. You can make changes and explore options available.

If you have completed all the exercises in this tutorial, you should have made the following achievements:

* know where to find section toolbar and global toolbar.
* clone sections and move sections around.
* toggle section applications on and off.
* make changes to the section.
* export page data for backup.

Well done. You will acquire new skills and explore new features in other tutorials. Stay tuned.
