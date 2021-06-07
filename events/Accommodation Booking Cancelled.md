# Accommodation Booking Cancelled

## Javascript Code
```js
window.appEventData0706 = window.appEventData0706 || [];
appEventData0706.push({
  "event": "Accommodation Booking Cancelled",
    "booking": {
        "cancellationID": "<cancellationID>",
        "roomList": [
            {
                "location": {
                    "locationId": "<locationId>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|cancellationID|string|Unique identifier of a cancellation of a booking.  Typically not the same as the booking ID.|CN-34456789|||||||
|locationId|string|Unique Identifier of a Location. |155, 65588, 987764448|||||||
