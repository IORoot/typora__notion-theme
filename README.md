
<div id="top"></div>

<div align="center">

<div style="filter: invert(8%) sepia(8%) saturate(972%) hue-rotate(325deg) brightness(92%) contrast(83%);">
<img src="https://cdn.jsdelivr.net/npm/@mdi/svg@6.7.96/svg/language-markdown.svg" style="width:200px;"/>
</div>

<h3 align="center">Typora theme - Notion.so</h3>

<p align="center">
My little attempt at recreating the notion.so theme and functionality through pure CSS themes.
</p>    
</div>

##  1. <a name='TableofContents'></a>Table of Contents


* 1. [Table of Contents](#TableofContents)
* 2. [About The Project](#AboutTheProject)
	* 2.1. [Built With](#BuiltWith)
	* 2.2. [Installation](#Installation)
* 3. [Usage](#Usage)
	* 3.1. [Main feature - Top image full width image](#Mainfeature-Topimagefullwidthimage)
	* 3.2. [Hidden image folder](#Hiddenimagefolder)
	* 3.3. [Embedded Header Logo](#EmbeddedHeaderLogo)
	* 3.4. [Sidebar](#Sidebar)
	* 3.5. [Fences and Codeblocks](#FencesandCodeblocks)
* 4. [ Customising](#Customising)
* 5. [Troubleshooting](#Troubleshooting)
* 6. [Contributing](#Contributing)
* 7. [License](#License)
* 8. [Contact](#Contact)
* 9. [Changelog](#Changelog)



##  2. <a name='AboutTheProject'></a>About The Project

![Notion Screenshot](https://github.com/IORoot/typora__notion-theme/blob/master/notion/Notion.jpg?raw=true)
![Notion Screenshot](https://github.com/IORoot/typora__notion-theme/blob/master/notion/NotionPattern.jpg?raw=true)

<p align="right">(<a href="#top">back to top</a>)</p>


###  2.1. <a name='BuiltWith'></a>Built With

This project was built with the following frameworks, technologies and software.

- [Typora](https://typora.io/)

<p align="right">(<a href="#top">back to top</a>)</p>


###  2.2. <a name='Installation'></a>Installation

These are the steps to get up and running with this theme.

1. Clone the repo into your typora theme folder
    ```sh
    git clone https://github.com/IORoot/typora__notion-theme
    ```


<p align="right">(<a href="#top">back to top</a>)</p>


##  3. <a name='Usage'></a>Usage

Features listed below:

###  3.1. <a name='Mainfeature-Topimagefullwidthimage'></a>Main feature - Top image full width image

Place an image in the very first paragraph of the page and it will be converted into a full-width, 30vh sized image across the top of the page. 
The image is aligned top-center. and the rest will be cropped. You can change this to be center-center in the CSS.


###  3.2. <a name='Hiddenimagefolder'></a>Hidden image folder

Put all images in a 'hidden' folder called `.images`at the same directory level as the markdown file by selecting the option for images :  ''Copy image to custom folder"

```
./.images/${filename}
```

###  3.3. <a name='EmbeddedHeaderLogo'></a>Embedded Header Logo

I have my own logo embedded in the sidebar at the top as an SVG. Replace the SVG for your own.

###  3.4. <a name='Sidebar'></a>Sidebar

- Custom Notion.so colour.
- Removed folder icons
- Can add custom SVG sidebar backgrounds.  (Line 165 is commented out in `notion.css` - uncomment to include background SVG in sidebar.)


###  3.5. <a name='FencesandCodeblocks'></a>Fences and Codeblocks

Is similar to a dark 'Monokai' theme for VSCode.

![Notion Screenshot](https://github.com/IORoot/typora__notion-theme/blob/master/notion/NotionCode.jpg?raw=true)


##  4. <a name='Customising'></a> Customising

Edit the CSS File to create any customisations.

##  5. <a name='Troubleshooting'></a>Troubleshooting

None

<p align="right">(<a href="#top">back to top</a>)</p>


##  6. <a name='Contributing'></a>Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue.
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



##  7. <a name='License'></a>License

Distributed under the MIT License.

MIT License

Copyright (c) 2022 Andy Pearson

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

<p align="right">(<a href="#top">back to top</a>)</p>



##  8. <a name='Contact'></a>Contact

Author Link: [https://github.com/IORoot](https://github.com/IORoot)

<p align="right">(<a href="#top">back to top</a>)</p>

##  9. <a name='Changelog'></a>Changelog

- v1.0.2 Widen the writing space and add media queries to expand on bigger screens.
- v1.0.1 Move SVGs into external files (changing logo), add separate CSS variables for fences and codeblocks, recolouring mermaid SVG strokes.
- v1.0.0 Initial Release.
