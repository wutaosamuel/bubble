# 电子器件

## BJT

- 物理隔离模组, 用以降低功耗
  - 比如，隔离通讯模组。当设别休眠时关闭三极管，当设别唤醒时需要上报数据时，再打开三极管的开关
- 测量电压
  - 比如，电池电压

### BJT Model

- MMBT3904
  - NPN, V_ce = 40V, I_c = 200mA, h_fe = 300
- S8050
  - NPN, V_ce = 20V, I_c = 700mA, h_fe = 400

## MOSFET

- 物理隔离模组, 用以降低功耗

### MOSFET Model

- AO3401
  - P channel, V_ds = -30V, I_d(at V_gs = -10v) = -4.0A, V_gs = +- 12V
