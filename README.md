# portsforwarding
Simple forwarding for range of ports using ssh.

List with ports for forwarding sets in ```~/.portsforwarding.json```, for example: 
```
{
    "remote-host": "myserver.com",
    "port-mappings": [
        {
            "local": "8081",
            "remote": "80"
        },
        {
            "local": "8082",
            "remote": "10000"
        },
        {
            "local": "8083",
            "remote": "10001"
        }
    ]
}
```
