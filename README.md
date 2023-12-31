Common kernel fragments for Droidian adaptations
================================================

This repository contains common kernel fragments for Droidian
adaptations

| Kernel version | Branch                |
|----------------|-----------------------|
| 4.14           | `4.14-android`        |
| 4.19           | `4.19-android`        |
| 5.10-android12 | `5.10-android-common` |
| 5.10-android13 | `5.10-android-common` |
| 5.15-android13 | `5.15-android-common` |

To avoid duplication, the GKI common branches are valid for multiple
Android feature kernels (e.g. both `5.10-android12` and `5.10-android13`
share the same `5.10-android-common` branch).

Eventual feature-kernel specific configs are specified in the appropriate
config fragment.
