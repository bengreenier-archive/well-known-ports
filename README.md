# well-known-ports

exports a map of port => service name for well known ports. The data for the module comes from [wikipedia](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers).

# usage

first, `npm install well-known-ports`. Then `var wkp = require('well-known-ports')`. `wkp` will be a map of `"<port number>"` to `"<service description>"`.

# examples

```
var wkp = require('well-known-ports');

//ftp control (command)
console.log(wkp["21"]);

//Secure Shell (SSH)—used for secure logins, file transfers (scp, sftp) and port forwarding
console.log(wkp["22"]);
```

# License

MIT