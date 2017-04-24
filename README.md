Facebook Comments
=================
>Specifically for the Squarespace Pacific template 

Following these instructions will replace the default Squarespace comment system with Facebook comments. The comments will show only when comments are enabled.

### Usage

1. Copy the facebook-comments.block file to your blocks folder.
2. Copy the blog.item file into your collections folder (replacing the existing one). _If you have a custom blog.item already, just add_ <code>{.comments?}{@|apply facebook-comments.block}{.end}</code> _into the blog.item file where you'd like it to be._
3. **OPTIONAL** Copy the custom.less file into your styles folder. Then add the file to template.conf in the stylesheets array, as seen in the included template.conf. _This adjusts the width and margins of the facebook comments and the margin of the pagination._
4. Add the code from site.region to either the header or footer of your site.region file.

