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

    ..  _admin-panel:
    -   *Admin Panel*

        The Admin Panel is an administrative tool that can be enabled in the
        frontend to show debugging information, performed SQL queries and more
        for authenticated backend users.

    ..  _admin-tools:
    -   *Admin Tools*

        Admin tools are a group of backend modules. These include maintaining
        the installation, adjusting settings, executing upgrade wizards,
        checking environment information and setting up extensions.

    ..  _allow-fields:
    -   *Allow Fields*

        Allow fields refer to fields of content elements displayed in the TYPO3
        backend with regard to their permissions. Editors can only edit fields in
        the backend which are included in the list of "Allow fields" in their
        permission setup.

    ..  _assets:
    -   *Assets*

        Assets are media resources such as images, videos and documents that are
        uploaded and managed in the TYPO3 system. Also, extensions can include
        assets which can be referred to in the frontend, like specific icons or
        JavaScript libraries.

*   B

    ..  _backend---frontend:
    -   *Backend / Frontend*

        The Backend and Frontend are the two main areas of TYPO3 CMS. The backend is
        the administrative interface for editors and administrators. The
        frontend is the publicly accessible part of the website.

    ..  _backend-bookmarks:
    -   *Backend Bookmarks*

        Backend bookmarks are shortcuts that users can set for frequently used
        backend pages for quicker access.

    ..  _backend-layout:
    -   *Backend Layout*

        The backend layout defines the structure and design of the backend user
        interface for maintaining content elements and the layout
        of their input fields. A backend layout can be set on the page-level, and
        this attribute can actually be also evaluated in the frontend, to affect
        the arrangement of elements on a page.

    ..  _backend-module:
    -   *Backend Module*

        Backend modules are extendable components in the TYPO3 backend that
        provide various functionalities and tools such as user management and file
        management. The left hand panel in the backend display all the modules.

*   C

    ..  _callout:
    -   *Callout*

        A callout is a highlighted element designed to draw attention to
        important information or actions.

    ..  _cache--cache-backend--frontend-cache:
    -   *Cache (Cache Backend, Frontend Cache)*

        Caches are used to improve website performance by storing frequently
        accessed data. TYPO3 has multiple caches for various performance relevant areas in both for the frontend and backend.

    ..  _cache-tags:
    -   *Cache Tags*

        With cache tags one or more cache entries can be grouped together such that 
        all cache entries related to a cache tag can be invalidated with just one call.

    ..  _certification--t-cc--t-cd--t-ci--t-ce:
    -   *Certification (TCCC, TCCD, TCCI, TCCE)*

        Certifications in the TYPO3 ecosystem, such as TCCC (Consultant), TCCD
        (Developer), TCCI (Integrator), and TCCE (Editor) confirm the
        proficiency of developers and integrators in various aspects of TYPO3
        CMS. TYPO3 has an official certification strategy.

    ..  _cig-sig--special-interest-group:
    -   *CIG/SIG (Special Interest Group)*

        Special Interest Groups (SIGs) are groups of experts and enthusiasts who
        focus on specific topics within the TYPO3 ecosystem and work on
        improving those areas.

    ..  _clipboard:
    -   *Clipboard*

        The clipboard in the TYPO3 backend is a tool for copying, cutting, and
        pasting content elements and records.

    ..  _colpos:
    -   *colPos*

        :spl:`colPos` is a column in the TYPO3 database that defines the
        position and layout of content elements on a page within a template.

    ..  _constants-setup:
    -   *Constants/Setup*

        Constants and Setup are configuration options in TYPO3 TypoScript that
        set basic settings and variables for the website. "Constants" can be
        seen as variables that reference content defined in the backend GUI.
        The "Setup" uses these "Constants" to put the variables
        where they are needed, to define behaviour of the frontend (and sometimes also
        backend).

    ..  _content-blocks:
    -   *Content Blocks*

        Content blocks are predefined layouts and content elements that can be
        used to create page content in the TYPO3 backend. Currently *Content Blocks* refers to
        an extension which will be included in TYPO3 v13. Content
        Blocks are small sets of configuration, defining both Backend input and
        frontend output.

    ..  _content-elements:
    -   *Content Elements*

        Content elements in TYPO3 are building blocks of content that can be shown
        in the frontend. Each content element has many (and also custom)
        attributes, even consisting of nested hierachies of further content
        elements.

    ..  _core:
    -   *Core*

        The TYPO3 Core is the central framework of the CMS that provides all
        basic functions and features.

    ..  _core-development:
    -   *Core Development*

        Core Development refers to the development and maintenance of the
        central TYPO3 framework by the Core Team.

    ..  _core-merger:
    -   *Core Merger*

        A Core Merger is a person or team member responsible for merging code
        changes and updates into the TYPO3 core. TYPO3 Core Mergers are elected
        in a formal process.

    ..  _core-team:
    -   *Core Team*

        The Core Team consists of the main developers (Core Mergers) and contributors
        responsible for developing and maintaining the TYPO3 core.

    ..  _crop-variants:
    -   *Crop variants*

        Crop Variants are different cropping options for images that can be
        defined and used within the TYPO3 system, for example an image can have
        a crop variant for "mobile" and "desktop", or different aspect ratios.
        or any custom scheme.

    ..  _crowdin:
    -   *Crowdin*

        `Crowdin <https://crowdin.com/>`__ is a translation tool used for localizing and translating TYPO3
        content into different languages.

    ..  _ctype:
    -   *CType*

        :sql:`CType` stands for Content Type and is a database column field of
        the vital "tt_content" database table, where all content elements are
        stored. This column defines the name of a specific element, and
        influences how it is presented in the backend and frontend.

*   D

    ..  _dashboard---widgets:
    -   *Dashboard / Widgets*

        The dashboard is a customizable start page in the TYPO3 backend that
        contains various widgets for displaying important information and quick
        access.

    ..  _data-processor:
    -   *Data Processor*

        A data processor is a component that processes and manipulates data
        before it is displayed in the TYPO3 frontend. Data processors are
        implemented as PHP code and can be executed through TypoScript
        configuration and affect data passed on to Fluid templates. Thus, it is
        a specific implementation to operate on data before it is passed on to
        the presentation layer (Fluid templates).

    ..  _data-provider:
    -   *Data Provider*

        A data provider is a source of data that can be used by other components
        within the TYPO3 system. Data providers are commonly used for passing on
        data in the backend (for example defining available icons, item keys and
        values).

    ..  _datahandler:
    -   *DataHandler*

        The DataHandler is a central component in TYPO3 responsible for
        processing and storing data changes. It is a large PHP class that is
        used in the backend to receive data from the FormEngine (content
        elements and records), and is also part of an extensive API that can be
        used by extensions to operate on records.

    ..  _db-analyzer---db-compare:
    -   *DB Analyzer / DB Compare*

        DB Analyzer and DB Compare are tools in TYPO3 that analyze and compare
        database structures to identify needed changes on the database-level for
        both for system upgrades and extension integration. Other systems often
        call this "database migration".

    ..  _db-mounts---mount-points:
    -   *DB Mounts / Mount Points*

        Mount points allow TYPO3 editors to mount a page (and its subpages) from
        a different area in the current backend page tree.

    ..  _dbal:
    -   *DBAL*

        The Database Abstraction Layer (DBAL) is collection of API Interfaces and Classes in TYPO3
        that allows abstract access to various database systems. This allows to executing SQL queries without special adaptation to the supported database systems likeMariaDB, MySQL, PostgreSQL and SQLite.

*   E

    ..  _enhancer:
    -   *Enhancer*

        An enhancer is a component that adds additional functionalities or
        improvements to existing TYPO3 features, most commonly used for
        "Routing Enhancers" operating on speaking URL fragments.

    ..  _exclude-fields:
    -   *Exclude Fields*

        Exclude fields are fields that have been configured to allow being
        hidden in the TYPO3 backend for specific users or user groups. This is
        done via the permission setup.

    ..  _extbase:
    -   *Extbase*

        Extbase is a framework for developing extensions in the TYPO3 system
        based on the Model-View-Controller (MVC) principle. It allows to easily
        define models with their data fields (stored as records), that can be managed by editors in
        the backend. The models can then also be revealed in the frontend with
        any custom logic, adhering to standards, conventions and API
        definitions. The Extbase controllers which are part of an Extbase plugin
        allow to integrate this custom logic in PHP.

    ..  _extension:
    -   *Extension*

        An extension is an add-on to the TYPO3 system that adds additional
        functionalities and features. An extension can consist of multiple
        parts, for example backend modules, frontend plugins, scheduler tasks,
        console commands, API definitions, frontend styling and much more.

    ..  _extension-builder:
    -   *Extension Builder*

        The Extension Builder is a backend module in TYPO3 that facilitates the
        creation of (preferably) extbase extensions. The Extension Builder is a
        community extension and maintained on its own.

    ..  _extension-manager:
    -   *Extension Manager*

        The Extension Manager is an interface in the TYPO3 backend used for
        installing, updating, and managing extensions. It is very important in
        legacy installations, but in Composer-based installations it is only
        used for configuring extensions (composer then manages the
        (de-)installation of extensions).

    ..  _extension-scanner:
    -   *Extension Scanner*

        The Extension Scanner analyzes installed extensions for compatibility
        issues for current and future TYPO3 versions. It can report fixes that
        are needed to upgrade a custom extension.

*   F

    ..  _fal:
    -   *FAL*

        The File Abstraction Layer (FAL) is a system in TYPO3 that centralizes
        the management and access to files and media resources. This is the
        technical interface (API) to the integrated media asset database.

    ..  _fe-groups---be-groups:
    -   *fe_groups / be_groups*

        Frontend groups :sql:`fe_groups` and backend groups :sql:`be_groups`
        are user groups in TYPO3 that define different permissions and roles. Frontend groups restrict frontend content and possible actions to specific users in those groups. Backend groups allow to define permissions on what content and actions can be performed in the backend.

    ..  _felogin:
    -   *felogin*

        :t3ext:`felogin` is a TYPO3 system extension for managing and
        authenticating frontend users.

    ..  _fe-users---be-users:
    -   *fe_users / be_users*

        Frontend users :sql:`fe_users` and backend users :sql:`be_users` are the
        two main types of users in the TYPO3 system.

    ..  _file-reference:
    -   *file reference*

        A file reference is a reference to a file stored and used within the
        TYPO3 system. A file reference (in comparison to a file copy) is only a pointer to the original file, so when the original file changes, all references will too.

    ..  _file-resource:
    -   *file resource*

        A file resource is a physical file that is stored and managed within the
        TYPO3 system. A file reference always points to a file resource.

    ..  _file-storage:
    -   *file storage*

        File storage in TYPO3 manages the organization and storage of files and
        media resources. Other systems refer to this with a term like
        "asset storage".

    ..  _fileadmin:
    -   *fileadmin*

        The :file:`fileadmin` area is a special folder in the TYPO3 backend
        where files and media resources are managed. This is the default name of
        file storages since TYPO3 versions, but can be customized.

    ..  _filelist:
    -   *Filelist*

        The :t3ext:`filelist` is a module in the TYPO3 backend used for
        displaying and managing files and media resources. It displays contents
        of all configured file storages. When referencing files from content
        elements, a popup window will also display the filelist in the backend.

    ..  _flash-message:
    -   *Flash Message*

        Flash Messages are temporary notifications in the TYPO3 backend that
        inform users about important events or changes. Also the Extbase
        framework allows to use an API to display these kinds of messages in the
        frontend.

    ..  _flexform:
    -   *FlexForm*

        FlexForms are a selection of functionalities that allow to extend
        content element settings in the Backend, which can be accessed in the
        frontend. A flexForm data source (XML format) defines available sheets,
        sections and fields, which are displayed alongside a record in the
        backend record editing interface (based on TCA naming).
        The values entered in a FlexForm data source are also saved as XML data
        (as some kind of "blob", so it needs serialization and deserialization
        when being accessed), which allows for any kind of flexible additional
        data storage in parallel to the relational database tables (like
        :sql:`tt_content`).

    ..  _fluid:
    -   *Fluid*

        Fluid is a template engine in TYPO3 used for creating dynamic and
        customizable frontend layouts. The format looks like HTML and offers
        specific and extensible tags to be embedded. It also standard variable
        replacement as well as a large range of algorithmic and logical
        operations.

    ..  _forge---forger---gerrit:
    -   *Forge / Forger / Gerrit*

        `Forge <https://forge.typo3.org/>`__ is the central issue platform for
        letting the Core Team manage the TYPO3 project and its features and
        bugs. `Forger <https://forger.typo3.com/>`__ and `Gerrit
        <https://review.typo3.org/>`__
        are tools for code review and management.

    ..  _form-framework---form-extension:
    -   *Form Framework / Form Extension*

        The :t3ext:`form` framework in TYPO3 is used to create and manage
        complex forms with various fields and validations. A backend module
        allows to configure these forms with a powerful GUI.

    ..  _form-variants:
    -   *Form Variants*

        Form Variants are different versions or variations of a form built in
        the form framework, that can be defined and used within the TYPO3
        system.

    ..  _formengine:
    -   *FormEngine*

        The FormEngine is a vital component in TYPO3 responsible for displaying all record
        and content editing parts in the backend.

    ..  _fsc---csc:
    -   *fsc / csc*

        fsc (Fluid Styled Content) and csc (CSS Styled Content) are system
        extensions that can be used to render content elements in the frontend.

*   G

    ..  _generalutility:
    -   *GeneralUtility*

        GeneralUtility is a central PHP class in TYPO3 that provides a variety
        of general utility functions and methods.

    ..  _gifbuilder:
    -   *GifBuilder*

        GifBuilder is an API set in TYPO3 for creating and editing images. Even
        though it is called "Gif"-Builder, it can deal with all image formats
        and is used to embed overlays and other manipulation (color, geometry)
        into media files.

*   I

    ..  _indexed-search:
    -   *Indexed Search*

        Indexed Search is a system extension in TYPO3 for implementing search
        functionality on the website.

    ..  _infobox:
    -   *Infobox*

        An infobox is a highlighted area on a page that contains important
        information or notices.

    ..  _install-tool:
    -   *Install Tool*

        The Install Tool is a tool in the TYPO3 backend used for installing and
        configuring/upgrading the system.

    ..  _integrator---developer:
    -   *Integrator / Developer*

        Integrator and Developer are roles within the TYPO3 ecosystem.
        Integrators are responsible for setting up and configuring the system,
        while developers create new extensions and features.

    ..  _introduction-package:
    -   *Introduction Package*

        The Introduction Package is an example package in TYPO3 that contains a
        pre-configured website with sample content and configurations.

    ..  _irre:
    -   *IRRE*

        IRRE (Inline Relational Record Editing) is a feature in TYPO3 that
        allows for the editing of related records directly within the backend.
        It is displayed as a nested accordion structure (also supporting tabs)
        to manage child-records.

    ..  _itemprocessor:
    -   *ItemProcessor*

        An ItemProcessor is a component in TYPO3 that processes and manipulates
        individual data elements to be used within the FormEngine.

*   L

    ..  _legacy-installation:
    -   *Legacy Installation*

        TYPO3 can be operated in one of two modes: "Composer Installation"
        (using the Composer ecosystem and tooling to setup TYPO3, also referred
        to as "Composer mode") or "Legacy Installation", in which the TYPO3
        distribution files are simply maintained as files and folders put onto a
        server.

    ..  _link-browser:
    -   *Link Browser*

        The Link Browser is a tool in the TYPO3 backend for creating and
        managing links and references. It can be accessed when inserting links
        into content elements and is opened as a popup, allowing to pick pages,
        records, media files, or enter URLS for all fields configured as "link
        type", or within plain content edited through the RTE.

    ..  _linkhandler:
    -   *LinkHandler*

        The LinkHandler is a component in TYPO3 that provides advanced link and
        reference functionalities. Each kind of Link (like: files, pages,
        records, mails, telephone, ...) is implemented via the LinkHandler API.

    ..  _linkvalidator:
    -   *Linkvalidator*

        Linkvalidator is a tool in TYPO3 that checks links and references on the
        website for validity and identifies broken or invalid links. It operates
        on the level of content elements and their specific data fields.

    ..  _list-view:
    -   *List View*

        The :guilabel:`Web -> List` view is a view in the TYPO3 backend used for
        displaying and managing records in a list format.

*   M

    ..  _maintenance-mode:
    -   *Maintenance Mode*

        Maintenance Mode in TYPO3 is used to take the website offline
        temporarily for updates or maintenance. Only maintainers
        (administrators) are then able to access the backend and frontend.

    ..  _maintenance-tool:
    -   *Maintenance Tool*

        The Maintenance Tool is a tool in the TYPO3 backend used for performing
        maintenance tasks and system optimizations. It is part of the "Admin
        Tools" backend module.

    ..  _makeinstance:
    -   *makeInstance*

        `GeneralUtility::makeInstance()` is a method in the TYPO3 PHP API, used for creating
        instances of classes and objects. It can utilize "Dependency Injection"
        for service classes.

    ..  _modal:
    -   *Modal*

        A modal is a dialog or pop-up window in TYPO3 that prompts users to
        enter or confirm information.

    ..  _module:
    -   *Module*

        A module is a component that expands the TYPO3 backend by providing various
        functionalities and tools. Modules usually come in the form of
        "Backend Modules", and are part of the left-hand side navigation.

    ..  _multisite:
    -   *Multisite*

        Multisite refers to the capability of TYPO3 to manage multiple distinct
        websites from a single installation.

*   O

    ..  _overrides:
    -   *Overrides*

        Overrides, specifically "TCA Overrides", allow TYPO3 extensions to
        change central configuration of records and content elements.

*   P

    ..  _package:
    -   *Package*

        A Package is a bundle of files and resources used for installing and
        configuring extensions or functionalities in TYPO3. Commonly, TYPO3
        extensions are provided as "Composer Packages", where this term is the
        short form of.

    ..  _page-frame---tree-frame---module-frame---navigation-frame:
    -   *Page Frame / Tree Frame / Module Frame / Navigation Frame*

        Page frame, Tree frame, and Module frame are various sections in the
        TYPO3 backend used for displaying and navigating content and modules.

    ..  _page-tree:
    -   *Page Tree*

        The Page Tree is a hierarchical representation of the page structure in
        the TYPO3 backend used for navigating and managing the website. It is
        shown in the middle section of the TYPO3 Backend in the places where
        content is edited.

    ..  _page-view:
    -   *Page View*

        The Page View is a view in the TYPO3 backend used for editing and
        managing individual page content.

    ..  _pagebuilder:
    -   *Page builder* / *Sitepackage Builder*

        A Sitepackage Builder, or Pagebuilders, are tools in TYPO3 for creating and designing page layouts
        and content. They are often used to create "Sitepackage
        extensions", which define the central TYPO3 frontend look and the
        definitions of content elements. Since these sitepackages can often be
        repetitive and contain boilerplate code, buliders can help to
        auto-generate these sitepackages.

    ..  _pagerenderer:
    -   *PageRenderer*

        The PageRenderer is a PHP API component in TYPO3 responsible for
        rendering and displaying page content in the frontend.

    ..  _palette--tca:
    -   *Palette (TCA)*

        A Palette in the TCA (Table Configuration Array) is a grouping of fields
        that can be displayed and edited together.

    ..  _partial:
    -   *Partial*

        A Partial is a re-usable component of Fluid templates, that can be
        parametrized.

    ..  _permissions---acl:
    -   *Permissions / ACL*

        Permissions and Access Control Lists (ACL) are mechanisms in TYPO3 for
        managing access rights and restrictions for users and groups.

    ..  _pibase:
    -   *piBase*

        piBase was a base class for developing frontend plugins in TYPO3. The name "piBase" is based on the old class `class.tslib_pibase.php` ("pi" for "PlugIn"), which is today moved into a `AbstractPlugin` API class and provides base functionality that can be extended. 
        Nowadays, it has been superseded by Extbase or completely custom
        PHP-code plugins.

    ..  _pid---uid:
    -   *pid / uid*

        Each page and content element as a unique identifier (uid) assigned to
        it. The :sql:`pid` stands for "parent id" and references this :sql:`uid`
        for any child records.

    ..  _plugin:
    -   *Plugin*

        A plugin is an extension in TYPO3 that adds additional functionalities
        and features to the website. The term "Frontend plugin" usually defines
        a specific content element that renders individual dynamic frontend
        functionalities by utilizing Extbase, Fluid or raw PHP code.

    ..  _processed-file:
    -   *Processed file*

        A processed file is a file that has been handled and optimized by TYPO3,
        such as being cropped or compressed. It is a persisted artifact that can
        be regenerated, if missing.

*   R

    ..  _realurl:
    -   *Realurl*

        Realurl was a commonly used TYPO3 community extension that created and managed
        user-friendly URLs. Now, the TYPO3 Core offers exhaustive URL rewriting
        capabilities with Site Matchers, Route Enhancers/Decorators and slugs.

    ..  _records:
    -   *Records*

        A record is the smallest unit of a database entry. A record can be a
        content element but also any kind of configuration record, data storage
        record, user data record and much more. Records are defined via TCA and
        according to their configuration can be edited in the backend GUI.

    ..  _recycler:
    -   *recycler*

        The Recycler is a backend module for managing and restoring
        deleted records.

    ..  _redirects:
    -   *Redirects*

        Redirects are links that direct users from one URL to another, often
        used to correct outdated or invalid links.

    ..  _rendertype:
    -   *RenderType*

        RenderType is a TCA setting in TYPO3 that defines the rendering mode of
        fields and content elements when displayed in the FormEngine.

    ..  _repository:
    -   *Repository*

        This term is usually referred to in Extbase-context, and defines a PHP
        API class in Domain Driven Design (DDD), that manages access to
        entities/models defined through configuration and database records.

    ..  _reports:
    -   *reports*

        Reports are analyses and insights in the TYPO3 backend that provide
        information about system performance and usage of extensions.

    ..  _rest---restructuredtext:
    -   *reST / reStructuredText*

        reST (reStructuredText) is a markup format used for creating and
        formatting documentation in the official TYPO3 documentation and public
        extensions.

    ..  _route-enhancer:
    -   *Route Enhancer*

        A Route Enhancer is a component in TYPO3 used for improving and
        customizing the URL routing logic. It is part of the YAML Site
        configuration.

    ..  _route-decorator---enhancing-decorator:
    -   *Route Decorator / Enhancing Decorator*

        Route Decorators and Enhancing Decorators are part of the Route
        enhancement and can be seen as configuration and API implementations
        offering access to rewriting and accessing the URL routing.

    ..  _rte-wysiwyg-ckeditor-htmlarea-t3editor:
    -   *RTE (also: WYSIWYG, CKEditor, htmlarea, t3editor)*

        A Rich Text Editor (RTE) is a tool in TYPO3 that enables WYSIWYG editing
        (What You See Is What You Get), offered via the CKEditor Open Source
        project. An older component was "rte_htmlarea". The t3editor is a
        specific RTE that handles syntax-highlighting for code languages.

    ..  _runtests-sh:
    -   *runTests.sh (?)*

        runTests.sh is utility Script provided internally by the TYPO3 Core,
        which allows to run several tests (functional tests, unit tests,
        acceptance tests) and manage the Core developers instances for building
        assets.

*   S

    ..  _scheduler:
    -   *scheduler*

        The scheduler is a backend module that manages and executes scheduled
        tasks, like regular purging of temporary data or any kind of regular
        custom activity.

    ..  _scheduler-tasks:
    -   *Scheduler Tasks*

        Scheduler tasks in TYPO3 are automated jobs that can be scheduled to run
        at specific times or intervals.

    ..  _showfields--tca:
    -   *showfields (TCA)*

        showfields are part of the settings in the TCA (Table Configuration
        Array) that defines which fields are displayed in the FormEngine backend
        GUI.

    ..  _signalslot---hook---event-dispatcher---listeners:
    -   *SignalSlot / Hook / Event Dispatcher + Listeners*

        SignalSlot was a design pattern in TYPO3 for implementing event-driven
        programming and allowing components to communicate with each other. This
        was superseded by the PSR-14 compatible Event-API (using a Dispatcher
        and Event Listeners).

    ..  _site-configuration:
    -   *Site Configuration*

        A Site Configuration includes settings and options that affect the
        behavior and display of a TYPO3 website, mapped to a specific domain
        (with variants). The Site Configuration also include site settings,
        which is a simple key/value storage of variables that can affect the
        frontend (or backend sections).

    ..  _site-language---page-language:
    -   *Site Language / Page Language*

        Site language and page language define the languages in which a TYPO3
        website and its content are displayed. It is part of the site
        configuration.

    ..  _site-management:
    -   *Site Management*

        Site management includes tools and functions for managing and
        maintaining a TYPO3 website, including the site configuration of each
        site.

    ..  _site-matcher:
    -   *Site Matcher*

        A site matcher is a component in TYPO3 used for mapping and processing
        URL patterns and requests in conjunction with a specific part of the
        page tree (root page/site).

    ..  _site-package:
    -   *Site Package*

        A site package is a pre-configured package in TYPO3 that usually
        contains configuration, Content Element definitions, functionality (like PSR-14
        event listeners, middlewares), Templates and maybe even sample preset
        content.

    ..  _site-sets:
    -   *Site Sets*

        Site Sets are predefined collections of settings and configurations used
        for setting up and managing TYPO3 websites, mainly grouping TypoScript
        configuration to a site.

    ..  _sites:
    -   *Sites*

        Sites are the various websites / projects managed and operated within
        the TYPO3 system. It can be regarded as the short form for "Website".

    ..  _slug:
    -   *Slug*

        A slug is a user-friendly URL part, often generated from the page title
        or content elements. A URL can consist of multiple slug parts.

    ..  _static-file-cache:
    -   *Static File Cache*

        Static file cache in TYPO3 is an extension that is used to store
        pre-rendered pages as static files to improve performance, like a static
        page generator.

    ..  _styleguide:
    -   *Styleguide*

        The styleguide extension is a collection of example TCA-based content
        elements to showcase the functionality of TYPO3. It also features an
        example page tree for both these backend elements, as well as a frontend
        example site.
        On top of that, the module showcases all GUI elements (like dialogs,
        alerts, colors, accordions, grids, ...) that TYPO3 uses in the backend.

    ..  _svg-tree:
    -   *SVG Tree*

        The SVG tree is a visual representation of the page and content
        structure of a TYPO3 website in SVG format. This is the technical visual
        implementation of the page tree.

    ..  _sys-log---sys-history:
    -   *sys_log / sys_history*

        The :sql:`sys_log` and :sql:`sys_history` are database tables in TYPO3
        for recording and tracking system events and changes.

    ..  _sysext:
    -   *sysext*

        Sysexts are SYStem EXTensions in TYPO3 that provide core functions
        and features. This is the name of a central TYPO3 Core Sourcecode
        directory, and in older TYPO3 versions there was a stronger separation
        of system extension and local extension.

*   T

    ..  _t3dd:
    -   *T3DD*

        T3DD stands for TYPO3 Developer Days, an annual conference for TYPO3
        developers and enthusiasts.

    ..  _tca:
    -   *TCA*

        The Table Configuration Array (TCA) is a central configuration structure
        in TYPO3 for defining and managing database tables and fields.

    ..  _tceforms:
    -   *TCEforms*

        TCEforms are forms in TYPO3 used for editing database entries and
        content elements in the backend.

    ..  _templates---fluid:
    -   *Templates (=Fluid)*

        Templates in TYPO3, often created with Fluid, define the structure and
        layout of the frontend display.

    ..  _ter:
    -   *TER*

        The TYPO3 Extension Repository (TER) is a central directory for
        distributing TYPO3 extensions.

    ..  _testing-framework:
    -   *Testing Framework*

        The Testing Framework in TYPO3 provides tools and methods for conducting
        automated tests used for developing the TYPO3 Core or custom projects
        and extensions.

    ..  _tsconfig:
    -   *TSconfig*

        TSconfig uses the TypoScript configuration language in TYPO3 and is used
        for defining backend settings and configuration options. This is
        seperated into "User TSConfig" and "Page TSConfig"

*   U

    ..  _uid:
    -   *uid*

        :sql:`uid` stands for Unique Identifier and is a unique identifier for
        records and objects in the TYPO3 system. It complements the :sql:`pid`
        (parent identifier).

    ..  _upgrade-wizard:
    -   *upgrade wizard*

        The upgrade wizard is a module in the TYPO3 backend used for performing
        system and database upgrades.

*   V

    ..  _vendor:
    -   *Vendor*

        The term "Vendor" is most commonly used as a semantic grouping
        identifier for PHP namespaces in extensions. Composer collects
        all packages in a directory, that is also usually called "vendor" and
        contains subdirectories with the PHP namespace identifiers. A
        vendor can then provide multiple distinct extensions, each separated by
        an extension name identifier. The PHP Composer class-Loading
        functionality depends on these two basic identifiers.

    ..  _viewhelper:
    -   *ViewHelper*

        ViewHelpers are logical helper functions, utilized in Fluid templates
        and partials. ViewHelpers are implemented as PHP code and can perform
        any kind of functionality, however they should only be used for
        managing context of frontend output and should not contain too much
        domain logic.

*   W

    ..  _workspaces:
    -   *Workspace(s)*

        Workspaces are areas in TYPO3 used for managing and editing content in a
        "versioned" way. They allow to prepare content to be published, and
        verified in workflow steps before.

    ..  _web-component:
    -   *Web Component*

        The TYPO3 Cores backend makes considerable use of JavaScript-based,
        standards-compliant web components. These offer dynamic functionality
        using a standards-driven approach, compatible with most browsers and
        offering graceful degradation.

*   X

    ..  _xclass:
    -   *XCLASS*

        XCLASS is a mechanism in TYPO3 that allows developers to extend or
        override existing classes and functions. The TYPO3 Core can then replace
        one instance of a class with another custom class.
