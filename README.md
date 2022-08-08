# fortigate-nat64

Topology

![image](https://user-images.githubusercontent.com/77621054/183457773-2539e9b7-f810-455c-9eec-0f44c4d8423f.png)

IP v4/v6 Addressing
![image](https://user-images.githubusercontent.com/77621054/183460533-3f5999ac-e53d-490b-ae70-a2e6f9f0d71f.png)


Configure DNS for IPv6 enabled interface
![image](https://user-images.githubusercontent.com/77621054/183468823-b37fc13d-c95c-44de-954b-ed2735a42f2c.png)

config system dns64
    set status enable
    set dns64-prefix 64:ff9b::/96
    set always-synthesize-aaaa-record enable
end


