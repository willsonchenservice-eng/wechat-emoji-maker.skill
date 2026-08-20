# 微信表情包制作提示词模板

只在需要时读取本文件。所有提示词都要把参考图角色写清楚，并把不变量和禁止项分开。

## 1. Identity anchor

```text
Use case: stylized-concept
Asset type: IP identity reference
Input images: Image 1 = identity reference; Image 2 = relationship/style reference
Subject: preserve the exact character silhouette, palette, face, costume, accessories and proportions
Style/medium: same hand-drawn cartoon line art, outline weight and shading language as the reference
Constraints: do not redesign the character; do not add other characters or unrequested props
Avoid: photorealism, watermark, logos, illegible text
```

## 2. Three-view turnaround

```text
Create one clean model sheet with exactly three full-body views in equal scale:
FRONT, LEFT SIDE PROFILE, BACK.
Keep one consistent body proportion, costume construction and accessory placement.
The back view has no front-facing eyes, mouth or other facial features.
Use a clean light background and no scene props.
```

## 3. Single-character sticker

```text
Create one finished independent square Chinese WeChat sticker in the confirmed integrated-text die-cut style.
Use the user's IP image as the identity reference; use any supplied finished sticker only as a style reference.
Style: thick irregular white die-cut outline on a pale gray outside background, bold rounded hand-drawn Chinese display lettering, black main type with red emotional emphasis.
Create the exact keyword “<KEYWORD>”.
Only <CHARACTER> is present.
Action/emotion: <VISIBLE ACTION AND FACIAL EXPRESSION>
Visual proof of keyword: <CHART / PHONE / TEARS / SMOKE / OTHER>
Text (verbatim): “<KEYWORD>”. Integrate the text into the sticker composition, not a separate text box. Do not add any other words.
Avoid: blank caption area, rectangular title card, social-media cover layout, post-generation text overlay, <UNWANTED CHARACTERS, PROPS, ACTIONS, TEXT>
```

## 4. Two-character sticker

```text
Create one finished independent square Chinese WeChat sticker in the confirmed integrated-text die-cut style.
Use the user's IP images as identity references; use any supplied finished sticker only as a style reference.
Style: thick irregular white die-cut outline on a pale gray outside background, bold rounded hand-drawn Chinese display lettering, black main type with red emotional emphasis.
Create the exact keyword “<KEYWORD>”.
Both characters are present only because the meaning requires interaction.
Character A role: <EMOTION / ACTION>
Character B role: <CONTRAST / SUPPORT / ANALYSIS>
The relationship must read immediately without relying on the caption.
Text (verbatim): “<KEYWORD>”. Integrate the text into the sticker composition, not a separate text box. Do not add any other words.
Avoid: blank caption area, rectangular title card, social-media cover layout, post-generation text overlay.
```

## 5. Extension asset

```text
Asset type: <reward art / cover / header / collection page>
Platform and size: <KNOWN OR DEFAULT>
Character count: <ONE / BOTH / GROUP>
Primary hierarchy: IP first, supporting prop second, required platform information third.
Text: <EXACT TEXT, OR NO TEXT ONLY WHEN THE BRIEF EXPLICITLY REQUIRES IT>
Reserve safe area only for required QR codes, amounts or platform UI; never invent a caption box or poster-like blank area.
If copy is not finalized, confirm it before final typography instead of using a placeholder layout.
```

## 6. Confirmed integrated-text die-cut sticker

```text
Create one finished independent square Chinese WeChat sticker.
Use the user's IP image as the identity reference; use the supplied finished stickers as style references only.
Style: thick irregular white die-cut outline on a pale gray outside background, bold rounded hand-drawn Chinese display lettering, black main type with red emotional emphasis, dense expressive props and reaction marks.
The exact caption must be generated inside the image in the same pass and must be part of the sticker composition, not a separate text box.
Text (verbatim): "<KEYWORD>"
Line breaks: <EXACT LINE BREAKS>
Do not copy any other words, logos, watermark or title from the references.
Avoid: blank caption area, rectangular card, social-media cover layout, post-generation text overlay.
```
