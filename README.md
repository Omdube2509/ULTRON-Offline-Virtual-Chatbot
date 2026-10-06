# ULTRON – Offline Virtual Chatbot

> **Think. Process. Respond.**

ULTRON is an **offline virtual chatbot and AI assistant simulator** developed in **C++ using Object-Oriented Programming (OOP)** concepts.

The project simulates the basic behavior of a conversational assistant without requiring an internet connection, external APIs, databases, or real AI models.

---

## 📌 About the Project

ULTRON is designed as a beginner-friendly OOP project that demonstrates how concepts such as **classes, objects, encapsulation, inheritance, polymorphism, constructors, destructors, function overloading, static members, friend functions, and arrays of objects** can be combined to create an interactive console-based application.

The chatbot accepts predefined user queries, processes them using programmed logic, and provides suitable responses.

It also includes a simple **login/authentication system**, **session management**, and a **credit system** to make the chatbot experience more interactive.

---

## 🎯 Problem Statement

Traditional beginner-level programming projects often focus on management systems such as restaurants, hospitals, or libraries.

The objective of ULTRON is to create a more interactive application that demonstrates fundamental **C++ Object-Oriented Programming concepts** through an offline conversational chatbot simulation.

The system should:

- Accept user input.
- Identify predefined queries.
- Generate programmed responses.
- Provide basic chatbot commands.
- Manage user sessions.
- Provide a limited number of credits per session.
- Demonstrate important OOP concepts in a practical application.

---

## 🎯 Objectives

- To develop an offline virtual chatbot using C++.
- To apply Object-Oriented Programming concepts in a practical project.
- To implement a simple authentication system.
- To process predefined conversational queries.
- To implement a session-based credit system.
- To provide an interactive and user-friendly console interface.
- To understand how different OOP concepts work together in a single application.

---

## ⚙️ How ULTRON Works

```text
              ┌─────────────────┐
              │      START      │
              └────────┬────────┘
                       ↓
              ┌─────────────────┐
              │     LOGIN       │
              └────────┬────────┘
                       ↓
              ┌─────────────────┐
              │ Authentication  │
              └────────┬────────┘
                       ↓
              ┌─────────────────┐
              │  Start Session  │
              │  3 Credits      │
              └────────┬────────┘
                       ↓
              ┌─────────────────┐
              │ Enter Query     │
              └────────┬────────┘
                       ↓
              ┌─────────────────┐
              │ Process Query   │
              └────────┬────────┘
                       ↓
              ┌─────────────────┐
              │ Generate Reply  │
              └────────┬────────┘
                       ↓
              ┌─────────────────┐
              │ Credits Remain? │
              └──────┬─────┬────┘
                     │Yes  │No
                     ↓     ↓
                Next Query  End