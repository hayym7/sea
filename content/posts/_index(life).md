+++
title = "/posts/life"
description = "personal blog (≧◡≦)"
sort_by = "date"
template = "blog.html"
page_template = "postlife.html"
insert_anchor_links = "right"
generate_feeds = true

[slugify]
paths = "on"
taxonomies = "on"
anchors = "on"


[extra]

sections = [
  { name = "ai blog", path = "/posts/", is_external = false },
]

lang = "en"

title = "Posts"
subtitle = "on running, literature & love"

date_format = "%b %-d, %Y"

categorized = false # posts can be categorized
back_to_top = true # show back-to-top button
toc = false # show table-of-contents
comment = false # enable comment
copy = true # show copy button in code block

outdate_alert = false
outdate_alert_days = 12
outdate_alert_text_before = "This article was last updated "
outdate_alert_text_after = " days ago and may be out of date."
+++