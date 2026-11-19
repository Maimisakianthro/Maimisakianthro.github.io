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

## publications

### Monographs
* Misaki, M. (2026). Christianity, Colonialism and Indigenous History in French Polynesia. Series: Methodology and History in Anthropology (Oxford: Berghahn Books).

### Peer Reviewed Journal Articles
* Misaki, M. (2024). ‘Liberty of Land, Liberty for God: Between Indigenous Land-Human Relationship and State Sovereignty in French Polynesia’. Journal de la Société des Océanistes. 158-159: 97-109.
* Misaki, M. (2023). ‘The Double Bind of “Shame’ : The Colonial Ramifications in Tahitian Language Revitalization”. Journal of Linguistic Anthropology. 33 (1): 51-71.
* Misaki, M. (2021). ‘Rā'au Mā'ohi, the Sacred Gift of God: the Efficacy and Resurgence of Traditional Herbal Medicine in French Polynesia’. Journal de la Société des Océanistes. 153: 254-58.
* Misaki, M. (2021). ‘Colonial Rupture and Native Continuity in Indigenous Cultural Representations: through Hawaiian Ancient Dance Kahiko’. Dance Research Journal. 53 (1): 44-60.

<style>
  /* Hide only the navigation links and the mobile menu toggle button */
  #navbar .navbar-nav,
  #navbar .navbar-toggler,
  #navbar .collapse {
    display: none !important;
  }
  
  /* Keep the header, navbar bar, and your name (navbar-brand) visible */
  header, #navbar {
    display: flex !important;
  }
  .navbar-brand {
    display: inline-block !important;
  }

  /* Make the first name match the exact weight and font of the last name */
  .navbar-brand,
  .navbar-brand span,
  .navbar-brand .fw-bold,
  .navbar-brand .font-weight-bold,
  .navbar-brand strong,
  .navbar-brand b {
    font-weight: 400 !important;
    font-family: inherit !important;
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
