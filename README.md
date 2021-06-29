![Notion Screenshot](./notion/Notion.jpg)
![Notion Screenshot](./notion/NotionPattern.jpg)

# Typora theme - Notion.so

My little attempt at recreating the notion.so theme and functionality through pure CSS themes.

## Main feature - Top image full width image

Place an image in the very first paragraph of the page and it will be converted into a full-width, 30vh sized image across the top of the page. 
The image is aligned top-center. and the rest will be cropped. You can change this to be center-center in the CSS.


## Hidden image folder

Put all images in a 'hidden' folder called `.images`at the same directory level as the markdown file by selecting the option for images :  ''Copy image to custom folder"

```
./.images/${filename}
```

## Embedded Header Logo

I have my own logo embedded in the sidebar at the top as an SVG. Replace the SVG for your own.

## Sidebar

- Custom Notion.so colour.
- Removed folder icons
- Can add custom SVG sidebar backgrounds.  (Line 165 is commented out in `notion.css` - uncomment to include background SVG in sidebar.)


## Fences and Codeblocks

Is similar to a dark 'Monokai' theme for VSCode.

![Notion Screenshot](./notion/NotionCode.jpg)

## Changelog

- v1.0.1 Move SVGs into external files (changing logo), add separate CSS variables for fences and codeblocks, recolouring mermaid SVG strokes.
- v1.0.0 Initial Release.