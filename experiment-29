def detect_arp_spoof(arp_table):
    seen = {}
    for entry in arp_table:
        ip, mac = entry
        if ip in seen and seen[ip] != mac:
            print(f"ARP Spoof Detected: {ip} mapped to multiple MACs!")
        else:
            seen[ip] = mac

arp_table = [
    ("192.168.1.1", "AA:BB:CC:DD:EE:FF"),
    ("192.168.1.1", "11:22:33:44:55:66")
]

detect_arp_spoof(arp_table)
