ReadySET: User FAQ {#readyset-user-faq}
------------------

### General Information {#general-information}

What is ReadySET?
:   It is a set of ready-to-use software engineering templates. Please,
    see the [ReadySET homepage](http://readyset.tigris.org/).

Where does the name "ReadySET" come from?
:   "ReadySET" is short for "Ready-to-use Software
    Engineering Templates". It also sounds like the phrase "ready, set,
    go!" which is said at the beginning of a race to give everyone a
    fair start.

Where did the ideas for ReadySET templates come from?
:   The general idea came from a need for me to provide a lot of
    guidance to university students learning software engineering
    without spending time lecturing to them. This fits well with the
    tigris.org mission of promoting open source software engineering,
    and previous efforts, like [ArgoUML](http://argouml.tigris.org/) to
    ease adoption of software engineering tools and practices
    in industry. The content of specific templates came from our
    understanding of software engineering literature, our experience on
    software development projects, and our understanding of cognitive
    challenges of engineering decision-making.

What is the competition for ReadySET?
:   The main alternative to ReadySET is to do it yourself and reinvent
    the wheel or try to generalize from whatever documents you produced
    on your last project. That pattern leads to many individuals in our
    industry trying to develop their own methodology as they move from
    project to project and company to company. ReadySET is an attempt to
    gather that same knowledge from many people and share it
    more effectively. There are also products such as
    [EssentialSET](http://www.merant.com/News/PR/PR_02182003.asp) and
    [RUP](http://www-306.ibm.com/software/awdtools/rup/).

### Download and Install {#download-and-install}

How can I obtain ReadySET?
:   [Download
    it](http://readyset.tigris.org/servlets/ProjectDocumentList).
    Please, see the [ReadySET homepage](http://readyset.tigris.org/).

What licence covers ReadySET?
:   The [ReadySET license](../templates/readyset-license.html) is a
    BSD-style license.

What do I need to use ReadySET?
:   A web browser and a text editor or HTML editor. Please see our list
    of [recommended tools](recommended-tools.html).
:   It is also strongly recommended that you use a web server, a version
    control system, and web-based issue tracking system. You can work
    through setting up these tools yourself, or use a Collaborative
    Development Environment such as [CollabNet's
    SourceCast](http://www.collab.net/).

How do I install ReadySET?
:   Simply unarchive it. Make a copy of the template files to use as
    your project documents.

How do I upgrade from an older version of ReadySET?
:   For any users not using CVS for their own project: simply
    copy-and-paste any desired text from the new templates into your
    project documents.
:   For users that use CVS for their own project: you can use CVS's
    [vendor
    branch](http://cvsbook.red-bean.com/cvsbook.html#Tracking_Third-Party_Sources__Vendor_Branches_)
    feature to help you merge the latest changes from the ReadySET
    project into your project. Follow these [upgrade
    steps](HOWTO-upgrade.html).

### Main Concepts {#main-concepts}

What is a "ReadySET template"?
:   It is an HTML file that with sample text that you should use to
    create project documents.

What is a "project document"?
:   It is an HTML file, copied from a ReadySET template, that contains
    specific information about your project.

What is a "prompt"?
:   In most other document template sets, the templates are basically
    outlines with headings and subheadings. In ReadySET subheadings are
    written in the form of a question or prompt. That helps make the
    documents more self-explanatory and easier for other stakeholders to
    quickly read or write an answer to.

What are the colored bars in the right-hand margin?
:   Those bars indicate sections of sample text. They are explicitly
    marked so that you can see at a glance which parts have been filled
    in and which parts are still the original sample text. Once you edit
    the text, you should remove the HTML attribute class="sample1" to
    remove the bar.

Why are there multiple answers (and colored bars) to each prompt?
:   Rather than give a long explanation of the meaning of each prompt,
    ReadySET includes a few sample answers to most prompts. That works
    best when one of the sample answers includes ideas that relate to
    your specific project. In many cases, much of the process of filling
    in a template is reduced to "chipping away" at the sample text by
    removing text that does not apply to your project.

<a name="chipaway"></a>What is "chipping away"? 
:   The term "chipping away" comes from an old joke: when a sculptor is
    asked how he carved a marble statue of a horse, he replies "It was
    easy, I just started with a big block of marble and chiped away
    everything that did not look like a horse."

What is an "attached worksheet"?
:   The idea is similar to filling in an IRS form and using worksheets
    to calculate subtotals or make specific decisions. That is to say,
    there is a hierarchy to the templates: there are the main templates,
    and then worksheets for specific topics. We have divided the
    information into several files so that each file is focused on one
    topic, and so that each file can be worked on by one person in a
    reasonable amount of time.

What is the "process impact" box about?
:   The process impact box explains where the current template fits into
    the software development process. It usually includes a brief
    comment on who should create the document, and who would be expected
    to make use of it. You can change the process impact box, but you
    should not need to.

What is a "checklist"?
:   There are two kinds of checklists:
    -   Many of the templates have a section with questions that help
        you check your work in that template. Often the sample answers
        to the questions prompt you to take some corrective action.
    -   For design and code review meetings, there are links to
        guidelines and checklists that help you identify common errors
        in those artifacts.

What is a "sticky note"?
:   The idea is similar to a post-it note attached to a document that
    tells you do "sign here" or fill in a certain part. There are two
    types of sticky notes:
    -   TODO: Instructs you on how to fill in the template. This is the
        minimum that you need to do. One of the main goals of ReadySET
        is to help your team *quickly* carry out basic software
        engineering activities. The TODO sticky notes make that easy by
        making the templates more self-explanatory.
    -   TIP: Helps you think of better ways to fill in the template. One
        of the other main goals of ReadySET is to help your team make
        better decisions that can make your whole project more
        successful. The TIP sticky notes help with that.

    After you have done what the sticky note says, you can delete the
    sticky note. In the HTML file, they are marked with class="sticky".

Why do some links have dashed underlines?
:   Those are links to the definitions of terms. They are visually
    different so that readers whill know that they can quickly read the
    definition of that term without being side-tracked. Also, the dashed
    underlines do not appear when the document is printed.

### Configuring and Customizing ReadySET {#configuring-and-customizing-readyset}

One of the ReadySET templates is not needed for my project. How do I remove it?
:   Just delete it, and remove any links to it.

How do I add a new file to the set?
:   Just open a new file in your HTML editor. Save the file, and add
    links to it from other templates as you see fit. You may want to
    copy an existing template and tear out all its content and put your
    content there instead, that way the new template will have the
    proper HTML HEAD elements, but these are simple anyway.

How can I use ReadySET for projects using technologie like .NET or J2EE?
:   ReadySET does not have any complex customization tools. There are no
    "plug-ins" or meta-models. Those layers of abstraction make it
    harder to get started. ReadySET is just a set of XHTML templates.
    You can edit them any way you like, it is up to you and there is
    nothing preventing you from doing it.
    [ReadySET Pro](http://www.readysetpro.com/) takes a more powerful
    approach that does have a bit of a learning curve, but scales well
    to corporate usage.

How can I add "Company Proprietary" to every page?
:   That text is already there in a paragraph with CSS class="legal1".
    Normally that CSS style is invisible. You can make it visible by
    editing css/inst.css to uncomment the line "display:
    block !important". If you need to change the text, you can use a
    global search and replace in your text editor.

Who uses ReadySET?
:   Stay tuned to the ReadySET mailing list for user testimonials.

### Contributing to the Project {#contributing-to-the-project}

Who can contribute to this project?
:   Everyone is welcome, especially project managers or team leads who
    have first-hand experience on many projects where templates like
    these would have helped.

How can someone start to contribute?
:   Make sure that you are familiar with the templates, then send your
    comments to the project mailing list and we will go from there. Only
    a core group of developers will have commit access, but others can
    make contributions via the mailing list and we will review them and
    integrate changes.
:   Please do not send in any proprietary or copyrighted content. We
    will have to immediately delete it. E.g., if you have a document
    template that you use at your current company, please do not send
    it. Instead, you can give us a few bullet points or examples on
    specific things that you think help make that type of document more
    useful based on your general experience. Of course, you should never
    send in any actual document that contains any actual information
    about your business, product plans, schedules, budgets, personnel,
    or customers.

Who is contributing to ReadySET?
:   Stay tuned to the ReadySET mailing list for information.

### Other Questions {#other-questions}

My question is not on this page. How do I find the answer?
:   Your question may have already been asked and answered, to find it:
    search the project [mail
    archives](http://readyset.tigris.org/servlets/SummarizeList?listName=dev)
    and [issue tracking
    system](http://readyset.tigris.org/servlets/ProjectIssues). If you
    still don't find it, you can ask the question on the the ReadySET
    developers' mailing list or you can enter an issue. You must
    subscribe to the mailing list before you may post. For commercial
    support and training, see
    [ReadySET Pro](http://www.readysetpro.com/).


