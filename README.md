# Auto config OpenVpn by bash

At first set `.env` variables

### init configs
Initialize the configuration files and certificates. (will obtain ur ip automatically)
```bash
$ ./ov-init.sh 
```

### add user
Generate a client certificate
```bash
$ ./ov-add-user.sh USERNAME PASSWORD 
```