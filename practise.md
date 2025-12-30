demo
Agent Execution Instructions

Start with architecture planning

Folder structure

API structure

Auth flow

Implement authentication first

Signup

Login

Role-based guards

Build user features

Build admin dashboard

Secure all sensitive routes

Provide clean, commented, production-grade code

Include environment variables

Provide setup & run instructions

Do NOT skip role enforcement

Ask questions only if absolutely necessary

🔹 Deliverables

Full source code

Database schema

Auth flow explanation

API routes

Environment variable template

Local run instructions

Future improvements section

🔹 Start Execution Now

Begin by:

Defining system architecture

Creating database schema with roles

Setting up authentication and authorization flow

🔹 Optional Enhancements (Later)

Multi-admin support

Admin approval flow

Role-based UI rendering

Audit logs

Two-factor authentication

If you want, I can also:

Make a short ultra-compact version

Customize for MERN only

Adapt for headless commerce

Write a Claude-optimized agent memory plan

Just say the word 🚀

give me a short summery of the above prompt

Short Summary

The prompt instructs Claude Sonnet 4.5 (Agent mode) to build a production-ready e-commerce website with role-based authentication. Both Users and Admins can sign up and log in, but have different permissions. Users can browse products, manage carts, place orders, and view their history, while Admins access a protected dashboard to manage products, orders, and users. The system must use a modern full-stack architecture, enforce strict role-based access control, and deliver complete source code, database schema, authentication flow, and setup instructions.

give me a step wise prompt agent can understand better

Below is a step-by-step, agent-friendly prompt designed specifically for Claude Sonnet 4.5 (Agent mode).
It breaks the work into clear phases, so the agent can reason, plan, and execute more reliably.

✅ Step-Wise Prompt for E-commerce Website (User + Admin Roles)
Agent Role

You are a senior full-stack engineer and system architect building a production-ready e-commerce website.

🔹 STEP 1: System Planning

Propose overall system architecture

Decide:

Frontend framework

Backend/API approach

Database

Authentication strategy

Output:

High-level architecture diagram (text)

Folder structure

Tech stack justification

🔹 STEP 2: Database & Models

Design the database schema with role support.

Required Models:

User

id

name

email

password (hashed)

role (USER, ADMIN)

Product

Category

Order

OrderItem

Cart

Output:

Schema definitions

Relationships

Indexing decisions

🔹 STEP 3: Authentication & Authorization

Implement secure authentication.

Requirements:

Signup & login for both Users and Admins

JWT / NextAuth based authentication

Role-based access control (RBAC)

Middleware to protect routes

Output:

Auth flow explanation

API routes for signup/login

Role guard logic

🔹 STEP 4: User Functionality

Build User-side features:

Browse products

Search & filter

Product detail page

Cart management

Checkout flow

Order history

Profile management

Output:

UI components

API endpoints

Business logic

🔹 STEP 5: Admin Functionality

Build Admin-only features:

Admin login/signup

Admin dashboard

Product CRUD

Category management

Order management

User management

Rules:

Admin routes only accessible to ADMIN role

Enforce backend and frontend guards

🔹 STEP 6: Payments & Orders

Integrate Stripe (test mode) or mock gateway

Secure checkout process

Order creation & status updates

🔹 STEP 7: Security & Validation

Input validation

Password hashing

Protected APIs

Error handling

Basic rate limiting

🔹 STEP 8: Finalization

Environment variables example

Setup & run instructions

Deployment readiness

Summary of completed features

Suggestions for future improvements

🔹 Execution Rules for the Agent

Work step by step

Complete one step before moving to the next

Explain reasoning briefly

Write clean, commented code

Ask questions only if critical

Do NOT skip role enforcement

🔹 Start Now

Begin with STEP 1: System Planning

If you want, I can also:

Convert this into a checklist-style agent prompt

Make a very short ultra-minimal agent prompt

Adapt it for mobile-first or API-only backend

Just tell me 👍
