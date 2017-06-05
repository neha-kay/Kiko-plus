---
layout: post
title: "Footsteps"
description: "A hobo unleashed..."
date: 2017-06-02
tags: [about neha]
comments: true
share: true
---

### Footsteps as of June 2017.

![footsteps](/images/footsteps.jpg)
*[Salinas Grandes, Argentina], one of the biggest salt flats in the world* (https://www.google.com/maps/place/Salinas+Grandes/@-23.621901,-65.8941867,-366m/data=!3m1!1e3!4m5!3m4!1s0x940355b07e40a169:0xe42ee3f2b7e54a39!8m2!3d-23.621901!4d-65.891998)

__Africa |__
Ghana

__Asia |__
Hong Kong
India
Japan
Malaysia
Myanmar
South Korea
Thailand

__Europe |__
Belgium
Czech Republic
France
Germany
Italy 
Netherlands
Spain
Switzerland
United Kingdom

__North America |__
Canada
United States

__South America |__
Argentina
Brazil
Chile
Colombia
Ecuador
Peru

__Oceania |__
Coming soon ;) 

__Antartica |__
Coming soon ;)

<script src="https://www.amcharts.com/lib/3/ammap.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/maps/js/worldHigh.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/themes/dark.js" type="text/javascript"></script>
<div id="mapdiv" style="width: 900px; height: 405px;"></div>
<script type="text/javascript">
var map = AmCharts.makeChart("mapdiv",{
type: "map",
theme: "dark",
projection: "mercator",
panEventsEnabled : true,
backgroundColor : "#535364",
backgroundAlpha : 1,
zoomControl: {
zoomControlEnabled : true
},
dataProvider : {
map : "worldHigh",
getAreasFromMap : true,
areas :
[
	{
		"id": "CA",
		"showAsSelected": true
	},
	{
		"id": "US",
		"showAsSelected": true
	},
	{
		"id": "AR",
		"showAsSelected": true
	},
	{
		"id": "BR",
		"showAsSelected": true
	},
	{
		"id": "CL",
		"showAsSelected": true
	},
	{
		"id": "CO",
		"showAsSelected": true
	},
	{
		"id": "EC",
		"showAsSelected": true
	},
	{
		"id": "PE",
		"showAsSelected": true
	},
	{
		"id": "GH",
		"showAsSelected": true
	},
	{
		"id": "HK",
		"showAsSelected": true
	},
	{
		"id": "IN",
		"showAsSelected": true
	},
	{
		"id": "JP",
		"showAsSelected": true
	},
	{
		"id": "MY",
		"showAsSelected": true
	},
	{
		"id": "MM",
		"showAsSelected": true
	},
	{
		"id": "KR",
		"showAsSelected": true
	},
	{
		"id": "TH",
		"showAsSelected": true
	}
]
},
areasSettings : {
autoZoom : true,
color : "#B4B4B7",
colorSolid : "#84ADE9",
selectedColor : "#84ADE9",
outlineColor : "#666666",
rollOverColor : "#9EC2F7",
rollOverOutlineColor : "#000000"
}
});
</script>
