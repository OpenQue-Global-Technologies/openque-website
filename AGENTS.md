# STRICT ACCURACY & CONTEXT GROUNDING DIRECTIVES

1. ZERO GUESSWORK / NO SPECULATION:
   - Always verify the actual active page/route and exact file lines before answering questions or making edits.
   - If multiple routes/pages share similar tags or component names, inspect the exact route template (e.g. route hash or component structure) currently in view.

2. PRECISE ELEMENT TARGETING:
   - When inspecting CSS selectors or elements, cross-reference the active view template and exact text content (e.g. "Hospital staff Journey") rather than relying blindly on generic nth-child or nth-of-type indexes across multi-route single-page apps.

3. FACTUAL VERIFICATION:
   - Before answering any question about visual styles, colors, layouts, or text values, view the actual source code lines and state the exact computed/inline values found in the code.
   - Do not claim an element has a specific property unless you have verified the exact line of code containing that element and confirmed its active state.

4. ROUTE AWARENESS:
   - Clearly state which page/route template you are modifying or inspecting (e.g., Home vs. How It Works / Product vs. Pricing).
