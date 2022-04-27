# Markdown-CustomCSS-GoogleStyle

This is wrote based on VSCode+MarkdownPreviewEnhanced.

Most of code just copy the source code from [here](https://developers.google.com/protocol-buffers)

## Install

You need to install 2 fonts: "Product Sans", "Roboto".
Both of them are easy to get from the internet.

Then open VSCode:
1. cmd+shift+p
2. Enter "Custom CSS"
3. Replace origin text with Style.css

> Style2.css is an optimized version which I'm using.

## Feature
- Custom Head1, Head2, Head3.
- Limit width to 862px.
- Custom code chunks and reference chunks, add warning chunks, and they are all adapt to first-level lists.
  ```
  <warning>
  warning content.
  </warning>
  ```
- Image with shadow, you can also add image name
  ```
  <div align=center><img src="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png" style="zoom:60%"></div>
  <div align=center class="imgname">Image Name</div>
  ```

## Illustration
![pic1](./pic1.png)
![pic2](./pic2.png)
