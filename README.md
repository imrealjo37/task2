# حساب عزم الدوران لكل محرك في ذراع الروبوت

 حساب عزم الدوران المطلوب لكل محرك في ذراع الروبوت بناءً على المعادلات الفيزيائية لعزم الدوران.

## المعادلات المستخدمة
```math
\tau = F \times d
```
حيث:
- `τ` هو عزم الدوران (N.m)
- `F` هو القوة المؤثرة (N) نتيجة وزن الحمل
- `d` هو ذراع العزم (m)

## حساب الوزن المؤثر
```math
F = m \times g
```
حيث:
- `m = 1 kg` (الكتلة)
- `g = 9.81 m/s^2` (تسارع الجاذبية)
```math
F = 1 \times 9.81 = 9.81 N
```

## حساب عزم الدوران لكل محرك

### المحرك الأول (القاعدة - يشمل كامل الذراع)
```math
d1 = 0.15 + 0.10 + 0.04 = 0.29 m
\tau_1 = 9.81 \times 0.29 = 2.84 N.m
```

### المحرك الثاني (المفصل الأوسط - يشمل الجزء الأمامي فقط)
```math
d2 = 0.10 + 0.04 = 0.14 m
\tau_2 = 9.81 \times 0.14 = 1.37 N.m
```

### المحرك الثالث (نهاية الذراع - يشمل فقط الملقط)
```math
d3 = 0.04 m
\tau_3 = 9.81 \times 0.04 = 0.39 N.m
```

## اختيار محركات السيرفو المناسبة

| المفصل | المحرك المقترح | العزم (N.m) | رابط الشراء |
|---------|----------------|-------------|--------------|
| القاعدة | Dynamixel XM540-W270-R | 4.1 | [رابط الشراء](https://www.robotshop.com/products/dynamixel-xm540-w270-r) |
| المفصل الأوسط | Dynamixel MX-64AT | 6 | [رابط الشراء](https://www.robotshop.com/products/dynamixel-mx-64at-robot-actuator) |
| نهاية الذراع | Dynamixel AX-12A | 1.5 | [رابط الشراء](https://www.robotshop.com/products/dynamixel-ax-12a-robot-actuator) |



