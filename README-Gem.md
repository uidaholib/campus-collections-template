# Gem

This is a highly customized collection.
The content was created by migrated an much older pre-collectionbuilder collection, that was highly custom.
Most of the features and layout as modeled on the old collection.
However, the new version broke the old URL structure, since it was idiosyncratic to this collection only. 

Each Gem yearbooks has:

- object_location - PDF on libobjects
- cover, small, thumb
- image_spine - spine image
- highlight_images - pages from the book
- "quote" taken from the volume
- "sponsor" - donors
- "signatures" - digital signatures submitted
- archive_link - the pdf uploaded to internet archive. 

## Internet Archive embed

All PDFs are uploaded to Internet Archive.
This allows us to embed the IA reader on the item page. 

IA reader provides flipbook style reading and internal search of the ocr content.

A limitation is that for some reason, the embed does not have a fullscreen view button, even though the reader normally does.
I couldn't figure out a way to get that added to the ui.
I added a "view fullscreen" btn link as a work around. 

The IA api allows us to open the book to a specific page. 
The item page has this option built in as an search query api (using js to write the iframe onto the page after checking the url).
Adding `?page=1` will open the reader to the designated page. 
This is used for random internal links that cite specific pages. 
