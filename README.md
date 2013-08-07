# ProcessWire PageReferencesTab #

A little addon to display pages referencing the page being currently edited.

* Lists references via Page fields in a new tab (References). Title, path and referencing field are displayed, as well as view & edit links (when applicable).
* Only fields of type FieldtypePage are considered to be references, but they're checked also inside repeaters.
* Enabled templates can be chosen via module settings. If no template is chosen, the tab is shown regardless of the template.
* System templates and fields are always skipped: Tab wont be added when editing a page with a system template and references from system fields (roles, permissions) are not shown.

[See screenshot](http://processwire.com/talk/index.php?app=core&module=attach&section=attach&attach_rel_module=post&attach_id=1047)

------
PageReferencesTab Copyright (c) 2013 Niklas Lakanen