---
title: The Aphasic Manifesto
name: Yihang Zhang
---

<div class="chapter-two">

##### 張一航 Yihang Zhang

# The Aphasic Manifesto

## The Algorithm Does Not Write. It Samples.

<div class="body-text">

_沉默呵，沉默呵！不在沉默中爆發，就在沉默中滅亡。_<br>
_Silence, silence\! Unless we burst out in silence, we perish in it._<br>
— Lu Xun, In Memory of Miss Liu Hezhen (1926), translation by the author

I asked a model to write 處 (place), and it returned a shape whose outline resembled 慶 (celebration) but whose strokes matched neither—four times, without exception. I tested three text-to-image models—SD 1.5 (2022, West), FLUX.1 schnell (2024, West), GLM Image (2025, China)—on six traditional characters, and the result overturned my assumption. It is not that Western models are mute and Chinese models fluent; all of them are aphasic, and the severity is set by how often a character appears in the training data. Algorithmic aphasia keeps the topological outline of a character and destroys its stroke logic. The model does not write; it samples a visual impression from a sparse, distorted distribution. I appropriate Glissant's right to opacity (Glissant 1997\) to rename this failure as refusal: these collapsed characters are not junk but evidence of a power structure. This manifesto does not propose to fix aphasia. It lets aphasia speak.

I asked a generative model trained for Chinese to write 處, four times. Four images came back, all resembling 慶—without exception. It sampled a shape with a similar outline and far higher frequency, and handed it to me.

The six characters were not arbitrary. They are the manifesto's own line: 失語者宣言／我在此處—The Aphasic Manifesto / I Am Here. I asked the model to write my own declaration of presence, and it returned a presence that cannot be read. That sentence came back unreadable.

The experiment was simple: the same prompt and the same seeds given to three models—SD 1.5 (2022, West), FLUX.1 schnell (2024, West), and GLM Image (2025, China), specially trained for Chinese (Zhipu AI 2025)—for the six characters 失, 語, 宣, 言, 我, 處. I assumed the Western models would be mute and GLM fluent. What came back was stranger than that.

It was only after the experiment that I understood how the machine works. A diffusion model does not write a character; it learns how pixels tend to distribute when a text description appears, and it samples the cluster of pixels that best matches. Ted Chiang describes such models as a lossy compression of their training data—a blurry JPEG of the web (Chiang 2023). For Chinese characters the compression is lossier still: they are rare in the data, and often an image contains a character while its label is only English, so the model is never told what the symbol means. It fills in strokes until the texture looks convincing enough. The rarer the character, the vaguer the impression—處 is more broken than 我 because it is far rarer—and errors run toward too many strokes, the fingerprint of texture-matching rather than writing.

This raises the objection Mattia pressed on me: why use an image model at all? A language model writes 處 without ever failing, because it does not write—it retrieves a fixed code point and a font renders it. There is nothing to see there. I chose the system where writing must actually happen, pixel by pixel, because aphasia can only appear where synthesis is required. And the failure is not symmetrical. Given the same prompt and seeds, FLUX renders the English words—loss, language, place—legibly, while the six characters collapse into one shape. At the same unit of meaning, one word against one character, the alphabet survives and the hanzi does not. Twenty-six letters cover most English; each of thousands of characters must be learned alone. Even a perfectly balanced dataset would not equalise this, because the architecture already treats the complexity of the alphabet as its default. Recent computer-vision research names this exact pattern long-tail text rendering: image quality and character accuracy both fall as a character grows rarer in the data (Zhuang et al. 2025). My 處\-into-慶 is one instance of a documented law.

<img src ="/static/images/Ethan/image4.jpg" class="single-column-img">

_Fig. 1 Same model, prompt, seeds. Top: six characters, collapsed into one shape. Bottom: six matched English words, legible._

At first I assumed East versus West: Western models mute, the Chinese model fluent. The results broke that. SD 1.5 produced no single character at all—a scroll of dense, illegible marks with no character boundary. FLUX gave the shape of one character, but wrote all six as the same form, differing only in small ways. GLM, trained for Chinese, came closest: it separated the six, its strokes were more plausible—and it still failed, strangely. 失 gained extra strokes, the radical of 語 loosened, the interior of 宣 broke down. Then 處: four images, all resembling 慶, without exception.

<img src ="/static/images/Ethan/image2.jpg" class="single-column-img">

_Fig. 2 Six characters, three models. Top: SD 1.5 (West, 2022). Middle: FLUX.1 (West, 2024). Bottom: GLM Image (Chinese, 2025). One sample per character._

The model is not writing wrong; it is replacing. 處 barely appears in the data, so its impression is vague, while 慶 shares an outline and is far more frequent—so the model samples 慶. It does not know they are different characters; it knows only that a dense shape with roughly this outline belongs here. This is not a slip. It is the mechanism exposed.

My East-West binary collapsed. The variable is not which civilisation trained the model but frequency. The three models form a descending order—SD 1.5 heaviest, FLUX next, GLM lightest—without exception. As a native reader I see it at the stroke level: the outline survives, the stroke logic is gone. From a distance it looks like writing; up close it is misalignment, one stroke too many or too few. Readability dissolves with distance.

<img src ="/static/images/Ethan/image1.jpg" class="single-column-img">

_Fig. 3 Diptych: The Aphasic Manifesto / I Am Here. Left: generated English, collapsed. Right: pseudo-characters, structurally held but internally broken. Fine-tuned model, edited by the artist._

This descent is neither random nor a mere technical flaw; it is a visible register of power. Crawford argues that machine classification is never neutral—it records who holds weight in the world of data (Crawford 2021). The claim that such classification is objective is what Haraway calls the god trick: a view from nowhere that hides the position it speaks from (Haraway 1988). To stage this at small scale I trained a CNN on a deliberately skewed set, 95% Latin to 5% Chinese. It is a conceptual reenactment: the minority class is not unlearnable—it is learned late, and never quite caught up.

<img src ="/static/images/Ethan/image3.gif">

_Fig. 4 Validation accuracy per epoch. Latin (95%) mastered at once; Chinese (5%) never catches up. Conceptual reenactment._

Tsang Tsou-choi, the self-styled Kowloon Emperor, brushed his name and lineage across Hong Kong—utility boxes, road signs, walls (Tsang 1990s). The authorities cleared it as graffiti, refusing to read it as writing. My collapsed characters and his wall-names share a fate: unread by the system, one processed as graffiti, the other as noise. The algorithm does not fail to see 處; it meets an unfamiliar symbol and substitutes the nearest known one, reading 處 as 慶. In every classificatory system, marginal writing is not processed—it is overwritten.

Here I must be exact about Glissant. His right to opacity is a right claimed by a subject: the refusal to be made fully legible to colonial power. My characters are the inverse. Their opacity is not claimed but imposed—the statistics of the dataset, not the characters, made them unreadable. The model grants them visibility without readability: a shape appears, the stroke logic is gone. That is why their opacity is evidence of marginalisation, not resistance. The reversal happens in the act of naming. The characters do not resist; I resist on their behalf—by refusing to correct them, and by calling their collapse a manifesto. The right to opacity is not exercised by the characters. It is claimed by me, for them, after the fact.

One risk must be named. Xu Bing's Book from the Sky invented some four thousand non-existent characters, later absorbed by Western institutions as mysterious Eastern aesthetics (Xu 1987-91). This project courts the same fate—its collapsed characters read as intriguing Eastern signs, the aesthetic swallowing the argument. I state the political position plainly, rather than trusting the image to speak, precisely to resist that absorption.

These characters do not need to be fixed. Aphasia is not an error to correct; it is the trace a training-data power structure leaves on the image. I show the collapse not to improve the model but because the collapse is testimony. Cultural marginality settles into the loss of readability across viewing distance. From afar it looks like characters; up close, ruins. The algorithm does not write. It samples. It forgets.

**We do not fix aphasia. We let it speak.**

</div>
<div class="divider"></div>
<div class="endnote-container" class="single-column-img">

#### END NOTES

- Chiang, Ted (2023), 'ChatGPT Is a Blurry JPEG of the Web', The New Yorker, 9 February
- Crawford, Kate (2021), Atlas of AI: Power, Politics, and the Planetary Costs of Artificial Intelligence (New Haven: Yale University Press)
- Glissant, Édouard (1997), Poetics of Relation, trans. by Betsy Wing (Ann Arbor: University of Michigan Press)
- Haraway, Donna (1988), 'Situated Knowledges: The Science Question in Feminism and the Privilege of Partial Perspective', Feminist Studies 14.3, 575-599
- Lu, Xun (1926), 'In Memory of Miss Liu Hezhen' \[记念刘和珍君\], Yusi Weekly 74, 12 April
- Tsang, Tsou-choi (King of Kowloon) (1990s), Untitled \[ink on board\], M+, Hong Kong \<https://www.mplus.org.hk/en/collection/makers/tsang-tsou-choi-aka-king-of-kowloon/\> \[accessed 5 July 2026\]
- Xu, Bing (1987-91), Book from the Sky \[Tianshu\], installation, hand-printed books and scrolls of invented characters, ink on paper
- Zhuang, Shuhan, Mengqi Huang, Fengyi Fu, Nan Chen, Bohan Lei and Zhendong Mao (2025), 'HDGlyph: A Hierarchical Disentangled Glyph-Based Framework for Long-Tail Text Rendering in Diffusion Models', in Proceedings of the 33rd ACM International Conference on Multimedia (MM '25) (Dublin: ACM)
</div>
</div>
