+++
# Hero widget.
widget = "hero"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

title = ""
subtitle = ""

# Hero image (optional). Enter filename of an image in the `static/img/` folder.
hero_media = "picture_with_rounded_corners.png"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  #color = "navy"
  
  # Background gradient.
  #gradient_start = "#4bb4e3"
  #gradient_end = "#2b94c3"
  
  # Background image.
  # image = "welcome.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  # text_color_light = true

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.

#[cta]
#  url = "https://arizona.csod.com/ux/ats/careersite/4/home/requisition/5276?c=arizona"
#  label = "Apply now to find out"
#  icon_pack = "fas"
#  icon = "link"
  
#[cta_alt]
#  url = "https://sourcethemes.com/academic/"
#  label = "View Documentation"

# Note. An optional note to show underneath the links.
#[cta_note]
#  label = '<a class="js-github-release" href="https://sourcethemes.com/academic/updates" data-repo="gcushen/hugo-academic">Latest release<!-- V --></a>'
+++

<script type="text/javascript"> <!--
function UnCryptMailto( s )
{
    var n = 0;
    var r = "";
    for( var i = 0; i < s.length; i++)
    {
        n = s.charCodeAt( i );
        if( n >= 8364 )
        {
            n = 128;
        }
        r += String.fromCharCode( n - 1 );
    }
    return r;
}

function linkTo_UnCryptMailto( s )
{
    location.href=UnCryptMailto( s );
}
// --> </script>

Our lab focuses on the expression, splicing, and regulatory roles of coding and
non-coding RNAs, such as circular RNAs, in cardiovascular and stress-related
systems.

Our research integrates high-throughput sequencing, transcriptomics,
and systems biology to uncover how cells respond and adapt at the molecular
level.

We are actively involved in open-source software development, creating tools 
that support reproducible and scalable analyses in RNA research.
