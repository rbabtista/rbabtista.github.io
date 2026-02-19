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
  bg_class: "wrapper gradient-8 bg-lines"
  title_tag: "h2"
  title_class: "h6 text-uppercase ls-xl text-white mb-5"
  title: "Welcome to Wish Upon a Fish"
  main_title: "Reimagine. Repurpose. <span class=\"underline-2 underline-gradient-6\"><em>Restore</em></span>."
  main_title_class: "display-1 fs-68 lh-xxs mb-8 text-white"
  buttons:
    - label: "Donate"
      url: "#"
      class: "btn btn-lg btn-white"

# Video Section
video:
  bg_class: "wrapper bg-light"
  vimeo_id: "704880862?h=fea84ae9db&autoplay=1&loop=1&muted=1&autopause=0&title=0&byline=0&portrait=0"
  poster: "/assets/img/photos/movie3.webp"
  alt: "Wish Upon a Fish overview video"  
# About Section
about:
  title_class: "fs-16 text-uppercase text-primary mb-3"
  main_title: "Feeding the World, One Fish at a Time"
  main_title_class: "display-3 mb-5"
  text: "Wish Upon a Fish is a U.S.-based nonprofit reimagining how the world fights hunger by transforming underutilized, invasive fish into a sustainable source of nutrition. Grounded in compassion, environmental stewardship, and pragmatic innovation, the organization aims to fortify the diets of women and children in developing countries with shelf-stable, protein-rich fish powder. By restoring ecosystems, repurposing overlooked resources, and partnering across sectors, Wish Upon a Fish envisions a future where hunger and malnutrition are not inevitable—but solvable."
  images:
    - image: "/assets/img/photos/Asian_Carp_1.webp"
      image2x: "/assets/img/photos/Asian_Carp_1.webp"
    - image: "/assets/img/photos/chowder2-1024x768.webp"
      image2x: "/assets/img/photos/chowder2-1024x768.webp"
    - image: "/assets/img/photos/haiti.webp"
      image2x: "/assets/img/photos/haiti.webp"

# Values Section
values:
  items:
    - number: 1
      title: Our Vision
      text: Reimagine. Repurpose. Restore.
    - number: 2
      title: Our Mission
      text: A US-based nonprofit that uses fish protein powder to fortify the diets of women and children in developing countries

# Join Community Section
join_community:
  title_tag: "Join Our Community"
  title_class: "fs-16 text-uppercase text-white mb-3"
  main_title: "We are <span class=\"underline-2 underline-gradient-6\"><em>trusted</em></span> by over 5000+ clients. Join them now and grow your business."
  main_title_class: "display-3 text-white mb-6"
  button:
    label: "Join Us"
    url: "#"
    class: "btn btn-white"

# Footer
footer:
  style: "dark"
  text_inverse: true
---

<div class="content-wrapper bg-light">
<header class="position-absolute w-100 pt-1">
{% include components/navbar/navbar.html 
    classList="center-nav transparent position-absolute navbar-dark caret-none"
    logoLight=true
    logoBoth=true
    otherClassList="w-100 d-flex ms-auto"
    otherSearch=true
    otherInfo=true
%}
</header>
<!-- /header -->

{% include components/sections/wuaf/hero.html %}
{% include components/sections/wuaf/vimeo.html %}
{% include components/sections/wuaf/about.html %}

{% include components/footer/footer.html style="default" text_inverse=true %}
</div>
