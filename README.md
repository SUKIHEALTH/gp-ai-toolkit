# gp-ai-toolkit
AI tools for GPs: summarize notes, detect specialist, generate referral letters

This toolkit is built for General Practitioners (GPs) who want to work smarter, not harder.

Using the OpenAI API, this Jupyter-based tool allows you to:

✅ Read and process multiple patient notes  
✅ Summarize each consultation automatically  
✅ Detect the most appropriate medical specialist  
✅ Generate referral letters with your practice name  
✅ Save each referral as a `.txt` file for documentation

---

## 💡 Example Use Case

You copy/paste 5 notes into a text file like this:

45F, fatigue and weight gain. Reports cold intolerance and constipation. No palpitations. Family history of thyroid disease.

---

56M, chest pain on exertion for 3 weeks. No SOB or nausea. Hypertension, diabetes. Family history of CAD.

---

22F, recurrent UTIs. Sexually active. No fever or flank pain. Normal renal function. History of E. coli positive urine cultures.

---

60M, progressive shortness of breath. Former smoker. Bilateral wheezing on auscultation. Awaiting spirometry. History of COPD.

---

32F, persistent headaches. Worse with stress. Normal neuro exam. No aura. Family history of migraines. Normal MRI last year.

Then run the notebook — and instantly receive:
- A clinical summary
- The right specialist (e.g., cardiologist)
- A complete referral letter saved to file

---

## 🧪 Built With

- Python 3
- Jupyter Notebook
- OpenAI API
- `dotenv` for API key management

---

## ⚙️ How to Use

1. Clone or download this repo  
2. Add your OpenAI API key to a `.env` file:

3. Add your patient notes to `all_notes.txt` (use `---` to separate notes)  
4. Run the notebook `gp_referral_bot.ipynb`  
5. Referral letters are auto-generated and saved to text files.

---

## 👨‍🏫 For Tutors or Reviewers

To view the notebook and test output:

1. Clone the repo or use GitHub Codespaces  
2. Open `gp_referral_bot.ipynb` in Jupyter  
3. Run each cell (you’ll need an OpenAI API key)

---

## 🔒 Ethical Note

This tool is for educational and prototyping use only. Do not use real patient identifiers or data without proper ethical approval.

---
