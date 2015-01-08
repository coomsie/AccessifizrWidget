AccessifizrWidget 1.0
==

Accessifizr is a Dojo plugin intended to quickly make web applications tab navigable and compliant with AODA/Section 508 accessibility standards without having to massively modify core application code and UI.  Originally developed for use with ESRI Javascript Templates, additional functionality is planned to be rolled into the application with future releases.

The Accessifizr Widget is designed to easily port this functionality into the Web AppBuilder for ArcGIS.  It follows all configuration and internationalization support outlined in the Accessifizr.js project, and configuration is completely handled via the handlebars.json file.

For more information regarding how to customize handlebars.json, please consult the documentation accompanying the core Accessifizr library at https://github.com/cmndrbensisko/Accessifizr.js

Please note that this is not an in-panel widget.  To add it to your ArcGIS Web AppBuilder, add the widget to your \client\stemapp\widgets directory, and add a reference to the widget in the standard default2Dapp configuration located at \client\builder\predefined-apps\default2DApp\config.json, under the widgetOnScreen section.

Example:

	"widgetOnScreen": {
		"widgets": [{
			{
				"uri": "widgets/AccessifizrWidget/Widget"
      		},
      	...
      	]}
	}