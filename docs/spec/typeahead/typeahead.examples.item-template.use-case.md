16.2: Typeahead Item template example
=====================================
**Primary Actor**: User

**Scope**: Ngx-bootstrap DEMO / BS version 3&4

**Goal**: Show user Item template functionality

Main success scenario:
----------------------
1. User opens Typeahead demo page
2. User click on Item template sub-menu
3. User sees typeahead input and typeahead card with "Model:" text
4. When user starts to type a name of a State from "states" array and there is no matches the drop-down is hidden. The "Model" is filled with inputted data
5. When there are any matches then a drop-down with a list of States matches is shown. The list contains a template "This is: "_matched state_" index: _index #"_
6. Items in the drop-down are clickable
7. When user clicks on any item in typeahead drop-down, then typeahead container auto-fills with a selected State

Extensions:
-----------
4a. Typing a part of the template "This is:" or "Index" does not call the drop-down

Variations:
-----------
2*. User scrolls to Item template sub-menu
