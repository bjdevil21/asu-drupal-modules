# ASU Request for Information Changelog

### ASU RFI 7.x-1.12, 2017-07-17
- Update Lead API Programs URL
- Update Lead API submissions to Lead API 4.0 and handling to support.

### ASU RFI 7.x-1.11, 2018-05-24
- Add RFI-specific jQuery to module instead of Innovation theme
- Fix program name text when email is rendered and sent
- Fix up the changelog

### ASU RFI 7.x-1.10, 2018-05-09
- Amended RFI module logic to better behave with ASU Academic Programs module after switching from ASU Degrees

### ASU RFI 7.x-1.9, 2018-03-15
- Removed ASU Degrees dependency
- Removed ASU Feeds dependency
- Added degree mappings helper function
- Changed degree variables to use degree mappings helper function
- Added initial support for ASU Academic Programs (make sure to
  read the upgrade instructions before applying this update)

### ASU RFI 7.x-1.8, 2017-03-02
- Add missing ->save() calls on the failed lead submission status
  transitioning.
- Fix value used on "action_required" leads to match what's configured.

### ASU RFI 7.x-1.7, 2016-10-15
- Fixing EdPlus API call
- Increased "college_name" size on RFI forms
- Increased text limit for "From" email field
- Updated the auto-response email

### ASU RFI 7.x-1.6, 2016-08-31
- Implemented new location functionality
- Added new Web Standards styling to the forms
- The RFI now supports requests for Online degree information from EdPlus
- Fixed a bug causing a white screen after some graduate submissions
- Fixed the logic behind the Graduate submission routing.

### ASU RFI 7.x-1.5, 2016-07-15
- Fixed a typo in the auto-response email

### ASU RFI 7.x-1.4, 2016-04-15
- Implementing updated email templates for both grad and undergrad submissions
- fixing grad environment check
- Updating queue handling to better prevent duplicate submissions
- Changing the way that the URL is grabbed for submissions

### ASU RFI 7.x-1.3, 2016-04-15
- Adding Salesforce tracking code to the first part of the multistep form.

### ASU RFI 7.x-1.2, 2015-07-27
- Updated module to send message to middleware upon App key request.
— Updated module to show error log message to admins upon form submission failure if the connection between middleware and the form is lost.
- Added “Action require” status term to ASU RFI Submissions cck field.
- Updated the module to send pending submissions to middleware only once and alert site admins of failed submissions.
- Added Google analytics tracking code.
- Enhanced RFI lead submissions view to include search by students email or last name.
- Fixed “uncaught error” message in Jquery file.
- Added CSS to Date of birth modal message box
- Fixed some upper case and lower case field names.

### ASU RFI 7.x-1.1, 2015-05-15
- Updated form mode variable value
- Updated RFI module link settings
- Updated title of ASU RFI settings menu
- Added the ability to add customized confirmation node ids for Grad RFI form and Undergrad RFI form (if both exist in the site) on the admin settings page.

### ASU RFI 7.x-1.0, 2014-11-15
- Initial release
