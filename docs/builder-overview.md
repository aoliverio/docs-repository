# RAD Overview

Rapid Application Development (RAD) is both a general term used to refer to alternatives to the 
conventional waterfall model of software development as well as the name for James Martin's approach to rapid development.
In contrast to the waterfall model, which emphasizes rigorous specification and planning, 
RAD approaches emphasize the necessity of adjusting requirements in reaction to knowledge gained as the project progresses.
In addition to James Martin's RAD method, other approaches to rapid development include Agile methods and the spiral model. 
RAD is especially well suited (although not limited to) developing software that is driven by user interface requirements. 
Graphical user interface builders are often called rapid application development tools.

**Builder** from aoliverio/builder, is my solution, developed as a plugin in CakePHP 3.x framework, for the use of the best 
techniques and technologies, to development of web-oriented applications.

## Builder

**Builder** is a CakePHP 3.x plugin used to generate code in Bootstrap 3 style. 

Some of the highlights:

- Defined a new Bake template for generate CRUD using Bootstrap 3 framework.
- Added filter action to controller and generate base filter template.
- Open add, edit, delete and filter templates in the Bootstrap 3 modal view.
- Used grid and detail template to extend the index and view actions functionality.
- Used element to import in CakePHP 3 app default code and behavior.
- Used DataTables JQuery plugin for table in the index template.
- Integrated simple Role-Based Access Controll.

See the docs on [how to use Builder](http://aoliverio.readthedocs.org/projects/builder/en/latest/).

## Builder Extensions

Multisite and multi languages CMS solution:

- **Content** plugin, a content management system backend.
- **Site** plugin, a content management system frontend.

See the docs on [how to use Builder CMS](http://aoliverio.readthedocs.org/projects/content/en/latest/).