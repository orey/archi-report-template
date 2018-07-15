# Simple template for Archi report

## Features

This repo is containing a simple template for [Archi](https://archimatetool.com).

It is slightly different from the standard template delivered with the product, but it contains some nice features that makes it distributable to end users :

  * You can add a logo with your organization.
  * You can specify your organization name in the footer.
  * It generates a PDF index with links to all the diagrams.
  * It proposes, after each diagram, a table with all the artifacts that contains the artifact description.
  * It does not include a documentation on relationships. In the standard template, this documentation can be quite heavy and hard to use.

## Customizing the report template

### Logo

Add your logo by referencing the absolute path to the image in the `main.jrxml` file (search for `TODO 1` in the file).

### Footer

Search for `TODO 2` in the `main.jrxml` file and indicate your company name.

## Tip for your reports

As the views are sorted alphabetically in reports, you can sort views with letters then numbers (such as `a01 Some view`, `a02 Some other view`, `b01 A view about something else`, etc.) to master the way the views are ordered in your model.


## Donation

[Archi](https://archimatetool.com) is a great tool that is Archimate 3 compliant. Consider making a donation.
