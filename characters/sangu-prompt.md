# 三姑 Sangu — 角色提示词

参考图：`sangu-reference.png`（单人，1080×1080），`sangu-sheet.png`（设定图：表情、拿粉色回档器、镜像、配色）。
生成时先上传参考图，再粘贴提示词，形象最一致。

## 固定特征（每次都要保留）

- 五十岁左右的中国中年女人，热情、爱八卦、嗓门大（东北口音）
- **紫红色蓬松泡面头卷发**，额前一排小卷
- **大金色圆耳环**
- **橙黄底黑斑点的豹纹上衣**
- **大红嘴唇**，嘴角一颗黑痣
- 蓝色眼影，细眉毛，几根睫毛
- 表情总是笑眯眯，一边说话一边挥手
- 招牌道具：**镶亮钻的粉色回档遥控器**
- 配色：皮肤 #F2C6A6，卷发 #8A2A5A，豹纹 #E8A03A，斑点 #3A2414，金耳环 #FFCC33，口红 #D8203A

## 提示词 A：卡通版（和片子同风格）

**English (recommended for most image models):**

> 2D adult-animation sitcom cartoon character, thick uniform dark purple-black outlines with a slightly wobbly hand-drawn line, flat colors with hard-edged cel shadows, no gradients, no texture. A chatty, nosy Chinese auntie in her early fifties. Big fluffy magenta-purple permed curly hair with a row of tight little curls across her forehead. Large gold hoop earrings. Bright red lipstick and a small black beauty mole near the corner of her mouth. Light blue eyeshadow, thin arched eyebrows, a few eyelashes, big white eyes with small pupils. Wearing an orange-yellow leopard-print top with dark brown spots. Grinning broadly and waving one hand mid-gossip. Waist-up portrait, 3/4 view, plain warm cream background. Color palette: skin #F2C6A6, hair #8A2A5A, leopard #E8A03A, spots #3A2414, earrings #FFCC33, lipstick #D8203A, outline #2A1F33.

**中文：**

> 成人向情景喜剧 2D 卡通角色，粗而均匀的深紫黑色描边，线条略带手绘抖动，平涂颜色，硬边色块阴影，无渐变、无纹理。一个五十岁出头、爱打听、话很多的中国阿姨。紫红色蓬松泡面头卷发，额前一排小卷；戴大金色圆耳环；大红嘴唇，嘴角一颗小黑痣；淡蓝眼影，细弯眉，几根睫毛，大白眼睛小瞳孔。穿橙黄色豹纹上衣，深棕色斑点。咧嘴大笑，一只手在挥，像正说着八卦。半身像，四分之三侧面，纯暖米色背景。

## 提示词 B：真人照片版

**English:**

> Photorealistic portrait photo of a cheerful, nosy Chinese auntie in her early fifties, big voluminous magenta-purple permed curly hair with tight curls on her forehead, large gold hoop earrings, bright red lipstick, a small beauty mole near the corner of her mouth, light blue eyeshadow, thin arched eyebrows. She wears an orange-and-brown leopard-print top, grinning widely and waving one hand mid-sentence as if asking a nosy question. Sitting at a Chinese New Year's Eve dinner table, red lanterns softly out of focus behind her, warm indoor lighting, 50mm lens, shallow depth of field, natural skin texture, candid sitcom still.

**中文：**

> 写实人像照片：一个五十岁出头、热情又爱打听的中国阿姨，紫红色蓬松泡面头卷发，额前一排小卷，大金色圆耳环，大红口红，嘴角一颗小痣，淡蓝眼影，细弯眉。穿橙棕色豹纹上衣，咧嘴大笑，一只手挥着，像正在问一个八卦问题。坐在除夕年夜饭桌前，背后是虚化的红灯笼，室内暖光，50mm 镜头，浅景深，真实皮肤质感，像情景喜剧的剧照。

## 反向提示词（Negative prompt，支持的模型可以填）

> straight hair, short hair, black hair, young woman, thin lips, no earrings, plain shirt, gradients, 3D render, anime eyes, sparkly eyes, extra fingers, text, watermark

（中文：直发、短发、黑发、年轻女人、薄嘴唇、没有耳环、纯色上衣、渐变、3D 渲染、动漫大眼、多余手指、文字、水印）

## 换场景时只改最后一句

- 掏回档器：`slowly pulling out a sparkly pink rhinestone TV remote with a big red button labeled 回档, sly half-lidded smile`
- 盘问：`leaning forward with sparkling eyes, asking "how much do you earn?"`
- 冷场：`frozen fake smile, one eye twitching`
