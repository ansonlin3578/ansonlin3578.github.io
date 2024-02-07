---
title: Web server end-to-end automated tesing flow
summary: |
  <em><small style="background-color: #c5c5f7; color: #330066; padding: 5px;">nodeJS/selenium/playwright/webdriver/postman/</small></em><br>
  <small><em>Sep 2023 – Oct 2023</em></small><br>
  The automated testing program I developed has reduced the testing time to `one-tenth` of the original manual testing time.<br>
  [Maintaned website](https://www.kolradar.com/?gad_source=1&gclid=CjwKCAiA8YyuBhBSEiwA5R3-E6FUlu5Qdbs0fb4d2B5GIptRWLuzycL-b8oxWVI2Co9mXhhDn6IkvhoCupsQAvD_BwE)
tags:
  - Automated testing 
date: '2023-09-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ''
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
### Abstract
In this project, I first conducted a comprehensive analysis to identify all the test scenarios that needed to be covered. Then, I proceeded to create a <u style="color: #7dafe2;">flowchart</u> outlining the automation testing process. This flowchart included the <u style="color: #7dafe2;">validation items, test data, definition of positive and negative test cases</u>, as well as the expected error codes and messages that the web server should respond with in different scenarios.

After finalizing the flowchart, I proceeded to develop the <u style="color: #7dafe2;">automated testing package</u>. This package was designed to take the response from the web server as input and generate a detailed test report as output. The testing package included various test cases covering both positive and negative scenarios to ensure thorough testing of the web server's functionality.

Overall, this approach enabled us to streamline the testing process and significantly reduce the time required for testing while ensuring comprehensive coverage of all relevant test scenarios.
