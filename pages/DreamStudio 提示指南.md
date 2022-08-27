- ## Basics of Prompt Engineering
- ### A guide by   [Graverman](https://twitter.com/dailystablediff)
- Today I propose a simple formula for beginners to use and create better generations with text to image AI. This was tested on stable diffusion but it should work on any model if it was trained on enough art data.
  今天，我为初学者提出了一个简单的公式，让他们使用文本到图像AI创建更好的世代。这是在稳定扩散上测试的，但如果在足够的艺术数据上训练，它应该在任何模型上工作。
- After reading this document and applying these simple steps, you’ll be able to generate better images with the same amount of effort.
  阅读本文档并应用这些简单步骤后，您将能够以相同的工作量生成更好的图像。
- ### 1. Raw prompt 原始提示
- Raw prompt is the simplest way of describing what you want to generate, for instance;
  例如，原始提示是描述要生成的内容的最简单方法;
	- Panda
	- A warrior with a sword
	- Skeleton
- This is the basic building block of any prompt. Most new people start by only using raw prompts, this is usually a mistake as the images you generate like this tend to get random and chaotic. Here are some examples that I generated with running the earlier prompts
  这是任何提示的基本构建基块。大多数新人只使用原始提示，这通常是一个错误，因为您像这样生成的图像往往会变得随机和混乱。以下是我在运行前面的提示时生成的一些示例
- ![](https://beta.dreamstudio.ai/media/images/prompt-guide-example.png)
- As you can see, these images have random scenery and don’t look very aesthetically pleasing, I definitely wouldn’t consider them art. This brings me to my next point;
  正如你所看到的，这些图像有随机的风景，看起来不是很美观，我绝对不会认为它们是艺术。下面我要谈一谈我的下一点。
- ### 2. Style 风格
- Style is a crucial part of the prompt. The AI, when missing a specified style, usually chooses the one it has seen the most in related images, for example, if I generated landscape, it would probably generate realistic or oil painting looking images. Having a well chosen style + raw prompt is sometimes enough, as the style influences the image the most right after the raw prompt.
  风格是提示的关键部分。当缺少指定样式时，AI通常会选择它在相关图像中看到最多的样式，例如，如果我生成风景，它可能会生成逼真或油画的图像。有时，选择良好的样式 + 原始提示就足够了，因为样式在原始提示之后对图像的影响最大。
- The most commonly used styles include:
  最常用的样式包括：
	- Realistic
	- Oil painting
	- Pencil drawing
	- Concept art
- I’ll examine them one by one to give an overview on how you might use these styles.
  我将逐一检查它们，以概述如何使用这些样式。
- In the case of a realistic image, there are various ways of making it the style, most resulting in similar images. Here are some commonly used techniques of making the image realistic:
  在逼真的图像的情况下，有多种方法可以使其成为样式，大多数方法都会产生相似的图像。以下是使图像逼真的一些常用技术：
	- a photo of + raw prompt
	- a photograph of + raw prompt
	- raw prompt, hyperrealistic
	- raw prompt, realistic
- You can of course combine these to get more and more realistic images.
  当然，您可以结合这些来获得越来越逼真的图像。
- To get oil painting you can just simply add “an oil painting of” to your prompt. This sometimes results in the image showing an oil painting in a frame, to fix this you can just re-run the prompt or use raw prompt + “oil painting”
  要获得油画，您只需在提示中添加“油画”即可。这有时会导致图像在框架中显示油画，要解决此问题，您可以重新运行提示或使用原始提示+“油画”
- To make a pencil drawing just simply add “a pencil drawing of” to your raw prompt or make your prompt raw prompt + “pencil drawing”.
  要制作铅笔画，只需将“铅笔画”添加到原始提示中，或使提示原始提示+“铅笔画”即可。
- The same applies to landscape art.
  这同样适用于景观艺术。
- ### 3. Artist 艺术家
- To make your style more specific, or the image more coherent, you can use artists’ names in your prompt. For instance, if you want a very abstract image, you can add “made by Pablo Picasso” or just simply, “Picasso”.
  若要使样式更具体，或者使图像更连贯，可以在提示中使用艺术家的姓名。例如，如果你想要一个非常抽象的图像，你可以添加“由巴勃罗毕加索制作”或简单地添加“毕加索”。
- Below are lists of artists in different styles that you can use, but I always encourage you to search for different artists as it is a cool way of discovering new art.
  以下是您可以使用的不同风格的艺术家列表，但我总是鼓励您搜索不同的艺术家，因为这是发现新艺术的一种很酷的方式。
- #### Portrait 肖像
  id:: 6308a38f-3385-417c-a966-e7e8d0a92ffb
	- John Singer Sargent
	- Edgar Degas
	- Paul Cézanne
	- Jan van Eyck
- Oil painting 油画
	- Leonardo DaVinci
	- Vincent Van Gogh
	- Johannes Vermeer
	- Rembrandt
- Pencil/Pen drawing 铅笔/钢笔画
	- Albrecht Dürer
	- Leonardo da Vinci
	- Michelangelo
	- Jean-Auguste-Dominique Ingres
- Landscape art 风景艺术
	- Thomas Moran
	- Claude Monet
	- Alfred Bierstadt
	- Frederic Edwin Church
- Mixing the artists is highly encouraged, as it can lead to interesting-looking art.
  高度鼓励混合艺术家，因为它可以带来有趣的艺术。
- ### 4. Finishing touches 最后的润色
- This is the part that some people take to extremes, leading to longer prompts than this article. Finishing touches are the final things that you add to your prompt to make it look like you want. For instance, if you want to make your image more artistic, add “trending on artstation”. If you want to add more realistic lighting add “Unreal Engine.” You can add anything you want, but here are some examples:
  这是一些人采取极端措施的部分，导致比本文更长的提示。最后润色是添加到提示中以使其看起来像您想要的那样的最后内容。例如，如果您想使图像更具艺术性，请添加“artstation上的趋势”。如果您想添加更多逼真的光照，请添加“虚幻引擎”。您可以添加任何您想要的内容，但以下是一些示例：
- Highly detailed, surrealism, trending on art station, triadic color scheme, smooth, sharp focus, matte, elegant, the most beautiful image ever seen, illustration, digital paint, dark, gloomy, octane render, 8k, 4k, washed colors, sharp, dramatic lighting, beautiful, post processing, picture of the day, ambient lighting, epic composition
  id:: 6308a38f-8ee5-4841-86d6-6742b96524cb
  高度详细， 超现实主义， 艺术站趋势， 三元配色方案， 平滑， 清晰的焦点， 哑光， 优雅， 有史以来最美丽的图像， 插图， 数字油漆， 黑暗， 阴郁， 辛烷值渲染， 8k， 4k， 水洗的颜色， 锐利， 戏剧性的照明， 美丽， 后期处理， 当天的图片， 环境照明， 史诗般的构图
- ### 5. Conclusion 结论
- Prompt engineering allows you to have better control of what the image will look like. It (if done right) improves the image quality by a lot in every aspect. If you enjoyed this “article”, well, I’m glad I didn’t waste my time. If you see any ways that I can improve this, definitely let me know on discord (Graverman#0804)
  提示工程使您能够更好地控制图像的外观。它（如果做得好）在各个方面都大大提高了图像质量。如果你喜欢这篇“文章”，好吧，我很高兴我没有浪费时间。如果你看到任何我可以改善这一点的方法，一定要让我知道不和谐
- *From the DreamStudio team: "Thanks Graverman!"*