# 电子器件

- [BJT](#bjt)
- [MOSFET](#mosfet)
- [压敏电阻/Varistor](#压敏变阻-varistor)
- [功分器/Power Divider](#公分器-power-divider)

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

## 压敏变阻 Varistor

一种对电压敏感的非线性半导体电阻器件

- 阻值会随着电压的变化而变化
- 低电压下提供M-ohm级的电阻
- 电流可以双向流动

## 公分器 Power-Divider

一种被动的器件，用来将输入信号分成二个或者多个输出信号

- 功率分配
- 功率合成
- 端口隔离和保护
