---
title: "Visit Directly"
date: 2021-08-31
weight: 4
description: >
---

If you want to send the requet to downstream that address determined, you can choose visiting directly without service discovery.

Client can specify downstream address in two forms:

- Using `WithHostPort` Option, supports two parameters:
  - Normal IP address, in the form of `host:port`, support `IPv6`
  - Sock file address, communicating with UDS (Unix Domain Socket) 
- Using `WithURL` Option, the parameter must be valid HTTP URL address