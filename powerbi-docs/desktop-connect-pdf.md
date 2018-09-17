---
title: Connect to a PDF file in Power BI Desktop (Preview)
description: Easily connect to and use data from PDF files in Power BI Desktop
author: davidiseminger
manager: kfile
ms.reviewer: ''

ms.service: powerbi
ms.component: powerbi-desktop
ms.topic: conceptual
ms.date: 09/10/2018
ms.author: davidi

LocalizationGroup: Connect to data
---
# Connect to a PDF file in Power BI Desktop (Preview)
In Power BI Desktop, you can connect to a **PDF file** and use the included data from the file, just like any other data source in Power BI Desktop.

![Connect to data in PDF files](media/desktop-connect-pdf/connect-pdf_04.png)

The following sections describe how to connect to a **PDF file**, select data, and bring that data into **Power BI Desktop**.

## Enable the PDF connector
The PDF connector is in preview for **Power BI Desktop**, and must be enabled. To enable the PDF connector, select **File > Options and Settings > Options > Preview features**, then select the checkbox beside **Get data from PDF files**. 

![Enable the PDF connector from Options > Preview features](media/desktop-connect-pdf/connect-pdf_01.png)

You'll need to restart **Power BI Desktop** after you make the selection.

When you first use the **PDF (beta)** connector, you'll be warned that the PDF connector is still under development, and may change in the future. Select **Continue** to use the connector.

We always recommend upgrading to the most recent release of **Power BI Desktop**, which you can get from a link in [get Power BI Desktop](desktop-get-the-desktop.md). 

## Connect to a PDF file
To connect to a **PDF** file select **Get Data** from the **Home** ribbon in Power BI Desktop. Select **File** from the categories on the left, and you see **PDF (beta)**.

![Select PDF from Get Data](media/desktop-connect-pdf/connect-pdf_01.png)

You're prompted to provide the location of the PDF file you want to use. Once you provide the file location and the PDF file loads, a **Navigator** window appears and displays the data available from the file, from which you can select one or multiple elements to import and use in **Power BI Desktop**.

![Connect to data in PDF files](media/desktop-connect-pdf/connect-pdf_04.png)

Selecting a checkbox next to discovered elements in the PDF file displays them in the right pane. When you're ready to import, select the **Load** button to bring the data into **Power BI Desktop**.


## Next steps
There are all sorts of data you can connect to using Power BI Desktop. For more information on data sources, check out the following resources:

* [What is Power BI Desktop?](desktop-what-is-desktop.md)
* [Data Sources in Power BI Desktop](desktop-data-sources.md)
* [Shape and Combine Data with Power BI Desktop](desktop-shape-and-combine-data.md)
* [Connect to Excel workbooks in Power BI Desktop](desktop-connect-excel.md)   
* [Enter data directly into Power BI Desktop](desktop-enter-data-directly-into-desktop.md)   
