# Style guides (a.k.a. pattern libraries, templates)

Notes for style guide discussion for SRCCON 2014.

## What is a style guide?

This is my own definition.

A style guide creates standards and best practices for a system or set of decisions that are otherwise subjective.

To note, "style" does not mean that the decisions are visual, it means that the decision that is made is subjective and based on opinion or style.

There are two main questions to think about when defining what a style guide is.  The style of what system or set of decisions?  And, how are standards and best practices transferred or communicated?

[Wikipedia article about style guides](http://en.wikipedia.org/wiki/Style_guide)

### The style of what?

There are many different possibilities of what it is that is being styled.

* digital interfaces (web)
* print design/layout
* code
* copy
* tone
* visualizations
* interactives
* project management

### Medium of the guide

How these best practices and standards are communicated can vary as well.

* narrative
* code
* specifications
* generative

## Examples

This is not an exhaustive list.

### News

News interface examples:

* [MinnPost styles](http://code.minnpost.com/minnpost-styles/): CSS and JS framework for data/interactive pieces.
* [Dallas Morning News graphics stylebook](https://knightcenter.utexas.edu/mooc/file/tdmn_graphics.pdf): Narrative with explicit values on how to make graphics, includes charts and maps; preumably this is for print and web.  Also includes a bit about workflow of how graphics are made as well as maps of the building and where different departments are.
* [Chicago Tribune style guide](http://newsapps.github.io/bootstrap/styleguide/): A CSS and JS framework, altered from Bootstrap for the Newsapps team's pieces.
* [Knight lab style guide (Blueline)](http://blueline.knightlab.com/): Web interface style guide.
* [WNYC style guide](http://wnyc.github.io/): (experimental) Web interface style guide.
* [KPCC Style Guide](https://github.com/SCPR/scpr-styleguide): Looks to be a web interface style guide, but not actually public anywhere.
* [BBC Global Experience Language (GEL)](http://www.bbc.co.uk/gel): A set of interface and copy guidelines for all digital mediums.

News copy examples:

* [Associated Press Stylebook](https://www.apstylebook.com/):  Copy style guide (reusable and for sale).
* [New York Times Manual of Style and Usage](http://en.wikipedia.org/wiki/The_New_York_Times_Manual_of_Style_and_Usage): Copy style guide (reusable and for sale).
* [The Wall Street Journal Guide to Business Style and Usage](http://amazon.com/Street-Journal-Guide-Business-Guides/dp/0743212959): Copy style guide as well as glossary/reference for business terms.
* [BBC News style guide](http://www.bbc.co.uk/academy/journalism/news-style-guide): Copy and grammar guide.
    * An older [BBC style guide](http://www2.media.uoa.gr/lectures/linguistic_archives/academic_papers0506/notes/stylesheets_3.pdf): Copy and tone style guide with a heavy hand of the why for style decisions.
* [Economist style guide](http://www.economist.com/styleguide/introduction): Copy and tone style guide.
* [Guardian style guide](http://www.theguardian.com/guardian-observer-style-guide-a): Glossary style copy guide.
* [Telegraph style book](http://www.telegraph.co.uk/topics/about-us/style-book/): Grammar and copy style guide by topic and glossary.

News code examples:

* [NYT Objective-C style guide](https://github.com/NYTimes/objective-c-style-guide): Code style guide.

News code project templates:

* [Tarbell](http://tarbell.tribapps.com/): Python based templating system for publishing web sites.
* [NPR's app templates](https://github.com/nprapps/app-template): Python based template for making NPR news apps.
* [MinnPost templates](https://github.com/MinnPost/minnpost-templates): Yeoman based system for generating MinnPost projects.

Other news examples:

* [Propublica's nerds guides](https://github.com/propublica/guides/): A set of narrative best practices for project philosophy, application components, coding, FB/Twitter HTML tagging, and data processing.
* [NPR best practices](https://github.com/nprapps/bestpractices): A set of best practice documents for project workflow, versioning, and coding for the NPR Visuals team.  Tied closely to their [app-template](https://github.com/nprapps/app-template).

### Non-news

Non-news interface examples:

* [Article about Eventbrite's style guide](https://engineering.eventbrite.com/styleguide-driven-development-at-eventbrite-introduction/): Looks like a CSS and JS framework.
* [Google's HTML and CSS style guide](https://google-styleguide.googlecode.com/svn/trunk/htmlcssguide.xml): Instructions on how to write CSS and HTML code.
* [Starbuck's general web style guide](http://www.starbucks.com/static/reference/styleguide/): CSS and JS framework for (probably) general web assets.  Does not seem to be downloadable or much info about it.
* [Yelp style guide](http://www.yelp.com/styleguide): CSS and JS style framework for whole site.
    * [About](http://engineeringblog.yelp.com/2014/02/yelps-got-style-and-the-guide-to-back-it-up.html)
* [Github CSS style guide](https://github.com/styleguide/css): CSS framework for Github itself.
    * Also includes a [mobile interface style guide](https://github.com/styleguide/mobile).
* [A List Apart style guide](http://patterns.alistapart.com/): CSS/JS web interface guide.  
* [Code for America style guide for web properties](http://style.codeforamerica.org/): CSS/JS web interface guide.
* [MailChimp style guide](http://ux.mailchimp.com/patterns/): CSS/JS web interface guide.
* [Editorially style guide](http://editorially.github.io/styleguide/): CSS/JS web interface guide.
* [Apple's Mac App style guide](https://developer.apple.com/library/mac/documentation/UserExperience/Conceptual/AppleHIGuidelines/Intro/Intro.html): Desktop application interface design guide.
* [Mapbox style guide](https://www.mapbox.com/base/): Web interface style guide.
* [Salesforce style guide](http://sfdc-styleguide.herokuapp.com/): Web interface design guide.
* [Lonely Planet style guide](http://rizzo.lonelyplanet.com/styleguide/design-elements/colours): Web interface design guide.
* Reusable prototyping libraries
    * [Twitter's Bootstrap](http://getbootstrap.com/): A CSS/JS web interface guide inspired by Twitter.
    * [Barebones](http://barebones.paulrobertlloyd.com/): A CSS web interface style guide for a minimal design.

Non-news code examples:

* [AirBnB JS style guide](https://github.com/airbnb/javascript): Coding style guides for JS.  MinnPost has adopted these.
* Also has a [Ruby style guide](https://github.com/airbnb/ruby)
* [Github style guide](https://github.com/styleguide/css): Includes code style guides for CSS, HTML, JS, and Ruby.
* [Django Python style guide](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/): Based from [PEP8](http://legacy.python.org/dev/peps/pep-0008/), a more general Python style guide.
[SMACSS](http://smacss.com/): CSS coding style guide.

Non-news design examples:

* [Sunlight Labs Data Visualization guide](http://design.sunlightlabs.com/projects/Sunlight-StyleGuide-DataViz.pdf): CSS-ish guide to data visualization such as charts and maps.
    * What looks to be a [CSS/JS implementation of this](https://github.com/sunlightlabs/chartoff).
* [Best Buy brand identity guide](http://bbybrandidentity.com/): A set of design guidelines for brand idenitiy management.
* [Mozilla style guide](https://www.mozilla.org/en-US/styleguide/): Design and brand style guide for Mozilla and its affiliates.
* [Adobe brand guidelines](http://brandcenterdl.adobe.com/Corpmktg/Brandmktg/Campaign_Assets/guidelines/corporate/corporate_brand_guidelines.pdf): Specifications and philosophy for design and brand management.
* [Government of Alberta, Canada corporate identity](http://corporateidentity.alberta.ca/downloads/Alberta_Corporate_Identity_Manual.pdf): Specifications and philosophy for design and brand management.
* [Channel 4 style guide](http://www.channel4.com/about_c4/styleguide/downloads/C4StyleGuide1.1.pdf): Specifications and philosophy for design and brand management.
* [MailChimp branding](http://mailchimp.com/about/brand-assets/): Brand resources and guide.

Non-news copy examples:

* [Mailchimp tone and voice](http://voiceandtone.com/): Tone and voice guide.
* [Wikipedia style manual](http://en.wikipedia.org/wiki/Wikipedia:Manual_of_Style): How to write articles.
* [ISO standard for "presentation of contributions to periodicals and other serials"](http://www.iso.org/iso/catalogue_detail.htm?csnumber=4086): ...
* [EU style guide](http://publications.europa.eu/code/en/en-000100.htm): Guide for all written materials from the EU; in 23 languages.
* [MLA Style Manual and Guide to Scholarly Publishing](http://www.mla.org/store/CID25/PID341): Copy style guide for research and academic works.
* [The Elements of Style](http://en.wikipedia.org/wiki/The_Elements_of_Style): General American English copy style guide.
* [The Yahoo! Style Guide](http://amazon.com/The-Yahoo-Style-Guide-Sourcebook/dp/031256984X): General style guide for copy on the web.

Other non-news examples:

* [Gov.uk service design manual](https://www.gov.uk/service-manual): Guides and instructions on how to design a service.

## References

Helpful links:

* [A List Apart "Creating Style Guides"](http://alistapart.com/article/creating-style-guides)
* [A List Apart "Getting Started with Pattern Libraries"](http://alistapart.com/blog/post/getting-started-with-pattern-libraries)
* [Clearleft Pattern Portfolios](http://clearleft.com/thinks/onpatternportfolios/)
* [Style guide generators](http://welchcanavan.com/styleguide-roundup/)
* [List of various style guides](https://medium.com/@iamtec/a-list-of-style-guides-brand-guidelines-and-front-end-frameworks-e5bb62db91e5)
* [List of brand guides](http://www.logodesignlove.com/brand-identity-style-guides)
* [FindGuideline.es](http://findguidelin.es/): Search for brand assets from different organizations.
* [Github search for "style"](https://github.com/search?q=style+user%3Aminnpost+user%3Anytimes+user%3Apropublica+user%3Adatadesk+user%3Atexastribune+user%3Anewsapps+user%3Anprapps+user%3Awnyc+user%3Awashingtonpost+user%3Aguardian+user%3AopenNews+user%3Adocumentcloud+user%3Aajam+user%3Asourcefabric+user%3Aquartz+user%3Acensusreporter+user%3Aireapps+user%3Adatawrapper+user%3ATheAssociatedPress+user%3AZeitOnline+user%3Aoverview+user%3Ahuffpostdata+user%3Apoderopedia+user%3ALearningLab+user%3Aglasseyemedia+user%3Astateimpact+user%3Afreedomofpress+user%3ANUKnightLab+user%3Asuperdesk+user%3Anacion+user%3Acirlabs+user%3ABBC-News+user%3ASCPR+user%3APRX+user%3Avprnet+user%3Abuzzfeednews+user%3Amcclatchy+user%3Aregisterguard+user%3Adallasmorningnews+user%3Avoxmedia+user%3Afivethirtyeight+user%3Atheupshot+user%3Athunderdome-data+user%3Asunlightlabs+user%3Ainn+user%3Astlpublicradio+user%3AAPMG&type=Repositories&ref=advsearch&l=) for only orgs listed in CAR-Code.

## Discussion

### Introduction

* `Assign note taker.`
* Gatekeeper.  If you speak more than twice, you should really think about speaking again.
* Who I am and the like.
* Our recent style guide.
* Goals and outline:
    1. Better define a style guide
    1. What are the benefits and weaknesses
    1. How can we make style guides
    1. Can we make a general style guide
* (depending on how many people in room) Introduce each other
    * Name
    * Org
    * Favorite thing to read on the internet, besides your own org.

### Feel for the room:

|Question       |  Answer|
|:------------- |-------:|
| How many people have a style guide at their organization for any purpose? | _ |
| How many people have written code? Any amount, including HTML/CSS? | _ |
| How many people have worked on a style guide of any sort? | _ |

### Examples

Let's get the creative juices flowing and look at some examples.

* [AP Stylebook](https://www.apstylebook.com/)
    * Copy and grammar style guide example
    * Standard for American journalism.
    * Not open.
* [BBC news style guide](http://www.bbc.co.uk/academy/journalism/news-style-guide)
    * Copy and grammar style guide example that is free and public.
    * Cross between dictionary and style guidelines.
* [Voice and Tone (MailChimp)](http://voiceandtone.com/)
    * Tone example.
    * Not sure why this is a separate site when content is pretty specific to MailChimp.
    * Talks about user feelings and reasoning for responses.
    * Uses examples.
* [The Dallas Morning News Graphics Stylebook](https://knightcenter.utexas.edu/mooc/file/tdmn_graphics.pdf)
    * Example of print-ish design guide.
    * Focuses on graphics, charts, maps, etc.
    * Exact specifications for design and layout of graphics.
    * Even has map of the building to help person get oriented.
* [Chicago Tribunes NewsApps style guide](http://newsapps.github.io/bootstrap/styleguide/)
    * Web interface example.
    * Based/forked from Bootstrap.
    * Stylings for near all HTML elements.
    * Reusable components.
    * Code-based.
* [Bootstrap](http://getbootstrap.com/)
    * Web interface example.
    * Meant for general re-use.
* [NYT Objective-C Style Guide](https://github.com/NYTimes/objective-c-style-guide)
    * Code style guide example.
* [NPR Visuals' Best Practices](https://github.com/nprapps/bestpractices)
    * Technical project management guide.
    * Specifics about project structure, versioning, and coding techniques.
    * Ties to their template.
* [Tarbell](http://tarbell.tribapps.com/)
    * Application/templating system for publishing lightweight web apps.
    * Makes a lot of decisions for you.

### Groups (maybe)

Depending on number of people, break out into groups of about 7.

* Number off (if lots of people), or just arbitrarily split the room.
* Assign note taker.
* Assign report(back)er.

### Discussion points

For each question, groups should discuss then report back to whole group.

1. What are the types of things that have style?
    * What could have a style guide?
    * Try to aim broad, like "code".  But if you get in the details, that's alright too.
1. What are the benefits and weaknesses of style guides?
    * How would you sell the idea to your org?
    * What are the perceived roadblocks of creating a style guide?
1. How would you go about creating a style guide? im
    * Pick a type of style guide.  For interface, for code, for copy.
    * What are the parts you need?
    * Who do you need for it?
    * How do you keep it up to date?
    * How do ensure others are using it?
    * What tools or techniques would you use (or have you used)?
    * How do you get buy in?
* Can or should we make style guides to use across multiple newsrooms?
    * For instance, the AP Stylebook.
    * Or the ProPublica Nerd's Guide

### Discussion notes

Types of things to style?

* Devops best practices.  Example: TwelveSteps
* Code (syntax)
* Internal communication
    * Tools to use
    * Tone
    * Ensure email has a subject
* External communication, tone
* General computer use
    * File sharing
    * Password management
* Code of Conduct
* Design
    * Typography
    * Colors
* Photography
    * Processing
    * Resizing
* Advertising
* Interaction patterns
* Web interface
* Copy, grammar

Pros and Cons

* Pros
    * Helps with onboarding new employees or contributors to project.
    * Less debate about stylistic things
    * Generally saves time
    * Provides an essential, referencable source
    * Forces decision making
    * Can require thinking about accessibility or other things that may be often overlooked.
    * Helps maintain control and scope on projects
    * Makes things that don't follow require and show importance.  Shining breakthroughs.
    * Don't have to start from scratch
    * Suppresses whims of superiors
    * Requires specific understanding of why there is a need to break or go outside the style guide.
    * Offers a good amount flexibility.  "guide" not "rules".
    * Offers ownerhip
        * Will be used by team that creates it
    * Solidifies branding and identity
    * My original list
        * Saves time building.
        * Makes communication smoother.
        * Provides consistency.
        * Easier to maintain whatever the style guide is for.
        * Can provide for an early testbed.
        * (CSS) Ensures most minimal amount of CSS is written.
* Cons
    * Requires time, commitment, and execution
    * Requires maintenance
    * Requires buy-in and use
    * Might have to defend (often) against haters.
    * Could provide a false send of security
        * Ex. just because an app passes Apple's guidelines, doesn't make it useful or important.
    * Can stifle innovation or creativity
    * Requires adjustment period to use
    * Balancing comprehesiveness and flexibility
    * Can become stale
    * Not always shared across organization
        * Ex. Print department may have their own style guide, while the web department does too
    * How to reconcile web and print style guides
    * Overall investment
    * Can become too authoritative, or "gospel-like"
    * Misuse of the style guide
    * Not having ownership can mean not using
        * If team uses old team's style guide
    * Can be a significant barrier to entry, specifically to contributing to a (open source) project.
    * Can be very negative if style guide goes against larger, universal styles
    * My original list
        * Takes time to create.
        * Takes time to maintain.
        * May limit creativity.
        * Requires expertise.

Thoughts on making style guides for SRCCON/journalism community.

* A guide on which (open source) tools are the best and why.
* Tough to reconcile between standards and best practices.
* "PEP8 for journalism"?
    * Is there specific coding styles that are needed for journalism.
* Best ways to write a README geared towards the journalist audience.
* Best ways to release open source software for journalists.
* Best ways to evaulate tools
* Philosphies and values could be shared across the community.
* Reconcile principle versus styles
* What is practival for everyone as opposed to specific to a brand or identity
* The AP Stylebook is somehwat unique/driven-by that their content is distrbuted across many organizations
* Making audio expercial for everyone
