---
title: Modal
description: The modal component is used to overlay an area of the screen with a
  prompt, dialogue or interaction and prevents users from interacting with
  content outside of it until it’s closed.
author: Juan Ruitiña
date: 2024-04-11T09:55:51.210Z
status: Draft
tags:
  - created
---
<!-----

You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 5

Conversion time: 2.561 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β35
* Thu Apr 11 2024 02:56:29 GMT-0700 (PDT)
* Source doc: Modal - UX/design spec
* Tables are currently converted to HTML tables.
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server. NOTE: Images in exported zip file from Google Docs may not appear in  the same order as they do in your doc. Please check the images!


WARNING:
You have 5 H1 headings. You may want to use the "H1 -> H2" option to demote all headings by one level.

----->


<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 1; ALERTS: 5.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>
<a href="#gdcalert2">alert2</a>
<a href="#gdcalert3">alert3</a>
<a href="#gdcalert4">alert4</a>
<a href="#gdcalert5">alert5</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>



# Modal spec


[TOC]



# 


# Overview

The modal component is used to overlay an area of the screen with a prompt, dialogue or interaction and prevents users from interacting with content outside of it until it’s closed. 


# General Usage


## When to use



* To prevent or correct critical errors;
* To request information critical to continuing the current process;
* To ask information that could significantly lessen users’ work or effort;
* To reveal relevant information or contextual information;
* To expand media assets.


## How to use



* The modal title should tell users what the modal is about;
* Try to match the primary button text with the modal window title to make it easier for users to understand the context;
* Be mindful of the modal’s length, avoiding the use of a scrollbar - if it has a lot of content consider a regular page or other alternatives instead.


## When not to use



* For information that is not related to the current page/flow;
* To interrupt processes. I.e. checkout flows;
* When the user requires additional information unavailable in the modal;
* When the user can proceed with their flow _without _the interruption. Use only when a modal is absolutely necessary.
* To show error, wait, or success states - use the notifications component instead;
* To show contextual information that can be displayed in a panel or less disruptive components.


## Behaviour


### Opening the modal

A modal can be opened by clicking:



* Call-to-action buttons
* Text links
* Media assets such as images and videos
* A modal can be triggered by a system event, for example “Do you really wish to leave this page? Your changes will be lost.”


### Active

When a modal is active, the main content is disabled until the user interacts with the modal dialogue or the close button (if available). 

A  scrim will appear between the main content and the modal to convey that the rest of the page is disabled and so the focus is on the modal


### Close

A modal can be dismissed by:



* Clicking the close button (if available)
* Interacting with the dialogue (if available)
* Pressing the keyboard Escape key if the modal can be ignored.


# Variants 


## Overview


<table>
  <tr>
   <td>Variants
   </td>
   <td>Description
   </td>
   <td>Configurations
   </td>
  </tr>
  <tr>
   <td rowspan="2" >A) Content view
   </td>
   <td rowspan="2" >To read text or view media assets.
<p>
Disables the main content until the user clicks on the close icon to return to the underlying page.
   </td>
   <td>Title
   </td>
  </tr>
  <tr>
   <td>No title
   </td>
  </tr>
  <tr>
   <td rowspan="4" >B) Dialogue
   </td>
   <td rowspan="4" >Requires user interaction. \
Disables the main content until the user interacts with the modal dialogue or the close button (if available).
   </td>
   <td>Close button
   </td>
  </tr>
  <tr>
   <td rowspan="3" >No close button
   </td>
  </tr>
  <tr>
  </tr>
  <tr>
  </tr>
</table>



## Variant A - Content view


### Definition

Use the content view modal to reveal relevant or contextual information or to expand images or view media assets.


### Configurations


#### Title


##### Desktop



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")



##### Mobile


#### No title


##### Desktop



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")


<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")



##### Mobile


## 


## Variant B - Dialogue


### Definition

Use the dialogue modal to request information or actions from the user.


### Configurations


#### No close button

To close this configuration, the user must select an action. 


##### Desktop



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")



##### Mobile


#### Close button

When displaying the close button, make sure it is clear what it will do to avoid ambiguity between close and the action button(s). To clarify the close button intent, consider having a tooltip confirming the action.


##### Desktop



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")



##### Mobile


# References



* [UX Planet - Best Practices For Modal Window Design](https://uxplanet.org/best-practices-for-modal-window-design-627f7aba57f1) (Nick Babich, 2021)
* [NN/g - Modal & Nonmodal Dialogs: When (& When Not) to Use Them](https://www.nngroup.com/articles/modal-nonmodal-dialog/) (Therese Fessenden, 2017)
* [Cancel vs Close: Design to Distinguish the Difference](https://www.nngroup.com/articles/cancel-vs-close/) (Aurora Harley, 2019)
* [Material Design - Dialogs component](https://material.io/components/dialogs) (Google)
* [Carbon Design System - Modal component](https://www.carbondesignsystem.com/components/modal/usage/) (IBM)