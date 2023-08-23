![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1cdti/hw/get/6310301012/model-01/WSH-SN01
Payload: {
    "action"    : "get",
    "project"   : "6310301012",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Get firmware version
```
Topic: v1cdti/hw/get/6310301012/model-01/WSH-SN01
Payload: {
    "action"    : "get",
    "project"   : "6310301012",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "firmware_version",
    "value"     : "2WSH0201"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/get/6310301012/model-01/WSH-SN01
Payload: {
    "action"    : "get",
    "project"   : "6310301012",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "manufactur_id",
    "value"     : "20125496"
}

Topic: v1cdti/hw/get/6310301012/model-01/WSH-SN01
Payload: {
    "action"    : "get",
    "project"   : "6310301012",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "geo_location",
    "value"     : "13.810553, 100.525975"
}
```

## Set geo-location or location placement
```
Topic: v1cdti/hw/set/6310301012/model-01/WSH-SN01
Payload: {
    "action"    : "set",
    "project"   : "6310301012",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "geo_location",
    "value"     : "13.810553, 100.525975"
}
```

## Monitor machine sensor
```
Topic: v1cdti/hw/monitor/6310301012/model-01/WSH-SN01
Payload: {
    "action"    : "monitor",
    "project"   : "6310301012",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "speed",
    "value"     : "1200"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/set/6310301012/model-01/WSH-SN01
Payload: {
    "action"    : "set",
    "project"   : "6310301012",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "Machine_status",
    "value"     : "maint"
}
```