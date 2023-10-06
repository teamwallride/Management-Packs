# Purpose

Collects SCOM update rollup information.

# Enhancements

# Bugs

- 2016 Gateway versions need to be fixed, the files are updated inconsistently. Use this to get versions:

(Get-ItemProperty -Path "C:\Program Files\System Center Operations Manager\Gateway\HealthService.dll").VersionInfo.fileversion

(Get-ItemProperty -Path "C:\Program Files\System Center Operations Manager\Gateway\MOMWsManModules.dll").VersionInfo.fileversion


