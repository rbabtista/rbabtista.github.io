---
layout: default
title: About
permalink: /about/
custom_color:
custom_font:
scroll_top_btn:
  enable: true

# Header / Hero Section
hero:
  title: "Hello! This is Wish Upon a Fish"
  subtitle: "A US-based nonprofit that uses fish protein powder to fortify the diets of women and children in developing countries"
  bg_image: /assets/img/photos/orange-fish.webp
  bg_color: "bg-gray"

# Who We Are Section
who_we_are:
  title: "In summary"
  #  subtitle: "We are a digital and branding company that believes in the power of creative strategy and along with great design."
  text: "About 1 in 9 people worldwide suffer from a low intake of nutrients and vitamins due to carbohydrate rich diets. Protein deficiencies cause poor health outcomes such as anemia, stunting and/or wasting. Fortified foods are the best way to treat and prevent these conditions. Use of invasive species is a promising, but overlooked strategy to address global malnutrition. The Mississippi River and its tributaries have an enormous supply of Asian carp that are available for humanitarian aid. Fish / soy powder is a healthy and cost-effective way to fortify local foods, thus increasing the nutritional benefits of women and children in developing countries."
  icon: "megaphone"
  images:
    - src: /assets/img/photos/Asian_Carp_1.webp
      src2x: /assets/img/photos/Asian_Carp_1.webp
    - src: /assets/img/photos/carp.webp
      src2x: /assets/img/photos/carp.webp
      
services:
  bg_class: "wrapper bg-dark text-inverse"
  title_tag: "Rationale"
  title_class: "fs-16 text-uppercase text-white mb-3"
  main_title: "Why fish powder? A practical, compassionate, and scalable solution."
  main_title_class: "display-3 text-white mb-10"
  service_items:
    - icon: "/assets/img/icons/lineal/users.svg"
      title: Humanity
      text: "New ideas are required to feed ~8 billion people worldwide, yet invasive species have been overlooked as a valuable source of protein. Let’s be creative."

    - icon: "/assets/img/icons/lineal/world.svg"
      title: Planet
      text: "Mother earth is groaning, partly due to invasive species. Removal is a pathway to ecological restoration for native fish—one that also benefits people and local communities. Let’s be environmental stewards."

    - icon: "/assets/img/icons/lineal/fish.svg"
      title: Food
      text: "Over 730 million people experience global hunger, yet the U.S. has an overly abundant and underutilized supply of freshwater fish. Protein-rich fish is a better restoration strategy than starchy foods. Let’s be pragmatic."

    - icon: "/assets/img/icons/lineal/heart-handshake.svg"
      title: Mercy
      text: "Jesus showed compassion to individuals with the greatest needs and fewest resources, and used fish in a miraculous way to feed thousands. Over 2 billion humans are malnourished, including many women and children in developing countries. Let’s practice altruism."

    - icon: "/assets/img/icons/lineal/cpu.svg"
      title: Technology
      text: "Modern equipment safely processes large amounts of fish. After removing by-products, the flesh is mixed with soy and repurposed into a low-moisture powder—no refrigeration or freezing needed—reducing transport costs. The protein concentrate can fortify local foods eaten by local people. Let’s be logical."

    - icon: "/assets/img/icons/lineal/users-group.svg"
      title: Partnerships
      text: "Global problems require global thinking. Solving the food crisis at home and abroad demands multiple approaches—reimagine fish powder as one of them. Success requires cooperation with domestic and international partners and support from public and private funding. Let’s do this."
      
# Team Section
team:
  title: "Board of Directors"
  #  subtitle: "Our Team"
  bg_color: "bg-light"

team2:
  title: "Collaborators"
  #  subtitle: "Our Team"
  bg_color: "bg-light"
---
<div class="content-wrapper">
<header class="wrapper bg-gray">
{% include components/navbar/navbar.html 
    classList="center-nav transparent navbar-light"
    otherClassList="w-100 d-flex ms-auto"
    otherLanguageSelect=true
    otherBtn=true
    otherBtnClassList="btn btn-sm btn-primary rounded-pill"
    otherBtnText="Contact"
    otherBtnLink="/contact"
%}
</header>
<!-- /header -->

{% include components/sections/about/hero.html %}
{% include components/sections/about/who-we-are.html %}
{% include components/sections/about/services.html %}
{% include components/sections/about/team.html %}
{% include components/sections/about/team2.html %}

{% include components/footer/footer.html 
  style="default"
  container_padding="pt-16 pt-md-18 pb-13 pb-md-15"
  bg_color="bg-dark"
  text_color="text-inverse"
%}
</div>
