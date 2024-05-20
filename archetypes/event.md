+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
artist = "Artist"
location = "Venue, Place"
time = "pm - pm"
price = "£ - £"
date = '{{ time.Now.Format "2006-01-02" }}'
draft = true

[params]
salsa = "primary"
bachata = "secondary"
kizomba = "secondary"
map_url = ""
+++
