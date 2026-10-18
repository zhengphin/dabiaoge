# 奶奶 Nainai — 角色提示词

参考图：`nainai-reference.png`（单人，1080×1080），`nainai-sheet.png`（设定图：表情、金色回档器、镜像、配色）。
生成时先上传参考图，再粘贴提示词，形象最一致。

## 固定特征（每次都要保留）

- 矮小的中国老奶奶，八十岁左右，平时慈祥，关键时刻一锤定音
- **白发盘成头顶的圆发髻**
- **金棕色细框圆老花镜**
- 眼角、嘴角有细皱纹，小圆鼻子，常带微笑
- **枣红色中式棉袄，正中一排金色盘扣**
- 手里拿木筷子；招牌道具：**巨大的金色回档遥控器**，底部有个红色"福"字
- 配色：皮肤 #EFC8A8，阴影 #D4A886，棉袄 #8A2A2A，棉袄阴影 #661C1C，白发 #F4F1EA，盘扣 #FFCC33

## 提示词 A：卡通版（和片子同风格）

**English (recommended for most image models):**

> 2D adult-animation sitcom cartoon character, thick uniform dark purple-black outlines with a slightly wobbly hand-drawn line, flat colors with hard-edged cel shadows, no gradients, no texture. A tiny, sweet Chinese grandmother around 80 years old. White hair pulled up into a round bun on top of her head. Thin gold-brown round reading glasses, small white eyes with tiny pupils, gentle half-lidded look, little wrinkle lines at the corners of her eyes and mouth, small round nose, a soft smile. Wearing a maroon traditional Chinese padded jacket with a row of gold frog-knot buttons down the center. Holding wooden chopsticks. Waist-up portrait, 3/4 view, plain warm cream background. Color palette: skin #EFC8A8, shadow #D4A886, jacket #8A2A2A, jacket shadow #661C1C, hair #F4F1EA, buttons #FFCC33, outline #2A1F33.

**中文：**

> 成人向情景喜剧 2D 卡通角色，粗而均匀的深紫黑色描边，线条略带手绘抖动，平涂颜色，硬边色块阴影，无渐变、无纹理。一个八十岁左右、矮小慈祥的中国老奶奶。白发在头顶盘成圆发髻；戴金棕色细框圆老花镜，小白眼睛小瞳孔，眼神温和半眯，眼角和嘴角有细皱纹，小圆鼻子，淡淡微笑。穿枣红色中式棉袄，正中一排金色盘扣。手里拿着木筷子。半身像，四分之三侧面，纯暖米色背景。

## 提示词 B：真人照片版

**English:**

> Photorealistic portrait photo of a tiny, sweet Chinese grandmother around 80, white hair in a neat round bun on top of her head, thin gold-rimmed round reading glasses, gentle wrinkled smile, wearing a maroon traditional Chinese padded jacket with gold frog-knot buttons, holding wooden chopsticks. Sitting at a Chinese New Year's Eve dinner table, red lanterns softly out of focus behind her, warm indoor lighting, 50mm lens, shallow depth of field, natural skin texture, candid sitcom still.

**中文：**

> 写实人像照片：一个八十岁左右、矮小慈祥的中国老奶奶，白发在头顶盘成整齐的圆发髻，戴金色细框圆老花镜，满脸皱纹的温和笑容，穿枣红色中式棉袄，一排金色盘扣，手里拿着木筷子。坐在除夕年夜饭桌前，背后是虚化的红灯笼，室内暖光，50mm 镜头，浅景深，真实皮肤质感，像情景喜剧的剧照。

## 反向提示词（Negative prompt，支持的模型可以填）

> young woman, dark hair, loose hair, no glasses, modern clothes, gradients, 3D render, anime eyes, sparkly eyes, extra fingers, text, watermark

（中文：年轻女人、深色头发、披发、没戴眼镜、现代服装、渐变、3D 渲染、动漫大眼、多余手指、文字、水印）

## 换场景时只改最后一句

- 终结全场：`slamming the table, raising a huge golden TV remote with a red 福 character, shouting "Stop rewinding! Eat!"`
- 晕倒：`fainting sideways dramatically, eyes turned into X marks`
- 眯眼笑：`eyes closed into happy curves, laughing softly`
