def detect_ip_spoof(packets, trusted_ips):
    alerts = []
    for pkt in packets:
        if pkt["src"] not in trusted_ips:
            alerts.append(f"Suspicious packet from {pkt['src']}")
    return alerts

packets = [{"src": "192.168.1.5"}, {"src": "10.0.0.99"}]
trusted = ["192.168.1.5"]

alerts = detect_ip_spoof(packets, trusted)
print("Alerts:", alerts)
