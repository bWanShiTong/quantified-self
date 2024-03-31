# Quantified Self

Main purpose of this project is to quantify self, to measure and record as much data about yourself as possible, as easy as possible.

## Why?

Many parts of corporate quantified self are shit, with subscription requirements, hard to export data, not showing you certain data, every device needs an app, and more. On [QuantifiedSelf](https://www.reddit.com/r/QuantifiedSelf) reddit, there are several posts about seeking health app, either for android or ios, and in several cases one app can track 80% of requirements, second app 10%, and so on, and even with all apps, another website/project is needed to export or convert data between apps.

## Purpose

First purpose would be to create system that can be self hosted, and enable anyone to easily input, sync and aggregate data.

Second purpose would be to ease automation and collecting of that data, instead of needing 1 app for every device, this software would integrate those devices.

Third purpose would be to allow users to enable data sharing, allowing people to perform data analysis.


## General idea

This software should have 3 parts, that should work both solo and combined.

1. Backend service
2. UI
3. App


### Backend service

Backend service would be simple REST api, that would allow use to sync with devices, and cloud, this service would host UI.

### UI

UI would be used primary on desktops, it would be used to control backend service, and should have something like Jupyter notebook for data aggregation, processing and data analysis

### App

App could work both as UI for backend service, where it would read/write to backend service, or as backend service where it get's data from devices and stores them on device.