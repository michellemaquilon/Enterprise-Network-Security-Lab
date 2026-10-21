# Enterprise-Network-Security-Lab

Project Overview

This project simulates an enterprise network environment using Cisco Packet Tracer. The goal is to practice networking, infrastructure administration, and network security through hands-on configuration and testing.

Objectives

Design an enterprise network topology.

Configure VLANs and inter-VLAN routing.

Implement DHCP for network addressing.

Apply Access Control Lists (ACLs) to restrict network traffic.

Configure secure remote management using SSH.

Implement NAT/PAT and static NAT.

Host and test a web server in a DMZ.

Practice troubleshooting and incident response.

Technologies Used

Cisco Packet Tracer

Cisco IOS CLI

VLANs and trunking

Inter-VLAN routing

DHCP

Access Control Lists (ACLs)

SSH

NAT/PAT

DMZ architecture

GitHub Markdown documentation

Network Design

The simulated network uses multiple VLANs to separate different types of devices and services.

VLAN

Purpose

VLAN 10

Users

VLAN 20

IT

VLAN 30

Security

VLAN 40

Guest

VLAN 50

Servers

VLAN 60

DMZ

VLAN 99

Management

The network uses the 10.10.x.0/24 addressing scheme for its internal VLANs.

Security Controls

VLAN segmentation to separate network traffic.

ACLs to control communication between network segments.

SSH for secure remote device administration.

NAT/PAT for outbound network connectivity.

A DMZ to isolate the public-facing web server from internal systems.

Testing and Validation

Testing includes connectivity checks, network configuration verification, and access testing.

Evidence and results will be documented in the screenshots and documentation folders as the project progresses.

Incident Response

The incident-response portion of this project will simulate identifying suspicious activity, containing a compromised device, reviewing network access controls, and validating recovery.

Project Structure

screenshots/ — Visual evidence of network configurations and testing.

documentation/network-design.md — Network architecture and IP addressing.

documentation/security-controls.md — Security configurations and testing.

documentation/incident-response.md — Incident scenario, containment, and recovery.

Key Takeaways

This project provides hands-on practice with enterprise networking, network segmentation, security controls, troubleshooting, and technical documentation.

This documentation will be updated as additional configurations, tests, and incident-response activities are completed.
