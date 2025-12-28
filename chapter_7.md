# Chapter 7: Trigonometric Functions (ထရီဂိုနိုမက်ထရစ် လုပ်ဆောင်ချက်များ)

## အခန်း အကျဉ်းချုပ်

ဤအခန်းတွင် ထရီဂိုနိုမက်ထရစ် လုပ်ဆောင်ချက်များ၏ ဂရပ်များ၊ ပြောင်းလဲမှုများနှင့် differentiation များကို လေ့လာမည် ။

---

## 7.1 Sine Functions ၏ ဂရပ်များ

### အခြေခံ လက္ခဏာများ

**Periodic Function (အလှည့်ကျ လုပ်ဆောင်ချက်)**
- အကယ်၍ $f(x) = f(x + p)$ ဖြစ်ပါက $f$ သည် periodic function ဖြစ်သည်
- $p$ သည် period (အလှည့်ကျ ကာလ) ဖြစ်သည်

**Amplitude (လှိုင်းမြင့်)**
$$\text{Amplitude} = \frac{1}{2}(\text{အမြင့်ဆုံး တန်ဖိုး} - \text{အနိမ့်ဆုံး တန်ဖိုး})$$

### $y = a \sin bx$ ၏ ဂရပ် (a > 0, b > 0)

**လက္ခဏာများ:**
- **Domain:** $\mathbb{R}$ (အားလုံး real numbers)
- **Range:** $\{y \mid -a \leq y \leq a\}$
- **Period:** $\frac{2\pi}{b}$
- **Amplitude:** $a$

**ငါးခု အဓိက အမှတ်များ (y = sin x အတွက်):**
1. $(0, 0)$ - မူလ အမှတ်
2. $\left(\frac{\pi}{2}, 1\right)$ - အမြင့်ဆုံး အမှတ်
3. $(\pi, 0)$ - x-axis ဖြတ်သန်းမှု
4. $\left(\frac{3\pi}{2}, -1\right)$ - အနိမ့်ဆုံး အမှတ်
5. $(2\pi, 0)$ - တစ်ကြိမ် လှည့်ပြီး

### ပုံ: y = sin x ၏ ဂရပ်

```
     y
     |
   1 |     ╱‾‾‾╲
     |   ╱       ╲
     | ╱           ╲
   0 |─────────────╲─────╱─────> x
     |         ╲   ╱   ╱
  -1 |          ╲╱╲╱
     |
     0   π/2  π  3π/2  2π
```

**ဂရပ် ရှင်းလင်းချက်:**
- လှိုင်းပုံစံ ဖြစ်သည်
- x-axis ကို $(0,0)$, $(\pi, 0)$, $(2\pi, 0)$ တွင် ဖြတ်သည်
- အမြင့်ဆုံး တန်ဖိုး = 1, အနိမ့်ဆုံး တန်ဖိုး = -1
- တစ်ကြိမ် လှည့်ပြီး = $2\pi$

---

## 7.2 Cosine Functions ၏ ဂရပ်များ

### $y = a \cos bx$ ၏ ဂရပ် (a > 0, b > 0)

**လက္ခဏာများ:**
- **Domain:** $\mathbb{R}$
- **Range:** $\{y \mid -a \leq y \leq a\}$
- **Period:** $\frac{2\pi}{b}$
- **Amplitude:** $a$

**အဓိက အမှတ်များ (y = cos x အတွက်):**
- $(0, 1)$ - အမြင့်ဆုံး အမှတ်
- $\left(\frac{\pi}{2}, 0\right)$ - x-axis ဖြတ်သန်းမှု
- $(\pi, -1)$ - အနိမ့်ဆုံး အမှတ်
- $\left(\frac{3\pi}{2}, 0\right)$ - x-axis ဖြတ်သန်းမှု
- $(2\pi, 1)$ - အမြင့်ဆုံး ပြန်ရောက်

### ပုံ: y = cos x ၏ ဂရပ်

```
     y
     |
   1 |‾‾‾╲     ╱‾‾‾╲
     |     ╲   ╱     ╲
     |      ╲ ╱       ╲
   0 |───────╳─────────╳───> x
     |        ╲       ╱
  -1 |         ╲_____╱
     |
     0   π/2  π  3π/2  2π
```

**ဂရပ် ရှင်းလင်းချက်:**
- Sine လှိုင်း ကို $\frac{\pi}{2}$ ဘယ်ဘက်သို့ ရွှေ့လိုက်သလို ဖြစ်သည်
- $(0, 1)$ မှ စတင်သည်
- Period = $2\pi$, Amplitude = 1

---

## 7.3 အခြား Trigonometric Functions များ၏ ဂရပ်များ

### Tangent Function: $y = \tan x$

**လက္ခဏာများ:**
- **Domain:** $x \neq \frac{\pi}{2}, \frac{3\pi}{2}, ...$
- **Range:** $\mathbb{R}$
- **Period:** $\pi$
- **Asymptotes (ချဉ်းကပ်မျဉ်း):** $x = \frac{\pi}{2} + n\pi$ ($n$ သည် integer)

### ပုံ: y = tan x ၏ ဂရပ်

```
     y
     |    |         |         |
   ∞ |    |    ╱    |    ╱    |
     |    |  ╱      |  ╱      |
     |    |╱        |╱        |
   0 |────────────────────────> x
     |  ╱ |       ╱ |       ╱
     |╱   |     ╱   |     ╱
  -∞ |    |   ╱     |   ╱     |
     |    |         |         |
    -π/2  0   π/2   π  3π/2  2π
         (asymptotes)
```

**ဂရပ် ရှင်းလင်းချက်:**
- Vertical asymptotes များ: $x = \pm\frac{\pi}{2}, \pm\frac{3\pi}{2}, ...$
- $(0, 0)$ ကို ဖြတ်သန်းသည်
- Period = $\pi$ (sine/cosine ထက် တစ်ဝက်သာ)

### Cotangent Function: $y = \cot x$

**လက္ခဏာများ:**
- **Domain:** $x \neq 0, \pi, 2\pi, ...$
- **Range:** $\mathbb{R}$
- **Period:** $\pi$
- **Asymptotes:** $x = n\pi$

### Secant Function: $y = \sec x = \frac{1}{\cos x}$

**လက္ခဏာများ:**
- **Domain:** $x \neq \frac{\pi}{2} + n\pi$
- **Range:** $(-\infty, -1] \cup [1, \infty)$
- **Period:** $2\pi$

### ပုံ: Secant နှင့် Cosecant Functions

**y = sec x (အနီရောင်) နှင့် y = cos x (အပြာရောင်):**
```
     y
     |
   ∞ |  U       U       U
   2 |  |       |       |
   1 |──╲──╱‾‾‾╲──╱────────> x
     |   ╲╱     ╲╱
  -1 |────────────────────
  -2 |   |       |
  -∞ |   ∩       ∩
     |
     0   π/2   π  3π/2  2π
```

**ရှင်းလင်းချက်:**
- Secant သည် Cosine ၏ reciprocal ဖြစ်သည်
- Cosine = 0 ဖြစ်သည့် နေရာတွင် asymptotes ရှိသည်
- Range: $y \leq -1$ သို့မဟုတ် $y \geq 1$

### Cosecant Function: $y = \csc x = \frac{1}{\sin x}$

**လက္ခဏာများ:**
- **Domain:** $x \neq n\pi$
- **Range:** $(-\infty, -1] \cup [1, \infty)$
- **Period:** $2\pi$

---

## 7.4 Inverse Trigonometric Functions (ပြောင်းပြန် ထရီဂိုနိုမက်ထရစ် လုပ်ဆောင်ချက်များ)

### အဓိက Inverse Functions သုံးခု

**1. Inverse Sine:** $y = \sin^{-1} x$ (သို့မဟုတ် arcsin x)
- **Domain:** $-1 \leq x \leq 1$
- **Range:** $-\frac{\pi}{2} \leq y \leq \frac{\pi}{2}$
- **အဓိပ္ပါယ်:** $\sin y = x$ ဖြစ်သည်

### ပုံ: Inverse Sine Function

```
     y
     |
  π/2|────•
     |   ╱
     | ╱
   0 |╱──────────> x
     |╲
     | ╲
 -π/2|  ╲
     |   •────
    -1   0   1
```

**2. Inverse Cosine:** $y = \cos^{-1} x$ (သို့မဟုတ် arccos x)
- **Domain:** $-1 \leq x \leq 1$
- **Range:** $-\frac{\pi}{2} \leq y \leq \frac{\pi}{2}$
- **အဓိပ္ပါယ်:** $\sin y = x$ ဖြစ်သည်

**2. Inverse Cosine:** $y = \cos^{-1} x$ (သို့မဟုတ် arccos x)
- **Domain:** $-1 \leq x \leq 1$
- **Range:** $0 \leq y \leq \pi$
- **အဓိပ္ပါယ်:** $\cos y = x$ ဖြစ်သည်

### ပုံ: Inverse Cosine Function

```
     y
     |
   π |•────
     | ╲
     |  ╲
 π/2 |   ╲
     |    ╲
   0 |─────•─────> x
    -1     0     1
```

**3. Inverse Tangent:** $y = \tan^{-1} x$ (သို့မဟုတ် arctan x)
- **Domain:** $\mathbb{R}$
- **Range:** $-\frac{\pi}{2} < y < \frac{\pi}{2}$
- **အဓိပ္ပါယ်:** $\tan y = x$ ဖြစ်သည်

### ပုံ: Inverse Tangent Function

```
     y
     |
  π/2|------------ (asymptote)
     |     ╱
     |   ╱
   0 |─╱───────> x
     |╱
     ╱
 -π/2|------------ (asymptote)
     |
```

**ရှင်းလင်းချက်:**
- Range ကို ကန့်သတ်ထားသည် (one-to-one function ဖြစ်ရန်)
- Horizontal asymptotes များ ရှိသည်

### ဥပမာ တွက်ချက်မှုများ

$$\sin^{-1}\left(\frac{1}{2}\right) = \frac{\pi}{6}$$

$$\cos^{-1}\left(-\frac{1}{2}\right) = \frac{2\pi}{3}$$

$$\tan^{-1}(1) = \frac{\pi}{4}$$

---

## 7.5 Trigonometric Functions များ၏ Differentiation

### Unit Circle သုံး သက်သေပြချက်

```
      y
      |
    1 |    • P(x,y)
      |   /|
      |  / |θ
      | /  |
      |/___| 
    0 |────────> x
      0    1
      
   sin θ = y/r = y (r=1 အတွက်)
   lim(θ→0) sin θ/θ = 1
```

**အရေးကြီး Limit:**
$$\lim_{x \to 0} \frac{\sin x}{x} = 1$$

ဤ limit သည် sine function ကို differentiate လုပ်ရာတွင် အခြေခံ ဖြစ်သည်။

### အခြေခံ Derivative ပုံသေနည်းများ

**ငြင်းခွင့် ခြောက်ခု:**

$$\frac{d}{dx}(\sin x) = \cos x$$

$$\frac{d}{dx}(\cos x) = -\sin x$$

$$\frac{d}{dx}(\tan x) = \sec^2 x$$

$$\frac{d}{dx}(\cot x) = -\csc^2 x$$

$$\frac{d}{dx}(\sec x) = \sec x \cdot \tan x$$

$$\frac{d}{dx}(\csc x) = -\csc x \cdot \cot x$$

### Chain Rule အသုံးပြု Differentiation

**အကယ်၍ $u = u(x)$ ဖြစ်ပါက:**

$$\frac{d}{dx}(\sin u) = \cos u \cdot \frac{du}{dx}$$

$$\frac{d}{dx}(\cos u) = -\sin u \cdot \frac{du}{dx}$$

$$\frac{d}{dx}(\tan u) = \sec^2 u \cdot \frac{du}{dx}$$

$$\frac{d}{dx}(\cot u) = -\csc^2 u \cdot \frac{du}{dx}$$

$$\frac{d}{dx}(\sec u) = \sec u \cdot \tan u \cdot \frac{du}{dx}$$

$$\frac{d}{dx}(\csc u) = -\csc u \cdot \cot u \cdot \frac{du}{dx}$$

### အရေးကြီး Limit

$$\lim_{x \to 0} \frac{\sin x}{x} = 1$$

ဤ limit သည် $\frac{d}{dx}(\sin x) = \cos x$ ကို သက်သေပြရာတွင် အသုံးပြုသည်။

---

## ဥပမာ ပုစ္ဆာများ

### ဥပမာ ၁: Differentiation

**ပုစ္ဆာ:** $y = \sin(3x^2)$ ကို differentiate လုပ်ပါ။

**အဖြေ:**
$$\frac{dy}{dx} = \cos(3x^2) \cdot \frac{d}{dx}(3x^2)$$
$$= \cos(3x^2) \cdot 6x$$
$$= 6x\cos(3x^2)$$

### ဥပမာ ၂: Period and Amplitude

**ပုစ္ဆာ:** $y = 3\sin(2x)$ ၏ amplitude နှင့် period ကို ရှာပါ။

**အဖြေ:**
- **Amplitude:** $a = 3$
- **Period:** $\frac{2\pi}{b} = \frac{2\pi}{2} = \pi$

**ဂရပ် ပုံစံ:**
```
     y
     |
   3 |    ╱‾‾╲
     |  ╱      ╲
   0 |╱─────────╲────╱─> x
     |           ╲  ╱
  -3 |            ╲╱
     |
     0   π/4  π/2  3π/4  π

   အမြင့် 3 ဆ၊ period တစ်ဝက်
```

### ဥပမာ ၃: Second Derivative

**ပုစ္ဆာ:** $y = \cos x$ ၏ second derivative ကို ရှာပါ။

**အဖြေ:**
$$\frac{dy}{dx} = -\sin x$$
$$\frac{d^2y}{dx^2} = -\cos x$$

---

## အဓိက Identity များ

$$\sin^2 x + \cos^2 x = 1$$

$$\sec^2 x = 1 + \tan^2 x$$

$$\csc^2 x = 1 + \cot^2 x$$

$$\sin(\alpha - \beta) = 2\cos\left(\frac{\alpha+\beta}{2}\right) \cdot \sin\left(\frac{\alpha-\beta}{2}\right)$$

---

## အကျဉ်းချုပ်

Chapter 7 တွင် အောက်ပါ အချက်များကို လေ့လာခဲ့သည်:

1. **Sine နှင့် Cosine functions** များ၏ ဂရပ်များ၊ transformation များ၊ amplitude နှင့် period
2. **Tangent, Cotangent, Secant, Cosecant** functions များ၏ လက္ခဏာများနှင့် asymptotes များ
3. **Inverse trigonometric functions** များ၊ ၎င်းတို့၏ domain နှင့် range ကန့်သတ်ချက်များ
4. **Differentiation** - ထရီဂိုနိုမက်ထရစ် functions ခြောက်ခု အားလုံး၏ derivatives များ
5. **Chain rule** အသုံးပြု ရှုပ်ထွေး သော functions များ၏ differentiation

ဤ အခန်းသည် calculus နှင့် advanced mathematics များတွင် အခြေခံ အရေးကြီး သော အခန်းတစ်ခု ဖြစ်သည်။
