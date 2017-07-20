## Todo:
* Image Resizing
    * SEO image
    * Publicity Stunt "chargify.png"
    * bullseye_yellow.png in Bullseye Framework > Slide 5
* Change image borders
* More graphics

### To Spin Up Locally
See [reveal-md](https://www.github.com/webpro/reveal-md) and [reveal.js](https://www.github.com/hakimel/reveal.js) for installation instructions.
Run `reveal-md traction_summary.md`

### To Spin Up Remotely
Slides can be found at: https://smaroukis.github.io/traction_summary/

#### Updating the Remote
Make necessary edits in `traction_summary.md` (see github.com/webpro/reveal-md) 

Create static html file with `reveal-md traction_summary.md --static .`

Change the title with `ex -sc '%s/reveal-md/Traction: A Summary/g|x' index.html`

`git commit`,`git push`, etc.
