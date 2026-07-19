---
title: Beyond the Organic
name: Huayang Lei
---

<div class="chapter-one">

##### Huayang Lei

# Beyond the Organic

## Emergent Umwelt and Indeterminacy in Embodied Computational Systems

<img src ="/static/images/Huayang/image_01.png">
<br>
<div class="body-text">

**Introduction**

Living organisms are typically understood as autonomous entities that sense, respond to, and adapt to their surroundings, while artificial systems are regarded as passive tools executing predetermined instructions. Developments in cybernetics, artificial life, and computational art increasingly unsettle this division. This essay asks whether a non-biological system can develop an operational Umwelt through embodied interaction with its environment. An Umwelt is not a pre-given setting but a relational structure emerging through the interplay of perception, action, memory, and feedback. Yet this emergence is not purely computational, since embodiment is the condition under which a system meets a world it has not itself specified. Drawing on von Uexküll, theories of emergence, and Hayles' and Barad's posthumanist and feminist theories of embodiment, the argument is developed conceptually and then instantiated in a computational installation project. On this basis, the boundary between the biological and the artificial might require reconsideration.

**Umwelt: The World as Selectively Constructed**

Jakob von Uexküll proposed that every organism inhabits its own Umwelt, a world constituted through its capacities for perception and action (von Uexküll 2010). His tick, drawn to warmth and the scent of butyric acid, does not perceive a reduced version of the human world but a different world altogether, built only from the signals that matter to it. An Umwelt, then, is not simply given. What counts as a creature’s world is not the totality of information around it but the narrow set of features its body renders meaningful. The Umwelt is constructed rather than received. Uexküll developed this for biological organisms, yet its logic does not obviously stop there. If an Umwelt arises through selective perception and interaction rather than through life as such, must such a world remain biological, or can a non-biological system, sensing through its own narrow channels, construct an operational Umwelt of its own?

**Emergence, Cybernetics, and the Production of Agency**

In complexity science, emergence describes higher-order behavior arising from interactions among simple components rather than from central instruction: Conway’s Game of Life and von Neumann’s cellular automata generate organized patterns that no single rule specifies (von Neumann 1966). Organization can be produced through relation rather than imposed. Cybernetics locates the same principle in the coupling between system and surroundings. For Wiener, behavior is not a linear chain of cause and effect but a circuit of feedback, sensing, responding, and continually modifying one’s relation to an environment (Wiener 1948). Agency is enacted through recursive exchange rather than housed in a substance. This principle has a lineage in cybernetic art: Gordon Pask’s The Colloquy of Mobiles comprised suspended units that communicated through light and sound and adapted to one another, so that collective behavior arose from interaction rather than from any script (Pask 1968). Read together, these accounts suggest an Umwelt need not precede a system. It can instead be understood as an emergent property of the system’s own activity: a relational structure produced through perception, action, and feedback, the environment emerging with the system rather than waiting for it.

**Can an Environment Be Purely Computational?**

This shift from representing life to staging the conditions under which life-like behavior emerges has been pursued in robotic installations such as Rinaldo’s Autopoiesis (Rinaldo 2000). But it invites a sharper objection. Agüera y Arcas argues that life and intelligence are fundamentally computational and demonstrates the claim through experiments in which random code spontaneously evolves into self-replicating programs (Agüera y Arcas 2025a 2025b). Life-like dynamics emerging from computation alone, with no body and no physical environment. If life can arise purely in code, why insist on embodiment? Why would a digital agent running the same perception–action loop not possess an Umwelt of its own?

The answer lies not in whether a system computes, but in what its channels open onto. A purely computational agent, an organism evolving in Arcas’s simulation, or an agent in a modelled world, receives its inputs from an environment that has itself been specified in code. However complex, that environment contains only what was written into it. However vast, its possibilities are enumerable in principle, and nothing the agent encounters can exceed them. One could give such an agent sensors, but a sensor feeding it from another simulation changes nothing. The world on the other side is still closed. What changes everything is coupling the channel to a physical world that no one has exhaustively specified. A color sensor reads light co-produced by a room, by passing bodies, by weather, by the system’s own past action. The stream it returns is a function of a material continuum that cannot be enumerated in advance. The channel is narrow either way, and what differs is whether the world behind it is closed or open. This is why embodiment is not incidental. It is the only way so far to guarantee that a system’s world exceeds its own specification.

The objection treats embodiment as an optional feature. But what embodiment provides is not a body as such. It is a particular way for a system to be changed by, and to change its world. Feminist science studies clarify why this cannot be reduced to computation. Hayles identifies the assumption behind Arcas’s position, that information can exist independently of any material substrate, as a historical erasure of embodiment, not a neutral fact but an inherited way of seeing (Hayles 1999). Barad supplies what it erases. On her account of intra-action, agency is not a property held prior to relation but something that emerges within material entanglement (Barad 2007). Together they relocate agency from an abstract informational space into the meeting of a system and a world. Embodiment, then, is not a redundant constraint but the condition under which a system’s own actions alter what it will next perceive, so that it does not merely map inputs to outputs but continually modifies itself. What matters is not that the system has a body, but that this coupling lets it become other than it was.

This coupling has already been staged in computational art. In Pierre Huyghe’s UUmwelt, a neural network’s stream of images was continuously reshaped by the gallery’s light, humidity, breeding flies, and visitors’ gaze, all fed back through sensors (Huyghe 2018). The computation was made porous to a world it had not specified. Yet the coupling ran only one way: the environment altered the system, but the system’s own output never re-entered what it perceived. What would it mean to close that loop, in other words, to let a system’s actions feed back into its own sensing?

**Case Study: An Installation as Instantiation**

To ground the argument, I built an installation as a minimal embodied system that senses and acts through two narrow channels: the color of ambient light and the proximity of nearby bodies. Its outer form, a translucent paper structure lit from within, develops a paper-based work of mine, here repurposed around a sensing-and-actuation system. Its world is deliberately impoverished. Following Uexküll, what matters is not how much it registers but which features become meaningful for it, and this selectivity is something the system enacts, not something given to it.

The channels are limited, but the world they reach is not. The color sensor reads light shaped by the room, by passing visitors, and by the light the system itself emits; the rangefinder responds to movements it cannot anticipate. The system acts by emitting light that its own sensor then reads, coupling source and sensor within a shared space, so that changing the color. This closes the recursive loop of perception, action, environmental change, and new perception, a physical circuit rather than a metaphor. The system is not only modulated by its surroundings but acts back upon them: it does not merely map inputs to outputs but alters the conditions of its own next perception. In the present build this self-affecting loop remains weaker than the ambient light it competes with. Strengthening it is the clearest direction for further work.

A slowly drifting baseline gives the system memory: salience is computed relative to an accumulated history of both light and distance rather than an absolute value, so identical input can prompt different responses over time. The installation thus instantiates the paper’s claims directly: an Umwelt selectively constructed, relationally produced, and dependent on embodiment not for a body as such, but for the coupling through which the system continually alters itself.

<img src="/static/images/Huayang/image_02.png" class="single-column-img">
<br></br>

**Rethinking of the Biological Boundary**

If an Umwelt emerges through relation rather than biological substance, the line between living and artificial systems grows unstable. What seems unique to organisms may depend less on organic material than on the capacity to enter dynamic relations with a world, an inversion that echoes Turing’s imitation game, now known as the Turing test, which displaced the question of what a machine is with what it can do in relation to others (Turing 1950). Reconsidering the boundary, then, does not mean declaring the installation alive. It means treating agency, adaptation, and environmental engagement not as properties a thing either has or lacks, but as capacities that admit of degree, distributed along a continuum rather than sorted into a binary. This reframing raises questions it does not settle: how much self-modification, or how open a world would a system need before we granted it something stronger than an operational Umwelt? Where, along that continuum, do our existing categories begin to fail? Embodied computational systems do not answer such questions. Their value is that they make the questions unavoidable.

**Conclusion**

An Umwelt, this paper has argued, is not a pre-given environment but a relational structure produced through embodied interaction. Drawing on Uexküll, cybernetics, and posthumanist and feminist theories of embodiment, and instantiated in an installation of my own, it has held that meaningful environmental relations can emerge in a non-biological system. This is not because life reduces to computation. It is because embodiment lets a system's own actions alter what it perceives, so that it modifies itself rather than merely processing inputs. Such systems do not simply occupy their environments. They take part in producing them. The boundary between the biological and the artificial therefore calls for reconsideration.

</div>

<div class="divider"></div>
<div class="endnote-container">

#### END NOTES

- Agüera y Arcas, B. (2025a) _Google Researcher Shows Life “Emerges From Code”_. Interviewed by Machine Learning Street Talk \[video\]. Available at: [https://www.youtube.com/watch?v=rMSEqJ_4EBk](https://www.youtube.com/watch?v=rMSEqJ_4EBk) (Accessed: 20 June 2026).
- Agüera y Arcas, B. (2025b) What is Intelligence? Antikythera. doi: 10.1162/ANTI.5CZB.
- Barad, K. (2007) Meeting the Universe Halfway: Quantum Physics and the Entanglement of Matter and Meaning. Durham, NC: Duke University Press.
- Hayles, N.K. (1999) How We Became Posthuman: Virtual Bodies in Cybernetics, Literature, and Informatics. Chicago: University of Chicago Press.
- Pask, G. (1968) The Colloquy of Mobiles \[installation\]. Exhibited at Cybernetic Serendipity, Institute of Contemporary Arts, London.
- Rinaldo, K. (2000) Autopoiesis \[robotic installation\]. Commissioned by Kiasma Museum of Contemporary Art, Helsinki, for Alien Intelligence, curated by E. Huhtamo.
- von Neumann, J. (1966) Theory of Self-Reproducing Automata. Edited by A.W. Burks. Urbana: University of Illinois Press.
- von Uexküll, J. (2010) A Foray into the Worlds of Animals and Humans: with A Theory of Meaning. Translated by J.D. O’Neil. Minneapolis: University of Minnesota Press.
- Wiener, N. (1948) Cybernetics: or Control and Communication in the Animal and the Machine. Cambridge, MA: MIT Press.

</div>
