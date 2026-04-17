# Linux DNS Troubleshooting Lab

## Overview
In this lab, I worked through DNS troubleshooting inside an Ubuntu virtual machine. The goal was to understand how Linux handles hostname resolution, DNS configuration, and connectivity testing.

## What I practiced
- Troubleshooting DNS resolution issues
- Editing `/etc/hosts`
- Working with `/etc/resolv.conf`
- Testing connectivity with `ping`
- Distinguishing between network connectivity issues and DNS resolution issues

## Problem
The system was unable to resolve `google.com`, resulting in:

```bash
ping: google.com: Temporary failure in name resolution
