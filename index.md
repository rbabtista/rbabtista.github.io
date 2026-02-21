---
layout: default
title: Wish Upon a Fish
permalink: /
custom_color: primary
custom_font: space
box_layout: true
bg_light: true

# Hero Section
hero:
  bg_image: /assets/img/photos/orange-fish.webp
  bg_class: "wrapper gradient-8 bg-lines"
  title_tag: "h2"
  title_class: "h6 text-uppercase ls-xl text-white mb-5"
  title: "Welcome to Wish Upon a Fish"
  main_title: "Reimagine. Repurpose. Restore."
  main_title_class: "display-1 fs-68 lh-xxs mb-8 text-white"
  buttons:
    - label: "Donate"
      url: "https://givebutter.com/wishuponafish"
      class: "btn btn-lg btn-white"

# Video Section
video:
  bg_class: "wrapper bg-light"
  vimeo_id: "704880862?h=fea84ae9db&autoplay=1&loop=1&muted=1&autopause=0&title=0&byline=0&portrait=0"
  alt: "Wish Upon a Fish overview video"

# About Section
about:
  title_class: "fs-16 text-uppercase text-primary mb-3"
  main_title: "Feeding the World, One Fish at a Time"
  main_title_class: "display-3 mb-5"
  text: "Wish Upon a Fish is a charitable organization that reimagines global malnutrition using Asian carp, an overly abundant but underutilized invasive species in U.S. waterways. Grounded in compassion, environmental stewardship, and pragmatic innovation, this nonprofit aims to fortify the diets of women and children in developing countries with a shelf-stable, protein-rich fish powder. By restoring ecosystems, repurposing overlooked resources, and partnering across sectors, Wish Upon a Fish is more than a creative solution for undernourishment – it’s a moral imperative. Please join us in the fight."
  images:
    - image: "/assets/img/photos/haiti.webp"
      image2x: "/assets/img/photos/haiti.webp"

# Footer
footer:
  style: "dark"
  text_inverse: true
  cta: false
  newsletter: false
---

<div class="content-wrapper bg-light">
<header class="position-absolute w-100 pt-1">
{% include components/navbar/navbar.html 
    classList="center-nav transparent position-absolute navbar-dark caret-none"
    logoLight=true
    logoBoth=true
    otherClassList="w-100 d-flex ms-auto"
    otherInfo=false
%}
</header>
<!-- /header -->

{% include components/sections/wuaf/hero.html %}
{% include components/sections/wuaf/about.html %}

{% include components/footer/footer.html style="default" text_inverse=true %}
</div>
