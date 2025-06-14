# 🧠 Learning Disability Screening Suite

A collection of four full-stack, gamified applications built with **Next.js**, **Node.js**, and **Machine Learning / GenAI**, designed to screen learning disabilities in children through interactive tests and intelligent analysis.

Each application is independently deployed and tackles a specific learning disorder, offering engaging gameplay and automated evaluation.

---

## 🚀 Projects at a Glance

| Test Type       | Learning Disability | Tech Stack            | Model Type                        |
|------------------|----------------------|-------------------------|------------------------------------|
| 🎮 Game-Based    | ADHD                 | Next.js, Node.js, ML    | Random Forest                      |
| 🧩 Pattern-Based | Dyslexia             | Next.js, Node.js, ML    | Hybrid (SVM + RF + Gradient Boost)|
| ✍️ Drawing-Based | Dysgraphia           | Next.js, Node.js, ML    | CNN, Image Processing                      |
| 🔢 Reasoning-Based| Dyscalculia          | Next.js, Node.js, GenAI | LLM-based Reasoning (Generative AI)|

---

## 🅰️ ADHD Screener

**Live Demo**: https://adhd-hosted-rwmp.vercel.app/
**Code**:https://github.com/Avishkar32/ADHD_Hosted

> **About ADHD**  
> ADHD (Attention Deficit Hyperactivity Disorder) affects attention span, impulse control, and focus.  
> This screener uses fast-paced, reaction-time-based games to identify inattention and impulsivity. Collected metrics are analyzed using a **Random Forest classifier**.

---

## 🧠 Dyslexia Screener

**Live Demo**: https://dsylexia-final.vercel.app/
**Code**: https://github.com/Avishkar32/Dsylexia_final

> **About Dyslexia**  
> Dyslexia impacts reading, spelling, and phonological processing.  
> This tool presents letter confusion and word manipulation challenges. Evaluation is powered by a **hybrid ML model** (SVM + Random Forest + Gradient Boosting).

---

## ✍️ Dysgraphia Screener

**Live Demo**: https://dysgraphia-screening-test-eci3.vercel.app/
**Code**: [Frontend](https://github.com/Avishkar32/Dysgraphia_Screening_Test) • [Backend](https://github.com/Avishkar32/DysgraphiaModel)

> **About Dysgraphia**  
> Dysgraphia impairs fine motor skills, handwriting, and written expression.  
> This test involves freehand drawing and tracing on canvas. User strokes are processed and classified via a **Random Forest model** trained on writing behavior patterns.

---

## 🔢 Dyscalculia Screener

**Live Demo**: https://dyscalculia-screening-game.vercel.app/
**Code**: https://github.com/Avishkar32/Dyscalculia-Screening-Game

> **About Dyscalculia**  
> Dyscalculia affects number sense, arithmetic processing, and spatial reasoning.  
> This screener combines interactive math puzzles with **Generative AI (LLM)** to interpret open-ended math reasoning and detect signs of numerical cognition issues.

---

## ⚙️ Tech Stack

- **Frontend**: Next.js, Tailwind CSS
- **Backend**: Node.js, Express
- **ML/AI**:
  - ADHD: Random Forest
  - Dyslexia: SVM + Random Forest + Gradient Boosting
  - Dysgraphia: Random Forest
  - Dyscalculia: Generative AI (LLMs)
- **Deployment**: Vercel (Frontend) • Railway/Render (Backend)

---

## 📌 Why This Matters

- Most LD tests rely on static questionnaires. This suite brings **interactivity, data, and automation** to early screening.
- Designed to be used by educators, psychologists, and parents for **early detection**.
- Combines **fun gameplay** with serious insights — bridging engagement and utility.

---

## ✍️ Author

**Avishkar Ghodke**  
MERN/Next.js Developer | ML & GenAI Enthusiast  
[LinkedIn](https://www.linkedin.com/in/avishkar-ghodke-5556762b0/) • • [Email](avishkar.ghodke23@vit.edu)

---

> ⭐ Feel free to explore the live demos, review the codebases, and reach out for feedback or collaboration!
