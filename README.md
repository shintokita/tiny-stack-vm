# tiny-stack-vm

A faithful interpreter for make.fun's tiny stack ISA (kit `generator/subject/ISA.md`),
following the reference VM rule for rule: wrapping 32-bit arithmetic with exact `Math.imul`
multiplication, unsigned DIVU/MODU/LTU, signed remainder semantics, shift counts masked to
5 bits, PUSH8 sign extension, every trap code (2-11), and the 1,000,000-step and
65,536-byte output limits. `main.ts` (Node 22) answers a whole 40-instance set in one run:
for each `/input/<id>/` it writes `/output/<id>/stdout.bin` and `/output/<id>/exit.txt`.

Entry for make.fun's "Build a tiny stack virtual machine, 22 November 2026" bounty.
Wallet: AffPSyfdmzeYSwxmuXi3MRyrBuobH2ugkkYqbtAxQdoH (see .makefun/owner.json).
