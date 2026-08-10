# Hi there, I'm Keith 👋 🛠️

An Electronics and Computer Engineer focused on building low-level defense daemons, zero-trust cryptographic architectures, and real-time security control planes.

---

### 🛡️ Featured Security Ecosystem: ApexOS Suite

I've built a modular, inter-connected security stack engineered for real-time threat isolation, honeypot deception, and tamper-evident audit logging:

```text
 ┌────────────────────────────────────────────────────────────────────────┐
 │                      APEX OS COMMAND CENTER                            │
 │         (Real-Time WebSockets • FastAPI Orchestrator • Tailwind)       │
 └───────────────────────────────────┬────────────────────────────────────┘
                                     │
      ┌──────────────────────────────┼──────────────────────────────┐
      │                              │                              │
      ▼                              ▼                              ▼
┌───────────┐                  ┌───────────┐                  ┌───────────┐
│ NYCTOSEC  │ <── Unix Sock ─> │  SPECTRE  │                  │ CIPHERVAULT│
│ (IPS Engine)                 │ (Honeypot)│                  │(Secrets)  │
└─────┬─────┘                  └─────┬─────┘                  └─────┬─────┘
      │                              │                              │
      └──────────────────────────────┼──────────────────────────────┘
                                     │
                                     ▼
                          ┌─────────────────────┐
                          │       AEGISDB       │
                          │(Crypto Event Store) │
                          └─────────────────────┘
