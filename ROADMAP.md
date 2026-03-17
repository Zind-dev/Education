# Embedded Developer Relocation Roadmap

This repository is my learning space for becoming a stronger embedded developer and preparing for international relocation.

## Goal

Build a profile strong enough for embedded software jobs abroad by improving:
- Embedded C fundamentals
- Debugging and hardware interaction skills
- RTOS knowledge
- Linux basics and Embedded Linux
- English for engineering communication
- Interview readiness
- Public learning notes and project documentation

---

## Target Profile

A practical target for relocation:
- 2-4 years of commercial embedded experience
- Strong C and low-level debugging skills
- Good understanding of MCU peripherals and communication protocols
- RTOS experience
- Basic to intermediate Embedded Linux knowledge
- English level around B1+ to B2
- Clear GitHub portfolio with notes, examples, and learning progress

---

## Main Learning Directions

### 1. Embedded C Core
Topics:
- Pointers, memory layout, stack vs heap
- `volatile`, `const`, `static`, storage duration
- Structures, unions, bit fields
- Interrupt-safe code
- Linker and startup basics
- Undefined behavior and common mistakes in C

Practice:
- Write small examples for memory manipulation
- Implement ring buffer, state machine, and simple driver abstractions
- Document common bugs and fixes

### 2. MCU and Hardware Work
Topics:
- GPIO, timers, interrupts, watchdogs
- ADC, PWM, DMA
- UART, SPI, I2C, CAN
- Reading schematics and datasheets
- Debugging with logic analyzer, oscilloscope, JTAG/SWD

Practice:
- Create peripheral bring-up notes
- Write examples for UART/SPI/I2C communication
- Keep troubleshooting logs from experiments

### 3. RTOS
Topics:
- Tasks/threads
- Scheduling
- Queues, semaphores, mutexes, event groups
- Timing problems and race conditions
- Memory management in RTOS-based systems

Practice:
- Build a small multitask firmware example
- Compare polling vs interrupt vs RTOS task models
- Write notes about synchronization mistakes

### 4. Linux Basics
Topics:
- Shell navigation
- Files, directories, and permissions
- Users and groups
- Processes and jobs
- Pipes and redirection
- Environment variables
- Text tools: `grep`, `sed`, `awk`
- SSH and SCP
- Package managers
- Basic networking commands

Practice:
- Complete daily shell exercises
- Write notes about common commands and their options
- Set up and use a Linux environment regularly

### 5. Embedded Linux
Topics:
- Cross-compilation and toolchains
- Bootloaders overview
- Kernel basics
- Device tree
- Serial communication in Linux
- Networking basics
- Buildroot and Yocto introduction
- Systemd basics
- Board bring-up workflow

Practice:
- Build and run a small userspace C application on Linux
- Cross-compile for a target board
- Write notes for serial, GPIO, and networking workflows

### 6. Tools and Engineering Workflow
Topics:
- Git and GitHub
- Build systems
- Compiler warnings and sanitizers
- Unit testing basics
- Static analysis basics
- CI concepts
- Writing technical documentation

Practice:
- Keep repository structure clean
- Add README files for each topic
- Summarize what was learned after each study block

### 7. English for Engineering
Target:
- Reach practical B1+ or B2 level for work communication

Focus areas:
- Explaining technical decisions
- Describing bugs and debugging steps
- Reading documentation fluently
- Writing concise status updates
- Speaking in interviews

Practice:
- Write some notes in English
- Maintain a technical vocabulary list
- Summarize one technical topic per week in English
- Practice answering interview questions aloud

### 8. Career and Relocation Preparation
Topics:
- CV and LinkedIn preparation
- Relocation-friendly countries and companies
- Interview preparation
- Salary research
- Visa sponsorship awareness
- Behavioral questions in English

Practice:
- Create a list of target roles
- Save common interview questions
- Track gaps between current skills and job requirements

---

## Suggested Repository Structure

- `README.md` - overview of repository goals
- `ROADMAP.md` - this roadmap
- `embedded-c/` - C fundamentals and low-level programming notes
- `mcu/` - peripherals, hardware, and board bring-up notes
- `rtos/` - RTOS concepts and examples
- `linux-basics/` - foundational Linux command-line and system concepts
- `embedded-linux/` - cross-compilation, device tree, Buildroot, board bring-up
- `protocols/` - UART, SPI, I2C, CAN, USB, Ethernet notes
- `debugging/` - debugging cases, tools, and lessons learned
- `english/` - technical vocabulary and speaking practice notes
- `career/` - CV, interview, and relocation preparation notes

---

## 6-Month Plan

### Month 1 - Strengthen C Foundations
- Review pointers, memory model, storage classes, and bit operations
- Solve small C exercises every week
- Write notes about common embedded C mistakes
- Start technical English vocabulary list

### Month 2 - MCU Peripherals and Debugging
- Focus on UART, SPI, I2C, timers, interrupts
- Document peripheral initialization patterns
- Practice debugging with tools when possible
- Write one short English summary each week

### Month 3 - RTOS Basics
- Learn tasks, queues, semaphores, mutexes
- Build a small RTOS demo project
- Study race conditions and deadlocks
- Practice speaking about one project in English

### Month 4 - Linux Basics and Embedded Linux
- Learn shell commands, processes, permissions, and text tools
- Cross-compile a simple C project for a target board
- Study serial and networking basics on Linux
- Start Buildroot or Yocto overview notes

### Month 5 - Portfolio and Interview Preparation
- Clean and organize GitHub repository
- Add examples, notes, and mini-projects
- Prepare project explanations for interviews
- Practice English answers for common technical questions

### Month 6 - Job Market Preparation
- Review target countries and role requirements
- Update CV and LinkedIn
- Compare job descriptions with current skills
- Start applying to roles that match current level

---

## Weekly Routine Example

- 4 days: technical study and practice
- 1 day: English for engineers
- 1 day: documentation and GitHub updates
- 1 day: rest or review

Example weekly split:
- 3-5 hours Embedded C / MCU
- 2-3 hours RTOS or Linux
- 2 hours English
- 1-2 hours documentation and career preparation

---

## Priority Order

If time is limited, prioritize in this order:
1. Commercial embedded experience
2. Strong C and debugging
3. English improvement
4. RTOS and protocols
5. Embedded Linux
6. Portfolio and interview preparation

---

## Notes to Myself

- Do not wait for perfect conditions before starting relocation preparation.
- Gain experience locally if needed, but prepare for the international market in parallel.
- English and Embedded Linux are force multipliers.
- Consistency is more important than speed.
- Public notes can become proof of discipline and growth.

---

## Next Steps

Recommended immediate actions:
1. Add a `README.md` for the repository
2. Create topic folders from the structure above
3. Add the first study notes in `embedded-c/` and `english/`
4. Update the repository every week
5. Convert learning into small practical examples whenever possible