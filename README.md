<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e293b,100:2563eb&height=170&section=header&text=Suhaib%20Ben%20Zreiba&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=Computer%20Systems%20Engineering%20%7C%20FPGA%20%26%20RTL%20Design%20%7C%20Verification&descAlignY=58&descSize=15&animation=fadeIn" width="100%"/>

<a href="https://linkedin.com/in/suhaib-ben-zreiba"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="mailto:suhaibbenzreiba@cmail.carleton.ca"><img src="https://img.shields.io/badge/Email-1f2937?style=flat-square&logo=gmail&logoColor=white" /></a>
<img src="https://img.shields.io/badge/Ottawa%2C_Canada-1f2937?style=flat-square&logo=googlemaps&logoColor=white" />

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=15&pause=1200&color=2563EB&center=true&vCenter=true&width=560&lines=Designing+and+verifying+digital+hardware;Building+production+systems+that+actually+ship;Currently%3A+RV32I+FPGA+SoC+with+fault+injection" alt="Typing SVG" />

</div>

<br>

## About

Third-year Computer Systems Engineering student at Carleton University (**10.57/12.0 GPA, Dean's List**). I work at the boundary of hardware and software: designing and verifying digital logic in Verilog/SystemVerilog on one side, and independently building a production system that a real organization runs on every day on the other.

Seeking **Winter 2027 co-op** roles in FPGA engineering, ASIC design/verification, or embedded systems.

<br>

## Technology Stack

**Hardware & HDL**

![Verilog](https://img.shields.io/badge/Verilog-334155?style=flat-square)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-334155?style=flat-square)
![Vivado](https://img.shields.io/badge/Vivado-334155?style=flat-square)
![Logisim](https://img.shields.io/badge/Logisim-334155?style=flat-square)
![EDA Playground](https://img.shields.io/badge/EDA_Playground-334155?style=flat-square)

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-437291?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)

**Tools & Platforms**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![MATLAB](https://img.shields.io/badge/MATLAB-334155?style=flat-square)

<br>

## Featured Projects

**🏭 AlBayan School Management Platform** — production registration, tuition-payment, and attendance system running live for a real school, not a class assignment.
- Transactional QR/payment-code check-in with idempotent writes: safe under concurrent scans, double-clicks, and retries
- Automated e-transfer reconciliation pipeline that parses deposit-notification emails via the Gmail API and matches them against payment records, with duplicate-payment detection
- Role-based session auth (admin desk vs. check-in desk), Google Sheets backup sync, scheduled cron jobs
- Vitest coverage on check-in and payment edge cases
`Next.js` `TypeScript` `Firestore` — **[Live](https://albayanschool.online)** · source private (handles student financial data)

**⚙️ FPGA Digital Systems Design & Verification** — synthesizable RTL (decoders, registers, an FSM-driven arithmetic controller), verified with self-checking testbenches, synthesized and bench-tested on real FPGA hardware with timing/pin constraints in Vivado.
`Verilog` `SystemVerilog` `Vivado` · *repo pending — coursework, being cleaned up for publish*

**🧠 32-Bit ARM-Inspired Pipelined Processor** — a pipelined 32-bit ARM-style datapath (fetch/decode/execute), with hazard and data-flow issues traced and resolved through cycle-by-cycle simulation.
`Logisim` `Computer Architecture` · *repo pending*

**🔧 Digital Arithmetic Calculator with FSM Controller** — datapath-based calculator driven by a finite-state-machine controller, with SystemVerilog testbenches, assertion-style checks, and waveform-based debugging across edge-case inputs.
`SystemVerilog` · *repo pending*

**🔍 [hex-data-parser](https://github.com/Suhaib-Ben-Zreiba/hex-data-parser)** — parses raw hexadecimal byte streams and maps byte ranges to named register fields via a JSON register map; decodes hex/uint8/uint16 fields into a readable register table.
`Python`

**🗂️ [student-record-analyzer](https://github.com/Suhaib-Ben-Zreiba/student-record-analyzer)** — C program parsing and validating structured student records from file input, with search, sort, and summary statistics over dynamically allocated data.
`C`

**☕ [student-records-system](https://github.com/Suhaib-Ben-Zreiba/student-records-system)** — layered Java CLI application (model / service / storage) with full CRUD and CSV-backed persistence.
`Java`

**🧹 [course-file-organizer](https://github.com/Suhaib-Ben-Zreiba/course-file-organizer)** — normalizes inconsistent filenames and sorts files into type-based directories, with safe duplicate handling.
`Python`

<br>

## Currently Building

**Fault-Tolerant RISC-V FPGA SoC** — RV32I-subset core with hardware fault injection and detection

- [x] Architecture planning (PC, decoder, register file, ALU, load/store path)
- [ ] Core datapath + control logic
- [ ] Self-checking SystemVerilog testbenches
- [ ] FPGA synthesis and on-board bring-up
- [ ] Hardware fault injection (ALU / register / PC corruption) + detection
- [ ] Dual-core lockstep comparison

<br>

## GitHub Activity

<img src="https://github-readme-stats.vercel.app/api?username=Suhaib-Ben-Zreiba&show_icons=true&theme=tokyonight&hide_border=true&count_private=false" height="165"/>
<img src="https://streak-stats.demolab.com?user=Suhaib-Ben-Zreiba&theme=tokyonight&hide_border=true" height="165"/>

<br>

## Let's Connect

[LinkedIn](https://linkedin.com/in/suhaib-ben-zreiba) · [Email](mailto:suhaibbenzreiba@cmail.carleton.ca) · Ottawa, ON

