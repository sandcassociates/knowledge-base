---
layout: default
title: PSET Creation
parent: Plan Sheets
nav_order: 3
---

# Creating a Print Set (PSET) for Plan Sheets
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

This document will guide you through creating a Print Set (.pset) of
sheets in ORD.

1.  Find the project 2D seed file, right click, then click **Copy**.
    Paste it into the S&C sheet folder for the project.

    -   The 2d seed file is usually located in the **Project
        Development** \> **Project Resources** **\> OpenRoads Designer**
        \> **Project Seeds** directory. It'll be named something like
        **xxxxx_Seed2d.dgn**

2.  Rename the seed file using this naming convention:
    12345_Discipline_Date.PSET

    -   E.g., 20445_Util_03102022_Pset (is it supposed to be .pset or
        \_pset?)

3.  Open the .pset file

4.  Go to **File** \> **Print** \> **Print Organizer**

    -   **Alternative option:** Open one of the plan sheets from your
        project, then select **File** \> **Print** \> **Print
        Organizer**. Follow the steps below.

![](media/image2.png){width="2.74in" height="2.31in"}

5.  Select **Add Files to Set**.

![Graphical user interface, application, Word Description automatically
generated](media/image3.png){width="2.07in" height="1.01in"}

6.  Select **Add**.

![Graphical user interface, application Description automatically
generated](media/image4.png){width="1.74in" height="1.54in"}

7.  Add all the files you want included in the .pset.

8.  Set the Print Definitions (this step is important, go slow and check
    that you made the right selections.)

    -   Select **Manually Specified Options**, not **"..."**

> ![Graphical user interface, text, application, email Description
> automatically generated](media/image5.png){width="2.8in"
> height="2.45in"}

9.  For Utility Sheets, use the Utility Pen Table. See the below
    settings for the recommended selection.

    -   Utility Sheets:

        -   Pen Table=ITD.tbl

        -   Design Script=Halfsize Utility

    -   SWPPP Sheets:

        -   Pen Table=ITD.tbl

        -   Design Script= Automatic Size and Color

        -   ![](media/image6.png){width="3.55in"
            height="3.9298611111111112in"}Set the Logical name in the Z
            Base file. See the screen shot below for the Logical names
            that the automatic size and color can read. Note that each
            logical name needs to be unique. So if you need multiple
            files to print in Black and White, Type BW-1, BW-2 Etc.
            Logical names can be manipulate in the references dialog in
            the Zbase.

> ![](media/image8.png){width="3.0597222222222222in" height="3.35in"}

10. Click **OK**, then click **OK** again

11. Print

    -   When the pset is done and asks if you want to save, select
        **Yes**, then **No Wizard**. Update the pset file name and make
        sure it's saving to your current S&C Plan Sheet folder location.

**Automatic Size and Color Design Script recognizes the following
logical names:**

BW= Black and White

DG= Dark Grey

MG= Medium Grey

LG= Light Grey

VL= Very Light Grey

Color= Color

Adjust these in References \> Logical

-   If Logical is not an option, right click in the top bar where it
    says file name. Check **Logical**.

![](media/image10.png){width="6.779861111111111in"
height="1.979861111111111in"}
