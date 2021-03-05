
# Changelog

---

## 0.1.3

### Bugfixes

- Fixed the "Name" field disappearing upon full deletion of text
- Fixed a bug with single/multi-select fields working unintuitively for adding new values (eg: Character personality traits field or Sex field)
- Added an auto-remover of no longer existing relationships filled in within single and multi relationship fields
- Fixed a typo with "Sciences/Technologies" missing the plural form
- Adjusted the naming of "Other/Notes" to "Lore notes/Other notes" to be functional with the new search engine (apologies for this one, a new solution might be implemented later)

### New features

- Added a safeguard dialog for new project creation in case an opened project exists
- Added a safeguard dialog for project importing in case an opened project exists
- Added automatic redirecting to the project screen upon importing an existing project or creating a new one (better transition effect will be added later)
- Added an "Advanced search guide" dialog with a manual on how to use the advanced search
- Added a "Changelog" dialog - you might be reading it right now!
- Added "About Fantasia Archive" dialog showing current app version (more details will be added in the future)
- New control bar added for documents and project control along with a more intelligent button redesign
- A new logo added to the app (better visibility of the logo in small scales and icons)
- Massive overhaul of the search engine used by the Quick opening existing document and single/multi relationship fields (now supports tags, categories, document types, intelligent filtering, and intelligent sorting via the importance of the found values)
- Added color support to single/multi relationship fields
- Added a hierarchical path to Quick opening existing document and single/multi relationship fields
- Added filtering to include or exclude documents that are considered categories in the  Quick opening existing document dialog
- Added automatic opening of hierarchical tree branches upon adding/moving documents under/among them
- Added tags support

### QoL adjustments

- Lightly modified the app color-scheme to offer better readability of contrast
- Changed icon for the button triggering quick-adding of new documents
- Changed the looks of tooltips, relationship fields, and selects to go well with the current app looks
- Adjusted tab-list width to allow for more content to show
- Improved scroll behavior in the keybind cheatsheet dialog (looks a little strange now, but will work better as more keybinds are added)
- Added a tooltip showing how many of the objects in the hierarchical tree are documents and how many are categories
- Hierarchical tree search bar is now attached on the top of the tree and no longer scrolls along with the rest of the content of the tree to allow better useability. The search now also expands to full app width on focus via user's interaction. The search icon was moved to the right and the field reset icon was moved to the left.
- Modified selected and activity indicators for already selected/active items in dropdown lists to not clash with the highlighting from the filter results
- Slightly modified the scrollbar visuals to be less intrusive
- Added a light golden tint to the background of the app to go easy on the user's eyes before the dark mode is added
- Improved performance by reducing the amount of time the side-tree re-renders
- Visually aligned custom order badge for both nodes with and without children
- Added dark visuals to the single-select and multi-select fields to align with the rest of the app
- All popup dialogs have been unified to a dark-color mode
- Prettified a dialog popup for confirmation of closing a document with active edits
- Added a small filter over the big white areas to ease-up on the user's eyes before the dark mode is added

---

## 0.1.2

### Bugfixes

- Fixed a safeguard for opening multiple overlapping dialogs unintentionally

### New features

- Reworked hierarchical left tree
- Added "Add under parent" button to the hierarchical tree, document page view, and quick search existing documents
- Added mouse button support and improved keyboard support to the hierarchical tree
- Reworked the top bar of the app to include tabs, window control elements, and basic menus of the app
- Added a check upon closing the app to avoid unintentional loss of data due to unsaved documents

### QoL adjustments

- Added middle-click closing for the tabs
- Added automatical opening of the project page after opening an existing project from a folder
- Reversed default custom sorting for the "Order" field in the left side tree
- Modified auto-closing behavior of hierarchical left tree nodes when moving/adding/removing documents
- Added a delay for tooltip popups on fields of documents
- Remove persistence from the document with an active edits confirmation dialog
- Unified graphical interface coloring of Quick-add and Quick-search dialogs to work consistently with the coloring of individual documents/document types same as the left hierarchical tree

---

## 0.1.1

### Bugfixes

- Fixed a bunch of typos
- Fixed names not changing with single/multi relationships if one gets name updated showing on the others properly
- Fixed forced lower-case for notes in lists and relationship fields
- Fixed a bug that prevented documents with the same names properly working in the hierarchical tree

### New features

- Added keyboard shortcut support
- Added quick-add new document pop-up
- Added quick-search existing document pop-up
- Added keybinds cheatsheet pop-up
- Added control buttons for keybinds cheatsheet, quick search, and quick add
- Added document coloring support for the document hierarchical tree and tabs on the top
- Added category/document switch for handling custom subcategories
- Added tooltip support for all input fields
- Added "Color picker" type field
- Added "Switch" type field

### QoL adjustments

- Alphabetically sorted most predefined lists (eg: types of political groups) with "Other/Unique" fields at the bottom. The fields that are ordered logically (eg: severity of racial weakness/strength) remain ordered via logical sorting and not by alphabet
- Added explanation via tooltip to "Belongs under", "Order" and "Color" fields
- Adjusted tooltip font-size to be actually readable
- Added program FAVICON support
- Moved the document edit/save/delete buttons to the top
- Adjusted text selection to look better with the aesthetics of the app
- Adjusted scrollbars to look better with the aesthetics of the app
- Added auto-focus on name field when opening edit mode of a document
- Added auto-focus AND auto-select of all text of the name field when creating a new document
- Renamed "Lore notes" to "Other/Notes" for more intuitive usage
- Renamed "Other names" to "Other names & Epithets" across all document types
- Renamed "Power level" to "Combat rating" in "Characters" document type
- Renamed "Level of sentience" to "Level of sapience" in "Species/Races" document type
- Added "Oldest known" and "Average adulthood" fields to the "Species/Races" document type
- Added "Continent" and "Landmass" to prefilled options to the "Location type" field in the "Locations" document type
- Added "Ethnicity" field in "Characters" document type
- Added "Titles" field in "Characters" document type

---

## 0.1.0

### Innitial release