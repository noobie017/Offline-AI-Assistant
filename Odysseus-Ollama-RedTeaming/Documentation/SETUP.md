## Complete Setup Guide

### Prerequisites

1. Install **[Docker Desktop](https://www.docker.com/products/docker-desktop/)**
2. Install **[Ollama](https://ollama.com/)**
3. Make sure Ollama is running (`ollama serve` in terminal)

---

### Step-by-Step Installation

#### 1. Clone Odysseus

```bash
git clone https://github.com/pewdiepie-archdaemon/odysseus.git
cd odysseus
### 2. Copy Environment Filebash

cp .env.example .env

### 3. Start Odysseusbash

docker compose up -d --build

### 4. Get Admin Passwordbash

docker compose logs odysseus | grep -i "initial admin"







