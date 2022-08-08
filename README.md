# fortigate-nat64

<H2>Reference from my blog.</H2>

Topology

![image](https://user-images.githubusercontent.com/77621054/183476036-ccb1cbba-1654-4d1b-8e0b-0bb91ec93653.png)

IP v4/v6 Addressing
![image](https://user-images.githubusercontent.com/77621054/183460533-3f5999ac-e53d-490b-ae70-a2e6f9f0d71f.png)


Configure DNS for IPv6 enabled interface
![image](https://user-images.githubusercontent.com/77621054/183468823-b37fc13d-c95c-44de-954b-ed2735a42f2c.png)

config system dns64

set status enable

set dns64-prefix 64:ff9b::/96

set always-synthesize-aaaa-record enable

end

Policy Configuration and NAT64 configurations

![image](https://user-images.githubusercontent.com/77621054/183469459-2f595f32-2f97-439a-8b9e-43ed5996d4b3.png)


![image](https://user-images.githubusercontent.com/77621054/183469549-4daf7777-94e3-4b55-802f-769adee3a82a.png)


![image](https://user-images.githubusercontent.com/77621054/183469666-e521434f-d985-4aa9-8284-cbb59423f8d9.png)


![image](https://user-images.githubusercontent.com/77621054/183469780-9aed0fc6-43ce-4e59-a099-3330a9f2747d.png)


![image](https://user-images.githubusercontent.com/77621054/183469901-e54172c3-1db9-4a9a-899f-805636ef0009.png)


Linux - v6 to v6
![image](https://user-images.githubusercontent.com/77621054/183488982-ee91e281-7a93-4003-9488-f048dffda396.png)











