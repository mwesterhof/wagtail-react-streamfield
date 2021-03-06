What’s new in wagtail-react-streamfield?
========================================

0.8.5
-----

- Added ``min_num`` and ``max_num`` support for ``ListBlock``
- Fixes duplication of remaining unsupported blocks: ``ChooserBlock`` & ``DateBlock``
- Fixes rendering of errors on non-chooser blocks
- Fixes a Python error when migrations use combinations of ``ListBlock`` with ``StructBlock``
- Removes the confirm dialog shown when leaving the page without changes

0.8.4
-----

- Fixes loading of Draftail RichTextBlock in some *scenarii*

0.8.3
-----

- Fixes loading and duplication of TableBlock, Hallo.js RichTextBlocks
- Fixes Draftail RichTextBlock duplication
- Avoids showing a confirm when exiting an unmodified page
- Fixes handling of custom empty block values
- Fixes handling of extra undefined data

0.8.2
-----

- Adds ``max_num`` support
- Adds a transition when using move arrows
- Adds a transition on the panel listing the block types to add
- Fixes StructBlock as a StructBlock field

0.8.1
-----

- Automatically opens blocks with errors while adding a red highlight
- Fixes the load of JavaScript widgets such as RichTextField & ChooserPanels

0.8.0
-----

First working version with all essential features
