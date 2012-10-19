grails-changelog
================

Grails plugin

Similar to localizations and database migrations plugins. 
It enables a developer pattern of the following:

- create branch
- fix one or more bugs  or add a feature
- add appropiate change logs as a bug is fixed or refine a change log as a feature is refined
- when ready, merge in master
- update version number
- commit and merge branch into master

Could then have  means of emailing any unemails changes. When you click the button "Email unemailed changelogs", it will 
compile an email, send them to an email or emails specified in the config and mark those change logs as emailed.

