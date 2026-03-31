# 🛡️ Wazuh SIEM Lab – File Integrity Monitoring

> Hands-on lab that was created as part of my journey of learning.

---

## 📌 Project Overview

This project documents the implementation and configuration that was done in Wazuh. **Wazuh** is an open source SIEM platform. In this project, I've primarily focused on setting up **File Integrity Monitoring (FIM)** which is a detection capability that can be used to identify unauthorized changes to system files, or randomly added files that weren't known by the user.

In this lab, I've learned what kind of monitoring can popup using FIM and how alerts work between the **Host**, **Wazuh**, and **Server**. 

---

## 🎯 Objectives

- Install Wazuh in a home lab environment (Ubuntu)
- Configure the Wazuh Agent
- Enable and Customize File Integrity Monitoring (FIM) for specific folder.
- Trigger and Observe Real-Time alerts from file created, deleted, and modified.
- Understand how FIM relates or correlates to real-world threat detections.

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Wazuh** | Open-source SIEM platform |
| **Wazuh Manager** | Central server for collecting and analyzing logs |
| **Wazuh Agent** | Installed on monitored endpoint |
| **Wazuh Dashboard** | Web UI for visualizing alerts and events |
| **VirtualBox / VMware** | Virtualization for lab environment |
| **Linux / Windows** | Operating systems used for endpoints |
