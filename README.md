# webservermonitor
 Now create another alarm, but this time we are interested in making 
 sure that your Lambda is invoked every minute:

* Look for your Lambda name in the listing of metrics, and click on the checkbox for the row where the metric name is "Invocations". 
Click "Next".
* Enter a name and description for this alarm.
* Setup the alarm to be triggered whenever "Invocations" is less than 3, for 1 consecutive period(s).
* Select "Sum" as the Statistic and 5 minutes (or the amount of minutes that's reasonable for your use case) in the "Period" dropdown.
* In the "Notification" box, click the Select a notification list dropdown and select your new SNS endpoint.
* Click "Create Alarm".
