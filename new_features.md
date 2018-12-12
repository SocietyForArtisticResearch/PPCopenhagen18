---
title: "New RC Features"
author: Döbereiner/Schipper
date: December 13, 2018
transition: fade
---

# PHP 7 Upgrade

* Upgrade of all code from PHP 5
* Increase of loading speed of administration pages (user list  8s vs 47s)
* Editing and creating tools is significantly faster
* Expositions loading time ca. 1/3
* Code cleanup


# Source Code Availability

* Up-to-date source code is available 
* https://www.researchcatalogue.net/docu/researchcatalogue.zip
* Github: <https://github.com/SocietyForArtisticResearch>
* Development blog: <https://societyforartisticresearch.github.io/rcblogpublic/>


# Web Analytics

* One designated admin per portal has access to statistics
* Total visits
* Visits by Exposition
* Average visit duration
* Visits by country
* <https://monitoring.researchcatalogue.net>

# Sharing Link


# HTML Import

* Expositions can created directly using HTML/CSS and uploaded
* Allows for multiple pages
* Filtering of potentially dangerous content (no *JavaScript*)
* Automatic transcoding of media content
* Upload as a single zip-File


# Responsiveness of RC Pages

* Main RC pages are now responsive 
* Front page, profile page, details page 
* <https://researchcatalogue.net>


# Search

* Findability: Search for authors, titles etc. will return associated objects.
* Seach results can be exported as JSON 
* Results can thus be processed
* example : <https://www.researchcatalogue.net/view/496747/496748>

# User Management

* Users can be removed from the portal but not deleted by the admin
* Admins can create reviewer accounts that are automatically confirmed
* "Members of" list is no longer displayed on public profile
* <https://www.researchcatalogue.net/admin/user/list?context=26>


# Text-Editor Fixes and Updates

* Captions
* Saving/Loading
* Warning when deleting media items
* Preview of missing media
* Appending of imported documents


# 4K Video Import

* this used to be turned off, but is now allowed.

# Dealing with Autoplay

* Safari is blocking auto play by default.
* There was no warning for the reader that something was blocked.

## We now catch this situation and:
* when audio/video is blocked the user is prompted to start playback manually.


