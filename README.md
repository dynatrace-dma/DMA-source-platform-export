# DMA Source Platform Export

Scripts that export your observability configuration from a source platform, for the
**Dynatrace Migration Assistant (DMA)**. Each script runs in your environment, reads your
configuration through the platform's API, and writes an archive that you import into the DMA.

| Source platform | Folder | Scripts | Documentation |
| --------------- | ------ | ------- | ------------- |
| Splunk Enterprise and Splunk Cloud | [`splunk/`](splunk/) | [`splunk/splunk-export/`](splunk/splunk-export/) | [Splunk export guide](splunk/splunk-export/README.md) |
| New Relic | [`new-relic/`](new-relic/) | [`new-relic/newrelic-export/`](new-relic/newrelic-export/) | [New Relic export guide](new-relic/README.md) |

The Datadog export scripts are in their own repository,
[`dynatrace-dma/datadog-to-dynatrace`](https://github.com/dynatrace-dma/datadog-to-dynatrace).

## Moved from `splunk-to-dynatrace`

This repository was named `splunk-to-dynatrace` and held only the Splunk scripts, at the root.
They now live in `splunk/`, with the same content:

- `splunk-export/` is now [`splunk/splunk-export/`](splunk/splunk-export/);
- `tests/` is now [`splunk/tests/`](splunk/tests/).

If a saved link or a download command stopped working, add `splunk/` in front of the path.
Release tags made before the move keep the old layout.
