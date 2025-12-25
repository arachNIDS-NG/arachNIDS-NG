# arachNIDS-NG

[![Status](https://img.shields.io/badge/Status-In_Development-orange.svg)]()
[![Offline](https://img.shields.io/badge/Privacy-100%25_Offline-green.svg)]()
[![License](https://img.shields.io/badge/License-MIT-blue.svg)]()

Modern, offline first IDS signature knowledgebase for **Snort** and **Suricata**. 

> Continuation of the `arachNIDS` project — now CLI-native, versioned, and built for modern DevSecOps workflows.

---

## Overview

**arachNIDS-NG** is a local toolkit to manage, test, and deploy Intrusion Detection System (IDS) rules. It eliminates the friction of managing raw rule files by using a structured **YAML-native format** that can be indexed, searched, and compiled into engine-specific syntax.

### Why arachNIDS-NG?
- **Unified Logic:** Write a detection once; export it for Snort 2, Snort 3, or Suricata.
- **Verification:** Stop "deploy and pray." Test your rules against PCAPs locally.
- **Privacy:** Designed for air-gapped environments. No telemetry, no cloud dependencies.

---

## Status: In Development

This project is currently under active development. 

**Coming Soon:**
* Full schema specification for IDS rules.
* CLI tool for rule indexing and searching.
* Automated translation logic for Snort/Suricata.

***Star** this repo to follow the progress.*
