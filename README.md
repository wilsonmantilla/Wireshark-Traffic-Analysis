<h1>Network Traffic Analysis with Wireshark</h1>

<h2>Description</h2>
Open a packet capture file using Wireshark, examine packet information, and apply display filters to analyze network traffic.
<br />
<br />
<h2>Task 1. Explore data with Wireshark</h2>

![1](https://github.com/wilsonmantilla/Wireshark-Traffic-Analysis/assets/159208489/da8df7d7-5ec3-42a6-890e-868fd1285464)

Overview of the key property columns listed for each packet:
- No. : The index number of the packet in this packet capture file
- Time: The timestamp of the packet
- Source: The source IP address
- Destination: The destination IP address
- Protocol: The protocol contained in the packet
- Length: The total length of the packet
- Info: Some information about the data in the packet (the payload) as interpreted by Wireshark

<h2>Task 2. Apply a basic Wireshark filter and inspect a packet</h2>

Used the following filter to inspect a packet:

Ip.addr == 142.250.1.139

![2](https://github.com/wilsonmantilla/Wireshark-Traffic-Analysis/assets/159208489/e78faf9a-b82d-4bac-a7c4-1adaed6cbeb0)


![3](https://github.com/wilsonmantilla/Wireshark-Traffic-Analysis/assets/159208489/42137e21-7265-4e4e-ae99-bec5994c6dca)

<h2>Task 3. Use filters to select packets</h2>

Used the following filters to filter packet information:

ip.src == 142.250.1.139

![4](https://github.com/wilsonmantilla/Wireshark-Traffic-Analysis/assets/159208489/f2a594f0-c323-4ca0-b2a5-bd35fae5b36a)

ip.dst == 142.250.1.139

![5](https://github.com/wilsonmantilla/Wireshark-Traffic-Analysis/assets/159208489/88ea8a72-2ed3-4b3f-8cab-0ddbc205b3cd)

eth.addr == 42:01:ac:15:e0:02

![6](https://github.com/wilsonmantilla/Wireshark-Traffic-Analysis/assets/159208489/d21f1327-a71b-4336-ad8c-7bc549788950)

<h2>Task 4. Use filters to explore DNS packets</h2>

Used the following filter to select UDP port 53 traffic:

udp.port == 53

![7](https://github.com/wilsonmantilla/Wireshark-Traffic-Analysis/assets/159208489/0be76c9a-58f9-42df-9f3d-d4a0b4442d0f)

<h2>Task 5. Use filters to explore TCP packets</h2>

Used the following filter to select TCP port 80 traffic:

tcp.port == 80

![8](https://github.com/wilsonmantilla/Wireshark-Traffic-Analysis/assets/159208489/08457741-0db2-43bc-8884-a617fff9c8c4)

<h2>Conclusion</h2>

I know have practical experience using Wireshark to:

- Open saved packet capture files.
- View high-level packet data.
- Use filters to inspect detailed packet data.





