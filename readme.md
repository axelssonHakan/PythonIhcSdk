# Introduction

This is a Python library for making a soap connection to an IHC controller
(IHC controller is a home automation controller made by LK). 
The primary goal for this library was to make an interface from Home Assistant to IHC, 
and only the few functions need to do this has been implemented in the library.

The library implements:

* Authentication
* Get runtime values
* Set runtime values
* Notification when a resource changes. 
 
## Examples

See the examples folder.

For more infomation about this library look at

http://www.dingus.dk/ihc-soap-client-python/

# Note

From version 1.0.2 (first release), folder structure has been changed to make is easier
to have the libray included in PyPi. The library files are now in the ihcsdk subfolder

# License

IHCSoapClient is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

IHCSoapClient is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with ArduinoIHC.  If not, see <http://www.gnu.org/licenses/>.

