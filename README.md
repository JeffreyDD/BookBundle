BookBundle
==========

The BookBundle allows you to easily create books, with subpages, and subpages, and subpages.

2 Entities:

## Book
A book has a title and many pages.

## Page
A page has a title, slug, content, can have a parent and / or can have subpages.
The content is stored as markdown.
The slug is auto-generated based on the title.
