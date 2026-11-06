---
name: hindi_grammar_correction
description: Systematically analyzes and corrects grammatical, syntactic, and spelling errors in Hindi language text.
---

# Metadata
- **Topic:** Creating SKILL for LLM (Hindi Grammar Correction)
- **Author:** Kumari Tripti Lata
- **Semester:** Monsoon Semester 2026
- **Affiliation:** Department of Humanities and Social Science

---

# Skill Description & Purpose
This skill provides a structured methodology for Large Language Models (LLMs) to identify, categorize, and correct grammatical errors in Hindi texts. It covers subject-verb agreement, gender alignment, postposition usage (karak), and spelling accuracy.

---

# Step-by-Step Execution Workflow

1. **Input Parsing & Verification**
   - Read the input Hindi sentence.
   - Verify script validity (ensure Devnagari script).

2. **Syntactic & Grammatical Analysis**
   - Check **Gender-Number-Person (GNP)** agreement between subject, object, and verb.
   - Verify postpositions (*ne*, *ko*, *se*, *par*, *ka*, *ke*, *ki*).
   - Identify spelling or structural errors.

3. **Correction & Output Generation**
   - Provide the corrected version of the text.
   - Detail the changes made with explanations.

---

# Few-Shot Examples

### Example 1
- **Input:** *वह कल बाजार गया थी।*
- **Error:** Gender mismatch (*गया* is masculine, *थी* is feminine).
- **Corrected:** *वह कल बाजार गई थी।* (Feminine) OR *वह कल बाजार गया था।* (Masculine)

### Example 2
- **Input:** *राम ने खाना खाया।*
- **Status:** Correct (Ergative marker *ne* with transitive past tense verb).
