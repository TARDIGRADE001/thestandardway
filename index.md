# The Standard

> *A collection of decades of experience in the engineering industry*

Welcome to **The Standard** - your comprehensive guide to software engineering excellence. This living document represents hundreds of years of collective experience from engineers worldwide, distilled into practical principles and patterns that will guide you through the vast ocean of software development knowledge.

## What is The Standard?

The Standard is not just another programming guide—it's a philosophy, a methodology, and a compass for engineers who want to build systems that can change the world. It's built on the understanding that technology evolves rapidly, but the principles of good engineering remain constant.

### Our Core Philosophy: The Tri-Nature of Everything

At the heart of The Standard lies a simple yet powerful theory: everything in this world comprises three main categories:

- **Dependencies** - What the system relies on to function
- **Purposes** - What the system is designed to achieve  
- **Exposures** - How the system presents itself to the outside world

This pattern repeats at every scale, from the smallest components to the largest systems, creating a fractal architecture that's both intuitive and scalable.

## Architecture Overview

The Standard defines a clear, layered architecture that separates concerns and promotes maintainability:

```
┌─────────────────┐
│    Exposers     │ ← Controllers, UIs, Communication Protocols
├─────────────────┤
│    Services     │ ← Business Logic Layer
│  ┌───────────┐  │
│  │Foundation │  │ ← Validation & Primitive Operations
│  │Processing │  │ ← Higher-Order Business Logic
│  │Orchestrate│  │ ← Complex Multi-Entity Operations
│  │Aggregation│  │ ← Single Point of Contact
│  └───────────┘  │
├─────────────────┤
│    Brokers      │ ← Integration with External Resources
└─────────────────┘
```

## Core Principles

### 🎯 People-First
Code must be simple, readable, and understandable by entry-level engineers. We build for humans, not just machines.

### 🔄 Rewritability  
Every system should be easily rewritable as business requirements evolve. Assume change is constant.

### 🏗️ Mono-Micro
Build monolithic systems with a modular mindset—every flow should be extractable as a microservice.

### 👶 Level 0
Code must be understandable by newcomers to the industry. They are our measure of success.

### ✈️ Airplane Mode
Systems should run entirely offline on a developer's machine without cloud dependencies.

### 📖 Open Code
Everything should be publicly available to foster learning and collaboration.

### 👥 No Toasters
The Standard is taught person-to-person, not enforced by tools or analyzers.

## The Three Pillars

### 1. Brokers
*The integration layer between your business logic and the outside world*

Brokers are thin wrappers around external dependencies—databases, APIs, file systems, or any external resource. They provide a local interface while abstracting away the complexities of external integrations.

**Key Characteristics:**
- Implement local interfaces
- No flow control logic
- Own their configurations
- Disposable and replaceable

### 2. Services  
*The heart of your business logic*

Services contain all business logic and are categorized into four types:

- **Foundation Services**: Validation and primitive operations
- **Processing Services**: Higher-order business logic combining primitives
- **Orchestration Services**: Complex operations across multiple entities
- **Aggregation Services**: Single points of contact for exposure layers

**Key Rules:**
- Single responsibility per service
- Pure business language
- Comprehensive validation (structural, logical, external)

### 3. Exposers
*Your gateway to the outside world*

Exposers make your business logic accessible through various protocols and interfaces:

- **Communication Protocols**: REST APIs, gRPC, GraphQL
- **User Interfaces**: Web apps, mobile apps, desktop applications
- **I/O Components**: Background services, daemons

## Getting Started

Ready to implement The Standard in your projects? Here's your roadmap:

1. **[Start with the Theory](0.%20Introduction/0.0%20The%20Theory.md)** - Understand the foundational principles
2. **[Learn the Principles](0.%20Introduction/0.2%20Principles.md)** - Master the core guidelines  
3. **[Implement Brokers](1.%20Brokers/1.%20Brokers.md)** - Build your integration layer
4. **[Design Services](2.%20Services/2.%20Services.md)** - Create your business logic
5. **[Build Exposers](3.%20Exposers/3.%20Exposers.md)** - Expose your functionality

## Why Follow The Standard?

> *"The Standard helped me think out of the box while designing any system."*  
> **— Awais Shabir, Lead Software Engineer**

> *"Better separation of concerns. Unification of project templates between different teams."*  
> **— Raúl Lorenzo Boulllosa, Software Engineer**

Engineers worldwide have adopted The Standard to:

- ✅ **Reduce complexity** and cognitive load
- ✅ **Improve code quality** and maintainability  
- ✅ **Accelerate development** with clear patterns
- ✅ **Enable better collaboration** through shared vocabulary
- ✅ **Build scalable systems** that stand the test of time

## The Journey Ahead

The Standard is not a destination—it's a journey of continuous improvement. As you implement these principles, you'll discover that they extend beyond software into management, relationships, and life itself.

Whether you're a seasoned architect or just starting your engineering journey, The Standard provides the compass you need to navigate the complex world of software development.

---

**Ready to transform your engineering approach?** Dive into the documentation and join thousands of engineers building better software with The Standard.

[Explore the Documentation →](0.%20Introduction/0.%20Introduction.md)
