# hugo-image-processing-shortcode
Hugo image processing from static folder with shortcode (most basic example).

For this to work, images need to be in the static folder (static/images) and the following module mounts added to your themes config file (note below is for .toml)

---- config.toml -----

  [[module.mounts]]
    source = "static/images"
    target = "assets/images"
 
---- config.toml end -----
    
    
 And the shortcode:
 
 {{< image src="/images/name.jpg"  alt="desc of image" >}}

 
