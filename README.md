# awesome-transit [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 435,879 | 🐛 68 | 📅 2026-01-28 [![RSS](https://img.shields.io/badge/Subscribe-RSS-blue.svg)](https://github.com/MobilityData/awesome-transit/commits/master.atom) ⭐ 1,664 | 🐛 15 | 📅 2026-01-30

##### Community list of data standards, APIs, apps, tools, datasets, and research around open source technology of public transit.

Open technology provides an opportunity for various stakeholders to collaborate efforts to improve public transit.

Elements of open technology include:

* Open standards
* Open data
* Open source software (both as consumer-facing apps like OpenTripPlanner and developer tools like the GTFS Validator)

This list is focused around the open technology ecosystem for public transportation. Included technologies may be open source themselves and/or rely on open standards and/or open data.

Have something to add or change? Open a [pull request](https://github.com/MobilityData/awesome-transit/pulls) ⭐ 1,664 | 🐛 15 | 📅 2026-01-30 or [issue](https://github.com/MobilityData/awesome-transit/issues) ⭐ 1,664 | 🐛 15 | 📅 2026-01-30 at [MobilityData/awesome-transit](https://github.com/MobilityData/awesome-transit) ⭐ 1,664 | 🐛 15 | 📅 2026-01-30.

***

### Table of Contents

* [Producting Data](#producing-data)
  * [GTFS](#gtfs)
    * [GTFS Libraries](#gtfs-libraries)
    * [GTFS Converters](#gtfs-converters)
    * [GTFS Data Collection and Maintenance Tools](#gtfs-data-collection-and-maintenance-tools)
    * [GTFS Merge Tools](#gtfs-merge-tools)
    * [GTFS Analysis Tools](#gtfs-analysis-tools)
    * [GTFS Timetable Publishing Tools](#gtfs-timetable-publishing-tools)
    * [GTFS Validators](#gtfs-validators)
  * [GTFS Realtime](#gtfs-realtime)
    * [GTFS Realtime Libraries & Demo Apps](#gtfs-realtime-libraries--demo-apps)
    * [GTFS Realtime Validators](#gtfs-realtime-validators)
    * [GTFS Realtime (and Other Real-time API) Archival Tools](#gtfs-realtime-and-other-real-time-api-archival-tools)
    * [GTFS Realtime Convertors](#gtfs-realtime-convertors)
    * [GTFS Realtime Utilities](#gtfs-realtime-utilities)
  * [SIRI](#siri)
  * [Other multimodal data formats](#other-multimodal-data-formats)
* [Sharing Data](#sharing-data)
* [Using Data](#using-data)
  * [Consumer Apps](#consumer-apps)
    * [Web Apps (open source)](#web-apps-open-source)
    * [Web Apps (closed source)](#web-apps-closed-source)
    * [Native Apps (open source)](#native-apps-open-source)
    * [Native Apps (closed source)](#native-apps-closed-source)
  * [Hardware](#hardware)
  * [Software for Creating APIs](#software-for-creating-apis)
  * [SDKs](#sdks)
  * [Visualizations](#visualizations)
  * [Agency Tools](#agency-tools)
* [Resources](#resources)
  * [Community](#community)

## Producing Data

### GTFS

* [GTFS.org](https://gtfs.org) official documentation site for the General Transit Feed Specification.

#### GTFS Courses

* [GTFS-books](https://github.com/MobilityData/GTFS-books) ⭐ 20 | 🐛 1 | 📅 2023-05-29 - Comprehensive guides to GTFS and GTFS Realtime. These books were written by [Quentin Zervaas](https://github.com/HendX), and have been donated to [MobilityData](https://mobilitydata.org/) and made open access.
* [MBTA GTFS Onboarding](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb) - An interactive tutorial created by MBTA for GTFS static. A [stand-alone Docker image](https://github.com/mbta/gtfs_onboarding) ⭐ 8 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-01-10 is available on GitHub as well as a [hosted/no-install version](https://mybinder.org/v2/gh/mbta/gtfs_onboarding/main?urlpath=lab/tree/GTFS_Onboarding.ipynb) of the Jupyter notebook.
* [MobilityData - "Understanding GTFS: An intro and overivew](https://www.youtube.com/watch?v=SDz2460AjNo) - Video provides an overview of of the General Transit Feed Specification (GTFS) and why it is useful for transit agencies, riders, and policymakers.
* [World Bank - "Intro. to GTFS" online course](https://olc.worldbank.org/content/introduction-general-transit-feed-specification-gtfs-and-informal-transit-system-mapping) - A free, online, self-paced course for learning about GTFS and GTFS-realtime.
* [Open Transit Data Toolkit](http://transitdatatoolkit.com/) - A series of lessons to help people utilize open transit data.
* [ArcGIS - Introduction to GTFS](https://www.youtube.com/watch?v=8OQKHhu1VgQ\&t=148s)
* [Planetizen "Building a Transit Map Web App" course](https://courses.planetizen.com/course/building-transit-map-app) - A video tutorial on setting up your own web-based mapping application, with no coding experience required.

#### GTFS Consumer App Guidance

* [Google Transit Developers](https://developers.google.com/transit/gtfs/) - Additional Google-specific documentation of GTFS.
* [Transit app Guidelines for Producing GTFS Static Data](https://resources.transitapp.com/article/458-guidelines-for-producing-gtfs-static-data-for-transit) - Additional Transit app-specific documentation of GTFS.
* [Bing Maps Transit - Add your transit data to Bing Maps](https://www.bing.com/maps/transitcontentproviders) - Additional Bing-specific documentation of GTFS.
* [Yandex Maps - Transport integration](https://yandex.ru/support/m-maps/transport.html?lang=en#connect-display) - Additional Yandex-specific documentation of GTFS.

#### GTFS Libraries

Software that makes it easy to consume GTFS data in a variety of languages.

##### C

* [RRRR Rapid Real-time Routing](https://github.com/bliksemlabs/rrrr) ⭐ 173 | 🐛 48 | 🌐 C | 📅 2020-12-27 - RRRR (usually pronounced R4) is a C-language implementation of the RAPTOR public transit routing algorithm.
* [CGTFS](https://github.com/rakhack/cgtfs) ⭐ 10 | 🐛 0 | 🌐 C | 📅 2019-08-22 - C library for reading static GTFS feeds. Supports reading unpacked feeds into application memory or into SQLite databases.

##### C++

* [just\_gtfs](https://github.com/mesozoic-drones/just_gtfs) ⭐ 26 | 🐛 2 | 🌐 C++ | 📅 2023-11-10 - C++17 header-only library for reading and writing GTFS (used in [Valhalla](https://github.com/valhalla/valhalla) ⭐ 5,365 | 🐛 867 | 🌐 C++ | 📅 2026-02-07). Main features: fast reading and writing of GTFS feeds, support for [extended GTFS route types](https://developers.google.com/transit/gtfs/reference/extended-route-types), simple working with GTFS Date and Time formats.

##### C\#

* [ESRI public-transit-tools](https://github.com/Esri/public-transit-tools) ⭐ 185 | 🐛 9 | 🌐 Python | 📅 2026-01-28 - Tools for working with public transit data in ArcGIS (license for ArcGIS required).
* [GTFS Feed Parser](https://github.com/OsmSharp/GTFS) ⭐ 73 | 🐛 20 | 🌐 C# | 📅 2022-04-25 - .Net/Mono implementation of a GTFS parser.

##### Go

* [Go GTFS Parser](https://github.com/geops/gtfsparser) ⭐ 49 | 🐛 1 | 🌐 Go | 📅 2018-08-17 - A GTFS parsing library for Go.

##### Java

* [OneBusAway GTFS Modules](https://github.com/OneBusAway/onebusaway-gtfs-modules/wiki) ⭐ 142 | 🐛 31 | 🌐 Java | 📅 2026-01-29 - A Java-based library for reading, writing, and transforming public transit data in the GTFS format, including database support.

##### JavaScript

* [Node-GTFS](https://github.com/BlinkTagInc/node-gtfs) ⭐ 493 | 🐛 8 | 🌐 TypeScript | 📅 2026-01-22 - Loads transit data from GTFS files, unzips it and stores it to a SQLite database. Provides some methods to query for agencies, routes, stops and times.
* [gtfs-via-postgres](https://github.com/derhuerst/gtfs-via-postgres) ⭐ 127 | 🐛 30 | 🌐 JavaScript | 📅 2025-12-11 – Yet another tool to process GTFS using PostgreSQL.
* [gtfs-utils](https://github.com/public-transport/gtfs-utils) ⭐ 45 | 🐛 16 | 🌐 JavaScript | 📅 2022-02-26 – Utilities to process GTFS data sets (e.g., "flattening" `calendar.txt` & `calendar_dates.txt`, computing arrival/departure times of trips).
* [gtfs-sequelize](https://github.com/evansiroky/gtfs-sequelize) ⭐ 20 | 🐛 2 | 🌐 JavaScript | 📅 2018-01-15 - Node.js library modeling the static GTFS using sequelize.js.

##### PostgreSQL

* [gtfs-via-postgres](https://github.com/derhuerst/gtfs-via-postgres) ⭐ 127 | 🐛 30 | 🌐 JavaScript | 📅 2025-12-11 – Yet another tool to process GTFS using PostgreSQL.
* [gtfs-schema](https://github.com/tyleragreen/gtfs-schema) ⚠️ Archived - PostgreSQL schema for GTFS feeds.

##### Python

* [ESRI public-transit-tools](https://github.com/Esri/public-transit-tools) ⭐ 185 | 🐛 9 | 🌐 Python | 📅 2026-01-28 - Tools for working with public transit data in ArcGIS (license for ArcGIS required).
* [partridge](https://github.com/remix/partridge) ⭐ 179 | 🐛 7 | 🌐 Python | 📅 2023-12-03 - A fast, forgiving Python GTFS reader built on pandas DataFrames.
* [gtfsdb](https://github.com/OpenTransitTools/gtfsdb) ⭐ 174 | 🐛 17 | 🌐 Python | 📅 2026-01-12 - Python library for converting GTFS files into a relational database.
* [gtfspy](https://github.com/CxAalto/gtfspy) ⭐ 167 | 🐛 21 | 🌐 Python | 📅 2023-05-23 - Public transport network analysis and travel time computations using Python3. Compatible with Postgres/PostGIS, Oracle, MySQL, and SQLite. Used by [gtfspy-webviz](https://github.com/CxAalto/gtfspy-webviz) ⭐ 64 | 🐛 4 | 🌐 JavaScript | 📅 2024-08-27.
* [gtfs\_functions](https://github.com/Bondify/gtfs_functions) ⭐ 135 | 🐛 12 | 🌐 Python | 📅 2025-10-27 - Python package with useful functions to create geo-spatial visualizations from GTFS feeds.
* [GTFS Kit](https://github.com/mrcagney/gtfs_kit) ⭐ 111 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-02-04 - A Python 3.8+ tool kit for analyzing General Transit Feed Specification (GTFS) data. Supersedes GTFSTK.
* [multigtfs](https://github.com/tulsawebdevs/django-multi-gtfs) ⭐ 55 | 🐛 35 | 🌐 Python | 📅 2023-02-10 - A Django application to import and export GTFS.
* [gtfs-segments](https://github.com/UTEL-UIUC/gtfs_segments) ⭐ 49 | 🐛 3 | 🌐 Python | 📅 2025-06-30 - Python package that represents GTFS data for buses in a concise tabular manner using segments.
* [gtfslib-python](https://github.com/afimb/gtfslib-python) ⚠️ Archived -  An open source library in python for reading GTFS files and computing various stats and indicators about Public Transport networks.
* [TransitGPT](https://github.com/UTEL-UIUC/TransitGPT) ⭐ 37 | 🐛 0 | 🌐 Python | 📅 2025-03-17 - TransitGPT is a Generative AI-powered chatbot that enables transit enthusiasts to access and analyze General Transit Feed Specification (GTFS) data through natural language instructions.
* [Mapzen GTFS](https://github.com/transitland/mapzen-gtfs) ⭐ 30 | 🐛 4 | 🌐 Python | 📅 2018-12-07 - A Python GTFS library that supports reading individual GTFS tables, or constructing a graph to represent each agency in a feed.
* [gtfsman](https://github.com/geops/gtfsman) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2016-11-11 - Repository-like tool in Python to manage and update a huge number of GTFS feeds.
* [transit\_service\_analyst](https://github.com/psrc/transit_service_analyst) ⭐ 13 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2025-08-28 - A Python library to support transit service analysis.
* [Make GTFS](https://github.com/mrcagney/make_gtfs) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2024-12-19 - A Python library to make GTFS feeds from basic route information.

##### R

* [tidytransit](https://github.com/r-transit/tidytransit) ⭐ 162 | 🐛 4 | 🌐 R | 📅 2026-01-29 - Use tidytransit to map transit stops and routes, calculate travel times and transit frequencies, and validate transit feeds. tidytransit reads the General Transit Feed Specification into tidyverse and simple features data frames.
* [gtfsio](https://github.com/r-transit/gtfsio) ⭐ 17 | 🐛 3 | 🌐 R | 📅 2025-10-16 - Fast and flexible functions to read and write GTFS in R.
* [mobdb](https://github.com/jasonad123/mobdb) ⭐ 7 | 🐛 2 | 🌐 R | 📅 2026-02-05 - R functions to search, discover, and access transit feed data from the [Mobility Database](https://mobilitydatabase.org/).
* [r-transit](https://github.com/r-transit) - Collection of tools for GTFS in R.

##### Ruby

* [GTFS-viz](https://github.com/vasile/GTFS-viz) ⭐ 92 | 🐛 8 | 🌐 Ruby | 📅 2016-03-20 - Ruby script that converts a set of GTFS files into a SQLite database + GeoJSONs (needed by the [Transit Map](https://github.com/vasile/transit-map) ⭐ 369 | 🐛 10 | 🌐 JavaScript | 📅 2019-03-12 web application)

##### Rust

* [gtfs-structure](https://github.com/rust-transit/gtfs-structure) ⭐ 70 | 🐛 21 | 🌐 Rust | 📅 2026-02-03 - This crates provides GTFS structures and helpers to read GTFS archives.

#### GTFS Converters

Converters from various static schedule formats to and from GTFS.

* [gtfs-to-geojson](https://github.com/BlinkTagInc/gtfs-to-geojson) ⭐ 149 | 🐛 3 | 🌐 TypeScript | 📅 2026-01-22 - Javascript tool that converts transit data in GTFS shapes and stops into geoJSON. This is useful for creating maps of transit routes.
* [osm2gtfs](https://github.com/grote/osm2gtfs) ⭐ 100 | 🐛 32 | 🌐 Python | 📅 2024-04-04 - Turn OpenStreetMap data and schedule information into GTFS.
* [GTFS-OSM-Sync](https://github.com/CUTR-at-USF/gtfs-osm-sync) ⚠️ Archived - A Java tool for synchronizing data in GTFS format with [OpenStreetMap.org](http://www.openstreetmap.org/).
* [gtfs2gps](https://github.com/ipeaGIT/gtfs2gps) ⭐ 77 | 🐛 11 | 🌐 R | 📅 2025-10-08 - An R package that converts public transportation data in GTFS format to GPS-like records in a `data.table`, where each row represents the timestamp of each vehicle at a given spatial resolution.
* [transit\_model](https://github.com/hove-io/transit_model) ⭐ 66 | 🐛 13 | 🌐 Rust | 📅 2026-01-26 - A Rust library to convert to/from the following formats: GTFS, NTFS (for Navitia, see [Software for Creating APIs](#software-for-creating-apis)), TransXChange (UK specification), KV1 (NL specification), NeTEx (EU specification).
* [gtfs2emis](https://github.com/ipeaGIT/gtfs2emis) ⭐ 32 | 🐛 11 | 🌐 R | 📅 2026-02-03 - An R package to estimate the emission levels of public transport vehicles based on General Transit Feed Specification (GTFS) data.
* [Open-Transport SYNTHESE Convertors](https://github.com/Open-Transport/synthese/wiki) ⭐ 24 | 🐛 1 | 🌐 C++ | 📅 2016-01-29 - Converts French-Transmodel, SIRI, NETeX, HAFAS, HASTUS, VDV452, and more.
* [GTFS-route-shapes](https://github.com/kotrc/GTFS-route-shapes) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2016-02-03 - A Python script to generate a single geoJSON shape for each transit route in a GTFS archive.
* [onebusaway-vdv-modules](https://github.com/OneBusAway/onebusaway-vdv-modules) ⭐ 15 | 🐛 4 | 🌐 Java | 📅 2022-03-02 - A Java library for working with transit data in the VDV format, including converting VDV-452 schedule data into GTFS.
* [o2g](https://github.com/hiposfer/o2g) ⭐ 13 | 🐛 5 | 🌐 Python | 📅 2019-08-13 - A simple tool to extract GTFS feed from OpenStreetMap.
* [Hafas2GTFS](https://github.com/geops/hafas2gtfs) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2014-03-25 - Hafas2GTFS converter written in Python, optimized for SBB HAFAS feeds.
* [kml-to-gtfs-shapes](https://github.com/bdferris/kml-to-gtfs-shapes/tree/gh-pages) ⭐ 9 | 🐛 0 | 📅 2014-11-16 - Javascript tool to convert polylines from a KML file into a GTFS shapes.txt file. Hosted on GitHub [here](http://bdferris.github.io/kml-to-gtfs-shapes/).
* [NeTEx-to-GTFS Converter Java](https://github.com/entur/netex-gtfs-converter-java) ⭐ 8 | 🐛 10 | 🌐 Java | 📅 2026-02-02 - Converts NeTEX datasets into GTFS datasets. The input NeTEx datasets are required to follow the Nordic NeTEx Profile.
* [extract-gtfs-shapes](https://github.com/derhuerst/extract-gtfs-shapes) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2021-05-20 – Command-line tool to extract shapes as GeoJSON from a GTFS dataset.
* [gtfs-parser](https://github.com/ioTransit/gtfs-parser) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2023-11-19 - The GTFS-PARSER library is a library to allow javascript to parse gtfs and create geojson on client or server.
* [hafas-generate-gtfs](https://github.com/derhuerst/hafas-generate-gtfs) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2020-07-30 *(work-in-progress)* – A Javascript tool to generate GTFS dumps from HAFAS endpoints.
* [Transmodel and IFF to GTFS](https://github.com/bliksemlabs/bliksemintegration) ⭐ 6 | 🐛 7 | 🌐 Python | 📅 2015-07-11 - Imports and syncs (Transmodel) BISON Koppelvlak1, IFF (a format written by HP/EDS, somewhat similiar to ATCO CIF) to import timetables of the railway networks. The internal pseudo-NETeX datastructure allows to export to GTFS and there are proof-of-concepts to export to other formats such as NETeX, GTFS and IFF.
* [extract-gtfs-pathways](https://github.com/derhuerst/extract-gtfs-pathways) ⭐ 4 | 🐛 1 | 🌐 JavaScript | 📅 2024-07-01 – Command-line tool to extract pathways as GeoJSON from a GTFS dataset.
* [gtfs-service-area](https://github.com/cal-itp/gtfs-service-area) ⚠️ Archived - Compute a transit service area from static GTFS. Results are output as single-layer .geojson files. Dockerized version of [gtfs-to-geojson](https://github.com/BlinkTagInc/gtfs-to-geojson) ⭐ 149 | 🐛 3 | 🌐 TypeScript | 📅 2026-01-22.
* [gtsf](https://github.com/r-gtfs/gtsf) ⚠️ Archived - general transit (GTFS) simple (geographic) features (sf) in R. can be used to convert from GTFS to Shapefile, GeoJSON, and other formats through GDAL.
* [Transporter-Project transxchange-to-gtfs](https://github.com/Transporter-Project/transxchange-to-gtfs) ⭐ 3 | 🐛 1 | 🌐 Objective-C | 📅 2015-02-15 TransXChange to GTFS converter written in Objective-C.
* [transloc-gtfs-rectifier](https://github.com/laidig/transloc-gtfs-rectifier) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2018-01-11 - Python application that attempts to assign GTFS stop\_ids to [TransLoc](http://transloc.com/) IDs using [TransLoc's API](https://market.mashape.com/transloc/openapi-1-2) ([TransLoc](http://transloc.com/) doesn't provide GTFS `stop_ids` in their API).
* [onebusaway-gtfs-to-barefoot](https://github.com/OneBusAway/onebusaway-gtfs-to-barefoot) ⭐ 1 | 🐛 1 | 🌐 Java | 📅 2020-02-11 - A Java tool to create a [Barefoot](https://github.com/bmwcarit/barefoot) ⭐ 688 | 🐛 58 | 🌐 Java | 📅 2023-04-14 mapfile from a GTFS file.
* [Chouette](https://enroute.atlassian.net/wiki/spaces/PUBLIC/pages/539426886/Chouette+Convert) - Converts between French-Transmodel [NeTEX](https://transmodel-cen.eu/index.php/netex/) and GTFS.
* [TXC TransXChange publisher (UK Department for Transport)](https://www.gov.uk/government/publications/transxchange-publisher) - The TXC TransXChange publisher is a standalone software tool that can be used to publish TransXChange compliant XML documents in a format that’s easy to read and print.
* [UK2GTFS](https://itsleeds.github.io/UK2GTFS/) - R package that converts UK format TransXchange (bus, metro, tram, ferry) and CIF (rail) timetables to GTFS.
* [OSMTracker](https://wiki.openstreetmap.org/wiki/OSMTracker_\(Android\)) - OSMTracker is an offline GPS tracking app designed for collecting Points of Interest (POIs) and recording GPX tracks for collaborative use.

#### GTFS Data Collection and Maintenance Tools

* [pfaedle](https://github.com/ad-freiburg/pfaedle) ⭐ 265 | 🐛 12 | 🌐 C++ | 📅 2026-01-09 - Precise map-matching for GTFS using OpenStreetMap data
* [static-GTFS-manager](https://github.com/WRI-Cities/static-GTFS-manager) ⭐ 156 | 🐛 64 | 🌐 JavaScript | 📅 2022-06-05 - A (self-hosted) browser-based user interface for creating, editing, exporting static GTFS (see [related post](https://groups.google.com/forum/#!topic/transit-developers/GFz5rTJTB0I)).
* [IBI Data Tools](https://github.com/ibi-group/datatools-ui) ⭐ 140 | 🐛 151 | 🌐 JavaScript | 📅 2026-02-05 - A web application that handles GTFS editing, validating, quality checking, and deploying to OpenTripPlanner. (Combines and builds upon the functionality of the deprecated
* [GTFS Editor](https://github.com/conveyal/gtfs-editor) ⭐ 138 | 🐛 134 | 🌐 JavaScript | 📅 2017-06-20 - A (self-hosted) web-based GTFS editing framework. (Note: this project has been deprecated in favor of [IBI Data Tools](https://github.com/ibi-group/datatools-ui) ⭐ 140 | 🐛 151 | 🌐 JavaScript | 📅 2026-02-05.)
* [Data-Tools Server](https://github.com/ibi-group/datatools-server) ⭐ 54 | 🐛 43 | 🌐 Java | 📅 2026-01-29 - Server for IBI's GTFS data management platform.
* [TransitWand](https://github.com/conveyal/transit-wand) ⭐ 44 | 🐛 17 | 🌐 JavaScript | 📅 2015-07-01 - An open source web and mobile application for collecting transit data. Use it to create GTFS feeds, capture passenger counts or generate GIS datasets.
* [bus-router](https://github.com/atlregional/bus-router) ⭐ 40 | 🐛 3 | 🌐 Python | 📅 2016-12-20 - Python script that generates missing shapes.txt for GTFS using routing from [Google Maps Directions API](https://developers.google.com/maps/documentation/directions/) or [OSRM](https://github.com/Project-OSRM/osrm-backend/wiki/Server-api) ⭐ 7,457 | 🐛 442 | 🌐 C++ | 📅 2026-02-06.
* [Gtfs Data Manager](https://github.com/conveyal/gtfs-data-manager) ⭐ 24 | 🐛 37 | 🌐 JavaScript | 📅 2016-04-22 and [GTFS Editor](https://github.com/conveyal/gtfs-editor) ⭐ 138 | 🐛 134 | 🌐 JavaScript | 📅 2017-06-20.)
* [gtfs-station-builder](https://github.com/kostjerry/gtfs-station-builder) ⭐ 20 | 🐛 8 | 🌐 TypeScript | 📅 2023-05-06 - UI tool to help build the internal structure of stations (including pathways.txt)
* [Amarillo](https://github.com/mfdz/amarillo) ⭐ 11 | 🐛 11 | 🌐 Python | 📅 2026-01-28 - Aggregates and enhances carpooling-offers and publishes them as GTFS(-RT)
* [GTFS shape mapfit](https://github.com/HSLdevcom/gtfs_shape_mapfit) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2023-11-23 - Python tool that fits GTFS shape files and stops to a given OSM map file. Uses [pymapmatch](https://github.com/tru-hy/pymapmatch) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2015-06-30 for the matching.
* [gtfs-blocks-to-transfers](https://github.com/TransitApp/GTFS-blocks-to-transfers) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-11-12 - A Python tool to convert GTFS blocks, defined by setting [trip.block\_id](https://github.com/google/transit/blob/master/gtfs/spec/en/reference.md#example-blocks-and-service-day) ⭐ 898 | 🐛 132 | 📅 2026-02-02 into a series of [trip-to-trip transfers (proposal)](https://github.com/google/transit/pull/303) ⭐ 898 | 🐛 132 | 📅 2026-02-02.
* [GTFS Editor for Vagrant](https://github.com/laidig/vagrant-gtfs-editor) ⭐ 7 | 🐛 2 | 🌐 Shell | 📅 2017-06-03 - Quickly set up the GTFS editor (above) using [Vagrant](https://www.vagrantup.com/)
* [Uttu](https://github.com/entur/uttu) ⭐ 6 | 🐛 15 | 🌐 Java | 📅 2026-02-02 - Back-end for Nplan, a simple timetable editor.
* [GTFS Text-to-Speech Tester](https://github.com/BlinkTagInc/node-gtfs-tts) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2025-04-01 - A command-line tool that reads GTFS stop names out loud using Text-to-Speech to determine which need Text-to-Speech values for tts\_stop\_name in stops.txt.
* [IBI Data Tools Infra](https://github.com/cal-itp/ibi-datatools-infra) ⭐ 4 | 🐛 1 | 🌐 Dockerfile | 📅 2023-10-24 - A tool to quickly setup and run a local instance of the above IBI Data Tools project.
* [AddTransit](https://addtransit.com/gtfs-transit-file.php) - SaaS (Software as a Service) platform to create, edit and publish schedules in GTFS format.
* [GTFS Diff](https://transport.data.gouv.fr/tools/gtfs_diff) - GTFS Diff is a specification created by transport.data.gouv.fr and aims at providing a simple and unified way to express differences between GTFS files.
* [GTFS.html](https://gtfs.pleasantprogrammer.com) - An entirely browser-based tool to view GTFS feeds. Use it to view routes, stops, timetables, etc.
* [GTFS Builder](http://nationalrtap.org/Web-Apps/GTFS-Builder) - A free web-based application to help you create GTFS files. Maintained by the National Rural Transit Assistance Program (RTAP).
* [Spare GTFS-Flex Builder](https://sparelabs.com/en/spare-gtfs-flex-builder) - A free tool that helps transit agencies easily create, manage, and export their transportation data in GTFS-Flex format.
* [Swiftly](https://goswift.ly/) - Tool generate realtime transit data.
* [Chouette SaaS](https://bitbucket.org/enroute-mobi/chouette-core) - Tool to generate GTFS Schedule data
* [Ara SaaS](https://bitbucket.org/enroute-mobi/ara) - Tool to generate GTFS Realtime data.
* [GTFS Studio](https://gtfs.studio) - Online editor for GTFS feeds

#### GTFS Merge Tools

* [Transitfeed merge function](https://github.com/google/transitfeed/wiki/Merge) ⚠️ Archived - A Python library with a function to merge two different GTFS feeds.
* [GTFS Kit](https://github.com/mrcagney/gtfs_kit) ⭐ 111 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-02-04 - A Python 3.8+ tool kit for analyzing and merging General Transit Feed Specification (GTFS) data. [Info on how to aggregate and clean feeds provided here](https://mrcagney.github.io/gtfs_kit_docs/index.html#module-gtfs_kit.cleaners).
* [combine\_gtfs\_feeds](https://github.com/psrc/combine_gtfs_feeds) ⭐ 9 | 🐛 2 | 🌐 Python | 📅 2025-04-25 - A Python tool to combine multiple gtfs feeds into one feed/dataset.
* [gtfsmerge](https://github.com/now8-org/gtfsmerge) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-01-30 - A Python Script to merge GTFS ZIP archives into one.

#### GTFS Analysis Tools

* [R5: Rapid Realistic Routing on Real-world and Reimagined networks](https://github.com/conveyal/r5) ⭐ 361 | 🐛 237 | 🌐 Java | 📅 2026-01-26 - A Java-based routing engine developed by Conveyal for multimodal (transit/bike/walk/car) networks. It currently plans many trips over a time window for scenario planning and analytics purposes. A related R wrapper package ([r5r](https://github.com/ipeaGIT/r5r/) ⭐ 224 | 🐛 32 | 🌐 R | 📅 2026-02-03) is developed independently by IPEA. See also the performance comparison from Higgins et al. (2022), linked below.
* [Peartree](https://github.com/kuanb/peartree) ⭐ 208 | 🐛 23 | 🌐 Python | 📅 2023-05-05 - A Python library for converting transit data into a directed graph for network analysis.
* [ESRI ArcGIS Public Transit Tools (GTFS)](https://github.com/Esri/public-transit-tools) ⭐ 185 | 🐛 9 | 🌐 Python | 📅 2026-01-28 - Tools for working with public transit data in ArcGIS
* [tidytransit](https://github.com/r-transit/tidytransit) ⭐ 162 | 🐛 4 | 🌐 R | 📅 2026-01-29 - An R package to read GTFS data into tibbles and simple features dataframes to map transit stops and routes, calculate travel times and transit frequencies, and validate transit feeds.
* [GTFS Kit](https://github.com/mrcagney/gtfs_kit) ⭐ 111 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-02-04 - A Python 3.6+ tool kit for analyzing General Transit Feed Specification (GTFS) data. Supersedes [GTFSTK](https://github.com/araichev/gtfstk).
* [gtfstools](https://github.com/ipeaGIT/gtfstools) ⭐ 46 | 🐛 17 | 🌐 R | 📅 2025-01-21 - A set of convenient tools for editing and analysing transit feeds in GTFS format in R.
* [GTFS-to-Chart](https://github.com/BlinkTagInc/gtfs-to-chart) ⭐ 38 | 🐛 1 | 🌐 JavaScript | 📅 2026-01-22 - Creates stringline charts showing all vehicles on a transit route from GTFS data.
* [transitr](https://github.com/tmelliott/transitr) ⭐ 23 | 🐛 18 | 🌐 C++ | 📅 2023-06-06 - An R package for constructing and modelling a transit network in real time to obtain vehicle ETAs
* [transit\_service\_analyst](https://github.com/psrc/transit_service_analyst) ⭐ 13 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2025-08-28 - A Python library to support transit service analysis.
* [Busbuzzard](https://github.com/bmander/busbuzzard) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2013-09-05 - Inference of probabilistic schedules from empirical data about transit vehicles.
* [transit-intensity](https://github.com/ioTransit/transit-intensity) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2024-04-10 - A simple project for measuring transit intensity written in Go.
* [GTFS Display](https://codeberg.org/dancingCycle/gtfs-display) - Analyse, monitor and maintain GTFS data ([Example instances](https://www.swingbe.de/activity/gtfs-display/)).
* [PTNA](https://wiki.openstreetmap.org/wiki/Public_Transport_Network_Analysis) - Public Transit Nework Analysis is a open source system for finding and aggregating information about public transportation lines mapped in OSM.

#### GTFS Timetable Publishing Tools

* [Timetable Kit](https://github.com/neroden/timetable_kit) ⭐ 47 | 🐛 5 | 🌐 Python | 📅 2024-08-10 - An open source Python 3.10 module and scripts depending on [GTFS Kit](https://github.com/mrcagney/gtfs_kit) ⭐ 111 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-02-04, designed to create complex printed/PDF timetables with flexible layouts. Currently only working out of the box for Amtrak's GTFS, but under active development.
* [TimeTablePublisher (TTPUB)](https://github.com/OpenTransitTools/ttpub) ⭐ 26 | 🐛 2 | 🌐 HTML | 📅 2019-09-06 - A web publishing system developed by TriMet that allows a transit agency to examine, modify, and transform raw scheduling data into easy-to-read timetables for customer information purposes
* [GTFS-to-HTML](https://gtfstohtml.com) - Generate human-readable timetables in HTML or PDF format directly from GTFS.

#### GTFS Validators

* [Google's feedValidator](https://github.com/google/transitfeed/wiki/FeedValidator) ⚠️ Archived - Google-supported Python-based GTFS validator.
* [MobilityData's gtfs-validator](https://github.com/MobilityData/gtfs-validator) ⭐ 386 | 🐛 173 | 🌐 Java | 📅 2026-02-06 - A open-source GTFS validator canonically following the GTFS spec implemented in Java licensed under Apache v2.0 maintained by [MobilityData](https://mobilitydata.org/).
* [gtfstidy](https://github.com/patrickbr/gtfstidy) ⭐ 140 | 🐛 14 | 🌐 Go | 📅 2026-01-19 - A Go-based tool to tidy and validate GTFS feeds.
* [Conveyal's gtfs-lib](https://github.com/conveyal/gtfs-lib/) ⭐ 78 | 🐛 65 | 🌐 Java | 📅 2024-05-16 - Conveyal's successor to their own [gtfs-validator](https://github.com/conveyal/gtfs-validator) ⭐ 37 | 🐛 19 | 🌐 Java | 📅 2021-04-11, a Java-based library for loading and saving GTFS feeds of arbitrary size with disk-backed storage.
* [Reflect GTFS Validator (hosted by Foursquare ITP)](https://reflect.foursquareitp.com) - Transit schedule and GTFS validation platform by [Foursquare ITP](https://www.foursquareitp.com) that includes a free, web-based GTFS validator based on [gtfs-lib](https://github.com/conveyal/gtfs-lib/) ⭐ 78 | 🐛 65 | 🌐 Java | 📅 2024-05-16.
* [Transport Validator](https://github.com/etalab/transport-validator/) ⭐ 46 | 🐛 10 | 🌐 Rust | 📅 2026-02-05 - An open-source validator implemented in [Rust](https://www.rust-lang.org/). Used by the [French National Access Point](https://transport.data.gouv.fr/validation/).
* [Conveyal's gtfs-validator](https://github.com/conveyal/gtfs-validator) ⭐ 37 | 🐛 19 | 🌐 Java | 📅 2021-04-11 - A Java-based GTFS validator based on the OneBusAway GTFS Modules, runs in Java and is faster than the Google provided one.
* [GTFSVTOR](https://github.com/mecatran/gtfsvtor) ⭐ 30 | 🐛 20 | 🌐 Java | 📅 2024-11-28 - An open-source GTFS validator implemented in Java licensed under GPLv3 maintained by [Mecatran](https://www.mecatran.com/).
* [GTFS Data Package Specification](https://github.com/Stephen-Gates/GTFS) ⭐ 18 | 🐛 9 | 🌐 Python | 📅 2018-03-19 - A Data Package specification with validation accomplished with Good Tables. Includes a data package, schemas, tests, and uses South East Queensland GTFS data as an example.
* [gtfsclean](https://github.com/public-transport/gtfsclean) ⭐ 16 | 🐛 4 | 🌐 Go | 📅 2025-09-13 - A tool for checking, sanitizing, and minimizing GTFS feeds. Fork of gtfstidy, with some additional fixes that haven't been merged upstream yet.
* [Transit App's gtfs-fares-v2-validator](https://github.com/TransitApp/gtfs-fares-v2-validator) ⚠️ Archived - A Python tool that validators GTFS-Fares-v2 data based on the [draft specification](https://docs.google.com/document/d/19j-f-wZ5C_kYXmkLBye1g42U-kvfSVgYLkkG5oyBauY/edit#).
* [gtfs-validator-api](https://github.com/cal-itp/gtfs-validator-api) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2023-08-16 - This Python package is a thin wrapper around [MobilityData/gtfs-validator](https://github.com/MobilityData/gtfs-validator) ⭐ 386 | 🐛 173 | 🌐 Java | 📅 2026-02-06 that handles intermediate files produced and finds gtfs-validator's output file so it can be given a specific name or returned as a string.
* [gtfs-accessiblity-validator](https://github.com/BlinkTagInc/gtfs-accessibility-validator) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-01-22 - Validates the presence of accessiblity-related fields and files in a GTFS file. Can be a command line tool or node.js package.

### GTFS Realtime

* [GTFS-realtime documentation](https://github.com/google/transit/tree/master/gtfs-realtime) ⭐ 898 | 🐛 132 | 📅 2026-02-02.
* [GTFS-realtime Autodoc](https://laidig.github.io/gtfs-rt-autodoc/index.html) - Automatically generated documentation for GTFS-realtime, generated from the official [GTFS-realtime protocol buffer specification](https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto) ⭐ 898 | 🐛 132 | 📅 2026-02-02 and including some extensions.

#### GTFS Realtime Libraries & Demo Apps

* [gtfs-realtime-bindings](https://github.com/google/gtfs-realtime-bindings) ⭐ 415 | 🐛 33 | 🌐 Java | 📅 2025-12-04 - The official bindings for Java, .NET, Node.js, Python, and Ruby generated from the official [GTFS-realtime protocol buffer specification](https://github.com/google/transit/blob/master/gtfs-realtime/proto/gtfs-realtime.proto) ⭐ 898 | 🐛 132 | 📅 2026-02-02.
* [GTFS-realtime Vehicle Positions Consumer/Visualizer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-visualizer) ⭐ 64 | 🐛 6 | 🌐 Java | 📅 2022-09-07 - A Java-based demo project for consuming a GTFS-realtime Vehicle Positions feed and displaying this info on a map.
* [GTFS-realtime Exporter](https://github.com/OneBusAway/onebusaway-gtfs-realtime-exporter/wiki) ⭐ 19 | 🐛 9 | 🌐 Java | 📅 2024-05-16 - A Java-based tool that assists in producing and sharing a GTFS-relatime feed.
* [GTFS-realtime TripUpdates & VehiclePositions Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-trip-updates-producer-demo/wiki) ⚠️ Archived - A Java-based demo project for producing GTFS-realtime TripUpdates (estimated arrivals) and Vehicle Positions.
* [GTFS-realtime Alerts Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-alerts-producer-demo/wiki) ⚠️ Archived - A Java-based demo project for producing GTFS-realtime Service Alerts.
* [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) ⚠️ Archived - A Java-based web application for producing GTFS-realtime Service Alerts.
* [gtfs-rt](https://crates.io/crates/gtfs-rt) - Rust crate to read, write, and manipulate GTFS-Realtime data

#### GTFS Realtime Validators

* [gtfs-realtime-validator](https://github.com/MobilityData/gtfs-realtime-validator) ⭐ 54 | 🐛 128 | 🌐 Java | 📅 2024-11-26 - A GTFS Realtime validation tool originally developed by the [Center for Urban Transportation Research](https://www.cutr.usf.edu/) at the University of South Florida and now maintained by [MobilityData](https://mobilitydata.org/).

#### GTFS Realtime (and Other Real-time API) Archival Tools

* [retro-gtfs](https://github.com/SAUSy-Lab/retro-gtfs) ⭐ 57 | 🐛 4 | 🌐 Python | 📅 2025-09-23 - A Python application that collects real-time data from the Nextbus API and archives it into the GTFS format (i.e., retrospective GTFS).
* [gtfsrdb](https://github.com/CUTR-at-USF/gtfsrdb) ⚠️ Archived - A Python tool that supports reading and archiving GTFS-realtime feeds into a database
* [GTFS-Realtime-Capsule](https://github.com/tsdataclinic/gtfs-realtime-capsule) ⚠️ Archived - A command-line tool that scrapes, normalizes, and archives real-time public transit data.
* [gtfsdb\_realtime](https://github.com/OpenTransitTools/gtfsdb_realtime) ⭐ 13 | 🐛 4 | 🌐 Python | 📅 2024-06-18 - Real-time GTFS database loader and ORM library
* [Transi](https://gitlab.com/cutr-at-usf/transi) - A Cloud-native GTFS-RT/GTFS archiving system.

#### GTFS Realtime Convertors

* [GTFS-realtime to SIRI-Lite](https://github.com/etalab/transpo-rt/) ⭐ 23 | 🐛 13 | 🌐 Rust | 📅 2021-07-08 - A [Rust](https://www.rust-lang.org/) webserver to convert multiple GTFS-RT feeds to a SIRI-Lite API.
* [gtfs-realtime-translators](https://github.com/Intersection/gtfs-realtime-translators) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2025-12-18 - A Python-based tool to translate custom arrival API formats to GTFS-realtime.  As of July 2019 it supports LA Metro and SEPTA.
* [hafas-gtfs-rt-feed](https://github.com/derhuerst/hafas-gtfs-rt-feed) ⭐ 21 | 🐛 7 | 🌐 JavaScript | 📅 2024-04-18 – A Javascript tool to generate a GTFS Realtime feed from a HAFAS endpoint.
* [OrbCAD SQL Server to GTFS-realtime](https://github.com/CUTR-at-USF/HART-GTFS-realtimeGenerator/) ⚠️ Archived - A Java-based command-line utility that extracts vehicle positions and trip updates information from an OrbCAD SQL Server and exports them to the GTFS-realtime TripUpdates and VehiclePositions formats.
* [NextBus API to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-nextbus-cli/wiki) ⚠️ Archived - A Java-based command-line utility to convert from the [NextBus API format](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) to GTFS-realtime.  Note that NextBus now directly offers a GTFS-realtime API for their products.  See [Cubic site](http://nextbus.cubic.com/Products/Real-Time-Rider-Information) and [this FAQ](https://medium.com/omnimodal/want-more-riders-open-up-your-nextbus-api-with-gtfs-realtime-7387c80f31e1#.pkuzizhl5).
* [SIRI to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli) ⭐ 12 | 🐛 6 | 🌐 Java | 📅 2022-04-11 - A Java-based command-line utility to convert from the [SIRI format](https://www.siri.org.uk/) to GTFS-realtime
* [WMATA BusPositions API to GTFS-realtime](https://github.com/kurtraschke/wmata-gtfsrealtime) ⚠️ Archived - Java-based tool to convert from WMATA's [BusPositions API](https://developer.wmata.com/docs/services/54763629281d83086473f231/operations/5476362a281d830c946a3d68) and Alert RSS feeds from [MetroAlerts](http://www.wmata.com/rider_tools/metro_service_status/rail_bus.cfm?) to GTFS-realtime TripUpdates, VehiclePositions, and Alerts feeds.
* [CTA API to GTFS-realtime](https://github.com/kurtraschke/ctatt-gtfsrealtime) ⭐ 4 | 🐛 0 | 🌐 Java | 📅 2013-12-28 - Java-based tool to convert [CTA's](http://www.transitchicago.com/) [Train Tracker data](http://www.transitchicago.com/developers/traintracker.aspx) to GTFS-realtime.
* [Live Transit Event Trigger](https://github.com/ipublic/live_transit_event_trigger) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2013-03-26 - Extracts data from [Ride On's](http://www.montgomerycountymd.gov/dot-transit/) OrbCAD database and export as GTFS-realtime.
* [Civic Transit](https://github.com/jestin/CivicTransit) ⭐ 4 | 🐛 0 | 🌐 PHP | 📅 2013-06-02 - Screen-scrapes [KCATA’s](http://www.kcata.org/) TransitMaster WebWatch installation to produce a GTFS-realtime feed.
* [Transloc API to GTFS-realtime](https://github.com/jonathonwpowell/transloc-to-gtfs-real-time) ⭐ 4 | 🐛 22 | 🌐 JavaScript | 📅 2023-01-05 - A Node.js based tool to convert the Transloc API to GTFS-realtime.
* [Syncromatics API to GTFS-realtime](https://github.com/CUTR-at-USF/bullrunner-gtfs-realtime-generator) ⚠️ Archived - A Java-based command-line utility to convert from the [Syncromatics API](http://www.syncromatics.com/) format to GTFS-realtime TripUpdates and VehiclePositons.
* [SoundTransit to GTFS-realtime](https://github.com/bdferris/onebusaway-sound-transit-realtime) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2012-02-13 - Convert text file feed from [Sound Transit](http://www.soundtransit.org/) to GTFS-realtime
* [SEPTA API to GTFS-realtime](https://github.com/kurtraschke/septa-gtfsrealtime) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2014-06-22 - Java-based tool to convert [SEPTA's](http://www.septa.org/) [real-time bus and rail data](http://www3.septa.org/hackathon/) to GTFS-realtime
* [Detroit DOT to GTFS-realtime](https://github.com/prashtx/ddot-avl) ⭐ 2 | 🐛 1 | 🌐 C# | 📅 2019-02-07 - Extract real-time info from [DDOT's](http://www.detroitmi.gov/How-Do-I/Locate-Transportation/Bus-Schedules) TransitMaster installation (database) and convert to GTFS-realtime
* [KV6,15,17, and ARNU to GTFS-realtime](https://github.com/bliksemlabs/bliksemintegration-realtime) ⭐ 1 | 🐛 2 | 🌐 Java | 📅 2014-11-06 - Java-based tool to process incoming KV6,15,17 and ARNU and match them to static transit data present in a RID integration database. It then proceeds to export this data as ARNU RITinfo, GTFS(realtime) and KV78turbo
* [GTFS-realtime VehiclePositions to GTFS-realtime TripUpdates (TransitClock)](https://thetransitclock.github.io/) - Java application that can consume raw vehicle positions and generate prediction times in formats such as GTFS-realtime.  Formerly known as "Transitime".

#### GTFS Realtime Utilities

* [gtfs-rt-inspector](https://public-transport.github.io/gtfs-rt-inspector/) – Web app to inspect & analyze any (CORS-enabled) GTFS Realtime feed. Open-source on [GitHub](https://github.com/public-transport/gtfs-rt-inspector) ⭐ 51 | 🐛 11 | 🌐 JavaScript | 📅 2026-01-24.
* [bus\_kalman](https://github.com/cmoscardi/bus_kalman) ⭐ 31 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2017-09-21 - A Kalman Filter used to interpolate bus travel times using NYC MTA real-time data.
* [Concentrate](https://github.com/mbta/concentrate) ⭐ 28 | 🐛 15 | 🌐 Elixir | 📅 2026-02-06 - Combines realtime transit information from multiple sources into single output files. Maintained by [
  Massachusetts Bay Transportation Authority (MBTA)](https://github.com/mbta).
* [gtfs-rt-dump](https://github.com/kurtraschke/gtfs-rt-dump) ⭐ 25 | 🐛 5 | 🌐 Kotlin | 📅 2025-01-28 - Converts protocol buffer format to plain text for easy viewing of a GTFS-realtime feed in plain text (for debugging purposes)
* [print-gtfs-rt-cli](https://github.com/derhuerst/print-gtfs-rt-cli) ⭐ 24 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-24 – Javascript tool to read a GTFS Realtime feed from stdin, print human-readable or as JSON.
* [Transit Network Model](https://github.com/tmelliott/TransitNetworkModel) ⭐ 14 | 🐛 5 | 🌐 C++ | 📅 2018-08-01 - A tool to generate predictions using GTFS-realtime VehiclePositions, a particle filter, and a Kalman Filter.
* [GTFS-realtime Printer](https://github.com/laidig/gtfs-rt-printer) ⭐ 9 | 🐛 0 | 🌐 Java | 📅 2018-06-18 - Java-based utility to print out information from a GTFS-realtime file or URL.
* [GTFS Data Pipeline for TfNSW Bus Datasets](https://github.com/teckkean/GTFS-Data-Pipeline-TfNSW-Bus) ⭐ 8 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-10-31 - A data pipeline developed for the TfNSW's GTFS Static and Realtime datasets. The datasets generated using the pipeline have been used to validate the performance of TfNSW's Transit Signal Priority Request via Public Transport Information and Priority System (PTIPS).
* [gtfs-rt-admin](https://github.com/conveyal/gtfs-rt-admin) ⭐ 7 | 🐛 1 | 🌐 JavaScript | 📅 2014-07-09 - An admin tool for managing GTFS-RT service alerts (JavaScript and Java).
* [transit-feed-quality-calculator](https://github.com/CUTR-at-USF/transit-feed-quality-calculator) ⚠️ Archived - A Java project that uses the [gtfs-realtime-validator](https://github.com/CUTR-at-USF/gtfs-realtime-validator) ⚠️ Archived to assess the quality of a large number of transit feeds, fetching the feed URLs from a global directory ([TransitFeeds.com/OpenMobilityData.org](https://openmobilitydata.org/)).
* [gtfs-rt-differential-to-full-dataset](https://github.com/derhuerst/gtfs-rt-differential-to-full-dataset) ⭐ 5 | 🐛 5 | 🌐 JavaScript | 📅 2025-10-23 – Javascript tool to transform a continuous GTFS Realtime stream of `DIFFERENTIAL` incrementality data into a `FULL_DATASET` dump.
* [manual-gtfsrt](https://github.com/pailakka/manual-gtfsrt) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2017-04-28 - A Go-based tool that serves a GTFS-RT feed created from editable JSON.
* [gtfs-realtime-test-service](https://github.com/CUTR-at-USF/gtfs-realtime-test-service) ⚠️ Archived - A tool for mocking GTFS-realtime feed content (e.g., for use in testing a GTFS-realtime consuming application).
* [GTFS-realtime Munin Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-munin-plugin) ⚠️ Archived - Provides a [Munin](http://munin-monitoring.org/) plugin for logging information about a GTFS-realtime feed.
* [GTFS-realtime Nagio Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-nagios-plugin) ⚠️ Archived - Provides a [Nagios](https://www.nagios.org/) plugin for monitoring a GTFS-realtime feed
* [transitcast](https://github.com/OpenTransitTools/transitcast) - Uses GTFS and GTFS-RT vehicle position feed generating an estimated transition time it takes for each vehicle to move from scheduled stop to scheduled stop recording these an "observed\_stop\_time" table. These records can later be used to train a machine learning model to make vehicle travel predictions. Created by TriMet as part of [an FTA IMI project](https://trimet.org/imi/program.htm).
* [GTFS Realtime Display](https://codeberg.org/dancingCycle/gtfs-rt-display) - Analyse, monitor and maintain GTFS Realtime data. [Example instances](https://www.swingbe.de/activity/gtfs-rt-display/)
* [GTFS Realtime Prediction Accuracy metrics](https://docs.google.com/document/d/1-AOtPaEViMcY6B5uTAYj7oVkwry3LfAQJg3ihSRTVoU/edit#heading=h.j27shba7rlk6) - Useful Performance Metrics for GTFS-Realtime.

### SIRI

* [SIRI API](https://github.com/OneBusAway/onebusaway/wiki/SIRI-Resources) ⭐ 362 | 🐛 10 | 📅 2024-06-05 - Java classes generated from the v1.0 and v1.3 [SIRI](https://www.siri.org.uk/) schemas.
* [SIRI REST Client](https://github.com/CUTR-at-USF/SiriRestClient/wiki) ⚠️ Archived - An open-source Android library for interacting with the RESTful SIRI interface for real-time transit data, such as that currently being used by the [MTA Bus Time API](http://bustime.mta.info/wiki/Developers/SIRIIntro).
* [Edwig](https://github.com/af83/edwig) ⭐ 20 | 🐛 1 | 🌐 Go | 📅 2025-12-17 - A golang server for real-time public transport data exchange, using the SIRI protocol.
* [SIRI to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) ⭐ 12 | 🐛 6 | 🌐 Java | 📅 2022-04-11 - A Java-based command-line utility to convert from the [SIRI format](https://www.siri.org.uk/) to GTFS-realtime.
* [SIRI 2.0 API](https://github.com/laidig/siri-20-java) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2017-11-30 - Java classes generated from the v2.0 [SIRI](https://www.siri.org.uk/) schemas.
* [SIRI 1.3 POJOs (Android-compatible)](https://github.com/CUTR-at-USF/onebusaway-siri-api-v13-pojos/wiki) ⚠️ Archived - Android-compatible Plain Old Java Objects (POJOSs) used for data binding (deserliazing XML/JSON) responses for SIRI v1.3 APIs.  Used by the [SIRI REST Client](https://github.com/CUTR-at-USF/SiriRestClient/wiki) ⚠️ Archived.
* [King County Metro Legacy AVL to SIRI](https://github.com/bdferris/onebusaway-king-county-metro/tree/master/onebusaway-king-county-metro-legacy-avl-to-siri) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2012-09-30 - Java-based tool to convert [King County Metro's](http://metro.kingcounty.gov/) Legacy AVL format to SIRI.
* [pysiri2validator](https://github.com/laidig/pysiri2validator) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2022-12-09 - Simple validator for SIRI 2.0 written in Python 3.
* [SIRI 2.0 Autodoc](https://laidig.github.io/siri-20-java/doc/) - Automatically generated documentation from the (incredibly well) annotated SIRI 2.0 Schema Definition.
* [BISON](https://bison.dova.nu/standaarden/nederlands-siri-profiel) - Netherlands implementation of SIRI.

### Other multimodal data formats

#### Widely adopted

* [MDS](https://github.com/openmobilityfoundation/mobility-data-specification) ⭐ 727 | 🐛 23 | 📅 2026-02-06 - Mobility Data Specification: A format to implement realtime data sharing, measurement and regulation for municipalities and mobility as a service providers. It is meant to ensure that governments have the ability to enforce, evaluate and manage providers. Maintained by the [Open Mobility Foundation](https://www.openmobilityfoundation.org/).
* [TOMP](https://github.com/TOMP-WG/TOMP-API) ⭐ 107 | 🐛 43 | 🌐 Python | 📅 2026-01-24 - Transport Operator Mobility-as-a-service Provider API: API standard for use by transport operators and mobility-as-a-service providers for operator discovery, trip planning, end user interaction, booking, and payment.
* [GBFS](https://gbfs.org/) - General Bikeshare Feed Specification: open data standard for real-time information about bikeshare, scootershare, mopedshare, and carshare.
  * [gbfs R package](https://github.com/simonpcouch/gbfs) ⭐ 38 | 🐛 0 | 🌐 R | 📅 2025-01-13 - Functions to interface with GBFS feeds in R, allowing users to save and accumulate tidy .rds datasets for specified cities/bikeshare programs.
* [APDS](https://www.allianceforparkingdatastandards.org/) - Alliance for Parking Data Standards: formed by the [International Parking Institute (IPI)](https://www.parking.org/), the [British Parking Association (BPA)](http://www.britishparking.co.uk/), and the [European Parking Association (EPA)](http://www.europeanparking.eu/). APDS is a not-for-profit organization with the mission to develop, promote, manage, and maintain a uniform global standard that will allow organizations to share parking data across platforms worldwide.
* [DATEX](https://datex2.eu/) - EU data standard for road traffic and travel information.
* [NeTex](http://netex-cen.eu/) - A general purpose XML format designed for the exchange of complex static transport data among distributed systems managed by the [CEN standards process](https://www.cencenelec.eu/european-standardization/european-standards/).
* [TODS](https://ods.calitp.org/) - Transit Operational Data Standard: standard format for representing transit schedules used by drivers, dispatchers, and planners to carry out transit operations.

#### Pilot or development stage

* [GMNS](https://github.com/zephyr-data-specs/GMNS) ⭐ 125 | 🐛 20 | 🌐 Jupyter Notebook | 📅 2026-02-04 - General Modeling Network Specification: A format for sharing routable road network files designed to be used in multi-modal static and dynamic transportation planning and operations models. Volpe/FHWA partnership with Zephyr Foundation.
* [OSDM](https://github.com/UnionInternationalCheminsdeFer/OSDM) ⭐ 84 | 🐛 29 | 🌐 Shell | 📅 2026-02-06 - Open Sales and Distribution Model: Aims to substantially simplify the booking process for customers of rail trips and to lower complexity and distribution costs for distributors and railway carriers. Contains a specification of an offline model and on-line API. Maintained by the [International Union of Railways (UIC)](https://github.com/UnionInternationalCheminsdeFer).
* [CurbLR](https://github.com/curblr/curblr-spec) ⭐ 74 | 🐛 3 | 🌐 JavaScript | 📅 2024-07-16 - A specification for curb regulations.
* [OMX: The Open Matrix data file format](https://github.com/osPlanning/omx) ⭐ 54 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2025-12-16 - A structured collection of two-dimensional array objects and associated metadata, for possible use in the transportation modeling industry.
* [GTFS-ride](https://github.com/ODOT-PTS/GTFS-ride) ⭐ 52 | 🐛 9 | 📅 2021-12-30 - An open, fixed-route transit ridership data standard developed through a partnership between the Oregon Department of Transportation and Oregon State University.
* [TIDES](https://github.com/TIDES-transit/TIDES) ⭐ 51 | 🐛 48 | 🌐 Python | 📅 2026-01-08 -  Transit ITS Data Exchange Specification (TIDES) is a proposed effort to create standard data structures, APIs, and data management tools for historical transit ITS data including AVL, APC and AFC Data.
* [OJP](https://github.com/VDVde/OJP) ⭐ 34 | 🐛 28 | 🌐 XSLT | 📅 2025-08-27 - Open Journey Planner.
* [GTFS-plus](https://github.com/osplanning-data-standards/GTFS-PLUS) ⭐ 22 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2018-06-12 - A GTFS-based transit network format for *vehicle and capacity data* suitable for dynamic transit modeling developed by Puget Sound Regional Council, UrbanLabs LLC, LMZ LLC, and San Francisco County Transportation Authority.
* [shared-row](https://github.com/d-wasserman/shared-row) ⭐ 18 | 🐛 3 | 📅 2021-12-24 - A specification for right-of-way (ROW) for a SharedStreets Reference.
* [MaaS API](https://github.com/maasglobal/maas-tsp-api/blob/master/specs/Booking.md) ⭐ 17 | 🐛 4 | 🌐 JavaScript | 📅 2020-04-04 - A set of open documents and test suite that defines a MaaS-compatible API.
* [MTLFS](https://github.com/vta/Managed-and-Tolled-Lanes-Feed-Specification) ⭐ 10 | 🐛 17 | 📅 2018-02-09 - Managed and Tolled Lanes Feed Specification: Proposal for a schema that comprise the Managed and Tolled Lanes Tolling Feed Specification (MTLFS) and defines the fields used in all of those files developed by [Santa Clara Valley Transportation Authority](http://www.vta.org/).
* [Prism](https://github.com/Jungle-Bus/prism) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-01-29 - Prism is a tool to extract public transport data from OpenStreetMap.
* [Open Street Map Public Transport Parser](https://github.com/cualbondi/osmptparser) ⭐ 8 | 🐛 1 | 🌐 Rust | 📅 2025-06-30 - Open Street Map Public Transport Parser
* [GTFS-stat](https://github.com/osplanning-data-standards/GTFS-STAT) ⭐ 4 | 🐛 3 | 📅 2018-04-12 - An extension to a GTFS transit network with additional files that contain performance data developed by UrbanLabs LLC and San Francisco County Transportation Authority.
* [Dyno-Demand](https://github.com/osplanning-data-standards/dyno-demand) ⭐ 3 | 🐛 5 | 📅 2018-07-02 - A GTFS-based travel demand data format focusing on individual passenger *demand* suitable for dynamic network modeling developed by San Francisco County Transportation Authority, LMZ LLC, and UrbanLabs LLC.
* [Dyno-Path](https://github.com/osplanning-data-standards/dyno-path) ⭐ 2 | 🐛 2 | 📅 2017-04-06 - (Under development - see [this post](https://github.com/osplanning-data-standards/GTFS-PLUS/pull/52#issuecomment-331231000) ⭐ 22 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2018-06-12) Data for individual passenger *trajectories*.
* [IXSI](https://github.com/RWTH-i5-IDSG/ixsi) ⭐ 2 | 🐛 1 | 🌐 Makefile | 📅 2018-05-29 -  interface for exchanging information between a travel information system and a sharing system (carshare, bikeshare).
* [GTNS](https://zephyrtransport.org/trb17projects/7-general-travel-network-specification/) - General Travel Network Specification: A planned data specification for sharing travel demand model networks.
* [NCHRP 08-119 Developing Data Standards and Guidance for Transportation Planning and Traffic Operations - Phase 1 (Anticipated)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4543) - The objective of this research is to develop standards and/or guidance to be used and adopted by the transportation community in collecting, managing, and sharing static and real-time data for transportation planning and operations.
* [SAE Shared and Digital Mobility Committee](http://articles.sae.org/15799/) - Appears to be working on a data standard for car share and transportation network companies (TNCs) / rideshare.
* [TCRP G-16 Development of Transactional Data Specifications for Demand-Responsive Transportation (In progress)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4120) - The objective of this research is to develop technical specifications for transactional data for entities involved in the provision of demand-responsive transportation.  Expected completion date is late 2018.
* [OpenStop](https://wiki.openstreetmap.org/wiki/OpenStop) - OpenStop is a free app to add information about barriers and other accessibility properties of public transport stops to OpenStreetMap.
* [JOSM Plugins - PT Assistant](https://wiki.openstreetmap.org/wiki/JOSM/Plugins/PT_Assistant) - The plugin validates public transport routes against a set of criteria and, where possible, suggests ways to fix them.
* [JOSM Validator Rules](https://josm.openstreetmap.de/wiki/Rules) - The JOSM validator (Tag checker) can be customized with different rules based on MapCSS.
* [OSM Relatify](https://wiki.openstreetmap.org/wiki/Relatify) - OSM Relatify is a tool that simplifies the process of maintaining public transport relations.
* [OpenStreetMap Route Editor](https://osm-simple-route-editor.kyle.kiwi/) - A tool for efficiently editing Route Relations in OpenStreetMap - OSM
* [Sketch Line](http://www.overpass-api.de/public_transport.html) - A tool to create transport diagram out of OSM data.

### Software for Creating APIs

Software that you can set up to provide an API to transit and multimodal data.

* [GraphHopper Routing Engine](https://github.com/graphhopper/graphhopper/#public-transit) ⭐ 6,259 | 🐛 255 | 🌐 Java | 📅 2026-02-05 Open source routing engine for OpenStreetMap. Use it as Java library or server.
* [pyBikes](https://github.com/eskerda/pybikes) ⭐ 595 | 🐛 30 | 🌐 Python | 📅 2026-02-06 - Software powering [CityBikes](http://api.citybik.es) for worldwide bikeshare system info
* [MOTIS](https://github.com/motis-project/motis) ⭐ 456 | 🐛 86 | 🌐 C++ | 📅 2026-02-07 - Multi Objective Travel Information System, written in C++ and Java. Can consume schedule timetables in the GTFS or HAFAS format as well as real time information in the GTFS-RT (and RISML, a propriatary format at Deutsche Bahn) as input data. For pedestrian routing (handled by Per Pedes Routing) and car routing (handled by OSRM) OpenStreetMap data is used.
* [Navitia](https://github.com/hove-io/navitia) ⭐ 449 | 🐛 47 | 🌐 Python | 📅 2026-02-06 is the opensource engine behind the [Navitia.io](http://www.navitia.io/) live API.
* [OneBusAway](http://onebusaway.org/) - A Java app that consumes GTFS and GTFS-Realtime (along with [other formats](https://github.com/OneBusAway/onebusaway-application-modules/wiki/Real-Time-Data-Configuration-Guide) ⭐ 235 | 🐛 77 | 🌐 Java | 📅 2026-02-08) and turns them into an easy to use REST API.
* [gtfs-server](https://github.com/denysvitali/gtfs-server) ⭐ 38 | 🐛 8 | 🌐 Rust | 📅 2022-12-07 - A web server, written in Rust that uses PostGIS as a backend to serve GTFS data via a HTTP endpoint
* [hafas-rest-api](https://github.com/public-transport/hafas-rest-api) ⭐ 26 | 🐛 7 | 🌐 JavaScript | 📅 2024-04-22 – Expose a [HAFAS](https://de.wikipedia.org/wiki/HAFAS) endpoint as a REST API.
* [Iran Railway-Trains](https://github.com/keyone2693/IRTrainDotNet) ⭐ 16 | 🐛 0 | 🌐 C# | 📅 2022-09-14 - Iran Railway-Trains (Raja-Fadak-Safir) all in one package for DotNet (Api-WebService)
* [Simple Transit Api](https://github.com/ioTransit/simple-transit-api) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2024-05-21 - A simple way to get started with a GTFS api in Golang.
* [Linked Connections](http://linkedconnections.org/) - An open-source, scalable intermodal route planning engine, which allows clients to execute the route planning algorithm (as opposed to the server). Uses GTFS data.
* [Mobroute](http://sr.ht/~mil/mobroute) - Mobroute is a general purpose FOSS public transportation router (e.g. trip planner) Go library and CLI that works by directly ingesting timetable (GTFS) data from transit agencies themselves (sourced from the [Mobility Database](https://database.mobilitydata.org/)). It can be used to quickly run & test routing requests based on GTFS data on your device (via its CLI) or it can be embedded as a library to add GTFS routing to existing navigation apps.
* [OpenTripPlanner](http://www.opentripplanner.org/) - An open source platform for multi-modal and multi-agency journey planning, as well as returning information about a multi-modal graph (using data sources such as GTFS and [OpenStreetMap](http://www.openstreetmap.org/)).
* [TransitClock](https://thetransitclock.github.io/) - Java application that can consume raw vehicle positions and generate prediction times in formats such as GTFS-realtime.  Formerly known as "Transitime".
* [Transitous](https://transitous.org) - Community-run free and open public transport routing service.

## Sharing Data

Places to access collections of GTFS and other transit and multimodal data.

#### 3rd party GTFS URL directories

* [The Mobility Database](https://mobilitydatabase.org/) - JSON and CSV files [on GitHub](https://github.com/MobilityData/mobility-database-catalogs) ⭐ 323 | 🐛 186 | 🌐 Python | 📅 2026-02-05 that is a repository of 2000+ mobility datasets across the world. Contains contents of OpenMobilityData/TransitFeeds.com.
* [Transitland](https://transit.land/) - Community editable list of many transit agency GTFS datasets. Also provides an API to access the data as JSON/GeoJSON and a playground to try out the data.
* [TransitData.io](https://transitdata.io/) - A list of GTFS data in parts of Latin America. Must contact website maintainers directly to access feeds, as they're not publicly available.
* [~~OpenMobilityData~~ (Deprecated)](https://openmobilitydata.org/) - List of GTFS and [GTFS-RT](https://openmobilitydata.org/search?q=gtfsrt) feeds. [Archives and validates](https://openmobilitydata.org/p/capital-metro/24) the GTFS feeds and allows you to preview both [GTFS](https://openmobilitydata.org/p/capital-metro/24/latest) and [GTFS-RT](https://openmobilitydata.org/p/capital-metro/495) through the browser. Formerly TransitFeeds.com. [MobilityData announced](https://database.mobilitydata.org/#h.u71vp6xgkckf) it is end-of-life as of early 2022 with a shutdown date to be determined.

#### Transit agency data archives

* [CapMetrics](https://github.com/scascketta/CapMetrics) ⚠️ Archived - Historical vehicle locations for Austin's transit agency (CapMetro). Data is collected by [capmetricsd](https://github.com/scascketta/capmetricsd) ⚠️ Archived, a Go daemon.
* [Bus Observatory API](https://api.busobservatory.org/) - Public archive of real-time data on vehicle movements and status, collected from transit systems around the world.

#### National government datasets

* [National Transit Database (USA)](https://www.transit.dot.gov/ntd) - Information and statistics on the transit systems of the United States, run by the Federal Transit Administration.
* [transport.data.gouv (France)](https://transport.data.gouv.fr/) - Data platform for the French transport ecosystem.
* [European long-distance transport operators (EU) *(Unofficial)*](https://github.com/public-transport/european-transport-operators) ⚠️ Archived - Unofficial list of available API endpoints, GTFS feeds and client libraries

#### Proprietary (non-standard) vendor APIs

* [CityBikes](http://api.citybik.es) - REST API for aggregated bikeshare data from around the world. Powered by [pyBikes](https://github.com/eskerda/pybikes) ⭐ 595 | 🐛 30 | 🌐 Python | 📅 2026-02-06.
* [Navitia.io](http://www.navitia.io/) - REST API for journey planning, stop schedules, isochrones and lot more on US and EU. [Navitia](https://github.com/hove-io/navitia) ⭐ 449 | 🐛 47 | 🌐 Python | 📅 2026-02-06 is the opensource engine behind the live API.
* [Transport API](https://www.transportapi.com/) - REST API for aggregated transit data for the United Kingdom.  Fee-based access.
* [NextBus API](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) - REST API for real-time vehicle, route, stop, and arrival data for agencies that have puchased NextBus's hardware and/or software.
* [HAFAS](https://de.wikipedia.org/wiki/HAFAS) – Propriety public transport management software by [HaCon](https://www.hacon.de) ([list of endpoints](https://gist.github.com/derhuerst/2b7ed83bfa5f115125a5))
* [Citymapper API](https://docs.external.citymapper.com/api/) - REST API for transit journey planning, realtime transit data and walk, cycle, scooter travel times.
* [TripGo API](https://developer.tripgo.com) - REST API for multi-modal journey planning and real-time data by [SkedGo](https://skedgo.com).

#### Crowdsourced transit data

* [Citylines.co](https://www.citylines.co) - A collaborative platform for mapping transit systems, with an emphasis on their historical evolution. The data can be downloaded as GeoJSON or CSV from [citylines.co/data](https://www.citylines.co/data).
* [OpenStreetMap (OSM)](https://www.openstreetmap.org) - The collaborative platform for mapping the world, including transport, transit, and routing data.
* [GTFS-Hub](https://github.com/mfdz/gtfs-hub) ⭐ 31 | 🐛 8 | 🌐 Makefile | 📅 2026-01-31 - Community tested, probably quality/content enhanced, partially merged or filtered GTFS-feeds of (currently German) transport agencies. Maintained by [MITFAHR|DE|ZENTRALE](https://github.com/mfdz).

#### Sample GTFS and GTFS Realtime datasets used for software testing

* [OpenTripPlanner unit tests](https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/src/test) ⭐ 2,540 | 🐛 147 | 🌐 Java | 📅 2026-02-07 - Some [GTFS datasets](https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/src/test/resources/gtfs) ⭐ 2,540 | 🐛 147 | 🌐 Java | 📅 2026-02-07 are defined for the unit tests ([GtfsTest](https://github.com/opentripplanner/OpenTripPlanner/blob/dev-2.x/src/test/java/org/opentripplanner/GtfsTest.java) ⭐ 2,540 | 🐛 147 | 🌐 Java | 📅 2026-02-07 and [mmri folder](https://github.com/opentripplanner/OpenTripPlanner/tree/dev-2.x/src/test/java/org/opentripplanner/mmri) ⭐ 2,540 | 🐛 147 | 🌐 Java | 📅 2026-02-07).
* [transitfeed unit tests](https://github.com/google/transitfeed/tree/master/tests/data) ⚠️ Archived - Test data created for the original Google [Python GTFS validator](https://github.com/google/transitfeed/wiki/FeedValidator) ⚠️ Archived.
* [gtfs-realtime-validator unit tests](https://github.com/MobilityData/gtfs-realtime-validator/tree/master/gtfs-realtime-validator-lib/src/test/) ⭐ 54 | 🐛 128 | 🌐 Java | 📅 2024-11-26 - Some [GTFS datasets (zip files)](https://github.com/MobilityData/gtfs-realtime-validator/tree/master/gtfs-realtime-validator-lib/src/test/resources) ⭐ 54 | 🐛 128 | 🌐 Java | 📅 2024-11-26 are included and a large number of GTFS RT messages are defined [programmatically in Java](https://github.com/MobilityData/gtfs-realtime-validator/tree/master/gtfs-realtime-validator-lib/src/test/java/edu/usf/cutr/gtfsrtvalidator/lib/test/rules) ⭐ 54 | 🐛 128 | 🌐 Java | 📅 2024-11-26 via the gtfs-realtime-bindings library.
* [Transitland GTFS and GTFS Realtime unit tests](https://github.com/interline-io/transitland-lib) ⭐ 48 | 🐛 19 | 🌐 Go | 📅 2026-02-05 - For testing the [transitland-lib](https://github.com/interline-io/transitland-lib) ⭐ 48 | 🐛 19 | 🌐 Go | 📅 2026-02-05 library that handles GTFS and GTFS Realtime parsing and validation for Transitland:
  * [GTFS - "bad entities" at the single row level](https://github.com/interline-io/transitland-lib/tree/master/test/data/bad-entities) ⭐ 48 | 🐛 19 | 🌐 Go | 📅 2026-02-05
  * [GTFS - validation errors that that involve entities in one or more files](https://github.com/interline-io/transitland-lib/tree/master/test/data/validator/errors) ⭐ 48 | 🐛 19 | 🌐 Go | 📅 2026-02-05
  * [GTFS - best practices](https://github.com/interline-io/transitland-lib/tree/master/test/data/validator/best-practices) ⭐ 48 | 🐛 19 | 🌐 Go | 📅 2026-02-05
* [sample-gtfs-feed](https://github.com/public-transport/sample-gtfs-feed) ⭐ 13 | 🐛 3 | 🌐 JavaScript | 📅 2024-06-25 - An imaginary GTFS data set used for testing.

## Using Data

### Consumer Apps

Apps people use when taking transit.

#### Web Apps (open source)

* [Transitive.js](https://github.com/conveyal/transitive.js) ⭐ 695 | 🐛 17 | 🌐 JavaScript | 📅 2022-06-10 - Creates a customizable web map layer of transit routes using Leaflet or D3.
* [Google I/O Transport Tracker](https://github.com/googlemaps/transport-tracker) ⚠️ Archived - Shows shuttle arrival times for Google I/O conference, based on the open-source [transport-tracker project](https://github.com/googlemaps/transport-tracker) ⚠️ Archived.  Note: To implement this yourself, you need a [Google Maps APIs Premium Plan license](https://developers.google.com/maps/pricing-and-plans/).
* [Transit-Map](https://github.com/vasile/transit-map) ⭐ 369 | 🐛 10 | 🌐 JavaScript | 📅 2019-03-12 - Web app that animates vehicles (markers) on a map using the public transport timetables to interpolate their positions along the routes (polylines).
* [Bustime](https://busti.me) - Public transport real-time monitoring with WebSocket updates. Open-source [on GitHub](https://github.com/norn/bustime) ⭐ 96 | 🐛 0 | 🌐 JavaScript | 📅 2024-11-22.
* [OTP-UI React Component Library](https://github.com/opentripplanner/otp-ui) ⭐ 68 | 🐛 87 | 🌐 TypeScript | 📅 2026-02-06 - React Javascript component library, which can be used to build trip planner webapps. See the [Storybook](http://www.opentripplanner.org/otp-ui) for a demo.
* [OpenTripPlanner.js](https://github.com/conveyal/otp.js) ⭐ 19 | 🐛 2 | 🌐 JavaScript | 📅 2020-01-14 - A Javascript-based client for OpenTripPlanner (no longer under development)
* [HRT BUS Web app](https://github.com/Code4HR/hrt-bus-api) ⚠️ Archived - HRT Bus API publishes real time bus data from Hampton Roads Transit through an application programming interface for developers to make apps from it.
* [OpenTripPlanner Client GWT](https://github.com/mecatran/OpenTripPlanner-client-gwt) ⭐ 12 | 🐛 3 | 🌐 Java | 📅 2022-03-14 - A Google Web Toolkit-based web interface for OpenTripPlanner
* [MBTA tile-server](https://github.com/mbta/tile-server) ⭐ 9 | 🐛 0 | 🌐 CartoCSS | 📅 2024-07-22 - Scripts to create a Docker container that encapsulates all the elements necessary to develop map tiles for use on MBTA.com
* [Cadê Meu Busão](https://tarifazerobh.org/cade-meu-busao/) - Realtime tracking transit buses from Belo Horizonte, Brazil. Open-source on [GitHub](https://github.com/tarifazero/monitoramento) ⭐ 9 | 🐛 0 | 🌐 PHP | 📅 2022-06-20.
* [Tiramisu Transit](https://github.com/CMU-RERC-APT/tiramisu3-pr) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2022-01-26 - An adaptive mobile transit app that shows real-time bus arrival information developed and deployed by Carnegie Mellon University. No longer maintained.
* [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) ⚠️ Archived - A Java-based web application for producing GTFS-realtime Service Alerts.
* [Catenary Maps](https://catenarymaps.org) - Realtime and Schedule global public transport map and navigation software, written in Rust and Svelte.
* [Instabus](http://instabus.org) - Realtime map of Austin's (CapMetro) public transit. Has no server/backend dependency at all and runs completely on GitHub pages.
* [1-Click](origin/\[http:/camsys.software/products/1-click]\(https:/github.com/camsys/oneclick\)) - A virtual “trip aggregator” that assembles information on a wide variety of available modes: public transit, private, rail, rideshare, carpool, volunteer, paratransit, and walking and biking.
* [Transit Tracker](https://transittracker.ca/#/) - Realtime vehicle position for Greater Montreal & Toronto, Canada
* [GTFS Builder](http://nationalrtap.org/Web-Apps/GTFS-Builder) - A free web-based application to help you create GTFS files. Maintained by the National Rural Transit Assistance Program (RTAP).
* Dede - An independent and universal passenger information system (PIS) mapping realtime movement. A message feed with Vehicle Position entities in the GTFS-Realtime format or the [Dede app](https://github.com/dancesWithCycles/dede-android) can be used as data source.
* [OsmAnd](https://wiki.openstreetmap.org/wiki/OsmAnd) - OsmAnd is a GPS Navigation and map application that runs on many Android and iOS smartphones and tablets, featuring optional offline maps and turn by...

#### Web Apps (closed source)

* [TransitScreen](http://transitscreen.com/) - Custom realtime displays of all local transportation choices
* [Citylines.co](https://www.citylines.co) - A collaborative platform for mapping transit systems, with an emphasis on their historical evolution.
* [Bikeshare Map](http://bikes.oobrien.com/) - Status of all worldwide bikeshare stations
* [Bongo](http://ebongo.org) - Real-time Transit Tracking for Iowa City, Coralville and the University of Iowa. Combines three disparate transit systems into one UI.
* [CityMapper Webapp](https://citymapper.com/nyc) - Really polished webapp with trip planner and route status for over 30 of cities.
* [TransSee](https://www.transsee.ca/) - Real-time transit predictions based on actual travel times, vehicle locations, schedules and maps. Premium gives you access to a detailed history of schedules, vehicle locations, stop arrivals, schedule adherance, charts and graphs. For an additional fee custom queries can be run on this data.
* [YourStop](http://yourstop.info) - Mobile friendly web app which consumes GTFS feeds and displays both live and scheduled trips for stops. Launched with MBTA, YRT/Viva and Maryland MTA.
* [DC MetroHero](https://dcmetrohero.net) - Realtime vehicle position and arrivals and departure information for the Washington, D.C. region's WMATA Metrorail and Metrobus systems. WebApp, Android, and iOS apps avaliable.

#### Native Apps (open source)

* [Transportr](https://github.com/grote/Transportr) ⭐ 1,142 | 🐛 108 | 🌐 Kotlin | 📅 2025-12-03 An Android app that uses [public-transport-enabler](https://github.com/schildbach/public-transport-enabler) ⭐ 429 | 🐛 188 | 🌐 Java | 📅 2026-02-02 in order to connect to many different transport networks worldwide.
* OneBusAway Apps - [Android](https://play.google.com/store/apps/details?id=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android) ⭐ 533 | 🐛 168 | 🌐 Java | 📅 2026-01-31, [Fire Phone](http://www.amazon.com/gp/mas/dl/android?p=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android) ⭐ 533 | 🐛 168 | 🌐 Java | 📅 2026-01-31, [iOS](https://itunes.apple.com/us/app/onebusaway/id329380089)  [*(source code)*](https://github.com/OneBusAway/onebusaway-ios) ⭐ 138 | 🐛 88 | 🌐 Swift | 📅 2026-02-01, [Windows Phone](https://www.microsoft.com/en-us/store/apps/onebusaway/9nblggh0cbd9) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows-phone) ⚠️ Archived, [Google Glass GDK](https://github.com/OneBusAway/onebusaway-android/pull/219) ⭐ 533 | 🐛 168 | 🌐 Java | 📅 2026-01-31 [*(source code)*](https://github.com/OneBusAway/onebusaway-android/pull/219) ⭐ 533 | 🐛 168 | 🌐 Java | 📅 2026-01-31, [Alexa skill](https://www.amazon.com/OneBusAway/dp/B01ELVUYCW/) [*(source code)*](https://github.com/OneBusAway/onebusaway-alexa) ⭐ 52 | 🐛 17 | 🌐 Java | 📅 2022-12-16
* [OpenTripPlanner Android](https://github.com/CUTR-at-USF/OpenTripPlanner-for-Android/wiki) ⚠️ Archived - An Android app for [OpenTripPlanner](http://www.opentripplanner.org/)
* [OpenTripPlanner iOS](https://github.com/opentripplanner/OpenTripPlanner-iOS) ⚠️ Archived - An iOS app for [OpenTripPlanner](http://www.opentripplanner.org/)
* [KDE Itinerary](https://apps.kde.org/itinerary/) - App (Desktop and Android) for planning trips. It can find public transport routes, store them offline, add events to your trips, see the floor plan of train stations, and much more. [Souce Code](https://invent.kde.org/pim/itinerary), [GitHub](https://github.com/KDE/itinerary) ⭐ 56 | 🐛 0 | 🌐 C++ | 📅 2026-02-07
* [Trufi App](https://github.com/trufi-association/trufi-app) ⭐ 13 | 🐛 2 | 🌐 Dart | 📅 2025-07-31 - A cross-platform Flutter app that uses [OpenTripPlanner](http://www.opentripplanner.org/)
* [MACS Transit Android App](https://github.com/yeSpud/MACSTransitApp) ⭐ 9 | 🐛 7 | 🌐 Kotlin | 📅 2025-12-03 - A bus tracker app for Android devices for the MACS Transit system in Fairbanks, Alaska. Uses RouteMatch APIs.
* [Tiramisu Transit](https://github.com/CMU-RERC-APT/tiramisu3-pr#mobile-app-client) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2022-01-26 - An adaptive mobile transit app that shows real-time bus arrival information developed and deployed by Carnegie Mellon University. Written using Ionic framework. No longer maintained.
* [opentripplanner-client-library](https://github.com/CUTR-at-USF/opentripplanner-client-library) ⚠️ Archived - A Kotlin Multiplatform library for making API requests and parsing responses from an OpenTripPlanner v2 server for trip plans, bike rental info, and server metadata for Android, iOS, and web.
* [Next Train - Connecticut](https://github.com/data-creative/NextTrainCT) ⭐ 1 | 🐛 6 | 🌐 JavaScript | 📅 2019-07-11 - A React-native mobile app for searching train schedules published by the Shore Line East transit agency in Connecticut. Relies on a deployment of the [Next Train API](https://github.com/data-creative/next-train-api) ⭐ 4 | 🐛 1 | 🌐 Ruby | 📅 2018-12-29.
* [Offi Directions](https://gitlab.com/oeffi/oeffi) - An Android app that provides trip planning, schedules, live departure times, and disruption information for transport authorities in Europe and beyond.
* [Transito](http://git.sr.ht/~mil/transito) - FOSS data-provider-agnostic public transportation app that let's you route between locations using openly available public GTFS feeds (sourced from the [Mobility Database](https://database.mobilitydata.org/)). Utilizing the [Mobroute Go API](http://sr.ht/~mil/mobroute), the Transito app lets you performs routing calculations right on your phone. Cross-platform app currently supporting Android & Linux.

#### Native Apps (closed source)

* [Transit](http://transitapp.com/)
* [CityMapper](https://citymapper.com/)
* [Moovit](http://moovitapp.com/)
* [Transit Display](http://transitdisplay.com/) - Multimodal and real-time transit display software.
* [Ualabee](https://ualabee.com/company/) - Community driven trip planner with focus on user interaction, users can report anomalies, upload pictures, edit transit data and chat with other passengers.
* [ÖPNV Navigator](https://navigatorapp.net/)
* [TripGo](https://tripgo.com/)

### Hardware

Experimental and production transit hardware.

* [Train departure Display](https://github.com/chrisys/train-departure-display) ⭐ 306 | 🐛 34 | 🌐 Python | 📅 2025-08-08 - A replica, near real-time, miniature UK railway station train departure sign based upon a Raspberry Pi Zer0.
* [Bus Tracking GPS](https://github.com/herrdragon/busTrackingGps) ⭐ 34 | 🐛 0 | 🌐 Scala | 📅 2016-11-27 - Code for Miami prototype of a cheap open-source solution to track transit buses.

### SDKs

* [TripKit](https://github.com/alexander-albers/tripkit) ⭐ 107 | 🐛 9 | 🌐 Swift | 📅 2026-01-14 - TripKit is a Swift-library to get data from public transport providers.
* [KPublicTransport](https://invent.kde.org/libraries/kpublictransport) - A C++ library for accessing realtime public transport data and for performing public transport journey queries.
* [SkedGo's TripKit SDKs](https://developer.tripgo.com) - Open source SDKs for Android, iOS and React for accessing [SkedGo](https://skedgo.com)'s TripGo API, including trip planning UI components.

### Visualizations

#### GTFS Based Visualizations

* [Mapnificent](https://www.mapnificent.net/) - Shows areas you can reach with public transport in a given time. Open-source [on GitHub](https://github.com/mapnificent/mapnificent) ⭐ 392 | 🐛 22 | 🌐 JavaScript | 📅 2024-04-19, live at <https://www.mapnificent.net/>.
* [TransitFlow](https://github.com/transitland/transitland-processing-animation) ⭐ 288 | 🐛 6 | 🌐 Processing | 📅 2020-01-22 Animate GTFS data around the world using Processing and Transitland.
* [gtfs-visualizations](https://github.com/cmichi/gtfs-visualizations) ⭐ 142 | 🐛 1 | 🌐 JavaScript | 📅 2020-12-31 - Open-source NodeJS application for visualizing the routes of GTFS datasets.
* [gtfspy-webviz](https://github.com/CxAalto/gtfspy-webviz) ⭐ 64 | 🐛 4 | 🌐 JavaScript | 📅 2024-08-27 - Web application for animation and visualization of GTFS data using [gtfspy](https://github.com/CxAalto/gtfspy) ⭐ 167 | 🐛 21 | 🌐 Python | 📅 2023-05-23.
* [Toronto Transit Explorer](https://github.com/sidewalklabs/totx) ⚠️ Archived - A Java application that visualizes transit, biking and walking accessibility across the city of Toronto. Uses a modified version of [R5](https://github.com/conveyal/r5) ⭐ 361 | 🐛 237 | 🌐 Java | 📅 2026-01-26 for routing.
* [GTFS Viz 🚉](https://github.com/gabrielAHN/gtfs-viz) ⭐ 30 | 🐛 2 | 🌐 TypeScript | 📅 2025-07-08 - A web app that visualizes GTFS Data on the browser at scale without a backend on the client side using [duckdb-wasm 🦆](https://duckdb.org/docs/api/wasm/overview.html).
* [All Transit](https://all-transit.com) - Interactive GTFS route and schedule animation (for U.S. cities) using Mapbox GL JS, Deck.gl and Transitland. Github repository [here](https://github.com/kylebarron/all-transit) ⭐ 27 | 🐛 25 | 🌐 JavaScript | 📅 2023-01-11.
* [fastest-bus-analysis-in-the-west](https://github.com/vta/fastest-bus-analysis-in-the-west) ⭐ 24 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2018-11-13 - A python Pandas script that combines Ridership/APC, Swiftly speed and dwell data, bus stop inventory, GTFS, and geospatial shapes to create a stop by stop, route by route, time grouping filterable dataset for cross-analyses.  The dataset is then visualized in [Tableau](https://public.tableau.com/profile/vivek7797#!/vizhome/stopsandspeedanalyses/Story1) to help VTA Planners find places to make bus and rail network faster and more reliable through speedups methods like stop consolidation and dedicated lanes.
* [TNExT](https://github.com/ODOT-PTS/TNExT) ⭐ 17 | 🐛 23 | 🌐 Java | 📅 2023-03-22 - Transit Network Explorer Tool (TNExT) is a web-based software tool developed for the visualization, analysis, and reporting of regional and statewide transit networks in the state of Oregon.
* [Transit Vis](https://github.com/zackAemmer/transit_vis) ⭐ 15 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-03-05 - A visualization tool to display performance metrics derived from the King County Metro GTFS-RT feed (OneBusAway API). Viewable [here](https://www.transitvis.com/). Used for [this paper](https://link.springer.com/article/10.1007/s12469-022-00291-7).
* [Simple Transit Site](https://transit.chat/simple-transit-site) - An online example of how to create a transit website all from your gtfs [on Github](https://github.com/ioTransit/simple-transit-site) ⭐ 6 | 🐛 0 | 🌐 HTML | 📅 2024-07-18
* [BusGraphs Access Analyzer](https://gitlab.com/publictransitanalytics-pub/readme) - Web application for measuring the access provided by real and hypothetical fixed-route public transit networks, and visualizing and decomposing this access in variety of ways.
* [gtfs-to-geojson](https://www.transit.chat/gtfs-to-geojson) - A simple online converter for gtfs to geojson with a list of feeds.
* [Local Transit](https://www.localtransit.app) - Map visualization of public transit frequency, created using QGIS.
* [MIT COAXS](http://mittransportanalyst.github.io/) - Co-creative Planning of Transit Corridors using Accessibility-Based Stakeholder Engagement (shows route scenarios using [OpenTripPlanner Analyst](http://www.opentripplanner.org/analyst/)).
* [MOTIS](https://motis-project.de/) - Intermodal Mobility Information System including [visualization](https://europe.motis-project.de/)
* [MTA Frequency](http://www.tyleragreen.com/maps/new_york/) - Frequency visualization of subways and buses in New York City built using [Transitland](https://transit.land/).
* [SEPTA Rail OTP Report](https://apps.phor.net/septa/) - An online on-time performance reporing & drill down tool using GTFS.
* [Simple Transit Map](origin/\[https:/transit.chat/simple-transit-map]\(https:/github.com/ioTransit/simple-transit-map\)) - An online example of how to host and update a webmap.
* [TRAVIC Transit Visualization Client](http://tracker.geops.ch/) - Visualizes vehicles moving based on static GTFS data (and sometimes realtime data). Supports over 260 cities.  Github account for geOps organization is [here](https://github.com/geops).
* [Traze](https://traze.app/) by [Veridict](https://www.veridict.com) - Visualization of public transport vehicles from all over the world. Collaborate with other users to get real-time updates even when it is not available from the agency. Based on a number of sources, including GTFS and GTFS-RT. (Previously known as Livemap24).
* [Visualizing MBTA Data](http://mbtaviz.github.io/) - Interactive graphs that show how people use Boston's subway system.
* [QGIS - GTFS plugins](https://plugins.qgis.org/search/?q=gtfs) - List of plugins for GTFS in QGIS

#### Transit Map Creation

* [Brand New Subway](https://jpwright.github.io/subway/) - An interactive transportation planning game that lets players alter the NYC subway system to their heart's content.
* [BENO Metro Mapm Creator](https://beno.uk/metromapcreator/#) - A very old fashioned but classic transit map creator.
* [Tennessine Metro Designer](https://tennessine.co.uk/metro/) - A modern and aesthetically pleasing transit map designer.
* [loom](https://github.com/ad-freiburg/loom) ⭐ 244 | 🐛 11 | 🌐 C++ | 📅 2026-01-15 - Software suite for the automated generation of geographically correct or schematic transit maps.
* [Metro Map Maker](https://metromapmaker.com/)   - An open source and simple metro map maker software.
* [MetroDreamin'](https://metrodreamin.com/explore) - A modern, open source software that allows users to create, save, like, and share interactive transit maps with agents.
* [Rail Map Generators](https://wongchito.github.io/RailMapGenerator) - Tool for generating railway maps and information panels in the styles of various cities' public transportation systems.
* [MetroSets](https://metrosets.ac.tuwien.ac.at/) - A flexible web tool to visualize set systems using the metro map metaphor. Based on this [paper](https://www.computer.org/csdl/journal/tg/2021/02/09224192/1nV7Me0F3Lq)

##### General Drawing Applications for making transit visualizations

* [Adobe illustrator](https://www.adobe.com/ca/products/illustrator.html) - The industry-leading vector graphics software (requres membership plan).
* [Inkscape](https://inkscape.org/) - A free desgn tool similar to Adobe Illustrator.

##### General GIS Applications for making transit visualizations

* [Felt](https://felt.com/) - An aestically pleasing Modern GIS software.
* [Google Mymaps](https://www.google.ca/maps/about/mymaps/) - Create and share custom maps with Google My Maps.
* [Google Earth](https://www.google.com/earth/about/) - Create and share custom maps with one of the the world's most detailed statelite applications.

#### Transit Map Aggregation

* [UrbanRail.Net](http://www.urbanrail.net/) - Worldwide reference map of urban rail transport (metros,trams,commuter rail) with detailed and up-to-date information.
* [OpenRailwayMap](https://www.openrailwaymap.org/) - Worldwide map of railways using OpenStreetMap data.
* [AllRailMap](https://www.allrailmap.com/) - Another worldwide map of railways using OpenStreetMap data.
* [European Railway Atlas](https://europeanrailwayatlas.com/) -  A reference book of European railway maps that is available for purchase.
* [Rail Transit Maps](http://www-personal.umich.edu/~yopopov/rrt/railroadmaps/) - A collection of railway maps covering Europe (especially Russia).
* [Tramscale](https://alexander.co.tz/tramscale/) - Website outlining maps showing the scales of tram systems around the world.
* [Timelines](https://alexander.co.tz/timelines/) - Compare the timelines of Rapid Transit Projects around the world.
* [Metrolinemap](https://www.metrolinemap.com/) - Interactive Maps of the world's Metro systems.
* [Metrocyclopaedia](https://blog.csaladen.es/metro/ ) - 3d maps of metro systems across the world (uses data from Metrolinemap).
* [RailFansCanada](https://map.railfans.ca/) - Interactive System Map detailing the  the present and future of different urban rail systems in Canada.
* [North American Transit](https://www.google.com/maps/d/u/0/viewer?mid=1GAXiiEp8a62LvZNDueYN76NPTCoUxvdx\&ll=43.71257881237152%2C-79.385523993394\&z=11) - Map of all Passenger Rail in North America including (intercity rail, metros, trams and tourist lines)
* [Intercity Rail map](https://asm.transitdocs.com/) - Map of the real time location and schedule information for  Amtrak and Via trains
* [Indian Railways Map](https://indiarailinfo.com/atlas) - Interactive Maps of the Indian Main rail network.
* [National Rail Network Map](https://www.arcgis.com/apps/mapviewer/index.html?webmap=96ec03e4fc8546bd8a864e39a2c3fc41) - This map shows the extent and ownership of rail lines in the United States, including passenger and freight lines.
* [Ferrocarta](https://ferrocarta.net/) - A series of maps covering all of the passenger rail networks in Brazil, Canada and France.
* [Train Lookout](https://trainlookout.com/) - A tool to easily Log, map and share your journeys by train.
* [Australian Rail Maps](http://www.railmaps.com.au/) -   Detailed Australian railway maps from the national, state and city levels.
* [Steam Engine "IS"](https://parovoz.com/maps/supermap/) - Maps of railways in the USSR.
* [Carto.Metro](https://cartometro.com/) - Detailed maps of metro and tram networks of global cities (especially in France).
* [Railway Stations](https://map.railway-stations.org/) - Photos of Railway Stations across the world.
* [INAT](https://www.inat.fr/maps/) - Aesthetically pleasing static maps of worldwide metros systems.
* [Transit Maps](https://transitmap.net/) - Critiques and reviews of the design of transit maps from across the world.
* [Transit Explorer](https://www.thetransportpolitic.com/transitexplorer/) - A map containing fixed-guideway transit around the world.
* [Britsh Railways](https://www.merrittcartographic.co.uk/british_railways.html) An interactive map of Great Britain's rail network.
* [TransitLand Map](https://www.transit.land/map)  - Worldwide map of transit services (which have a GTFS Feed).
* [DB InfraGO](https://geovdbn.deutschebahn.com/pgv/public/map/isr.xhtml)  - Interactive Map of German Rail infrastructure.
* [SNCF Carte interactive](https://www.sncf-reseau.com/fr/carte/carte-interactive-reseau-ferre-francais-0) - Interactive Map of French Rail infrastructure.
* [Project Mapping](https://www.projectmapping.co.uk/index.html) - Schematic maps of UK and worldwide rail networks.
* [China Railway Map](http://cnrail.geogv.org/enus/about) - An online Interactive map for the passenger railway transportation system of China, presenting station and rail information.
* [Canadian Rail Atlas](https://rac.jmaponline.net/canadianrailatlas/) - a user-friendly, interactive map of Canada’s nearly 43,000-kilometre railway network.
* [The Rail Map](https://www.therailmap.com/) - An Interactive Map with Train lines in North America using data from OpenStreetMap.
* [JR pass](https://www.jrpass.com/map#) - Interactive Map of Mainline Rail in Japan.
* [Openptmap](https://wiki.openstreetmap.org/wiki/Openptmap) - openptmap shows public transport lines.
* [OSMTransportViewer](https://gileri.github.io/OSMTransportViewer/) - Use OSM Overpass API to get network data
* [PTMap](https://ptmap.plepe.at/#lat=48.20200\&lon=16.33800\&zoom=15) - The PTMap shows public transport routes as they are entered to the OpenStreetMap.
* [Unroll](https://jungle-bus.github.io/unroll/) - Public transport routes
* [Jungle Bus Map](https://jungle-bus.github.io/map/#15/48.8584/2.34846) - A webmap for viewing transport stop deails in OpenStreetMap.
* [AccraMobile3](https://wiki.openstreetmap.org/wiki/AccraMobile3) - Accra Mobile 3 is a project launched in July 2017 to map all the Tro tro lines of Accra, Ghana for the Department of Transport (DoT) of Accra...
* [OpenStationMap](https://openstationmap.org/#17/52.51022/13.43477/8.8/55) - Displays indoors of public transport stations (including rails and platforms).

### Agency Tools

Tools for transit agencies.  See also [GTFS Data Collection and Maintenance Tools](#gtfs-data-collection-and-maintenance-tools) for tools specific to GTFS.

* [RidePilot](https://github.com/camsys/ridepilot) ⭐ 24 | 🐛 4 | 🌐 Ruby | 📅 2023-01-31 - An open-source Computer Aided Scheduling and Dispatch (CASD) software system to meet the needs of small scale human service transportation agencies.
* [TNExT](https://github.com/ODOT-PTS/TNExT) ⭐ 17 | 🐛 23 | 🌐 Java | 📅 2023-03-22 - Transit Network Explorer Tool (TNExT) is a web-based software tool developed for the visualization, analysis, and reporting of regional and statewide transit networks in the state of Oregon.
* Route Trends ([webapp](https://metrotransitmn.shinyapps.io/route-trends/), [GitHub](https://github.com/metrotransit/route-trends) ⭐ 16 | 🐛 2 | 🌐 R | 📅 2019-05-29) - An R Shiny app to ingest ridership time series, and return seasonal, trend, and residual components according to [STL methodology](https://otexts.com/fpp2/stl.html) and forecasts including uncertainty based on those components.  Sponsored by [Metro Transit](https://www.metrotransit.org/) (Minneapolis-St. Paul).
* [AC Transit Training and Education Department (TED) application](https://github.com/actransitorg/ACTransit.Training) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2016-09-20 - This application supports the District's training operations for transportation and maintenance employees, primarily in the positions of Bus Operators and Heavy Duty Coach Mechanics (Apprentice and Journey), although the system supports new courses and apprenticeship programs.
* [AC Transit Customer Relations application (CusRel)](https://github.com/actransitorg/ACTransit.CusRel) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2017-12-28 - Public transit ticketing system for customer issues and feedback with: inter-departmental routing with notifications, department/person assigments, simple workflow, ticket searching, pre-canned reports, daily reminders and more.
* [Next Train API](https://github.com/data-creative/next-train-api) ⭐ 4 | 🐛 1 | 🌐 Ruby | 📅 2018-12-29 - Serves any GTFS feed as a JSON API. Transit agencies and developers alike can deploy the open source code to their own Heroku server.
* [AC Transit RestroomFinder](https://github.com/actransitorg/ACTransit.RestroomFinder) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2022-10-18 - Pinpoints the nearest authorized restroom for bus operator and field staff, using GPS and on-screen map.
* [Remix by Via](https://ridewithvia.com/solutions/remix) - A webapp that lets transit agencies easily plan routes.
* [PTV Lines](https://www.ptvgroup.com/en/products/ptv-lines) - A cloud-based public transport software for line planning and public transport service optimisation
* [TransAM](origin/\[http:/camsys.software/products/transam]\(https:/github.com/camsys/transam_core\)) - An open-source asset management platform for public transportation agencies.
* [TBEST](https://tbest.org/) - TBEST (Transit Boardings Estimation and Simulation Tool) is an effort to develop a multi-faceted GIS-based modeling, planning and analysis tool which integrates socio-economic, land use, and transit network data into a platform for scenario-based transit ridership estimation and analysis. Funded by the Florida Department of Transportation. Free to use but not open-source.
* [RideSheet](https://docs.ridesheet.org) – A simple, spreadsheet-based tool for small demand-responsive transportation (DRT) services.

## Resources

### Community

Places to ask questions and find other community resources.

* [MobilityData Slack chat](https://share.mobilitydata.org/slack) - Chatroom that includes channels #gtfs, #gtfs-validators #mobility-database  #gtfs-realtime #gtfs\_best-practices #gtfs-pathways #gtfs-fares #gtfs-flex #trb-transit-data.
* [Transit Developers mailing list](https://groups.google.com/forum/#!forum/transit-developers)
* [OpenTripPlanner](https://github.com/opentripplanner/OpenTripPlanner) ⭐ 2,540 | 🐛 147 | 🌐 Java | 📅 2026-02-07 Community
  * [OpenTripPlanner User mailing list](https://groups.google.com/forum/#!forum/opentripplanner-users)
  * [OpenTripPlanner Developers mailing list](https://groups.google.com/forum/#!forum/opentripplanner-dev)
* OneBusAway
  * [OneBusAway Developers mailing list](http://groups.google.com/group/onebusaway-developers)
  * [OneBusAway API mailing list](http://groups.google.com/group/onebusaway-api)

#### Local and regional groups

* [German Open Transport Meetup](https://github.com/transportkollektiv/meetup/wiki) ⭐ 51 | 🐛 0 | 📅 2023-12-08 - [Biweekly](https://hackmd.okfn.de/opentransportmeetup#) online meetup of the German-speaking open transport community.
* [German Open Transport Data Quality Meetup](https://github.com/transportkollektiv/meetup/wiki) ⭐ 51 | 🐛 0 | 📅 2023-12-08 - Bimonthly online meetup of the German-speaking open transport community dedicated to data quality.
* [Open Train Community](https://github.com/hasadna/OpenTrainCommunity) ⭐ 25 | 🐛 55 | 🌐 HTML | 📅 2023-01-13 - Opentrain repository for community data analysis of Israel Railways train delay data.
* [Transit Techies NYC](https://transittechies.nyc/) - NYC-based in-person/online hybrid meetup. [Speaker list](https://transittechies.nyc/past) includes many contributors to this repo.

### Research and Commentary

Blog posts, and reports related to open transit data.

#### Blog posts

* [When(ish) is my bus? Data and code](https://github.com/mjskay/when-ish-is-my-bus) ⭐ 45 | 🐛 0 | 🌐 R | 📅 2018-04-20 - The data and code (R) behind Whenish is my bus? Data includes three days of historical vehicle positions and the survey results.
* ["Legacy AVL system? It's okay, join the club." by Kurt Raschke](https://kurtraschke.com/2015/01/legacy-avl-export) - Discussion of options for transforming legacy AVL system data into the GTFS-realtime format.
* ["GTFS Best Practices now available!" by Sean Barbeau](https://medium.com/@sjbarbeau/gtfs-best-practices-now-available-88ac67194233) - Discusses some of the challenges of an open data format like GTFS and the GTFS Best Practices that were launched in early 2017 to help address data quality.
* ["What's new in GTFS-realtime v2.0" by Sean Barbeau](https://medium.com/@sjbarbeau/whats-new-in-gtfs-realtime-v2-0-cd45e6a861e9) - Discuss the shortfalls in GTFS-realtime v1.0 and the improvements in v2.0.
* ["AVL, CAD, and Real-Time Passenger Info for Beginners" by Tony Laidig](http://transitdata.net/avl-cad-and-real-time-passenger-info-for-beginners/) - Provides a general introduction to technology used to track vehicles.
* ["Visualizing Better Transportation: Data & Tools" by Steve Pepple](https://medium.com/@stevepepple/visualizing-better-transportation-data-tools-e48b8317a21c) - A collection of transportation-related data and tools for the San Francisco Bay Area and other cities in North America, originally collected and discussed at a 2018 Transit Week Event at ARUP in San Francisco.
* ["How to use GTFS data to track transit vehicles in realtime" by Tom Camp](https://www.ably.io/blog/gtfs-data-track-transit-vehicles-realtime) - Using GTFS and GTFS Realtime to provide continuous realtime updates.

#### Academic papers

* [Kay et al. - "When(ish) is my bus? User-centered Visualizations of Uncertainty in Everyday, Mobile Predictive Systems"](https://www.mjskay.com/papers/chi_2016_uncertain_bus.pdf) - Paper attempts to answr the question of "how do we communicate uncertainty in transit predictions?" Explains the problem, existing solutions and designs a [better interface for letting users know when to arrive at the bus stop](https://github.com/mjskay/when-ish-is-my-bus/blob/master/quantile-dotplots.md#quantile-dotplots) ⭐ 45 | 🐛 0 | 🌐 R | 📅 2018-04-20.
* [Aemmer et al. - "Measurement and classification of transit delays using GTFS-RT data"](https://link.springer.com/article/10.1007/s12469-022-00291-7) - Presents a method for extracting transit performance metrics from a General Transit Feed Specification’s Real-Time (GTFS-RT) component and aggregating them to roadway segments. Used with [Transit Vis](https://github.com/zackAemmer/transit_vis) ⭐ 15 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-03-05, viewable [here](https://www.transitvis.com/).
* [Gramacki et al. - "gtfs2vec - Learning GTFS Embeddings for comparing Public Transport Offer in Microregions"](origin/2021) - Methology using Uber's H3 spatial index and machine learning to identify areas of "similar" public transit service quality in cities. Source code available [on GitHub](https://github.com/pwr-inf/gtfs2vec) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-07-04.
* [Tang et al. - "Ridership effects of real-time bus information system: A case study in the City of Chicago"](https://www.sciencedirect.com/science/article/pii/S0968090X12000022) - Experiment in Chicago, IL showed modest increase in ridership when riders had access to real-time info via text message or email.
* [Watkins et al. - "Where Is My Bus? Impact of mobile real-time information on the perceived and actual wait time of transit riders"](https://www.sciencedirect.com/science/article/pii/S0965856411001030) - Experiments in Seattl,e WA showed that riders perceived shorter bus wait times when they had access to real-time info via mobile apps.
* [Brakewood et al. - “An experiment evaluating the impacts of real-time transit information on bus riders in Tampa, Florida”](https://www.sciencedirect.com/science/article/pii/S0965856414002146) - Controlled experiment in Tampa, FL showed that riders with access to real-time info via mobile apps perceived nearly 2 minute reduction in wait times compared to riders without real-time info.  Riders with real-time info also had decreases in anxiety and frustration and better reception of agency.
* [Brakewood et al. - "The impact of real-time information on bus ridership in New York City"](https://www.sciencedirect.com/science/article/pii/S0968090X15000297) - Experiment in NYC showed that ridership increased on long routes when real-time info was made available to riders.
* [Brakewood and Watkins - "A literature review of the passenger benefits of real-time transit information"](https://www.tandfonline.com/doi/full/10.1080/01441647.2018.1472147?scroll=top\&needAccess=true) (2018) - An overview of many different research studies looking at the benefits of real-time transit information.
* [Higgins et al. - "Calculating place-based transit accessibility: Methods, tools and algorithmic dependence" (2022)](https://doi.org/10.5198/jtlu.2022.2012) - Compares software tools for calculating accessibility by walking and public transit including ArcGIS Pro, Emme, R5R, and OpenTripPlanner.

#### Government reports

* [APTA Policy Development and Research - Public Transportation Embracing Open Data](http://www.apta.com/resources/reportsandpublications/Documents/APTA-Embracing-Open-Data.pdf) - APTA's discussion of the benefits and challenges of open transit data (a short summary of the below TCRP report).
* [TCRP Synthesis 115 - Open Data: Challenges and Opportunities for Transit Agencies](http://onlinepubs.trb.org/Onlinepubs/tcrp/tcrp_syn_115.pdf) (2015) - A comprehensive report looking at the benefits and challenges of open transit data.
* [TCRP Research Report 213: Data Sharing Guidance for Public Transit Agencies – Now and in the Future](http://www.trb.org/Main/Blurbs/180188.aspx) (2020) - A report designed to help agencies make decisions about sharing their data, including how to evaluate benefits, costs, and risks.
* [TCRP G-16 Development of Transactional Data Specifications for Demand-Responsive Transportation (In progress)](http://apps.trb.org/cmsfeed/TRBNetProjectDisplay.asp?ProjectID=4120) - The objective of this research is to develop technical specifications for transactional data for entities involved in the provision of demand-responsive transportation.  Expected completion date is late 2018.

#### Community-maintained lists

* [Vendors Providing GTFS Creation/Maintenance services](https://docs.google.com/spreadsheets/u/1/d/1Gc9mu4BIYC8ORpv2IbbVnT3q8VQ3xkeY7Hz068vT_GQ/pubhtml) - Add new vendors [here](http://goo.gl/forms/YDbPSPmufS).
* [Entities Providing Transportation Software Development Consulting Services](https://docs.google.com/spreadsheets/u/1/d/1n44CNMCK1vt1nyrsdYz-KD_hYxUMNIm6Me69M6ROBIg/pubhtml) - Add new entities [here](http://goo.gl/forms/cc6kcVERuP).

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [MobilityData](https://mobilitydata.org/),[Center for Urban Transportation Research](https://www.cutr.usf.edu/) at the [University of South Florida](http://www.usf.edu/), and [Luqmaan Dawoodjee](https://github.com/luqmaan) have waived all copyright and related or neighboring rights to this work.

## About

This is a community resource for informational use only - listing of a project/product does not imply endorsement.

This list is built and maintained by open source community contributors like you! [MobilityData](https://mobilitydata.org/) stewards the project.

\#Awesome-transit was originally created by [Luqmaan Dawoodjee](https://github.com/luqmaan) and was stewarded by the [Center for Urban Transportation Research](https://www.cutr.usf.edu/) at the [University of South Florida](http://www.usf.edu/) for several years before the project was transferred to MobilityData.
