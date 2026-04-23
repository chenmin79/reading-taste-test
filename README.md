# Reading Taste Test 📚

A comprehensive, multi-round reading preference interview framework designed to infer a reader's taste profile and generate tailored book recommendations.

## Features

- **Multi-dimensional analysis**: Goes beyond simple genre labels to understand cognitive style, difficulty tolerance, reading purpose, and more
- **Real book calibration**: Uses actual reading history (loved, liked, disliked, DNF'd books) for accurate profiling
- **Three testing modes**: Quick, Standard, and Deep modes for different precision needs
- **Structured output**: Provides clear taste profiles with tiered recommendations
- **Bilingual support**: Works in both English and Chinese

## How It Works

The test follows a multi-round interview structure:

1. **Round 1**: Fast orientation - identifies main reading family and cognitive style
2. **Round 2**: Book-history calibration - infers taste from real examples  
3. **Round 3**: Fine-grained preference mapping - distinguishes close-but-different tastes

## Dimensions Analyzed

The framework tracks 8 key dimensions:

- **Content type**: fiction / nonfiction / mixed
- **Preferred domains**: literature, history, social science, philosophy, science, business, psychology, etc.
- **Cognitive style**: narrative-driven, framework-driven, knowledge-dense, argument-driven, curiosity-driven
- **Difficulty tolerance**: light, moderate, hard, very hard
- **Reading purpose**: entertainment, insight, self-cultivation, practical use, research
- **Format preference**: long-form, essays, dense theory, popular science, case studies, etc.
- **Author/source preference**: domestic, translated, classic, contemporary
- **Evaluation style**: rating-led, reputation-led, content-led, independent

## Usage

### For AI Assistants (ChatGPT, Claude, etc.)

Copy the content from `reading-taste-test.md` and use it as a system prompt or instruction. Then guide users through the multi-round interview.

### For Human Interviewers

Use the questionnaire templates and flow structure provided in the framework document.

## Testing Modes

### Quick Mode (3-5 minutes)
- 4–6 orientation questions
- 1 short book-history prompt
- Concise profile + 5–8 recommendations

### Standard Mode (Default)
- Round 1: 6–8 orientation questions
- Round 2: 3 loved / 3 disliked-or-DNF books
- Round 3: 3–5 fine-grained comparison questions
- Final profile + tiered recommendations

### Deep Mode (High Precision)
- Round 1: orientation
- Round 2: detailed reading history
- Round 3: structural and tonal preferences
- Round 4: recommendation calibration
- Final profile with confidence notes

## Profile Archetypes

The framework identifies readers through nuanced archetypes:

- Knowledge-density reader
- Framework builder
- Narrative explorer
- Practical upgrader
- Classic-and-ideas reader
- Methodical sampler
- High-certainty curator
- Mixed-domain generalist
- Deep-dive specialist
- Curiosity-led explorer

## Output Format

A complete analysis includes:

1. **一段式阅读画像** - 4-8 sentence reading profile summary
2. **关键维度拆解** - Detailed breakdown across all dimensions
3. **可能的雷区** - Likely dislikes and friction points
4. **推荐清单** - Tiered book recommendations (Core fit, Strong fit, Bridge fit, Stretch fit)
5. **继续测试建议** - Next questions for even more precision

## License

This project is licensed under the **Creative Commons Attribution-ShareAlike 4.0 International License** - see the [LICENSE](LICENSE) file for details.

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Credits

Created as part of the [Hermes Agent](https://github.com/nous-research/hermes-agent) project.

## Related Projects

- [Hermes Agent](https://github.com/nous-research/hermes-agent) - An intelligent AI assistant framework
