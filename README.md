# Member

|  ID       |  Member's name     |
| --------- | ------------------ |
|  20521226 |  Trần Đại Dương    |
|  20521179 |  Trần Quốc Đạt     |
|  20521963 |  Nguyễn Hùng Thịnh |

# Environment and network diagram
- An Ubuntu 22.04 machine that had installed OpenWisp's package (openwisp-controller).
- A OpenWrt (virtual) machine that had installed OpenWisp's package (openwisp-config) and is also considered as an Access Point (AP) node.
- Client device(s) that connect to Access Point node. (such as smartphone, computer, etc).

<img width="890" height="592" alt="AP" src="https://github.com/user-attachments/assets/904c1900-4ce1-4fa9-9471-767bfda6284a" />


# Implementation
- Installing necessary packets and configuring OpenWrt by OpenWisp in the Ubuntu machine.
- Config OpenWrt's network interface through OpenWisp and start the access point.
- On Client device(s), connect to the OpenWrt through wireless network

# References
- https://github.com/openwisp/openwisp-config
- https://github.com/openwisp/openwisp-controller
- https://openwisp.io/docs/dev/index.html
