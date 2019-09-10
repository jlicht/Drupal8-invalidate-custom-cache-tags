kb_invalidate_custom_cache_tags
===============================

This is a module companion for the blog post:

http://karimboudjema.com/en/drupal/20190909/node-list-cache-tag-pitfall-drupal-8-views

This module will invalidated custom cache tags created by the 
contrib module Views Custom Cache Tags:
https://www.drupal.org/project/views_custom_cache_tag

There is also a hook_views_pre_view() that inserts the real time
in the header of two views: Block Pages and Block Article to help
you to easier check if the cache has been invalidated.


Install
-------
- Download or clone the module in your /modules/custom directory.
- Install it with Drupal Console: drupal moi kb_invalidate_custom_cache_tags 