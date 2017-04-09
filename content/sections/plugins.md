+++
weight = 40
title = "Plugins (i.e Shortcodes)"
link_text = "Plugins"
# hidden = true
+++

### What are they

As explained in the [markdown section](#what-are-the-and-about) above shortcodes can be *plugged* into the middle of your markdown files to give them added functionality.  Each shortcode is invoked with either a {{</* *name* */>}} or {{%/* *name* */%}} and possibly a closing {{</* /*name* */>}} if they enclose some more content.   It all depends on the nature of the shortcode.

{{< bookmark "test" "This" >}} landing page theme currently has 12 shortcodes that you might *plugin* and will likely have more in the future (make your requests).  Below they are documented.  Most shortcodes have one or more parameters that follow the *name*.  The shortcodes are listed below with an explanation use case and are linked to a documentation page with details of how to use them.  But many times the easist way is just to see them in action in the markdown and copy, paste and edit to suit.

* {{< link url="#modal-avatar" text="avatar" display="modal" >}}  - creates a large circle icon from an image  
* {{< link url="#modal-bookmark" text="bookmark" display="modal" >}}  places a bookmark on the page that to be linked to
* {{< link url="#modal-box" text="box" display="modal" >}} - wraps content in a flex box.  Useful for things like groups of buttons
* {{< link url="#modal-contact" text="contact" display="modal" >}} - takes contact information and makes a contact "card"
* {{< link url="#modal-disqus" text="disqus" display="modal" >}} - places a disqus comments section in the page
* {{< link url="#modal-embed" text="embed" display="modal" >}} - embed content from other sites that use "iframes" like youtube and google maps
* {{< link url="#modal-format" text="format" display="modal" >}} - wrap any content in custom classes.  Allows end user custom styling with  the custom css file(s)
* {{< link url="#modal-image" text="image" display="modal" >}} - places and image on the page with optional title and caption and modal click to enlarge
* {{< link url="#modal-jotform" text="jotform" display="modal" >}} - opens up a jotform by form id from jotform.com
* {{< link url="#modal-link" text="link" display="modal" >}} - creates custom links beyond simple markdown link including buttons
* {{< link url="#modal-lorem" text="lorem" display="modal" >}}lorem -  easily insert dummy lorem text when flessing out a site prototype
* {{< link url="#modal-social" text="social" display="modal" >}} -  add bar of social icons and links  

There will be a shortcode to make a gallery of photos from a directory of photos but this has not been automated yet and is only shown here in example.  It will be documented when it's available.
{{< gallery-photos >}}
