# CouplesCalendar

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Download](https://api.bintray.com/packages/yuyakaido/maven/CouplesCalendar/images/download.svg)](https://bintray.com/yuyakaido/maven/CouplesCalendar/_latestVersion)

Functional calendar library for Android

- Horizontal swipe
- Show dot for one day event
- Show line for multiple days event

## Display of event

Dot is displayed in case of the event belongs one day.

- One event, One dot
- Two events, Two dots
- More than three events, Two dots and plus mark

![](https://raw.githubusercontent.com/yuyakaido/CouplesCalendar/master/screenshots/6.png)

Line is displayed in case of the event extends multiple days.

- StartAt: 2015-08-10T00:00:00.000Z, EndAt: 2015-08-12T00:00:00.000Z, Color: Light Blue
- StartAt: 2015-08-12T00:00:00.000Z, EndAt: 2015-08-14T00:00:00.000Z, Color: Tiffany Blue
- StartAt: 2015-08-24T00:00:00.000Z, EndAt: 2015-08-26T00:00:00.000Z, Color: Light Blue
- StartAt: 2015-08-25T00:00:00.000Z, EndAt: 2015-08-27T00:00:00.000Z, Color: Green
- StartAt: 2015-08-26T00:00:00.000Z, EndAt: 2015-08-28T00:00:00.000Z, Color: Orange

![](https://raw.githubusercontent.com/yuyakaido/CouplesCalendar/master/screenshots/1.png)

## Color of event

Event has color, dot or line is displayed by its color.

Library has ten colors by default.

- Red
- Orange
- Yellow
- Green
- Tiffany Blue
- Light Blue
- Blue
- Purple
- Pink
- Indigo

![](https://raw.githubusercontent.com/yuyakaido/CouplesCalendar/master/screenshots/5.png)

## Theme color of cell

Date cell is highlighted when it is clicked.

- Red
- Orange
- Yellow
- Green
- Tiffany Blue
- Light Blue
- Blue
- Purple
- Pink
- Indigo

![](https://raw.githubusercontent.com/yuyakaido/CouplesCalendar/master/screenshots/4.png)

## Recurrence of event

Recurrence of event is defined by [RFC 2445](https://tools.ietf.org/html/rfc2445). It is called RRule.

StartAt is start date of event, RRule is recurrence frequancy of event.

- StartAt: 2015-08-01T00:00:00.000Z, RRule: FREQ=WEEKLY
- StartAt: 2015-08-02T00:00:00.000Z, RRule: FREQ=WEEKLY;INTERVAL=2

![](https://raw.githubusercontent.com/yuyakaido/CouplesCalendar/master/screenshots/2.png)

# Install

- Latest version is [![Download](https://api.bintray.com/packages/yuyakaido/maven/CouplesCalendar/images/download.svg)](https://bintray.com/yuyakaido/maven/CouplesCalendar/_latestVersion)

```
compile 'com.yuyakaido.android:couples-calendar:${LatestVersion}'
```

# License
```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
