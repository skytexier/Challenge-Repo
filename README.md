# Week 1 Challenge Assignment

## Description

For this project we were tasked with refactoring existing code for a website to make it more accesable, cleaner and to better display semantic HTML elements. First and foremost I added annotations and comments to the HTML and CSS files to better visualize and seperate each element. Through refactoring the code of this website I discovered a lot of HTML elements undefined in semantic terms, for example many elements were simply defined as <div> and not as headers, sections, footers and so on. Similarly many CSS elements were unecessarily complex and overlapped with eachother, so I wrapped up many classes into one which all had the same styling applied to them regardless. On top of all this I also added alt tags to the websites images to meet accsesabilty standards. 

In summary this website was built, or rather refactored, to  meet accsesability requirements and to make the backend tidy, intelligable and easy to modify/read going forward. In the process I learned quite a bit more about HTML semantic elements and their proper (hopefully) placements within a page. Also I learned about CSS styling tools that I otherwise didnt know about, like background-images for example. 

- What was your motivation?
- Why did you build this project? (Note: the answer is not "Because it was a homework assignment.")
- What problem does it solve?
- What did you learn?

# Table of Contents

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Usage](#usage)
- [Features](#features)
- [Credits](#credits)
- [License](#license)

# Installation

For proper installation or usage of the website include index.html, style.css and /images folder. No installation required unless modifying code, in such case proper git pulling from the repo and importing into editing software required.

# Usage

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

    ```md
    ![alt text](assets/images/screenshot.png)
    ```
md [alt text](images/)

# Features

Some unique features I added to this refactored project include on hover styling for the navbar links.
This implementation was intended to better help display the nav bars intended usage and to help with accesability. 

As stated earlier a feature I added, or rather refactored, was to combine many CSS classes for the aside and main content styling, thus making it easier to change all elements at once rather than individually adjusting classes for each element. 

Smaller new features include alt tags for images and increased text size for <p> elements within <main> to allow for easier reading and overall increased accesability. Also changed <aside> styling to be a bit more compact and readable by centering text.

# Credits

While I did not collaborate with any other developers, I did use a myriad of resources to help define HTML elements and to better understand some CSS styling options. These resources include:

- W3Schools, HTML and CSS tutorials: [https://www.w3schools.com/](https://www.w3schools.com/)
- Penn State Accessibility: [https://accessibility.psu.edu/images/imageshtml/](https://accessibility.psu.edu/images/imageshtml/)
- MDN Web Docs, HTML elements reference guide: [https://developer.mozilla.org/en-US/docs/Web/HTML/Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- Coding-boot-camp Professional README Guide: [https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)

# License

MIT License

Copyright (c) [2022] [Sky Hamilton Texier]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.