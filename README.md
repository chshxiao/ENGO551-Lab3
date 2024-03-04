# ENGO551-Lab3

CREATOR: Chunsheng Xiao

This is a web mapping application about building permits in Calgary. Users are able to filter to certain date range and visualize building permits in Calgary in a mapping front-end. Four components are used in this applications: leaflet, a leaflet plugin called marker cluster group, open Calgary API, and a free plugin called date range picker.

The default page is a Calgary base map. On the left corner is the zoom-in zoom-out button. On the right top corner, you can see the date range picker and the refresh button. Refresh button always bring you back to the default view.

The date range picker allows you to select a date range either by choosing the date or typing it in the bar. Once you click apply, the start date and end date will be post to Open Calgary and we will obtain the data. The default start date is the earliest permit issued date derived from the AP.I

The marker cluster group plugin groups all the building permit closed to each other. You can see the area covered by the cluster group if you hover over it. Once you click, it will zoom in and show you more information about building permits.

A popup box is enabled if you click on the marker. The permit number, issued date, workclass group, contractor name, community name and original address are included. The permits located at the same location is distinguished by the marker spider leg.

You can find the documentations of four plug-ins below:

Leaflet
https://leafletjs.com/index.html

Marker cluster group
https://github.com/Leaflet/Leaflet.markercluster

Open Calgary API
https://www.opendatanetwork.com/dataset/data.calgary.ca/c2es-76ed

Date range picker
https://www.daterangepicker.com/