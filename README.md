CARTO | Leidos Training Course
============================

You can also find the complete [training course below](#complete).

* Course Main Landing Page: [http://cartodb.github.io/training/introductory/leidos-training.html](http://cartodb.github.io/training/introductory/leidos-training.html)

* Course Materials: [https://github.com/CartoDB/carto-workshop/tree/170418-1225-leidos](https://github.com/CartoDB/carto-workshop/tree/170418-1225-leidos)

### Requirements 
* Laptop computer with Chrome installed as the browser connected to the internet.
* A CARTO account. For those without an account you can [create a FREE account here](https://carto.com/signup/) and follow along. 

### Training Schedule
Tenative schedule of tasks/talks, subject to change/update.


* **1:00 pm** - 
[Introduction to CARTO](00-intro-carto/)

* **1:10 pm** - Shaking Hands with CARTO, a quick tour of the platform, 
	* Maps/Datasets view, 
	* Inside a CARTO Map 
		* Layers
			* Data
			* Analysis
			* Style
			* Pop-Up
			* Legend
		* Widgets
			* Category
			* Histogram
			* Formula
			* Time-Series
* **1:20 pm** - [CARTO Builder Analysis Tools](https://docs.google.com/document/d/1Eki8nndjQvaGldPWwSoAh561JgUoCqI1bB_93TNHW_k/edit?usp=sharing)
* **1:30 pm** - [Carto Docs](https://carto.com/docs)
* **1:35 pm** - [Exercise: San Francisco tree map](01-builder-visualization/exercises/sf-trees.md)

* **1:50 pm** - [Dive into API's](https://docs.google.com/presentation/d/1-gfFWpen7hXKy3Jk-AuaQUdbJyTxCOjVz6SgOHClFkk/edit#slide=id.g157539adf3_0_111)
	
### API examples:	
##### SQL API:
		
Select *
	
	https://ashleysimcox.carto.com/api/v2/sql?q=SELECT * FROM ny_boroughs

Get count rows:

	https://ashleysimcox.carto.com/api/v2/sql?q=SELECT count(*) FROM ny_boroughs	
	
Export as Shapefile:
	
	http://ashleysimcox.cartodb.com/api/v2/sql?q=SELECT * FROM ny_boroughs	&format=shp	
	
	
#### Static Maps API example	

	https://cartocdn-ashbu.global.ssl.fastly.net/nygeog/api/v1/map/static/named/tpl_2034a658_8fe9_11e6_9bbb_0e233c30368f/600/300.png	
	
	
	
	
If we move very quickly. Here are some **additional exercises** we can work on:

* [Styling Maps: Vintage Map of Africa with CartoCSS](03-cartography/exercises/africa.md)
* [Market Analysis (Dominos Pizza) Demo](02-builder-analysis/exercises/dominos.md)


# CARTO Course Materials

## [Introduction to CARTO](00-intro-carto/). 

Introduction to the training sessions, GIS and webmapping and general explanation about CARTO as a platform: product positioning, general overview of the portfolio and examples of how CARTO can solve different use cases.

## [CARTO BUILDER I: Data visualizations and Styling](01-builder-visualization/). 

This course will cover different BUILDER (CARTO's web interface) workflows for generating cartographic data visualizations. We'll dig into new Builder features and some differences with old Editor. During this first part, we'll cover those aspects related to data visualizations, cartographic styles, legend's definition and dashboard creation with actionable Widgets that interact with the map.

## [CARTO BUILDER II: Geospatial analysis and prediction](02-builder-analysis/). 
This advanced workshop will let users know the most powerful analytic capabilities of CARTO BUILDER. Analysis workflows and its link with Widgets will occupy the central part of the course, along with a review of the different analyses that BUILDER currently offers.

## [Cartography and advanced symbology](03-cartography/). 

This session focuses on the advanced use of BUILDER, creating cartographic rules for powerful webmap visualizations. It also goes through our new tools for thematic mapping (TurboCARTO) and all the different options that Torque offers for creating dynamic maps.

## More Resources

#### Map Academy, tutorials and other online resources

* [**Map Academy** courses](https://academy.cartodb.com/).
* [**Tutorials**](https://docs.cartodb.com/tutorials/).
* [Carto Docs](https://carto.com/docs)
* [Other online resources](https://github.com/ramiroaznar/intro-cartodb).

#### Further questions and troubleshooting

* Email to **support@carto.com**.
* Some questions could be already answered at **[GIS Stack Exchange](http://gis.stackexchange.com/questions/tagged/carto)** `carto` tag.


<a name="complete"></a>
CARTO complete Training Course
============================
This link provides access to our full-week intensive training.

## [http://bit.ly/carto-workshop](http://bit.ly/carto-workshop)