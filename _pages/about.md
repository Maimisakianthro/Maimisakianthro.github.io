---
layout: about
title: about
permalink: /


# profile:
#  align: right
#  image: prof_pic.jpg
#  image_circular: false # crops the image to make it circular
#  more_info: >
#    <p>555 your office number</p>
#    <p>123 your address street</p>
#    <p>Your City, State 12345</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page


latest_posts:
  enabled: false
  scrollable: false # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Social Anthropologist (DPhil) - religion, colonialism, language, healing<br>
Assistant Professor at Hakubi center, Kyoto University<br>
contact: misaki.mai.3e@kyoto-u.ac.jp

<style>
  /* Hide only the navigation links and the mobile menu toggle button */
  #navbar .navbar-nav,
  #navbar .navbar-toggler,
  #navbar .collapse {
    display: none !important;
  }
  
  /* Keep the header, navbar bar, and your name (navbar-brand) visible */
  header, #navbar, .navbar-brand {
    display: flex !important;
  }
  
  /* Make the first name match the regular weight of the last name */
  .navbar-brand .font-weight-bold {
    font-weight: normal !important;
  }
</style>
<script>
  document.addEventListener("DOMContentLoaded", function () {
    document.querySelectorAll("h2").forEach(function (heading) {
      if (heading.textContent.trim().toLowerCase() === "selected publications") {
        const link = heading.querySelector("a");
        if (link) {
          link.textContent = "publications";
        } else {
          heading.textContent = "publications";
        }
      }
    });
  });
</script>
