# Xenon Var-Rho Noise Discrimination

Dual-phase xenon time-projection chambers — the LZ and XENONnT class — read
scintillation light with photomultiplier arrays at single-photon sensitivity,
and their published background literature is a catalog of the exact enemy
this program hunts: dark-count coincidences, afterpulsing trains,
delayed-correlated scintillation, flashing PMTs, single-electron populations.

This record documents a trigger-level, falsifier-auditable noise-rejection
layer for that environment. It does not compete with these collaborations'
event-level physics selection — their S1 pulse-shape discrimination is
world-class and this work says so. It claims the adjacent ground instead:
a locked criterion set (Var > 1000, ρ > 0.8, hold-off re-derived per rate
regime), certified statistics on the accepted stream, and portability cheap
enough for PMT screening benches, small university-scale TPCs, and
next-generation sensor programs.

**The comparison debt:** falsifier X6 pre-commits a head-to-head against the
published cuts (multiplicity requirements, S1 PSD, afterpulsing/PMT flags) on
identical simulated noise. If the gate underperforms on their ground, the
paper says so and stands on the certification ground. A comparison that can
only come out one way is worth nothing.

**Status:** concept note v1.0 (this repository's seed document). Pre-
registration (locking X1–X6, including X6's margin) and the Phase-1
simulation follow. No data are reported anywhere in this record yet.

**Phases, stated plainly:** Phase 1 = simulation from the open literature
(LZ/XENONnT data are not public; nothing in Phase 1 waits on permission).
Phase 2 = real waveforms, conditional on access, reported only if it
materializes.

**Lineage:** QCID-Sigma v5.4 (10.5281/zenodo.23378709) → muon
pre-registration v1.1 (10.5281/zenodo.23405991) → swarm veto protocol
(10.5281/zenodo.23431140) → swarm validation (10.5281/zenodo.23433610) →
front-consistency veto (10.5281/zenodo.23482628) → IceCube DOM study
(10.5281/zenodo.23494707) → this record.

**License:** MIT / CC BY. Civilian application.
