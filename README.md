# LocationTrackerApplication
Sample Android Application to keep track the current location of the device in a background service and share it the Activities in the application

It tracks the location of the device using a background service with Google LocationServices API Client and share the location to the Activity using a broadcast receiver. The background service will keep running as long as the application exists in the memory and sticks to the notification drawer. 

The service handles the following functionalities, 

<ul>
<li>Connecting to Google LocationServices API</code>
<li>Getting the current location</code>
<li>Sharing the result to the Activity</code>
</ul>

Result

![track_location_device_devdeeds](https://user-images.githubusercontent.com/6814816/31053345-fa030622-a6b8-11e7-92ca-d1108a0f404a.png)
