---
layout: article
title: Reporting data options in Street Manager
date: 2020-01-28T15:36:38.118Z
type: article
published: 'true'
status: publish
---
# Reporting data options in Street Manager

Street Manager offers a number of ways your organisation can retrieve data to do reporting.

## List pages

Street Manager has a number of list pages designed to display key information about your organisations works. These lists have complex filtering options which allow you to request specific sets of the information for reporting purposes. 

The filter options are persisted in the page URL, so you can bookmark the page in your browser to save pre-defined reports and share with others.

## Export CSV

Each list page has an option at the bottom of the screen to export your results as CSV, allowing you define your report and then export the data set.

The CSV file can be opened in common spreadsheet applications, such as Microsoft Excel, to use the data in common reports or combine with other organisational data.

Other data reporting and analysis tools can use CSV files, such as Power BI. See [here](https://departmentfortransport.github.io/street-manager-docs/articles/getting-street-manager-data-into-powerbi.html) for instructions on how to use the data in Power BI.

## Via API

Street Manager has a number of external APIs for submitting and extracting data from the Service. If you need to extract the lowest level of information about individual Permits/Inspections/FPNs then creating an application that calls the API to get specific data gives you the most control for custom reporting. See [here](https://departmentfortransport.github.io/street-manager-docs/api-documentation/) for full details on the Street Manager API.

## Get all my data

_(This functionality is not yet available)_

Street Manager has an organisation level data export function available in the UI/API, that allows you to bulk export data as CSV files. This allows you to build a full relational database of Street Manager data related to your organisation.

This option is for organisations that require all work data for complex business specific reporting which cannot be fulfilled by other reporting data.

To use this data you must understand the schema and reference data used in Street Manager.
