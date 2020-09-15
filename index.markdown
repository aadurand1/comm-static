---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: splash
header:
  overlay_image: /assets/images/noun_static_line_white.png
  overlay_filter: 0.7 # same as adding an opacity of 0.5 to a black background
  caption: "Image credit: [**CreationsbyElise for the Noun Project**](https://thenounproject.com/)"
#  actions:
#    - label: "Read More"
#      url: "https://google.com"
#      excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
  intro:
    - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
#feature_row:
#   alt: "placeholder image 1"
#    title: "Placeholder 1"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
#  - image_path: /assets/images/...
#    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
#    alt: "placeholder image 2"
#    title: "Placeholder 2"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
#    url: "#test-link"
#  - image_path: /assets/images/...
#    title: "Placeholder 3"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/noun_discussion_bubbles.png
    # image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Dialogue"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/dialogue-archive"
feature_row3:
  - image_path: /assets/images/noun_tuning.png
    # image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Harmony"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/music-archive"

# Include the following to add a 3 pic feature row
# {% include feature_row %}
---

 {% include feature_row id="feature_row2" type="left" %}
 {% include feature_row id="feature_row3" type="right" %}
