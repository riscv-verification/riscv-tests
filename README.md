# High Quality RISC-V Test Suites
=================================

When verifying a CPU design - you can never have enough tests...

There are many places to get tests to execute on your RISC-V core to assist in architectural validation and verification. Here we will provide links to those we are aware of that are thorough and well written with good coverage.

We will add more links soon.


**Imperas free simulator** and initial test suite: The riscvOVPsim simulator and initial tests are available [imperas-riscv-tests](https://github.com/riscv-ovpsim/imperas-riscv-tests)

**OVPworld** provides the source of many good test suites: [OVPworld.org](https://www.ovpworld.org/library/wikka.php?wakka=riscvOVPsimPlus).

RV32I, RV32M, RV32C, RV64I, RV64M, RV64C, Zmmul - base

RV32F, RV64F, RV64D - floating point

RV32Kscalar, RV64Kscalar - crypto

RV32B, RV64B - bitmanip

RV32V - vector

RV32P, RV64P - DSP/SIMD

You can see the details of the tests here: [test_details](https://github.com/riscv-ovpsim/imperas-riscv-tests/tree/master/riscv-test-suite).
