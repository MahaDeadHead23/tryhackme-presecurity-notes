# 🖧 Intro to LAN
(Notes go here)

# 🌐 LAN Topologies

LAN topologies define how devices are arranged in a network.
## ⭐ Star Topology
- Devices connect to a central hub/switch.
- ✅ Reliable & scalable.
- ❌ Expensive, depends on central device.
## ⭐ Star Topology
- Devices connect to a central hub/switch.
- ✅ Reliable & scalable.
- ❌ Expensive, depends on central device.

  
## 🚌 Bus Topology
- Devices share a single backbone cable.
- ✅ Cheap, easy setup.
- ❌ Bottlenecks, hard troubleshooting, single point of failure.
<img width="1140" height="801" alt="image" src="https://github.com/user-attachments/assets/da863863-b406-4e9a-b462-283a8edff5a7" />


## 🔗 Ring Topology
- Devices form a loop, forwarding data around.
- ✅ Easy to troubleshoot, fewer bottlenecks.
- ❌ If one device/cable fails, the whole ring breaks.
<img width="878" height="801" alt="image" src="https://github.com/user-attachments/assets/3b2987af-049a-4de9-9277-26d603e660f7" />

# 🔀 Switches

- Aggregates multiple devices (PCs, printers, etc.) via Ethernet.
- Ports: 4, 8, 16, 24, 32, 64+.
- Smarter than hubs: sends data only to target device.
- ✅ Reduces traffic, improves efficiency.
- Can connect with routers for redundancy.
<img width="1409" height="801" alt="image" src="https://github.com/user-attachments/assets/3477314a-7beb-4d10-860e-532f9778b2d4" />


# 📡 Routers

- Connects networks & forwards data between them.
- Uses **routing** to create delivery paths.
- Allows multiple paths = redundancy.
- ✅ Ensures connectivity even if one path fails.
<img width="1140" height="390" alt="image" src="https://github.com/user-attachments/assets/e2da201d-9944-49ac-b7ea-c99176ef1135" />

# 🍰 Subnetting

Splitting a network into smaller sub-networks = more control.
<img width="908" height="801" alt="image" src="https://github.com/user-attachments/assets/2d87f258-4d04-485d-a387-b151720a471e" />

## Uses:
- Identify **network address** (e.g., 192.168.1.0).
- Identify **host address** (e.g., 192.168.1.100).
- Identify **default gateway** (e.g., 192.168.1.254).

## Benefits:
- ⚡ Efficiency
- 🔒 Security
- 🎛 Control
<img width="1140" height="488" alt="image" src="https://github.com/user-attachments/assets/080e60ee-7673-4696-b053-5aa7648656d8" />

👉 Example: Café = one subnet for staff devices, one for public Wi-Fi.

# 🏷️ Address Resolution Protocol (ARP)

Maps IP addresses ↔ MAC addresses.

## How it works:
- Device keeps a **cache** of IP ↔ MAC mappings.
- 📢 **ARP Request:** "Who has this IP?"
- 📩 **ARP Reply:** "I do. Here’s my MAC."

✅ Helps devices identify and talk to each other.

<img width="823" height="864" alt="image" src="https://github.com/user-attachments/assets/d2356bae-9106-4724-a393-1ab09aa27b14" />

# 🤝 DHCP (Dynamic Host Configuration Protocol)

Automates IP address assignment.

## Steps:
1. 📢 **DHCP Discover** – Device asks for IP.
2. 🎁 **DHCP Offer** – Server suggests IP.
3. 👍 **DHCP Request** – Device accepts.
4. ✅ **DHCP ACK** – Server confirms.

👉 Without DHCP = manual IP entry required.

<img width="636" height="870" alt="image" src="https://github.com/user-attachments/assets/5facb0c7-88b6-46d5-a4dc-ae9951d89586" />

<img width="1092" height="632" alt="image" src="https://github.com/user-attachments/assets/0c965399-1643-4be5-b7f1-52b7fb1bc678" />
