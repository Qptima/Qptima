# Qptima
A verifiable bounty board for hard optimization problems on QMS. Post a problem, lock a reward, and the chain verifies and pays the best solver.



# Qptima

A verifiable bounty board for hard optimization problems, built on
[QMS](https://qms.finance), the post-quantum Layer 1 with Proof-of-Useful-Work.

## The idea

Some problems are hard to solve but easy to check. Qptima turns that into a
marketplace:

1. A client posts a problem and locks a reward.
2. Solvers compete to submit the best solution.
3. The chain verifies each submission and pays the winner.

No trust required. The contract does the judging.

## Why QMS

QMS's Proof-of-Useful-Work vision is a network where computation solves
real problems for paying clients. Qptima is a working preview of that
client-and-solver loop, running on QMS's EVM-compatible testnet.

## Status

Early stage. Currently in design, with a testnet prototype planned for the
Builder Program.

## Roadmap

- [ ] Escrow and verification contract on QMS testnet
- [ ] Reference solver bot
- [ ] Web app for posting problems and tracking solutions
- [ ] Additional problem types

## Contact

Built by @braicbraic. Building in public.
