<h1 align="center">Hi, I'm Prajwal Khadepatil 👋</h1>

<p align="center">
  <b>Hardware Verification Engineer</b> &nbsp;|&nbsp; PCIe · UVM · SystemVerilog · FPGA
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ItsKhade">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/ItsKhade">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## About Me

I am an Electrical and Computer Engineering graduate with 1–2 years of hands-on experience in **digital design verification**, **high-speed interface protocols**, and **FPGA development**. My work focuses on building robust, self-checking verification environments for complex SoC and PCIe-based systems.

- 🎓 **M.Eng. Electrical and Computer Engineering** — Western University, London, Ontario, Canada
- 🎓 **B.E. Electrical Engineering** — G.H. Raisoni College of Engineering, Nagpur, India
- 🔍 Currently focused on **PCIe verification**, **UVM testbench development**, and **high-speed interface validation**
- 📍 Based in Toronto, Canada

---

## Technical Skills

| Domain | Tools & Technologies |
|---|---|
| **Verification Languages** | SystemVerilog, UVM 1.2, Verilog |
| **Protocols** | PCIe 3.0, AXI4-Lite, PIPE Interface |
| **Scripting & Automation** | Python, Tcl, Perl |
| **Programming** | C, C++ |
| **Simulators** | Aldec Riviera-PRO, ModelSim, EDA Playground |
| **Hardware** | FPGA (Xilinx / Intel), Digital Logic Design |
| **Concepts** | TLP Parsing, BFM Verification, Functional Coverage, Assertions |

---

## Featured Projects

### 🔷 PCIe TLP Parser & Protocol Checker
> Python CLI tool + interactive web UI that decodes PCIe 3.0 Transaction Layer Packets and validates them against the PCIe Base Specification.

- Implements **9 protocol violation checks** — zero-length, poisoned TLP, payload mismatch, completion error status, reserved field misuse, and more
- Supports **MemRd, MemWr, CplD, Cpl, Msg** TLP types (32-bit & 64-bit addressing)
- **25 automated test vectors** with 25/25 passing
- No external dependencies — pure Python 3.7+

[![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/ItsKhade/pcie-tlp-parser)
[![Live Demo](https://img.shields.io/badge/Live-Demo-00C853?style=flat-square)](https://ItsKhade.github.io/pcie-tlp-parser)

---

### 🔷 UVM AXI-Lite Verification Testbench
> Complete UVM-based verification environment for a 4-register AXI4-Lite slave interface.

- Full UVM architecture: **sequencer → driver → monitor → scoreboard → coverage collector**
- **5 directed test sequences** — write/read-back, all-registers walk, back-to-back writes, error injection (SLVERR on read-only register), byte strobe masking
- Self-checking scoreboard with **4-register reference model**
- **5 functional covergroups** including cross-coverage (address × transaction type)

[![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/ItsKhade/uvm-axi-lite-tb)

---

### 🔷 PCIe PIPE Interface Simulation
> SystemVerilog simulation of the PIPE (PHY Interface for PCI Express) MAC-to-PHY boundary — the exact interface used in PCIe BFM verification environments.

- Models full **link training state machine**: Reset → Detect → Polling → L0
- Covers **power state transitions** P0 / P1 / P2 with correct PhyStatus handshaking
- **7 directed tests, 16 self-checking assertions** — PhyStatus pulses, RxStatus codes, ordered sets, data loopback, electrical idle detection
- References **PIPE Specification Rev 4.4** signal definitions and timing

[![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github)](https://github.com/ItsKhade/pipe-interface-sim)
[![EDA Playground](https://img.shields.io/badge/EDA-Playground-blue?style=flat-square)](https://edaplayground.com)

---

## Education

| Degree | Institution | Year |
|---|---|---|
| M.Eng. Electrical & Computer Engineering | Western University, London, Ontario, Canada | 2024 |
| B.E. Electrical Engineering | G.H. Raisoni College of Engineering, Nagpur, India | 2022 |

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ItsKhade&show_icons=true&theme=default&hide_border=true&count_private=true" height="160"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ItsKhade&layout=compact&hide_border=true&theme=default" height="160"/>
</p>

---

<p align="center">
  <i>Open to hardware verification and digital design roles — feel free to connect on LinkedIn.</i>
</p>
