DoubleClick For Publishers Advanced Native Example
==================================================

This project is an advanced native ads example intended to show how publishers
might construct a list-based user experience (such as a news feed might have)
that incorporates multiple native ad formats.

The project uses a single activity that maintains a ListView and an array of
items. Most of these items are mocked listings for real estate, which stand in
example application data. Placed among the sample listings are AdPlacement
objects. These objects us AdFetchers to request ads from DFP Custom Rendering,
construct NativeAdView instances to display them, and cache references to
individual asset views in AdViewHolders.

Most of the AdPlacement classes handle a single type of ad.
The MultiFormatAdPlacement, however, can request and display App Install,
Content, and either of two custom template formats.

Prerequisites
-------------

- Android API Level v14 or higher
- Android Build Tools v25 or higher
- Play Services Ads v11.8.0 or higher

How to Build
------------

This sample uses the Gradle build system. To build the project, use the
"gradlew build" command.

To open this project with
[Android Studio](http://developer.android.com/sdk/index.html), use the "Import
project" choice in the welcome menu, and select the root directory of the
project.

Support
-------

You can see our [Developers' site](https://developers.google.com/mobile-ads-sdk/)
for documentation on using the SDK, and join the developer community on
[our forum](https://groups.google.com/forum/#!forum/google-admob-ads-sdk).

License
-------

Copyright 2015 Google Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
