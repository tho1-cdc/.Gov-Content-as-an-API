.Gov-Content-as-an-API
======================

Standards, Tools, and Guidance for offering web content and digital media through a web service for inclusion in web sites, mobile apps, social media,  Electronic Health Records (EHRs), Personal Health Records (PHRs), Clinical Decision Support sytems, and emerging digitial channels.  This ecompasses providing API and media discovery mechanisms for searching and browsing, and methods to retrieve the embed code needed to embed a media item into a hosting site.  Includes tools for capturing view and click-through metrics from syndicated media, methods for collecting feedback on media items, administrative tools to support managing media discovery, and Software as a Service (Saas) implementations for hosting multiple media storefronts against a single set of media syndication services.


### API Standards for Content APIs 
* [White House API Standards](https://github.com/WhiteHouse/api-standards) CDC and HHS/ASPA have embraced the White House API Standards with a few extensions; specifically to allow for multiple messages in the return for buld operations and also an extension of the pagination mechanism.  These changes have been proposed as enhancements to the Whitehouse.gov specification on GitHub.  
* 
Key Components of a Media API
1. Media and API Discovery
   Creating an API for serving digital media and making media available are only the beginnings of opening a digitial media channel.  Making multi-channel syndication work requires a means for developers to discover the APIs and the for downstream communicators to dicover the media that is available.  Developer community efforts and developer documentation are covered later in this document.   This section will focus on media discovery by downstream communicators who wish to syndicate media into their channels to support a communication objective. For this purpose media storefronts, or libraries provide a user friendly presence where users can search and browse available media and can get the embed code they need to use that media in their web-sites, social media presences, apps, or other outlets that serve digital media.  Since most syndication providers have multiple types of media to share, media type is a key facet of browsing and discovery.  Allowing users to pivot through types on a single topic provides cross marketing opportunites to the media provider.  For example, if a user is looking at infographics there is a reasonable chance that other visualizations (maps, charts, etc.) from the same source dataset or related datasets might be of interest. 

   Faceted browsing and filtering is a proven paradigm for product discovery. Media created, updated, and publish dates, media source and systems should allow media providers and storefront managers to establish new facets and assign values to them.  The canonical example is "reading level"; if a content provider feels it would improve discovery to tag their media with a reading level then they should be able to add that attribute to the affected media types and provide a list of values.  These attributes and their associated value sets should be available through the API to allow storefront and application developers to provide these values to end users for selection.

   During media capture, manual administrators or ingestion services should then allow for the tagging of media items to those values and the storefront search and browse experience should reflect the new facet and values.  In addition to providing a navigable list for browsing, these extensible facets should be made available as filters for search results. 
   
   API driven search mechanisms should be sensitive to the needs to the developers who use them in low-band width or partially connected situations. Media APIs should provie accomodations such as allowing the developer to specify a maximum time they are willing to wait for search results and returning an indication of the search execution duration as well as a flag indicating if the results are from a completed search or a partially completed search.  Developers who expect to page through results in small chunks should also be able to request that the results of a search are cached for a period of time to improve paging performance.
   
   To support the testing of 
 
  


   g. Allowing for out of band discovery
   h. Real time or near real time discovery
   i. Retraction of Content
   j. Collecting feedback on content

2. Extensibility
   a. New content / Media types

3. Metadata
   a. Discovering Metadata
   b. Providing access to value sets for facets
   c. Geographical Metadata
   d. Metadata extensibility
   e. Tying media to metadata

4. Enabling Media Embedding
   a. Static embed types
   b. Dynamic embed types
   c. A little JavaSecipt Help
   d. The ingestors

5. Providing for Registration
   a. The case for registration
   b. The case against registration

6. Terms of Service / Usage Guidelines
  
7. Versioning the API

8. Providing API consumption tools / SDKs

9. Building communities around Content

10. Building Developer Communities to reach new channels



### Tools for Content API generation
* [Drupal Content API](http://www.fcc.gov/encyclopedia/content-api-drupal-module)
* [Wordpress JSON plugin](http://wordpress.org/plugins/json-api/)
* [HHS Digital Media API Platform](http://sourceforge.net/projects/contentservices/) - Used for the CDC, FDA, NIAID, and HHS.gov content APIs.  


### Examples of Content APIs in the US Government
* [Economic Research Service, USDA](http://www.ers.usda.gov/developer/website-content-api.aspx)
* [Centers for Disease Control, HHS](https://tools.cdc.gov/syndication/api.aspx)
* [Food and Drug Administration, HHS - Tobacco Content](http://tools.fda.gov/CSStorefront/api.aspx)
* [National Institute of Allergy and Infectious Diseases, HHS](http://tools.niaid.nih.gov/register/api.aspx)
* [Substance Abuse and Mental Health Services Administration, HHS](http://store.samhsa.gov/developer)
* [Healthcare.gov, HHS](https://www.healthcare.gov/developers/)
* [HealthFinder.gov, HHS](http://healthfinder.gov/contentsyndication/)
* [HHS.gov, HHS](https://syndication.hhs.gov/storefront/apiDoc)
* [Federal Communications Commission](http://www.fcc.gov/developers/fcc-content-api)
* [Information Sharing Environment](http://www.ise.gov/developer)
* [Small Business Administration](http://www.sba.gov/about-sba/sba_performance/sba_data_store/web_service_api/content_share_api)
* [BusinessUSA](http://business.usa.gov/apis)
* [Veterans Affairs - Press Releases](http://www.va.gov/webservices/press/documentation/releases.cfm)



Assorted Notes  
* 'Started at CDC, now also at CMS, center for tobacco products (for FDA), HHS
flu.gov, vaccine.gov'   
* CMS
* Flu.gov
* FR
* GSA - In Prototype
* [CDC has been talking to some parts of State]
* http://next.data.gov/?json=1



