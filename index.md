---
custom_page_title: Leonardo Uieda
banner_image: images/valley-of-fire.jpg
banner_title: 👋🏽 Olá! I'm Leo Uieda
banner_position: top right
banner_subtitle: |
  <span class="nowrap">Geophysicist</span>
  <span class="nowrap">• Educator</span>
  <span class="nowrap">• Scientist</span>
  <span class="nowrap">• Programmer</span>
template: home.html
---

{% import "macros.html" as macros %}


<h2 class="">A bit about me</h2>

<div class="row align-items-center justify-content-center gy-3 mb-4">
<div class="col-9 col-sm-4 order-sm-last">

<img src="https://github.com/leouieda.png" alt="Photo of me from 2019" class="headshot mb-4">

</div>
<div class="col-sm-8">

* Brazilian geophysicist, currently living in the UK
* Creator of methods for imaging the inside of the Earth from measured
  disturbances in the planet's gravity and magnetic fields, from global to
  micro scale 🛰️🔬🌎
* Open-source software developer: [Fatiando a Terra][fatiando], [PyGMT][pygmt],
  and more
* Advocate for openness in the scientific process
* Leader of the [Computer-Oriented Geoscience Lab][compgeolab]
* Proud father and amateur baker

</div>
</div>

{{ macros.button_link(site["about/index"].path|relative_to(page.path), "More about me", icon="far fa-arrow-alt-circle-right", external="false") }}
{{ macros.button_link(site["contact/index"].path|relative_to(page.path), "Contact", type="btn-light", icon="fa fa-envelope", external="false") }}
{{ macros.button_link("https://www.compgeolab.org", "CompGeoLab", type="btn-outline-light", icon="fa fa-external-link-square-alt") }}


[deoes]: https://www.liverpool.ac.uk/earth-ocean-and-ecological-sciences/
[compgeolab]: https://www.compgeolab.org
[pygmt]: https://www.pygmt.org/
[fatiando]: https://www.fatiando.org
[nene]: https://nene.leouieda.com
[ssi-fellowship]: https://software.ac.uk/about/fellows/leonardo-uieda
[swung]: https://softwareunderground.org/
