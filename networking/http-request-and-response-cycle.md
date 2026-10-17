# HTTP Request and Response Cycle

## Question

What is the HTTP Request and Response Cycle and how does it function?

## Short Answer

The Hypertext Transfer Protocol (HTTP) is an application-layer protocol operating on a request-response cycle between web clients and servers. A client sends an HTTP request containing a method (such as GET or POST), a target URL, headers, and an optional body. The server processes the request and returns an HTTP response containing a numeric status code (such as 200 OK or 404 Not Found), response headers, and payload content.

## Simple Example

Browser sends: `GET /index.html HTTP/1.1`
Server responds: `HTTP/1.1 200 OK` followed by HTML content.

## Key Point

HTTP operates as a stateless request-response protocol driving communication across the World Wide Web.

<!-- date: 2026-10-17 -->
