Colormap (PHP)
========================================

Author: Kenn Wilson

Author URL: [http://www.corvidworks.com/](http://www.corvidworks.com/)

Project URL: [http://www.corvidworks.com/projects/colormap/](http://www.corvidworks.com/projects/colormap/)


Description
-------------------

Colormap provides helper methods to convert colors between different formats used on the web. Supported formats are:

 * Six-character hexadecimal (eg, `#000000`)
 * Three-character hexadecimal (eg, `#000`)
 * RGB (eg, `rgb(0,0,0)`)
 * HTML named color, including non-W3C colors (eg, `black`)

Three character hex codes are normalized to six characters and all input is normalized to lowercase. Colors can be converted from any one of these formats to any other.

This library was extracted from [Hextractor](http://www.hextractor.com/).


Usage
-------------------

Include class and instantiate a ColorMap object:

	include_once "colormap.php";
	$map = new ColorMap();

Call various methods, as needed:

	$hex  = $map->rgb_to_hex('119 125 66');        // Returns '#777d42'
	$rgb  = $map->hex_to_rgb('#777d42', 'string'); // Returns '119 125 66'
	$name = $map->hex_to_name('#ffffff');          // Returns 'white'


Documentation
-------------------

Additional information can be found at:

[http://www.corvidworks.com/projects/colormap/](http://www.corvidworks.com/projects/colormap/)


License
-------------------

This code is released under the terms of the [MIT License](http://www.opensource.org/licenses/mit-license.php) and is free to use and redistribute for any purpose. If you find this code helpful, a link back to [my site](http://www.corvidworks.com/) would be cool, but it’s not required.





