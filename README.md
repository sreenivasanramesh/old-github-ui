# Old GitHub UI (Chrome / Firefox extension)

## Note: I'll be archiving this repo soon. All active development will be at [Old School GitHub](https://github.com/daattali/oldschool-github-extension).

> This chrome extension tries to bring back parts of the old User Interface for Github.
> This is a modified fork of [Old School GitHub](https://github.com/daattali/oldschool-github-extension) made by [Dean Attali](https://deanattali.com).


GitHub rolled out a brand new UI on June 23, 2020. This extension modifies some of the elements to bring back the classic GitHub look, including moving the sodebar to the top.


## Installation

Installation is extremely easy: just go to [the Chrome extension store](https://chrome.google.com/webstore/detail/old-github-ui/dhifdlfedboijpanpblghhhakpnncadb) or [Firefox add-ons page](https://addons.mozilla.org/en-US/firefox/addon/old-github-ui/) and install with one button click there.

## Features

2. **Move the sidebar to the top of the content area:** In the June update, GitHub moved some of the elements from the top of the page to a sidebar. This extension moves it back to the top..

2. **Move headers to main content area:** In the June update, GitHub moved the header buttons ("Code"/"Issues"/"Pull Requests"/etc) to the far left of the page. This was only an issue if you have a big wide monitor because those buttons are now very very far from the rest of the page content. If you're on a laptop you probably won't notice the difference.

3. **Highlight selected page in header:** Prior to the update, the selected page you're on was clearly highlighted. The update made the current page selection much more subtle.

4. **Classic-syle buttons:** The old buttons had depth, and the new buttons are flat and look less clickable. 

5. **Add row separators in file explorer:** The file explorer that shows all the files and folders currently has no borders between rows, making it harder to read the file list.

6. **Remove circular user images:** The new circular user photos result in unwanted rounding near the corners, cropping significant features from photos that are intended to be square for some users.

And many other UI fixes such as fix the text width of issue counters and issue label, fix the whitespace of issues, add a slight background to README title, and more.

## Screenshots

#### 1, 2. Move sidebar, headers to main content area

![Headers Before](/img/doc/screenshot-headers-before.png)
VS
![Headers After](/img/doc/screenshot-headers-after.png)

#### 3. Highlight selected page in header

![Selectors Before](/img/doc/screenshot-selected-before.png)
VS
![Selectors After](/img/doc/screenshot-selected-after.png)

#### 4, 5, 6: add row separators, use classic buttons, remove circular images

![Before](/img/doc/screenshot-main-before.png)
VS
![After](/img/doc/screenshot-main-after.png)




## Disclaimer

This is my first time working with CSS. The code is probably ugly and definitely not bug-free, so please do create issues.

This was written in just a couple hours and does not deal with some of the biggest UI changes like the layout of the sidebar vs the main content. Because GitHub uses AJAX to load many of its pages (like when navigating from the Code page to Pull Requests), I had to make everything use CSS and no JavaScript.

