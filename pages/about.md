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

{% include feature/image.html objectid="/assets/img/2020_08_04_Clarks_adult_opt.jpg;/assets/img/2020_08_04_DFNWR_western_grebe_opt.jpg" caption="Clark's Grebe;Western Grebe" alt="bird floating low in the water with red eye with brown feathers;bird floating low in the water with dark feathers and red eye"%}

## About the Project

This interactive website provides access to a summary of Western and Clark's Grebe breeding data to better document population status and regional variation in abundance.

Anne Yen originally developed the database in 2023 during her graduate research at University of Idaho supervised by Courtney Conway and Kerri Vierling ([College of Natural Resources](https://www.uidaho.edu/natural-resources), Fish and Wildlife Sciences).
Yen's related masters thesis [Western and Clark's Grebes: Impacts of Weather on Nest Fate and a Range-wide Summary of Threats to Breeding Colonies](https://verso.uidaho.edu/esploro/outputs/996671146401851) was published in 2024.

The website was developed as part of a [Center for Digital Inquiry and Learning](https://cdil.lib.uidaho.edu/) Graduate Student Fellowship supported by Evan Peter Williamson (University of Idaho Library).

<div class="about-narrowed-content">{% include feature/card.html header="Citation" text="Yen, A., C. J. Conway. K. T. Vierling, and E. P. Williamson. 2025. Western and Clark's Grebe Breeding Lakes of North America. Website. University of Idaho Library, Moscow, Idaho. DOI: https://doi.org/10.60841/EVS7-B505" %}</div>

## Data

Grebe breeding lakes can be browsed by [record information]({{ '/browse.html' | relative_url }}), [map]({{ '/map.html' | relative_url }}), [characteristics]({{ '/facets.html' | relative_url }}), and [table]({{ '/data.html' | relative_url }}).
Each individual lake record contains information about the location, a summary of survey data, a list of surveys, and a list of sources.
The source references can be used to find additional details and the original data.

If you have any questions about this project or if you have Western and Clark’s Grebe data to share, please contact Anne Yen at <ayen@uidaho.edu>.

{% capture note %}
This project is based in summarizing broad survey data.
All care is taken to best communicate the details provided in the data sources, however some interpretation is needed (noted in data comments) and there may be some errors.

All data can be traced back to the original sources through the citations. 
All the data shared here is publicly available and/or shared with us with the intent to share publicly for this project. 

Please note, exact colony coordinates are not included. 
Western and Clark’s grebes are protected by the Migratory Bird Treaty Act.

{% endcapture %}
<div class="about-narrowed-content">
{% include feature/card.html text=note %}</div>

## Acknowledgements

We are grateful for all our contacts who have shared their grebe data with us and contributed their knowledge and expertise to this project. We are also grateful to our partners and collaborators for making this project possible.

<div class="row row-cols-2 justify-content-center text-center about-narrowed-content">{% for a in site.data.acknowledgements %}
<div class="col p-4"><a href="{{ a.link }}" title="{{ a.title }}"><img class="img-fluid rounded" src="{{ a.src | relative_url }}" alt="{{ a.title }}"></a></div>{% endfor %}
</div>