---
title: Sectra Monitoring Checks
check-section-id: sms-checks
---

| Check           | Description                                                                                                                        | Result                                                                                                                                                                                                                                   | Version<br><sub>(Available since)</sub> | **Fixable** |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------: | :---------: |
| Access to smglobal | Check access to https://sm-global-1.sectra.com/sm/                                                                                                                | **Fail:**&nbsp;&nbsp;&nbsp;&nbsp;Error executing command or null result <br> **Pass:**&nbsp;&nbsp;Result Status Code matches '200'(HTTP Status Code OK) |                  v1.10                   |     No      |
