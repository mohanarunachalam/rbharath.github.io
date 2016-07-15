---
published: true
layout: post
---
Fifty years ago, the first molecular dynamics papers allowed scientists to exhaustively simulate systems with a few dozen atoms for picoseconds. Today, due to tremendous gains in computational capability from Moore's law, and due to significant gains in algorithmic sophisticiation from fifty years of research, modern scientists can simulate systems with hundreds of thousands of atoms for milliseconds at a time. Put another way, scientists today can study systems tens of thousands of times larger, for billion of times longer than they could fifty years go. The effective reach of physical simulation techniques has expanded handleable computational complexity ten-trillion fold. The scope of this achievement should not be underestimated; the advent of these techniques along with the maturation of deep-learning has permitted a host of start-ups ([1](http://www.atomwise.com/), [2](http://www.twoxar.com/), [3](http://www.cloudpharmaceuticals.com/), etc) to investigate diseases using tools that were hitherto unimaginable. 

The dramatic progress of computational methods suggests that one day scientists should be able to exhaustively understand complete human cells. But, to understand how far contemporary science is from this milestone, we first require estimates of the complexity of human cells. One [reference](http://book.bionumbers.org/how-big-is-a-human-cell/) suggests that a human sperm cell has a volume of 30 cubic micrometers, while [another](http://book.bionumbers.org/what-is-the-density-of-cells/) reveals that most human cells have densities quite similar to that of water (a thousand kilograms per cubic meter). Using the final fact that the molar mass of water is 18 grams, a quick calculation suggests that human sperm cells contain roughly a trillion atoms. For another datapoint, [assuming](http://www.sciencedirect.com/science/article/pii/S1058674183710165) neuronal cell volume of 6000 cubic micrometers, the analogous number for neurons is roughly 175 trillion atoms per cell. In addition to this increased spatial complexity, cellular processes take much longer than molecular processes, with mitosis (cell division) occurring on the order of hours. Let’s assume that mitosis takes eight hours for a standard cell. Putting together the series of calculations that we've just done suggests that exhaustively understanding a single sperm cell would require molecular simulation techniques to support an increase in spatial complexity from hundreds of thousands of atoms to trillions of atoms, and from millisecond-scale simulations to multi-hour simulations. In sum, simulations of sperm cells will require 10 million fold increases in spatial complexity and about 10 million fold increase in simulation length, for a total increase in complexity on the order of a hundred-trillion fold. Following the historical example from the previous paragraph, and assuming that Moore's law continues in some form, we are at least 50 years of hard research from achieving thorough understanding of the simplest of human cells.

Let's extend the thought experiment a bit further. How far is human science from understanding a human brain? There [are](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC2776484/) roughly a hundred-billion neurons in the brain, and human-learning occurs on the order of years. Assuming that each neuron contains 175 trillion atoms, the total brain contains roughly 2 * 10^25 atoms. To put this number in perspective, that's roughly 29 [moles](https://en.wikipedia.org/wiki/Mole_(unit)) of atoms! It follows that simulation techniques must support an increase in spatial complexity from today's limits on the order of a billion-trillion fold (20 orders of magnitude improvement). As for time complexity, there are rougly 31 million seconds in a year, so simulations would need to run tens of billions of times longer than today's millisecond computations to understand the dynamics of human learning. Combining both of these numbers, roughly 30 orders of magnitude increase in handleable total complexity is required to understand the human brain. To summarize, assuming Moore's law continues, we are at least 100 years of hard research from achieving thorough understanding of the human brain.

An important point that I've finessed in the preceding paragraphs is that both estimates above are likely low. An important, but often ignored fact about biological systems is that all nontrivial biomolecules exhibit significant quantum entanglement. The wavefunctions of biological macromolecules are quite complex, and until [recently](http://www.petachem.com/publications.html) have remained beyond the reach of even the most approximate solvers of Schrodinger's equation. As a result, most simulations of biomolecular systems use crude approximation to handle fundamental biological phenomenon such as phosphorylation or ATP processing. More accurate simulations of cells will require extremely large quantum simulations on a scale far beyond today's capabilities. We have to assume that a Moore's law for quantum computing will emerge for our estimates to have any hope of remaining accurate. However, given the extreme difficulty of maintaining large entangled states, no such progress has yet emerged from the nascent quantum computing discipline.

To summarize our discussion, simple back-of-the-envelope calculations hint at the extraordinary complexity that undergirds biological systems. Singulatarians routinely posit that it will be possible to upload our brains into the cloud within the not-too-distant future. The calculations within this article serve as a reality check upon such musings. It may well be possible to one day upload human brains into computing systems, but the computational requirements to simulate a brain (a necessary component of high-fidelity upload) are so daunting that even optimistic estimates suggest that a hundred years of hard research are required. Given that the US National Science Foundation is only [66](https://en.wikipedia.org/wiki/National_Science_Foundation#History_and_mission) years old, the difficulty of planning research programs on the century time scale becomes more apparent.

None of this is to suggest that computational investigation of biological systems is useless. On the contrary, I believe that increased use of computation is the best path forward for science to comprehend the dazzling array of biological phenomenon that support even the most pedestrian life forms. However, today's scientific environment is polluted with [AI-hype](http://smerity.com/articles/2016/ml_not_magic.html), which naively suggests that artificial intelligence can solve all hard problems in short time frames. The danger of such thinking is when learning systems run into their inevitable failures, disappointed backers will start questioning research plans and will start withdrawing funding. Cold breezes from AI-winter have already started drifting into research buildings following the tragic death of [Joshua Brown](https://www.theguardian.com/technology/2016/jun/30/tesla-autopilot-death-self-driving-car-elon-musk) in a self-driving Tesla. Scientists need to combat the spread of hype and the proliferation of naive forecasts of AI utopia in order to create the solid research plans and organizations required to bridge the gap between modern science and revolutionary advances in biology.