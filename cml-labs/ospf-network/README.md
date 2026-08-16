# Multi-Area Enterprise OSPF & GRE WAN Architecture (see topology below)

A production-grade, 5-node Enterprise WAN simulation designed and built in **Cisco Modeling Labs (CML)**. This project demonstrates advanced control plane engineering, GRE overlay tunneling across a simulated WAN transport, multi-area OSPF routing, site optimization using **Totally Stubby Areas**

---

## Technical Overview & Design Philosophy

Modern enterprise networks separate the **Transport Underlay** (physical connectivity) from the **Service Overlay** (encapsulated routing control planes). This architecture implements a classic Hub-and-Spoke WAN design connecting a Corporate Headquarters (HQ) to three regional branches and one downstream remote sub-site.

## How to Run in it for yourself in Cisco Modeling Labs (CML)

1. Download the [`cml-ospf-wan-lab.yaml`](./cml-ospf-wan-lab.yaml) file from this repository. 
2. In CML, click **Import** on the Dashboard and select the YAML file.

<img width="1256" height="669" alt="Screenshot 2026-08-16 at 2 12 15 PM" src="https://github.com/user-attachments/assets/b2d32825-fb64-48da-b866-ec1e5ccde854" />
