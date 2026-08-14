**CCNA Day 2: 7/6/26**

**Ethernet** - A collection of network protocols/standards

**Bit** - 0 or 1

**Byte** - 8 bits = 1 byte

Speed is measured in bits per second (Kbps, Mbps, Gbps) not bytes per second. Data on a hard drive is measured in bytes. Gigabyte (hence the name)

1 kilobit (Kb)= 1,000 bits

1 megabit (Mb) = 1,000,000 bits (1 Million Bits)

1 gigabit (Gb) = 1,000,000,000 bits (1 Billion Bits)

1 terabit (Tb) = 1,000,000,000,000 bits (1 Trillion Bits)

**IEEE 802.3 is ethernet standards**

<img width="1132" height="586" alt="Screenshot 2026-07-23 114020" src="https://github.com/user-attachments/assets/4f440046-ccc4-44fe-81ac-22bbce873df0" />

**T for informal name means twisted pair. Max length for twisted pair cables are 100m**

**To put into perspective:**

<img width="460" height="352" alt="Screenshot 2026-07-23 114321" src="https://github.com/user-attachments/assets/02129228-4504-49bd-8bfe-06cdf9b4972b" />

Copper cables: Use UTP cables = Unshielded Twisted Pair (unshielded is having to metallic shield, tinfoil looking thing). Helps with electrical magnetic interference.

**Fast ethernet/10Bast-T/100Base-T connection (4 cables):**

<img width="1292" height="531" alt="Screenshot 2026-07-23 114743" src="https://github.com/user-attachments/assets/d0dd6fb6-5f53-4b29-9f33-c50cf1c60f47" />

Full Duplex means they can send and receive data at the same time no problem, not having any problems with collision as they use separate wires to transmit and receive data.

**Same setup when it comes to a pc and router:**

<img width="1285" height="549" alt="Screenshot 2026-07-23 115005" src="https://github.com/user-attachments/assets/0cd9b8eb-bf30-4a1a-a366-af57b8792356" />

This is also known as a straight through cable where the same pin connects to its correlating number. ex . 1 to 1, 2 to 2, 3 to 3, and 6 to 6.

So what if you were to use the same setup with a router to router, pc to pc, or switch to switch?

It will not work since it’s not prepared to receive and transmit data. The solution is a cross over cable. In the diagram it shows how the cables “cross over to be able to transmit and receive when both devices transmit and receive on the same interfaces:

<img width="1352" height="589" alt="Screenshot 2026-07-23 115342" src="https://github.com/user-attachments/assets/39b02be9-a6f7-4c1c-bdca-e32d09d08a91" />


<img width="1119" height="610" alt="Screenshot 2026-07-23 115513" src="https://github.com/user-attachments/assets/04071461-fd76-4e5c-93c2-821325fd5bbc" />

In today's world now though, this is basically irrelevant, becuase modern networking devices have a feature called auto MDI-X. Auto MDIX will actually detect which pins the other device is receiving and transmitting, and then switch to the corresponding input.

<img width="1341" height="602" alt="Screenshot 2026-07-23 115733" src="https://github.com/user-attachments/assets/70bc9d8f-7ab8-499b-85f0-58ea75115527" />

**UTP Cables 1000 Base-T and 10G Base-T use the remaining wires, and are bi drectional.** 

**SFP transceiver - Small Form Factor Pluggable:**

<img width="456" height="299" alt="Screenshot 2026-07-23 120022" src="https://github.com/user-attachments/assets/0233606f-f7ce-4298-bf93-ec3ac6ee9f73" />


**Usually connect Fiber optic into the SFP:**

<img width="1289" height="356" alt="Screenshot 2026-07-23 120111" src="https://github.com/user-attachments/assets/fba05c3d-bb24-4956-9a72-0a173d85b377" />


1. Fiberglass Core 
2. Cladding (reflects light)
3. Protective Buffer
4. OuterJacket of Cable

<img width="561" height="522" alt="Screenshot 2026-07-23 120226" src="https://github.com/user-attachments/assets/005f1a4c-ade3-41c3-8398-be51965198f4" />


**Single Mode Fiber vs Multi Mode Fiber:**

Single-mode is very narrow (8 to 10 μ m). Multimode is much larger (50 to 62.5 μ m) 

Light Source: Single-mode utilizes high-power lasers. Multimode relies on less expensive, broader LEDs or VCSELs 

Distance Capabilities: Single-mode can span from 2 km to over 100 km without signal repeaters. Multimode is typically limited to distances under (500-600 meters (up to 2 km for low speeds). 

Single is good for really long distances and high speeds within longer distances. Multimode is good for short distances, cheaper, and high speeds in shorter distances. 

Comparison between UTP vs Fiber:

<img width="1261" height="665" alt="Screenshot 2026-07-23 120337" src="https://github.com/user-attachments/assets/0f40151b-dc98-44ed-9dfa-a0d9751922cc" />





