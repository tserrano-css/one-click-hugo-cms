---
title: Hey esto funciona!!
date: 2020-05-16T20:52:50.108Z
description: Esto es una prueba para ver qué tal me funciona este administrador
  de sitio creado con Hugo!
image: img/about-shade-grown.jpg
---
We also provide diffAsCarbonInterval() act like diff() but returns a CarbonInterval instance. Check CarbonInterval chapter for more information. Carbon add diff methods for each unit too such as diffInYears(), diffInMonths() and so on. diffAsCarbonInterval() and diffIn*() and floatDiffIn*() methods all can take 2 optional arguments: date to compare with (if missing, now is used instead). 

Absolute boolean option (true by default) that make the method return an absolute value no matter which date is greater than the other. If set to false, it returns negative value when the instance the method is called on is greater than the compared date (first argument or now). Note that diff() prototype is different: its first argument (the date) is mandatory and its second argument (the absolute option) defaults to false.

These functions always return the total difference expressed in the specified time requested. 

This differs from the base class diff() function where an interval of 122 seconds would be returned as 2 minutes and 2 seconds via a DateInterval instance. The diffInMinutes() function would simply return 2 while diffInSeconds() would return 122. All values are truncated and not rounded. Each function below has a default first parameter which is the Carbon instance to compare to, or null if you want to use now(). The 2nd parameter again is optional and indicates if you want the return value to be the absolute value or a relative value that might have a - (negative) sign if the passed in date is less than the current instance. This will default to true, return the absolute value.