ngCalendar
===========
AngularJS calendar based on dhtmlxCalendar.

<p>
  <a href="https://gitter.im/miamarti/ng-calendar" target="_blank"><img src="https://img.shields.io/gitter/room/nwjs/nw.js.svg"></a>
  <img src="https://img.shields.io/badge/ngcalendar-release-green.svg">
  <img src="https://img.shields.io/badge/version-1.2.5-blue.svg">
  <img src="https://img.shields.io/github/license/mashape/apistatus.svg">
  <a href="https://github.com/miamarti/ngcalendar/tarball/master"><img src="https://img.shields.io/github/downloads/atom/atom/latest/total.svg"></a>
  <img src="https://img.shields.io/bower/v/bootstrap.svg">
</p>

<a data-flickr-embed="true"  href="https://www.flickr.com/photos/43673546@N06/27207773213/in/dateposted-public/" title="ngcalendar"><img src="https://c6.staticflickr.com/8/7293/27207773213_1f075ef135_b.jpg" width="790" height="367" alt="ngcalendar"></a>


<h3>dhtmlxCalendar</h3>
JavaScript DatePicker Component.

dhtmlxCalendar is a lightweight cross-browser JavaScript calendar which can be configured as a popup date picker or a flat calendar. The component is easy-to-use and fully customizable. It can be attached to any text input field and provides fast and intuitive date selection in web- based apps.

dhtmlxCalendar features custom date format, the choice of any day as the first day of week, a year drop down list, and various skins and languages to choose from. The component can also be used as a date range selection tool, when dates prior to and after the available date range are disabled accordingly.


## Dependencies
* AngularJS

## Implementation
```
<i class="input-calendar-icon" ng-calendar ng-model="modelDate"></i>
```

The parameter bind = "ng-model" you are referring to variable $scope.modelDate

## Bower install de dependency
```
$ bower install ngcalendar --save
```

## Module AngularJS include
```
angular.module('example', ["ngCalendar"]);
```
