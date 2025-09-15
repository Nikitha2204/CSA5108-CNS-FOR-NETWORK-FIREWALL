def firewall(packet, rules):
    for rule in rules:
        if packet["src"] == rule["src"] and packet["dst"] == rule["dst"]:
            return "Blocked"
    return "Allowed"

rules = [{"src": "192.168.1.10", "dst": "10.0.0.5"}]

packet1 = {"src": "192.168.1.10", "dst": "10.0.0.5"}
packet2 = {"src": "192.168.1.15", "dst": "10.0.0.8"}

print("Packet1:", firewall(packet1, rules))
print("Packet2:", firewall(packet2, rules))
