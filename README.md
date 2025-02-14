
Repository containing data accompanying the paper
"*Periodic Boundary Conditions for Bosonic Path Integral Molecular Dynamics*"
by J. Higer, Y. M. Y. Feldman and B. Hirshberg, https://arxiv.org/abs/2501.17618.

The code is available in https://github.com/higj/pimd-b/tree/pbc (commit `e25c5d8`).

`inputs/` Contains PIMD-B inputs for the simulations of bosonic particles presented in the paper.

- **Fig 4**: Energy per particle as a function of temperature for the free Bose gas.
    -    `pbc/free_bosons_P{num_beads}_N64_D0.035_m4.0_T{temperature}_dt{timestep}_S10000000_pbc1_wind1_{seed}.ini`
    (e.g. `pbc/free_bosons_P12_N64_D0.035_m4.0_T2.0_dt2.0_S10000000_pbc1_wind1_18886.ini`)
    -    `no_pbc/free_bosons_P{num_beads}_N64_D0.035_m4.0_T{temperature}_dt{timestep}_S10000000_{seed}.ini`
    (e.g. `no_pbc/free_bosons_P4_N64_D0.035_m4.0_T2.0_dt2.0_S10000000_18886.ini`)
- **Fig 5**: Energy per particle as a function of temperature for the sinusoidal trap.
    -    `pbc/cosine_bosons_P{num_beads}_N32_A0.3_D0.035_m4.0_T{temperature}_dt{timestep}_S10000000_pbc1_wind1_{seed}.ini`
    (e.g. `pbc/cosine_bosons_P14_N32_A0.3_D0.035_m4.0_T3.0_dt0.3_S10000000_pbc1_wind1_18886.ini`)
    -    `no_pbc/cosine_bosons_P{num_beads}_N32_A0.3_D0.035_m4.0_T{temperature}_dt{timestep}_S10000000_{seed}.ini`
    (e.g. `no_pbc/cosine_bosons_P14_N32_A0.3_D0.035_m4.0_T3.0_dt0.3_S10000000_18886.ini`)
- **Fig 6**: Scaling of bosonic PIMD with PBC with the number of particles.
    -    `pbc/free_bosons_P32_N{num_atoms}_D0.035_m4.0_T3.0_dt0.5_S1000_wind1_18886.ini`
    (e.g. `pbc/free_bosons_P32_N512_D0.035_m4.0_T3.0_dt0.5_S1000_wind1_18886.ini`)
   -    `mic/free_bosons_P32_N{num_atoms}_D0.035_m4.0_T3.0_dt0.5_S1000_pbc1_18886.ini`
    (e.g. `mic/free_bosons_P32_N512_D0.035_m4.0_T3.0_dt0.5_S1000_pbc1_18886.ini`)
   -    `no_pbc/free_bosons_P32_N{num_atoms}_D0.035_m4.0_T3.0_dt0.5_S1000_18886.ini`
    (e.g. `no_pbc/free_bosons_P32_N512_D0.035_m4.0_T3.0_dt0.5_S1000_18886.ini`)
- **Fig 7**: Scaling of bosonic PIMD with PBC with the winding cutoff.
    -    `free_bosons_P4_N2_D0.035_m4.0_T3.0_dt0.5_S1000_pbc1_wind{max_wind}_18886.ini`
    (e.g. `free_bosons_P4_N2_D0.035_m4.0_T3.0_dt0.5_S1000_pbc1_wind64_18886.ini`)
- **Fig 8**: Energy (per particle) convergence as a function of P for the free Bose gas.
    -    `pbc/free_bosons_P{num_beads}_N64_D0.035_m4.0_T0.5_dt4.0_S10000000_pbc1_wind1_{seed}.ini`
    (e.g. `pbc/free_bosons_P10_N64_D0.035_m4.0_T0.5_dt4.0_S10000000_pbc1_wind1_18886.ini`)
   -    `mic/free_bosons_P{num_beads}_N64_D0.035_m4.0_T0.5_dt4.0_S10000000_pbc1_wind0_{seed}.ini`
    (e.g. `mic/free_bosons_P10_N64_D0.035_m4.0_T0.5_dt4.0_S10000000_pbc1_wind0_18886.ini`)
   -    `no_pbc/free_bosons_P{num_beads}_N64_D0.035_m4.0_T0.5_dt4.0_S10000000_pbc1_wind0_{seed}.ini`
    (e.g. `no_pbc/free_bosons_P10_N64_D0.035_m4.0_T0.5_dt4.0_S10000000_pbc1_wind0_18886.ini`)
- **Fig 9** Energy (per particle) convergence as a function of P for the sinusoidal trap.
    -    `pbc/cosine_bosons_P{num_beads}_N32_A0.3_D0.035_m4.0_T1.0_dt2.0_S10000000_pbc1_wind1_{seed}.ini`
    (e.g. `pbc/cosine_bosons_P4_N32_A0.3_D0.035_m4.0_T1.0_dt2.0_S10000000_pbc1_wind1_18886.ini`)
   -    `mic/cosine_bosons_P{num_beads}_N32_A0.3_D0.035_m4.0_T1.0_dt2.0_S10000000_pbc1_{seed}.ini`
    (e.g. `mic/cosine_bosons_P8_N32_A0.3_D0.035_m4.0_T1.0_dt2.0_S10000000_pbc1_18886.ini`)
   -    `no_pbc/cosine_bosons_P{num_beads}_N32_A0.3_D0.035_m4.0_T1.0_dt2.0_S10000000_{seed}.ini`
    (e.g. `no_pbc/cosine_bosons_P8_N32_A0.3_D0.035_m4.0_T1.0_dt2.0_S10000000_18886.ini`)
- **Fig 10**: Discarded winding probability for the free Bose gas.
    -    `free_bosons_P{num_beads}_N64_D0.035_m4.0_T0.5_dt4.0_S10000000_pbc1_18886.ini`
    (e.g. `free_bosons_P4_N64_D0.035_m4.0_T0.5_dt4.0_S10000000_pbc1_18886.ini`)
- **Fig 11**: Discarded winding probability for the sinusoidal trap.
    -    `cosine_bosons_P{num_beads}_N32_A0.3_D0.035_m4.0_T1.0_dt2.0_S10000000_pbc1_18886.ini`
    (e.g. `cosine_bosons_P4_N32_A0.3_D0.035_m4.0_T1.0_dt2.0_S10000000_pbc1_18886.ini`)
        