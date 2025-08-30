# MiniCPU
Custom mini CPU design

TBD

Repo contents:

* docs/          - system design docs, block diagrams, etc
* examples/      - example code using the Stack CPU
* hw/            - hardware design files
* ref/           - reference documents for integrated packages
* src/           - source code for the Stack CPU tools


## Requirements

* MiniCPU **shall** support TBD.


## High Level Design

### Machine Model

![model](https://github.com/dervish77/MiniCPU/blob/main/docs/MiniCPU-Machine-Model.png?raw=true)

### Register Model 

tbd

### Instruction Model

```
 OPERATION
```

### Architecture Diagram

![architecture](https://github.com/dervish77/MiniCPU/blob/main/docs/MiniCPU-Architecture.png?raw=true)

### Instructions

```
Instruction Fetch                                         fetch op_code -> <inst dec>
```

### Examples

#### Adds Numbers

```
; Adds numbers from 1 to 5, outputs sum
```


## Detailed Design

### Hardware

#### Logic Blocks

tbd

#### Implementations

tbd

### Software

#### Simulator

tbd

#### Tools

tbd


## Tools Used

* DrawIO - [https://www.drawio.com/](https://www.drawio.com/)
* Notepad++ - [https://notepad-plus-plus.org/](https://notepad-plus-plus.org/)
* GVim - [https://www.vim.org/download.php](https://www.vim.org/download.php)
* GitHub Desktop - [https://github.com/apps/desktop](https://github.com/apps/desktop)
* Cygwin - [https://www.cygwin.com/](https://www.cygwin.com/)
  * gcc - from Cygwin
  * g++ - from Cygwin
  * make - from Cygwin
  * git - from Cygwin
* Custom tools
  * bindump - used to examine binary files
  * binedit - used to edit contents of binary file
  * bingen - used to generate binary files


