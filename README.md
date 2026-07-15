# UKK-TKJ-PAKET 4

Daftar Alat dan Bahan

Router Cisco (3 Interface Gigabit Ethernet)

Switch Unmanaged 8 Port (2 Unit)

PC Client / Laptop (8 Unit)

PC Server (1 Unit)

Printer Jaringan / LAN (1 Unit)

Kabel UTP & RJ-45 (Tipe Straight T568B)

Settingan IP Router

Port ke Internet (GigabitEthernet0/0): 10.10.10.2 | Netmask: 255.255.255.0

Port ke LAN Kiri (GigabitEthernet0/1): 192.168.10.1 | Netmask: 255.255.255.0

Port ke LAN Kanan (GigabitEthernet0/2): 192.168.11.1 | Netmask: 255.255.255.0
*Catatan: Menggunakan Routing RIP agar LAN Kiri dan LAN Kanan bisa saling terhubung.

Settingan IP Server & Printer (LAN Kiri)

Server -> IP: 192.168.10.2 | Netmask: 255.255.255.0 | Gateway: 192.168.10.1

Printer -> IP: 192.168.10.3 | Netmask: 255.255.255.0 | Gateway: 192.168.10.1

Settingan IP PC Client
Semua Subnet Mask diisi 255.255.255.0

PC 1 -> IP: 192.168.10.11 | Gateway: 192.168.10.1

PC 2 -> IP: 192.168.11.2  | Gateway: 192.168.11.1

PC 3 -> IP: 192.168.11.3  | Gateway: 192.168.11.1

PC 4 -> IP: 192.168.11.4  | Gateway: 192.168.11.1

PC 5 -> IP: 192.168.11.5  | Gateway: 192.168.11.1

PC 6 -> IP: 192.168.11.6  | Gateway: 192.168.11.1

PC 7 -> IP: 192.168.11.7  | Gateway: 192.168.11.1

PC 8 -> IP: 192.168.11.8  | Gateway: 192.168.11.1

Hasil Uji (Ping)
Tes kirim surat dan ping antar perangkat lintas jaringan statusnya sudah 100% Successful.
