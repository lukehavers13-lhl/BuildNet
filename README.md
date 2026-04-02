# BuildNet AI Systems

This repository contains the core systems, prompts, and workflows being developed under BuildNet AI.

The focus is on building practical AI-powered tools for real business use, particularly within retail and product-based environments.

---

## Current Projects

### Brand Tone Generator (in collaboration with Hot Cognition)

This system is responsible for generating structured brand tone documents.

These documents define:
- voice
- style
- language constraints
- positioning

The output of this system feeds directly into the Product Description Engine.

Most of the critical and nuanced work sits within this layer, as it determines the quality, consistency, and accuracy of all downstream content.

---

### Product Description Engine

This system generates high-quality, structured product descriptions.

It operates using:
- predefined output structures
- SEO/AEO-informed rules
- brand tone documents produced by the Brand Tone Generator

The goal is to create consistent, scalable, and production-ready product content.

---

### Price Manager (in development)

A more technically advanced system focused on pricing logic and management.

This project is being led by Hot Cognition, with BuildNet AI contributing and learning throughout the process.

The system aims to handle complex pricing environments, including:
- multiple suppliers
- varying cost structures
- dynamic pricing logic

---

## Repository Structure

- prompts → reusable AI prompts and system logic  
- workflows → system designs, flows, and architecture  

---

## Purpose

This repository acts as:
- a system library  
- a development workspace  
- a record of evolving AI tools and methodologies  

The long-term goal is to build scalable, reusable AI systems that deliver real operational value.
