### Initial network topology and instruction

![Network Topology](basic-device-security-ss1.png)

### Changed the hostname of both R1 and SW1 from "Router" and "Switch" to "R1" and "SW1" from global configuration mode)

![Step 1](basic-device-security-ss2.png)

### Enabled unencrypted password for R1 and SW1 for privileged EXEC mode

![Step 2](basic-device-security-ss3.png)

### Enabled a type 7 encrypted password for R1 and SW1 'service password-encryption'

![Step 3](basic-device-security-ss4.png)

### Enabled a MD5 encrypted password for R1 and SW1 (trumps the former passwords) 'enable secret [password]'

![Step 4](basic-device-security-ss5.png)

### Save the configuration to startup config using the 'write' command

![Step 5](basic-device-security-ss6.png)
