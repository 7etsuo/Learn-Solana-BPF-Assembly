# Solana BPF Assembly (sBPF)

```
    ███        ▄████████     ███        ▄████████ ███    █▄   ▄██████▄  
▀█████████▄   ███    ███ ▀█████████▄   ███    ███ ███    ███ ███    ███ 
   ▀███▀▀██   ███    █▀     ▀███▀▀██   ███    █▀  ███    ███ ███    ███ 
    ███   ▀  ▄███▄▄▄         ███   ▀   ███        ███    ███ ███    ███ 
    ███     ▀▀███▀▀▀         ███     ▀███████████ ███    ███ ███    ███ 
    ███       ███    █▄      ███              ███ ███    ███ ███    ███ 
    ███       ███    ███     ███        ▄█    ███ ███    ███ ███    ███ 
   ▄████▀     ██████████    ▄████▀    ▄████████▀  ████████▀   ▀██████▀  
                                                                        
```

This repository serves as a Solana BPF Assembly (sBPF) learning resource. It aims to guide developers, from beginners to experts, in writing low-level Solana programs in Assembly. We consolidate project-specific technical documentation and highlight key examples from the broader Solana development community, featuring valuable work by developers like Dean 利迪恩 (@deanmlittle) and the Firedancer team to illustrate practical sBPF programming.

**Key Features:**
- Progressive learning paths from foundational concepts to advanced topics.
- Curated references to high-quality, optimized community examples.
- Consolidated instruction set details, opcode tables, and sBPF specifics.
- In-depth technical documentation on the sBPF execution model, memory map, and register usage.
- Clear, organized navigation to help you find information quickly.

**Connect with the Community:**
- **Tetsuo Coin:** [Buy on DexScreener](https://dexscreener.com/solana/2kb3i5ulkhucjuwq3poxhpuggqbwywttk5eg9e5wnlg6)
- 🐦 **X/Twitter:** [@tetsuoai](https://www.x.com/tetsuoai)
- 🌐 **Website:** https://tetsuoproject.com/

---

## 📚 Documentation Overview

This documentation is structured to guide you through sBPF Assembly programming.

### 🔍 [Foundations](./docs/foundations)
*Core concepts for getting started with sBPF programming.*
- [Introduction to sBPF](./docs/foundations/01_introduction.md): Understand Solana sBPF and its relation to eBPF.
- [Execution Model](./docs/foundations/02_execution_model.md): Learn about registers, memory, and VM specifics.
- [Toolchain Setup](./docs/foundations/03_toolchain.md): Set up your development environment.

### 📖 [Assembly Language Reference](./docs/reference)
*Detailed references for the sBPF assembly language.*
- [GAS Syntax Primer](./docs/reference/01_gas_syntax.md): Learn the GNU Assembler syntax used for sBPF.
- [Opcode Tables](./docs/reference/02_opcode_tables.md): Quick lookup for sBPF opcodes.
- [Instruction Set](./docs/reference/03_instruction_set.md): Comprehensive details on available instructions.

### ⚙️ [Solana Integration (Usage)](./docs/usage)
*(Partially Coming Soon)* How sBPF programs interact with the Solana runtime.
- Program Deployment (Coming Soon)
- Testing Strategies (Coming Soon)
- Development Workflow (Coming Soon)
- *Helper/Syscall Catalogue (Planned)*

### 🔮 [Advanced Topics](./docs/advanced)
*(Coming Soon)* Deeper dives into complex sBPF programming aspects.
- Account Interactions
- Cross-Program Invocation
- Program Derived Addresses
- Heap Usage

### 📑 [Appendices](./docs/appendices)
*Supplementary materials and detailed references.*
- [Opcode Reference](./docs/appendices/01_opcode_reference.md): Exhaustive sBPF opcode details.
- [Memory Map Reference](./docs/appendices/02_memory_map.md): Detailed view of the sBPF memory layout.
- [Linker Script Guide](./docs/appendices/03_linker_script.md): Understanding linker scripts for sBPF.
- [Build Flags](./docs/appendices/04_build_flags.md): Common build flags and their effects.
- [Register Reference](./docs/appendices/05_register_reference.md): In-depth guide to sBPF registers.

---

## 💻 Code Examples

Learn by doing with these practical examples:

### [No-Operation Program](./examples/sbpf-asm-noop)
A minimal Solana program in assembly by Dean 利迪恩 (@deanmlittle). Optimized to just 336 bytes, it's a great starting point.

### [Fibonacci Calculator](./examples/solana-fibonacci-asm)
Calculates Fibonacci numbers using assembly, by Dean 利迪恩 (@deanmlittle). Demonstrates computation, achieving F(93) in only 653 CUs.

### [Token Program](./examples/token.sbpf)
A complete token program implementation by Firedancer Contributors. Highly optimized, performing transfers in just 56 CUs.

---

## 🛠️ Getting Started

1.  **Set Up Your Environment:**
    Follow the [Toolchain Setup guide](./docs/foundations/03_toolchain.md).
2.  **Build an Example Program:**
    Refer to the instructions in an example directory, e.g., [`./examples/sbpf-asm-noop/README.md`](./examples/sbpf-asm-noop/README.md).
3.  **Deploy to Solana:**
    Deployment guides will be available in the [Solana Integration (Usage)](./docs/usage) section (coming soon).

---

## 📝 Contributing

Contributions are highly welcome! Please feel free to submit a Pull Request.
