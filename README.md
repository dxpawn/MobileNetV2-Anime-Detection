# Enhanced Attention-Based Classification of Human-Created vs AI-Generated Anime Images Using MobileNetV2

> [72hr Speedrun] Using deep learning to classify real vs. AI-generated anime images, achieving **97.28% accuracy** with attention-enhanced MobileNetV2.  
> Final term report for the Machine Learning course at VNU-UET, June 2025.

---

## 🧠 Abstract

The proliferation of AI-generated anime images presents significant challenges for online platforms, artists, and consumers. In this paper, we address the problem of distinguishing between **human-created** and **AI-generated** anime images using deep learning techniques.

We present a novel approach that enhances the **MobileNetV2** architecture with **channel attention mechanisms** and **optimized test-time augmentation**.

- **Dataset**: 5,700 balanced images  
  - 2,850 human-created  
  - 2,850 AI-generated  
- **Accuracy**: **97.28%**
- **F1-score**: **97.29%**
- **Architecture**: Lightweight, attention-augmented MobileNetV2
- **Strengths**:
  - Captures subtle artistic differences
  - Resource-efficient; suitable for deployment
  - Outperforms previous state-of-the-art methods

Our results show that strategic architectural enhancements and inference-time techniques can significantly improve performance **without increasing model complexity**. This contributes to the growing field of AI-generated content detection and provides tools for **protecting human artistic expression**.

---

## 💥 VeryDeepQuote™

> _"If a machine can paint a thousand masterpieces in an hour, yet has never felt the anguish of creation or the joy of inspiration, can its output truly be called art? Does the soul manifest not in the final work, but in the struggle to create it?"_

---

## 📝 Notes

- No detailed `README.md` provided — because you can just read the full paper.
- But hey, thanks for checking this out. ❤️
- ~Uploading to arXiv is a hassle, I will try that in the near future~ -> Got rejected by arXiv (probably cuz it's a course project 😂)
- If I want to get accepted, I'd probably have to add the "other parts" in + condense paper down to 8 pages - nah, too much work -> Just enjoy the current status quo <3
- Plus I can't find a free anonymous filehoster to host my 7.5GB dataset... so you gotta wait on that (Zenodo doesn't recognize my ORCID, Terminal.LC is closed, I am finding more options)
  
VGhlcmUncyBhIGhpZGRlbiBtZXNzYWdlIHNvbWV3aGVyZS4uLg== ❓

<!-- You know, if only my instructor gave me this assignment for 10 weeks instead of 2, I would've done a much better job...
Imagine having to finish 4 deadlines of 4 different courses in that 2 weeks...
So yea, really sorry if you find my project shoddy 😭
What I would've done if I had more time (and a more... permissive environment):
- Much bigger dataset: At least 100k images is necessary 
- Much more selective dataset: Handpicked and curated specifically to my tastes
- Much more diverse AI images: Would've taken the most non-distinguishable images from Stable Diffusion and all that magic shit - Currently all the AI images I possess is NSFW or too risque to be in an academic setting, that's why I chose thisanimedoesnotexist.ai ; Of course there is still aibooru, but I wonder if the filters there are even working properly...
- Much more adaptability by including NSFW images: Hell yea we all love those, no reason to exclude them
- Much less money in my pocket: For some reason training this already took anywhere from 16-45GB of RAM. Yes, 45GB, you heard that right. So a 100k images dataset would be exponentially harder to deal with. But as long as I possess an iron will, nothing can stop me.
- Much much less money in my bank account: I'd need a big ass NVMe SSD for this. SATA may work too, but not HDDs. Imagine having to load 100k images at the speed of your grandma's dial-up internet. Nahhh...
- If you're reading this, then damn I am impressed by your curiosity. Thank you ahahah 🧡
-->
