# SharePoint 2013 Filtered Lookup Field

This is SharePoint 2013 port of *SharePoint 2010 Filtered Lookup* provided [here](http://sp2010filteredlookup.codeplex.com/) by Dev4Side, which is also a port of the package provided [here](http://filteredlookup.codeplex.com/) :) SharePoint 2016 version can be found [here](https://github.com/hasangok/sharepoint-2016-filtered-lookup-field).

Description below is copied from [here](http://filteredlookup.codeplex.com/).

## Description
This project creates a custom SharePoint lookup field that offers new functionalities to default SharePoint lookup field by allowing filters to be applied to retrieved data. Applied filters can be either dynamic CAML queries or pre-defined list views residing in source lists.

Below is a few of the features offered by Filtered Lookup field over standard SharePoint Lookup field:  
* Cross-site lookup (all sites within same site collection)
* Filter retrieved data using list views
* Filter retrieved data using dynamic/ad-hoc CAML queries. This means you don't need to create a list view each time you want to apply a lookup filter to source data
* Supports retrieving data recursively using either list views or dynamic queries
* Supports MultiLookup with filtered data
* Same look and feel as default SharePoint Lookup and MultiLookup (i.e. in list forms)

## Installation
Download source, publish wsp package, put it into your SharePoint server machine and run the following commands in *SharePoint 2013 Management Shell*.
```powershell
Add-SPSolution "/path/to/Dev4Side.SP2013.FilteredLookup.wsp"
Install-SPSolution –Identity Dev4Side.SP2013.FilteredLookup.wsp –GACDeployment
```

## Screenshot
![filtered_lookup_sp2013.png](https://raw.githubusercontent.com/hasangok/sharepoint-2016-filtered-lookup-field/master/filtered_lookup_sp2016.png)
