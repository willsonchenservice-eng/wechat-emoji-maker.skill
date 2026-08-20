# 微信表情包制作验收清单

## Keyword research gate

- [ ] Every keyword has a traceable current meme/image source: platform, link, retrieval date and original reference image or screenshot.
- [ ] The keyword text is copied from the original source and has user confirmation; it is not a model-invented paraphrase.
- [ ] The source's defining visual anchor is written down: gesture, facial close-up, crop, composition or prop.
- [ ] The candidate can be understood visually without relying only on enlarged text; weak or non-visualizable candidates are removed instead of used to fill the target count.
- [ ] Similar candidates are deduplicated and the batch is not padded with several versions of the same reaction.

## Per-asset checklist

- [ ] Correct IP identity: face, silhouette, colors, costume and fixed accessories.
- [ ] Correct character count: one IP when the brief says single; both only when interaction adds meaning.
- [ ] Keyword is visible through action, facial expression, prop or composition.
- [ ] The original meme reference is actually reflected in the defining pose, expression, crop, composition or prop; the image is not a generic interpretation of the phrase.
- [ ] Text is exact, complete and legible; a no-text asset exists only when the brief explicitly requires it.
- [ ] No accidental extra words, logos, watermark or random speech bubbles.
- [ ] Text is drawn into the same composition: no blank caption area, reserved text box, white title card or post-generation overlay.
- [ ] The confirmed sticker treatment is present: pale gray outside, continuous irregular white die-cut edge, hand-drawn display lettering and black/red emphasis.
- [ ] No cropped face, hand, hoof, wing, tail or key prop.
- [ ] Consistent line weight, palette, shading and background language with the pack.
- [ ] No unrequested character, species, costume or prop.
- [ ] No dangerous action or graphic content; distress can be expressed safely and non-literally.
- [ ] Output path and filename clearly map to the keyword and version.

## Batch-level checklist

- [ ] Every requested keyword has one independently saved asset.
- [ ] Single-character and two-character compositions are intentionally varied.
- [ ] No one generic composition has been copied across the entire batch.
- [ ] The same IP does not drift in size, palette, facial structure or fixed accessories.
- [ ] No default no-text or placeholder-text batch has been introduced.
- [ ] Older attempts are preserved or clearly superseded; no silent overwrite.
- [ ] A manifest records keyword, character count, text rule, reference roles, version and QA result.
- [ ] The manifest records source evidence, visual anchor and user confirmation for every keyword.

## Extension-material checklist

- [ ] Design drafts and upload candidates are saved separately.
- [ ] Each asset records actual dimensions, format, file size and any transparency requirement.
- [ ] Safe area is used only for required QR codes, amounts or platform UI; no fake caption box is added.
- [ ] Cover, header, icon and reward art are designed for their own proportions; no main sticker is simply stretched.

## Adversarial review

Before claiming completion, ask:

1. What would make the owner say “这不是我的 IP”？
2. What would make the keyword unreadable without the caption?
3. What is the most likely text error or accidental extra object?
4. Which asset most clearly violates the single-vs-double-character rule?
5. Which asset would fail when cropped into a small WeChat sticker thumbnail?

If a check fails, regenerate with one targeted change and re-check the same item. Do not hide failures behind a batch-level average.
