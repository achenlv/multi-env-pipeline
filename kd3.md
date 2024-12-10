# Analītiskās ģeometrijas uzdevumu risinājumi

## 22. Uzdevums
**Uzdevums:** Uzrakstīt taisnes parametrisko un kanonisko vienādojumu, ja tā iet caur punktiem (1, –3, 6) un (3, 3, 1).

**Risinājums:**
1) Virziena vektors $\vec{s} = (3-1, 3-(-3), 1-6) = (2, 6, -5)$
2) Parametriskais vienādojums:
   ```
   x = 1 + 2t
   y = -3 + 6t
   z = 6 - 5t
   ```
3) Kanoniskais vienādojums:
   $(x-1)/2 = (y+3)/6 = (z-6)/(-5)$

**Atbilde:** Taisnes parametriskais un kanoniskais vienādojumi uzrakstīti augstāk.

## 23. Uzdevums
**Uzdevums:** Uzrakstīt vienādojumu taisnei, kas iet caur punktu (3, 3) perpendikulāri taisnei 2x – 3y + 1 = 0.

**Risinājums:**
1) Dotās taisnes virziena vektors $\vec{s_1} = (3, 2)$
2) Perpendikulārās taisnes virziena vektors $\vec{s_2} = (-2, 3)$
3) Vienādojums: $-2(x-3) + 3(y-3) = 0$
4) Vienkāršojot: $-2x + 3y - 3 = 0$

**Atbilde:** $-2x + 3y - 3 = 0$

## 24. Uzdevums
**Uzdevums:** Atrast taišņu 5x – y – 4 = 0, un x – y + 1 = 0 krustpunktu.

**Risinājums:**
1) Sistēma:
   ```
   5x - y = 4
   x - y = -1
   ```
2) Atņemot vienādojumus: $4x = 5$
3) $x = 5/4$
4) Ievietojot pirmajā vienādojumā:
   $5(5/4) - y = 4$
   $25/4 - y = 4$
   $y = 25/4 - 4 = 25/4 - 16/4 = 9/4$

**Atbilde:** Krustpunkts $(5/4, 9/4)$

## 25. Uzdevums
**Uzdevums:** Noteikt punktam P(–2, 4) simetrisko punktu attiecībā pret taisni 3x + y – 8 = 0.

**Risinājums:**
1) Simetriskā punkta koordinātas aprēķina pēc formulas:
   ```
   x' = x + 2a(ax₀ + by₀ + c)/(a² + b²)
   y' = y + 2b(ax₀ + by₀ + c)/(a² + b²)
   ```
2) Šajā gadījumā a = 3, b = 1, c = -8
3) Ievietojot:
   ```
   x' = -2 + 2·3(3·(-2) + 1·4 - 8)/(3² + 1²)
   y' = 4 + 2·1(3·(-2) + 1·4 - 8)/(3² + 1²)
   ```
4) Aprēķinot: $x' = 2$, $y' = 0$

**Atbilde:** Simetriskais punkts $(2, 0)$

## 26. Uzdevums
**Uzdevums:** Uzrakstīt vienādojumu plakņu {x + y + z – 4 = 0; 2x – y + 4z + 5 = 0} šķēluma taisnei.

**Risinājums:**
1) Virziena vektors $\vec{s} = \vec{n_1} \times \vec{n_2}$
   $\vec{s} = (1,1,1) \times (2,-1,4)$
2) $\vec{s} = (5,-2,-3)$
3) Taisnes kanoniskais vienādojums:
   $(x-x_0)/5 = (y-y_0)/(-2) = (z-z_0)/(-3)$

**Atbilde:** $(x-x_0)/5 = (y-y_0)/(-2) = (z-z_0)/(-3)$, kur $(x_0,y_0,z_0)$ ir jebkurš punkts uz šķēluma taisnes.

## 27. Uzdevums
**Uzdevums:** Doti punkti A(3,–1,2), B(4,–1,–1), C(2,0,2). Uzrakstīt plaknes vienādojumus.

**Risinājums:**
a) Vispārīgais vienādojums:
1) Vektori $\vec{AB} = (1,0,-3)$ un $\vec{AC} = (-1,1,0)$
2) Normālvektors $\vec{n} = \vec{AB} \times \vec{AC} = (3,3,1)$
3) Vienādojums: $3(x-3) + 3(y+1) + (z-2) = 0$
4) Vienkāršojot: $3x + 3y + z - 11 = 0$

b) Parametriskais vienādojums:
```
x = 3 + t₁
y = -1 + t₂
z = 2 + (-3t₁ + 0t₂)
```

c) Asu nogriežņos:
$x/a + y/b + z/c = 1$, kur $a$, $b$, $c$ ir krustpunkti ar asīm

**Atbilde:** Sniegta trīs veidu vienādojumos augstāk.

## 28. Uzdevums
**Uzdevums:** Uzrakstīt vienādojumu plaknei, kas iet caur punktu M(2, –1, 1) perpendikulāri divām plaknēm 2x – z + 1 = 0, un y = 0.

**Risinājums:**
1) Normālvektori: $\vec{n_1} = (2,0,-1)$ un $\vec{n_2} = (0,1,0)$
2) Plaknes normālvektors: $\vec{n} = \vec{n_1} \times \vec{n_2} = (-1,0,2)$
3) Vienādojums: $-x + 2z + c = 0$
4) Ievietojot punktu M: $-2 + 2(1) + c = 0$
5) $c = 0$

**Atbilde:** $-x + 2z = 0$

## 29. Uzdevums
**Uzdevums:** Atrast punkta P(5, 2, –1) projekciju uz plaknes 2x – y + 3z + 23 = 0.

**Risinājums:**
1) Projekcijas punkta koordinātas:
   ```
   x' = x₀ - 2k
   y' = y₀ + k
   z' = z₀ - 3k
   ```
   kur $k = \frac{2x₀ - y₀ + 3z₀ + 23}{\sqrt{4 + 1 + 9}}$
2) Ievietojot koordinātas:
   $k = \frac{2(5) - 2 + 3(-1) + 23}{\sqrt{14}} = \frac{27}{\sqrt{14}}$
3) Aprēķinot projekcijas koordinātas:
   ```
   x' = 5 - 2(27/√14)
   y' = 2 + 27/√14
   z' = -1 - 3(27/√14)
   ```

**Atbilde:** Projekcijas punkts $(5 - 54/\sqrt{14}, 2 + 27/\sqrt{14}, -1 - 81/\sqrt{14})$

## 30. Uzdevums
**Uzdevums:** Sastādīt vienādojumu plaknei, kas iet caur punktu A(1, –1, 2) un ir paralēla plaknei x – 3y + 2z + 1 = 0.

**Risinājums:**
1) Paralēlās plaknes vienādojums būs ar tādu pašu normālvektoru: $x – 3y + 2z + c = 0$
2) Ievietojot punktu A: $1 - 3(-1) + 2(2) + c = 0$
3) $1 + 3 + 4 + c = 0$
4) $c = -8$

**Atbilde:** $x – 3y + 2z - 8 = 0$

## 31. Uzdevums
**Uzdevums:** Aprēķināt attālumu starp divām paralēlām plaknēm 3x – 4y + 12z + 26 = 0, un 3x – 4y + 12z – 39 = 0.

**Risinājums:**
1) Attālumu aprēķina pēc formulas:
   $d = \frac{|c_2-c_1|}{\sqrt{a^2+b^2+c^2}}$
2) $d = \frac{|-39-26|}{\sqrt{9+16+144}}$
3) $d = \frac{65}{\sqrt{169}} = 5$

**Atbilde:** 5 vienības

## 32. Uzdevums
**Uzdevums:** Atrast leņķi starp taisni {x + y + z – 4 = 0; 2x – y + 4z + 5 = 0} un plakni x + y +3z – 1 = 0.

**Risinājums:**
1) Taisnes virziena vektors $\vec{s}$ ir šķēluma plakņu normālvektoru vektoriālais reizinājums
2) $\vec{s} = (1,1,1) \times (2,-1,4) = (5,-2,-3)$
3) Plaknes normālvektors $\vec{n} = (1,1,3)$
4) Leņķi aprēķina: $\sin \phi = \frac{|\vec{s}\cdot\vec{n}|}{|\vec{s}||\vec{n}|}$
5) $\sin \phi = \frac{|5+(-2)+(-9)|}{\sqrt{38}\sqrt{11}}$

**Atbilde:** $\phi = \arcsin(\frac{6}{\sqrt{38}\sqrt{11}})$

## 33. Uzdevums
**Uzdevums:** Atrast attālumu un leņķi starp taisnēm (x – 1)/2 = (y – 2)/3 = (z + 3)/–1, un (x + 1)/3 = y/4 = (z–10)/6.

**Risinājums:**
1) Virziena vektori:
   $\vec{s_1} = (2,3,-1)$
   $\vec{s_2} = (3,4,6)$
2) Leņķis:
   $\cos \phi = \frac{\vec{s_1}\cdot\vec{s_2}}{|\vec{s_1}||\vec{s_2}|}$
3) Attālums:
   $d = \frac{|(\vec{M_1M_2},[\vec{s_1}\times\vec{s_2}])|}{|\vec{s_1}\times\vec{s_2}|}$
   kur $M_1(1,2,-3)$ un $M_2(-1,0,10)$ ir punkti uz taisnēm

**Atbilde:** 
- Leņķis $\phi = \arccos(\frac{6+12-6}{\sqrt{14}\sqrt{61}})$
- Attālums aprēķināms pēc dotās formulas augstāk
