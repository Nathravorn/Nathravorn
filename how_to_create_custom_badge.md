1. Take a screenshot of the logo you wish to create a badge for.
2. Go to https://www.photopea.com/. Make the background transparent and crop the logo. Save it as a png with high compression and a resolution of about 50x50.
3. Go to https://b64.io/ to encode the image to base64. The base64 size should not be higher than 2-3kB or you risk the url being too long. Copy the base64 link to your clipboard.
4. Go to https://meyerweb.com/eric/tools/dencoder/, paste the base64 url and click "Encode".
5. Add the badge to your markdown file as follows, replacing TEXT, COLOR and URL by the corresponding value (COLOR should be the hex code for the color, e.g. ffffff).

```html
<img alt="TEXT" src="https://img.shields.io/badge/-TEXT-COLOR.svg?logoColor=white&logo=URL"/>
```
