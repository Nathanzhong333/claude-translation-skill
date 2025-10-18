# Usage Guide

Learn how to get the most out of the Claude Translation Skill.

## Basic Usage

### Simple Translation

```
Translate this English text to Chinese:
"The quick brown fox jumps over the lazy dog."
```

or

```
Use the translation skill to translate this Japanese to English:
「おはようございます」
```

## Understanding the Three-Layer Output

Every translation provides three layers of information:

### 【Core Translation】

The main translation in natural, fluent target language.

**Example:**
```
Original (EN): "Break a leg!"
Core Translation (CN): 祝你好运！[表演界的祝福用语]
```

### 【Key Terms Explanation】

2-4 critical terms with detailed analysis.

**Example:**
```
1. "Break a leg"
   - Original meaning: Good luck (theater superstition)
   - Cultural context: Western theater tradition avoiding direct "good luck"
   - Translation strategy: Functional equivalence ("祝你好运") rather than literal
   - Alternative: Could transliterate + explain, but target readers prefer natural expression
```

### 【Background Context】

Cultural, historical, and linguistic insights.

**Example:**
```
This phrase originates from theater superstition where saying "good luck" 
was believed to bring bad luck. The translation prioritizes communicating 
the intended meaning (encouragement) over preserving the literal imagery, 
as Chinese readers would find a literal translation ("摔断腿") confusing or alarming.
```

## Advanced Usage

### Specify Text Type

Different text types get optimized treatment:

**Literary Translation**
```
This is a poem by Robert Frost. Please translate it to Chinese 
using the translation skill, preserving the imagery and rhythm.

[Poem text]
```

**Academic Translation**
```
Translate this research abstract from English to German using 
the translation skill. Prioritize terminology accuracy.

[Abstract]
```

**Business Translation**
```
This is a contract clause. Use the translation skill for precise, 
unambiguous translation from Chinese to English.

[Contract text]
```

**Marketing Translation**
```
Translate this ad copy to Spanish using the translation skill. 
Focus on emotional impact and cultural adaptation rather than 
literal accuracy.

[Ad copy]
```

### Batch Translation

Translate multiple items while maintaining consistency:

```
I have these 5 product descriptions to translate from English to French.
Please use the translation skill and maintain consistent terminology.

1. [Description 1]
2. [Description 2]
...
```

### Bilingual Output

Create side-by-side translations:

```
Create a bilingual document with the translation skill:
- Left column: Original English
- Right column: Chinese translation
- Include key terms notes at the bottom

[Source text]
```

### Translation + Document Creation

Combine with other skills:

```
Use the translation skill to translate this report to Spanish,
then use the docx skill to create a professional document with:
- Bilingual layout
- Key terms glossary
- Cultural notes section

[Report text]
```

## Customization Options

### Emphasize Specific Aspects

**Focus on Cultural Context**
```
Translate this using the translation skill, with extra emphasis 
on explaining the cultural differences in the Background section.
```

**Detailed Terminology Analysis**
```
Use the translation skill and provide extensive Key Terms 
explanations for technical terminology.
```

**Stylistic Preservation**
```
This author has a distinctive writing style. Please use the 
translation skill focusing on preserving the author's voice.
```

### Target Audience Specification

```
Translate this academic paper for a general audience using 
the translation skill. Simplify technical terms where appropriate.
```

## Tips for Best Results

### 1. Be Specific About Context

❌ Poor: "Translate this"
✅ Good: "This is a legal document. Use the translation skill to translate to French, prioritizing precision."

### 2. Mention Special Requirements

```
This text contains many idioms. Please explain each one in 
the Key Terms section when using the translation skill.
```

### 3. Specify Tone/Register

```
This is a formal business letter. Maintain formal register 
in the Spanish translation using the translation skill.
```

### 4. Request Specific Output Format

```
Use the translation skill and format the output as:
- Core translation in a quote block
- Key terms as a bulleted list
- Background as a separate section
```

## Common Use Cases

### Case 1: Website Localization

```
I'm localizing my website. Use the translation skill to translate 
these UI strings from English to Japanese, Korean, and Chinese. 
Focus on natural, native-speaker expressions.

[List of UI strings]
```

### Case 2: Literary Analysis

```
Translate this Kafka excerpt to English using the translation skill, 
and analyze his unique style in the Background section.

[German text]
```

### Case 3: Medical Translation

```
This is a patient information leaflet. Use the translation skill 
to translate from English to Spanish, ensuring medical terms are 
accurate and the text is accessible to non-specialists.

[Medical text]
```

### Case 4: Subtitle Translation

```
These are movie subtitles. Use the translation skill to translate 
from Chinese to English, keeping each line under 42 characters.

[Subtitle text]
```

## Workflow Examples

### Workflow 1: Professional Document Translation

1. Upload source document
2. Request translation with skill
3. Review Key Terms for accuracy
4. Adjust specific terms if needed
5. Use docx skill to format final document

### Workflow 2: Quality Assurance

1. Translate with the skill
2. Review Background Context for strategy
3. Check Key Terms explanations
4. Request alternative translations for specific phrases
5. Finalize preferred version

### Workflow 3: Learning Translation

1. Try translating yourself first
2. Use the skill for comparison
3. Study the Key Terms explanations
4. Read Background Context to understand decisions
5. Apply insights to next translation

## Troubleshooting

### Issue: Output is too literal

**Solution**: Specify "Use natural target language expressions" or mention the text type.

### Issue: Missing cultural context

**Solution**: Ask for "detailed cultural background in the Background section"

### Issue: Terminology inconsistency

**Solution**: Provide a glossary: "Use these specific translations for these terms: [list]"

### Issue: Too formal/informal

**Solution**: Specify the register: "Keep the casual tone" or "Use formal business language"

## Next Steps

- Explore [Example Translations](../examples/)
- Read about the [Translation Theory](theory.md)
- Check the [FAQ](faq.md)
- [Share your translations](https://github.com/YOUR-USERNAME/claude-translation-skill/discussions)

## Feedback

Found a better way to use the skill? [Share it with the community!](https://github.com/YOUR-USERNAME/claude-translation-skill/discussions)
