# assessment
task


Stimulate temperature/GPS data from a publisher and sent it to a subscriber via DDS. Once data is received, subscriber should send it to a socket and the socket client will write the data to two different files, one for GPS and one for temperature data.

Define at least 10 dummy data in the below format
{
"GPS": {
  "Latitude": "24.40175",
  "Longitude": "54.57946"
},
"TempratureInCelsius": "22"
}
use cJSON library to parse the data
Send it from a DDS publisher to subscriber(refer Micro-XRCE-DDS)
From the subscriber send the data to a socket and the socket client should write the data to two separate files.

Expected output:
GPS data will be in a file named gps_data and Temprature data will be in another file named temperature_data
