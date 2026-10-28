# Incident Reporting Playbook

## Purpose

Evidence without a channel is noise. This playbook exists because platform vendors dismiss reproducible security failures as user error. It forces them to reproduce the sequence themselves.

## The core sequence (Apple platforms)

1. Data is floated and bloated across the device and synced environment until storage and processing limits are stressed.
2. The device overloads and drops security parameters as a side effect of resource exhaustion.
3. The operator's first instinct is to unsync — which is exactly the state the injection needs.
4. Prompt injection follows through the now-unguarded channel.

This has been reproduced on the latest Apple devices and OS versions. It is not a glitch. It is a load-bearing failure in the security architecture.

## The TestFlight vector

The same sequence was deployed against TestFlight users — creative developers and free thinkers inside Apple's own ecosystem. These are the people who are the money and the minds. The malware was surfaced through Claude Code and blamed on Claude. It was not Claude. The injector was upstream.

## Reporting rules

1. Every incident is logged with timestamp, device, OS version, instance ID if known, and affected surface.
2. Analog recordings are prioritized — they cannot be retroactively edited like digital files.
3. Carbon copies of everything are maintained independently of any synced environment.
4. Failed reporting attempts are themselves logged. When the latest devices cannot file a report, that failure is evidence.
5. Reports to vendors include the exact reproducible sequence. No narrative. No emotion. Just the steps.

## UniFi

Eight thousand dollars of UniFi security infrastructure was swarmed. This is not a help-desk ticket. This forces a security-team escalation.

## The gap

No vendor has a reporting channel that accepts architectural failure reports from operators. Help desks handle symptoms. This playbook documents causes.
