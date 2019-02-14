+++
date = "2019-01-09T00:00:00Z"
description = "Learn how to manage multiple pages with the same URL."
draft = false
gt_page_builder = true
header_class = "bg-transparent"
inner_icon = "file-alt"
iscjklanguage = false
lastmod = "2019-01-09T00:00:00Z"
lightness = 0.0
lightness_dark = 0.0
lightness_light = 0.0
lightness_lighter = 0.0
logo_url = "/images/logos/icon-on-dark.svg"
main_menu_align = "start"
primary_hue = 303.0
publishdate = "2019-01-09T00:00:00Z"
saturation = 40.0
skip_cover_nav = false
skip_slide_animation = false
title = "Starting a New Page"
type = "presentation"
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
  description = "from the same URL"
  intro = "starting "
  title = "New Page"
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
data = ""
data_key = "finding_toolbar"
id = "b9412"
is_global = true
partial = "goandtalk/slides/collection-big-icon-mono"

[[gmgt_section]]
id = "sqp7j3hrq"
partial = "goandtalk/slides/collection-big-icon-circle-mask"
is_global = true
data_key = "data_browser_database"

[[gmgt_section]]
data = ""
data_key = "site_and_page_data"
id = "snbvwe96k"
is_global = true
partial = "goandtalk/slides/collection-big-icon-mono"

[[gmgt_section]]
id = "sh57nfer5"
partial = "goandtalk/slides/collection-big-icon-mono"

  [gmgt_section.data]
  title = "What Happens When You Open a Page"
  content = ""
  intro = "Page Starts with a Placeholder"
  description = "  "
  column_class = "w-33-l"
  resize_column = "flex-auto"
  horizontal_position = "justify-center"
  is_global = false

    [[gmgt_section.data.column]]
    icon = "database"
    title = "Site Database"
    description = "* one database for each site (project)\n* site id is specified in the URL, for example `/?site=gt`\n* site id defaults to \"gt\""

    [[gmgt_section.data.column]]
    icon = "file-alt"
    title = "Page Doc in Database"
    description = "* each page is a unique document in the site database\n* page id is specified in the URL, for example /?doc=my-presentation\n* page id defaults to the current URL, followed by _index.md. "

    [[gmgt_section.data.column]]
    icon = "file-code"
    title = "Default Page Data"
    description = "* the page renders with the default data if custom data is not found in the site db.\n* for example, this page renders a tutorial if no custom data is found."

    [gmgt_section.data.appearance]
    section_background = "bg-white-80"
    card_background = "hover-primary-color"
    icon_color = "black-20"
    slide_animation = "fadeIn"

[[gmgt_section]]
id = "sd5m6kco3"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  content = "* make changes to a section, with something you can easily recognize, and save the section.\n* hover on the left edge of the screen to show the global toolbar\n* click on the file icon <i class=\"fas fa-file-alt\"></i> to open the page setting  window.\n* click on the grid icon <i class=\"fas fa-th-large\"></i> at the top of the window to show the management options.\n* at the tab labelled \"Current\", click the \"Delete Page\" button, and confirm the operation in the confirmation window.\n* the page will refresh and restore to the default tutorial.\n* you can make changes, save it again to create a new document in the db. The new document has the default id containing the current URL. For example, the id of this page is tutorial/starting-a-new-page/_index.md"
  intro = "Exercise"
  is_global = false
  title = "Reset Page Data to the Default"

    [gmgt_section.data.appearance]
    icon_color = "gold"
    section_background = "bg-primary-color-light"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    icon_transform = "shrink-6"
    mini_icon = "grip-vertical"
    mini_icon_color = "white"
    outer_icon = "circle"
    width = 20.0

[[gmgt_section]]
id = "s7c9ss9jr"
partial = "goandtalk/slides/collection-big-icon-mono"

  [gmgt_section.data]
  column_class = "w-25-l"
  content = ""
  description = "  "
  horizontal_position = "justify-center"
  intro = "Page Settings"
  is_global = false
  resize_column = "flex-auto"
  title = "Managing Page Data"

    [gmgt_section.data.appearance]
    card_background = "hover-primary-color"
    icon_color = "black-20"
    slide_animation = "fadeIn"

    [[gmgt_section.data.column]]
    description = "* save the current document under a different unique id. \n* after you click on the dropdown button, as you type, the ids of existing documents will show up.\n* make sure to choose different id to create a new document.\n* choose an existing id, and tick the override checkbox to replace."
    icon = "clone"
    title = "Save As"

    [[gmgt_section.data.column]]
    description = "* reload page from the selected page data.\n* you can load a different document from the same URL, for example, the tutorial homepage. \n* when you open a different document, the page id is included in the URL automatically. \n* you can bookmark a page with site id and page id to go to that document when you open the page."
    icon = "folder-open"
    title = "Open"

    [[gmgt_section.data.column]]
    description = "* you can delete the current document\n* once you confirm deleting the current document, it is deleted permanently.\n"
    icon = "trash"
    title = "Delete"

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
    section_background = "bg-accent-color-light"
    slide_animation = "fadeIn"

    [gmgt_section.data.icons]
    mini_icon = "download"

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
  intro = "Make a Difference with Innovation"
  object_fit_class = "of-scale-down"
  quote_display = "dn"
  title_align = "tc"
  title_font_size = "2"
  title_font_weight = "7"
  title_ph = "0"
  title_pv = "3"
  title_transform = "ttc"
  title = "Starting a New Page"
  content = "Go and Talk is a lightweight web design tool running in the browser. It empowers designers and marketers to create presentable pages quickly without coding. It is optimized for mobile devices.\n\nGo and Talk page builder stores data in IndexedDB, a feature offered by modern browsers. Each site  or project is a unique database. Each page is a document in the database with a unique ID. \n\nWhen a page loads, it checks for site id and page id from the URL query string. Site id defaults to 'gt', and page id defaults to the current path followed by _index.md. If custom page data is found, it renders the custom page data. Otherwise it renders the default page data, the tutorial. \n\nWhen you use the site and page setting user interface, the query string is automatically included in the page URL. You can manually change the site id or document id to load different data quickly, or create a new document.\n\nIf you have completed all the exercises in this tutorial, you should have made the following achievements:\n\n* know where to find section toolbar and global toolbar.\n* understand how the page loads data.\n* know how to reset the page to default data.\n\nWell done. You will acquire new skills and explore new features in other tutorials. Stay tuned.\n"

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

Go and Talk page builder stores data in IndexedDB, a feature offered by modern browsers. Each site  or project is a unique database. Each page is a document in the database with a unique ID.

When a page loads, it checks for site id and page id from the URL query string. Site id defaults to 'gt', and page id defaults to the current path followed by _index.md. If custom page data is found, it renders the custom page data. Otherwise it renders the default page data, the tutorial.

When you use the site and page setting user interface, the query string is automatically included in the page URL. You can manually change the site id or document id to load different data quickly, or create a new document.

If you have completed all the exercises in this tutorial, you should have made the following achievements:

* know where to find section toolbar and global toolbar.
* understand how the page loads data.
* know how to reset the page to default data.

Well done. You will acquire new skills and explore new features in other tutorials. Stay tuned.
