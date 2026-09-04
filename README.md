# The Wrong Address

Author: Sneegha

> Difficulty: `<easy>`

A beginner-friendly DNS investigation challenge using Wireshark.

Flag: `SPISECTF{trust_but_verify}`

## Backstory

The SPISE security team noticed unusual activity coming from an employee workstation.

The employee claims they only visited common websites during work hours, but the network logs tell a different story.

A packet capture was taken before the machine was isolated.

Your task is to investigate the DNS requests, identify the domain that does not belong, and recover the hidden flag.

Sometimes, the smallest difference can reveal the biggest threat.

## Challenge File

`dns_capture.pcapng`

## Requirements

Wireshark is required to inspect the packet capture.

Download Wireshark: https://www.wireshark.org/

## Instructions

1. Open `dns_capture.pcapng` in Wireshark.
2. Focus on the DNS traffic.
3. Carefully inspect the requested domain names.
4. Identify the suspicious domain.
5. Examine the relevant DNS response to recover and submit the flag.

