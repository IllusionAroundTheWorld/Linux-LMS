# Agent Instructions
Read this entire file before starting any task.

## Self-Correcting Rules Engine

This file contains a growing ruleset that improves over time. **At session start, read the entire "Learned Rules" section before doing anything.**

### How It Works
1. When the user corrects you or you make a mistake, **immediately append a new rule** to the "Learned Rules" section at the bottom of this file.
2. Rules are numbered sequentially and written as clear, imperative instructions.
3. Format: `N. [CATEGORY] Never/Always do X - because Y.`
4. Categories: `[STYLE]`, `[CODE]`, `[TOOLS]`, `[PROCESS]`, `[DATA]`, `[UX]`, `[UI]`, `[CONTENT]`, `[OTHER]`
5. Before starting any task, scan all rules below for relevant constraints.
6. If two rules conflict, the higher-numbered (newer) rule wins.
7. Never delete rules. If a rule becomes obsolete, append a new rule that supersedes it.

### When to Add a Rule
- User explicitly corrects your output ("no, do it this way")
- User rejects a file, approach, or pattern
- You hit a bug caused by a wrong assumption about this codebase
- User states a preference ("always use X", "never do Y")

### Rule Format Examples

```
14. [CODE] Always use `bun` instead of `npm` - user preference, and it is installed globally.
15. [STYLE] Never add emojis to commit messages - project conventions.
```

## Learned Rules

<!-- New Rules are appended below this line. Do not edit above this section. -->
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
15. [CODE] Never retain temporary working copies (e.g., Work_Today_* files) or unreferenced image assets in the repository - maintains a clean, single-source-of-truth structure across all course levels.
16. [UX] Always prioritize clean, breathable, uncluttered spacing over rigid single-screen viewport cramming - overrides strict one-screen height limits to ensure text fits comfortably inside diagram boxes without visual overwhelm.
17. [UI] Always structure module courses using the unified Module2.html SPA layout (horizontal level navigation tabs, concept chips, interactive simulator/flowchart, video reference, quick checklist, and self-check quiz) - user commanded matching /home/illusion/sda5/Fun/IST/LMS/Python/Module2.html.
18. [UI] Never display top summary-banners and only include Video References on levels with explicit practical video guides (Level 4: Installing Linux & Level 5: Virtual Machines) - keeps UI clean and avoids video placeholders on conceptual levels.
19. [CONTENT] Place course assessments exclusively in a dedicated final Quiz section followed by a Summary & Download (.txt) section, rather than attaching mini-quizzes to the end of every individual level - provides a unified testing experience and easy note export.
20. [CONTENT] Never test Linux terminal commands or CLI syntax in beginner quizzes - design all assessment questions around fundamental concepts, architecture roles, and operating system principles.
21. [UI] Always use interactive SVG flowcharts with live view toggles as the primary visual learning tool in Module1.html, and include the creator card with Linus Torvalds' portrait in Level 1.
22. [UX] Never include the quick checklist section in the course interface - user preference to remove checklists and keep individual level screens clean, breathable, and focused.
23. [CONTENT] Always format flowchart node content as keyword phrases connected with '-' (e.g., 'Keyword - Keyword') rather than long continuous conversational sentences - improves visual scanability and concise technical clarity.
24. [UI] Always feature both founding pioneers—Richard Stallman (GNU Project) and Linus Torvalds (Linux Kernel)—in Level 1 with prominent portrait cards (100px width/height with object-fit: contain) - honors GNU/Linux dual origin and guarantees clear visual prominence.
25. [CONTENT] Never include the Quiz section (Tab 9) in the course module interface - user preference to remove the Module Quiz section and have the course conclude directly with the Summary & Download section.
26. [UI] Never include top header bars [Inovate Solution Technology] or bottom level navigation buttons ([Next level] / [Previous level]) in course level files, and always deliver each level as a self-contained, standalone HTML file (inline CSS and JS in Module1/ and Module2/ folders) - user preference for completely decoupled, self-contained level files without navigation clutter.
27. [UI] Always format code and telemetry inspector boxes with rich syntax highlighting tokens and styles (e.g., colored keys, values, keywords, commands) instead of plain monochrome text on black - ensures high contrast, readability, and modern aesthetic.
28. [UI] Always include stylish, authentic ASCII art symbols (Arch, Ubuntu, Red Hat) when presenting famous distribution cards or details - provides engaging visual identity and terminal nostalgia.
29. [UI] Never include bottom completion status footers ('Level x Complete' & 'Interactive system lab powered by Inovate Solution Technology learning framework') in course level files - keeps the terminal/course view clean, focused, and uncluttered.
30. [UI] Always display the official Linux Tux mascot symbol instead of creator portrait photos (Linus Torvalds and Richard Stallman) in Level 1 - supersedes Rule 24 and Rule 21 per user request to represent Linux through its iconic community symbol.
31. [CONTENT] Always title Module 1 Level 2 as 'History of Linux, Distribution, Kernel' - aligns exact course level naming with user curriculum requirements.
32. [UI] Never include live terminal output simulations under the Fun Activity section in Module 1 Level 2 - display only the clean Step 1 (package installation) and Step 2 (command execution) syntax-highlighted command cards.
33. [UI] Always provide functional 'Copy to Clipboard' buttons on terminal command boxes in the Fun Activity section - gives learners a one-click way to copy commands directly into their real terminal.
34. [UI] Always display the official Tux mascot vector asset (tux.svg) in Level 1 - guarantees the authentic, high-quality, recognizable Linux mascot representation.
35. [UI] Never use local image file paths in course levels; always use reliable web-hosted image URLs (e.g., Wikimedia Commons, official CDNs) - user commanded that all images across every level must load from the website rather than local files.
36. [CONTENT] Always label the aerospace Linux domain as 'Space Research' instead of 'SpaceX' in Level 1 - user commanded replacing corporate SpaceX references with broader Space Research coverage.
37. [UI] Always design simulator progress bars and status indicators with generous padding, dedicated container cards, and legible text positioned cleanly outside or below progress tracks (never crammed inside thin bars), and enclose all status alerts in structured cards without horizontal text overflow - ensures high-contrast visual clarity and eliminates cramped or clipped simulator UI.
