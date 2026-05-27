# David Dedić
Systems, Compiler, and High-Performance Computing Engineering

Focusing on low-level software architectures, spanning bare-metal embedded systems, custom compiler design, and hardware-accelerated parallel computing. Software is engineered with a focus on physical hardware limits, execution pipelines, and memory hierarchies.

Technical Stack:
* Proficient: C, CUDA, ARM Assembly (AArch64 / Thumb-2), AVR Assembly
* Familiar: C++, Python

---

## Core Engineering Projects

### Custom Language Toolchains and Compilers
* **Multi-Pass Subset-C to ARM64 Compiler:** Architected a multi-pass compiler backend that lowers a functional subset of the C programming language into native AArch64 machine code. Features an optimization pipeline utilizing Chaitin-style graph coloring for global register allocation.
* **Self-Hostable Thumb-2 Compiler:** Developed a single-pass compiler for a custom scripting language dialect. Implemented greedy register allocation integrated with loop-depth-aware spilling heuristics, lazy flag storage tracking, and register state snapshotting across conditional branch states.

### Operating Systems and Bare-Metal Firmware
* **Custom Cortex-M4 Microkernel / RTOS:** Developed a preemptive, bare-metal real-time operating system from scratch without a Hardware Abstraction Layer (HAL). Implemented a deterministic round-robin co-op scheduler via PendSV interrupts, low-latency mailbox IPC, hardware timer tracking, and a zero-fragmentation localized memory allocator.
* **Bare-Metal Device Drivers:** Written native AVR Assembly and C drivers for LCD displays and bit-banged PS/2 keyboard matrices utilizing direct memory-mapped register manipulation and hardware interrupts.

### Computer Graphics and High-Performance Simulation (HPC)
* **Global Illumination Path Tracers:** Engineered two distinct ray-object intersection engines from the ground up:
  * **CUDA Accelerated Path Tracer:** A parallelized global illumination engine utilizing shared memory allocation and thread-coalescence techniques.
  * **Library-Free C Path Tracer:** A standalone, pure C ray tracer built with zero external framework dependencies, outputting raw image bytes directly via localized math routines.
* **Software Rasterization Pipelines:** Developed discrete rendering pipelines to explore resource-constrained vs. massively parallel execution:
  * **CUDA Parallel Rasterizer:** A high-throughput, hardware-accelerated rasterization pipeline written completely in custom CUDA kernels.
  * **Cortex-M4 Software Rasterizer:** A highly resource-constrained software engine utilizing optimized floating-point math and frame-buffer optimizations to render geometry under strict microprocessing RAM limits.
* **CUDA Eulerian Fluid Dynamics Simulator:** Developed a high-performance Computational Fluid Dynamics (CFD) simulation engine. Leveraged GPU parallelism to solve the Navier-Stokes equations natively across uniform grid structures.

---

## Connect With Me
* Email: david.dedic.2008@gmail.com

Fun Note: My profile picture is cool :)
