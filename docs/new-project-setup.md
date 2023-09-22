---
layout: default
title: New Project Setup
parent: Project Setup
nav_order: 1
---

# New Project Setup
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

This page is a resource for setting up a new project. For new projects, you'll need to set up the [plan sheets], [container file] (also sometimes called the zbase file), and the [border file].

## Create a new S&C Plan Sheet folder and copy plan sheets in
***

1.  Navigate to the project in ProjectWise

2.  Find the Plan Sheets folder for the project (**Project Development** > **Plan Sheets**)

3.  Create a new folder in the Plan Sheets folder called **S&C** (if one doesn't already exist)

4.  Locate the [prime]'s plan sheets, copy them, then paste them into the S&C folder.

    -   The prime's plan sheets will be in the folder with the prime's name and should be called something like `xxxx_plan_001.dgn`

5.  Right-click the first copied file in the S&C folder, then select **Properties...**

6.  On the General tab, change the Document Name to the swpp convention: `xxxx_swpp_001.dgn`

    -   The xxxx is the project number, which is left the same, and the 001 is the file number, which is also left the same. Project plan sheet file names may vary from project to project.

7.  Update the description to include "SWPP".

    -   For example, if the original description is "Plan Sheet," update it to "SWPP Plan Sheet"
    
    {: .note}
    You can select multiple files at the same time, then right click. Select **Modify**, then change the description for all the files to "SWPP Plan Sheet". This will change the description for all the files at once.

8.  Click **Save**

9.  Click **>** to proceed to the next file.

10. Follow steps 6 - 9 for the rest of the plan sheets in the S&C folder.

## Create a new SWPP border file and container file
***

1.  Locate the prime's border file, then copy it (right click > **Copy**).

2.  Paste the border file into the S&C plan sheet folder

3.  Right click the border file, then select **Rename**

4.  Rename the file to something like `SWPP_border.dgn`

5.  Locate the prime's [container file], then copy it (right click > **Copy**)

    -   Container files are sometimes referred to as Zbase files

6.  Paste the container file into the S&C plan sheet folder

7.  Right click the container file, then select **Rename**

8.  Rename the file to something like `xxxx_swpp_cf.dgn`

    -   Xxxx would be the project name

## Update the sheet plans to reference the border file & container file
***

When you first open the plan sheet file, it may take a long time to load. It will also include all the references and bubble call outs from the original prime version of the file. You'll need to replace the prime's [container file] and [border file] references with the new swpp
versions of them, and then detach all the other references. Then, you'll want to clean up the bubble call outs, leaving only the annotations that are relevant to SWPPP work. Finally, you'll want to create a new saved view called "SWPP".

1.  Open the first plan sheet file.

2.  Detach all the references except the original border file and the original container file.

    -   In the Level Display pane, right click the reference you want to detach, then select **Detach**

3.  In the References pane, double click the border file reference to bring up the Attachment Properties dialog.

4.  Select **Browse** next to the File Name

5.  Navigate to the border file in the S&C plan sheet folder and select **Add**, then **Open**

6.  Delete any text in the Logical Name text field

7.  Click **OK**

8.  Follow steps 2-7 for the container file, making sure to browse to the new container file in the S&C folder.

## Create saved view
***

1.  Remove any bubble call outs and annotations that aren't relevant to the SWPPP sheets.

    -   Generally, we only want to keep road names, begin & end construction annotations, and township and range annotations (will look something like T.3N, R.18E, B.M.).

2. Create a saved view by going to **Drawing Production** > **Create Saved View**

3. Set the Method to "From 2-Points", View Type to "General, Name to "SWPP", and Clip Volume to "(From View)"

    -   Leave Description, Create Drawing, and Associative blank

4. Select the top left corner of the cut-sheet box, then select the lower right corner.

    -   The Information center (bottom left of screen) will say "Saved View "SWPP" Created" to confirm.

    -   You can also use the key-in `namedview create 1 SWPP` 

5. Close and Check In the file, then repeat the above steps for the rest of the swpp plan sheets.

## Update the border file
***

1.  Open the border file in ProjectWise

2.  In the References pane, select **Tools** > **Attach**

3.  Navigate to a border file from a recent project and select **Add**, then **Open**

    -   You'll use the previous border file to copy-paste some elements into the new border file

4.  Copy-paste all the elements you want in your new border file.

    -   Usually, you'll want to keep the Notes, Legend, Names, Drawing Date, S&C Associates title, Project No., Project Name, Stationing, preliminary stamp, Sherri's stamp, and the bubble call outs/ boneyard elements outside the border.

    -   To copy, highlight the elements you want to copy, then select **Drawing** > **Manipulate** > **Copy** from the Ribbon. Click, then click again to copy the element into the exact same location.

    -   Turn the reference border file display on and off (in Level Display, right click the reference, then click **Display**) to verify you have everything in your current border file.

5.  Once you have the border file set up, turn the reference display off.

6.  Close and Check In the file.

## Set up the print set (pset) for the project
***

Follow the steps in [Pset Creation].

[Pset Creation]: /knowledge-base/docs/pset-creation
[plan sheets]: /knowledge-base/docs/glossary#sheet-file
[container file]: /knowledge-base/docs/glossary#container-file
[border file]:/knowledge-base/docs/glossary#border-file
[prime]: /knowledge-base/docs/glossary#prime
