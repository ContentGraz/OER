# What’s in the box? Wireframes, types and content objects: core concepts in content management


Following the process of a wireframe analysis, this lecture report touches on some of the basic questions, concepts and insights presented in Deane Barker’s class “Introduction to Content Management”.

## Question 1: What is a wireframe?

Wireframes show different elements on a screen visually and functionally and are demonstrating what is going to be built in a Content Management System (CMS). Due to their versatility, they can be used in different fields like designing or developing for different reasons. Mostly there is one wireframe built for each content type.

Wireframes are not just arrangements of text and pictures, so-called screen mockups. They focus on what a screen does, not what it looks like. They are showing graphically what is going to be built in the CMS, so each party of a project will be on the same page and know what is going to be developed. A Content Management System is a

> software system which automates the tasks around the management of content. A CMS assists editors in creating, organizing, controlling, securing, and ultimately delivering content. [@barkerWebContentManagement]

<!-- Replaced the definition of CMS. They don't necessarily need a database. -->

Wireframes should also show different kinds of information like categories, content objects etc. (which we will come to later), that are displayed and show the functionality available.

## Different professions, different wireframe uses

On the one hand, there are designers that use wireframes for the visual design of user interfaces. On the other hand, developers use them to understand functionalities and get an idea of the technical requirements needed. An analyst uses wireframes to show business rules for example. So wireframes are focusing on interaction and/or navigational paths and are helping to understand functionality and the user interface (the point of human-computer interaction and communication) of the end-product on the screen. http://myprojectanalysis.com/i...

There are some good examples for wireframes Deane Barker made, that can be easily understood when you’ve visited a bunch of websites:
“1. A department subsite menu with a bunch of resources specific to that department explicitly placed in a hierarchy. 2. A blog with a group of blog posts ordered from latest to oldest. 3. A topic page about something with a bunch of disparate resources all related to that topic in order 4. of relevance as determined by a content retrieval algorithm. 5. A set of “related content” links under an article. 6. A list of the “Latest News” headlines on the home page.”

– https://gadgetopia.com/post/8069/

Often the same wireframe type is used instances of the same [content type](https://flyingsquirrelbook.com/glossary/term/content-type/ "Term: "Content Type"") (like e.g. blogpost, news article, web shop entry) U

<!-- misunderstanding of content types. Was: Usually there is one wireframe for each content type like text, image, video etc. -->

## Question 2: What is a wireframe made of? 

Basically a wireframe is made of the [Operative Content Object](https://flyingsquirrelbook.com/glossary/term/operative-content-object/ "Term: 'Operative Content Object'") and its surrounding that consists for example of a header, footer or sidebar (see a wireframe example image 1: yellow area (1) marks the Operative Content Object, green area (2) marks the surrounding).

Wireframe2 zones 01
“Once you’ve designed the basic layout (wireframe; note) for your article, you can load up the sidebars with all sorts of fun stuff – related links, today’s weather, promotional widgets for all sorts of stuff, etc.”

– https://gadgetopia.com/post/7114/

A common problem can be that most Content Management Systems have functions - like managing and displaying - for the Operative Content Object itself but not for the surrounding. The surrounding is related to the OCO through links for example but a direct association can be missing. You could solve this problem contextually:

“This means that each piece of content “lives” in some larger construct. It belongs to a “category” ... or some other grouping that enables you to abstract the Surround away. So, you have some logical construct to which both (1) OCO, and (2) the surround gets assigned. This is where those two “meet” and are associated with each other.”

– https://gadgetopia.com/post/7114/

If you look at each piece of information in the surrounding and assign it to a bigger context you will get a wireframe with a solid basis. After you’ve created the wireframe you can start to plan your project.
Question 3: What’s in all those boxes and how are they filled? #

So, having discussed the framework, let us go into the details of what content is displayed where and how it ends up there. Before taking a closer look at the Operative Content Object, we will descend in the hierarchy of things, examine how the content we are seeing on the page is inputted, modeled and presented.

But even before that, let us get to the core of the matter and clarify:

What is content? #

When looking at our wireframe of the page, and looking at our Operative Content Object, we see what appears to be a CV of a staff member, consisting of a name, a sub-line with title and department, the text, an image, some contact information and two lists listing the education and the courses taught.

Assuming that this is our content is true, but not of full accuracy: what we see is the assembly of content that has been modeled and rendered into this actual visible form.

The page displayed in our OCO is the rendering of a defined model of what a staff member page should consist of (and look like) that has been created in the CMS. This is an example of a content type. It could be called “staff member page”. All parts of that page (the name, title, department and so forth) are modeled content shown in its representations as well. These are the content attributes that are bundled in the content type.

Thus, the content itself, before modeled and represented, is data in raw form, that “comes to live” when transformed for the channels it is displayed in. Other than a website in our example, these can be social media posts, a PDF, an E-Mail, a text-message or physical media.

The raw data (that becomes the content) is inputted into the CMS by the editors.
Types and models #

The content modelling defines what content types there are available, what attributes these types consist of, what datatype each attribute consists of (e.g. text, date, digit, email-adress, …) and which validations are used to secure that the right kind of data is inputted for each attribute.

So in our example, the content type could consist of these attributes:

● the name (that requests the datatype text and could be validated with an required input),

● the title (which should be kept optional in validation, and an edited list could be provided to choose from),

● the position (datatype: text or chosen from edited list provided, validation: required)

● the subject (datatype: text or chosen from edited list provided, validation: required)

● body text (datatype: text, validation: required)

● subheadline ‘education’ (datatype: chosen from edited list provided, validation: required)

● subheadline ‘courses taught (datatype: chosen from edited list provided, validation: required)

● portrait image (datatypes: jpg/png, validation: image format, size)

There are four more content objects on the page that are attributes in the content type, but that could draw their data not from the input provided by the editor but could be pulling the data from the organisation’s data base for example:

● list ‘education’

● list ‘courses taught’

● Email-adress

● Telephone number
We are surrounded #

Having explained the Operative Content Model our wireframe has been built for to evaluate and design, let’s have a brief look on what else can be seen.

The surround, as introduced above, consists of a logo and two sets of menus.

When we look at a menu – and let’s focus on the main menu here – we see the names of sections (About, Academics, Admissions…), BUT – beyond the surface of information architecture, in the depths of content management – we are also looking at some sort of representation of the content structure. Menus are not the content itself, but are references to the content, and often are - unless “hardcoded” ­– a content aggregation. Dependent on the shape of content, aggregations can be put to use for generating a site’s navigation.

Content comes in different shapes. The most common three ones are serial, hierarchical and tabular. Serial content is organized – guess what – in a serial matter, and ordered by a parameter. Hierarchical content is organized into a tree, and content objects have an ancestral relation to each other. Tabular content is organized in a grid or “table” as we know it from spreadsheets.

So how content is organized within an CMS also determines the possibilities it can be displayed and represented in the chosen output channel. So an information designer and a person setting up a CMS will be looking at the same page from two very different angles.
4 - A little floored? #

A lot of folks have had some experience with Content Management Systems or at least think they have a rough idea of what they are about. By doing this short run-through of a wireframe analysis we touched some of the core concepts and opened a couple of doors to the world of managing content. But these are only glimpses. Dean Barker’s lectures enter the depths of it’s modelling, aggregating, implementing, templating and migrating, aswell as editorial workflows and aquisition. And they are just an introduction.



Bibliography #

    Barker, Deane. 2012. „The Art and Practice of Content Assembly: Where IA and CMS Meet“. Https://Gadgetopia.Com/. Abgerufen 25. November 2020 (https://gadgetopia.com/post/8069/).
    Barker, Deane. 2010. „The Problem of Context“. Https://Gadgetopia.Com/. Abgerufen 25. November 2020 (https://gadgetopia.com/post/7114/).
    O A. o. J. „Understanding Wireframes! - Business Analyst Training Online“. Abgerufen 25. November 2020 (http://myprojectanalysis.com/index.php/business-analysis/item/295-understanding-wireframes).

© 2021 FH Joanneum —@ContentGraz
