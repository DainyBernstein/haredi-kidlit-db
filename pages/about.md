---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://cdil.lib.uidaho.edu/images/palouse_sm.jpg" %}

{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

## About the Collection

I started working on this project as part of a certificate course in Judaica Librarianship through the Association of Jewish Libraries (AJL) and the Jewish Theological Seminary (JTS).

As a researcher of American Haredi (ultra-Orthodox Jewish) children's literature for almost a decade, I had been gathering bibliographic information about these texts and maintaining several spreadsheets with relevant information.

A significant portion of my time that was supposed to be devoted to research and writing was spent hunting down details like original publication dates, relationships between publishers when more than one is listed for a single book, etc. Many of these texts are cataloged at minimal level in OCLC, some have errors, and others have not been cataloged anywhere that I could find.

A few years ago, I realized that the work I'd done collecting this bibliographic information could be valuable to other scholars. From that point, I began formatting my metadata with an eye toward sharing it publicly.

Though I submitted several fellowship and grant applications to various organizations, the project was never funded, and I couldn't justify taking time away from writing and pursuing publication to work on it in my free time, primarily since academic job search and tenure committees tend not to view digital projects in the same category as journal publications.

Now, working as a librarian, I have access to several tools that were unavailable to me before (like OCLC access through my employer). The AJL/JTS certificate program's internship requirement also gave me a reason to go back to this project, and a framework of mentorship to help me learn the digital skills I needed, which I'd had a rudimentary understanding of before.

Using CollectionBuilder-GH (see below), I've been able to learn a tremendous amount in a relatively short time, while still working full-time. Now that I've completed the internship and the certificate program, I have a solid grounding in what I need to do. But playing around in this repo has meant making lots of mistakes, trying to fix them, then trying to fix what I broke through the attempted fix, etc. etc. I decided to revert this repo back to the last commit before I truly messed things up.

I also decided to switch to CollectionBuilder's template which is their "most robust and flexible," the CSV template, because the amount of items in this collection* is higher than CB-GH's basic ability to host. I have over 4000 books, approximately 1000 people (authors, illustrators, translators, etc.) and about 120 publishers so far, each of which will be a separate item in the collection, making CB-CSV the better choice now.

Switching to a new repo also gives me the chance to start fresh rather than building over what I started when I was just learning, trying to figure out how to implement my vision for search and facet functions, multiple browse pages that each operate slightly differently, linked data, and more.

When the new repo / site is ready, I will link it here.

If you have any thoughts about the content, format, or function of this project, please do get in touch!

I'm building this from the perspective of a researcher-turned-librarian, and I could always use other perspectives.

*Note: These books are not all together physically in one collection. "Collection" in my case basically means bibliographic data, not physical items.

# About CollectionBuilder

This site is generated using [CollectionBuilder-GH](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPG images or PDF documents

The template repository features four objects from the University of Idaho Library's [Digital Collections](https://www.lib.uidaho.edu/digital). 

For full details of creating your own collection site, visit [CollectionBuilder Documentation](https://collectionbuilder.github.io/cb-docs/)!
