+++
title = "Multiplayer Painting"
date = 2018-06-10T00:18:58+08:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["WebVR", "Networking", "SIGGRAPH Asia"]

# Project summary to display on homepage.
summary = "A socket based multiplayer server example for a-painter, a WebVR painting application."

# Optional image to display on homepage.
image_preview = "projects/a-painter.png"

# Optional external URL for project (replaces project detail page).
external_link = "https://github.com/mrfrase3/a-painter-socket-server"

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

This server uses a-painter's main repo, except instead of using a cli webpack server, it hosts its own express server with webpack implemented and then runs a socket.io server on top. It also injects the multiplayer layer into the client application.

This serves as a basic example and the method can easily be modified to support different communication types, like mongo, firebase, webRTC, etc...
