+++
title = "Chromeduino"
date = 2018-06-10T00:21:07+08:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Education", "Chrome App", "IDE"]

# Project summary to display on homepage.
summary = "A Chrome App which uses the serial API on the chrome browser to program AVR Arduinos with a serial bootloader that is avrdude compatible (Arduino Uno, Mega, etc)"

# Optional image to display on homepage.
image_preview = "projects/chromeduino.png"

# Optional external URL for project (replaces project detail page).
external_link = ""

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
![Main interfaces](/img/projects/chromeduino.png)

Chromeduino is a coding interface made for ChromeOS. The project was originally created by Casey Halverson (Spaceneedle) and was lacking in terms of features and stability. 
As this application is the only free option for coding Arduinos with ChromeOS, there is a need for such a tool in classrooms, where all the students have 
educational Chromebooks but the teacher/school does not have the resources to pay for the other editors.

This project involved taking the existing codebase and drastically modifying it to add in the necessary features to make the coding interface useful.
The application used a remote compiling server to translate the written code into the binaries to be flashed to the Arduinos. 
Unfortunately, the code for the original compile server was lost, so a new server also had to be created from scratch using Node.js.

The [new version of the application can be found here.](https://chrome.google.com/webstore/detail/chromeduino2/llclpgogfbmiicabgcfbndeokekmggpm?hl=en) The [GitHub can be found here.](https://github.com/spaceneedle/Chromeduino)

![Server Selector](/img/projects/chromeduino-servers.png)
