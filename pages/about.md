---
title: About
layout: page
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

## About 
{:.display-3}

<div class="mb-4 mx-5">
    <figure>
        <blockquote class="blockquote fs-4">
            <p class="mb-0">The Gem of the Mountains marks the beginning of what we hope will be a series of profitable publications for our beloved institution ... [If] it adds the least beauty to the crown of history that rests upon the fair head of our Alma Mater ... then we feel that it bears its name well.</p>
        </blockquote>
        <figcaption class="blockquote-footer text-end fs-4"><cite title="Source Title"><a href="{{ '/items/uidaho_gem_1903.html?page=14' | relative_url }}">Foreword to the first Gem, 1903</a></cite></figcaption>
    </figure>
</div>

<div class="row">
<div class="col-md-8" markdown="1">

## The Gem of the Mountains
{:.display-5}

*The Gem of the Mountains* was the official yearbook of the University of Idaho from 1903 to 2004. 
During this time, the Gem recorded the [traditions]({{ '/items/uidaho_gem_1916.html?page=14' | relative_url }}), [triumphs]({{ '/items/uidaho_gem_1955.html?page=30' | relative_url }}), [controversies]({{ '/items/uidaho_gem_1980.html?page=120' | relative_url }}), [histories]({{ '/items/uidaho_gem_1955.html?page=82' | relative_url }}), and [achievements]({{ '/items/uidaho_gem_1950.html?page=246' | relative_url }}) of the University, documenting both the [curricular]({{ '/items/uidaho_gem_1965.html?page=12' | relative_url }}) and [extra-curricular]({{ '/items/uidaho_gem_1981.html?page=214' | relative_url }}) lives of its [students]({{ '/items/uidaho_gem_1934.html?page=112' | relative_url }}), [faculty]({{ '/items/uidaho_gem_1906.html?page=40' | relative_url }}), and [administrators]({{ '/items/uidaho_gem_1948.html?page=68' | relative_url }}).

From a school of just [23 faculty members]({{ '/items/uidaho_gem_1903.html?page=26' | relative_url }}) and four buildings to 2004's thoroughly [modern university]({{ '/items/uidaho_gem_2000.html?page=40' | relative_url }}), the University has undergone a tremendous evolution, and the yearbooks bear witness to these changes. Two aspects remain constant, however, among the many physical, cultural, and stylistic changes documented: the [beauty of the campus]({{ '/items/uidaho_gem_1932.html?page=20' | relative_url }}) and the [resilience of the Idaho spirit]({{ '/items/uidaho_gem_1944.html?page=8' | relative_url }}).

## The Collection
{:.display-5}

The Gem of the Mountains Digital Yearbook Collection was digitized and processed for online viewing during the academic year 2011-2012 by staff and librarians in the digital initiatives department of the University of Idaho Library.

Over 100 volumes — constituting more than 33,000 pages and 3 terabytes worth of image files — were broken apart, sliced at their bindings and fed through a feed scanner to produce the collection of PDFs, images, and selections here before you.

Famous Vandals can be found within the collection (see feature at right), as well as family members, former students, and beloved professors.

## The Coloring Book
{:.display-5}

In honor of #ColorOurCollections Digital Initiatives created a free downloadable coloring book featuring illustrations from the Gem. To download and learn more, please visit the [Coloring page]({{ '/coloring.html' | relative_url }}).

## Credits
{:.display-5}

Editor: Devin Becker

Digital Production Managers: Kevin Dobbins and Estelle Sertich

Student Assistants: Sierra Magnusson, Jordan Proctor, Keila Dubois, Lynette Andersen, Andrew Rowe, Kendra Chilbert

2023 Collection Migration: Evan Peter Williamson

</div>
<div class="col-md-4 p-4">
<div class="card"><div class="card-body">
<h2 class="display-5 fs-1">Famous Vandals</h2>
<div class="text-center">
{% for f in site.data.famous-vandals %}
<figure class="figure mb-4">
    <a href="{{ '/items/' | relative_url }}uidaho_gem_{{ f.yearbook }}.html?page={{ f.page }}">
        <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 3 2'%3E%3C/svg%3E" data-src="{{ f.image }}" alt="yearbook photo of {{ f.name | escape }}" class="figure-img img-fluid rounded lazyload">
    </a>
    <figcaption class="figure-caption text-center">{{ f.name }} <br>{{ f.description }}</figcaption>
</figure>{% endfor %}
</div>
</div></div>
</div>
</div>
