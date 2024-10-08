---
uid: Cube_Feature_Release_10.4.10
---

# DataMiner Cube Feature Release 10.4.10 – Preview

> [!IMPORTANT]
> We are still working on this release. Some release notes may still be modified or moved to a later release. Check back soon for updates!

> [!TIP]
> For release notes for this release that are not related to DataMiner Cube, see [General Feature Release 10.4.10](xref:General_Feature_Release_10.4.10).

## Highlights

*No highlights have been selected yet.*

## New features

*No new features have been added yet.*

## Changes

### Enhancements

#### Visual Overview: Support for dynamic values in AlarmFilter shape data value [ID_40228]

<!-- MR 10.3.0 [CU19] / 10.4.0 [CU7] - FR 10.4.10 -->

In the AlarmFilter shape data value, dynamic values (e.g. session variables) are now supported.

### Fixes

#### False-positive warning log entry when Services or Profiles module was opened [ID_40385]

When the Services or Profiles module was opened in Cube, a false-positive warning entry could be added to the Cube logging, with the following message:

```txt
Profile and Services - The visio file name was empty or null. Check the response message from the server
```
