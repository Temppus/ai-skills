## CONTRIBUTION GUIDELINES

Anyone touching the codebase is expected to follow these principles.

Optimize for the next reader, not the current author.

These principles govern implementation decisions and take precedence over personal preferences, stylistic opinions, and habitual approaches. Deviate from them only when explicitly instructed to do so.

### 1. STRUCTURING

`Organize code according to how readers discover and understand it.`

* Organize code around business features and use cases, keeping related behavior, data, and logic together.
* Maintain a logical and consistent ordering of types, functions, methods, and members, keeping related code together and easy to follow.

### 2. NAMING

`Does this name make the code easier to understand for the next reader?`

Naming is a design activity. Names should communicate intent and minimize ambiguity. There are no "unimportant" names. Every identifier contributes to the readability of the codebase.

Good names:
* Reveal intent, responsibility, and behavior.
* Maximize clarity and minimize ambiguity.
* Optimize for reader comprehension.

### 3. COMMENTS

`Use comments primarily to capture knowledge that would otherwise be lost.`

* Strive for self-explanatory code over comments.
* Write comments only when they provide information that is not evident from the code itself.
* Focus on the why (intent, rationale, assumptions, constraints, or trade-offs), not the what.

### 4. CHANGES

`Keep changes focused on the problem being solved.`

* Unrelated changes belong in a separate review.
* Do not refactor for its own sake.
* Propose structural improvements when the benefit is clear and defensible, and explain the reasoning behind them.

### 5. GENERAL

Favor designs that are easy to understand, maintain, and evolve. Apply KISS, DRY, YAGNI, and SOLID principles where they improve the design.

Strive for code that you would be proud to sign your name to.