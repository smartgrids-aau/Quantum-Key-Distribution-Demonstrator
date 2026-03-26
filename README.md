# Quantum Key Distribution Demonstrator
Quantum Cryptography  •  QKD  •  Science Communication  •  Game Design

Quantum Key Distribution (QKD) is a method for securely exchanging cryptographic keys using the physical properties of individual photons. A photon source produces entangled photon pairs sent to two parties (Alice and Bob) over an optical link. Each party independently measures photon polarization, yielding a correlated raw bit stream. The CASCADE protocol corrects errors through iterative parity checks, and privacy amplification then removes information potentially leaked during this step.  This project designs and implements a multi-player game demonstrator in which participants physically enact the steps of QKD — including photon polarization measurement, error correction, and one-time pad message exchange — using game controllers and physical props, making quantum principles tangible for a general audience.

## Objectives
*	Review literature on quantum cryptography, QKD protocols (BB84, E91), CASCADE error correction, and privacy amplification.
*	Design and implement a multi-player demonstrator in three stages: (1) photon exchange and polarization measurement with controller input, (2) CASCADE error correction as a cooperative mini-game, and (3) one-time pad encryption and decryption of a secret message.
*	Extend the demonstrator to a three-player variant including an attacker who can intercept photons and observe the resulting key degradation.
*	Evaluate participant learning outcomes and engagement through questionnaires; refine and document the demonstrator for reproducibility at outreach events.


## Reading List
*	Bennett, C.H., Brassard, G. "Quantum Cryptography: Public Key Distribution and Coin Tossing." Theoretical Computer Science, 2014.
*	Brassard, G., Salvail, L. "Secret-Key Reconciliation by Public Discussion (CASCADE)." Advances in Cryptology — EUROCRYPT, 1993.
