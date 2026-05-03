# my-plp-assignment

## **Savannah Tracker Report: Precision Prompting for Maternal Health AI**

### **Introduction (≈50 words)**

Precision in maternal health AI is not a luxury—it directly affects outcomes. In rural East Africa, generic advice can be irrelevant or harmful due to differences in diet, access to care, and cultural practices. Tailored prompts ensure guidance is actionable, trusted, and aligned with real-life constraints.

---

## **Prompt A: Nutrition Advice (Rewritten)**

### **AIM Framework**

* **A (Audience):** Pregnant women in rural Kenya and Uganda with limited income, relying on local staples like ugali, matooke, beans, and sukuma wiki
* **I (Intent):** Provide practical, affordable, culturally relevant nutrition advice during pregnancy
* **M (Medium):** SMS (160 characters per message, simple language, no medical jargon)

### **MAP Framework**

* **M (Mode):** Step-by-step tips using familiar foods
* **A (Anchoring):** Reference local staples (e.g., matooke provides a large share of calories; beans for protein; greens for iron)
* **P (Personalization):** Adjust suggestions based on trimester and food availability

### **Rewritten Prompt**

“Generate 3 short SMS messages giving nutrition tips for a pregnant woman in rural Kenya or Uganda. Use local foods like ugali, matooke, beans, sukuma wiki, eggs, and milk. Ensure advice is affordable, culturally appropriate, and trimester-specific. Avoid expensive or imported foods. Keep each SMS under 160 characters and use simple, supportive language.”

### **Key Improvement**

This version reduces irrelevance by grounding advice in locally available foods and economic realities, improving adherence and trust while lowering hallucination risk about inaccessible diets.

---

## **Prompt B: Appointment Reminders (Rewritten)**

### **AIM Framework**

* **A (Audience):** Pregnant women living >5 km from clinics, often relying on walking, boda boda, or community health workers
* **I (Intent):** Remind and enable attendance at antenatal visits
* **M (Medium):** SMS with actionable logistics

### **MAP Framework**

* **M (Mode):** Reminder + planning guidance
* **A (Anchoring):** Include travel time, clinic days, and CHW support
* **P (Personalization):** Adapt based on distance, prior attendance, and known clinic schedules

### **Rewritten Prompt**

“Create an SMS reminder for a pregnant woman in rural East Africa about her upcoming antenatal visit. Include: estimated travel time (walking or boda), checking clinic open days, and option to contact a community health worker. Keep under 160 characters, supportive tone, and include a suggestion to prepare transport money (e.g., M-Pesa or cash).”

### **Key Improvement**

The prompt shifts from passive reminders to actionable planning, increasing attendance by addressing real barriers like transport, clinic schedules, and mobile money constraints.

---

## **Prompt C: Emergency Triage (Rewritten with Chain-of-Thought + Verifier Pattern)**

### **AIM Framework**

* **A (Audience):** Pregnant women in rural areas with limited immediate access to hospitals
* **I (Intent):** Provide safe, calm, and clear triage guidance for symptoms
* **M (Medium):** SMS or short message sequences

### **MAP Framework**

* **M (Mode):** Guided decision support (symptom → action)
* **A (Anchoring):** Focus on common danger signs (bleeding, severe headache, swelling, no fetal movement)
* **P (Personalization):** Adjust advice based on severity and access to care

### **Rewritten Prompt (with reasoning structure embedded)**

“Guide a pregnant woman in rural East Africa who feels unwell. Step 1: Ask 1–2 simple questions to identify danger signs (e.g., bleeding, severe pain, no baby movement). Step 2: Based on answers, give clear next steps (rest, contact CHW, or go to nearest clinic). Step 3: Reassure calmly without causing panic. Step 4 (Verifier): Double-check that advice prioritizes safety, avoids diagnosis, and directs urgent cases to immediate care. Keep messages short, clear, and culturally appropriate.”

### **Key Improvement**

By structuring reasoning and adding a verification step, this reduces unsafe or overly confident advice while ensuring critical symptoms trigger urgent care guidance without alarming the user unnecessarily.

---

## **Reflection (≈100 words)**

This exercise highlights that AI in healthcare is only as effective as its contextual understanding. Precision prompting transforms AI from a generic information tool into a localized support system that respects culture, infrastructure, and economic realities. It shifts the role of AI from “advisor” to “adaptive assistant.” In low-resource settings, this distinction matters: poorly contextualized outputs can erode trust or cause harm, while well-designed prompts can extend the reach of healthcare systems. Going forward, I see prompt design as a form of health systems engineering—where language, context, and constraints must be treated as critical inputs, not afterthoughts.
