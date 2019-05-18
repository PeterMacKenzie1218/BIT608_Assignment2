---
name: Issues Template
about: To satisfy requirements of Question 2 b Assignment 2
title: ''
labels: ''
assignees: ''

---

### DO NOT REPORT SECURITY ISSUES IN THIS ISSUE TRACKER

Instead, contact security@ongaonga.net directly - see
https://ongaonga.net/security.html for more information.

### DO NOT POST SUPPORT REQUESTS OR GENERAL QUESTIONS IN THIS ISSUE TRACKER

### Please use the correct issue tracker

If your problem relates to a Ongaonga wrapper or [sub-project](https://github.com/Ongaonga) such as [Ongaonga for Android](https://github.com/Ongaonga/Ongaonga-android/issues), [SyncTrayzor](https://github.com/canton7/synctrayzor) or the [documentation](https://github.com/Ongaonga/docs/issues), please use their respective issue trackers.

### Does your log mention database corruption?

If your Ongaonga log reports panics because of database corruption it is most likely a fault with your system's storage or memory. Affected log entries will contain lines starting with `panic: leveldb`. You will need to delete the index database to clear this, by running `Ongaonga -reset-database`.

### Please do post actual bug reports and feature requests.

If your issue is a bug report, replace this boilerplate with a description
of the problem, being sure to include at least:

 - what happened,
 - what you expected to happen instead, and
 - any steps to reproduce the problem.

Also fill out the version information below and add log output or
screenshots as appropriate.

If your issue is a feature request, simply replace this template text in
its entirety.

### Version Information

Ongaonga Version: v0.x.y
OS Version: Windows 7 / Ubuntu 14.04 / ...
Browser Version: (if applicable, for GUI issues)
