def packet_sniffer(packets):
    for pkt in packets:
        print(f"Captured packet: SRC={pkt['src']} DST={pkt['dst']} DATA={pkt['data']}")

packets = [
    {"src": "192.168.1.1", "dst": "8.8.8.8", "data": "GET /index.html"},
    {"src": "192.168.1.2", "dst": "8.8.4.4", "data": "PING"}
]

packet_sniffer(packets)
