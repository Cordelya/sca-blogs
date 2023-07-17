# The SCA Blogs Webring

This is the application code for the [SCA Blogs Webring](https://cordelya.github.io/sca-blogs/) hub and member page snippets.

## Features

* This site is built with Jekyll as a static site and is run with GitHub Pages **for free**.

* Only a few lines of JavaScript need to be added to member sites, no additional configuration is needed by members.

* It also uses modern interoperability standards, and provides an [Atom RSS](https://validator.w3.org/feed/docs/atom.html) feed of member sites' posts (if they provide an Atom or RSS feed), an [OPML](http://opml.org/) file of the members that folks can subscribe to with their RSS readers, and a [FOAF](http://xmlns.com/foaf/0.1/) file for portability of discovering members.

* If you would like to create your own webring hub, begin by visiting [Bill Hunt's Webring Starter Repository](https://github.com/krusynth/webring-starter), from which this repository is forked.

## Getting Started

If you have a blog that covers SCA topics, it is eligible for membership. You may request to join by [submitting a ticket](https://github.com/Cordelya/sca-blogs/issues). If you know how to reach Cordelya (aka Cordeilla) via any method (for example: Knowne World Discord) you may do so to request a link to an alternate request form that does not require a Github account. 

You may grab the member site snippet from the [Join](https://cordelya.github.io/sca-blogs/join/) page and insert it in your blog's header, footer, or sidebar (it should appear on every page. In the case of blogs with SCA categories and other unrelated content, it should appear on all pages/posts that are part of the relevant category.) at any time, even if you haven't requested membership yet. Other member sites won't link to your site until you request membership, but the snippet should work no matter what.

Please note: Official SCA websites are not eligible for membership. 

## How the Webring Works

The snippet on a member website will display the name of the webring (links to the webring hub main page). It will also display two navigation links - one that points to the next site in the webring, and one that points to the previous site in the webring. If a visitor repeatedly clicks on the "next" link, they will visit all of the sites in the ring until they finally return to where they began.

The Webring Hub site will also display a list of recent entries, limited to no more than 10 entries per blog, and limited to entries posted within the past 30 days. Each list-item will link to the entry itself. The RSS feed has the same parameters - past 30 days with a limit of 10 posts from each member.
