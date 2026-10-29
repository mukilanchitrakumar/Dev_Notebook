# TCP Three-Way Handshake

## Question

How does TCP Three-Way Handshake work and what problem does it solve?

## Short Answer

TCP uses a three-way handshake (SYN, SYN-ACK, ACK) to establish a reliable connection between two endpoints before normal data transfer begins. This process synchronizes initial sequence numbers and verifies that both client and server can send and receive data. Once completed, a full-duplex transmission channel is established.

## Simple Example

Client sends SYN (Seq=100) -> Server replies SYN-ACK (Seq=300, Ack=101) -> Client sends ACK (Ack=301). The connection is now established.

## Key Point

The handshake establishes the connection parameters and sequence numbers so subsequent packets can be tracked reliably.

<!-- date: 2026-10-29 -->
