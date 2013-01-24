#Social Knowledge Creation Tools


##Contents:

1. **[Intro](#section1)**
	- [Definition](#section2.1)
	- [Properties](#section2.2)
1. **[Collaborative Annotation](#section2)**
	- [Development Tools](#section2.1)
	- [Research Tools](#section2.2)
2. **[User-Driven Content](#section3)**
	- [Development Tools](#section3.1)
	- [Research Tools](#section3.2)
3. **[Folksonomy Tagging](#section4)**
	- [Development Tools](#section4.1)
	- [Research Tools](#section4.2)
4. **[Community Bibliography](#section5)**
	- [Development Tools](#section5.1)
	- [Research Tools](#section5.2)
5. **[Shared Text Analysis](#section6)**
	- [Development Tools](#section6.1)
	- [Research Tools](#section6.2)
4. **[Bibliography](#section7)**

#[Intro](id:section1)

##Definition

Let's start by defining a **Social Knowledge Creation Tool**, 

##Properties

###Developer Tools

* **License Type**: The type of license dictates how the software can be used, most open-source software uses variations of the following families of licenses:
	* *BSD* Licenses are a family of permissive free software licenses, imposing minimal restrictions on the redistribution of covered software.
	* *GNU GPL* License is the most widely used software license, which guarantees end users the freedoms to use, study, copy, and modify the software.
	* *MIT* License is a free software license originating at the Massachusetts Institute of Technology (MIT). It is a permissive free software license, meaning that it permits reuse within proprietary software provided all copies of the licensed software include a copy of the MIT License terms.
* **Last Updated**: It's important to know that a project is being actively maintained, if it hasn't been updated in several years then you could be dealing with deprecated/legacy code.
* **Documentation**: Well documented source can make all the difference. A new developer should be able to pick up a project 
* **Technologies Used**: This is important because it describes the requirements of the server environment to run these scripts

###Research Tools



####Category Definitions

* **Collaborative Annotation**:
* **User-Driven Content**:
* **Folksonomy Tagging**:
* **Community Bibliography**:
* **Shared Text Analysis**:

---

#[Collaborative Annotation](id:section2)

##[Developer Toools](id:section2.1)

###[A.nnotate](http://a.nnotate.com)
* **Description**: A.nnotate is an online annotation, collaboration and indexing system for documents and images, supporting PDF, Word and other document formats. 
* **License Type**: Proprietary
* **Last Updated**: Unknown
* **Documentation**: The documentation is a bit of an eyesore, most of the information seems to be there, however it's hard to navigate.
* **Technologies Used**: LAMP (Linux Apache MySQL Perl/Python)
* **Notes**: This is a closed-source proprietary project, but what is a bit worrying is that there's no prices listed on the site, in addition there's no blog or public change log. 

###[Annotate It](http://annotateit.org) / [Annotator](https://github.com/okfn/annotator)
* **Description**: Annotator is a web annotation system. Loaded into a webpage, it provides the user with tools to annotate text (and other elements) in the page.
* **License Type**: MIT / GNU GPL
* **Last Updated**: Actively Maintained.
* **Documentation**: Well documented, with a lot of guides.
* **Technologies Used**: Front-End JavaScript (Req. Jquery)
* **Notes**: Annotator has solid docs and appears relatively easy to implement in any web based environment. There are many similar libraries however this particular project was specifically made for annotations.

### [Digress.it](http://digress.it) 
* **Description**: Digress.it is a WordPress plugin that offers paragraph-level commenting in the margins of a text. 
* **License Type**: GPL
* **Last Updated**: It appears to have been actively maintained until November 2011
* **Documentation**: Well documented.
* **Technologies Used**: PHP/HTML/CSS/JS
* **Notes**: The google code page lacks a download, probably because it's no longer being actively maintained, however it's new enough that it should still work well with active Wordpress sites.

##[Research Tools](id:section2.2)

### [Diigo](http://diigo.com)
* **Description**: Diigo allows you to highlight text and attach sticky notes to specific parts of web pages.
* **License Type**: [Proprietary ToS](http://www.diigo.com/terms)
* **Last Updated**: Actively maintained.
* **Documentation**: Appears to be well documented.
* **Technologies Used**: Diigo does have an RESTful API, but requires an API key similar to Facebook or Twitter.
* **Notes**: The free version is has ads.

### [MarkUp](http://markup.io) 
* **Description**: Markup lets you draw on any webpage with a variety of tools to express your thoughts, make a point or just simply edit. 
* **License Type**: Unknown
* **Last Updated**: Unknown
* **Documentation**: Well documented guide.
* **Technologies Used**: JavaScript Bookmarklet (Node.js Backend)
* **Notes**: Markdown is essentially a chrome app that let's you draw in Chrome and save your drawings and notes. While it appears to be free, it's not exactl

---

#[User-Derived Content](id:section3)

##[Developer Toools](id:section3.1)


### [Buddy Press](http://buddypress.org) 
* **Description**: Buddypress is a social networking modification for wordpress, that extends wordpress into a portal/community site.
* **License Type**: GPL
* **Last Updated**: Actively Maintained.
* **Documentation**: Detailed documentation across multiple versions.
* **Technologies Used**: LAMP.
* **Notes**: Buddypress is wordpress with a lot more features, it's similar to more feature-filed PHP CMSs like Drupal, it's similar to archaic portal CMSs like phpNuke.

### [ckan](http://ckan.org) 
* **Description**: CKAN is the world’s leading open-source data portal platform. 
* **License Type**: AGPL
* **Last Updated**: Actively Maintained.
* **Documentation**: Appears to have detailed, and well-written documentation.
* **Technologies Used**: Written in Python and requires PostreSQL
* **Notes**: Requires Ubuntu 10.04(apt-get), which would be installed on a Virtual Private Server (VPS) or dedicated server

### [Omeka](http://omeka.org) 
* **Description**: Omeka is a free, open source content management system for online digital collections. As a web application, it allows users to publish and exhibit cultural heritage objects, and extend its functionality with themes and plugins. 
* **License Type**: GNU GPL
* **Last Updated**: Actively Maintained/
* **Documentation**: Well documented.
* **Technologies Used**: LAMP
* **Notes**: 

##[Research Tools](id:section3.2)

### [CrowdVoice](http://crowdvoice.org) 
* **Description**: CrowdVoice is a user-powered service that tracks voices of protest from around the world by crowdsourcing information. 
* **Technologies Used**: Unknown 
* **Notes**: Crowdvoice is a really powerful tool for allowing protesters a way to crowdsource information. The source is closed, as those who submit content could risk persecution in their countries of origin for contributing content to the site.
 
### [mediacommons](http://mediacommons.futureofthebook.org) 
* **Description**: MediaCommons is a community network for scholars, students, and practitioners in media studies, promoting exploration of new forms of publishing within the field.
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

---

#[Folksonomy Tagging](id:section4)

##[Developer Toools](id:section4.1)

### [bit.ly](http://bitly.com)
* **Description**: bitly is the easiest and most fun way to save, share and discover links from around the web. We call these links bitmarks, and you can use bitly to remember, curate and share them.
* **License Type**: [Proprietary ToS](https://bitly.com/pages/terms-of-service)
* **Last Updated**: Actively Maintained.
* **Documentation**: Well Written.
* **Technologies Used**: Supports a large variety of API Code Libraries.
* **Notes**: While not a free open-source tools itself, bitty offers open source libraries in many popular client-side and server-side languages to interact with the bitty API.


### [netvibes](http://netvibes.com/en) - 
* **Description**: Netvibes is a proprietary web-based dashboard tool, that allows you to install widgets, manage feeds, and retrive information from multiple sources.
* **License Type**: [Proprietary ToS](http://www.netvibes.com/static.php?show=tos)
* **Last Updated**: Actively maintained.
* **Documentation**: Limited, however the tool is relatively simplistic.
* **Technologies Used**: It does support an open developer API.
* **Notes**: The social media and dev blog have not been updated since 2009, which is a little bit bizarre for company with offices in Paris, London, and San Francisco.
 
### [Flickr](#)
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

### [Delicious](http://delicious.com)
* **Description**: Social bookmarking platform that's been around for nearly a decade (the naming was part of _iciou.us fad).
* **License Type**: [Proprietary ToS](https://delicious.com/terms)
* **Last Updated**: Actively Maintained.
* **Documentation**: Well documented.
* **Technologies Used**: Extensive feeds and APIs of similar calibre to those of Twitter, Facebook, etc...
* **Notes**: 

### [Twitter](#)
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

### [Tumblr](#)
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

##[Research Tools](id:section4.2)


### [Blackboard Scholar](http://www.itap.purdue.edu/tlt/Scholar/) `!`
* **Description**: Blackboard Scholar is a social bookmarking service customized for education.
* **License Type**: Unknown.
* **Last Updated**: Unknown.
* **Documentation**: The documentation appears to be out of date.
* **Technologies Used**: Unknown.
* **Notes**: It looks like I may need to be a Blackboard user to access this tool, however the website 'scholar.com' doesn't work at this time.

---

#[Community Bibliography](id:section5) 

### [BibServer](http://bibserver.org) 

* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: their headline example 'BibSoup' doesn't have any datasets (even sample data), which seems extremely odd, it was last updated 7 months ago and was written in Python, although it uses 

### [BibSonomy](http://bibsonomy.org)
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

### [Citeline](http://citeline.mit.edu) 
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: appears to be out of date and does not support modern browsers

### [citeulike](http://citeulike.org)
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

### [Connotea](http://connotea.org)
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

### [Greenstone](http://greenstone.org) 
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 
 
### [Zotero](http://zotero.org)
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

##[Shared Text Analysis](id:section6)
### [Argo](http://nactum.ac.uk/argo)
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

### [CATMA](http://catma.de)
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

### [CommentSpace](http://vis.berkeley.edu/papers/commentspace) 
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

### [MONK](http://monkproject.org)
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

### [Voyant](http://voyeur.hermeneuti.ca)
* **Description**: 
* **License Type**:
* **Last Updated**: 
* **Documentation**: 
* **Technologies Used**: 
* **Notes**: 

y an open-source tool, as it's a browser level app/bookmarklet and not made for website integration.
