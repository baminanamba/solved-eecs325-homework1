Download Link: https://assignmentchef.com/product/solved-eecs325-homework1
<br>
<h1></h1>

<ol>

 <li> Consider a 100 Mbps link, that is preceded by a router with a queue that can hold 1000 packets. Suppose the average packet length is 125 bytes and the average packet arrival rate is 80k pps (packets per second). (Note: 1 byte = 8 bits)

  <ol>

   <li> Calculate the transmission delay for one packet.</li>

   <li> What is the average number of packets in the queue? (Hint: average queue length = <u>traffic intensity</u></li>

  </ol></li>

</ol>

)

1−traffic intensity

<ol>

 <li> What is the average amount of waiting time for a packet?</li>

</ol>

<ol start="2">

 <li>Consider two hosts A and B, connected by a direct link of capacity 4 Mbps. Suppose the propagation delay between the two hosts could be ignored. Host A wants to send a 10 MB file to Host B. Before sending the file, A divides the file into 1000-byte chunks and adds an additional 60-byte packet header to each packet.

  <ol>

   <li> How long does it take for Host B to receive the complete file?</li>

   <li> Based on question a, what is the ’goodput’ from A to B? (Hint: Goodput can be calculated as the number of payload bits arriving per second. Goodput is the application level throughput, i.e. the number of useful information bits, delivered by the network to a certain destination,per unit of time.)</li>

  </ol></li>

 <li>Suppose a company uses satellites to provide Internet access. The satellite is located at 750km above Earth (assume this is the direct distance between the equipment and the satellite). Packets are transmitted from the sender (equipment) to the receiver (equipment) via the satellite as illustrated by the figure above. Suppose the average packet size is 1250 bytes and link bandwidth (between the sender/receiver equipment and the satellite) is 100 Mbps.

  <ol>

   <li> Calculate the propagation delay for a packet from the sender to receiver, given the propagation speed is 3 × 10<sup>8 </sup>m/s.</li>

   <li> If the sender could not send another packet until it receives an acknowledgement message from the receiver, then what would be the average throughput of this communication channel? (You can also represent this as a fraction of the link capacity. The length of the acknowledgement packet could be ignored.)</li>

   <li> Based on question b, how large each packet should be to fully utilize the link capacity (In other words, the average throughput could reach 100 Mbps)?</li>

  </ol></li>

 <li> There are two hosts A and B in a packet-switched network, interconnected by three routers, as illustrated in the figure below. Each link is annotated with link capacity (above) and propagation delay (below). Each router follows the store-andforward model to process packets, and has a queue that can hold 5 packets for each direction. If the queue is full and a new packet arrives at the router, the new packet is dropped. (Note: Once a packet starts being transmitted, it will be removed from the queue. Thus, there may be 6 packets in the router at any given time point). Suppose the network is empty and all the routers are idle.</li>

 <li>If Host A sends a packet of length 1500 bytes to Host B, how long doesit take for this packet to arrive at Host B?</li>

 <li>If Host A sends three 1500 byte packets to Host B, one immediately af-ter the other. How long does it take for the last packet to reach Host B?</li>

 <li>If Host A sends 20 back-to-back 1500 byte packets to Host B, which packetswill be dropped during the transmission? Assume the packets are numbered from 1 to 20 in order.</li>

 <li>Calculate the worst-case end-to-end delay for (Hint: not all the queues will be full):</li>

</ol>

<ul>

 <li>For Host A’s 1500 bytes packet to reach Host B</li>

 <li> For Host B’s 1500 bytes packet to reach Host A</li>

</ul>