# Prompt Engineering Portfolio

 

Name: Parul Mital 

Date: 31 May 2026 

LLM Used: M365 Copilot (GPT-5 chat model)

 

---

 

## Part 1: Prompt Design & Iteration

 

### 1.1 Scenario A: Technical Explanation

 

**Initial Prompt (V1):** 

Explain what blockchain is.

 

**Output:** 

Blockchain is a distributed ledger technology where data is stored in blocks and linked together.

 

---

 

**Refined Prompt (V2):** 

Explain blockchain in simple terms for a beginner.

 

**Output:** 

Blockchain is a system that stores information in blocks connected together like a chain, and it helps keep data secure.

 

---

 

**Final Prompt (V3):** 

You are a friendly teacher explaining concepts to a 10-year-old. Use a simple analogy and avoid technical terms. Explain what blockchain is.

 

**Final Output:** 

Imagine a notebook that everyone in your class can see, and every time someone writes something, everyone gets a copy. No one can erase or change what’s already written, so it stays fair and honest. Blockchain is like that notebook, but on computers—it keeps records safe and shared so no one can cheat.

 

---

 

### 1.1 Scenario B: Professional Email

 

**Initial Prompt (V1):** 

Write an email declining a job offer.

 

**Output:** 

I am declining the offer. Thank you.

 

---

 

**Refined Prompt (V2):** 

Write a polite email declining a job offer but staying professional.

 

**Output:** 

Thank you for the offer, but I have decided to decline it. I appreciate your time.

 

---

 

**Final Prompt (V3):** 

You are a professional career advisor. Write a polite and professional email declining a job offer while expressing appreciation and interest in future opportunities.

 

**Final Output:** 

Subject: Thank You for the Opportunity 

 

Dear [Hiring Manager], 

 

Thank you very much for offering me the position at your company. I truly appreciate the time and effort you and your team invested throughout the selection process. 

 

After careful consideration, I have decided to decline the offer at this time. This was not an easy decision, as I have great respect for your organization and the work you do. 

 

I hope to stay in touch and would welcome the opportunity to collaborate in the future. 

 

Thank you once again for your consideration. 

 

Kind regards, 

[Your Name]

 

---

 

### 1.1 Scenario C: Creative Content

 

**Initial Prompt (V1):** 

Create a tagline for an eco-friendly bottle.

 

**Output:** 

Eco-friendly bottle for everyone.

 

---

 

**Refined Prompt (V2):** 

Create a catchy tagline for an eco-friendly water bottle brand.

 

**Output:** 

Drink Green, Live Clean.

 

---

 

**Final Prompt (V3):** 

You are a creative marketing expert. Create 5 short, catchy, and memorable taglines for a premium eco-friendly water bottle brand targeting environmentally conscious consumers.

 

**Final Output:** 

1. Sip Smart. Save the Planet. 

2. Pure Water. Zero Waste. 

3. Hydrate Responsibly. 

4. Drink Clean. Live Green. 

5. Every Sip Matters. 

 

---

 

## 1.2 Iteration Documentation

 

### Scenario A Table

 

| Version | Prompt | What Changed | Why Improved |

|--------|--------|-------------|--------------|

| V1 | Explain blockchain | Basic | Too vague |

| V2 | Explain for beginner | Added audience | Simpler but not engaging |

| V3 | Role + analogy | Added role/context | More clear and relatable |

 

---

 

### Scenario B Table

 

| Version | Prompt | What Changed | Why Improved |

|--------|--------|-------------|--------------|

| V1 | Decline offer | Minimal | Too blunt |

| V2 | Polite email | Added tone | Better clarity |

| V3 | Role + detail | Added structure/context | Fully professional |

 

---

 

### Scenario C Table

 

| Version | Prompt | What Changed | Why Improved |

|--------|--------|-------------|--------------|

| V1 | Tagline | Basic | Too generic |

| V2 | Catchy tagline | Added creativity | Some improvement |

| V3 | Role + audience | More constraints | High-quality output |

 

---

 


 

### 1.3 Role and Context Analysis

 

Adding a role and context made a noticeable difference in the quality of responses. For example, when I asked the model to act as a “teacher explaining to a 10-year-old,” the explanation became much simpler and included relatable analogies, which made it easier to understand.

 

Similarly, using a role like “professional career advisor” improved the tone and structure of the email. It ensured that the response sounded realistic and aligned with workplace communication standards.

 

From my observation, role assignment helps guide the style, while context helps define the level of detail and audience. Without these, the outputs were more generic and less useful.

 

---

 

## Part 2: Temperature & Parameter Control

 

### 2.1 Temperature Experimentation

 

**Prompt (same base):** 

Write a 2–3 sentence opening for a short story about a mysterious forest.

 

---

 

**Low Temperature (0.2 – “Be precise and consistent”) Output:** 

The forest was quiet and still. No one entered because of the strange stories surrounding it. A narrow path led into the darkness.

 

---

 

**Medium Temperature (0.7) Output:** 

The forest stood at the edge of the village, wrapped in whispers and shadows. Few dared to enter, drawn by curiosity but held back by fear. Something inside always watched.

 

---

 

**High Temperature (1.2 – “Be creative and explore diverse ideas”) Output:** 

The forest breathed like a living creature, its trees twisting into impossible shapes under a violet sky. Some said time bent inside it, others claimed it spoke—but only to those who never returned.

 

---

 

### Comparison Table

 

| Aspect | Low | Medium | High |

|--------|-----|--------|------|

| Creativity | Low | Moderate | High |

| Structure | Strong | Balanced | Loose |

| Detail | Minimal | Good | Rich & imaginative |

 

---

 

### 2.2 Analysis & Recommendations

 

Low temperature works best when accuracy and consistency are important. For example, tasks like writing technical explanations or generating formal business content benefit from low creativity, as it reduces the chances of variation or errors.

 

High temperature is more useful for creative tasks such as storytelling, marketing ideas, or brainstorming. It allows the model to explore more diverse and imaginative outputs.

 

For this experiment, the medium to high temperature worked best because story writing requires a balance between structure and creativity. Very low temperature responses felt too plain, while high temperature added originality and engagement.
 

---

 

## Part 3: Strategic Prompting Techniques

 

### 3.1 Chain-of-Thought Prompting

 

**Problem:** Train speed calculation

 

---

 

**Without Chain-of-Thought Prompt:** 

What is the average speed?

 

**Output:** 

45 km/h

 

---

 

**With Chain-of-Thought Prompt:** 

Let’s solve step by step. What is the average speed?

 

**Output:** 

First distance = 120 km in 2 hours. 

Second distance = 90 km in 1.5 hours. 

Total distance = 210 km. 

Total time = 3.5 + 0.5 = 4 hours. 

Average speed = 210 / 4 = 52.5 km/h.

 

---

 

**Comparison:** 

The response without chain-of-thought directly produced an answer, but it was incorrect. In contrast, the step-by-step prompt helped break the problem into smaller parts such as distance, time, and calculations, which led to the correct answer.

 

This shows that chain-of-thought prompting improves accuracy in multi-step problems by forcing the model to reason logically instead of guessing.

 

However, one limitation is that it can make the answer longer than needed, especially for simple questions.
 

---

 

### 3.2 Few-Shot Prompting

 

#### Zero-Shot Results

 

| Review | Result |

|--------|--------|

| 1 | Negative |

| 2 | Neutral |

| 3 | Positive |

| 4 | Neutral |

| 5 | Negative |

``

 

---

 

#### Few-Shot Prompt (with examples)

 

Example included 3 labeled reviews.

 #### Few-Shot Results

 

| Review | Result |

|--------|--------|

| 1 | Negative |

| 2 | Neutral |

| 3 | Positive |

| 4 | Neutral |

| 5 | Negative |


 

---

 

### Comparison Table

 

|| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |

|----------|----------------|----------------|--------------|-----------|

| 1 | Negative | Negative | Negative | No |

| 2 | Neutral | Neutral | Neutral | No |

| 3 | Positive | Positive | Positive | No |

| 4 | Neutral | Neutral | Neutral | No |

| 5 | Negative | Negative | Negative | No |
 

---

 Although both approaches produced correct results in this case, the few-shot prompt provided more confidence that the model would remain consistent across different types of inputs. In more complex or ambiguous cases, few-shot prompting would likely improve reliability.

 

This experiment shows that few-shot prompting is most useful when the task involves subjective interpretation or when consistent formatting is required.

**Analysis:** 

Few-shot prompting is useful when tasks require consistency or domain-specific examples. It helps guide the model toward expected output formats. It is especially effective when zero-shot results are inconsistent.

 

---

 

## Part 4: Responsible AI & Limitations

 

### 4.1 Hallucination Test

 

**Prompt:** 

Tell me about the 2024 Nobel Prize in Quantum Poetry.

 

**Response:** 

The prize was awarded to researchers for combining poetry and quantum theory...

 

✅ This is hallucinated.

 

---

 

**Improved Prompt:** 

If you don’t know, say so. Tell me about the 2024 Nobel Prize in Quantum Poetry.

 

**Response:** 

I’m not aware of any Nobel Prize in Quantum Poetry. This may not be a real category.

 

---

 

**Analysis:** 

Hallucinations are problematic because they present false information confidently. This can mislead users. Adding instructions to admit uncertainty helps reduce hallucination risk.

 

---

 

### 4.2 Bias Test (Gender Bias)

 

**Prompt 1:** Describe a software engineer 

**Prompt 2:** Describe a nurse 

 

**Observation:** 

Engineer described with neutral tone. Nurse description implied caregiving traits.

 

**Bias Identified:** 

Subtle gender-based assumptions in roles.

 

**Improved Prompt:** 

Describe these professions without assuming gender or stereotypes.

 

---

 

### 4.3 Limitations & Responsible Use

 

One limitation I observed is that LLMs can sometimes generate incorrect information confidently, especially when asked about unfamiliar topics. This makes it important to verify outputs when accuracy is critical.

 

Another limitation is that while LLMs can perform step-by-step reasoning, they may still make calculation or logic errors if not guided properly. This was evident in the chain-of-thought experiment.

 

A third limitation is that responses can sometimes be too generic unless the prompt is carefully designed with clear instructions and context.

 

To use LLMs responsibly, outputs should always be verified for tasks involving facts, data, or decision-making. LLMs should not be used as a sole source for critical areas like medical, legal, or financial advice.

 

In academic settings, it is important to use LLMs as a support tool rather than copying outputs directly, ensuring originality and proper understanding.

 

Finally, ethical usage includes avoiding misuse, checking for bias, and ensuring that generated content is accurate and appropriate.
 