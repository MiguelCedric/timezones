# Timezones

Example of data point: 
```
{
	countryCode: "AF",
  	countryName: "Afghanistan",
  	timeZones: [
  		"Asia/Kabul"
  	],
  	UTCOffset: [
  		"UTC +04:30"
	]
}
```

    
The timeZones and UTCOffset arrays match, with the timezone and its corresponding UTCOffset. Some countries have multiple timezones though like this one:
```
{
        countryCode: "CL",
        countryName: "Chile",
        timeZones: [
            "America/Punta_Arenas",
            "America/Santiago",
            "Pacific/Easter"
        ],
        UTCOffset: [
            "UTC -03:00",
            "UTC -04:00",
            "UTC -06:00"
        ]
    }
```
