# Set device type when sending data

To apply a device type to a device, either new or existing, simply add the `?type=` parameter to the URL. For example:


```html
POST /api/v1.6/devices/<device_label>/?type=<device_type_label>
```

```json
{
	"temperature":23,
	"humidity":88
} 
```