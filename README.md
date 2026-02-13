# 🚩 TryHackMe - Basic Pentesting Writeup
**Date:** 12-02-2026  
**Difficulty:** Easy    

---

## 📑 Summary
This is a machine that allows you to practise **web app hacking** and **privilege escalation**.
---

## 🔍 1. Enumeration

### 1.1 Port Scanning (Nmap)
Initial scan to identify open ports and services:
```bash
nmap -sC -sV -T4 -oX init_scan_BasicPentesting.xml [VICTIM_IP]
