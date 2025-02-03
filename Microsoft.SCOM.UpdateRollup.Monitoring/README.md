# Disclaimer
Use this management pack at your own risk. I accept no responsibility if it causes damage.

# Summary
Shows update rollup information for these SCOM versions:

  * 2012 R2
  * 2016
  * 1801
  * 2019

# Improvements

  * Track hotfixes/patches released in between URs? 2019 is a good example.
  * Need a way to identify SCOM 2019 ACS URs as they are .sql files.

# Bugs

# Links

[SCOM Build Versions](https://thesystemcenterblog.wordpress.com/scom-build-versions)

# Versions

  * 2025.2.3.4 - 2019 update rollups completed.
  * 2025.1.31.0 - Redo 2019 reporting patch section to use a single file.
  * 2025.1.28.0 - Multiple fixes:
    * $ReportServerVersion returning blank for some versions, moved to line before switch statement.
    * Incorrect $ReportServerVersion version for 2019 RTM. Changed from 10.19.1032.0 to 10.19.10050.0.
  * 2024.3.14.0 - Initial release.
