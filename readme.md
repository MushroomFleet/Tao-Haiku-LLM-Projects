# Tao-Haiku Generator

A specialized LLM prompt engineering project for generating paradoxical Taoist wisdom in haiku form.

## Overview

This project emerged from a study in structured prompt engineering, exploring the generation of philosophical haiku that embody the core Taoist paradox: "The world that can be constructed is not the True World." The system is designed to produce consistent, meaningful verses that maintain both poetic structure and philosophical depth.

## Project Structure

```
README.md                 # This documentation file
tao-haiku-prompt.txt      # Core rules and format specifications
tao-haiku-test.txt       # Test cases and verification
generated-haiku-log.json # Output tracking and state management
```

## Required Setup Files
These files are not uploaded to the project but are used for setup:

- project-instructions.txt: Used as Custom Instructions
- init-prompt.txt: Used to start each new chat session

## Core Files

### tao-haiku-prompt.txt
Contains the core rules and format specifications for haiku generation. Defines the fundamental paradox, syllable structure, and thematic requirements.

### project-instructions.txt
Details the operational parameters for the project, including file relationships, error handling, and maintenance procedures.

### init-prompt.txt
The initialization prompt used to start a new generation session. This is the file whose contents you'll paste to begin interaction.

### tao-haiku-test.txt
Contains test cases and verification criteria to ensure proper functioning of the generator.

### generated-haiku-log.json
JSON structure for tracking generated content and maintaining state across sessions. Helps prevent repetition and maintain variety.

## Example Output

```
The Sages say:
Maps that claim to show
All paths through mountain passes
Hide the true journey

The Sages say:
Wisdom wrapped in words
Like pearls in silken cases
Masks the naked truth

The Sages say:
Knowledge we can hold
In cups of understanding
Mocks the ocean's depth

The Sages say:
Power we can name
In scrolls of ancient learning
Blinds true mastery

The Sages say:
Light we try to catch
In mirrors of description
Dims the primal flame
```

## Usage with Claude Projects

1. Create a new Claude Project
2. Add only the files listed in Project Structure section above
3. Open project-instructions.txt from the repository
4. Copy its contents and paste them into the "Custom Instructions" section of your Claude Project settings
5. Ensure generated-haiku-log.json is properly formatted (empty json structure is fine for first use)
6. Start a new chat
7. Open init-prompt.txt from the repository and copy its contents
8. Paste the init-prompt.txt contents into your chat to begin
9. The system will generate the first 5 haiku
10. Type "continue" for additional sets of 5 unique haiku

Note: Neither project-instructions.txt nor init-prompt.txt should be uploaded to the project files. They are setup files only.

## Implementation Notes

- Optimized for Claude Projects
- Maintains philosophical integrity while ensuring poetic structure
- Uses JSON for state tracking and repetition avoidance
- Clean interface with single-word command
- No meta-commentary or explanation in outputs

## Contributing

Issues and enhancement requests welcome. Development areas:
1. Additional philosophical frameworks
2. Extended verse formats
3. Improved tracking mechanisms
4. Alternative paradox structures

## License

MIT License - See LICENSE file for details

## Version

1.0.1 - Updated file structure and formats

---

*"The prompt that can be prompted is not the eternal prompt."*
