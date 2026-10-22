# 🕉️ Chandas Anveshana — Sanskrit Meter Detector

🥈 **2nd Prize Winner | Department-Level Hackathon**  
🏆 My First Hackathon Project

## 📌 Project Overview

Chandas Anveshana is a Sanskrit poetic meter detection project based on Chandashastra, the traditional system of Sanskrit prosody formalized by Pingala.

The project analyzes a Sanskrit verse or transliterated text, identifies its syllables, generates the Laghu–Guru pattern, and matches the pattern against supported Chandas meters.

The project was developed as part of my first department-level hackathon, where our team won **2nd prize**.

## ❗ Problem Statement

Identifying the Chandas (poetic meter) of a Sanskrit verse manually can be difficult. It requires splitting the verse into syllables, distinguishing Laghu (short) and Guru (long) syllables, and checking the resulting metrical pattern against the rules of Chandashastra.

The challenge was to build a program that automates this analysis and identifies a supported meter.

## 💡 Solution

Chandas Anveshana provides a programmatic approach to Sanskrit meter identification.

The program accepts a poetic verse, analyzes its syllables, determines the Laghu–Guru pattern, and compares the pattern with predefined rules for supported Chandas meters. If no supported meter matches, the program returns `Unknown`.

## ✨ Features

- 📝 Accepts Sanskrit verses or transliterated text.
- 🔤 Splits the verse into syllables.
- ⚖️ Identifies Laghu (L) and Guru (G) syllables.
- 🔍 Generates the metrical pattern.
- 📚 Checks the pattern against predefined Chandas rules.
- 🕉️ Supports Anushtubh, Indravajra, and Upendravajra.
- 🧹 Ignores punctuation and handles extra spaces.
- ✅ Returns the detected meter or `Unknown` when no supported match is found.

## 🛠️ Tech Stack

Add the actual programming language, libraries, and tools used in your implementation here.

- **Programming Language:** To be specified
- **Libraries and Tools:** To be specified

## ⚙️ How It Works

1. **Input:** Provide a Sanskrit verse or transliterated text containing 1–4 lines.
2. **Syllable Detection:** Split the verse into syllables.
3. **Laghu–Guru Analysis:** Classify syllables as short (L) or long (G).
4. **Pattern Generation:** Construct the metrical pattern.
5. **Rule Matching:** Compare the pattern against the supported Chandas rules.
6. **Output:** Display the detected Chandas name, optionally with the Laghu–Guru pattern.

## 📖 Supported Chandas

### 1. Anushtubh
A widely used Sanskrit meter, commonly associated with the shloka form. Identification follows the syllable-position rules specified in the problem statement.

### 2. Indravajra
A meter with eleven syllables per pāda and a defined pattern of long and short syllables.

### 3. Upendravajra
A meter similar to Indravajra, distinguished by a short first syllable according to the given rules.

## 🏆 Hackathon Achievement

**🥈 Secured 2nd Prize at a Department-Level Hackathon**

This was my first hackathon experience. It gave me an opportunity to work on a defined technical problem, develop a solution under time constraints, and present our work.

Winning second prize made this experience an important milestone in my technical learning journey.

## 📚 What I Learned

- Breaking down a problem statement into implementation steps.
- Applying rule-based logic to a language-related problem.
- Working toward a solution within a hackathon deadline.
- Collaborating and presenting a technical project.

## 🚀 Future Improvements

- Improve syllable segmentation and Laghu–Guru classification.
- Expand support for additional Sanskrit meters.
- Add a user-friendly interface for entering verses and viewing results.
- Include detailed explanations of how each meter is identified.

---

**Built with curiosity for Sanskrit literature, algorithms, and problem-solving.**
