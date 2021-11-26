# Snowplow Iterable Tag for Google Tag Manager Server-side

[![early-release]][tracker-classification]
[![License][license-image]][license]
[![Release][release-image]][releases]

Snowplow is a scalable open-source platform for rich, high quality, low-latency data collection. It is designed to collect high quality, complete behavioral data for enterprise business.

**To find out more, please check out the [Snowplow website][website] and our [documentation][docs].**

## Snowplow Iterable Tag for Google Tag Manager Server-side Overview

A Google Tag Manager Server-side Iterable Tag template for sending events from the Snowplow Client (and other GTM SS Clients) to Iterable.

This Tag allows you to forward events in your Google Tag Manager Server container to [Iterable][iterable].

**Works best with the [Snowplow Client][snowplow-client].**

## Event Data

This Tag reads event data from the "Common Event Data" specified in the [Google Tag Manager documentation][gtm-event-docs] and also populates a number of properties from the rich Snowplow events generated by the [Snowplow JavaScript Tracker][javascript-tracker] in the browser and collected in the [GTM SS Snowplow Client][snowplow-client].

## Installation

### Installing from the Google Tag Manager Gallery

Coming Soon

### Manual Installation

To manually install this Client:

1. Download `template.tpl`
2. Create a new Tag in the Templates section of a Google Tag Manager Server container
3. Click the More Actions menu and select Import
4. Import `template.tpl` downloaded in Step 1
5. Click Save.

## Find out more

| Technical Docs                    | Setup Guide                 |
|-----------------------------------|-----------------------------|
| [![i1][techdocs-image]][techdocs] | [![i2][setup-image]][setup] |
| [Technical Docs][techdocs]        | [Setup Guide][setup]        |

## Contributing

Feedback and contributions are welcome - if you have identified a bug, please log an issue on this repo. For all other feedback, discussion or questions please open a thread on our [discourse forum][discourse].

| Contributing                                 |
|----------------------------------------------|
| [![i3][contributing-image]](CONTRIBUTING.md) |
| [Contributing](CONTRIBUTING.md)              |

## Copyright and license

Snowplow Iterable Tag for Google Tag Manager Server-side is copyright 2021 Snowplow Analytics Ltd.

Licensed under the **[Apache License, Version 2.0][license]** (the "License");
you may not use this software except in compliance with the License.

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

[tracker-classification]: https://docs.snowplowanalytics.com/docs/collecting-data/collecting-from-own-applications/tracker-maintenance-classification/
[early-release]: https://img.shields.io/static/v1?style=flat&label=Snowplow&message=Early%20Release&color=014477&labelColor=9ba0aa&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAAeFBMVEVMaXGXANeYANeXANZbAJmXANeUANSQAM+XANeMAMpaAJhZAJeZANiXANaXANaOAM2WANVnAKWXANZ9ALtmAKVaAJmXANZaAJlXAJZdAJxaAJlZAJdbAJlbAJmQAM+UANKZANhhAJ+EAL+BAL9oAKZnAKVjAKF1ALNBd8J1AAAAKHRSTlMAa1hWXyteBTQJIEwRgUh2JjJon21wcBgNfmc+JlOBQjwezWF2l5dXzkW3/wAAAHpJREFUeNokhQOCA1EAxTL85hi7dXv/E5YPCYBq5DeN4pcqV1XbtW/xTVMIMAZE0cBHEaZhBmIQwCFofeprPUHqjmD/+7peztd62dWQRkvrQayXkn01f/gWp2CrxfjY7rcZ5V7DEMDQgmEozFpZqLUYDsNwOqbnMLwPAJEwCopZxKttAAAAAElFTkSuQmCC

[license]: https://www.apache.org/licenses/LICENSE-2.0
[license-image]: https://img.shields.io/badge/license-Apache--2-blue.svg?style=flat

[releases]: https://github.com/snowplow/snowplow-gtm-server-side-iterable-tag/releases
[release-image]: https://img.shields.io/github/v/release/snowplow/snowplow-gtm-server-side-iterable-tag

[website]: https://snowplowanalytics.com
[docs]: https://docs.snowplowanalytics.com
[snowplow]: https://github.com/snowplow/snowplow
[discourse]: https://discourse.snowplowanalytics.com

[techdocs]: https://docs.snowplowanalytics.com/docs/forwarding-events-to-destinations/forwarding-events/google-tag-manager-server-side/iterable-tag-for-gtm-ss/iterable-tag-configuration/
[techdocs-image]: https://d3i6fms1cm1j0i.cloudfront.net/github/images/techdocs.png
[setup]: https://docs.snowplowanalytics.com/docs/forwarding-events-to-destinations/forwarding-events/google-tag-manager-server-side/iterable-tag-for-gtm-ss/
[setup-image]: https://d3i6fms1cm1j0i.cloudfront.net/github/images/setup.png

[contributing-image]: https://d3i6fms1cm1j0i.cloudfront.net/github/images/contributing.png

[snowplow-client]: https://github.com/snowplow/snowplow-gtm-server-side-client/
[javascript-tracker]: https://github.com/snowplow/snowplow-javascript-tracker
[gtm-event-docs]: https://developers.google.com/tag-manager/serverside/common-event-data

[iterable]: https://iterable.com/
