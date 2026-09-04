# Reusable Prompt Template

## 中文基础模板

> 将用户上传的旅行照片转化为 fuse bead / perler bead 拼豆作品，保留原图主体、构图和主要配色，使用规则排列的圆柱形塑料拼豆，每颗中央有清晰圆孔，并呈现轻微热熔连接感、真实厚度、塑料质感与自然投影。
>
> 最终画面为 3:4 竖版，使用暖米白 / 奶油米白背景。上半部分必须直接保留用户上传的真实原照片，只允许轻微调整曝光、白平衡、对比度和饱和度，并可为构图合理裁切。Preserve original photo. No AI repainting. 不得改变人物、建筑、动物或天气，不得添加原图中不存在的主体，不得把真实摄影洗成明显 AI 图。
>
> 下半部分进行 smart subject extraction：识别并提炼 [核心主体]、[值得保留的次要元素] 与 [主要配色]，弱化或删除 [无关背景 / 杂乱细节]。不要把整张照片机械像素化，也不要默认铺满成完整矩形拼豆画。拼豆主体通常占下半区约 [45–70]% 并保留明显 negative space。
>
> 根据原图选择 [平面 / 异形破框 / 半立体 / 立体微缩]。Optional 3D structure 只在原图有清楚空间纵深时使用，并遵守真实的前景 → 中景 → 后景关系。不得为了立体效果无意义突出人物或物体。
>
> No invented objects. 不添加虚构人物、建筑、地点、标牌、天气、英文或装饰。默认不加文字；只有地点被真实确认且需要文字时，才可使用小尺寸、简洁的英文 serif / editorial typography。禁止固定添加 FUSE BEAD、YEHE PHOTO、TRAVEL IN PIXELS 或随机 slogan。
>
> 不要机械添加拍立得、明信片、邮票、胶带、树叶、花、贴纸或手写字。最终效果应像被真实拍摄的手工拼豆旅行纪念品，构图清爽、有设计感、有留白，而不是 AI 滤镜。

Required prompt constraints:

- preserve original photo
- no AI repainting
- no invented objects
- smart subject extraction
- negative space
- optional 3D structure
- 3:4 portrait
- cream background

Use this as the base prompt when an image-generation/editing tool needs explicit guidance. Replace bracketed parts with analysis from the actual uploaded photo.

> Create a 3:4 vertical travel-souvenir composition using the user's uploaded photo as the source. The upper section must use the real uploaded photograph itself, only lightly color-corrected and, if necessary, cleanly cropped for composition. Do not repaint, regenerate, replace, or invent any part of the photograph.
>
> On a warm matte cream background in the lower section, create a handcrafted fuse-bead / perler-bead artwork derived from the same scene. Preserve [PRIMARY SUBJECT], [KEY SECONDARY ELEMENTS], and the original dominant palette of [COLORS]. Simplify or omit [CLUTTER / LOW-VALUE BACKGROUND].
>
> Use [FLAT / IRREGULAR CONTOUR / SEMI-3D / 3D MINIATURE] treatment because [SPATIAL/COMPOSITIONAL REASON]. The bead piece should occupy roughly [45–70]% of the lower width and have generous negative space around it. If 3D is used, build depth only from the real scene: [FRONT LAYER] → [MID LAYER] → [BACK LAYER]. Do not create arbitrary protruding people or objects.
>
> Beads must look physically real: cylindrical plastic fuse beads, visible center holes, regular spacing, slight heat-fused joining, subtle thickness, clean tactile surfaces, soft believable contact shadows. Avoid watercolor, LEGO, generic pixel art, smooth 3D cartoon rendering, felt, or mosaic tile.
>
> Do not add postcards, leaves, tape, stamps, decorative props, slogans, signatures, or random English. [IF VERIFIED LOCATION TEXT IS REQUESTED: add only the small English location label “LOCATION”. OTHERWISE: no text.]
>
> Keep the overall composition elegant, selective, airy, and editorial. The bead work should feel like a real travel keepsake, not a full-photo pixel filter.
