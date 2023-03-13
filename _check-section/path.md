---
title: Pathology Checks
check-section-id: path-checks
---

| Check           | Description                                                                                                      | Result                                                                                                                                                                          | Version<br><sub>(Available since)</sub> | **Fixable** |
| --------------- | ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------- | :---------: |
| DotNet Runtimes | List DotNet Runtime                                                                                              | Error: Error executing command <br> Fail: Result does not match 'AspNetCore.App 6.0' and 'NETCore.App 6.0' <br> Pass: Result matches 'AspNetCore.App 6.0' and 'NETCore.App 6.0' | v1.5                                    |   **No**    |
| WebSockets      | <details><summary>Check for the following Cluster features: </summary><ul><li>Web-WebSockets</li></ul></details> | Error: Error executing command <br> Fail: if one or more required features report as 'Available' <br> Pass: all required features report as 'Installed'                         | v1.6                                    |   **Yes**   |