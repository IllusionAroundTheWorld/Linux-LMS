# Agent Instruction 
Read this entire file before starting any task 

## self-correcting Rules Engine

this file contain a growing ruleset that imporve over time . **At session start, read the entire "Learned Rules" section before doing anything**

### How its works 
1. When the user correct your or your make a mistakes, **immediately append a new rules** to the "Learned Rules " section at the bottom of this file.
2. Rules are number sequentially and written as clear, imperative instructions.
3. Format: `N. [CATEGORY] Never/ALways do  - because Y.`
4. Cateogries: `[STYLE], '[CODE]', '[TOOLS]', '[PROCESS]', '[DATA]', '[UX]', '[OTHER]'
5. Before ask any task, scan all rules below for relevant constraints.
6. If two rules conflict, the higher-numbered (newer) rule wins.
7. Never delete the rules. If a rule becomes obsolete, appedn a new rule that supersedes it. 

### When to add a rules
 - User explicitly correct your output ["no, do it this way"]
 - User rejects a file, approach, or pattern
 - You hit a bug caused by a wrong assumption abuot his codebase
 - User state a preference ("always use X", "never do Y")

### Rules format example

```
14. [CODE] Always use `bun` instead of `npm` - user preference, but ins installed globally.
15. [STYLE] Never add emojis to commit message - project convertions.

```

## Learned Rules

<!-- New Rules are appended below this line. Do not edit about this section. -->
1. [UX] Always design content to fit comfortably within a single-screen viewport without unnecessary page scrolling or overflow - keeps the learning interface focused, clean, and accessible.
2. [UI] Always display images fully without clipping or awkward cropping (use `object-fit: contain` and proper aspect ratios) - prevents important parts of portrait or diagram images from being cut off.
3. [STYLE] Always align UI aesthetics, colors, and typography with Inovate Solution Technology branding (https://www.inovatesolutiontechnology.in/) - maintains professional corporate brand identity.
4. [STYLE] Always use the authentic Inovate Solution Technology live theme tokens (`--primary: #1571ba`, `--ink: #17202c`, `--muted: #5d6470`, `--line: #dfe3e8`, `--paper: #f7f8fa`, `--surface: #f5f9fc`, clean `#ffffff` header, and `Inter` font) - ensures exact fidelity with the official corporate site.
5. [UX] Never display AI icons, emojis, or lightning/sparkle badges in the LMS course interface - keeps the user experience clean, human-designed, and free of confusing AI indicators.
6. [CONTENT] Always write simple, clear lesson content where every explanation and takeaway has more than 10 words - guarantees high clarity while providing complete, easy-to-understand educational context.
7. [UX] Always keep core concept summaries and takeaway notes concise and tightly focused (between 11 and 16 words each) - prevents visual clutter and ensures complete single-screen display without vertical scrolling.
8. [UX] Always use the IST Learn interactive pattern (1. Simple Idea with minimal text, 2. Interactive SVG flowchart with live controls, 3. Quick Check chips) - eliminates heavy text walls and creates an engaging, hands-on learning experience.
9. [UX] Always present single-topic lessons directly without multi-step tab navigation or top tab buttons when focusing on a specific topic - keeps the interface streamlined and focused on one complete learning experience.
10. [CONTENT] Always refer to Linus Torvalds simply as "Linus Torvalds" without his middle name "Benedict" - keeps creator references natural, modern, and professional.
11. [UI] Always represent Linux architecture using concentric onion rings (Center: Hardware, then Kernel, Shell, and Outer Ring: Application) - accurately mirrors standard Linux architectural hierarchy as requested.
12. [UX] Always use clear, interactive SVG flowcharts instead of static diagram images for system architecture concepts - ensures educational concepts are engaging, animated, and easy to understand.
13. [CONTENT] Never add extra command simulations or runtime traces to architecture diagrams when explaining the 4 layers - keep the flowchart strictly focused on the 4 core tiers (Hardware, Kernel, Shell, Application) for maximum clarity and simplicity.
14. [UX] Always present architecture sidebar layer inspector details in short, sweet, bullet-style summaries (Role and Examples only) - avoids text overload and keeps technical definitions instantly digestible.
