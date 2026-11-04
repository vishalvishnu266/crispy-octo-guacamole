# WEEK 1 – CSAT (Number System + RC) & QUICK-REVISION KIT
**Use:** CSAT practice daily, 16:15–17:15 (alternate Quant and RC days). Do the **Rapid Revision** and **Revision Plan** on Sunday.

---

# PART 1 – CSAT: NUMBER SYSTEM BASICS

## ⏱ Snapshot
CSAT is **qualifying** (you need **66/200**, i.e., 33%), but **many serious aspirants fail it**. The Number System underlies almost every Quant topic. This week: **classification, divisibility, factors, HCF/LCM, unit digits, remainders, and series sums**.

## 1.1 Classification of numbers
| Type | Definition | Key facts / traps |
|---|---|---|
| Natural (N) | 1, 2, 3, … | **0 is not natural** |
| Whole (W) | 0, 1, 2, … | — |
| Integers (Z) | …, −2, −1, 0, 1, 2, … | — |
| Rational (Q) | p/q, q ≠ 0 | **Terminating or recurring** decimals (e.g., 0.333…) |
| Irrational | Non-terminating, non-recurring | √2, π, e. ⚠️ **22/7 is rational** (it is only an approximation of π) |
| Prime | Exactly 2 factors | **2 is the only even prime**. **1 is neither prime nor composite**. **25 primes up to 100** |
| Composite | More than 2 factors | Smallest composite = **4** |
| Co-prime | HCF = 1 | (8, 15) are co-prime even though neither is prime |

🧠 **Primes up to 100 (25):** 2 3 5 7 · 11 13 17 19 · 23 29 · 31 37 · 41 43 47 · 53 59 · 61 67 · 71 73 79 · 83 89 · 97 (count per decade: 4-4-2-2-3-2-2-3-2-1)
**Quick prime test for N:** check divisibility by the primes ≤ √N.

## 1.2 Divisibility rules 📌
| By | Rule | Example |
|---|---|---|
| 2 | Last digit even | 3,456 ✓ |
| 3 | **Sum of digits** divisible by 3 | 1,236 → 12 ✓ |
| 4 | **Last 2 digits** divisible by 4 | 7,316 → 16 ✓ |
| 5 | Last digit 0 or 5 | — |
| 6 | Divisible by **2 and 3** | — |
| 7 | **Double the last digit and subtract it** from the rest; repeat | 343 → 34 − 6 = 28 ✓ |
| 8 | **Last 3 digits** divisible by 8 | 5,128 → 128 ✓ |
| 9 | **Sum of digits** divisible by 9 | 7,281 → 18 ✓ |
| 10 | Last digit 0 | — |
| 11 | **(Sum of odd-place digits) − (sum of even-place digits)** = 0 or a multiple of 11 | 918,082 → (2+0+1) − (8+8+9) = −22 ✓ |
| 12 | Divisible by **3 and 4** | — |
| Composite n | Divisible by its **co-prime factors** (e.g., 15 → 3 and 5; 18 → 2 and 9, **not** 3 and 6) | ⚠️ The factors must be **co-prime** |

## 1.3 Factors, HCF, LCM 📌
- If **N = aᵖ × bᵠ × cʳ** (prime factorisation):
  - **Number of factors = (p+1)(q+1)(r+1)**
  - **Sum of factors = [(a^(p+1) − 1)/(a − 1)] × [(b^(q+1) − 1)/(b − 1)] × …**
  - **Odd factors**: ignore the power of 2. **Even factors = total − odd**
  - A number has an **odd number of factors only if it is a perfect square**
- **HCF × LCM = product of the two numbers** (for 2 numbers only)
- **HCF of fractions = HCF(numerators) / LCM(denominators)**
- **LCM of fractions = LCM(numerators) / HCF(denominators)**
- **Classic forms:**
  - Largest number that divides a, b, c leaving the **same remainder** = **HCF of the differences** (b−a, c−b, c−a)
  - Smallest number that, when divided by x, y, z, leaves remainder r = **LCM(x, y, z) + r**
  - Smallest number that, when divided by x, y, z, leaves remainders that are each **k less** than the divisor = **LCM − k**

## 1.4 Unit digit (cyclicity) 📌
| Last digit | Cycle | Period |
|---|---|---|
| 0, 1, 5, 6 | Always itself | 1 |
| 4 | 4, 6 (odd power → 4, even → 6) | 2 |
| 9 | 9, 1 (odd → 9, even → 1) | 2 |
| 2 | 2, 4, 8, 6 | 4 |
| 3 | 3, 9, 7, 1 | 4 |
| 7 | 7, 9, 3, 1 | 4 |
| 8 | 8, 4, 2, 6 | 4 |

**Method:** find the power mod 4. If the remainder is 0, use the **4th** term of the cycle.

## 1.5 Remainders & useful results
- **(a × b) mod n = [(a mod n) × (b mod n)] mod n**, and likewise for sums
- **aⁿ − bⁿ** is divisible by **(a − b)** always, and by **(a + b)** when **n is even**
- **aⁿ + bⁿ** is divisible by **(a + b)** when **n is odd**
- **Trailing zeros of n!** = ⌊n/5⌋ + ⌊n/25⌋ + ⌊n/125⌋ + …
- **Sums:** 1+2+…+n = n(n+1)/2 · 1²+…+n² = n(n+1)(2n+1)/6 · 1³+…+n³ = [n(n+1)/2]² · **sum of the first n odd numbers = n²** · sum of the first n even numbers = n(n+1)
- **Arithmetic Progression:** nth term = a + (n−1)d; sum = n/2 × (first + last)
- **Counting multiples:** how many numbers from 1 to N are divisible by k = ⌊N/k⌋. **Inclusion–exclusion:** |A∪B| = |A| + |B| − |A∩B|

## 1.6 Practice Set (18 Qs, target 25 min) – attempt first, answers below

1. Unit digit of **7⁹⁵**?
2. Number of factors of **360**?
3. Number of trailing zeros in **100!**?
4. The HCF of two numbers is 12 and their LCM is 360. One number is 72. Find the other.
5. Smallest number which, when divided by 12, 15 and 20, leaves remainder 5 in each case?
6. Remainder when **2³¹** is divided by 5?
7. Is **918,082** divisible by 11? Find the quotient if it is.
8. Sum of all **two-digit** numbers divisible by 7?
9. How many numbers from 1 to 100 are divisible by **neither 2 nor 3**?
10. Unit digit of **3⁶⁵ × 6⁵⁹ × 7⁷¹**?
11. A number leaves remainder 3 when divided by 6. What is the remainder when its **square** is divided by 6?
12. Largest number that divides 1305, 4665 and 6905 leaving the **same remainder** in each case?
13. How many **even** factors does **2⁴ × 3³ × 5** have?
14. Remainder when **17²³** is divided by 16?
15. Sum of the first **50 odd** natural numbers?
16. LCM of **2/3, 4/9, 5/6**?
17. Trailing zeros in **125!**?
18. *(UPSC-type)* A 3-digit number **4a3** is added to 984 to give the 4-digit number **13b7**, which is divisible by 11. Find **a + b**.

---

# PART 2 – CSAT: READING COMPREHENSION (RC)

## 2.1 UPSC RC question types and how to crack them 📌
| Type | Asked as | Strategy |
|---|---|---|
| **Main idea / central theme** | "Which best reflects the crux of the passage?" | Find the **thesis** (usually in the first or last 2 lines). Reject options that are **too narrow** (one detail) or **too broad** (beyond the passage) |
| **Inference** | "Which can be inferred / is the most logical inference?" | It must **follow from** the passage without being stated outright. **No outside knowledge** |
| **Assumption** | "Which is a valid assumption?" | An **unstated premise** the author **must** believe for the argument to work. **Negation test:** negate it; if the argument collapses, it is an assumption |
| **Corollary / implication** | "What is the most rational corollary?" | A natural **consequence** of the main argument |
| **Author's tone / attitude** | "The author's view on X is…" | Look at **adjectives and qualifiers** ("merely", "yet", "however") |
| **Vocabulary in context** | "What does 'X' mean in the passage?" | Meaning **in context**, not the dictionary meaning |

### ⚠️ Elimination rules (they win most RC marks)
1. **Extreme words** (always, never, only, all, completely) are usually wrong.
2. **True in real life but not in the passage**: wrong.
3. **Partially true** (half right, half wrong): wrong.
4. **Out of scope**: a new idea not discussed: wrong.
5. **Opposite** of the author's stance: wrong.
6. Between two close options, choose the one that is **closer to the passage's central concern**.

### Method (about 4 min per passage)
1. Read the **questions' stems first** (10 sec).
2. Read the passage actively and mark the **thesis**, the **contrast words** (but, yet, however) and the **conclusion**.
3. Answer from the passage, using elimination.
4. Do **2 passages a day** from CSAT PYQs (2013–2026) and log your accuracy.

## 2.2 Practice Passages (linked to this week's GS topics)

### Passage 1
> "Constitutional morality," a phrase Dr Ambedkar borrowed from the historian George Grote, means more than obedience to the text of a constitution. It is a disposition: a willingness among rulers and citizens alike to respect the forms of the constitution, to submit to authority acting within those forms, and yet to keep the freedom to criticise that authority openly. Ambedkar warned that such morality is not a natural sentiment; it has to be cultivated. Where democracy is only a top-dressing on a soil that is essentially undemocratic, he argued, the administration could be perverted without changing a single word of the constitution. The real danger, therefore, lies less in the text than in the conduct of those who work it. A constitution, however good, may turn out bad if those called upon to work it lack the temper it presupposes.

**P1.Q1** Which of the following is the most logical inference from the passage?
(a) The Indian Constitution's text is defective and needs to be rewritten.
(b) The survival of constitutional democracy depends largely on the values and conduct of those who operate it.
(c) Citizens should refrain from criticising constitutional authorities.
(d) Constitutional morality emerges automatically once a constitution is adopted.

**P1.Q2** Consider the following assumptions:
1. The spirit of a constitution can be undermined even while its form remains unchanged.
2. Democratic values were already deeply rooted in the society to which the passage refers.
Which of the above is/are valid?
(a) 1 only (b) 2 only (c) Both 1 and 2 (d) Neither 1 nor 2

**P1.Q3** In the passage, "top-dressing" most nearly means:
(a) a strong foundation (b) a superficial layer (c) a decorative ceremony (d) a legal amendment

### Passage 2
> In the early nineteenth century, India was not merely an agrarian economy; its weavers, metal-workers and ship-builders supplied markets across Asia and Europe. The decline of these crafts is often explained by the superior efficiency of British machines. Yet efficiency alone does not explain the speed of the collapse. Indian goods entering Britain faced steep duties, while British manufactures entered India almost freely. Railways, built to carry raw cotton to the ports, carried Lancashire cloth back to the smallest market towns. Displaced artisans did not move to factories, for there were few; they moved to the land, which was already crowded. What is described as the "ruralisation" of India was thus not a return to a simpler past but the outcome of a particular structure of trade and power.

**P2.Q1** Which of the following best reflects the central idea of the passage?
(a) British machines were more efficient than Indian handicrafts.
(b) The decline of Indian crafts resulted from colonial trade policy and power structures, not merely technological inferiority.
(c) Railways were the main reason for the decline of Indian agriculture.
(d) Indian artisans preferred farming to factory work.

**P2.Q2** Which of the following can be inferred from the passage?
1. Without discriminatory tariffs, Indian crafts might have declined more slowly.
2. India had no manufacturing capability before British rule.
3. The movement of artisans to agriculture increased pressure on land.
Select: (a) 1 and 2 only (b) 2 and 3 only (c) 1 and 3 only (d) 1, 2 and 3

**P2.Q3** The author's attitude towards the "efficiency" explanation is that it is:
(a) fully convincing (b) completely false (c) incomplete (d) irrelevant

---

# ⚠️ ANSWERS: CSAT (check only after attempting)

| Q | Answer | Working |
|---|---|---|
| 1 | **3** | Cycle of 7: 7, 9, 3, 1. 95 mod 4 = 3, so the 3rd term = **3** |
| 2 | **24** | 360 = 2³ × 3² × 5 → (3+1)(2+1)(1+1) = 24 |
| 3 | **24** | ⌊100/5⌋ + ⌊100/25⌋ = 20 + 4 |
| 4 | **60** | (12 × 360)/72 = 60. Check: HCF(72, 60) = 12 ✓, LCM = 360 ✓ |
| 5 | **65** | LCM(12, 15, 20) = 60, plus 5 |
| 6 | **3** | 2⁴ ≡ 1 (mod 5). 31 = 4×7 + 3, so 2³ = 8 ≡ **3** |
| 7 | **Yes, 83,462** | Alternating sum = −22, a multiple of 11. 918,082 ÷ 11 = 83,462 |
| 8 | **728** | Terms 14, 21, …, 98: n = 13. Sum = 13 × (14 + 98)/2 = 13 × 56 |
| 9 | **33** | Divisible by 2: 50, by 3: 33, by 6: 16. Union = 67, so 100 − 67 = **33** |
| 10 | **4** | 3⁶⁵ → 3 (65 mod 4 = 1); 6⁵⁹ → 6; 7⁷¹ → 3 (71 mod 4 = 3). 3 × 6 × 3 = 54, so **4** |
| 11 | **3** | n = 6k + 3, so n² = 36k² + 36k + 9 ≡ 9 ≡ **3** (mod 6) |
| 12 | **1120** | Differences: 3360, 2240, 5600. HCF = 1120. (Each number leaves remainder 185) |
| 13 | **32** | Total = (4+1)(3+1)(1+1) = 40. Odd factors (ignoring 2) = 4 × 2 = 8. Even = **32** |
| 14 | **1** | 17 ≡ 1 (mod 16), so 1²³ = **1** |
| 15 | **2500** | n² = 50² |
| 16 | **20/3** | LCM(2, 4, 5) / HCF(3, 9, 6) = 20/3 |
| 17 | **31** | 25 + 5 + 1 |
| 18 | **10** | Units: 3 + 4 = 7, no carry. Hundreds: 4 + 9 = 13 with **no carry from the tens**, so a + 8 = b (< 10). 13b7 divisible by 11: (7 + 3) − (b + 1) = 9 − b = 0, so **b = 9** and **a = 1**. a + b = **10** |

**RC Answers**
| Q | Ans | Why (and why the others are wrong) |
|---|---|---|
| P1.Q1 | **(b)** | The passage says the danger lies "less in the text than in the conduct". (a) The passage doesn't say the text is defective. (c) It is the opposite: the passage values the "freedom to criticise". (d) It is the opposite: morality "has to be cultivated" |
| P1.Q2 | **(a)** | Statement 1 is implied ("perverted without changing a single word"). Statement 2 contradicts "a soil that is essentially undemocratic" |
| P1.Q3 | **(b)** | A thin layer on top of an undemocratic soil, i.e., superficial |
| P2.Q1 | **(b)** | The thesis is in "efficiency alone does not explain…" and the last line. (a) is a detail the passage challenges. (c) is a distortion: railways carried cloth, and agriculture is not the subject. (d) is not stated: there were "few" factories |
| P2.Q2 | **(c)** | 1 follows from the role of the tariffs. 3 follows from "the land, which was already crowded". 2 contradicts the first line |
| P2.Q3 | **(c)** | "Efficiency **alone** does not explain…": the author accepts it partly but finds it insufficient |

---

# PART 3 – RAPID REVISION: WEEK 1 IN 60 FACTS (read aloud on Sunday, about 15 min)

### Polity (35)
1. **Regulating Act 1773**: first step to control the EIC; GG of Bengal (Hastings); SC at Calcutta (1774).
2. **Pitt's India Act 1784**: Board of Control; double government.
3. **Charter Act 1813**: ended the trade monopoly (except tea and China); ₹1 lakh for education.
4. **Charter Act 1833**: GG of India (Bentinck); EIC purely administrative; centralisation.
5. **Charter Act 1853**: legislative and executive functions separated; open competition for the civil service.
6. **GoI Act 1858**: Crown rule; Viceroy (Canning); Secretary of State plus a 15-member Council.
7. **1861**: Indians nominated; portfolio system; ordinances (6 months).
8. **1892**: indirect election; budget discussion.
9. **1909 Morley–Minto**: separate electorate for Muslims; S.P. Sinha on the Executive Council.
10. **1919 Montford**: provincial dyarchy; bicameral Centre; direct elections; Public Service Commission.
11. **1935 Act**: 321 sections; three lists (59/54/36); provincial autonomy; Federal Court; RBI.
12. **Indian Independence Act 1947**: two dominions; the CA becomes sovereign and the legislature.
13. **CA**: Cabinet Mission; 389 seats (296 + 93); indirectly elected; Congress 208, League 73.
14. 9 Dec 1946 first meeting (Sinha temporary); 11 Dec, **Rajendra Prasad**; B.N. Rau adviser.
15. **Objectives Resolution**: Nehru, 13 Dec 1946; adopted 22 Jan 1947.
16. **Drafting Committee**: 29 Aug 1947; 7 members; Ambedkar.
17. Adopted **26 Nov 1949** (Preamble, 395 Articles, 22 Parts, 8 Schedules); in force **26 Jan 1950**.
18. Provisions in force on 26 Nov 1949: **citizenship, elections, provisional Parliament, transitional provisions, short title** (the CEPTS hook).
19. **Preamble**: amended once (42nd; Socialist, Secular, Integrity); part of the Constitution (Kesavananda); non-justiciable.
20. Preamble ideals: Justice from **USSR**; Liberty, Equality, Fraternity from **France**.
21. Sources: DPSP from **Ireland**; residuary powers from **Canada**; Concurrent List and joint sitting from **Australia**; amendment from **South Africa**; FDs from the **USSR**; procedure established by law from **Japan**.
22. **Art 3**: simple majority; President's recommendation; state's views not binding.
23. Cession of territory requires an **Art 368** amendment (Berubari 1960). The **100th Amendment** gave effect to the LBA with Bangladesh.
24. Citizenship by birth: before 1 July 1987, any parents; to 3 Dec 2004, one parent a citizen; after that, both parents (or one, with the other not an illegal migrant).
25. **CAA**: six communities; three countries; entry by 31 Dec 2014; Rules notified March 2024.
26. Rights only for citizens: **Arts 15, 16, 19, 29, 30**.
27. **6 FRs**; property became Art 300A (44th Amendment).
28. **Arts 20 and 21** are never suspended. Art 19 is suspended only in a war or external-aggression emergency.
29. **Art 21**: Gopalan → Maneka (the golden triangle) → Puttaswamy (privacy, 2017).
30. **Reservation**: Indra Sawhney (50%, creamy layer) → Janhit Abhiyan (EWS upheld, 3:2) → Davinder Singh (sub-classification, 6:1, 2024).
31. **Writs**: habeas corpus also lies against private persons; mandamus not against the President; prohibition and certiorari against judicial bodies (certiorari also against administrative ones); quo warranto only for public offices.
32. **Art 32**: "heart and soul"; the HC's power under Art 226 is wider.
33. **DPSP**: the 42nd Amendment added 39(f), 39A, 43A and 48A; 44th: 38(2); 86th: 45; 97th: 43B.
34. **FDs**: 42nd Amendment (Swaran Singh); 11 duties; (k) added by the 86th; citizens only.
35. **Basic Structure**: Kesavananda (1973, 7:6) → Indira Gandhi (1975) → Minerva Mills (1980) → NJAC (2015).

### Modern History (25)
36. Order of arrival: **Portuguese → Dutch → English → Danes → French**.
37. **Albuquerque** captured Goa (1510); Cunha made it the capital (1530).
38. Bombay came as a **dowry** (1661) and was leased to the EIC in 1668 at £10 a year.
39. **Farrukhsiyar's farman (1717)**: the Company's "Magna Carta"; dastaks.
40. **Carnatic Wars**: St Thome (1746) showed European superiority; **Wandiwash (1760)** was decisive.
41. **Plassey (1757)**: won through conspiracy (Mir Jafar). **Buxar (1764)**: against three powers, leading to the Diwani.
42. **Treaty of Allahabad (1765)**: Diwani of Bengal, Bihar and Orissa; ₹26 lakh a year to Shah Alam.
43. **Dual Government (1765–72)**: Clive; abolished by Hastings. The Bengal famine of 1770.
44. **Mysore treaties**: Madras (1769), Mangalore (1784), Seringapatam (1792); Tipu killed in 1799.
45. **Maratha treaties**: Salbai (1782), Bassein (1802); the Peshwaship ended in 1818.
46. **Subsidiary Alliance**: Wellesley; Hyderabad was the first to accept (1798).
47. **Doctrine of Lapse**: Dalhousie; Satara the first (1848); **Awadh** annexed in 1856 for misgovernance, not lapse.
48. **Cornwallis**: father of the civil services; the Cornwallis Code (1793) separated revenue and judicial work.
49. **Ripon**: local self-government (1882); repealed the VPA; the Ilbert Bill.
50. **Wood's Despatch (1854)**: the Magna Carta of English education; universities in 1857.
51. **Macaulay's Minute (1835)**: downward filtration.
52. **Drain of wealth**: Naoroji (*Poverty and Un-British Rule*, 1901); R.C. Dutt.
53. **Permanent Settlement**: Cornwallis, 1793; zamindars; 10/11th share; sunset law; about 19% of the area.
54. **Ryotwari**: Munro and Read; Madras and Bombay; about 51% of the area.
55. **Mahalwari**: Holt Mackenzie, 1822; NWP and Punjab; about 30%; Bird and Thomason.
56. **Brahmo Sabha (1828)** → split in 1866 (Adi Samaj vs Brahmo Samaj of India) → Sadharan Samaj (1878).
57. **Arya Samaj**: Bombay, 1875; *Satyarth Prakash*; Shuddhi; the DAV vs Gurukul split.
58. **Theosophical Society**: New York, 1875; Adyar; Annie Besant.
59. **Satyashodhak Samaj (1873)**: Phule; *Gulamgiri*. **SNDP (1903)**: Narayana Guru. **Vaikom (1924–25)**.
60. **Laws**: sati (1829, Bentinck), widow remarriage (1856, Canning), Age of Consent (1891), Sarda Act (1929).

---

# PART 4 – WEEK 1 REVISION & ANSWER-WRITING PLAN

## 4.1 Daily routine with these notes
| Time | Activity | File |
|---|---|---|
| 06:00–06:30 | Read yesterday's **⏱ Snapshot + ⚠️ Traps** | Notes |
| 08:45 (first 15 min) | Attempt today's **Question Bank** block cold | Q&A file |
| 08:45–11:45 | Laxmikanth, then cross-check with the notes | Polity notes |
| 12:00–13:00 | PYQs on today's topic | PYQ book |
| 14:30–16:00 | Spectrum, then cross-check | History notes |
| 16:15–17:15 | CSAT (Mon/Wed/Fri: Quant; Tue/Thu/Sat: RC) | This file |
| 18:30–19:30 | **Write 2 analytical answers** (7 min each) + 15 min of maps | Notes ❓ sections |
| 21:00–21:30 | Mistake register | — |

## 4.2 Sunday (8 Nov) plan
| Slot | Task |
|---|---|
| 09:00–09:20 | **Part C** of the Question Bank (10 Qs, timed) |
| 09:20–11:00 | PYQs on **FR/DPSP/Preamble** (2013 onwards) and **Land Revenue/Reform Movements** |
| 11:00–13:00 | Analysis: fill in **Part E** of the Question Bank; mark your **wrong-but-Sure** answers |
| 14:30–16:00 | **Rapid Revision (60 facts)** aloud, plus both **Cheat-sheets** |
| 16:00–17:30 | Compare your written analytical answers with the **Answer Frameworks**. Note the missing points |
| Evening | Off ✔️ |

## 4.3 Spaced repetition for Week 1 content
| When | What (about 45 min) |
|---|---|
| **Day 7** (Sun 8 Nov) | Full revision as above |
| **Day 21** (Sun 22 Nov) | Snapshots + Traps + 60 facts; re-attempt the Q&A answers you got wrong |
| **Day 45** (Wed 16 Dec) | Cheat-sheets only, plus 20 random MCQs from the Week 1 bank |
| **Phase 2** (late Jan 2027) | Revision 1 with your short notes |

## 4.4 How to write the analytical answers (the 3-part frame)
1. **Intro (2 lines):** define the term, or give a fact, Article or case that frames the issue.
2. **Body (3–5 sub-headings):** each one has **a point, an example, and an Article/case/data point**. For "critically examine" or "evaluate" questions, give **both sides**.
3. **Conclusion (2 lines):** a balanced view, a way forward, or a link to a constitutional value or current reform.

**Self-check rubric (score each answer /10)**
| Criterion | Marks |
|---|---|
| Answered the directive word (examine / evaluate / compare) | 2 |
| At least 3 distinct dimensions covered | 3 |
| Specific evidence (Article, case, Act, date, data) | 3 |
| Balanced conclusion | 1 |
| Structure (headings, flow) | 1 |

> 💡 These answers are mainly practice for **Mains**. For **Prelims**, their value is that they force you to *understand* and *link* topics, and recent UPSC papers reward exactly that through statement-based questions.

---
*Week 1 study kit: `Week01_Study_Notes_Polity.md` · `Week01_Study_Notes_Modern_History.md` · `Week01_CSAT_and_Quick_Revision.md` · `Week01_Questions_and_Answers.md`*
