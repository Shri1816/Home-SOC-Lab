
# Home SOC Lab – Network Setup & Connectivity Test

## Project Overview
This project demonstrates the creation of a beginner cybersecurity home lab using VirtualBox.  
The lab is to create a small private network to practice SOC monitoring, penetration testing, and incident detection.

---

## Objectives
- Install VirtualBox Oracle
- Create Kali Linux VM (Attacker Machine)
- Create Windows VM (Victim Machine)
- Create Ubuntu VM (Log Server)
- Configure internal network
- Test connectivity between virtual machines

---

## Lab Architecture

Attacker Machine → Kali Linux  
Victim Machine → Windows 
Ubuntu Machine → Log Server

All three machines connected using **Internal Network**

---

## Step 1 — Install VirtualBox
VirtualBox was installed to create the virtual lab environment.

---

## Step 2 — Create Kali Linux VM
Kali Linux is used as the attacker machine for security testing.

---

## Step 3 — Create Windows VM
Windows machine acts as the victim machine.

---

## Step 4 — Create Ubuntu VM
Ubuntu machine acts as the Log Server when needed.

---

## Step 5 — Configure Internal Network
Three VMs were connected to the same internal network in VirtualBox.

---

## Step 6 — Verify IP Address

a] Kali Linux IP

b] Windows IP

c] Ubuntu IP

---

## Step 7 — Connectivity Test

a] Ping from Kali → Windows

b] Ping from Kali → Ubuntu

---

## Result
virtual machines successfully Connected with each other and are ready to Communicate.  
The lab network is ready for penetration testing and SOC monitoring labs.

