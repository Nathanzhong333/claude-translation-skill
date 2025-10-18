# Installation Guide

This guide will help you install and set up the Claude Translation Skill.

## Prerequisites

- Access to Claude AI (claude.ai)
- A web browser
- The `translation.zip` file from this repository

## Installation Steps

### Step 1: Download the Skill

1. Go to the [Releases](https://github.com/YOUR-USERNAME/claude-translation-skill/releases) page
2. Download the latest `translation.zip` file
3. Save it to your computer

Alternatively, you can download directly from the repository:
- Click on the `translation.zip` file in the root directory
- Click the "Download" button

### Step 2: Upload to Claude

1. Visit [claude.ai](https://claude.ai)
2. Start a new conversation or continue an existing one
3. Click the attachment button (📎) or drag and drop the `translation.zip` file
4. Wait for the file to upload

### Step 3: Install the Skill

Once uploaded, tell Claude:

```
Please install this translation skill
```

or

```
Please help me set up this translation skill
```

Claude will:
- Extract the skill files
- Install them in the correct location
- Confirm when ready to use

### Step 4: Verify Installation

Test the skill with a simple translation:

```
Use the translation skill to translate "Hello, world!" to Spanish
```

You should receive a three-layer output:
1. Core Translation
2. Key Terms Explanation  
3. Background Context

## Alternative Installation Methods

### Method 1: Direct Use Without Installation

You can use the skill immediately after upload:

```
Use this skill to translate: [your text]
```

### Method 2: Manual Installation

If you prefer to install manually:

1. Extract `translation.zip` on your computer
2. Upload the `SKILL.md` file to Claude
3. Ask Claude to install it to `/mnt/skills/user/translation/SKILL.md`

## Troubleshooting

### Issue: Claude doesn't recognize the skill

**Solution**: Try re-uploading the file and explicitly asking Claude to install it as a translation skill.

### Issue: Skill not working as expected

**Solution**: Make sure you're using phrases like "use the translation skill" or "translate using the skill" to trigger it.

### Issue: File upload fails

**Solution**: 
- Check your internet connection
- Try a different browser
- Ensure the file isn't corrupted (download again if needed)

## Updating the Skill

To update to a new version:

1. Download the new `translation.zip`
2. Upload to Claude
3. Say: "Please update my translation skill with this new version"

## Uninstalling

To remove the skill:

```
Please remove the translation skill
```

Note: Skills are session-based. Starting a new conversation will reset any installed skills.

## Next Steps

- Read the [Usage Guide](usage.md) for examples
- Check out [Example Translations](../examples/) 
- See the [FAQ](faq.md) for common questions

## Need Help?

- [Open an issue](https://github.com/YOUR-USERNAME/claude-translation-skill/issues)
- Check existing [discussions](https://github.com/YOUR-USERNAME/claude-translation-skill/discussions)
