---
layout: default
title: Spreadsheet Setup
parent: Quantities
nav_order: 1
---

# Quantities Spreadsheet Setup
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


Follow these instructions to set up the Quantities spreadsheet in Excel. The Quantities spreadsheet is used to tabulate the quantities of each bid item needed for a project. Each column in the spreadsheet represents the stationing from a given sheet. The bid items in each column represent the quantity of those items in each plan sheet.

## Copy the Quantities Template
***

Rather than start from scratch, it's easier to copy the existing Quantities Template from the S&C Knowledge Library. That way, you don't
have to worry about reproducing the formulas in the new spreadsheet. The template is located in the `Templates` folder. Alternatively, the template also exists in the `PROJECT FILE (copy for each project)`, so if you've already copied over a new project file, you should be all set.

Once you've copied the template:

1.  In Dropbox, go to **Project Development** > **Design** > **Estimates**

2.  Paste the copied spreadsheet in the Estimates folder

3.  The file should be called `XXXX_Quantities and Estimates_SWPPP_MMDDYYYY`

    -   Replace the `XXXX` with the project name and `MMDDYYYY` with the date

## Prepare the Quantities Template
***

Before you begin, you'll want to set the template up for your project.

1.  Update the stationing for each sheet in the Estimate Summary tab:

    ![](../assets/images/stationing.png)
    {: .ml-2 }

    -   You can confirm the station numbers in the sheet file's border in ORD.

    -   Except for the first station (cell E7), the start station will automatically update based on the end station from the previous column. Overwrite it if necessary (for example, for BEGIN or END stations).

    -   To prevent the NAME values from incrementing up (e.g., SH75, SH76, SH77), hold the **CTRL** key while you drag.

2.  The **Design Quantities** stations should automatically update based on the **Estimate Summary** values.

3.  Update the NAME and KEY NO. for the project in the **Cost Estimate Summary** sheet.

4.  Add any additional bid items not on the template to both the **Design Quantities** and **Estimate Summary** sheets.

    -   Make sure the **Estimate Summary** Total column includes a SUM() function for the new bid item row.

5.  Verify the units for each bid items.

    -   Feet (FT), Cubic Yards (CY), Acres (ACRE), etc.

    -   Check the ITD Pay_Items_Working_Document (Dropbox\\Engineering Reference Docs\\ITD\\ITD Pay Item List\\Pay_Items_Working_Document) to confirm units, check with Sherri for help calculating them.

6.  Make sure that **File** > **Options** > **Advanced** > **Display Options for this Worksheet: "Estimate Summary"** > **Show a zero in cells that have zero value** is unchecked.

    -   With this setting off, empty cells will remain empty instead of displaying a 0.

    <img src="../assets/images/no-zeroes.png" width=500 style="margin-left: 1.5rem;">
