# Reverse Proxy

## Question

What does a Reverse Proxy do and why is it used?

## Short Answer

A reverse proxy sits in front of one or more backend servers and intercepts client requests, directing them to the appropriate server. It is commonly deployed to distribute network load across multiple instances, terminate SSL/TLS encryption, and cache frequently accessed assets. By masking backend internal network topography, reverse proxies also enhance security against direct exposure.

## Simple Example

Client -> Nginx Reverse Proxy (Port 443 HTTPS) -> Internal Backend Services (Port 8000, 8001).

## Key Point

A reverse proxy protects and optimizes backend services by handling SSL termination, load balancing, and request routing.

<!-- date: 2026-10-27 -->
