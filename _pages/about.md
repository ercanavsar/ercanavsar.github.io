---
layout: about
title: about
permalink: /
subtitle: 

profile:
  align: right
  image: ercan_pic.jpg
  image_circular: true # crops the image to make it circular
  #more_info: <p>DTU Aqua</p> <p>Technical University of Denmark</p> <p>Kongens Lyngby, Denmark</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false 
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts

---

<style>
#navbar .navbar-brand.social a,
#navbar .navbar-brand.social a i,
#navbar .navbar-brand.social a i::before {
  color: var(--global-text-color-light) !important;
  transition: color 0.2s ease;
}

#navbar .navbar-brand.social a:hover,
#navbar .navbar-brand.social a:hover i,
#navbar .navbar-brand.social a:hover i::before {
  color: var(--global-theme-color) !important;
}
  
.navbar-brand.social img {
  opacity: 0.55;
  transition: opacity 0.2s ease;
}
.navbar-brand.social img:hover {
  opacity: 1;
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const map = {
    "Github username": "GitHub",
    "Linkedin username": "LinkedIn",
    "Scholar userid": "Google Scholar",
    "Orcid id": "ORCID",
  };
  document.querySelectorAll(".navbar-brand.social a[title]").forEach(function (a) {
    if (map[a.title]) a.title = map[a.title];
  });
});
</script>


I am a researcher at [DTU Aqua](https://www.aqua.dtu.dk/), the National Institute of Aquatic Resources at the [Technical University of Denmark](https://www.dtu.dk/), where I develop computer vision methods for fisheries and marine applications.

My work focuses on turning underwater and on-board imagery into usable data:
detecting, counting and measuring fish, and making these models reliable enough
for the messy conditions of real surveys and commercial vessels.

Before joining DTU, I worked at Dokuz Eylul University and Cukurova University in Turkey.

**Collaboration:** I am always glad to hear from people interested in working
together. If you are a student looking for a thesis or internship project, or a
researcher or practitioner with a problem where computer vision might help, feel
free to [email me](mailto:erca@aqua.dtu.dk).
