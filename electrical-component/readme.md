# Electrical Component

## BJT

- isolate hardware modules to reduce power
  - e.g. isolate communication module. no data transfer while device in sleep and report data when device wakes up
- measure voltage
  - e.g. battery voltage

### BJT Model

- MMBT3904
  - NPN, V_ce = 40V, I_c = 200mA, h_fe = 300
- S8050
  - NPN, V_ce = 20V, I_c = 700mA, h_fe = 400

## MOSFET

- isolate hardware modules to reduce power

### MOSFET Model

- AO3401
  - P channel, V_ds = -30V, I_d(at V_gs = -10v) = -4.0A, V_gs = +- 12V
