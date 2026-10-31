# Multi-Router Network Configuration Using Static Routing

## Project Overview

This project demonstrates a multi-router network topology built in Cisco Packet Tracer. It is designed to practice router configuration, IP networking, static routing, and connectivity verification in a simulated network environment.

## Objectives

- Build a network using multiple routers and switches.
- Connect end devices across different network segments.
- Practice IPv4 addressing and router interface configuration.
- Configure static routes to enable communication between networks.
- Verify network connectivity using diagnostic commands.

## Tools and Technologies

- **Cisco Packet Tracer** — Network simulation
- **Cisco IOS CLI** — Router configuration
- **IPv4** — Network addressing
- **Static Routing** — Manually configured routes
- **Ping and traceroute** — Connectivity troubleshooting

## Network Topology

The current topology includes:

- 3 routers
- 3 Cisco 2960 switches
- 9 PCs
- Router-to-router links
- Ethernet connections between routers, switches, and PCs
- ## Network Topology

The network contains three routers, three Cisco 2960 switches, and nine PCs connected across multiple network segments.

![Network Topology](screenshots/network-topology.png)

## Router Interface Verification

The router interfaces were checked using the Cisco IOS command:

```text
show ip interface brief
```

This command displays interface IP addresses and their operational status.

![Router Interface Verification](screenshots/router-interfaces.png)

## Routing Table Verification

The routing table was inspected using:

```text
show ip route
```

This command displays directly connected networks and any static routes installed in the routing table.

![Routing Table](screenshots/routing-table.png)

## Connectivity Testing

Connectivity was tested in the Packet Tracer environment. The results should be documented alongside the relevant test outputs.

## Key Learning Outcomes

- Configuring router interfaces with IPv4 addresses.
- Understanding directly connected networks and static routes.
- Inspecting interface status and routing tables.
- Troubleshooting connectivity in a simulated network.
- Documenting a network lab for technical review.

## Configuration and Testing

The project is intended to cover:

1. Router interface IP addressing.
2. Interface status verification.
3. Static route configuration.
4. Routing table inspection using `show ip route`.
5. Interface inspection using `show ip interface brief`.
6. Connectivity testing using `ping`.
7. Path verification using `traceroute`.

## Verification Status

The topology has been created in Cisco Packet Tracer. Detailed configuration outputs and connectivity test results will be added after each test is verified.

## Learning Outcomes

- Understanding how routers connect different networks.
- Learning how static routes direct traffic between networks.
- Reading routing tables and interface status.
- Troubleshooting network connectivity.
- Documenting network configurations in a reproducible format.

## Project File

Download `multi-router-static-routing.pkt` from this repository and open it with Cisco Packet Tracer to inspect the topology.

## Author

**Praveen Kumar**

B.Tech Cybersecurity Graduate | Aspiring SOC Analyst | Networking and Cybersecurity Learner

GitHub: https://github.com/Praveen420420
