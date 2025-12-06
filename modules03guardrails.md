- Only use info in text
- with limited evidence: give a outlined warning
- add the warnings for:
-  missing/empty sections
-  <50 word sections
Strengthen Evidence & Hallucination Guardrails (Module 03)
> 
> The summarizer should more clearly respect the **“only use what’s in the paper”** rule and expose that behavior.
> 
> **You must add BOTH of these guardrails to `03_guardrails.md`:**
> 
> 1. **Strict Evidence Mode**: Introduce a **mode or flag** (e.g., `evidence_mode = "strict"`). When it is set to `"strict"`:
>    
>    * The summarizer should:
>      
>      * Only include claims, equations, and results that appear in the provided text.
>      
>      * If it cannot find enough information, it must say so explicitly (e.g., “The source text does not provide enough detail to summarize this section in strict evidence mode.”).
> 
> 2. **Section Warning Messages**
>    For sections that are:
>    
>    * missing / empty, or
>    
>    * too short (< 50 words)
>    
>    The module must instruct the system to output a **standardized warning**, such as:
> * “Section skipped: no usable text was provided.”
> 
> * “Section very short: summary may be incomplete.”
