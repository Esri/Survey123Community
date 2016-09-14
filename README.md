
While the Survey123 team still looks from time to time to this Github repo, we have moved into the [Survey123 GeoNet Group](https://geonet.esri.com/groups/survey123). In there you will find:
- A User Forum where you can ask technical questions and report  issues. We do our best to monitor activity daily.
- A Blog with lots of information about  using Survey123. 
- Video Tutorials

We keep this repo around because a ton of info that we do not want to lose and also because some people still come back here to report issues. Again, we still look into this repo, but if you want decent response times it is best  you use the [Survey123 GeoNet Group](https://geonet.esri.com/groups/survey123)

# Basics #

Video Tutorials on Survey123 available here: https://links.esri.com/survey123/videos/overview 

To get started navigate to http://survey123.esri.com and login with your ArcGIS Online credentials

1) Ask Questions: Download the Survey123 Connect tool into your Desktop to transform your own XLSForms into ArcGIS Surveys. In the Survey Gallery at survey123.esri.com, click on Create New Survey to access Survey123 Connect.

2) Get the Facts from the field: Share your Surveys with people in your organization. Ask folks in the field to download the Survey123 app and the Survey/s shared with them. The app is available in the google play and apple app stores. There are also downloads available for Windows and Macs.

3) Make better decisions: As people submit data from the field, you will be able to analyze it in Survey123.esri.com or with any ArcGIS tools.

Some more tips available at [our blog](https://geonet.esri.com/groups/survey123/blog): 

## Update (11-04-2016) ## 

Survey123 Field App (Build 1.3.38) Survey123 Connect (Build 1.3.18) International Children's Book Day 

Fixes
- https://github.com/Esri/Survey123Community/issues?utf8=%E2%9C%93&q=milestone%3A%22International+Children%27s+Book+Day+%28April+2%29%22+
___________________________________________________________________________________________________________________

## Update (09-03-2016) ## 

Survey123 Field App (Build 1.2.89)  International Women's Day (Hot Fix)

Fixes
- https://geonet.esri.com/groups/survey123/blog/2016/03/09/1289-critical-update-to-the-survey123-mobile-app
___________________________________________________________________________________________________________________

## Update (03-03-2016) ## 

Survey123 Field App (Build 1.2.82)  International Women's Day

Fixes
- https://geonet.esri.com/groups/survey123/blog/2016/03/04/international-women-s-day-release
___________________________________________________________________________________________________________________

## Update (02-02-2016) ## 

Survey123 Field App (Build 1.2.49)  Valentine's Day

Fixes
- https://github.com/Esri/Survey123Community/issues/234 (Boost Survey Loading Time)
- https://github.com/Esri/Survey123Community/issues/277 (Preview Map iOS only)


___________________________________________________________________________________________________________________

## Update (01-06-2016) ## 

Survey123 Field App (Build 1.2.19)  Three Wise Men Day

NEW FEATURES
- https://github.com/Esri/Survey123Community/issues/127 (Enable copy-paste on sign-in dialog)
- https://github.com/Esri/Survey123Community/issues/114 (Support offline basemaps)
- https://github.com/Esri/Survey123Community/issues/70  (Support offline basemaps)


___________________________________________________________________________________________________________________

## Update (08-09-2015) ## Hotfix

Survey123 Connect (Build 1.1.4)  

FIXES:
- https://github.com/Esri/Survey123Community/issues/167 (Relevant expressions no longer working in Connect 1.0.158)
- https://github.com/Esri/Survey123Community/issues/166 (Required not working on Signature questions. Note: Fix to the app planned for October 1st release) 

NEW FEATURES:
- This update includes a first implementation of Cascading Selects and Repeats. 
- To test Cascading selects and repeats in the app it is necessary to install the beta version from HockeyApp (requests to join beta program must be sent to survey123@esri.com).
- Support for cascading selects and repeats is planned to be made available in October 1st update.

___________________________________________________________________________________________________________________

## Update (31-08-2015) ## Random Acts of Kindness Day

Survey123 Connect (Build 1.0.158)  

FIXES:
- https://github.com/Esri/Survey123Community/issues/158 (You can now run Survey123 Connect in Windows 10)
- https://github.com/Esri/Survey123Community/issues/143 (Solved issues using Survey123 Connect through proxy servers, causing XLSForm Conversion Failed errors)
- https://github.com/Esri/Survey123Community/issues/139 (You can now create surveys using special characters in the name)  

Survey123 app

All new features planned for this milestone have been pushed into the next (National Bison Day on October 1, 2015). This includes: Cascaded Selects, Windows Phone 8 and 8.1 support.  Support for XLSForm Repeats continues to be planned for the October 1st update.

KNOWN ISSUE:
- Relevant expressions are not being honoured in the form preview in Survey123 Connect. Relevant expressions are still honoured as expected in the Survey 123 app. Note: This issue is fixed in Connect 1.1.4 (see update 08-09-2015)

___________________________________________________________________________________________________________________

## Update (30-07-2015) ## International Beer Day Milestone

Survey123 app (Build 1.0.171)  

FIXES:
- https://github.com/Esri/Survey123Community/issues/126
- https://github.com/Esri/Survey123Community/issues/111
- https://github.com/Esri/Survey123Community/issues/130

NEW FEATURES:
- https://github.com/Esri/Survey123Community/issues/42

Survey123 Connect (Build 1.0.143)  

FIXES:
- https://github.com/Esri/Survey123Community/issues/131
- https://github.com/Esri/Survey123Community/issues/58
- https://github.com/Esri/Survey123Community/issues/105
- https://github.com/Esri/Survey123Community/issues/132
- https://github.com/Esri/Survey123Community/issues/122
- https://github.com/Esri/Survey123Community/issues/80
- https://github.com/Esri/Survey123Community/issues/111

NEW FEATURES:
- You can now define the exact mapping of your question to esri field types using the new bind::esri:fieldType and bind::esri:fieldLength columns. More details in this [blog post](https://geonet.esri.com/groups/survey123/blog/2015/08/24/xlsform-mappings-to-arcgis-feature-services-an-introduction)
- Enhanced XLSForm support
  - username: this question type will automatically capture the name of the person logged in to the Survey123 app. It is similar to what you get with Editor Tracking... but it is handy to have this one when working with ArcGIS Server secured services used through a proxy with embedded credentials.
  - email: similar to username, but captures the email associated with the person logged in (as obtained from the ArcGIS profile)
  - start and end are two new types of XLSForm question types that we now support. They capture the time when the user opens the form (start) and when the form is flagged as ready to be submitted (end). These two questions are useful to better understand when the data is captured and how much time people are spending on every form submission. 
  - A bit more about these new questions is discussed in [this blog post](https://geonet.esri.com/groups/survey123/blog/2015/08/24/keeping-track-of-when-where-and-by-whom-data-is-captured)
  - hidden: this new type of question is useful when you want to use Connect to add additional fields into your feature service, but you do not want these fields to show in the Survey. You will typically use this type of question in combination with the columns bind::esri:fieldType and bind::esri:fieldLength.
  - signature: The [signature appearance](https://geonet.esri.com/groups/survey123/blog/2015/08/23/signatures) in image fields allows you to capture signatures from respondents.

___________________________________________________________________________________________________________________

## Survey123 Connect Update (30-06-2015) ## Tartan Day Milestone

Survey123 Connect (Build 1.0.118)  

This minor update addresses the form conversion errors described [in this thread](https://github.com/Esri/Survey123Community/issues/117). This is an issue that affected a few users running Survey123 Connect in environments with strict network rules.
If you ever run into these issues before, after installing the update please select the settings icon next to the version number of Survey123 Connect in the bottom-left corner. The Survey123 REST API URL should be set to https://survey123.esri.com/api. If not, delete the current entry, then close and open Survey123 Connect to get the new default setting. 
___________________________________________________________________________________________________________________

## Update (29-05-2015) ## Children's Day Milestone

Survey123 (Build 1.0.144)  
- UI scaling improvements.
- Workflows changed to be more email-like (Drafts, Outbox, Sent).
- Ability to delete draft surveys added.
- Passwords now saved for easier sign-in.
- HTML formatting supported in labels. 
- Size in Android is now 15Mb. In iOS is around 50Mb.

Survey123 Connect (Build 1.0.108)
- Specify form submission name supported (see http://xlsform.org/#instance-name).
- Ability to set map display units.
- General bug fixes.
 
___________________________________________________________________________________________________________________

## Update (22-05-2015) ##

Survey123 (Build 1.0.131)  
Survey123 Connect (Build 1.0.95)
- Calculate fields supported.
- Date fields displaying correctly in survey snippets.
- General bug fixes.

___________________________________________________________________________________________________________________

## Update (15-05-2015) ##

Survey123 (Build 1.0.124)  
Survey123 Connect (Build 1.0.89)
- Read-only support for geopoint fields. WIll display location on the map, but location cannot be captured manually. 
- UI scaling improved on high resolution devices.
- General bug fixes.
 
___________________________________________________________________________________________________________________

## Update (05-05-2015) ##

Survey123 (Build 1.0.114)  
- Select ones are now legible in Android if you use an appearance setting 
- Look and feel of the app has changed (a work in progress still)
- Location is now captured automatically as long as your device provides location. If you have a geopoint question, your location becomes the default for that question. If you have no geopoint question, we capture the location anyways.
- The map control now includes a basemap switcher (supports tiled services from ArcGIS Online, ArcGIS for Server as well as OpenStreetMap)
- Compact appearance for select_multiple fields improved
- Improved support for Image type of questions
 
Survey123 Connect (Build 1.0.81)
- You can now update a survey without having to delete the underlying feature service
- More options added so you can set the default basemap, the color scheme of your survey as well as a snippets


___________________________________________________________________________________________________________________

## Update (01-05-2015) ## May Day Milestone

Survey123 (Build 1.0.88)  
- Select Basemap in GeoPoint Control
- UI Improvements
 
Survey123 Connect (Build 1.0.75)
- UI Improvements
- Settings Tab allows you to set General, Display, Style, Map and Data options e.g.,
  - Set Form and Text Colors
  - Set Default Basemap and Basemap Extent
  - Set Form Background

Survey123 Web Site
- Updated XLSForm compatibility help page
- Added quick links in the Survey Gallery to the blog, community and installers for the Survey123 App and Connect

Other
- Works better when working behind a proxy


___________________________________________________________________________________________________________________

## Update (01-04-2015) ## Fools day Milestone

Survey123 (Build 1.0.83)  
Survey123 Connect (Build 1.0.65)

- Survey123 web site:
  - Quick links to download Survey123 Connect available in the Survey123 web site. Log in and look at the bottom.
  - Minor usability fixes.
- Survey123 App:
  - Delete functionality added. Select a survey to find a 'Delete' option in the menu.
  - Minor usability fixes. 
- Survey123 workflows now are compatible with ArcGIS Online organizations set to work over https only.
  - Note that SAML\Enterprise users are not supported in ArcGIS Online. You will only be able to work with built-in users.
- Survey123 workflows are compatible with Portal for ArcGIS 10.3.1. Specify your portal address in the 'Sign In' dialog to point Survey123 at your ArcGIS Portal.
  - Note that only token based authentication is supported. No IWA, PKI or oAuth are supported at this moment.
  - Support is limited to Portal for ArcGIS 10.3.1 configured with the ArcGIS Data Store.

___________________________________________________________________________________________________________________

## Update (02-04-2015) ##

Survey123 (Build 1.0.79)  
Survey123 Connect (Build 1.0.60)

-  Improved scaling of text and buttons for the Review Completed Survey messages

___________________________________________________________________________________________________________________


## Update (31-03-2015) ##

Survey123 (Build 1.0.64)  
Survey123 Connect (Build 1.0.60)

- Number fields on iOS are will use the standard keyboard instead of the numeric keyboard. Unlike the numeric keyboard, this keyboard has the ability to be dismissed.

- Improved scaling of text and buttons for the following:
  - Constraint messages
  - Required Fields messages
  - Cancel Survey messages
  - Save Draft messages
  - Complete Survey messages
 
- Option to begin a new survey added when leaving the current survey (Save Draft, Completed Survey & Cancel Survey).

- ComboBox has no initial selection if default value has been set. 

___________________________________________________________________________________________________________________

## Update (27-03-2015) ##

Survey123 (Build 1.0.61)

- Calendar Widget / Date Picker closes after date is selected 
- Improve regex handling for Relevant and Constraint fields
- Images are honoring Relevant expressions
- Sign In dialog reporting errors correctly

Survey123 Connect (Build 1.0.59)

- Browse to import existing spreadsheet added to New Survey menu
- When publishing a survey, you can choose to publish a WebMap
- When publishing a survey, you can choose to use labels as field alias names
- When publishing a survey, you can choose to enable Editor Tracking
- When publishing a survey, you can choose to create domains from survey choices
- Sign In dialog reporting errors correctly

___________________________________________________________________________________________________________________

## Update (19-03-2015) ##

Survey123 (Build 1.0.52)  
Survey123 Connect (Build 1.0.41)

- Small icons on Android are now resizing correctly
- Image fields are honoring relevant constraints as expected
- Text color legibility issue on Android fixed
 

___________________________________________________________________________________________________________________

## Update (27-02-2015) ##

Survey123 (Build 0.0.42)

Favorites:
Mark a set of answers as a favorite using the menu on the top right of the survey form. Once you have a favorite, use the same menu to paste the answers into a new survey. If you have already provided answers, they will not be overwritten by the paste. Your favorite survey will be saved in your Review list.

Submitted Surveys:
Submitted surveys are now automatically deleted from your device (unless they are set as the favorite).

Survey123 Connect (Build 0.0.39)

Defaults:
Use the default column in your spreadsheets to define the default values for your survey questions. Use today() in date fields to default to today's date. Use a comma separated list for more than one default value for multiple_select fields.

Required Fields:
Put a value of 'yes' in the required fields column of your spreadsheet to ensure a question is answered before it is submitted. If required fields are empty, the survey can only be saved as a draft, not completed.

Survey 123 Webpage:

Download CSV:
Locations are correctly exported to CSV.
