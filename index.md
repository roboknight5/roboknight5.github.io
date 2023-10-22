---
title: About Me
layout: splash
excerpt: 'Hi my name is **Mohamed Gougou**, I am a **Computer Engineer** interested in creating and building new things, I love learning new technologies and tools in terms of both **Software** and **Hardware** and applying them to build solutions that would benefit and help people.'
header:
    overlay_color: "#000"
    overlay_filter: "0.5"
    # overlay_filter: linear-gradient(rgba(255, 0, 0, 0.5), rgba(0, 255, 255, 0.5))
    overlay_image: /assets/images/banner-3.jpg

entries_layout: grid
intro: 
  - excerpt: 'Hi my name is Mohamed Gougou, I am a Computer Engineer interested in creating and building things, I love learning new technologies and tools in terms of both software and hardware and applying those to create solutions to problems that would benefit and help people.'
    # image_path: assets/images/profile.png
fullstack:
  - image_path: assets/images/login_2.png
    alt: "placeholder image 1"
    title: "Frontend"
    excerpt: "**Design** and **develop** a **User Interface** for web application that is both simple and appealing to clients while providing a **User Experience** that meets all client needs required by the system."
  - image_path: /assets/images/api.png
    alt: "backend"
    title: "Backend"
    excerpt: "**Engineer** and **build** efficient backend solutions that provides a business with a **Software System**, that would handle the required business logic in terms of both providing information to a client and manging and storing data efficiently."
  - image_path: /assets/images/server.png
    title: "Database"
    excerpt: "**Store** business **Data** in an efficient and safe manner that allows for **fetching data** and information quickly to meet a client's request while providing a stable infrastructure for both storing large amounts of data safely and securely."
mobile_application:
  - image_path: /assets/images/application.png
    alt: "placeholder image 2"
    title: "Mobile Application"
    excerpt: "**Design** and **Build** mobile application using frameworks such as **Flutter** , **React Native** and **Capacitor** that guarantee great **UI/UX** experience for clients while achieving the functionality and business logic needed by the system."
hardware:
  - image_path: /assets/images/iot.png
    alt: "placeholder image 2"
    title: "Hardware/Iot"
    excerpt: "Experience programming Devices such as **ESP32** to Develop **IoT** Solutions that interact with peripherals and transmit information over the internet using communication protocols such as **Websockets** and **Mqtt**."
programming_languages:
  - image_path: /assets/images/ide.png
    alt: "placeholder image 2"
    title: "Programming Languages"
    excerpt:  "Experience developing in programming languages such as **C/C++**, **Python**, **Javascript**, **C#**, **Java**, **Dart**, **Php**."
# frontend:
#   - image_path: assets/images/unsplash-gallery-image-1-th.jpg
#   alt: "placeholder image 1"
#   title: "Backend"
#   excerpt: "Expireinece Developing Backend system that would meet business needs."
# mobile:
#   - image_path: assets/images/unsplash-gallery-image-1-th.jpg
#   alt: "placeholder image 1"
#   title: "Backend"
#   excerpt: "Expireinece Developing Backend system that would meet business needs."
# iot:
#   - image_path: assets/images/unsplash-gallery-image-1-th.jpg
#   alt: "placeholder image 1"
#   title: "Backend"
#   excerpt: "Expireinece Developing Backend system that would meet business needs."     
# feature_row:
  # - image_path: assets/images/unsplash-gallery-image-1-th.jpg
  #   alt: "placeholder image 1"
  #   title: "Placeholder 1"
  #   excerpt: "This is some sample content that goes here with **Markdown** formatting."
  # - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
  #   image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
  #   alt: "placeholder image 2"
  #   title: "Placeholder 2"
  #   excerpt: "This is some sample content that goes here with **Markdown** formatting."
  #   url: "#test-link"
  #   btn_label: "Read More"
  #   btn_class: "btn--primary"
  # - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
  #   title: "Placeholder 3"
  #   excerpt: "This is some sample content that goes here with **Markdown** formatting."
# feature_row2:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Left Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row3:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Right Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
# feature_row4:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Center Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"

---
<!-- {% include my_feature_row id="intro" type="center" %} -->


## My Skills
# Full-Stack Development
{% include my_feature_row id="fullstack" %}


{% include my_feature_row id="mobile_application" type="center" %}

{% include my_feature_row id="hardware" type="left" %}

{% include my_feature_row id="programming_languages" type="center" %}


<!-- {% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %} -->

<!-- # Featured Projects
{% assign entries_layout = page.entries_layout | default: 'list' %}

<div class="entries-{{ entries_layout }}">
  {% include my-featured-projects.html collection="projects" sort_by=page.sort_by sort_order=page.sort_order type=entries_layout %}
</div> -->



