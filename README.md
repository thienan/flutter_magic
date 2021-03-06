# New article in Medium

https://medium.com/@rotoxl/api-explorer-a6b8c9aa97bb

# Now in beta@Google Play 

![https://play.google.com/store/apps/details?id=apiexplorer.com.app](screenshots/shop-android.png) 

![](screenshots/diapo-all.png)


# Magic API &amp; Flutter

* data is fetched from an API endpoint
* data is shown in listing+detail
* 4 flavours for listing (list, gridWithName, gridWithoutName, match)
* 4 flavours for detail (hero, data, compare, match)

![Structure](screenshots/composition.png)

# Next steps
* sprint 1
	* onboarding screen

* sprint 2 
	* list page -> set query parameter
	* cupertino style?
	* detail window -> related items widget
	* change API endpoint window
		* "add new endpoint" logic & form
	* detailconfig window
		* new chips, stats widgets, new fields are still not configurable

# Recently added
* analytics
	* basic scaffolding
	* add more and more
* startup
	* choose last used EndPoint
	* remote config with firebase
* "about this API" dialog
* app icon & splash
* list page
	* empty states
	* list page -> search (in results)
	* toggle view list/grid
	* more styles: gridWithText, gridWithoutText
* config/change API screen
	* firebase remote config support
	* sorted by endpoint (so that same-domain endpoints are grouped together)
	* "change endpoint" to choose from a list of bundled & user API endpoints (recently used first)
	* show color
	* added google books API
	* added (static) Planets API in 3 flavours
	* added (static) Places API
* detail window
	* more templates: heroStyle + compareStyle + match
	* poster photos are wiser now, if the image is a png it doesn't show a border
	* open main image
	* images widget
	* rebuild to be closer to [this](https://d33wubrfki0l68.cloudfront.net/4ac7d7e147f5505b66e74ce6698193a58f796776/67682/images/from-wireframes-to-flutter-movie-details-page/movie_details_ui_result.png)



