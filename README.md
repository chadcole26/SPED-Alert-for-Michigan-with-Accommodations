# SPED-Alert-for-Michigan-with-Accommodations
Update of Eric Krebill's SPED Accommodations for MI Schools PS SIS Plugin:
https://support.powerschool.com/exchange/view.action?download.id=705

This update is significant rewrite of Eric's original plugin.
It relied on over 60 legacy custom fields that most customers should have 
updated to table extensions a long time ago. This was why I had never tried
to update this before. The is a distinct possibility each distrcit using the
original plugin could have unique extension fields in use today.

This rewrite will remove the ability to print object reports with the
accommodation data on them, as extensions are available to object reports.

The rewrite creates a one to many extension of the students table. This
allows you to record an unlimited number of accommodations. I've also
added the ability to archive accommodations, which means the district can
keep a running history of accommodations for as long as the student is
enrolled.
