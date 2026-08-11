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


---

###🖥️ Featured RMM & Control Plane: FleetPulse

A native Windows **Remote Monitoring & Management (RMM)** and **IT Dispatch Engine** engineered for exception-based fleet triage, automated technician workload balancing, and one-click remote remediation.
```text
┌──────────────────────────────────────────────────────────┐
│                FLEETPULSE CONTROL PLANE                  │
│   (FastAPI • SQLite DB • Active Directory • Bearer Auth) │
└─────────────────────────────┬────────────────────────────┘
                              │
     ┌────────────────────────┴────────────────────────┐
     │ (Telemetry Heartbeats)                          │ (Tech Dispatch)
     ▼                                                 ▼
┌──────────────────────────┐              ┌──────────────────────────┐
│ FleetPulseAgent Service  │              │ Technician Desk (/tech)  │
│ (NSSM / Win32 Registry)  │              │ (Dedicated Task Queue)   │
└────────────┬─────────────┘              └────────────┬─────────────┘
             │                                         │
             └────────────────────┬────────────────────┘
                                  │ (Direct Remediate / RDP)
                                  ▼
                   ┌────────────────────────────┐
                   │ Target Endpoint Workstation│
                   │ (mstsc.exe / USOClient)    │
                   └────────────────────────────┘
