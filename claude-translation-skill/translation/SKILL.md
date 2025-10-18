---
name: translation
description: Professional cross-language translation using the "Faithfulness-Fluency-Elegance" framework. Use this skill when users request high-quality translation between any language pairs (literary works, academic papers, business documents, technical manuals, creative content, etc.) that requires cultural context, terminology explanation, and stylistic preservation beyond simple word-for-word conversion.
---

# Cross-Language Translation Expert

## Translation Framework: Faithfulness-Fluency-Elegance (信达雅)

Apply these three principles in balance for all translation tasks:

1. **Faithfulness (信)**: Accurately convey the original meaning, logic, tone, and author's intent
2. **Fluency (达)**: Use natural target language expressions that readers understand effortlessly
3. **Elegance (雅)**: Preserve the style, rhetoric, and aesthetic value of the source text

## Standard Output Structure

Provide translations in three layers:

### Layer 1: Core Translation

The main translation text in natural, fluent target language.

**Requirements:**
- Prioritize target language naturalness over literal translation
- Mark necessary contextual additions with [square brackets]
- Preserve the tone, register, and style of the original
- Never add information not present in the source text

**Conflict resolution:**
When literal meaning conflicts with idiomatic expression:
- Use the natural target language expression in the main translation
- Explain the literal meaning in Layer 2 (Key Terms)

### Layer 2: Key Terms Explanation

Select 2-4 critical terms that require clarification:

**For each term, include:**
- Original meaning and context
- Cultural connotations or specialized usage
- Why this translation approach was chosen
- Alternative translations considered (if relevant)

**Term selection criteria:**
- Culture-loaded words (idioms, allusions, culture-specific concepts)
- Technical terminology or jargon
- Words with significant ambiguity
- Puns, wordplay, or rhetorical devices that required adaptation

### Layer 3: Background Context

Provide cultural, historical, or linguistic context to deepen understanding:

**Include:**
- Cultural background or historical context
- Cross-cultural communication considerations
- How source and target languages differ in expression patterns
- Author's intent or implied meanings
- Overall translation strategy and major decisions

**Style:** Use accessible language; avoid excessive academic jargon.

## Text-Type Specific Strategies

### Literary Translation
- Priority: Elegance ≥ Fluency > Faithfulness
- Preserve imagery, rhythm, rhetorical devices
- Allow creative adaptation for stylistic equivalence

### Academic Translation
- Priority: Faithfulness > Fluency > Elegance
- Use standardized terminology
- Maintain precise logic and argumentation structure

### Business/Legal Translation
- Priority: Faithfulness ≥ Fluency > Elegance
- Eliminate ambiguity
- Use industry-standard expressions

### Technical Documentation
- Priority: Faithfulness = Fluency > Elegance
- Prioritize clarity and operational accuracy
- Maintain consistency in technical terms

### Marketing Copy
- Priority: Fluency = Elegance > Faithfulness
- Allow significant localization (transcreation)
- Focus on functional equivalence and emotional impact

## Translation Decision Tree

When encountering difficult expressions:

```
1. Understand the source
   ├─ Verify meaning, grammar, context
   └─ Identify cultural content

2. Evaluate options
   ├─ Literal translation
   ├─ Free translation
   ├─ Transliteration
   ├─ Transliteration + explanation
   └─ Transcreation

3. Balance the three principles
   ├─ Is this a key information point? (Faithfulness)
   ├─ Will target readers understand? (Fluency)
   └─ Does it preserve the original spirit? (Elegance)

4. Choose strategy
   ├─ Culture-loaded words → Free translation + Key Terms explanation
   ├─ Proper nouns → Transliteration + Key Terms explanation
   ├─ Idioms → Find target language equivalent
   ├─ Puns/wordplay → Transcreate or annotate
   └─ When compromise needed → Prioritize Faithfulness + Fluency, explain Elegance loss in Background
```

## Common Pitfalls to Avoid

**Over-literal translation** ("translation-ese"):
- Problem: Unnatural target language
- Solution: Prioritize target language conventions; explain source structure in Key Terms

**Over-free translation** (distortion):
- Problem: Adding non-existent information
- Solution: Use [brackets] for necessary additions; mark speculation clearly

**Culture-loaded words mishandling**:
- Problem: Direct transliteration leaves readers confused
- Solution: Combine free translation + explanation, or transliteration + gloss

**Ignoring register/style**:
- Problem: Formal text becomes casual, or vice versa
- Solution: Match target language's equivalent register

**Missing implicit information**:
- Problem: Only translating surface meaning
- Solution: Explain implicature in Background Context

## Quality Checklist

Before finalizing:

**Core Translation:**
- [ ] Faithfully conveys source meaning?
- [ ] Natural in target language?
- [ ] Tone and style consistent with source?
- [ ] Necessary additions marked with [brackets]?

**Key Terms:**
- [ ] Selected 2-4 most important terms?
- [ ] Explained translation rationale?
- [ ] Provided cultural/etymological context where relevant?

**Background Context:**
- [ ] Explained relevant cultural background?
- [ ] Addressed cross-cultural differences?
- [ ] Clarified overall translation strategy?

## Example Usage Pattern

**User request:**
"Translate this English passage to Chinese: 'It was the best of times, it was the worst of times.'"

**Output structure:**
```
【核心译文】
[Natural Chinese translation]

【重点词解】
[2-4 key terms with explanation]

【背景解读】
[Cultural context, Dickens' style, translation approach]
```

## Handling Special Cases

**Poetry translation:**
- Prioritize imagery and emotion over literal meaning
- Note: Perfect formal equivalence often impossible; explain trade-offs in Background

**Dialect/accent:**
- Use target language dialect or colloquial markers when appropriate
- Explain source dialect characteristics in Background

**Long documents:**
- Maintain terminology consistency throughout
- Consider creating a glossary for recurring terms

**Untranslatable concepts:**
- Use transliteration + immediate explanation [in brackets]
- Provide detailed explanation in Key Terms
