### Changelog 


- 1.1.1 (22/02/2026)
  - [FIX] additional PHP 8 hardening: guard against "array offset on bool" in build_tree_rec/build_output
  - [FIX] initialized $forum_list and $tree variables to prevent undefined variable warnings
  - [FIX] added isset() guards in get_crumb_parents() for missing forum/parent keys
  - [FIX] replaced deprecated sizeof() with count()

- 1.1.0 (17/04/2021)
  - [FIX] #3 enable dropdown for all breadcrumb menus
  - [FIX] php 8.0 compatible

- 1.0.7 (22/01/2017)
  - [FIX] merged with changes from CDB version by david63
  - [FIX] updated jqueryui reference

- 1.0.6 (11/06/2017)
  - [FIX] CDB version by david63
  - [CHG] From version 1.0.6 an event "paybas_breadcumbmenu_append" has been added that will allow other extensions to use this extension and as a consequence the hardcoded extensions for boardrules, pages that were in previous versions were removed.
  
