---
layout: article
title: Getting Street Manager data into PowerBI
date: 2020-01-28T15:36:38.118Z
type: article
published: 'true'
status: publish
---
# Getting Street Manager data into PowerBI

This is a basic guide for how to import Street Manager data into [PowerBI](https://powerbi.microsoft.com/en-us/) for reporting purposes. This is based on the online version of PowerBI and last updated on 28/01/2020, so there may be differences if you are using the desktop client or an updated version.

## Export CSV via UI and upload

The simplest way to get data into PowerBI is to manually export the data using the   CSV export links available on the Dashboard list pages and upload them into PowerBI for processing.

1. Log into Street Manager and go to the list page with the data you are interested in and set the filter criteria, e.g. Permits completed within a specific month.
    
    ![permit list for export](/docs/assets/images/cms/permit-list-for-export-1.png "permit list for export")
    
2. Click the "Export results" link at the bottom of the list to download a CSV file with the data.
    
    ![download csv link](/docs/assets/images/cms/permit-list-for-export-2.png "download csv link")
    
3. Navigate to PowerBI and the Workspace you are going to use then create a new Dataset.
    
    ![new dataset](/docs/assets/images/cms/powerbi-new-dataset.png "new dataset")
    
4. On the Get Data screen, click Get for Create new content > Files.
    
    ![PowerBI get data file](/docs/assets/images/cms/powerbi-get-data.png "PowerBI get data file")
    
5. Select "Local File" and upload the CSV you get from the Street Manager list screen.
    
    ![PowerBI local file](/docs/assets/images/cms/powerbi-local-file.png "PowerBI local file")
    
6. Your data will appear as a new Dashboard and Dataset which you can visualise and generate Reports.
    
    ![Dashboard](/docs/assets/images/cms/powerbi-dashboard.png "Dashboard")
    
    ![Report](/docs/assets/images/cms/powerbi-report.png "Report")
