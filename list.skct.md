#Social Knowledge Creation Tools

##Contents:

1. **[Intro](#section1)**
	- [Definition](#section1.1)
	- [Properties](#section1.2)
2. **[Collaborative Annotation](#section2)**
	- [Open Source](#section2.1)
		- [A.nnotate](#section2.1.1)
		- [Annotate It](#section2.1.2)
		- [Digress.it](#section2.1.3)
	- [Web-based](#section2.2)
		- [Diigo](#section2.2.1)
		- [MarkUp](#section2.2.2)
3. **[User-Driven Content](#section3)**
	- [Open Source](#section3.1)
		- [Buddy Press](#section3.1.1)
		- [ckan](#section3.1.2)
		- [Omeka](#section3.1.3)
	- [Web-based](#section3.2)
		- [CrowdVoice](#section3.2.1)
		- [mediacommons](#section3.2.2)
4. **[Folksonomy Tagging](#section4)**
	- [Open Source](#section4.1)
		- [bit.ly](#section4.1.1)
	- [Web-based](#section4.2)
		- [Flickr](#section4.2.1)
		- [Delicious](#section2.2.2)
		- [netvibes](#section2.2.3)
		- [Twitter](#section4.2.4)
		- [Tumblr](#section2.2.5)
	- [Deprecated](#section4.3)
		- [Blackboard Scholar](#section4.3.1)
5. **[Community Bibliography](#section5)**
	- [Open Source](#section4.1)
		- [Aigaion](#section5.1.1)	
		- [Bibliography Module](#section5.1.1)	
		- [BibServer](#section5.1.1)
		- [Greenstone](#section5.1.2)
		- [Zotero](#section5.1.3)
	- [Web-based](#section5.2)
		- [BibSonomy](#section5.2.1)
		- [Citeline](#section5.2.2)
		- [citeulike](#section5.2.3)
	- [Deprecated](#section5.3)
		- [Connotea](#section5.3.1)
6. **[Shared Text Analysis](#section6)**
	- [Open Source](#section6.1)
		- [CATMA](#section6.1.1)	
	- [Web-based](#section6.2)
		- [Argo](#section6.2.1)
		- [CommentSpace](#section6.2.2)
		- [MONK](#section6.2.3)
7. **[Game Enhanced Tools](#section7)**
	- [Open Source](#section7.1)
		- [Badge Stack](#section7.1.1)
		- [Open Badges](#section7.1.2)
	- [Web-based](#section7.2)
		- [Big Door](#section7.2.1)

#[Intro](id:section1)

##Definition

Let's start by defining a **Social Knowledge Creation Tool**, it is an application that enables researchers to collaborate  
 
##Properties

###Open Source

Open Source SKCTs are typically tools that have been made to be re-used and re-purposed, rather than tools that you can use out of the box.

* **License Type**: The type of license dictates how the software can be used, most open-source software uses variations of the following families of licenses:
	* *BSD* Licenses are a family of permissive free software licenses, imposing minimal restrictions on the redistribution of covered software.
	* *GNU GPL* License is the most widely used software license, which guarantees end users the freedoms to use, study, copy, and modify the software.
	* *MIT* License is a free software license originating at the Massachusetts Institute of Technology (MIT). It is a permissive free software license, meaning that it permits reuse within proprietary software provided all copies of the licensed software include a copy of the MIT License terms.
* **Last Updated**: It's important to know that a project is being actively maintained, if it hasn't been updated in several years then you could be dealing with deprecated/legacy code.
* **Documentation**: Well documented source can make all the difference. A new developer should be able to pick up a project 
* **Technologies Used**: This is important because it describes the requirements of the server environment to run these scripts

###Web-Based

Web-Based tools are typically services or browser extensions. They are usually closed-source, as they're not designed to be shared, however many of these services offer Application Programming Interface (API)

####Category Definitions

* **Collaborative Annotation**: 
* **User-Driven Content**:
* **Folksonomy Tagging**:
* **Community Bibliography**:
* **Shared Text Analysis**:

---

#[Collaborative Annotation](id:section2)

##[Open Source](id:section2.1)

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

##[Web-Based Tools](id:section2.2)

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

##[Open Source](id:section3.1)

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
* **Notes**: Omeka is a CMS, similar to Drupal, with an academic focus. It appears to be powerful, however to do anything really complex, it requires learning the framework and working within their pre-defined structure.

##[Web Based](id:section3.2)

### [CrowdVoice](http://crowdvoice.org) 
* **Description**: CrowdVoice is a user-powered service that tracks voices of protest from around the world by crowdsourcing information. 
* **Technologies Used**: Unknown 
* **Notes**: Crowdvoice is a really powerful tool for allowing protesters a way to crowdsource information. The source is closed, as those who submit content could risk persecution in their countries of origin for contributing content to the site.
 
### [mediacommons](http://mediacommons.futureofthebook.org) `!`
* **Description**: MediaCommons is a community network for scholars, students, and practitioners in media studies, promoting exploration of new forms of publishing within the field.
* **License Type**: [Copyright/Fair Use Policy](http://mediacommons.futureofthebook.org/copyright)
* **Notes**: I'm not entirely sure if this is a tool.

---

#[Folksonomy Tagging](id:section4)

##[Open Source](id:section4.1)

### [bit.ly](http://bitly.com)
* **Description**: bitly is the easiest and most fun way to save, share and discover links from around the web. We call these links bitmarks, and you can use bitly to remember, curate and share them.
* **License Type**: [Proprietary ToS](https://bitly.com/pages/terms-of-service)
* **Last Updated**: Actively Maintained.
* **Documentation**: Well Written.
* **Technologies Used**: Supports a large variety of API Code Libraries.
* **Notes**: While not a free open-source tools itself, bitty offers open source libraries in many popular client-side and server-side languages to interact with the bitty API.



##[Web Based](id:section4.2)

### [Flickr](#)
* **Description**: Flickr is an image hosting and video hosting website, web services suite, and online community 
* **License Type**: [Proprietary ToS](http://www.flickr.com/services/api/tos/) | [API ToS](http://www.flickr.com/services/api/tos/)
* **Last Updated**: Actively Maintained.
* **Documentation**: Well documented.
* **Technologies Used**: PHP with APIs in multiple languages
* **Notes**: Flickr is pretty amazing as an image source, and the options for creative commons sharing is great.

### [Delicious](http://delicious.com)
* **Description**: Social bookmarking platform that's been around for nearly a decade (the naming was part of _iciou.us fad).
* **License Type**: [Proprietary ToS](https://delicious.com/terms)
* **Last Updated**: Actively Maintained.
* **Documentation**: Well documented.
* **Technologies Used**: Extensive feeds and APIs of similar calibre to those of Twitter, Facebook, etc...
* **Notes**: 

### [netvibes](http://netvibes.com/en)
* **Description**: Netvibes is a proprietary web-based dashboard tool, that allows you to install widgets, manage feeds, and retrieve information from multiple sources.
* **License Type**: [Proprietary ToS](http://www.netvibes.com/static.php?show=tos)
* **Last Updated**: Actively maintained.
* **Documentation**: Limited, however the tool is relatively simplistic.
* **Technologies Used**: It does support an open developer API.
* **Notes**: The social media and dev blog have not been updated since 2009, which is a little bit bizarre for company with "offices in Paris, London, and San Francisco."

### [Twitter](#)
* **Description**: Twitter is an online social networking service and microblogging service that enables its users to send and read text-based messages of up to 140 characters, known as "tweets".
* **License Type**: [Proprietary ToS](https://twitter.com/tos)
* **Last Updated**: Actively Maintained.
* **Documentation**: Well documented.
* **Technologies Used**: Javascript,Ruby,Scala(Java)
* **Notes**: 

### [Tumblr](#)
* **Description**: Tumblr is a microblogging platform and social networking website, owned and operated by Tumblr, Inc. The service allows users to post multimedia and other content to a short-form blog. 
* **License Type**: [Proprietary ToS](http://www.tumblr.com/policy/en/terms_of_service)
* **Last Updated**: Actively Maintained.
* **Documentation**: Well documented.
* **Technologies Used**: 
* **Notes**: 


## [Deprecated](id:section4.3)

### [Blackboard Scholar](http://www.itap.purdue.edu/tlt/Scholar/) `!`
* **Description**: Blackboard Scholar is a social bookmarking service customized for education.
* **License Type**: Unknown.
* **Last Updated**: Unknown.
* **Documentation**: The documentation appears to be out of date.
* **Technologies Used**: Unknown.
* **Notes**: It looks like I may need to be a Blackboard user to access this tool, however the website 'scholar.com' doesn't work at this time.

---

#[Community Bibliography](id:section5) 

##[Open Source](id:section5.1)

### [Aigaion](http://sourceforge.net/projects/aigaion/) 

* **Description**: Aigaion is a php/mysql based multi-user system for managing annotated bibliographies.
* **License Type**: GNU GPL
* **Last Updated**: Actively Maintained.
* **Documentation**: Well documented (web docs returned a 404)
* **Technologies Used**: PHP/MySQL
* **Notes**: Their source forge page is active and has been updated in the past year, however their homepage and online documentation returns 404.

### [Bibliography Module (Drupal)](http://sourceforge.net/projects/aigaion/) 

* **Description**: This Drupal module allows users manage and display lists of scholarly publications.
* **License Type**: GNU GPL
* **Last Updated**: Actively Maintained.
* **Documentation**: Well documented.
* **Technologies Used**: PHP
* **Notes**: Seems like a handy module if you're developing a Drupal site.

### [BibServer](http://bibserver.org) 

* **Description**: BibServer is a tool for quickly and easily sharing collections of bibliographic metadata. 
* **License Type**: GNU Affero GPL v3
* **Last Updated**: Actively Maintained.
* **Documentation**: Well documented.
* **Technologies Used**: Uses a mishmash of dependencies, and it written in Python.
* **Notes**: Their headline example 'BibSoup' doesn't have any datasets (even sample data), which seems extremely odd, it was last updated 7 months ago and was written in Python, although it uses 

### [Greenstone](http://greenstone.org) 
* **Description**: Greenstone is a suite of software for building and distributing digital library collections.
* **License Type**: GNU GPL
* **Last Updated**: Actively Maintained.
* **Documentation**: Well documented, but the hierarchy of information is poorly organized.
* **Technologies Used**: C++.
* **Notes**: The design makes it look like it was developed in the 90s.
 
### [Zotero](http://zotero.org)
* **Description**: Zotero is an open source tool, and we welcome anyone who would like to contribute.
* **License Type**: [Privacy Policy](http://www.zotero.org/support/terms/privacy) | AGPL
* **Last Updated**: Actively Maintained.
* **Documentation**: Well Documented.
* **Technologies Used**: JavaScript | SQLite
* **Notes**: This is a really cool open source project with extensive APIs, a well designed site/interface and plenty of support.

##[Web Based](id:section5.2)

### [BibSonomy](http://bibsonomy.org)
* **Description**: BibSonomy is a system for sharing bookmarks and lists of literature.
* **License Type**: [Proprietary ToS](http://www.bibsonomy.org/help_en/Privacy)
* **Last Updated**: Actively Maintained.
* **Documentation**:  Well documented.
* **Technologies Used**: REST API available to developers.
* **Notes**: Looks like it was designed by a software engineer, due to the insufficient use of whitespace.

### [Citeline](http://citeline.mit.edu) `!`
* **Description**: Citeline is a service to facilitate the web publishing of bibliographies and citation collections as interactive exhibits and facilitate the sharing of this type of data.
* **License Type**: Unknown
* **Last Updated**: ~2008.
* **Documentation**: User guide is is detailed.
* **Technologies Used**: No API listed.
* **Notes**: Appears to be out of date (Copyright dates back to 2008) and does not support modern browsers (by their own admission).

### [citeulike](http://citeulike.org)
* **Description**: CiteULike is a free service to help you to store, organize and share the scholarly papers you are reading. 
* **License Type**: [Proprietary ToS](http://www.citeulike.org/terms)
* **Last Updated**: Actively Maintained
* **Documentation**: Well documented (requires login/registration).
* **Technologies Used**: Unknown.
* **Notes**:  

##[Deprecated Tools](id:section5.3)

### [Connotea](http://connotea.org) `!` 
* **Description**: Connotea is a free online reference management service. It allows you to save links to all your favourite articles, references, websites and other online resources with one click. Connotea is also a social bookmarking tool, so you can view other people's collections to discover new, interesting content.
* **License Type**: [Proprietary ToS](http://www.nature.com/info/tandc.html)
* **Notes**: Connotea will discontinue service on March 12, 2013.

#[Shared Text Analysis](id:section6)

##[Open Source](id:section6.1)

### [CATMA](http://catma.de) `!` #Desktop
* **Description**: CATMA is a practical and intuitive tool for literary scholars, students and other parties with an interest in text analysis and literary research.
* **License Type**: GNU GPL 3
* **Last Updated**: Actively Maintained.
* **Documentation**: [Detailed PDF Manual](http://www.catma.de/download)
* **Technologies Used**: Java
* **Notes**: CATMA seems like a really powerful tool. The lack of web-based documentation is a little disconcerting.

##[Web-Based](id:section6.2)

### [Voyant](http://voyeur.hermeneuti.ca)
* **Description**: Voyeur is the web-based tool for reading and analyzing your digital texts.
* **License Type**: Unknown, the web tool requires no login
* **Last Updated**: Actively maintained
* **Documentation**: Well documented with detailed tutorials.
* **Technologies Used**: Javascript
* **Notes**: This project is pretty cool, it uses a lot of client-side JS, although it's odd that the page is calling some 20 odd javascript files instead of 1 concatenated and minified JS file.

##[Deprecated Tools](id:section6.3)

### [Argo](http://nactem.ac.uk/argo/app/)
* **Description**: Argo is a workbench for building and running text-analysis solutions. It facilitates the development of custom workflows from a selection of elementary analytics. 
* **License Type**: [Terms and Conditions](http://nactem.ac.uk/terms_conditions.php) | AGPL
* **Last Updated**: Unknown.
* **Documentation**: Unknown.
* **Technologies Used**: Unknown.
* **Notes**: Took a really long time to load the app (~2min). Errors  during registration.

### [CommentSpace](http://vis.berkeley.edu/papers/commentspace) `!`  
* **Description**: Collaborative visual analysis tools can enhance sense making by facilitating social interpretation and parallelization of effort. 
* **License Type**: Uknown
* **Last Updated**: 2011
* **Documentation**: Introduction video and detailed paper.
* **Technologies Used**: Flash(Flex/Flare)
* **Notes**: There's no demo or download version currently available

### [MONK](http://monkproject.org) `!`
* **Description**: MONK is a digital environment designed to help humanities scholars discover and analyze patterns in the texts they study.
* **License Type**: [License](http://monkproject.org/docs/monk-datastore-doc/doc-files/license.html)
* **Last Updated**: Unknown.
* **Documentation**: Seems well-documented, but it doesn't state what version the documentation is relevant to.
* **Technologies Used**: Java
* **Notes**: Many parts of the Monk site were not working. The Monk datastore would potentially give users access to a lot of data/sampledata.

#[Gamification Tools](id:section7)

##[Open Source](id:section7.1)

### [Badge Stack](http://badgestack.com/) `!`  
* **Description**: BadgeStack is a social learning tool that encourages people to master new skills and get involved in your community.
* **License Type**: GNU GPL V2 (Maybe)
* **Last Updated**: To be released.
* **Documentation**: Limited.
* **Technologies Used**: Unknown.
* **Notes**: "We’re preparing to release an open source version for download. Before we do, we are consulting with members of the BadgeStack Advisory Board who come from education, museum, library and other non-profit organizations." ("Download." BadgeStack Project. N.p., n.d. Web. 31 Jan. 2013.)

### [Open Badges](http://openbadges.org/)
* **Description**: Mozilla Open Badges helps solve that problem, making it easy for any organization to issue, manage and display digital badges across the web.
* **License Type**: [License](http://beta.openbadges.org/tou.html)
* **Last Updated**: Actively Maintained
* **Documentation**: Well-documented, API, 
* **Technologies Used**: Java
* **Notes**: Many parts of the Monk site were not working. The Monk datastore would potentially give users access to a lot of data/sampledata.

##[Web-Based](id:section7.2)

### [Big Door](http://www.bigdoor.com/)
* **Description**: BigDoor powers Gamified Rewards Programs that create loyalty and engagement.
* **License Type**: [Terms and Conditions](http://nactem.ac.uk/terms_conditions.php) | AGPL
* **Last Updated**: Unknown.
* **Documentation**: Unknown.
* **Technologies Used**: Unknown.
* **Notes**: Took a really long time to load the app (~2min). Errors  during registration.
