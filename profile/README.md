# Breitbandmessung #

This organization provides the open source components of the service [breitbandmessung.de](https://breitbandmessung.de) of the German Federal Network Agency (Bundesnetzagentur) which originated in the BEREC [Net Neutrality (NN) Reference Measurement System](https://github.com/net-neutrality-tools/nntool). Every module contains information on build dependencies, building, and execution.

---------------

## Client Modules ##

The client modules provide the measurement libraries as well as demo applications for Android, iOS, Windows, MacOS, Linux, and Browsers. Using the server module (see below) deployed on a measurement peer, clients can perform Internet Access Speed (IAS) measurements which report the measured round-trip time, the measured download throughput, and the measured upload throughput, as well as meta information like, e.g., the used IP addresses and the network connectivity.

### ias-android ###
IAS demo application for Android. Uses the modules:
* ias-android-common
* ias-android-coverage
* ias-android-speed
* ias-client-cpp
* ias-libtool

### ias-ios ###
IAS measurement library and demo application for iOS. Uses the modules:
* ias-client-cpp
* ias-libtool

### ias-desktop ###
IAS measurement library and demo application for Windows, MacOS, and Linux. Uses the module:
* ias-client-js

### ias-client-js ###
IAS measurement library and demo application for Browsers.

## Server Module ##

The server module provides the measurement peer for the client modules.

### ias-server ###
IAS measurement server for Linux. Uses the module:
* ias-libtool

---------------

## Licenses ##

All modules of `Breitbandmessung` are released under the [AGPLv3](https://www.gnu.org/licenses/agpl-3.0.txt)

Copyright (C) 2016-2025 zafaco GmbH

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License version 3 
as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.