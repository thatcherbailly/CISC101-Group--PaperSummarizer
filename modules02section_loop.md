Add summarry: 
- Short: 1-2 sentences
- detailed: paragraph 3-5 bullet points 
- 250 word max per section 

module 2 must include:

- summary variables
- logic for short detailed sumamries

Add “Summary Level” Modes (Module 02)
   >  The summarizer should support two summary levels for each section:
   > 
   > * `summary_level = "short"`
   >   
   >   * 1–2 sentence summary per section
   > 
   > * `summary_level = "detailed"`
   >   
   >   * A short paragraph **plus** a bullet list of 3–5 key points for each section
   > 
   > **You must:**
   > 
   > * Add a **variable** (e.g., `summary_level`) to the module’s logic.
>    * keep the summary to 250 words max 
   > 
   > * Add **conditional behavior** in the section loop:
   >   
   >   * If `summary_level = "short"` → generate only a compact summary.
   >   
   >   * If `summary_level = "detailed"` → generate summary + bullet list.
