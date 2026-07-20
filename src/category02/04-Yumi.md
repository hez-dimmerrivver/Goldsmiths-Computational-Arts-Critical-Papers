---
title: The_Unarchivable
name: Yuxin Zhang
---

<div class="chapter-two">

##### Yuxin Zhang

# The_Unarchivable

## In the fold between Living and Machine Time

<div class= "body-text">

To most passers-by, pigeons appear almost identical. They belong to the familiar background of the city: birds gathering on pavements, rooftops and window ledges, visible almost everywhere but rarely noticed as individuals. The_Unarchivable began by interrupting this habitual form of attention. What does it mean for a life to be individually recognised by a system built to classify and generalise? Is this a question of how notions of identity become embedded within recognition systems or how algorithmic abstraction reflects a human image of the subject? More simply, is it an attempt to test the limits of the algorithm itself? It centred on Huihui and Diandian, two homing pigeons raised by the artist. Although they lived under human care and had individual names and histories, their appearance closely resembled that of the anonymous pigeons encountered across the city. Their position therefore remained uncertain: they were intimate and familiar lives, yet they also belonged visually to a population often treated as an interchangeable urban background.

The project asked whether technologies normally associated with classification, surveillance and identification could be redirected towards overlooked non-human life. Instead of detecting only the general category “pigeon,” could a machine-vision system learn to recognise Huihui and Diandian as separate individuals? Could this process create a space in which non-human life became visible, recordable and open to broader discussion?

<img src ="/static/images/Yumi/image1.png">
Photographs and videos of the two pigeons were selected, cropped, organised and labelled to form a bespoke dataset. A YOLO object-detection model was then trained to distinguish Huihui, Diandian and other pigeons. YOLO frames object detection as a regression problem in which a neural network predicts bounding boxes and associated class probabilities from an image (Redmon and others 2016, 779–80). It does not encounter a bird as a living subject. Instead, the image is processed as numerical input and translated into coordinates, class labels and confidence values. Crucially, YOLO is designed to register the presence of a class rather than the identity of an individual: it can report that a pigeon, or a human, is present, but not that this particular bird is Huihui or that this particular person is a named subject. This distinction matters because it exposes an asymmetry in how such technologies have been developed. Considerable engineering effort has produced systems that identify human individuals with high precision — face recognition, skeletal pose estimation, biometric tracking — yet no comparable apparatus exists for recognising non-human animals as individuals; machine vision typically distinguishes species categories, not the single creature.

<img src="/static/images/Yumi/image2.png" class="single-column-img">

<br></br>
<br></br>
<br></br>

This gap reflects a hierarchy in the distribution of computational attention. The Unarchivable works precisely within it, redirecting a category detector towards the individuation of two specific lives.

Recognition is therefore produced through abstraction. Visual differences are transformed into measurable features and compared with the categories established during training. As Trevor Paglen argues, machine-readable images increasingly operate through classifications, training sets and mathematical abstractions rather than through forms of vision addressed primarily to human spectators (Paglen 2016). What appears through the interface as the recognition of a stable object is consequently the visible result of a series of computational operations.

This process reveals the double function of classification. Classification can reduce a complex life to a limited category that a technical system is able to process. Yet in _The Unarchivable_, it also created an opportunity. What the project pursued, in this sense, was the individuality of non-human life — a status rarely granted to animals, with the partial exception of pets. The model was not asked simply to detect “a pigeon.” Huihui and Diandian entered the dataset as separate classes, requiring their differences to become computationally meaningful. By separating them from the general category of pigeon, the project attempted to interrupt the anonymity imposed on urban non-human life and to grant them a form of individuality usually reserved for humans or the animals closest to human domestic life.

The trained model operated as a speculative form of digital identification. A technology commonly used to locate and categorise objects was redirected towards two lives usually excluded from individual records. In this sense, machine vision became not only a tool of detection but also a method of sustained attention.

Yet this attention remained conditional. Huihui and Diandian could be recognised only through the photographs selected for the dataset, the labels assigned to them and the visual patterns learned from those examples. The model did not discover their identities independently. It produced them computationally through the conditions constructed by the dataset. When their bodies no longer corresponded closely enough to these learned patterns—because of rapid movement, overlap, occlusion or changes in silhouette—the stability of recognition began to break down.

<img src="/static/images/Yumi/image3.jpg" class="single-column-img">

_Learning to Fold_ developed from this contradiction rather than from a rejection of the earlier project. The two works form reciprocal moments within the same investigation. _The Unarchivable_ asks what machine recognition can make visible; _Learning to Fold_ examines the conditions under which that visibility becomes unstable. The technology that grants an individual position to the bird also reveals its limits when the body can nolonger be maintained as a coherent and readable object.
During the first project, detection was repeatedly disrupted when the pigeons moved rapidly, overlapped with one another or entered visually complex environments. Bounding boxes flickered, shifted, multiplied or disappeared. _Learning to Fold_ isolates one recurring source of this instability: the folding and unfolding of a pigeon’s wing. The same YOLO object-detection framework was used to examine how rapid transformation, self-occlusion and changing silhouettes affected computational recognition.

The project distinguishes embodied seeing from computational abstraction and classification. Embodied seeing involves an encounter situated within a perceptual and meaningful world. Computational abstraction, by contrast, translates visual variation into quantifiable features, while classification assigns those features to predefined categories. Machine recognition combines the latter operations, even though its interface often presents the outcome as though the machine had directly perceived a stable object (Paglen 2016). This contrast can be stated more directly. Embodied seeing unfolds as a temporal continuum — a duration in which perception and its object change together over time — whereas the computational paradigm identifies the living body with a static, fixed image, a discrete instant abstracted from the flow of time. The failure that follows is therefore not merely a matter of insufficient computing power. It is built into a paradigm that treats a life as though it were static, and it is for this reason that the paradigm can never fully capture a body that is, in its nature, continuous.

The project develops the term _algorithmic disorientation_ to describe moments when this calculation cannot be maintained consistently across successive frames. “Disorientation” does not imply that the algorithm is conscious, confused or capable of subjective experience. Rather, it names an operational condition in which the system loses the spatial and temporal consistency necessary to produce the appearance of one coherent object moving through time. The calculations continue, but bounding boxes compete for position, confidence values fall, and the detected object may fragment into several uncertain presences.

<img src="/static/images/Yumi/image4.png" class="single-column-img">

Since it was above all the wing’s folding, a flexible, hinge-like skeletal movement that repeatedly triggered this disorientation, isolating that movement from the rest of the living bird offered a way to examine it directly. To investigate this condition, _Learning to Fold_ moves away from the complete and alive pigeon and focuses on a custom-built skeletal wing structure. The structure abstracts the wing into hinges, extensions and folding relations, allowing selected movements to be repeated under more controlled conditions. It does not claim to reproduce pigeon anatomy. Instead, it functions as an experimental device for testing folding, vibration, acceleration, concealment and changes in outline.
These episodes of _algorithmic disorientation_ cannot be attributed to one cause. Within the experiments, folding produced overlap and concealed previously visible features. Speed introduced motion blur and greater visual differences between consecutive frames. Lighting, camera frame rate, object scale, processing latency and the limits of the training data also affected the model’s outputs. The project therefore does not claim that pigeon wings are intrinsically or permanently beyond computation. Improved cameras, larger datasets, faster hardware or different model architectures might reduce many of these errors. What matters is not the appearance of the wing, but its duration: the temporary interval in which the system used in the project cannot stabilise the moving body as a continuous computational identity.

Henri Bergson’s concept of duration helps to frame this interval. Bergson distinguishes lived duration from spatialised models of time that divide movement into separate and measurable units. In duration, successive moments do not exist as isolated points but flow into and transform one another (Bergson 2001, 100–06). Object detection, by contrast, samples movement through separate frames and reconstructs continuity from a sequence of individual predictions. Flickering and multiplying boxes expose moments when this reconstruction no longer appears seamless. The wing continues moving, but the model’s account of it becomes discontinuous. Bergson gives this partiality an optical figure. The mind, he suggests, refracts the continuous flow of duration into separate, spatialised units, pausing it, dividing it and giving each division a name (Bergson 1911, 242). Refraction is the bending of light as it passes between media of different densities, and what the bent ray delivers is not the object as it is, but a version of it, angled by the medium it has crossed, so that no single lens ever returns reality whole. The machine is one more such medium. It refracts the moving body into discrete, classifiable frames, and what it captures is therefore always a version of the pigeon, coherent within its own paradigm yet never continuous with the living duration from which it is cut.

</div>
<img src ="/static/images/Yumi/image5.png">
<br></br>
<div class= "body-text">
Building on these ideas, the project develops the term _temporal opacity_. Édouard Glissant’s right to opacity challenges the assumption that difference must become fully transparent or comprehensible in order to enter into relation. Opacity does not simply mean invisibility, isolation or withdrawal. It protects that which cannot be entirely reduced to the terms through which another person or system seeks to understand it (Glissant 1997, 189–94).

Zach Blas extends this concern into computational culture through the concept of _informatic opacity_. Blas examines opacity in relation to systems that convert identity, difference and behaviour into readable and classifiable information (Blas 2018, 197–99). His account is particularly relevant to technologies whose operation depends on rendering bodies computationally legible.

_Temporal opacity_ is not a term borrowed directly from either Glissant or Blas. Rather, it is developed through their work to describe unstable legibility across successive moments of object detection. The shift is deliberate: where Glissant claims opacity as an ethical right asserted against a colonial and capitalist drive towards total transparency, temporal opacity relocates opacity into the register of time, naming the mismatch between a body that endures continuously and a system that can only sample it in separate instants. _Learning to Fold_ brings opacity into the temporal
operation of machine vision. The wing is detected in one frame, lost in another and multiplied in the next. Its presence is not absent, but unevenly legible.

_Temporal opacity_ therefore does not prove that life will always exceed technology, nor does it turn the pigeon into a conscious political resistor. It describes a provisional condition produced through the relationship between a moving body, a camera, a dataset and an object-detection model. While this instability lasts, the bird remains visibly present without being fully maintained as one stable computational object.

Together, the two projects position recognition and opacity not as simple opposites, but as two conditions within the same encounter between machine vision and non-human life. Recognition can interrupt indifference and bring an overlooked life into attention. Yet complete legibility may also reduce that life to the categories through which a system is able to recognise it.

More powerful hardware, faster cameras, larger datasets or different detection models may eventually reduce, or even remove, many of the failures observed in the project. Yet the time held inside

the computer is not the time in which the pigeon lives. The machine proceeds by cutting continuous movement into frames at a fixed rate, but between one frame and the next there is always an instant too fine to be divided, and in that uncountable moment the living body slips past capture, like a fine fold in time. The bird does not leave the technological system. Instead, its movement opens a fold within recognition itself: a moment in which it remains present, but not fully resolved.

</div>

<div class="divider"></div>

<div class="endnote-container">

#### **End Notes**

- Bergson, Henri (1911), _Matter and Memory_, trans. by N. M. Paul and W. S. Palmer (London: George Allen & Unwin)
- Bergson, Henri (2001), _Time and Free Will: An Essay on the Immediate Data of Consciousness_, trans. by F. L. Pogson (Mineola, NY: Dover Publications)
- Blas, Zach (2018), 'Informatic Opacity', in _Posthuman Glossary_, ed. by Rosi Braidotti and Maria Hlavajova (London: Bloomsbury Academic), 197–99
- Glissant, Édouard (1997), _Poetics of Relation_, trans. by Betsy Wing (Ann Arbor: University of Michigan Press)
- Paglen, Trevor (2016), 'Invisible Images (Your Pictures Are Looking at You)', _The New Inquiry_, 8 December, [](https://thenewinquiry.com/invisible-images-your-pictures-are-looking-at-you/) [accessed 5 July 2026]
- Redmon, Joseph, and others (2016), 'You Only Look Once: Unified, Real-Time Object Detection', _Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition_ (IEEE), 779–88, [](https://doi.org/10.1109/CVPR.2016.91)

</div>

<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
<img src="/static/images/Yumi/image6.png">
