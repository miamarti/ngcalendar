ngcalendar
===========
AngularJS calendar based on dhtmlxCalendar.

<p>
  <a href="https://gitter.im/miamarti/ngcalendar?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge" target="_blank"><img src="https://badges.gitter.im/Join%20Chat.svg"></a>
  <img src="https://img.shields.io/badge/ngcalendar-release-green.svg">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg">
  <img src="https://img.shields.io/github/license/mashape/apistatus.svg">
</p>

<h3>dhtmlxCalendar</h3>
JavaScript DatePicker Component.

dhtmlxCalendar is a lightweight cross-browser JavaScript calendar which can be configured as a popup date picker or a flat calendar. The component is easy-to-use and fully customizable. It can be attached to any text input field and provides fast and intuitive date selection in web- based apps.

dhtmlxCalendar features custom date format, the choice of any day as the first day of week, a year drop down list, and various skins and languages to choose from. The component can also be used as a date range selection tool, when dates prior to and after the available date range are disabled accordingly.


<h3>Dependencies</h3>
* AngularJS

<h3>Implementation</h3>
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
