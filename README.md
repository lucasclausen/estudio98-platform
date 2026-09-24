# Estúdio 98 Platform

A full-stack operating platform built for a boutique fitness studio.

The platform brings client management, onboarding, plan requests, credits, notifications and administrative workflows into one system.

## What I Built

* Client and admin portals
* Role-based authentication
* Client onboarding
* Identity verification workflow
* Plan requests
* Credit management and payment reversals
* Notifications
* Password recovery
* Administrative workflows
* Database migrations
* Automated testing

## Tech Stack

* Next.js 16
* TypeScript
* Supabase
* PostgreSQL
* Vercel

## Why I Built It

The goal was to replace fragmented manual processes with a structured operating system that could handle both the client experience and the studio's internal workflows.

A key part of the project was designing the underlying states and business logic rather than simply creating an interface.

For example, the system needs to understand:

Client → Authentication → Onboarding → Account State → Plan Request → Approval → Credits → Activity

while allowing administrators to manage exceptions and changes safely.

## Product Areas

### Client Portal

Clients can manage their account, complete onboarding, request plans, view their credits and receive relevant updates.

### Admin Portal

Studio administrators can manage clients, requests, credits, account states and operational exceptions from a central interface.

### Authentication

The platform includes account invitations, secure login, password recovery and role-based access.

### Operational Logic

The platform handles workflows including credit changes, reversals, notifications and state transitions while maintaining a clear record of user actions.

## Architecture

Frontend
↓
Next.js / TypeScript
↓
Supabase Authentication
↓
Application Logic
↓
PostgreSQL / Supabase
↓
Notifications and operational workflows

## Status

The platform has been developed as a real operating product rather than a standalone prototype.

This public repository is a portfolio version of the project. Production credentials, private business information and customer data are intentionally excluded.
