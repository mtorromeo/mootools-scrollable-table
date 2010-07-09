ScrollableTable
===============

A class that makes table rows scrollable while keeping thead and tfoot fixed.

![Screenshot](http://mtorromeo.github.com/mootools-scrollable-table/screenshot.png)

How to use
----------

ScrollableTable works by taking the source table and splitting it in 3 separate tables containing the thead, tbody and tfoot.

The widths of the table columns are kept in sync by the update() method that must be called manually every time the table content/layout changes.

A wrapper element with overflow:auto is created around the central table (tbody) and must be given a height/max-height style to be scrollable. The wrapper class can be specifiend in the class options.

The classes that were assigned to the original table will be automatically assigned to the auto-generated tables for the header and footer.

	#JS
	var table = new ScrollableTable('mytable', {
		wrapperClass: 'tableBody'
	});

Working demo here: [jsFiddle](http://jsfiddle.net/gnTZ4/6/)