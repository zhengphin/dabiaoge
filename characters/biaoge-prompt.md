# 表哥 Biaoge — 角色提示词

参考图：`biaoge-reference.png`（单人，1080×1080），`biaoge-sheet.png`（设定图：表情、镜像、配色）。
生成时先上传参考图，再粘贴提示词，形象最一致。

## 固定特征（每次都要保留）

- 圆胖的年轻中国男人，20 多岁
- **光头，头顶只剩一根卷曲的头发**
- **巨大的圆形眼镜**，粗黑镜框，镜片把眼睛放大
- 眼皮半闭、小瞳孔，永远一脸面瘫、提不起劲
- 小圆鼻头，一字平嘴，大耳朵
- 浅灰蓝睡衣上衣，外面套**黑色绗缝羽绒马甲**
- 手里总拿着**一碗白米饭和一双木筷子**（或者一个缠着胶布的旧电视遥控器，上面有个大红键）
- 配色：皮肤 #E9B88E，阴影 #C99168，睡衣 #9AA3B5，马甲 #2A2A33，镜框/线条 #2A1F33，镜片 #E6F6FF

## 提示词 A：卡通版（和片子同风格）

**English (recommended for most image models):**

> 2D adult-animation sitcom cartoon character, thick uniform dark purple-black outlines with a slightly wobbly hand-drawn line, flat colors with hard-edged cel shadows, no gradients, no texture. A chubby, round young Chinese man in his late 20s. Completely bald round head with a single curly strand of hair sticking up on top. Huge round glasses with thick dark frames that magnify his half-closed, heavy-lidded eyes with tiny pupils — a bored, deadpan, unimpressed expression. Small round nose, small flat straight mouth, big ears. Wearing a light blue-grey pajama shirt under a black quilted puffer vest. Holding a white rice bowl in one hand and wooden chopsticks in the other. Waist-up portrait, 3/4 view, plain warm cream background. Color palette: skin #E9B88E, shadow #C99168, pajama #9AA3B5, vest #2A2A33, outline #2A1F33.

**中文：**

> 成人向情景喜剧 2D 卡通角色，粗而均匀的深紫黑色描边，线条略带手绘抖动，平涂颜色，硬边色块阴影，无渐变、无纹理。一个圆胖的二十多岁中国年轻男人，光头，头顶只翘着一根卷曲的头发；戴一副巨大的粗黑框圆眼镜，镜片放大了他半闭的、眼皮沉重的眼睛，瞳孔很小，一脸无聊、面瘫、不为所动的表情。小圆鼻子，一字平嘴，大耳朵。穿浅灰蓝色睡衣上衣，外面套黑色绗缝羽绒马甲。一手端着白米饭碗，一手拿木筷子。半身像，四分之三侧面，纯暖米色背景。

## 提示词 B：真人照片版

**English:**

> Photorealistic portrait photo of a chubby, round-faced Chinese man in his late 20s, completely shaved bald head with one single curly hair sticking up on top, wearing oversized round glasses with thick black frames, half-closed sleepy eyes and a deadpan, unimpressed expression, mouth closed in a flat line. He wears a light blue-grey pajama shirt under a black quilted puffer vest, holding a bowl of white rice and wooden chopsticks. Sitting at a Chinese New Year's Eve dinner table, red lanterns softly out of focus behind him, warm indoor lighting, 50mm lens, shallow depth of field, natural skin texture, candid sitcom still.

**中文：**

> 写实人像照片：一个圆脸微胖的二十多岁中国男人，剃光头，头顶只有一根卷曲的头发翘起来；戴着超大的粗黑框圆眼镜，眼睛半闭、睡眼惺忪，一脸面瘫、不为所动，嘴巴抿成一条直线。穿浅灰蓝睡衣，外套黑色绗缝羽绒马甲，手里端着一碗白米饭、拿着木筷子。坐在除夕年夜饭桌前，背后是虚化的红灯笼，室内暖光，50mm 镜头，浅景深，真实皮肤质感，像情景喜剧的剧照。

## 反向提示词（Negative prompt，支持的模型可以填）

> hair on head, full head of hair, thin face, small glasses, sunglasses, smiling broadly, gradients, 3D render, anime eyes, sparkly eyes, extra fingers, text, watermark

（中文：头发浓密、瘦脸、小眼镜、墨镜、大笑、渐变、3D 渲染、动漫大眼、多余手指、文字、水印）

## 换场景时只改最后一句

- 拿遥控器：`holding an old taped TV remote with a big red button labeled 回档, smirking slightly`
- 卖东西：`leaning forward like a shady salesman, holding up a gadget, one eyebrow raised`
- 震惊：`eyes wide open behind the glasses, tiny pupils, mouth open in shock`
