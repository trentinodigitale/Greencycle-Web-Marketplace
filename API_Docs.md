The Greencycle Web Marketplace platform automatically displays its public content using the Open Data paradigm; in this sense, in order to evaluate the ways in which through these data it is possible to create new services.

Some useful information is provided below for those who intend to develop applications and take advantage of the programming interfaces (API) made available by the ComunWeb platform to access data.

All the contents of the site, natively structured with the information classes provided in the patform, can be freely extracted in a structured format, using two different criteria:

* direct links to CSV format files (compatible with spreadsheet software such as Microsoft Excel and OpenOffice Calc), for citizens without special computer skills
* RESTful API in JSON format, for programmers

If access is not possible, please contact the development team <greencycle@tndigit.it> for direct support.

API v.2 (recommended for new projects)
A completely new version of the API has been created, based on the open services paradigm.

For more information on APIs and how to use them, visit the Github project (https://github.com/opendatatrentino/openservices/blob/master/README_en.md).

# API v.1 (not recommended for new projects)
All the contents of the site can be freely extracted in a structured format, through two different criteria:

* direct links to CSV format files (compatible with spreadsheet software such as Microsoft Excel and OpenOffice Calc), for citizens without special computer skills
* RESTful API in JSON format, programmers use JSON format

# the API exposes the following features:

* the list of all the datasets published on the site, complete with related metadata
* the list of all datasets containing structured information managed by ComunWeb, in JSON format: / api / opendata / v1 / content / classList

# Some practical examples:

* navigable list of municipal services: / api / opendata / v1 / content / class / service
* navigable list of available modules: / api / opendata / v1 / content / class / module
* list of the last 10 modules: / api / opendata / v1 / content / class / module / offset / 0 / limit / 10

By following the individual links, you can reach the documents / data with the related metadata associated with it.

Using the CSV format
In compliance with the licenses indicated, anyone can download the structured contents on the site, using a link in the form "/ exportas / csv / <tipologia_di_contenuto>", for example:
* to download the list of modules: / exportas / csv / module
* to download the list of services: / exportas / csv / service
