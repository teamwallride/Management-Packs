# Purpose

Collects update rollup info.

# Enhancements

- Change 'Agent MG Failovers' to just show mgmt group names. Currently, if there's too many it gets cut off. We can use other scripts to show agent failover.
- Add to daily report a table showing top 10 list of servers with low disk space.
- Add event monitor for SCOM.Rule.DailyReport.
- Add agent load balance script (code in TFS) as task? 
- Add the word Rule/Monitor to custom field so Operators know what type of alert it is?

# Bugs

- ACS Collectors state view is wrong. It's showing '%\% console install directory'.