---
title: Gem Coloring Books
layout: page
permalink: /coloring.html
---

## Gem Coloring Books
{:.display-3}

<div class="row">
<div class="col-md-8" markdown="1">

Get out your crayons, colored pencils, and markers and download our free Coloring Books!

In honor of the annual [#ColorOurCollections week](http://library.nyam.org/colorourcollections/about/) in February, we invite you to redecorate our collections. The [New York Academy of Medicine launched the idea](https://nyamcenterforhistory.org/2016/01/06/colorourcollections-february-1-5/) to merge the adult coloring book craze with digital collections in 2016, and libraries around the world joined in. This is a great opportunity to highlight our collections and have some fun!

To share some University of Idaho themed coloring, we created coloring books featuring illustrations from early editions of the University of Idaho's yearbook, The Gem of the Mountains. You can download ready to print PDFs of the coloring books below.

Go wild and Color Our Collections! Please remember to share a picture of your coloring with us @UofILibrary and the hashtag #ColorOurCollections.

Happy coloring!

{% include feature/image.html objectid="uidaho_gem_coloringbook_2016;uidaho_gem_coloringbook_2017;uidaho_gem_coloringbook_2018" %}

</div>
<div class="col-md-4 p-4">
<div class="card"><div class="card-body">
<h3 class="display-5 fs-1">Coloring Pages</h3>
<p>Click to download single page images:</p>
<div class="text-center">
{% for p in site.data.gem-coloring-pages %}
<figure class="figure mb-4">
    <a href="{{ p.image }}">
        <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 3 2'%3E%3C/svg%3E" data-src="{{ p.image_small }}" alt="{{ p.title | escape }}" class="figure-img img-fluid rounded lazyload shadow">
    </a>
    <figcaption class="figure-caption text-center">{{ p.title }}</figcaption>
</figure>{% endfor %}
</div>
</div></div>
</div>
</div>


