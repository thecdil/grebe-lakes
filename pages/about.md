---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

# {{ site.title }}

<div class="about-narrowed-content">
<figure class="figure text-center">
    <img class="figure-img img-fluid rounded" alt="grebe with black head, red eye, and white neck, floating on lake with it's reflection" src="{{ '/assets/img/2019_CSC_Neil_Paprocki_WEGR_one-5573_feature.jpg' | relative_url }}">
    <figcaption class="figure-caption"><small>Photo from Neil Paprocki</small></figcaption>
</figure>
</div> 

## About Grebes 

Western Grebes (*Aechmophorus occidentalis*) and Clark’s Grebes (*Aechmophorus clarkii*) are iconic waterbirds of western North America that breed in colonies on inland lakes and winter along the Pacific Coast. These species are rare and difficult to count using standard survey methods and, hence, we know relatively little about their population trends or dynamics. 

Western and Clark's Grebes are often counted together in breeding bird surveys because they are difficult to distinguish from a distance and often congregate together and breed within the same nesting colonies. Research studies often group Western and Clark’s Grebes together in their results as *Aechmophorus* grebes or employ a ratio to the group when referring to each species. 

**Can you spot the most obvious difference between these two species according to their photos below?**

{% include feature/image.html objectid="/assets/img/2020_08_04_Clarks_adult_opt.jpg;/assets/img/2020_08_04_DFNWR_western_grebe_opt.jpg" caption="Clark's Grebe;Western Grebe" %}

## Acknowledgements

{% capture note %}
This project is based in summarizing broad survey data.
All care is taken to best communicate the details provided in the data sources, however some interpretation is needed (noted in data comments) and there may be some errors. 
All data can be traced back to the original sources through the citations. 
All the data shared here is publicly available and/or shared with us with the intent to share publicly for this project. 

Please note, exact colony coordinates are not included. 
Western and Clark’s grebes are protected by the Migratory Bird Treaty Act.

If you have any questions about this project or if you have Western and Clark’s Grebe data to share, please contact Anne Yen at <ayen@uidaho.edu>.
{% endcapture %}
<div class="about-narrowed-content">
{% include feature/card.html text=note %}</div>

We are grateful for all our contacts who have shared their grebe data with us and contributed their knowledge and expertise to this project. We are also grateful to our partners and collaborators for making this project possible.

<div class="row row-cols-2 justify-content-center text-center about-narrowed-content">{% for a in site.data.acknowledgements %}
<div class="col p-3"><a href="{{ a.link }}" title="{{ a.title }}"><img class="img-fluid rounded" src="{{ a.src | relative_url }}" alt="{{ a.title }}"></a></div>{% endfor %}
</div>