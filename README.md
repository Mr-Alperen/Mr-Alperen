<p align="center">
  <img src="./aminike.jpg" alt="Profile header" width="1080"/>
</p>

<br/>

---

# Alperen Erkan

This page was not written to introduce me.

It exists to describe a way of thinking about systems  
that assumes hostility, failure, and misuse as defaults.

If that framing feels excessive,  
you are not the intended audience.

---

## Position

I work where software becomes infrastructure  
and infrastructure becomes policy.

Where abstractions stop protecting developers  
and start protecting assumptions.

Where correctness is defined not by success paths,  
but by what remains intact after failure.

---

## Orientation

My work lives at the intersection of:

- operating system design
- low-level security
- virtualization as a trust boundary
- offensive and defensive cyber operations

I am not interested in systems that behave well  
only when treated gently.

I am interested in systems that remain intelligible  
after they have been attacked.

---

## Core Principles

I evaluate systems according to a small set of non-negotiables:

- **Explicit trust**  
  Nothing is trusted implicitly. Every boundary is declared.

- **Deterministic isolation**  
  Separation must hold under stress, not just in theory.

- **Failure-first reasoning**  
  A system is only understood once its failure modes are mapped.

- **Observability without leakage**  
  Everything is visible. Nothing escapes.

- **Containment over prevention**  
  Compromise is assumed. Damage is bounded.

---

## Languages & Low-Level Tooling

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/c/c-original.svg" width="40" alt="C"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" width="40" alt="C++"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rust/rust-original.svg" width="40" alt="Rust"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" width="40" alt="Java"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="40" alt="Python"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bash/bash-original.svg" width="40" alt="Shell"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" width="40" alt="System / Assembly"/>
</p>

<p align="center">
  <em>
    Selected for control, auditability, and predictable behavior under failure.
  </em>
</p>

I do not treat languages as identities.  
They are instruments.

Each is chosen based on how honestly it exposes:
memory, time, authority, and cost.

---

## Major Systems Work

### NeOx OS  
**Sovereign Operating System for State-Level Cyber Operations**  
_Status: Active development · Horizon: 2026_  
_Deployment context: Critical government institutions_

NeOx OS is a ground-up operating system designed for environments  
where compromise is not a possibility, but an expectation.

It is not a hardened distribution.  
It is not a derivative of an existing OS family.  
It is not open by design.

Both the **kernel** and the **hypervisor** are implemented end-to-end by me.

No inherited trust.  
No commodity assumptions.

---

## Foundational Premise

> **Assume compromise.  
> Design for survival.  
> Preserve truth under attack.**

NeOx OS rejects the idea that security can be layered on top of convenience.

Instead, it treats **virtualization and isolation as the primary execution model**,  
not as optional features.

---

## Kernel & Hypervisor Co-Design

The most demanding aspect of NeOx OS lies at its core.

The kernel and hypervisor are not stacked abstractions.  
They are co-designed components, evolving together as a single security fabric.

### Kernel Responsibilities

- Explicit memory ownership and lifetime tracking
- Controlled privilege transitions
- Deterministic scheduling under hostile conditions
- Minimal implicit behavior

### Hypervisor Responsibilities

- Hard isolation between trust domains
- Mediation of all cross-domain interaction
- Enforcement of execution boundaries
- Containment during partial compromise

There is no “safe” layer.

Every layer is adversarial by default.

---

## Operational Scope

NeOx OS is engineered explicitly for:

- **Offensive cyber operations**
- **Defensive monitoring and containment**
- **Red-team / blue-team parity within the same platform**

Current internal capability scope includes:

- ~2600 offensive / hacking tools
- ~203 defensive, monitoring, and response tools
- Mandatory virtualization for all sensitive workloads
- Zero reliance on user discipline for security guarantees

Security is structural, not behavioral.

---

## The Black Box Architecture (Proprietary)

At the center of NeOx OS lies the **Black Box**  
— a proprietary system of my own design.

The Black Box is not a logging system.  
It is not an EDR.  
It is not an add-on.

It is a **parallel authority** operating alongside  
the kernel and hypervisor.

### Role & Position

- Co-operates with kernel and hypervisor
- Observes all critical system activity
- Cannot be bypassed, disabled, or deceived by domains
- Acts as the final arbiter of truth

### Capabilities

- Continuous system-wide observation
- AI-driven behavioral analysis
- Forensic completeness without data loss
- Full traceability of actions and state changes

All sensitive information is stored **only** within the Black Box.

- Double-layer **AES-256** encryption
- No unauthorized extraction
- No unobserved replication
- No silent exfiltration

Even under partial system compromise,  
the integrity of stored data is preserved.

---

## Data Sovereignty Model

NeOx OS is explicitly hostile to uncontrolled data movement.

- No data leaves the system unobserved
- No copy exists without traceability
- No insider is implicitly trusted

The system is designed to resist misuse  
by both attackers **and** authorized operators.

---

## Security Position

NeOx OS makes three statements simultaneously:

1. **Modern operating system security assumptions are insufficient.**  
2. **Compromise is inevitable; loss is not.**  
3. **A system that cannot explain its failure is already broken.**

This platform does not aim to be “unbreakable”.

It aims to remain truthful  
after it has been attacked.

---

## Experience (Context Only)

My work has been associated with environments  
where correctness, security, and survivability are mandatory:

- HAVELSAN  
- ASELSAN  
- NASA  
- MIT  
- European Space Agency (ESA)

These names are context, not credentials.

Constraints matter more than prestige.

---

## On Abstractions

Abstractions are useful until they hide:

- cost
- state
- authority
- failure propagation

When that happens,  
they cease to be tools  
and become liabilities.

I routinely dismantle abstractions  
until the system becomes explainable again.

---

## Closing

I do not optimize for visibility.  
I do not optimize for speed.

I optimize for systems that remain intelligible  
after they have been stressed, attacked,  
and partially broken.

If this page feels unresolved,  
that is intentional.

Some systems should never look finished  
until they have survived failure.
