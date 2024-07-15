.. include:: /Includes.rst.txt

.. _typo3-terminology:
Spelling and TYPO3 Terminology
==============================

This section establishes common keywords and the terminology that TYPO3 uses.
For a guide on how to spell certain trademark and product names, see
:ref:`Spelling, terms and glossary <h2document:spelling-ref-this-guide>`.

.. _1-spelling-and-typo3-terminology:

Spelling and TYPO3 Terminology
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*   A
    -   Admin Panel

        The Admin Panel is an administrative tool that can be enabled in the frontend,
        to show debugging information, performed SQL queries and more for authenticated
        backend users.

    -   Admin Tools

        Admin Tools are a group of Backend modules. These include maintaining the installation,
        adjusting settings, executing upgrade wizards, checking environment information and setting
        up extensions.

    -   Allow Fields

        Allow Fields refer to fields of content elements displayed in the TYPO3 backend in regard to
        their permissions. Editors can only edit fields in the backend, which are included in the
        list of "Allow fields" in their permission setup.

    -   Assets

        Assets are media resources like images, videos, and documents that are
        uploaded and managed in the TYPO3 system. Also, extensions can include "Assets" which
        can be referred to in the frontend, like specific icons or even JavaScript libraries.

*   B
    -   Backend / Frontend

        Backend and Frontend are the two main areas of TYPO3 CMS. The Backend is
        the administration interface for editors and administrators, while the
        Frontend is the publicly accessible part of the website.

    -   Backend Bookmarks

        Backend Bookmarks are shortcuts that users can set for frequently used
        backend pages for quicker access.

    -   Backend Layout

        The Backend Layout defines the structure and design of the backend user
        interface in regard to maintaining content elements and the arrangement of their
        input fields. A "Backend Layout" can be set on a page-level, and this attribute
        can actually be also evaluated in the frontend, to affect the arrangement of
        elements on a page.

    -   Backend Module

        Backend Modules are extendable components in the TYPO3 backend that
        provide various functionalities and tools like user management or file
        management. The left hand panel in the backend shows all these modules.

*   C
    -   Callout

        A Callout is a highlighted element designed to draw attention to important
        information or actions.

    -   Cache (Cache Backend, Frontend Cache)

        Caches are used to improve website performance by storing frequently
        accessed data. The Backend Cache stores data in the administration system,
        while the Frontend Cache stores data for the website display.

    -   Cache Tags

        Cache Tags are labels assigned to cache entries to facilitate the
        management and invalidation of cached data.

    -   Certification (T3CC, T3CD, T3CI, T3CE)

        Certifications in the TYPO3 ecosystem, such as T3CC (Consultant), T3CD (Developer),
        T3CI (Integrator), and T3CE (Editor) confirm the proficiency of developers and
        integrators in various aspects of TYPO3 CMS. TYPO3 has an official certification
        strategy.

    -   CIG/SIG (Special Interest Group)

        Special Interest Groups (SIGs) are groups of experts and enthusiasts who
        focus on specific topics within the TYPO3 ecosystem and work on improving
        those areas.

    -   Clipboard

        The Clipboard in the TYPO3 backend is a tool for copying, cutting, and
        pasting content elements and records.

    -   colPos

        colPos is a column in the TYPO3 database that defines the position and
        layout of content elements on a page within a template.

    -   Constants/Setup

        Constants and Setup are configuration options in TYPO3 TypoScript that set
        basic settings and variables for the website. "Constants" can be regarded
        as variables, referencing contents defined in the Backend GUI. The "Setup"
        uses these "Constants" to put the variables to the place they are needed, to
        define behaviour of the Frontend (and sometimes also Backend).

    -   Content Blocks

        Content Blocks are predefined layouts and content elements that can be used
        to create page content in the TYPO3 backend. Currently it refers to an
        extension, whose feature set shall be part of TYPO3 v13. Content Blocks are
        small sets of configuration, defining both Backend input and Frontend output.

    -   Content Elements

        Content Elements in TYPO3 are building blocks of content that can shown
        in the frontend. Each Content Element has many (and also custom) attributes,
        even consisting of nested hierachies of further Content Elements.

    -   Core

        The TYPO3 Core is the central framework of the CMS that provides all basic
        functions and features.

    -   Core Development

        Core Development refers to the development and maintenance of the central
        TYPO3 framework by the Core Team.

    -   Core Merger

        A Core Merger is a person or team member responsible for merging code
        changes and updates into the TYPO3 core. TYPO3 Core Mergers are elected
        in a formal process.

    -   Core Team

        The Core Team consists of the main developers and contributors responsible
        for developing and maintaining the TYPO3 core.

    -   Crop variants

        Crop Variants are different cropping options for images that can be defined
        and used within the TYPO3 system. One image can have for example a crop
        variant for "mobile" and "desktop", or different aspect ratios, or any
        custom scheme.

    -   Crowdin

        Crowdin is a translation tool used for localizing and translating TYPO3
        content into different languages.

    -   CType

        CType stands for Content Type and is a database column field of the
        vital "tt_content" database table, where all Content Elements are stored.
        This column defines the name of a specific element, and influences how it
        is presented in the Backend and Frontend.

*   D
    -   Dashboard / Widgets

        The Dashboard is a customizable start page in the TYPO3 backend that
        contains various widgets for displaying important information and quick
        access.

    -   Data Processor

        A Data Processor is a component that processes and manipulates data before
        it is displayed in the TYPO3 frontend. Data Processors are implemented as
        PHP code, and can be executed through TypoScript configuration, and affect
        data passed on to Fluid templates. Thus, it is a specific implementation
        to operate on data before it is passed on to the presentation layer (templates).

    -   Data Provider

        A Data Provider is a source of data that can be used by other components
        within the TYPO3 system. Data Providers are commonly used for passing on Data
        in the Backend (for example defining available icons, item keys and values).

    -   DataHandler

        The DataHandler is a central component in TYPO3 responsible for processing
        and storing data changes. It is a large PHP Class that is used in the Backend
        to receive data from the FormEngine (Content Elements and records), and
        is also part of an extensive API that can be used by extensions to operate on
        records.

    -   DB Analyzer / DB Compare

        DB Analyzer and DB Compare are tools in TYPO3 that analyze and compare
        database structures to identify needed changes on the dataase-level for
        both for system upgrades and extension integration. Other systems often
        call this "database migration".

    -   DB Mounts / Mount Points

        Mount points allow TYPO3 editors to mount a page (and its subpages) from a
        different area in the current backend page tree.

    -   DBAL

        The Database Abstraction Layer (DBAL) is an abstraction layer in TYPO3 that
        facilitates access to various database systems.

*   E
    -   Enhancer

        An Enhancer is a component that adds additional functionalities or
        improvements to existing TYPO3 features, most commonly used for
        "Routing Enhancers" operating on "speaking URL fragments".

    -   Exclude Fields

        Exclude Fields are fields that have ben configured to allow being hidden
        in the TYPO3 backend for specific users or user groups. This is done
        via the permission setup.

    -   Extbase

        Extbase is a framework for developing extensions in the TYPO3 system based
        on the Model-View-Controller (MVC) principle. It allows to easily define
        models with their data fields, that can be managed by editors in the backend.
        The models can then also be revealed in the frontend with any custom logic,
        adhering to standards, conventions and API definitions. The "Extbase Controllers"
        which are part of an "Extbase Plugin" allow to integrate this custom logic in PHP.

    -   Extension

        An Extension is an add-on to the TYPO3 system that adds additional
        functionalities and features. An extension can consist of multiple parts,
        for example Backend Modules, Frontend Plugins, Scheduler Tasks, Console Commands,
        API definitions, Frontend Styling and much more.

    -   Extension Builder

        The Extension Builder is a Backend Module in TYPO3 that facilitates the creation of
        (preferrably) Extbase Extensions. The Extension Builder is a community extension
        and maintained on its own.

    -   Extension Manager

        The Extension Manager is an interface in the TYPO3 backend used for
        installing, updating, and managing extensions. It is very important in
        "Legacy Installations", but in "Composer-based Installations" it is only
        used for configuring extensions (Composer then manages the (de-)installation
        of extensions).

    -   Extension Scanner

        The Extension Scanner analyzes installed extensions for compatibility
        issues for current and future TYPO3 versions. It can report fixes that
        are needed to upgrade a custom extension.

*   F
    -   FAL

        The File Abstraction Layer (FAL) is a system in TYPO3 that centralizes the
        management and access to files and media resources. This is the technical
        interface (API) to the integrated media asset database.

    -   fe_groups / be_groups

        Frontend Groups (fe_groups) and Backend Groups (be_groups) are user groups
        in TYPO3 that define different permissions and roles.

    -   felogin

        felogin is a TYPO3 system extension for managing and authenticating
        frontend users.

    -   feuser / beuser

        Frontend Users (feuser) and Backend Users (beuser) are the two main types
        of users in the TYPO3 system.

    -   file reference

        A File Reference is a reference to a file stored and used within the TYPO3
        system.

    -   file resource

        A File Resource is a physical file that is stored and managed within the
        TYPO3 system. A file reference always points to a file resource.

    -   file storage

        File Storage in TYPO3 manages the organization and storage of files and
        media resources. Other systems refer to this with a term like "asset storage".

    -   fileadmin

        The fileadmin area is a special folder in the TYPO3 backend where files and
        media resources are managed. This is the default name of file storages since
        TYPO3 versions, but can be customized.

    -   Filelist

        The Filelist is a module in the TYPO3 backend used for displaying and
        managing files and media resources. It displays contents of all configured
        file storages. When referencing files from content elements, a popup window
        will also display the Filelist in the Backend.

    -   Flash Message

        Flash Messages are temporary notifications in the TYPO3 backend that inform
        users about important events or changes. Also the Extbase framework allows
        to use an API to display these kinds of messages in the Frontend.

    -   FlexForm

        FlexForms are a selection of functionalities that allow to extend content
        element settings in the Backend, which can be accessed in the frontend.
        A FlexForm data source (XML format) defines available sheets, sections and
        fields, which are displayed alongside a record in the Backend record editing interface
        (based on TCA naming).
        The values entered in a FlexForm data source are also saved as XML data (as
        some kind of "blob", so it needs serialization and deserialization when being accessed),
        which allows for any kind of flexible additional data storage in parallel to the
        relational database tables (like tt_content).

    -   Fluid

        Fluid is a template engine in TYPO3 used for creating dynamic and
        customizable frontend layouts. The format looks like HTML and offers specific
        and extensible tags to be embedded. It also standard variable replacement as
        well as a large range of algorithmic and logical operations.

    -   Forge / Forger / Gerrit

        Forge is the central issue platform for letting the Core Team manage the TYPO3
        project and its features and bugs. Forger and Gerrit are tools for code review and management.

    -   Form Framework / Form Extension

        The Form Framework in TYPO3 is used to create and manage complex forms with
        various fields and validations. A Backend Module allows to configure these
        forms with a powerful GUI.

    -   Form Variants

        Form Variants are different versions or variations of a form built in the Form Framework,
        that can be defined and used within the TYPO3 system.

    -   FormEngine

        The FormEngine is a vital component in TYPO3 responsible for displaying all record
        and content editing parts in the Backend.

    -   fsc / csc

        fsc (Fluid Styled Content) and csc (CSS Styled Content) are system extensions that
        can be used to render content elements in the Frontend.

*   G
    -   GeneralUtility

        GeneralUtility is a central PHP class in TYPO3 that provides a variety of general
        utility functions and methods.

    -   GifBuilder

        GifBuilder is an API set in TYPO3 for creating and editing images. Even though it is
        called "Gif"-Builder, it can deal with all image formats and is used to embed
        overlays and other manipulation (color, geometry) into media files.

*   I
    -   Indexed Search

        Indexed Search is a system extension in TYPO3 for implementing search
        functionality on the website.

    -   Infobox

        An Infobox is a highlighted area on a page that contains important
        information or notices.

    -   Install Tool

        The Install Tool is a tool in the TYPO3 backend used for installing and
        configuring/upgrading the system.

    -   Integrator / Developer

        Integrator and Developer are roles within the TYPO3 ecosystem. Integrators
        are responsible for setting up and configuring the system, while developers
        create new extensions and features.

    -   Introduction Package

        The Introduction Package is an example package in TYPO3 that contains a
        pre-configured website with sample content and configurations.

    -   IRRE

        IRRE (Inline Relational Record Editing) is a feature in TYPO3 that allows
        for the editing of related records directly within the backend. It is displayed
        as a nested accordion structure (also supporint tabs) to manage child-records.

    -   ItemProcessor

        An ItemProcessor is a component in TYPO3 that processes and manipulates
        individual data elements to be used within the FormEngine.

*   L
    -   Legacy Installation

        TYPO3 can be operated in one of two modes: "Composer Installation" (using the
        Composer ecosystem and tooling to setup TYPO3, also referred to as "Composer mode")
        or "Legacy Installation", in which the TYPO3 distribution files are simply
        maintained as files and folders put onto a server.

    -   Link Browser

        The Link Browser is a tool in the TYPO3 backend for creating and managing
        links and references. It can be accessed when inserting links into content
        elements and is opened as a popup, allowing to pick pages, records, media files,
        or enter URLS for all fields configured as "link type", or within plain content
        edited through the RTE.

    -   LinkHandler

        The LinkHandler is a component in TYPO3 that provides advanced link and
        reference functionalities. Each kind of Link (like: files, pages, records,
        mails, telephone, ...) is implemented via the LinkHandler API.

    -   Linkvalidator

        Linkvalidator is a tool in TYPO3 that checks links and references on the
        website for validity and identifies broken or invalid links. It operates on
        the level of content elements and their specific data fields.

    -   List View

        The List View is a view in the TYPO3 backend used for displaying and
        managing records in a list format, usually for the File List.

*   M
    -   Maintenance Mode

        Maintenance Mode in TYPO3 is used to take the website offline temporarily
        for updates or maintenance. Only Maintainers (Administrators) are then
        able to access the Backend and/or Frontend.

    -   Maintenance Tool

        The Maintenance Tool is a tool in the TYPO3 backend used for performing
        maintenance tasks and system optimizations. It is part of the "Admin Tools"
        Backend module.

    -   makeInstance

        makeInstance is a method in the TYPO3 PHP API, used for creating instances of classes and
        objects. It can utilize "Dependency Injection" for service classes.

    -   Modal

        A Modal is a dialog or pop-up window in TYPO3 that prompts users to enter or
        confirm information.

    -   Module

        A Module is an extendable component in TYPO3 that provides various
        functionalities and tools. Modules usually come in the form of "Backend Modules",
        and are part of the left-hand side navigation.

    -   Multisite

        Multisite refers to the capability of TYPO3 to manage multiple distinct websites
        from a single installation.

*   O
    -   Overrides

        Overrides, specifically "TCA Overrides", allow TYPO3 extensions to change
        central configuration of records and content elements.

*   P
    -   Package

        A Package is a bundle of files and resources used for installing and
        configuring extensions or functionalities in TYPO3. Commonly, TYPO3 extensions
        are provided as "Composer Packages", where this term is the short form of.

    -   Page Frame / Tree Frame / Module Frame / Navigation Frame

        Page Frame, Tree Frame, and Module Frame are various sections in the TYPO3
        backend used for displaying and navigating content and modules.

    -   Page Tree

        The Page Tree is a hierarchical representation of the page structure in the
        TYPO3 backend used for navigating and managing the website. It is shown in
        the middle section of the TYPO3 Backend in the places where content is edited.

    -   Page View

        The Page View is a view in the TYPO3 backend used for editing and managing
        individual page content.

    -   Pagebuilder

        Pagebuilders are tools in TYPO3 for creating and designing page layouts
        and content. Pagebuilders are often used to create "Sitepackage extensions",
        which define the central TYPO3 frontend look and the definitions of content elements.
        Since these sitepackages can often be repetetive and contain boilerplate code,
        Pagebuilders can help to auto-generate these sitepackages.

    -   PageRenderer

        The PageRenderer is a PHP API component in TYPO3 responsible for rendering and
        displaying page content in the frontend.

    -   Palette (TCA)

        A Palette in the TCA (Table Configuration Array) is a grouping of fields
        that can be displayed and edited together.

    -   Partial

        A Partial is a re-usable component of Fluid templates, that can be parametrized.

    -   Permissions / ACL

        Permissions and Access Control Lists (ACL) are mechanisms in TYPO3 for
        managing access rights and restrictions for users and groups.

    -   piBase

        piBase is a base class for developing frontend plugins in TYPO3.
        Nowadays, it has been superseded by Extbase or completely custom PHP-code
        plugins.

    -   pid / uid

        Each page and content element as a unique identifier (uid) assigned to it.
        The "pid" stands for "parent id" and references this uid for any child
        records.

    -   Plugin

        A Plugin is an extension in TYPO3 that adds additional functionalities and
        features to the website. The term "Frontend plugin" usually defines a
        specific content element that renders individual dynamic frontend functionalities
        by utilizing Extbase, Fluid or raw PHP code.

    -   Processed file

        A processed file is a file that has been handled and optimized by TYPO3,
        such as being cropped or compressed. It is a persisted artifact that can
        be regenerated, if missing.

*   R
    -   Realurl

        Realurl was a commonly used TYPO3 extension that created and managed user-friendly URLs.
        Now, the TYPO3 Core offers exhaustive URL rewriting capabilities with Site Matchers,
        Route Enhancers/Decorators and slugs.

    -   Records

        A record is the smallest unit of a database entry. A record can be a "Content Element",
        but also any kind of configuration record, data storage record, user data record and much more.
        Records are defined via TCA and according to their configuration can be edited in the
        Backend GUI.

    -   recycler

        The Recycler is a tool in the TYPO3 backend for managing and restoring
        deleted records.

    -   Redirects

        Redirects are links that direct users from one URL to another, often used to
        correct outdated or invalid links.

    -   RenderType

        RenderType is a setting in TYPO3 that defines the rendering mode of fields
        and content elements when displayed in the FormEngine.

    -   Repository

        This term is usually referred to in Extbase-context, and defines a PHP API
        class in Domain Driven Design, that manages access to entities/models
        defined through configuration and database records.

    -   reports

        Reports are analyses and insights in the TYPO3 backend that provide
        information about system performance and usage of extensions.

    -   reST / reStructuredText

        reST (reStructuredText) is a markup format used for creating and formatting
        documentation in the official TYPO3 documentation and public extensions.

    -   Route Enhancer

        A Route Enhancer is a component in TYPO3 used for improving and customizing
        the URL routing logic. It is part of the YAML Site Configuration

    -   Route Decorator / Enhancing Decorator

        Route Decorators and Enhancing Decorators are part of the Route Enhancement,
        and can be seen as configuration and API implementations offering access to
        rewriting and accessing the URL routing.

    -   RTE (also: WYSIWYG, CKEditor, htmlarea, t3editor)

        A Rich Text Editor (RTE) is a tool in TYPO3 that enables WYSIWYG editing
        (What You See Is What You Get), offered via the CKEditor Open Source Project.
        An older component was "htmlarea". The t3editor is a specific RTE that handles
        syntax-highlighting for code languages.

    -   runTests.sh (?)

        runTests.sh is utility Script provided internally by the TYPO3 Core, which
        allows to run several tests (functional tests, unit tests, acceptance tests) and manage
        the Core Developers instances for building assets.

*   S
    -   scheduler

        The Scheduler is a tool in TYPO3 that manages and executes scheduled tasks, like
        regular purging of temporary data or any kind of regular custom activity.

    -   Scheduler Tasks

        Scheduler Tasks in TYPO3 are automated jobs that can be scheduled to run at
        specific times or intervals.

    -   showfields (TCA)

        showfields are part of the settings in the TCA (Table Configuration Array) that defines
        which fields are displayed in the FormEngine Backend GUI.

    -   SignalSlot / Hook / Event Dispatcher + Listeners

        SignalSlot was a design pattern in TYPO3 for implementing event-driven
        programming and allowing components to communicate with each other. This was superseded
        by the PSR-14 compatible Event-API (using a Dispatcher and Event Listeners).

    -   Site Configuration

        A Site Configuration includes settings and options that affect the behavior
        and display of a TYPO3 website, mapped to a specific domain (with variants).
        The Site Configuration also include Site Settings, which is a simple key/value
        storage of variables that can affect the Frontend (or Backend sections).

    -   Site Language / Page Language

        Site Language and Page Language define the languages in which a TYPO3
        website and its content are displayed. It is part of the Site Configuration.

    -   Site Management

        Site Management includes tools and functions for managing and maintaining a
        TYPO3 website, including the Site Configuration of each site.

    -   Site Matcher

        A Site Matcher is a component in TYPO3 used for mapping and processing URL
        patterns and requests in conjunction with a specific part of the Page Tree (Root Page/Site).

    -   Site Package

        A Site Package is a pre-configured package in TYPO3 that usually contains
        configuration, Content Elements, functionality (like PSR-14 event listeners,
        middlewares), Templates and maybe even sample preset content.

    -   Site Sets

        Site Sets are predefined collections of settings and configurations used
        for setting up and managing TYPO3 websites, mainly grouping TypoScript configuration
        to a Site.

    -   Sites

        Sites are the various websites / projects managed and operated within
        the TYPO3 system. It can be regarded as the short form for "Website".

    -   Slug

        A Slug is a user-friendly URL part, often generated from the page title or
        content elements. A URL can consist of multiple slug parts.

    -   Static File Cache

        Static File Cache in TYPO3 is an extension that is used to store pre-rendered
        pages as static files to improve performance, like a static page generator.

    -   Styleguide

        The Styleguide extension is a collection of example TCA-based content elements
        to showcase the functionality of TYPO3. It also features an example Page Tree for both
        these backend elements, as well as a Frontend Example Site.
        On top of that, the module showcases all GUI elements (like dialogs, alerts, colors,
        accordions, grids, ...) that TYPO3 uses in the Backend.

    -   SVG Tree

        The SVG Tree is a visual representation of the page and content structure of
        a TYPO3 website in SVG format. This is the technical visual implementation of the
        "Page Tree"

    -   sys_log / sys_history

        The sys_log and sys_history are database tables in TYPO3 for recording and tracking
        system events and changes.

    -   sysext

        Sysexts are SYStem EXTensions in TYPO3 that provide core functions
        and features. This is the name of a central TYPO3 Core Sourcecode directory,
        and in older TYPO3 versions there was a stronger seperation of "System Extension" and
        "Local Extension".

*   T
    -   T3DD

        T3DD stands for TYPO3 Developer Days, an annual conference for TYPO3
        developers and enthusiasts.

    -   TCA

        The Table Configuration Array (TCA) is a central configuration structure in
        TYPO3 for defining and managing database tables and fields.

    -   TCEforms

        TCEforms are forms in TYPO3 used for editing database entries and content
        elements in the backend.

    -   Templates (=Fluid)

        Templates in TYPO3, often created with Fluid, define the structure and
        layout of the frontend display.

    -   TER

        The TYPO3 Extension Repository (TER) is a central directory for distributing TYPO3
        extensions.

    -   Testing Framework

        The Testing Framework in TYPO3 provides tools and methods for conducting
        automated tests used for developing the TYPO3 Core or custom projects and
        extensions.

    -   TSconfig

        TSconfig uses the TypoScript configuration language in TYPO3 and is used for defining
        backend settings and configuration options. This is seperated into "User TSConfig"
        and "Page TSConfig"

*   U
    -   uid

        uid stands for Unique Identifier and is a unique identifier for records and
        objects in the TYPO3 system. It complements the "pid" (parent identifier).

    -   upgrade wizard

        The Upgrade Wizard is a module in the TYPO3 backend used for performing system
        and database upgrades.

*   V
    -   Vendor

        The term "Vendor" is most commonly used as a semantic grouping identifier for
        PHP namespaces in developed extensions. Composer collects all packages in a directory,
        that is also usually called "vendor" and contains subdirectories with each of those
        PHP namespace identifiers. A Vendor can then provide multiple distinct extensions,
        each separated by an extension name identifier. The PHP Composer Class-Loading functionality
        depends on these two basic identifiers.

    -   ViewHelper

        ViewHelpers are logical helper functions, utilized in Fluid templates and partials.
        ViewHelpers are implemented as PHP code and can perform any kind of functionality,
        however it is suggested to only use this for managing context of Frontend Output,
        and should not contain too much domain logic.

*   W
    -   Workspace(s)

        Workspaces are areas in TYPO3 used for managing and editing content in a "versioned"
        way. They allow to prepare content to be published, and verified in workflow steps
        before.

    -   Web Component

        The TYPO3 Core's Backend has considerable use of JavaScript-based, standards-compliant
        web components. These offer dynamic functionality using a standards-driven approach,
        compatible with most browsers and offering graceful degradation.

*   X
    -   XCLASS

        XCLASS is a mechanism in TYPO3 that allows developers to extend or override
        existing classes and functions. The TYPO3 Core can then replace one instance of a class
        with another custom class.