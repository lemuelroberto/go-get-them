# sitemap parser

> Website sitemap parser

# What we want

We want to get all URLs from a sitemap file. A sitemap file may have links to
other sitemap files and we should follow these links and get their URLs as well.

# The expected interface

We want to run the program in a command-line interface (CLI) passing a sitemap
URL as an argument and get the URL list in the standard output. Errors should be
given in the standard error output.

As an example, we should be able to run `./site-map-parser https://example.com/sitemap.xml`.

# What you can use to develop the program

## Programming language

Choose the programming language that better suits you, your knowledge and the
problem domain.

## Libraries

You must build your own sitemap parser. You can use input/output libraries,
HTTP clients, XML parsers, error handlers, or any other library that do not parse
a sitemap file.

# How to deliver

Fork this git repository, commit your work and submit a Pull Request with the
solution.

The deliverable should contain the dependencies and instructions to build the
program.
