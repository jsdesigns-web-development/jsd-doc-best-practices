# Creating Favicons

1. Design favicon graphic with Adobe Illustrator or Photoshop.
2. Export 1000px x 1000px PNG file of favicon graphic.
3. Upload image file to https://www.favicon-generator.org/
  - Select `Generate icons for Web, Android, Microsoft, and iOS (iPhone and iPad) Apps`
  - Select `Maintain Image Dimensions (don't resize to be square)`
4. Download the generated favicon zip file to your computer. Extract contents to desired folder.
5. Copy the provided code to each HTML document.

### Create 128x128 favicon
1. Duplicate `apple-icon-180x180.png`, naming the new file `favicon-128.png`.
2. Open `favicon-128.png` with Photoshop and resize to 128px x 128px, then save.
3. Update each HTML file with:

  ```
  <meta property="og:image"              content="https://example.com/static/img/favicon/favicon-128.png" />
  <meta property="og:image:secure_url"   content="https://example.com/static/img/favicon/favicon-128.png" />
  <meta property="og:image:type"         content="image/png" />
  <meta property="og:image:alt"          content="description of favicon image" />

  ...

  <meta property="twitter:image"         content="https://example.com/static/img/favicon/favicon-128.png" />
  <meta property="twitter:image:alt"     content="description of favicon image" />
  ```
