

In order to post a new request for a sunrise time you need to give the paramaters of lat, lng, and date.
For example if you were to send a post request with http://localhost:3000/sunrises?lat=47&lng=-25&date=2018-10-23
you will recieve the JSON data of 
{
    "results": {
        "sunrise": "1:11:03 AM",
        "sunset": "5:27:49 PM",
        "solar_noon": "9:19:26 AM",
        "day_length": "16:16:46",
        "civil_twilight_begin": "12:27:06 AM",
        "civil_twilight_end": "6:11:46 PM",
        "nautical_twilight_begin": "11:23:09 PM",
        "nautical_twilight_end": "7:15:43 PM",
        "astronomical_twilight_begin": "12:00:01 AM",
        "astronomical_twilight_end": "12:00:01 AM"
    },
    "status": "OK"
}
