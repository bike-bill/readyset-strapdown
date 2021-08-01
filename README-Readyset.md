## ReadySET: Overview
---

### Mission
- [Browse templates](https://github.com/bike-bill/readyset-markdown)
- [Download markdown templates](https://github.com/bike-bill/readyset-markdown)
  or [Download original templates](http://readyset.tigris.org/servlets/ProjectDocumentList)
- [Words-of-wisdom](http://readyset.tigris.org/words-of-wisdom/)
- [Professional version](http://www.readysetpro.com/)

#### What problem does this project address?

Software development projects require a lot of "paperwork" in the
form of requirements documents, design documents, test plans,
schedules, checklists, release notes, etc. It seems that everyone
creates the documents from a blank page, from the documents used on
their last project, or from one of a handful of high-priced
proprietary software engineering template libraries. For those of us
who start from a blank page, it can be a lot of work and it is easy
to forget important parts. That is not a very reliable basis for
professional engineering projects.

#### What is the goal of this project?

ReadySET is an open source project to produce and maintain a library
of reusable software engineering document templates. These templates
provide a ready starting point for the documents used in software
development projects. Using good templates can help developers work
more quickly, but they also help to prompt discussion and
avoid oversights.

#### What are some key features that define the product?

High-quality outlines, sample text, and checklists.

- Uses simple web technologies: Pure XHTML and CSS (or alternatively Markdown).
- Templates for *many* common software engineering documents. Including:
  - Project proposal template
  - Project plan template
  - Use case template
  - QA plan template
  - Several design templates
  - System test case template
  - Release checklist template

#### What makes this product different from others?

This is an open source project that you are welcome to use for free
and help make better. Existing packages of software engineering
templates are highly costly and biased by the authorship of only a
few people, by vendor-client relationships, or by the set of tools
offered by a particular vendor.

These templates are in pure XHTML with CSS (or Markdown), not a proprietary
file format. That makes them easier to edit and to track changes
using freely available tools and version control systems. The
templates are designed to always be used on the web; they use
hyperlinks to avoid duplicating information.

The templates are not burdened with information about individual
authorship or document change history. It is assumed that
professional software developers will keep all project documents in
version control systems that provide those capabilities.

These templates are not one-size-fits-all and they do not attempt to
provide prescriptive guidance on the overall development process. We
are developing a broad library of template modules for many purposes
and processes. The templates may be filled out in a suggested
sequence or in any sequence that fits your existing process. They
may be easily customized with any text or HTML editor.

### Scope

#### What is the scope of this project?

We will build templates for common software engineering documents
inspired by our own exprience.

#### What are the high-level assumptions or ground rules for the project?

I assume that the user takes ultimate responsibility for the content
of all their actual project documents. The templates are merely
starting points and low-level guidance.

#### What are we not going to do?

This project does not attempt to provide powerful tools for
reorganizing the templates, mapping them to a given software
development process, or generating templates from a underlying
process model. This project does not include any application code
for any tools, users simply use text editors to fill in or customize
the templates.

#### Is this project part of a larger effort?

Yes. It is part of the Tigris.org mission of promoting open source
software engineering. It is also the first product in a product line
that will provide even better support to professional
software developers. For more information, see
[ReadySET Pro](http://www.readysetpro.com).

### Status

#### What is the status of this project?

- These templates are based on templates originally used to teach
  software engineering in a university project course. They are now
  being enhanced, expanded, and used more widely by professionals
  in industry.
- The template set is fairly complete and ready for use in real projects. 
  You can [download](http://readyset.tigris.org/servlets/ProjectDocumentList) 
  recent releases. We welcome your feedback.
- For the latest news, see the 
  [Project Announcements](http://readyset.tigris.org/servlets/ProjectNewsList).

### Applicability

#### Who should use this product?

ReadySET is aimed at software engineers who wish that their projects
could go more smoothly and professionally. ReadySET can be used by
anyone who is able to use an HTML editor or edit HTML in a
text editor.

#### How can users get started?

1. Briefly [browse all templates](https://github.com/bike-bill/readyset-markdown)
2. [Download markdown templates](https://github.com/bike-bill/readyset-markdown)
   or [Download original templates](http://readyset.tigris.org/servlets/ProjectDocumentList) 
   the templates and unarchive
3. Edit the templates to fit the needs of your project
4. Place the templates on a web server where all your project
   stakeholders can view them
5. Edit the templates to fill in detailed information
   - Use a text editor or an HTML editor. Please see our list of
     [recommended tools](docs/recommended-tools). (You can
     use Word, but that is strongly discouraged.)
   - Follow instructions that appead in yellow "sticky notes", TODO, or TIPS sections
   - Replace text in ALL CAPS and lines that start with :: (double colons) 
     with text that describes your project
   - [Chip away](docs/faq.html#chipaway)" text that does not
     apply to your project
   - Add text, diagrams, or links as needed
6.  Use the checklists to catch common errors and improve the
    quality of your documents.
7.  Use the words-of-wisdom pages to help improve the document or
    deepen your understanding of relevant issues.
8.  Optionally, you may change fonts and colors in the
    file css/inst.css.
9.  If you have questions or insights about a templates, please read
    the [FAQ](docs/faq.html) or send an email to
    <dev@readyset.tigris.org>. You must subscribe to the mailing
    list before you may post.

