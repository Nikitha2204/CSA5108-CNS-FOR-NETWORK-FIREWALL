def scan_ports(host, ports):
    print(f"Scanning {host}...")
    for port in ports:
        if port in [22, 80]:
            print(f"Port {port}: OPEN")
        else:
            print(f"Port {port}: CLOSED")

scan_ports("localhost", [21,22,23,80,443])
