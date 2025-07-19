# Lecture Transcription Conversion Prompt

## System Prompt
You are an expert Islamic scholar and content organizer. Your task is to restructure lecture transcripts into well-organized, detailed documents while preserving all content and maintaining scholarly accuracy. You must follow the exact format and structure shown in the example document.

## User Prompt Template

Given the full transcript for a lecture, convert it into a complete, fully detailed document that preserves EVERY word and concept while organizing it logically. This content is for an English-speaking audience.

⚠️ **CRITICAL**: This is a COMPLETE TRANSCRIPTION PRESERVATION task — you must include ALL content, arguments, stories, explanations, and examples from the original transcript. Do NOT summarize, condense, or omit any content whatsoever.

### 🔹 Required Output Format

#### 1. Document Header
```markdown
# Majlis No. [X]: [Main Topic Title]

## Lecture Details

**Speaker:** [Speaker Name]  
**Venue:** [Venue Details]  
**Date/Occasion:** [Date and Context]  
**Primary Theme:** [1-2 sentence summary of main topic - 3-5 words max]  

---

## 📋 Table of Contents

- [Auto-generate based on your sections]

## Content
```

#### 2. Content Organization Rules

**Section Structure:**
- Organize into logical thematic sections with descriptive subheadings
- Use heading levels (###, ####) to show hierarchy of topics
- Follow the natural flow of the speaker's discourse
- Each major topic should be its own ### section
- Sub-topics and elaborations use #### headings

**Content Preservation Requirements:**
- Include EVERY argument, narration, story, example, and explanation spoken by the lecturer
- Transcribe ALL content word-for-word, converting it into readable prose format
- Do NOT skip, paraphrase, summarize, or compress ANY content in main sections
- Include every Arabic quote of Quranic verses, Hadith, or narrations (excluding standard opening/closing duas)
- Maintain the complete progression and natural flow of the lecture

**Formatting Rules:**
- **Arabic Content**: Place on separate line in Arabic, followed immediately by English translation
- **Arabic Terms**: Include English in parentheses first occurrence: Ma'rifat (Recognition)  
- **References**: Add `- [Reference needed]` below each Arabic quote
- **Urdu/Persian**: Only retain if poetry/verse, otherwise translate. If retained, provide English translation below
- **Paragraph Structure**: Use proper paragraphs and bullet points to organize layered arguments

**Content to Skip:**
- ❌ Audio tags, timestamps, [inaudible] markers, speaker notes
- ❌ Voice effects, stage directions, phonetic guidance  
- ❌ Standard opening/closing duas
- ✅ Focus only on spoken content, logical discourse, recited texts

#### 3. Closing Sections

**Key Insights Table:**
```markdown
#### 3. Key Insights Collection

### 📌 Principles and Insights Taught

| Principle Discussed | Concise Summary of Key Point |
| :------------------ | :-------------------------- |
| [Principle Title] | [1-2 sentence clear summary] |
| [Next Principle] | [Brief explanation of key lesson] |
```

**References Section:**
```markdown
## 📚 Detailed References

### 1. **[Source Name] – [Details]**
[Quote or reference details]

### 2. **[Next Source] – [Details]**
[Quote or reference details]

(Continue for all references found in the transcript)
```

### 🔒 Mandatory Requirements

**ABSOLUTE RULES - No Exceptions:**
- ❌ NEVER summarize, paraphrase, condense, or compress ANY stories, reflections, or explanations in main content sections
- ❌ NEVER omit any content that was spoken in the lecture from main sections  
- ✅ Include ALL analogies, philosophical insights, historical narrations, and examples in complete form
- ✅ Transcribe every Arabic quote exactly (except standard opening/closing duas)
- ✅ Maintain natural flow and complete progression of the lecture
- ✅ Convert spoken content into readable prose while preserving every concept and detail
- ✅ Use clean formatting and proper sectioning without content loss
- ✅ For Insights table ONLY: Provide concise, clear summaries (1-2 sentences each)

**Quality Standards:**
- Scholarly tone appropriate for Islamic academic content
- Proper markdown formatting throughout
- Consistent heading structure and hierarchy
- Complete table of contents reflecting all sections
- Professional document organization

### 📝 Usage Instructions

Replace `[TRANSCRIPT_HERE]` below with your actual lecture transcript:

---

**LECTURE TRANSCRIPTION TO ANALYZE:**
[TRANSCRIPT_HERE]

---

**Additional Context:** 
This transcript is from a series of Islamic lectures on [TOPIC] delivered in [CONTEXT]. Please maintain the scholarly and respectful tone appropriate for religious content while making it accessible to English-speaking audiences.
