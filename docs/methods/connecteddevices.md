#Admin Methods

## Connected Devices

Click [here](types.md) for supported input and output types.

### Example: Request Body

``` yaml
{  
   "apiKey":"string",
   "method":"ConnectedDevices",
   "payload":{}
}
	
```
### Example : Success ResponseBody

``` yaml
[
    {
        "name": "Win7-machine",
        "mpsuser": "standalone",
        "amtuser": "admin",
        "host": "8dad96cb-c3db-11e6-9c43-bc0000d20000",
        "icon": 1,
        "conn": 1
    }
]
```
