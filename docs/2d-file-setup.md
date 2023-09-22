---
layout: default
title: 2D File Setup
parent: Project Setup
nav_order: 2
---

# 2D File Setup in OpenRoads Designer
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

This document will guide you through the proper set up of 2D ITD Project files. Proper setup is essential to data management and a project's future success.

Setting up a 2D file is the second step when starting on a new project. The first step is to review our [Pre-Design Resources] and make
sure you understand the fundamental concepts behind the project you're undertaking. Generally, we have one 2D file per discipline: SWPPP, utility, and/or drainage. Which disciplines will require which file will depend on the project. 

2D files are used for SWPPP and utility projects, as well as drainage design files. For creating a 3D file for 3D drainage modeling, see [3D File Setup].

## Creating SWPPP, utility, or drainage design files
***

1.  Navigate to the project in ITD ProjectWise.

    -   The project is usually located in **PWITD** > **Documents** > **District** or **HDR_US_West_01**. You'll be given the appropriate file path and name at the start of the project.

2.  Find the project-specific seed file, usually located in the Design folder or in the Project Resources folder.

    -   The [seed] file, created by the [prime], contain coordinate information. Using this file creates a standard across the project and eliminates any errors in file setup. [ITD] standard line styles, text, and cell libraries will be imported by using the prime's seed file **Always use the seed files created by the prime.**

3.  Right click on the 2D seed file.

4.  Select **Copy**.

5.  Paste the file into the Design folder.

6.  Select **No Wizard** in the pop-up window and continue.

7.  Rename the pasted file to the appropriate convention.

    -   Typical naming convention for SWPPP: `20442_SWPPP_S01.dgn`

    -   Typical naming convention for Utility: `20442_UTIL_S01.dgn`

    -   Typical naming convention for a 3D Drainage file: `20442_DRAIN_S02.dgn`

        -   The letter delineator, here "S", is set by the prime, typically in a CAD Tech memo. This is to show which firm has ownership of each file. S&C typically uses "S" as its delineator. If "S" is unavailable, we default to "C".

    -   Add a description (e.g., SWPPP Design file, Utility Design file,
        2D Drainage Design)

8.  Open the renamed file.

9.  Attach any pertinent reference files. See [Tips & Tricks] for information on referencing. Make sure all references are attached using **Coincident World**.

    -   Typical references for all files:

        -   Topo
        -   Existing Surface
        -   Proposed Surface (often not available in early stages of a project)
        -   Aerial Imagery
        -   Design Files
        -   Alignment

10. Click **Fit View** in the View menu bar.
   
11. Close the file.

## Creating working design files
***

Working files are files that are not yet ready to be available for others to reference or view.

1.  Navigate to the project in ITD ProjectWise.

2.  Navigate to Design > Working > S&C >*Your Working Folder*.

    -   If a Working folder does not yet exist in the Design folder, create it.
        -   To create a new folder in ProjectWise, in the menu bar, click the **Folder** > **New Folder**

    -   Add a folder with your first initial and last name:

    ![](../assets/images/working-directory.png)
    {: .ml-5 }

3.  Find the project-specific [seed] file, usually located in the Design folder or in the Project Resources folder.

    -   The seed files, created by the [prime], contain coordinate information. Using this file creates a standard across the project and eliminates any errors in file set up. [ITD] standard line styles, text, and cell libraries will be imported by the prime's seed file. **Always use the Seed files created by the prime.**

4.  Right click the 2D seed file.

5.  Select **Copy**.

6.  Paste the file into your working Design folder.

7.  Rename the pasted file to the appropriate convention with `_Working.dgn`at the end.

    -   Typical naming convention for SWPPP: `20442_SWPPP_S01_Working.dgn`

    -   Typical naming Convention for Utility: `20442_UTIL_S01_Working.dgn`

    -   Typical naming convention for a 3D Drainage file: `20442_DRAIN_S02_Working.dgn`

        -   The letter delineator, here "S", is set by the prime, typically in a CAD Tech memo. This is to show which firm has ownership of each file. S&C typically uses "S" as its delineator. If "S" is unavailable, we default to "C".

8.  Open the renamed file.

9.  Attach any pertinent references.

    -   Typical references for all files:

        -   Topo
        -   Existing Surface
        -   Proposed Surface (often not available in early stages of a project)
        -   Aerial Imagery
        -   Design Files
        -   Alignment

10. When you are ready to move the file to the Design folder for others to use and reference, remove `_Working` from the end. Right click on the file, select **Cut**, and **Paste** it into the Design folder.

## Archiving files
***

Once you are done with a file, move it to **Design** > **Working** > **S&C** > **Archive**. This will help with data management. Never delete files, always archive them. If an Archive folder doesn't exist yet, create one.

[Pre-Design Resources]: /knowledge-base/docs/pre-design
[3D File Setup]: /knowledge-base/docs/3d-file-setup
[Tips & Tricks]: /knowledge-base/docs/tips-and-tricks
[New Project Setup]: /knowledge-base/docs/new-project-setup
[seed]: /knowledge-base/docs/glossary#seed-file
[prime]: /knowledge-base/docs/glossary#prime
[ITD]: /knowledge-base/docs/glossary#itd