ScrollableTable
===============

A class that makes table rows scrollable while keeping thead and tfoot fixed.

![Screenshot](http://mtorromeo.github.com/mootools-scrollable-table/screenshot.png)

How to use
----------

ScrollableTable works by taking the source table and splitting it in 3 separate tables containing the thead, tbody and tfoot.

A div container will be created around the original (tbody) table and will be given a overflow:auto style to make it scrollable.

Tha column widths will be kept in sync by the ScrollableTable.update() method that must be called if the table is modified.

	var table = new ScrollableTable('mytable', {
		wrapperClass: 'tableBody'
	});
