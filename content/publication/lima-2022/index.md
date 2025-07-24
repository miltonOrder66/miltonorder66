---
title: Beholder – A CEP-based intrusion detection and prevention systems for IoT environments
authors:
- Milton Lima
- Ricardo Lima
- Fernando Lins
- Michel Bonfim
date: '2022-01-01'
publishDate: '2025-07-24T16:51:38.026894Z'
publication_types:
- article-journal
publication: '*Computers & Security*'
doi: https://doi.org/10.1016/j.cose.2022.102824
abstract: IoT devices are vulnerable to security threats. The connectivity among such
  devices presents opportunities for cybercriminals to perform different types of
  attacks. In IoT, application layer protocols play an important role. They form the
  basis of communications between applications and services. Security is an optional
  design aspect in application layer protocols, leading developers to neglect these
  security settings, or others may lack security mechanisms in their standard configuration.
  This paper introduces Beholder, an Intrusion Detection and Prevention System (IDPS)
  to prevent attacks that exploit the vulnerabilities in the MQTT (Message Queue Telemetry
  Transport) and CoAP (Constrained Application Protocol) protocols. Most IoT systems
  adopt MQTT or CoAP. Beholder exploits the Complex Event Processing (CEP) technology
  to analyze data streams and detect attacks on IoT applications that use the MQTT
  and CoAP protocols. Beholder is the first IDS that relies on CEP technology to detect
  attacks on MQTT and CoAP protocols in IoT environments to the best of our knowledge.
  This work introduces a real scenario for the evaluation process, performing attacks
  on a smart home. Initially, we validated the quality of our IDS, comparing it against
  the well-known Snort IDS. Since Snort can only handle attacks on TCP, we restricted
  the experiment to attacks on this protocol. Results demonstrated that Snort achieved
  three 9s of precision, while Beholder reached a precision of four 9s. The experiment
  to evaluate Beholder’s precision for the MQTT and CoAP protocols revealed that Beholder
  obtained 100% precision for High QoS Flood (MQTT) and the Error Flood(CoAP).
tags:
- Security
- Intrusion detection systems
- IoT
- CEP
- MQTT
- CoAP
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0167404822002188
---
