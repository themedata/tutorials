+++
date = "2019-01-09T00:00:00Z"
description = "Learn how to manage multiple sites or projects with Go and Talk page builder."
draft = false
gt_page_builder = true
header_class = "bg-transparent"
inner_icon = "globe"
iscjklanguage = false
lastmod = "2019-01-09T00:00:00Z"
lightness = 0.0
lightness_dark = 0.0
lightness_light = 0.0
lightness_lighter = 0.0
logo_url = "/images/logos/icon-on-dark.svg"
main_menu_align = "start"
primary_hue = 85.0
publishdate = "2019-01-09T00:00:00Z"
saturation = 40.0
skip_cover_nav = false
skip_slide_animation = false
title = "Starting a New Site"
type = "presentation"
accent_color = "hsl(350,35%,45%)"
accent_color_light = "hsl(350,35%,55%)"

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
  title = "New Site"
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
  content = "* this is an alternative way to reset the data of all pages to the default, by specifying a new site id and creating a new blank database. this way does not delete the previous data.\n* make changes to a section on this page, with something you can easily recognize, and save the section.\n* hover on the left edge of the screen to show the global toolbar\n* click on the globe icon <i class=\"fas fa-globe\"></i> to open the site setting  window.\n* click on the grid icon <i class=\"fas fa-th-large\"></i> at the top of the window to show the management options.\n* at the tab labelled \"Open\", enter a new site id. for easy reference, please use letters and digits and underscore only. \n* click the \"open\" button at the bottom of the window. the page will refresh and restore to the default tutorial. The changes you have made should have disappeared.\n* go to the site setting window again, and select or enter the site id \"gt\". click the \"open\" button to reload the page.\n* verify the changes you have made are still there."
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
id = "ssr0ccthv"
partial = "goandtalk/slides/collection-big-icon-mono"

  [gmgt_section.data]
  title = "What Happens When You Open a New Site"
  content = ""
  intro = "The page loading process explained"
  column_class = "w-33-l"
  resize_column = "flex-auto"
  horizontal_position = "justify-center"
  is_global = false

    [[gmgt_section.data.column]]
    icon = "database"
    title = "Site Database"
    description = "* a new site id is specified in the query string\n* the page builder creates a new database as it does not exist"

    [[gmgt_section.data.column]]
    icon = "file-alt"
    title = "Page Doc in Database"
    description = "* the page builder gets doc id from the query string, and loads custom data if found.\n* as it is blank database, no data exists, default data will be used."

    [[gmgt_section.data.column]]
    icon = "file-code"
    title = "Default Page Data"
    description = "* the page renders with the default data if custom data is not found in the site db.\n* for example, this page renders a tutorial if no custom data is found."

    [gmgt_section.data.appearance]
    section_background = "bg-white-80"
    card_background = "hover-primary-color"
    icon_color = "black-20"
    slide_animation = "fadeIn"
    text_color = "primary-color-first-letter-h3"

[[gmgt_section]]
id = "sxgwm2o3u"
partial = "goandtalk/slides/collection-big-icon-mono"

  [gmgt_section.data]
  title = "What Happens When You Open an Existing Site"
  content = ""
  intro = "The page loading process explained"
  column_class = "w-33-l"
  resize_column = "flex-auto"
  horizontal_position = "justify-center"
  is_global = false
  description = "  "

    [[gmgt_section.data.column]]
    icon = "database"
    title = "Site Database"
    description = "* the site id is specified in the query string, and defaults to \"gt\"\n* the page builder loads data from this database if found."

    [[gmgt_section.data.column]]
    icon = "file-alt"
    title = "Page Doc in Database"
    description = "* the page builder gets doc id from the query string, and defaults to the current path followed by _index.md.\n* the page builder loads document with this doc id.\n* your custom data is found and rendered."

    [gmgt_section.data.appearance]
    section_background = "bg-white-80"
    card_background = "hover-primary-color"
    icon_color = "black-20"
    slide_animation = "fadeIn"
    text_color = "primary-color-first-letter-h3"

[[gmgt_section]]
id = "sxaab0xqs"
partial = "goandtalk/slides/alternate-text-and-big-icon-layer"

  [gmgt_section.data]
  title = "Deleting A Site"
  content = "* you can delete an existing database at \"Current\" tab of the site setting window.\n* after confirmation, the database will be permanently deleted. \n* if you have stored some real data in the database, double check before deleting a database. this process is not reversible. \n* if you are not sure, it is better to switch to a new site id to start afresh, without deleting the old database."
  intro = " "
  is_global = false

    [gmgt_section.data.icons]
    mini_icon = "exclamation"
    mini_icon_color = "black-50"
    outer_icon = "circle"
    width = 20.0
    icon_transform = "shrink-6"

    [gmgt_section.data.appearance]
    section_background = "bg-light-yellow"
    text_color = "black-50"
    icon_color = "yellow"
    slide_animation = "fadeIn"

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
