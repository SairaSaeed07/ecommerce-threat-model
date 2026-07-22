# E-Commerce API Threat Model

## Overview

This repository contains a STRIDE Threat Model developed using Microsoft Threat Dragon for an E-Commerce REST API.

## Architecture

- Customer
- Order Service
- Customer Database
- Internal Cloud Trust Boundary

## Security Threats

- User Account Impersonation
- Session Hijacking
- Order Tampering
- Unauthorized Order Access
- Sensitive Data Exposure
- Database Modification
- MITM Attack
- Replay Attack
- Data Manipulation

## Security Controls

- MFA
- HTTPS
- TLS 1.3
- JWT
- RBAC
- AES-256 Encryption
- Database Access Control
- Audit Logs
- Digital Signatures

## Files

- Threat Dragon JSON
- PDF Report
- Architecture Diagram

## Tools

- Microsoft Threat Dragon
- STRIDE Methodology
