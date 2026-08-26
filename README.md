<div align="center">

# `sameer@umass:~$ whoami`

### SAMEER KRISHNA

`Computer Science @ UMass Amherst`

**I like understanding how things work underneath the abstractions — and then building them myself.**

<br>

```text
╭──────────────────────────────────────────────────────────────╮
│                                                              │
│   SYSTEMS        NETWORKS        ARCHITECTURE                │
│   COMPUTATION    QUANTUM         CURIOSITY                   │
│                                                              │
│   status :: LEARNING / BUILDING / EXPLORING                 │
│                                                              │
╰──────────────────────────────────────────────────────────────╯
```

</div>

---

## `./interests`

```text
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   [01] SYSTEMS PROGRAMMING                                  │
│   [02] COMPUTER ARCHITECTURE                                │
│   [03] COMPETITIVE PROGRAMMING                              │
│   [04] QUANTUM COMPUTING                                    │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### `./languages`

`Python` · `C` · `SQL`

---

## `./projects`

### `01 :: background-service-manager`

> A personal service-management system built with Tkinter, designed to run and control background functionality across my machine.

```text
MUSIC
│
├── AutoPause
│   └── automatically pauses music when other media is detected
│
├── IntervalSkipper
│   └── skips configurable intervals within songs
│
└── SpeechPause
    └── pauses media when human speech is detected


SERVER
│
├── RemotePlayer
│   └── remotely controls laptop media
│
├── RemoteNotes
│   └── remotely reads and modifies project notes
│
├── RemoteStart
│   └── remotely starts applications and websites
│       according to the current mode
│
└── RemoteService
    └── remotely launches background services
```

`stack :: Python · Tkinter · FastAPI · WebSockets · Apple Shortcuts`

---

### `02 :: personal-home-server`

> Repurposed an old laptop into a personal server using a custom client-server architecture.

```text
CLIENT
   │
   ▼
LISTENER
   │
   ▼
SELECTOR
   │
   ▼
ROUTER
   │
   ▼
TOOLS
```

Current functionality includes file and directory transfer between machines.

`status :: ACTIVE DEVELOPMENT`

---

### `03 :: neural-network-from-scratch`

> A deep neural network implemented entirely from scratch using NumPy, without relying on machine-learning frameworks.

```text
dataset        :: MNIST
frameworks     :: none
implementation :: NumPy
accuracy       :: ~98%
```

Built the underlying network functionality myself to understand what happens beneath high-level ML abstractions.

---

### `04 :: particle-physics-engine`

> A particle simulation engine initially written in Python and later migrated to C for performance.

```text
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   ELECTROSTATIC FORCES                                     │
│   GRAVITY                                                   │
│   PARTICLE COLLISIONS                                      │
│   BOUNCING                                                  │
│   PARTICLE INTERACTIONS                                    │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

`Python → C`

---

### `05 :: general-purpose-llm-agent`

> A memory and context-aware chatbot with tool functionality built using only an LLM API.

```text
             ┌───────────────┐
             │    CONTEXT    │
             │               │
             │    memory     │
             │    history    │
             └───────┬───────┘
                     │
                     ▼
              ┌─────────────┐
              │     LLM     │
              └──────┬──────┘
                     │
                     ▼
             ┌───────────────┐
             │ TOOL ROUTER   │
             │               │
             │ MCP tools     │
             │ custom tools  │
             └───────────────┘
```

Designed to function as an agent capable of taking actions rather than purely generating conversational responses.

---

### `06 :: cpu-emulator`

> Currently building a CPU emulator to explore computer architecture at a lower level.

```text
             ┌──────────────────────┐
             │         CPU          │
             ├──────────────────────┤
             │                      │
             │     REGISTERS        │
             │         │            │
             │         ▼            │
             │   INSTRUCTION        │
             │      FETCH           │
             │         │            │
             │         ▼            │
             │      DECODE          │
             │         │            │
             │         ▼            │
             │      EXECUTE         │
             │         │            │
             │         ▼            │
             │      MEMORY          │
             │                      │
             └──────────────────────┘
```

`status :: BUILDING`

---

### `07 :: remote-screen-sharing`

> Secure screen sharing between my laptop and phone using personal server infrastructure and WebSockets.

```text
┌──────────────┐                         ┌──────────────┐
│    LAPTOP    │                         │     PHONE    │
│              │                         │              │
│   SCREEN     │────── WebSocket ───────▶│    DISPLAY   │
│   CAPTURE    │                         │              │
└──────────────┘                         └──────────────┘
```

`protocol :: WebSockets`

---

### `08 :: private-mesh-network`

> Currently exploring how to build a Tailscale-like private mesh network and VPN tunneling system from the ground up.

```text
                  ┌─────────┐
                  │ NODE A  │
                  └────┬────┘
                       │
              ┌────────┴────────┐
              │                 │
              ▼                 ▼
        ┌─────────┐       ┌─────────┐
        │ NODE B  │───────│ NODE C  │
        └─────────┘       └─────────┘
              │                 │
              └────────┬────────┘
                       ▼
                PRIVATE MESH
```

`status :: EXPERIMENTING`

---

## `./currently`

```text
$ cat status

learning    :: CPU architecture & emulation
building    :: private mesh networking
exploring   :: quantum computing
```

---

## `./philosophy`

<div align="center">

```text
╭──────────────────────────────────────────────────────────────╮
│                                                              │
│  "If I can understand the abstraction,                       │
│   I should be able to build it myself."                      │
│                                                              │
╰──────────────────────────────────────────────────────────────╯
```

</div>

---

## `./system`

```text
$ ./interests --recursive

systems
├── architecture
├── networks
├── computation
└── quantum

$ echo $STATUS

curious.
building.
going deeper.

$ _
```

<div align="center">

`_________ systems · networks · architecture · quantum · curiosity _________`

</div>
