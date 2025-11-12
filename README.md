3.4.6 Lab - Configure VLANs and Trunking (Physical Mode)

Lab ini bertujuan untuk membangun dan mengonfigurasi jaringan dengan VLAN serta trunk antar switch menggunakan Cisco Packet Tracer.
Sebagai bagian dari pengembangan untuk tugas akhir, saya menambahkan satu perangkat tambahan yaitu PC-C ke dalam jaringan untuk memperluas pengujian konektivitas VLAN 10.

Tujuan Pembelajaran:

Menyusun topologi jaringan sesuai diagram yang diberikan.
Mengonfigurasi VLAN dan port access pada switch.
Mengonfigurasi trunk antar switch dengan protokol 802.1Q.
Menguji konektivitas antar host dalam VLAN yang sama dan memastikan isolasi antar VLAN berbeda.

Hasil Uji Konektivitas:	
S1 ↔ S2	✅ Berhasil	Melalui VLAN 99 (Management)
PC-A ↔ PC-B	✅ Berhasil	Keduanya dalam VLAN 10
PC-A ↔ S1	❌ Gagal	Berbeda VLAN 
PC-B ↔ S2	❌ Gagal	Berbeda VLAN 
PC-C ↔ PC-A	✅ Berhasil	Tambahan pengujian VLAN 10 (Tugas Akhir)

Perangkat yang Digunakan:
2 Switch (2960)
3 PC — PC-A, PC-B, dan tambahan PC-C
Kabel Ethernet Straight-Through
Kabel Konsol

Video Penjelasan


YouTube:https://www.youtube.com/watch?v=htaYju_H2u0
