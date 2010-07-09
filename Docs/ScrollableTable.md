Class: ScrollableTable {#ScrollablTable}
========================================

## Implements:

Options

ScrollableTable Method: constructor {#ScrollableTable:constructor}
------------------------------------------------------------------

### Syntax:

	var table = new ScrollableTable(element, options);

### Arguments:

1. element - (*element*) Table element
2. options - (*object*, optional) Initial options for the class.

### Options:

* wrapperClass - (*string*, defaults to 'scrollable-container') The class assigned to the wrapper element around the table.
* scrollbarWidth - (*integer*, defaults to 15) The width of the scrollbar that the class should consider.

### Returns:
* (*object*) A new *ScrollableTable* instance.

ScrollableTable Method: update {#ScrollableTable:update}
--------------------------------------------------------

Updates the column widths. Must be called every time the layout/table content changes.

### Syntax:

	table.update();

### Returns:
* (*object*) Returns the *ScrollableTable* instance.