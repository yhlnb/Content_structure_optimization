# Fashion Source Framework

Use this file when optimizing clothing, bag, outfit-shopping, or menswear/lifestyle shopping-share scripts and the user wants stronger fashion expertise or source-backed styling logic.

## Source Types

Use two kinds of sources and keep them separate:

- Product sources: official brand pages, retailer pages, lookbooks, or product descriptions. Use these only for verifiable facts such as material, strap adjustability, compartments, size, closure, lining, care, and color.
- Styling sources: fashion editorials and styling guides such as Vogue, British Vogue, GQ, MR PORTER Journal, SSENSE editorials, Hypebeast, Highsnobiety, brand lookbooks, or runway/street-style coverage. Use these for outfit logic: silhouette, proportion, color pairing, seasonal context, and how a shape is usually styled.

## Reference Workflow

1. Identify the styling claim the script needs to make.
   - Example: "This soft hobo-like bag works with relaxed shirts and straight trousers."
2. Find a fashion styling source that supports the broader logic.
   - Example source angle: hobo bag + relaxed silhouettes; oversized shirt + tank/straight trousers; wide-leg pants + cleaner top; linen/camp-collar shirt + summer dressing.
3. Extract the useful principle, not the exact wording.
4. Translate it into the user's voice.
5. If giving advice to the user, include the reference link and a one-line explanation of what was borrowed from it.

## Starter Reference Examples

Use these as examples of the kind of source to look for. Refresh links with web search when current sourcing matters.

- Vogue, `What I Learned While Supersizing My Wardrobe`: useful for oversized/baggy proportions, large bags, and balancing volume.
  - https://www.vogue.com/article/baggy-fashion-summer-trend-styling-tips
- British Vogue, `4 Foolproof Ways To Style An Oversized Shirt This September`: useful for oversized shirts with jeans, tailored trousers, or other proportion-balancing bottoms.
  - https://www.vogue.co.uk/fashion/article/how-to-style-oversized-shirt
- GQ, `How to Style Wide-Leg Pants for Men`: useful for menswear wide-leg/straight-leg pants, shoe weight, top proportion, and practical styling language.
  - https://www.gq.com/story/how-to-style-wide-leg-pants
- Vogue, `The Best Linen Shirts for Effortless, Elevated Summer Style`: useful for linen shirts, summer texture, and warm-weather styling.
  - https://www.vogue.com/article/linen-shirts

## Output Pattern For Advice

When the user asks for sources, use this format:

```markdown
参考来源：[Source title](URL)
我提炼出的穿搭逻辑：...
可以转成你的口播：...
```

When writing the final recordable script, avoid footnote-like citations inside every sentence. Put references before or after the rewrite unless the user asks for line-by-line sourcing.

## Common Styling Logic

### Bags

- Soft hobo or slouchy shoulder bags usually pair better with relaxed silhouettes than with very formal tailoring because the bag shape already has movement and softness.
- Tote bags work well when the script emphasizes capacity, daily objects, and casual styling. Talk about what goes inside and what outfit mood it supports.
- Messenger/crossbody bags work well for commuting and travel when the script can show compartments, hands-free use, and a practical clothing context.

### Shirts

- Oversized shirts need proportion control. Wearing them open over a tank, pairing them with straighter trousers, or using a shorter layer can keep the look from feeling swallowed.
- Camp-collar/Cuban-collar shirts read more relaxed than standard button-ups. Pair them with shorts, cropped trousers, relaxed pants, sandals, loafers, or summer textures.
- Linen and linen-blend shirts carry summer texture and breathability. The script should mention looseness, wrinkles/texture, and how the piece behaves in heat.

### Pants

- Wide-leg or straight-leg pants need balance. A cleaner, slightly cropped, tucked, or well-fitted top often keeps the shape from looking sloppy.
- Pants with strong details, such as utility pockets, pleats, washed fabric, or patchwork, usually need simpler tops.
- White or light trousers rely heavily on fabric weight and opacity. Mention whether the fabric looks thin, stiff, soft, drapey, or clean.

## Good Source-To-Script Examples

### Hobo Bag With Relaxed Outfit

Source logic: Vogue discusses hobo bags and baggy/oversized styling as part of relaxed proportions.

User-voice version:

```text
它肩带可以调，所以背法会比较多。平时可以斜挎，想让造型更松一点的时候，就把肩带调短，当成偏 hobo 的感觉去背。因为包型比较软，所以它更适合搭宽松衬衫、直筒裤这类松弛一点的单品。
```

### Oversized Shirt

Source logic: Vogue styling guides often pair oversized shirts with tanks, jeans, trousers, or proportion-balancing layers.

User-voice version:

```text
这件我会里面叠一件白色背心，下半身搭直筒裤或者白色长裤。上半身有层次，但整体不会显得太厚。
```

### Wide-Leg Pants

Source logic: GQ styling guidance for wide-leg pants focuses on proportion, cleaner tops, fabric structure/drape, and shoe weight.

User-voice version:

```text
这种裤子我会更建议搭短一点的衬衫或者干净的短袖。裤子本身有量感，上半身收得利落一点，比例会更好。
```

## Guardrails

- Do not cite a source for a specific product fact unless the source is a product page or official brand/retailer page.
- Do not claim a specific publication recommends the exact item unless it does.
- Do not over-explain sources in the recordable script. The spoken version should still sound like the user, not like a research memo.
- If the source supports only a broad trend, phrase it as "这个逻辑可以参考..." rather than "某某说这件应该这样搭."
- Keep the user's phrasing direct. Avoid "不只是...而是..." and avoid generic planning phrases like "日常穿起来也不用太费力."
