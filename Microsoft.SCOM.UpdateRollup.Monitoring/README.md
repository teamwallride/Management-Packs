# Purpose

Collects SCOM update rollup information.

# Enhancements

- Add [this?]( https://support.microsoft.com/en-us/topic/update-for-idor-vulnerability-in-system-center-operations-manager-kb5006871-0e3a513a-ad80-4830-8984-2fc5a40ee7f7)

# Bugs

- 2016 Gateway versions need to be fixed, the files are updated inconsistently. Use this to get versions:

(Get-ItemProperty -Path "C:\Program Files\System Center Operations Manager\Gateway\HealthService.dll").VersionInfo.fileversion

(Get-ItemProperty -Path "C:\Program Files\System Center Operations Manager\Gateway\MOMWsManModules.dll").VersionInfo.fileversion


