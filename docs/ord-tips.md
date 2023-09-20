---
layout: default
title: ORD Tips
parent: Tips & Tricks
nav_order: 2
---

# ORD Tips and Tricks
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

This document covers the basics of the ORD tools and features we most commonly use at S&C.

## Attaching reference files

To add a reference file:

1.  Click the dropdown arrow on **Primary** > **Attach Tools** icon: 

![](/assets/images/attach-tools.png)

2.  Click **References**

3.  In the dialog box, go to **Tools** (in the menu) > **Attach**

    -   If the file you're looking for isn't there, try changing the file selection from ".dgn" to "all documents".

4.  Make sure all references are attached using **Coincident World**

    -   Coincident World keeps the coordinate system set in the seed file.

5.  Typical references for all files:

    -   Topo
    -   Existing Surface
    -   Proposed Surface (often not available in early stages of a project)
    -   Aerial Imagery
    -   Design Files
    -   Alignment

## Using the ribbon search bar

The ORD ribbon search bar is a powerful tool that makes finding tools and dialogs easier.

-   You can quickly access the search bar by pressing F4.
-   Search for terms in the text box or use the dropdown arrow to view
    your recent searches.
-   Hover over search results to see the location of the search result
    item in the ribbon.

## Levels

A "level" defines different layers or sections within a design, such as road surfaces, subgrades, utilities, and structures. 

Toggle the Level Display on or off with the Level Display icon: ![](/assets/images/level-display.png)

Or use the ribbon search bar to search for "Level Display."

### How to display a level

1.  Navigate to the Level Display pane.

2.  Right click the level you want to display.

3.  Check **Display**:

    ![](/assets/images/display.png)

    - Displayed levels will appear black in the Level Display pane while levels that aren't displayed will be grey.

### How to create a new level

1.  Right click anywhere in the Child Level box, then click **Level Manager**:

    ![](/assets/images/level-manager.png)
    
2.  Click **Levels** > **New** or the New Level icon: 

![](/assets/images/new-level.png)

### How to view and change the level of an element

1.  To view the level of an element, click the element, then hover over it to see information about the element.

2.  To change the level of an element, go to **Properties** > **General**, click **Level**, then select the new level from the dropdown: 

![](/assets/images/level-properties.png)

### How to set a level as active

1. Double-click the level to turn it from blue to green. 

2. Alternatively, right click the level, then click **Set Active**.

## Working with arrows on basin delineations

Use arrows to demarcate water flow directions and identify whether a basin is a shed or crown.

### Placing a new arrow

1.  Go to **Drawing** > **Placement** > **Place Active Cell** ![](/assets/images/place-active-cell.png)

2.  In the Place Active Cell dialog box, click **...** next to the Active Cell text box: ![](/assets/images/active-cell-name.png)

3.  Click **Display All Cells**

    ![](/assets/images/display-all-cells.png)

4.  Find the cell library with the straight and wavy arrow cell.

5.  Place the arrow on the appropriate level in the Plan view.

### Moving arrows

Arrows should be placed perpendicular to the contour lines. To move an arrow: 

1. Select the arrow 

2. In the ribbon (or use Search), click **Move** or **Copy** 

3. Place the arrow on a contour line

4. In the ribbon (or use Search), select **Rotate**

5. In the Rotate properties pane, set the **Method** to 3 points

6. Click the center of the arrow you want to rotate, then click somewhere outside the arrow

7. Then, use your mouse to rotate the arrow so it's 90° perpendicular to the contour line

## Find and Replace Text

Use Find and Replace to replace text in a file with something else.

1.  Navigate to the ribbon search bar and search for "replace."

2.  Select **Find/ Replace Text**

3.  Enter the term you want to replace in the Find text bar

4.  Enter the term you want to replace it with in the Replace text bar.

    ![](/assets/images/find-replace.png)

5.  Click **Replace All**

    -   Note that this will replace all the instances of the text in the file. If you only want to replace the text in a certain element or portion of the file, be sure to highlight the area you want to replace text in (multi-select by holding the left mouse button down and dragging from the lower right hand corner).

## Fixing Broken Associations

If the arrows on your seeding/ wattle bubbles are appearing as dashed lines, you may need to uncheck the Highlight Broken Associations option:

1.  Navigate File > Settings > Operation

2.  Uncheck **Highlight Broken Associations**

## Finding URN address in ProjectWise

1.  In ProjectWise, highlight the file you want the URN for

2.  In the Address bar, right click the file name

3.  Select **Copy URN**

## Troubleshooting Axis Lock

If elements seem like they're stuck on an x-y axis when you're moving them, you might have to turn off Axis Lock for the file:

1.  Navigate to File > Settings > File > Design File Settings

2.  Click **Axis**

3.  Uncheck **Axis Lock**
