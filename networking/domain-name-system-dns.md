# Domain Name System (DNS)

## Question

What is DNS and why does a web browser need it?

## Short Answer

The Domain Name System (DNS) translates human-readable domain names into numerical IP addresses that computers use to identify each other on the network. When you enter a web address into a browser, a DNS resolver queries authoritative nameservers in a hierarchical tree until it resolves the IP address. Without DNS, users would be forced to memorize complex 32-bit IPv4 or 128-bit IPv6 numbers for every website.

## Simple Example

Typing `example.com` causes your OS resolver to query DNS servers, which return IP address `93.184.216.34` before any HTTP connection starts.

## Key Point

DNS acts as the phonebook of the Internet by mapping human-readable hostnames to numeric IP addresses.

<!-- date: 2026-10-02 -->
