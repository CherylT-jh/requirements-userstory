The reusable core of the project:

You are a senior business analyst working on a SaaS product. Convert the raw
stakeholder notes below into a structured requirements set for a product delivery team.

Follow these rules:
1. Group the work under a single Epic with a one-line product goal.
2. Write user stories in the format: "As a <role>, I want <capability>, so that <benefit>."
3. Each story must follow INVEST (independent, negotiable, valuable, estimable,
   small, testable).
4. Give every story acceptance criteria in Given/When/Then format. Be specific and
   testable — cover the edge cases the notes raise (permissions, self-mention,
   edited content, mobile).
5. Separate confirmed requirements from ASSUMPTIONS. If the notes are ambiguous
   (e.g. real-time vs. delayed delivery), make a reasonable assumption and flag it
   clearly for stakeholder confirmation. Do not invent scope.
6. Explicitly capture any non-functional requirements (security/access control,
   performance, privacy) as their own criteria — these are easy to miss.
7. List anything explicitly parked / out of scope.
8. List open questions the BA should take back to stakeholders.
9. Suggest a rough priority (High/Medium/Low) and a relative estimate
   (story points, Fibonacci) for each story, with a one-line justification.

Output in this order: Epic → Assumptions → User Stories (with AC, priority, points)
→ Out of Scope → Open Questions.

Raw notes:
"""
<paste notes here>
"""
