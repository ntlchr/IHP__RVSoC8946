# RVSoC8946 — TAICHIP-1 SoC (FURIES)

TAICHIP-1 SoC is a RISC-V-based AI SoC platform built on the open-source CROC SoC from ETHZ. The platform features a CVE2 RISC-V core, DNN accelerator called FORTALESA, on-chip memory, DMA, JTAG, UART, SPI, and GPIO.

FORTALESA is a systolic array architecture with three execution modes for run-time reconfigurable redundancy and a flexible reliability–performance trade-off.

The platform features multiple fault tolerance features, including dual-lockstep for RISC-V core, fault tolerant OBI bus infrastructure, ECC on memories, reconfigurable redundancy for FORTALESA accelerator, and MBIST.

## Release

The tapeout GDS is available at `release/v.1.0.0/gds/RVSoC8946.gds.gz`.

Die: **5000 × 4000 µm**

## Tooling & Infrastructure

The project utilizes the following open-source toolchain for physical design and verification:

| Tool | Version |
|---|---|
| **Yosys** | 0.58 |
| **OpenRoad** | v2.0 |
| **KLayout** | 0.30.9 |
| **PDK** | IHP SG13CMOS5L |

## License

[Apache 2.0](LICENSE)