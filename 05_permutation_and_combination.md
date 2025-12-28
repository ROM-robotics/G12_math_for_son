## အခန်း (၅) — Permutation နှင့် Combination  
*(စာမေးပွဲအတွက် အတိုချုံး Notes + Formula + Trick)*

---

### ၁။ မိတ်ဆက်
Permutation နှင့် Combination သည် **ရေတွက်ခြင်း (Counting)** ဆိုင်ရာ သင်္ချာခေါင်းစဉ်ဖြစ်ပြီး  
**အစီအစဉ် (Order)** ကို စဉ်းစားရမလား / မစဉ်းစားရဘူးလား ဆိုတာက အဓိကပါ။

---

### ၂။ Factorial (!)

![factorial](https://latex.codecogs.com/svg.image?n!%20=%20n%20%5Ctimes%20(n-1)%20%5Ctimes%20...%20%5Ctimes%202%20%5Ctimes%201)

![zero factorial](https://latex.codecogs.com/svg.image?0!%20=%201)

ဥပမာ  
![example](https://latex.codecogs.com/svg.image?5!%20=%20120)

---

### ၃။ Permutation (အစီအစဉ်ပါ)

#### အဓိပ္ပါယ်
**Order (အစီအစဉ်) အရေးကြီးရင် → Permutation**

#### Formula
![nPr](https://latex.codecogs.com/svg.image?%5EnP_r%20=%20%5Cfrac%7Bn!%7D%7B(n-r)!%7D)

#### ဥပမာ
လူ ၅ ယောက်ထဲက ၃ ယောက်ကို **အစီအစဉ်ထားခြင်း**

![example](https://latex.codecogs.com/svg.image?5P3%20=%20%5Cfrac%7B5!%7D%7B2!%7D%20=%2060)

---

### ၄။ Special Permutation

#### (၁) Total 
![nPn](https://latex.codecogs.com/svg.image?nP_n%20=%20n!)

#### (၂) repeatation ပါရင်
![repeated](https://latex.codecogs.com/svg.image?%5Ctext%7BTotal%7D%20=%20%5Cfrac%7Bn!%7D%7Bp!%20q!%20r!%20...%7D)

#### (၃) exclude ဆိုရင်
Total ထဲက ပြန်နှုတ်
---

### ၅။ Combination (ရွေးချယ်ခြင်း)

#### အဓိပ္ပါယ်
**Order မအရေးကြီးရင် → Combination**

#### Formula
![nCr](https://latex.codecogs.com/svg.image?%5EnC_r%20=%20%5Cfrac%7Bn!%7D%7Br!(n-r)!%7D)

#### ဥပမာ
လူ ၅ ယောက်ထဲက ၃ ယောက် **ရွေးချယ်ခြင်း**

![example](https://latex.codecogs.com/svg.image?5C3%20=%20%5Cfrac%7B5!%7D%7B3!2!%7D%20=%2010)

---

### ၆။ P နှင့် C ဆက်စပ်မှု
![relation](https://latex.codecogs.com/svg.image?%5EnP_r%20=%20%5EnC_r%20%5Ctimes%20r!)

---

### ၇။ Addition Rule (ပေါင်းနည်း) ဘယ်အခြေအနေမှာ သုံးလဲ?

- Either / Or
- တစ်ချိန်တည်း တစ်ခုတည်းသာ ရွေးနိုင်
- ရွေးချယ်မှုတွေ မထပ်
```bash
# Formula
Total ways = m + n
# Example
Bus (3 ways) or Train (2 ways)
Total ways = 3 + 2 = 5
```
---
### ၈။ Multiplication Rule (မြှောက်နည်း) ဘယ်အခြေအနေမှာ သုံးလဲ?

- And / Then
- အဆင့်လိုက် ရွေးရတဲ့အခါ
- Choice တစ်ခုချင်းစီ ဆက်စပ်
```bash
# Formula
Total ways = m x n
# Example
Shirt 3 မျိုး and Pant 2 မျိုး
Total ways = 3 * 2 = 6
```

---
### ၉။ Counting Subsets of a Finite Set

- Element တစ်ခုစီမှာ ပါ / မပါ ဆိုပြီး ရွေးချယ်မှု ၂ မျိုး ရှိ
```bash
# Formula
Number of subsets = 2^n
# Example 
n = 3      ==>   2^3 = 8
```
---
### ၇။ Combination Properties (စာမေးပွဲထဲ မကြာခဏ)

#### Symmetry Rule
![symmetry](https://latex.codecogs.com/svg.image?%5EnC_r%20=%20%5EnC_%7Bn-r%7D)

#### Boundary Values
![boundary](https://latex.codecogs.com/svg.image?%5EnC_0%20=%20%5EnC_n%20=%201)

---

### ၈။ Exam Trick — P လား C လား ချက်ချင်းဆုံးဖြတ်နည်း 🔥

#### ❓ မေးခွန်းထဲမှာ ဒီစကားလုံးတွေတွေ့ရင်

| စကားလုံး | သုံးရမယ့်အရာ |
|--------|--------------|
| အစီအစဉ်ချ | Permutation |
| Seating / Arrangement | Permutation |
| Rank / Position | Permutation |
| ရွေးချယ် | Combination |
| Committee | Combination |
| Group ဖွဲ့ | Combination |

---

### ၉။ Golden Rule ⭐
> **Order ပြောင်းရင် အဖြေပြောင်းသွားလား?**

- ပြောင်းသွားရင် → **Permutation**
- မပြောင်းရင် → **Combination**

---

### ၁၀။ Exam Tip (အမှတ်မြင့်ဖို့)
- Formula ကို အရင်ရေး
- P / C ကို အရင်ဆုံးဆုံးဖြတ်
- Factorial ကို နောက်ဆုံးမှ ဖြုတ်တွက်

---

### ✅ အနှစ်ချုပ်
- **Permutation → Order အရေးကြီး**
- **Combination → Order မအရေးကြီး**
- Formula မှန်မှ အဖြေမှန်

---

📌 *Grade 12 Mathematics – Chapter 5*  