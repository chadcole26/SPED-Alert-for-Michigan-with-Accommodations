# SPED-Alert-for-Michigan-with-Accommodations
Update of Eric Krebill's SPED Accommodations for MI Schools PS SIS Plugin:
https://support.powerschool.com/exchange/view.action?download.id=705

YouTube walk through: https://youtu.be/FQlJK9H0eoQ

This update is significant rewrite of Eric's original plugin.
The original plugin relied on over 60 legacy custom fields most
customers should have updated to table extensions a long time ago. This
was why I had never tried to update it before. There is a distinct 
possibility each distrcit using the original plugin could have unique 
extension fields in use today.

This rewrite breaks the ability to print object reports with the
accommodation data on them. Extensions are not available to use on
object reports.

The rewrite creates a one-to-many extension of the students table. This
allows you to record an unlimited number of accommodations.

Other changes include:
- Added a district setup page where you can select your alert icons
- Added 504 alert separate from SpEd/IEP alert (keys off the state reporting 504 flag)
- Added ability to identify an accommodation as either SpEd/IEP or 504, alert dialogs will show the correct accommodations for the alert type
- Added start and end date
- Added the ability to archive accommodations
- Added tracking features identifying who created the accommodation, who last updated it, and who archived it
- Rewrote the meeting attendance page fragments to use less javascript

This update should also ensure compatibility with PS SIS 21.X and higher.

