=============
ckanext-featuredviews
=============

Display select resource views on dataset and home pages.

By default, CKAN only shows Resource Views on the resource page, but has no
mechanism for showing users which resources have visualizations, and where the
good ones are.

This extension lets you mark Resource Views as featured so they show up right
on your dataset pages or even on the CKAN front page.

Usage
=============
Add to the list of plugins: ::

    ckan.plugins = ... featuredviews


Run the migrations: ::

    paster --plugin=ckanext-featuredviews featured migrate
