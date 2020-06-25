# Old GitHub UI (Chrome / Firefox extension)

> This chrome extension tries to bring back parts of the old User Interface for Github.
> This is a modified fork of [Old School GitHub](https://github.com/daattali/oldschool-github-extension) made by [Dean Attali](https://deanattali.com).
> *Copyright 2020 [Sreenivasan Ramesh](https://sramesh.me). Licensed under the MIT license.*

_Source code available [on GitHub](https://github.com/sreenivasanramesh/old-github-ui)_     

GitHub rolled out a brand new UI on June 23, 2020. There are a aspects of the new UI that I (and many others) doesn't like and this extension brings modifies some of the elements to bring back the classic GitHub look.


## Installation

Installation is extremely easy: just go to [the Chrome extension store](https://sramesh.me) or [Firefox add-ons page](https://sramesh.me) and install with one button click there.

## Features

1. **Move headers to main content area:** In the June update, GitHub moved the header buttons ("Code"/"Issues"/"Pull Requests"/etc) to the far left of the page. This was only an issue if you have a big wide monitor because those buttons are now very very far from the rest of the page content. If you're on a laptop you probably won't notice the difference.

2. **Highlight selected page in header:** Prior to the update, the selected page you're on was clearly highlighted. The update made the current page selection much more subtle.

3. **Classic-syle buttons:** The old buttons had depth, and the new buttons are flat and look less clickable. 

4. **Add row separators in file explorer:** The file explorer that shows all the files and folders currently has no borders between rows, making it harder to read the file list.

5. **Remove circular user images:** The new circular user photos result in unwanted rounding near the corners, cropping significant features from photos that are intended to be square for some users.

And many other UI fixes such as fix the text width of issue counters and issue label, fix the whitespace of issues, add a slight background to README title, and more.

## Screenshots

#### 3, 4, 5: add row separators, use classic buttons, remove circular images

![Before](/img/doc/screenshot-main-before.png?raw=true)
<p align="center">
VS
</p>
![After](/img/doc/screenshot-main-after.png)

#### 1. Move headers to main content area

![Headers Before](/img/doc/screenshot-headers-before.png)
<p align="center">
VS
</p>
![Headers After](/img/doc/screenshot-headers-after.png)

#### 2. Highlight selected page in header

![Selectors Before](/img/doc/screenshot-selected-before.png)
<p align="center">
VS
</p>
![Selectors After](/img/doc/screenshot-selected-after.png)

## Disclaimer

I'm not a CSS person, this is my first time working with CSS. The code is probably ugly and definitely not bug-free, so if please do create issues.

This was written in just a couple hours and does not deal with some of the biggest UI changes like the layout of the sidebar vs the main content. Because GitHub uses AJAX to load many of its pages (like when navigating from the Code page to Pull Requests), I had to make everything use CSS and no JavaScript.

