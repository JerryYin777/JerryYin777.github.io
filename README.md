# A simple Github Pages template for academic personal website.

## Introduction

This is an academic personal website template based on bootstrap. This demo refers to [senli1073](https://github.com/senli1073/senli1073.github.io), thx to Mr.Sen Li's template.

This template supports markdown files as input content, and you don't need to build the webpage before deployment. When the webpage is loaded, the markdown files will be automatically parsed and embedded into the page.

Demo: https://jerrysys.top


## Getting Start
### 1. Fork this repository
The repository name should be `<username>.github.io`, which will also be your website's URL.


### 2. Edit page content

(1) Go to the folder where you want to store your project, and clone the new repository:
```
git clone https://github.com/<username>/<username>.github.io.git
```
The directory structure is as follows:

```.
.
├── contents
└── static
    ├── assets
    │   └── img
    ├── css
    └── js
```

(2) Edit the content of each section, which corresponds to `contents/*.md`.

(3) Edit the title, copyright information and other text of the website in `contents/config.yml`

(4) Replace background image and photo with new ones for your web pages in `static/assets/img`

(5) Push it: 
```
git commit -am 'init'
git push
```


### 3. Enjoy

Fire up a browser and go to `https://<username>.github.io`



## License

Copyright 2024, Jerry Yin and controlled via the MIT license, a permissive open-source (free software) license. You can copy and mess with this template.
