# Hi, I'm David Wang 👋

I build small, complete systems across the hardware/software boundary: FPGA datapaths, real-time telemetry tools, developer utilities, and browser games that ship without ceremony.

## 🔭 Current Focus

- **Digital hardware / AI acceleration** — building a Verilog neural-network inference accelerator from a single MAC unit toward an MNIST datapath on an Intel MAX 10 FPGA.
- **Real-time systems** — modeling industrial telemetry, fault detection, MQTT pipelines, persistence, and live browser dashboards.
- **Useful tools with evidence** — I like software that explains what it found, why it matters, and what to do next.

## 🧩 Featured Builds

**[VoltStream](https://github.com/DavidWang1231/voltstream)** — A real-time monitoring and fault-injection lab for 600 V three-phase induction motors. Simulated edge devices publish QoS 1 MQTT telemetry, a backend validates and persists fleet state in SQLite, and a live SSE dashboard shows faults, latency, throughput, and operator acknowledgements. [Public demo](https://voltstream-davidwang.wangjiacheng1231.chatgpt.site)

**[fpga-nn-accelerator](https://github.com/DavidWang1231/fpga-nn-accelerator)** — An active, from-scratch Verilog neural-network inference accelerator. The project builds from a MAC unit to a full quantized MNIST datapath, with Python golden-vector co-simulation and a TinyTapeout/SKY130 path for the core MAC engine.

**[repo-doctor](https://github.com/DavidWang1231/repo-doctor)** — Evidence-based repository health checks for real-world codebases. It scans local paths or GitHub URLs, detects project profiles before scoring, and produces prioritized HTML/Markdown/JSON reports with every finding backed by structured evidence. [Live demo](https://davidwang1231.github.io/repo-doctor/)

## 🕹️ Experiments & Games

**[signal-defender](https://github.com/DavidWang1231/signal-defender)** — SIGNAL, a PCB-aesthetic bullet-hell shooter in one HTML file: zero dependencies, no build step, 6 game modes, synthesized Web Audio, persistent progress, and English/中文 support. [Play it here](https://davidwang1231.github.io/signal-defender/)

**[alphapulse-radar](https://github.com/DavidWang1231/alphapulse-radar)** — A single-file Python pre-market stock-news radar that rotates through free news APIs, handles quota/failure modes, deduplicates headlines, keyword-matches market-moving events, and pushes alerts to Telegram.

## 🛠️ Toolbox

`Verilog` · `FPGA / Quartus / ModelSim` · `Python` · `JavaScript / Node.js` · `C++` · `MQTT` · `SQLite` · `Server-Sent Events` · `GitHub Actions`

## 📫 Reach Me

- Email: [wangjiacheng1231@gmail.com](mailto:wangjiacheng1231@gmail.com)
