![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1cdti/hw/get/6310301019/model-01/WSH-002
Payload: {
    "action"    : "get",
    "project"   : "6310301019",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Get firmware version
```
Topic: v1cdti/hw/get/6310301019/model-01/WSH-002
Payload: {
    "action"    : "get",
    "project"   : "6310301019",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "firmware",
    "value"     : "114"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/get/6310301019/model-01/WSH-002
Payload: {
    "action"    : "get",
    "project"   : "6310301019",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "geo-location",
    "value"     : "100","150"
}
```

## Set geo-location or location placement
```
Topic: v1vdti/hw/set/6310301019/model-01/WSH-002
Payload: {
    "action"    : "set",
    "project"   : "6310301019",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "geo-location",
    "value"     : "100","150"
}
```

## Monitor machine sensor
```
Topic: v1cdti/hw/monitor/6310301019/model-01/WSH-002
Payload: {
    "action"    : "monitor",
    "project"   : "6310301019",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "status",
    "value"     : "maint"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/set/6310301019/model-01/WSH-002
Payload: {
    "action"    : "set",
    "project"   : "6310301019",
    "model"     : "model-01",
    "serial"    : "WSH-002",
    "name"      : "wash_count",
    "value"     : "115"
}
```
