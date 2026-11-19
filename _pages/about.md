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
<br>
contact: misaki.mai.3e@kyoto-u.ac.jp
<br>
## publications
<br>
#### Monographs
* Misaki, M. (2026). Christianity, Colonialism and Indigenous History in French Polynesia. Series: Methodology and History in Anthropology (Oxford: Berghahn Books).

#### Journal Articles
* Misaki, M. (2024). ‘Liberty of Land, Liberty for God: Between Indigenous Land-Human Relationship and State Sovereignty in French Polynesia’. Journal de la Société des Océanistes. 158-159: 97-109.
* Misaki, M. (2023). ‘The Double Bind of “Shame’ : The Colonial Ramifications in Tahitian Language Revitalization”. Journal of Linguistic Anthropology. 33 (1): 51-71.
* Misaki, M. (2021). ‘Rā'au Mā'ohi, the Sacred Gift of God: the Efficacy and Resurgence of Traditional Herbal Medicine in French Polynesia’. Journal de la Société des Océanistes. 153: 254-58.
* Misaki, M. (2021). ‘Colonial Rupture and Native Continuity in Indigenous Cultural Representations: through Hawaiian Ancient Dance Kahiko’. Dance Research Journal. 53 (1): 44-60.

#### Recent Talks
* 2026 ‘Spiritualising Environmental Crisis: Eco-Theology and Religious Resistance in Environmental Activism’ presented at Kyoto University
* 2026  ‘Between Soil and State: Bridging Divergent Visions of Independence through Collective Dreaming in Māòhi Nui’ presented at the European Association of Social Anthropologists Conference 2026, Poznan 
* 2026  ‘A Book Launch and Discussion of Christianity, Colonialism and Indigenous History in French Polynesia: Advance into the Past’ at University of Warsaw
* 2026 ‘Reenactable Past as Sovereign Future?: Pro-Independence Narratives of Māòhi Nationalism in French Polynesia’ presented at the Department of Anthropology, University of Hawaii at Manoa
* 2025 ‘Keeping the Ties Together: the Role of Māòhi Missionaries in the Era of Secularisation in French Polynesia’ presented at 14th European Society for Oceanists Conference, Luzern
* 2025 ‘Remixing “Localness”: An Analysis of French-Tahitian Code-Switching in DJ Remixes’ presented at Association for Social Anthropology in Oceania Annual Conference, Nadi 

<style>
#navbar .navbar-nav,
  #navbar .navbar-toggler,
  #navbar .collapse {
    display: none !important;
  }
  header, #navbar {
    display: flex !important;
  }
  .navbar-brand {
    display: inline-block !important;
    font-weight: 300 !important;
  }
  .navbar-brand * {
    font-weight: inherit !important;
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
