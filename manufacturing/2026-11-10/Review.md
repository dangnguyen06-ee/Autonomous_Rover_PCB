# Parker rover Rev 1.0 — manufacturing export

November 10, 2026. Exported from the user-saved design after the user corrected Q2/Q3 pin assignments and moved the Q3 reference text. No design corrections were applied by the assistant during this release.

## Verification

- PCB DRC: zero errors, zero unconnected items, zero schematic-parity issues.
- 52 warnings remain for user-modified footprints differing from their library copies.
- Schematic ERC: zero errors; 44 existing off-grid drawing warnings. Schematic hashes unchanged since the ERC and semiconductor-pin review.
- Q1 AO3401A and Q2/Q3 AO3400A: gate 1, source 2, drain 3, checked through the schematic netlist and PCB pads.
- U1 TCA9548A, U2 SN74LVC8T245, U3 USBLC6-2SC6, U4 TPS2116DRL, and U5 AMS1117-3.3 pin assignments reviewed.
- Both copper layers, mask layers, silkscreen layers, front paste and board outline exported. Separate metric, absolute-origin Excellon PTH and NPTH drill files included.
- ZIP contains exactly eleven manufacturing files, checked against loose exports; no Finder metadata or design source files.
- Design files in the actual project remain unchanged.

These checks do not measure current consumption, regulator thermal performance, antenna performance, or prove the fit/authenticity of generic purchased parts. User reported checking USB-C fit against a 1:1 print. Hardware testing is still required after assembly.

The previous November 9 export and old review copies must not be used to order this revision. Use Parker_Rover_Rev1.0_2026-11-10.zip.
