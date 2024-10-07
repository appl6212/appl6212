- 👋 Hi, I’m @appl6212
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
from diffusers import StableDiffusionPipeline
import torch

# 加载预训练模型
pipe = StableDiffusionPipeline.from_pretrained("CompVis/stable-diffusion-v1-4", torch_dtype=torch.float16)
pipe = pipe.to("cuda")  # 如果有GPU，可以加速运算

# 定义花瓶的描述
prompt = "A vintage hand-painted ceramic vase with delicate floral patterns and faded glaze, in a classic oriental style, intricate details, slightly cracked surface, pastel colors"

<!---
appl6212/appl6212 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
