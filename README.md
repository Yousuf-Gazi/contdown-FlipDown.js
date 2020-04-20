<!-- changing future date by yousuf gazi -->
  // Unix timestamp (in seconds) to count down to
  var futureDay = (new Date().getTime() / 1000) + (86400 * 70) + 1;

  // Set up FlipDown
  var flipdown = new FlipDown(futureDay)

  ---------------------------------------------------------------------------------------------------------------------------------------------------------
  ---------------------------------------------------------------------------------------------------------------------------------------------------------
  new Date().getTime() / 1000 is current time. To get the time in second new Date().getTime() is divided by 1000.

  Here 86400 (timestamp) = 86400 sec = 1 day. Therefore 86400 * 70 (70 is 70 day). Just change 70 to your future remaining day. It means your current day to your future day difference (in day unit).

  -------> link to get the day diffrence
  ------->https://www.timeanddate.com/date/dateadded.html
<!-- changing future date by yousuf gazi -->