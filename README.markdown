#Java-Zangle-API

This is the project for the Java Zangle API written in Java.

Depends on the latest version of JSoup.

## Changelog

* Version 1.55 BETA
    * Fix login detection
    * Fix timeout detection
    * Remove more legacy code

* Version 1.50 BETA
    * Use JSoup for much quicker and cleaner parsing
    * Updated parsing for the newest version of Zangle/MiStar/StudentConnection
    * Cleaned some code

* Version 1.05 BETA
    * Added getPercent() function for classes to get students current     percent in the class.
    * Added isExtraCredit and isNotGraded methods for ZAssignment class.
    * Added getPercent and setPercent for assignments.
    * Updated update() method in ZangleConnections.  Now refreshes session data automatically if expired.
    * Added new method in ZangleConnections. isLoggedIn(), checks if the user is actually logged in with VALID session data
    * Code optimizations and cleanup