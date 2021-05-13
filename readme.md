# ONCVPSP

(针对QE中以UPF格式的优化的模守恒赝势[Optimized Norm-Conserving Vanderbilt Pseudopotential])


@https://gitee.com/cndaqiang/ONCVPSP

或者

@https://github.com/pipidog/ONCVPSP

## 1.特点：现在有两个ONCVPSP数据库,分别是


1)由ABINT官方网站提供：


@http://www.abinit.org/downloads/pseudodojo/pseudodojo


2)由Sg15数据库提供：


@http://www.quantum-simulation.org/potentials/sg15_oncv/

## 2.其他：
它们均可与QE适配，其中默认：
```
xx.in => the input file for ONCVPSP generation
xx_ONCV_PBE_sr.upf => scalar relativistic (for non-spin-orbit calculations)
xx_ONCV_PBE_fr.upf => fully relativistic (for spin-orbit calculatons)
```
也就是说，在包含SOC的情况下，用全相对论格式；不包含SOC的情况下，用标量相对论格式。
