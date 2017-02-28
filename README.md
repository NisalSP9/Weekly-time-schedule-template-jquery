# Weekly-time-schedule-template-jquery
24 X 7 time schedule

Developers can use this template whenever they want use time table, for an example if someone need to fire some event 
at a given time they can use this as follows.

Use this in your project front end. You can select a time and date by clicking on particular area or you can select many dates and times by click and drag. After you select dates and times you can click on save schedule it will return an array of dates and time sets following is an example,

["10", "11", "12", "13"] this array shows that user have selected monday(1),times(00.00h,01.00h,02.00h,03.00h).

You can easily store these values in mongodb or mysql json format.
Whenever you need to compare this values with real time you can ues javascript following code

var today = new Date();
var day = today.getDay();
var hour = today.getHours();
var nowDayHour = day + "" + hour;
