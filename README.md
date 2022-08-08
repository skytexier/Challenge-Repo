# Horiseon Refactoring Project
 
## Description
 
For this project we were tasked with refactoring existing code for a website to make it more accessible, cleaner and to better display semantic HTML elements. First and foremost I added annotations and comments to the HTML and CSS files to better visualize and separate each element. This helped me in the refactoring process to better understand which sections of code I was working with, but going forward it will also help define the code for future development and avoid confusion. 
    
Through refactoring the code of this website I discovered a lot of HTML elements undefined in semantic terms, for example many elements were simply defined as < div > and not as headers, sections, footers and so on. 
    
Similarly many CSS elements were unnecessarily complex and overlapped with each other in their styling. This was mainly due to a plethora of classes in the HTML file, many of which had the same CSS styling regardless of their distinct class labels. To simplify this I renamed many of the classes and wrapped their styling up under one class in CSS. Refer to [Examples of changes](#examples-of-changes) for a better depiction of this.
    
After labeling the HTML and CSSsections, while also simplifying their code, I added alt tags to the images to meet accessibility standards. 
 
In summary, my motivation behind refactoring this website was to meet accessibility requirements and to make the backend tidy, intelligible and easy to modify/read going forward. On top of that I felt that adding a few new features would improve how the website looked for both the backend and frontend. In the process I learned quite a bit more about HTML semantic elements and their proper placements within a page (hopefully I got them right). Also I learned about CSS styling tools that I otherwise didn't know about, like background-images for example.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Examples of changes](#examples-of-changes)
- [Credits](#credits)
- [License](#license)
 
## Link To Live URL

[Week 1 Challenge](https://skytexier.github.io/Horiseon-Refactor/)

## Installation
 
For proper installation or usage of the website include index.html, style.css and /images folder. No installation required unless modifying code, in such case proper git pulling from the repo and importing into editing software required.
 
## Usage

The files of this refactoring project are to be used in redefining and updating the old files related to the website "Horiseon." The implementation of this code will help to define the semantic elements of the HTML file, add comments to its structure, and will overall improve accessibility. To further the end of improving accessability alt tags have been added to the HTML, the usage of which can be pictured below: 

![alt text](/images/refactoredalttags.png)

These files can completely replace the old code without a dramatic effect on the styling or structure of the page except for a few instances as listed in [features](#features). Similarly the implementation of this code will have the same effect on the CSS styling. 

 
## Features
 
Some unique features I added to this refactored project include on hover styling for the navbar links.
This implementation was intended to better help display the nav bars intended usage and to help with accessibility. As shown below:

![alt text](/images/navbarhover.png)
 
As stated earlier a feature I added, or rather refactored, was to combine many CSS classes for the aside and main content styling, thus making it easier to change all elements at once rather than individually adjusting classes for each element.
 
Smaller new features include alt tags for images and increased text size for < p > elements within < main > to allow for easier reading and overall increased accessibility. Also changed < aside > styling to be a bit more compact and readable by centering text.

## Examples of changes
Below is an example of the old CSS code for elements regarding the websites center boxes. <br>
Each of these sections had unique classes like .search-engine-optimization and .online-reputation-management. <br>
Despite this, these classes all had the same styling in CSS (except for their float styling).

![alt text](/images/oldcss-maincontent.png)

In my code I've wrapped up these distinct classes into one called "main-content" while leaving the class selectors for their float styling.

![alt text](/images/newcss-maincontent.png)

I also did a similar process for the classes and styling within the < aside > elements of this document.

Overall I think this might have been a bit of an extra step, and while it would make it slightly more time consuming to change the individual secetions now, in the long run I think it clarifies how the CSS is manifesting on the page much more clearly.

## Credits
 
While I did not collaborate with any other developers, I did use a myriad of resources to help define HTML elements and to better understand some CSS styling options. These resources include:
 
- W3Schools, HTML and CSS tutorials: [https://www.w3schools.com/](https://www.w3schools.com/)
- Penn State Accessibility: [https://accessibility.psu.edu/images/imageshtml/](https://accessibility.psu.edu/images/imageshtml/)
- MDN Web Docs, HTML elements reference guide: [https://developer.mozilla.org/en-US/docs/Web/HTML/Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- Coding-boot-camp Professional README Guide: [https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)
 
## License
 
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
