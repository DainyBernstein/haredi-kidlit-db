# Narrative:

I started working on this project as part of a [certificate course](https://www.jtsa.edu/hidden-page/judaica-librarianship-certification/) in Judaica Librarianship through the Association of Jewish Libraries (AJL) and the Jewish Theological Seminary (JTS). 

As a researcher of American Haredi (ultra-Orthodox Jewish) children's literature for almost a decade, I had been gathering bibliographic information about these texts and maintaining several spreadsheets with relevant information. 

A significant portion of my time that was supposed to be devoted to research and writing was spent hunting down details like original publication dates, relationships between publishers when more than one is listed for a single book, etc. Many of these texts are cataloged at minimal level in OCLC, some have errors, and others have not been cataloged anywhere that I could find.

A few years ago, I realized that the work I'd done collecting this bibliographic information could be valuable to other scholars. From that point, I began formatting my metadata with an eye toward sharing it publicly. 

Though I submitted several fellowship and grant applications to various organizations, the project was never funded, and I couldn't justify taking time away from writing and pursuing publication to work on it in my free time, primarily since academic job search and tenure committees tend not to view digital projects in the same category as journal publications. 

Now, working as a librarian, I have access to several tools that were unavailable to me before (like OCLC access through my employer). The [AJL/JTS certificate program's](https://www.jtsa.edu/hidden-page/judaica-librarianship-certification/) internship requirement also gave me a reason to go back to this project, and a framework of mentorship to help me learn the digital skills I needed, which I'd had a rudimentary understanding of before.

Using CollectionBuilder-GH (see below), I've been able to learn a tremendous amount in a relatively short time, while still working full-time. Now that I've completed the internship and the certificate program, I have a solid grounding in what I need to do. But playing around in this repo has meant making lots of mistakes, trying to fix them, then trying to fix what I broke through the attempted fix, etc. etc. I decided to revert this repo back to the last commit before I truly messed things up. 

I also decided to switch to [CollectionBuilder's template](https://collectionbuilder.github.io/templates.html) which is their "most robust and flexible," the CSV template, because the amount of items in this collection\* is higher than CB-GH's basic ability to host. I have over 4000 books, approximately 1000 people (authors, illustrators, translators, etc.) and about 120 publishers so far, each of which will be a separate item in the collection, making CB-CSV the better choice now. 

Switching to a new repo also gives me the chance to start fresh rather than building over what I started when I was just learning, trying to figure out how to implement my vision for search and facet functions, multiple browse pages that each operate slightly differently, linked data, and more. 

When the new repo / site is ready, I will link it here.

If you have any thoughts about the content, format, or function of this project, please do get in touch!

I'm building this from the perspective of a researcher-turned-librarian, and I could always use other perspectives.

*\*Note: These books are not all together physically in one collection. "Collection" in my case basically means bibliographic data, not physical items.*

## Some of the tools I've used so far:

- GitHub (obviously), including GitHub desktop
- OCLC Connexion
- MarcEdit
- Visual Studio Code
- OpenRefine
  - built-in reconciliation with Wikidata
  - Library of Congress and VIAF reconciliation using [codeforkjeff's reconciliation services](https://github.com/codeforkjeff/conciliator)

# CollectionBuilder-GH

A project to generate a free and simple digital collection site using [GitHub Pages](https://pages.github.com/) given:

- a CSV of collection metadata
- a folder of JPEG images, PDF documents, MP3s, or links to videos hosted on YouTube or Vimeo

Visit the [demo site](https://collectionbuilder.github.io/collectionbuilder-gh/).

## Build a Digital Collection

Gather your digital objects together and create your metadata using the [CollectionBuilder-GH Metadata Template](https://docs.google.com/spreadsheets/d/1Uv9ytll0hysMOH1j-VL1lZx6PWvc1zf3L35sK_4IuzI/copy) and [metadata docs](https://collectionbuilder.github.io/cb-docs/docs/metadata/gh_metadata/). 

Then click the green "use this template" button to create your repository, and add your metadata and configure the repository to fit your collection and settings following the [CollectionBuilder Docs](https://collectionbuilder.github.io/cb-docs/). 

Please feel free to ask questions in the main [CollectionBuilder discussion forum](https://github.com/CollectionBuilder/collectionbuilder.github.io/discussions).

**Note:** 
Since CollectionBuilder-GH uses [GitHub Pages](https://pages.github.com/), it is only suitable for small collections, with lower resolution images. 
GitHub repositories are limited to 1GB.
For larger collections or those that require more customization, check out the [CollectionBuilder-CSV](https://github.com/CollectionBuilder/collectionbuilder-csv) template.

## CollectionBuilder-GH Quick Tutorial

Follow the [CollectionBuilder-GH Walkthrough](https://collectionbuilder.github.io/cb-docs/docs/walkthroughs/gh-walkthrough/) to set up a collection quickly using demo metadata and objects. 

- [Demo Metadata](https://docs.google.com/spreadsheets/d/1x48Te3duPAxh53foEihQVKTfCKUjaCCbH7TrMMd_yU4/copy)
- [Demo Objects](https://www.lib.uidaho.edu/collectionbuilder/demo-objects.zip)

## Teaching and Learning with CollectionBuilder-GH

CollectionBuilder-GH is intended as a simple template for hands-on teaching about digital libraries.
It can be used in a workshop setting to take participants through digitization and metadata creation, to having a live collection site hosted on GitHub.

CollectionBuilder-GH aims to be well documented and easy to configure by following the documentation, with the potential to scaffold learning of a multitude of transferable digital and data skills.
A project in "minimal computing", it provides a depth of learning opportunities, allowing users to take complete ownership over the project and make their work open to the world.

Learn about:

- Git and GitHub basics
- [Markdown](https://guides.github.com/features/mastering-markdown/), plaintext writing and content creation
- HTML, CSS, and JavaScript literacy
- command line literacy
- GitHub collaboration and project management
- [Jekyll](https://jekyllrb.com/) basics
- working in the Open, open source and open data
- digital libraries concepts such as "collections as data", minimal computing, data-driven design

> We prefer commonly understood formats (such as CSV spreadsheets over YAML), and convention over configuration (follow the example over learn all the options).

----------

## CollectionBuilder 

<https://collectionbuilder.github.io/>

CollectionBuilder is a project of University of Idaho Library's [Digital Initiatives](https://www.lib.uidaho.edu/digital/) and the [Center for Digital Inquiry and Learning](https://cdil.lib.uidaho.edu) (CDIL) following the [Lib-Static](https://lib-static.github.io/) methodology. 
Powered by the open source static site generator [Jekyll](https://jekyllrb.com/) and a modern static web stack, it puts collection metadata to work building beautiful sites.

The basic theme is created using [Bootstrap](https://getbootstrap.com/).
Metadata visualizations are built using open source libraries such as [DataTables](https://datatables.net/), [Leafletjs](http://leafletjs.com/), [Spotlight gallery](https://github.com/nextapps-de/spotlight), [lazysizes](https://github.com/aFarkas/lazysizes), and [Lunr.js](https://lunrjs.com/).
Object metadata is exposed using [Schema.org](http://schema.org) and [Open Graph protocol](http://ogp.me/) standards.

Questions can be directed to **collectionbuilder.team@gmail.com**

## License

CollectionBuilder documentation and general web content is licensed [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/). 
This license does *NOT* include any objects or images used in digital collections, which may have individually applied licenses described by a "rights" field.
CollectionBuilder code is licensed [MIT](https://github.com/CollectionBuilder/collectionbuilder-csv/blob/master/LICENSE). 
This license does not include external dependencies included in the `assets/lib` directory, which are covered by their individual licenses.
