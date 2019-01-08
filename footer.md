#### Footer Text
```html
<p>XXXX is published by  <a href="http://publishing.gmu.edu" target="_blank" rel="noopener">Mason Publishing</a>, a division of the <a href="http://libraries.gmu.edu" target="_blank" rel="noopener">George Mason University Libraries</a>. For more information or to discuss open access publishing options, please <a href="mailto:publish@gmu.edu">contact us</a>.</p>
```
### Modifications to LESS
```css
/**
 * @file plugins/themes/default/styles/footer.less
 *
 * Copyright (c) 2014-2018 Simon Fraser University
 * Copyright (c) 2003-2018 John Willinsky
 * Distributed under the GNU GPL v2. For full terms see the file docs/COPYING.
 *
 * @brief Classes for the page footer elements
 */

.pkp_structure_footer_wrapper {
	background: @bg-shade;
}

.pkp_structure_footer {
	text-align: center;
}

.pkp_footer_content {
		         	// !MPG changed next line to double
               //  padding: @triple;;
    padding: @double;
    text-align: left;
}

// OJS brand images in footer
.pkp_brand_footer {
	.pkp_helpers_clear();
	              // !MPG changed next line to double
               //  padding: @triple;;
	padding: @double;;

	a {
		float: right;
		display: block;
                 // !MPG changed next line to 50 from 150
		max-width: 50px;
	}
}
```
