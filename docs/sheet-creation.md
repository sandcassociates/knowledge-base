---
layout: default
title: Plan Sheet Creation
parent: Plan Sheets
nav_order: 2
---

# Plan Sheet Creation
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

This page will guide you through the full workflow for creating plan sheets in OpenRoads Designer Connect Edition

{: .alert}
It's much simpler (and preferred) to create plan sheets following the instructions on the [Sheet Setup] page.

**Set up your Container File**

1.  Copy the project 2D Design seed file to the S&C Plan Sheet folder in
    ProjectWise

2.  Rename the file to include "cf" ("container file")

3.  Open the file.

4.  Attach the reference files you want displayed in the sheets.

    a.  Usually Alignment, Terrain, ROW, Topo (are these the options you
        can choose, or do you usually select all four?)

**Drawing production process**

1.  In ORD, navigate to **Drawing Production** \> **Named Boundary**

2.  ![A picture containing text, office supplies, pen, writing implement
    Description automatically generated](media/image2.png){width="0.8in"
    height="0.7in"}Click the drop-down arrow.

3.  Click **Place Named Boundary**.

    -   The Place Named Boundary dialog window will display

4.  Select the type of profile you want to create.

    -   Generally for plan sheets, you will select **Civil Plan**. This
        creates sheets based on the project alignment.

![](media/image3.png){width="3.99in" height="2.22in"}

5.  Select your Drawing Seed based off the desired sheet scale. This can
    sometimes be a trial-and-error thing. (Why is it a trial and error
    thing? How do you determine the correct drawing seed selection?)

![](media/image5.png){width="3.776388888888889in"
height="4.317361111111111in"}

6.  The Detail Scale, Left Offset, Right Offset, and Length will be
    automatically defined based on your seed selection.

7.  Follow the prompts at the bottom left of the screen. (What do the
    prompts say? Are they located in the Place Named Boundary window or
    the whole screen?)

8.  Follow the command line in the bottom left side of the screen to
    select **Path Element (Alignment)** and the start and stop location
    of the sheet cuts. (Is the command line the same as the prompts?)

9.  Check **Create Drawing** and **Show Dialog**.

10. The Create Drawing dialog window will display.

![A screenshot of a computer Description automatically
generated](media/image6.png){width="3.56in"
height="5.050393700787402in"}

11. Name the sheet accordingly. (How do you pick a name accordingly?)

12. Check **One Sheet Per Dgn**.

13. Choose where to save the sheet.

14. Check that the remaining settings are correct.

    -   The settings should be pre-populated by the drawing seed.

15. Click **OK**.

16. Sheets will be created

    -   Sheet files have a drawing model and a sheet model. Toggle
        between the two by changing the model view in the lower left of
        your screen. (where?)

17. Annotate sheets as needed in the Sheet Model (white background) of
    the sheet file. (Where? What does this look like?)

\*To access, manage, or reprint the Named Boundaries you have created,
search *Named Boundaries* in the search bar, located in the upper
righthand corner of the screen. This is quicker than clicking on the
tool in the Drawing Production tab. (How would you do this via the
Drawing Production tab?)

[Sheet Setup]: /docs/sheet-setup.md