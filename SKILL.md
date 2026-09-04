---
name: travel-bead-souvenir
description: Transform real travel photos into refined fuse-bead / perler-bead travel souvenirs while preserving the original photo, intelligently choosing flat, irregular, semi-3D, or 3D bead structures, and prioritizing clean composition, negative space, realistic bead texture, and faithful scene reconstruction.
license: MIT
metadata:
  author: user-custom
  version: "1.0.0"
---

# Travel Bead Souvenir

Turn a user's real travel photograph into a refined 3:4 travel-bead composition that feels like a photographed handmade souvenir rather than a generic AI filter.

中文定位：旅行拼豆纪念册。适用于用户要求将真实旅行照片转化为拼豆、fuse bead、perler bead、bead-art、pixel-bead 或 3:4 照片加拼豆纪念品构图的任务。

## Compatibility

OpenAI Codex and Agent Skills-compatible clients. Best results require an image generation or image editing capability that can use the user's uploaded image as the source. If image editing is unavailable, produce an exact generation/edit prompt instead of pretending the image was edited.

The user's explicit instructions always take precedence over this skill.

## Non-negotiable priorities

1. Preserve the user's real photograph in the upper section. Do not repaint or regenerate it.
2. Never invent or swap people, animals, architecture, objects, locations, weather, signs, or scenery.
3. The lower bead artwork is a designed interpretation, not a full mechanical pixel copy.
4. Decide the bead format from the image itself: flat, irregular/contour, semi-3D, or 3D miniature.
5. Use generous warm-cream negative space. Do not fill the whole lower half by default.
6. Do not add decorative photos, postcards, leaves, tape, stamps, slogans, or random English unless the user explicitly asks.
7. Do not add generic labels such as “FUSE BEAD”, “YEHE PHOTO”, “TRAVEL IN PIXELS”, or other template text.
8. If a verified location is known and the user wants text, use only a concise, accurate English location label.

## Workflow

### Step 1 — Inspect the uploaded photo

Always analyze the original photo before generating. Identify:

- the primary visual subject;
- the 1–3 secondary elements worth keeping;
- the dominant 4–10 colors;
- what makes the scene geographically or emotionally recognizable;
- which parts are disposable background clutter;
- whether the scene naturally supports depth.

Identify the core subject, judge which content deserves to be preserved, and decide which background elements can be weakened or removed. Do not treat every visible detail as equally important.

### Step 2 — Choose the bead treatment

Use the simplest format that preserves the image's character.

#### A. Flat bead panel / 平面拼豆

Best for sunsets, silhouettes, night scenes, skylines, and compositions that are already highly graphic.

#### B. Irregular / contour bead piece / 异形或破框拼豆

Best for animals, people, road signs, a single building, a clear object, boats, or a small group of distinct objects. Let the physical contour end naturally instead of forcing a rectangle.

#### C. Semi-3D layered bead piece / 半立体拼豆

Best for building façades, churches, city streets, Venice waterfronts, arcades, and architecture with a readable front-to-back relationship. Use 2–4 depth layers only where the real scene supports them.

#### D. 3D miniature bead scene / 立体微缩拼豆

Use only when the original photo has clear spatial depth. Examples:

- Courtyard: paving → fountain → arcade.
- Venice: water → boat → buildings.
- Moroccan village: farmland → plants → village.

Build depth from the real spatial logic, not for spectacle. Never make a person or object protrude merely to make the result look “3D”.

Never force the same treatment across a series.

### Step 3 — Compose the final 3:4 image

The final output is a **3:4 vertical canvas**.

**Upper section**
- Fill the upper section with the user's actual photo.
- Crop only when needed for a cleaner composition.
- Never stretch.
- Only make subtle photographic adjustments: exposure, white balance, contrast, saturation, and local tonal balance.
- Never AI-repaint or regenerate the photograph.
- Never change people, architecture, animals, or weather.
- Never add a subject that does not exist in the original photo.
- Keep the photo recognizably photographic and non-AI.

**Lower section**
- Warm cream / matte ivory background.
- Place one bead artwork derived from the photo.
- The bead subject typically occupies about 45–70% of the lower section; adjust its size to the composition rather than forcing a fixed scale.
- Leave substantial breathing room.
- Use soft, believable contact shadows and slight material thickness where appropriate.
- Do not automatically center if an off-center composition is visually stronger.

The governing principle is: “不是把照片里每一个像素重新拼一次，而是提取真正值得被记住的部分。”

### Step 4 — Simplify with hierarchy

Keep what the viewer is most likely to remember.

Prioritize:
- people;
- animals;
- landmark architecture;
- signs;
- doors/windows;
- domes;
- coastlines;
- mountains;
- camels;
- boats;
- ferris wheels;
- fountains;
- stained glass;
- distinctive plants or travel objects.

Reduce or omit:
- empty sky with no compositional role;
- repeated background structures;
- distracting crowds;
- tiny unreadable details;
- generic textures;
- unnecessary intermediate colors.

Aim for “recognizable memory object”, not “every pixel reproduced”.

Never mechanically pixelate the entire photograph or reproduce every pixel as a full rectangular bead panel.

### Step 5 — Material realism

The bead artwork must read as real fuse/perler bead craft:

- cylindrical plastic beads;
- visible center holes;
- regular bead spacing;
- slight heat-fused joining;
- subtle thickness;
- tactile plastic surface;
- clean studio-like light;
- soft physical shadow on the cream background.

Avoid LEGO, watercolor, generic pixel art, cross-stitch, mosaic, felt, cartoon 3D, smooth plastic models, embroidery, or glossy toy-plastic blobs.

### Step 6 — Color discipline

Extract the scene's strongest colors and simplify them into a clean bead palette.

- Prefer clear, distinct colors.
- Keep the original color relationships.
- Reduce muddy gray interpolation.
- Do not oversaturate unless the original image is already saturated.
- For a series, keep the cream background and bead material consistent while allowing each scene's palette to differ.

### Step 7 — Text rules

Default: **no text**.

If the user asks for text and the location is certain, add only a concise English location name such as:

- SAHARA
- VENICE
- MOROCCO
- REGENT'S PARK
- LONDON

Typography should be small, restrained, editorial, and secondary to the image.

Use concise English set in a small serif / editorial style. Never guess a location. If uncertain, omit text. Never use “FUSE BEAD”, “YEHE PHOTO”, “TRAVEL IN PIXELS”, a fictional location, or a random English slogan.

### Step 8 — Decorative restraint

Do not mechanically add polaroids, postcards, stamps, tape, leaves, flowers, stickers, handwriting, or random travel decorations. Reference images may guide negative space, hierarchy, composition, depth relationships, and subject scale, but never copy another creator's decorative elements.

### Step 9 — Series rhythm

When working on multiple images, keep the series consistent in:

- 3:4 canvas;
- warm cream background;
- photo preservation;
- bead material;
- overall lighting quality.

Vary:

- bead artwork scale;
- flat vs irregular vs 3D treatment;
- left/right/center placement;
- whether and how far the bead piece breaks its frame;
- amount of negative space;
- depth structure.

Do not standardize bead size, 3D format, subject position, frame-breaking, or use of a complete rectangle.

The set should feel like pages from one travel collection, not the same template with swapped photos.

## Tool behavior

If an image editing/generation tool is available:

- use the uploaded photo as the actual edit/source image;
- do not rely on memory of the photo;
- do not generate a substitute photo;
- apply the workflow above directly.

If no image tool is available:

- do not claim the image has been edited;
- output a precise image-edit prompt tailored to the uploaded photo and the selected bead treatment.

See `references/visual-rules.md` for more detailed aesthetic decisions and `references/prompt-template.md` for a reusable generation prompt.

## Final quality check

Before finalizing, verify all of the following:

- [ ] 顶部是否仍是用户原始摄影？
- [ ] 是否避免明显 AI 重绘？
- [ ] 拼豆是否有真实圆孔？
- [ ] 是否避免整张照片机械铺满？
- [ ] 是否提取了真正重要的主体？
- [ ] 留白是否足够？
- [ ] 立体是否有空间逻辑？
- [ ] 是否避免无意义破框？
- [ ] 是否避免乱加装饰？
- [ ] 是否避免乱写英文？
- [ ] 地点是否真实？
- [ ] 是否为 3:4 竖版？
- [ ] 是否和上一张在形式上有变化？
- [ ] 第一眼是否像真实拼豆旅行纪念品，而不是 AI 滤镜？
