# awesome-holography

A curated list of resources on holographic displays, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

## Table of Contents
- Background, Theory, and Survey Papers
- Computer Generated Holography (CGH) for Coherent Light
    - Heuristic-based Methods
    - Iterative Phase Retrieval-based Methods
    - Optimization-based Methods
    - Data-driven (Learning-based) Methods
- Holographic Display Architectures and Optics
- Etendue / Eyebox Expansion

## Background, Theory, and Survey
### Background and Theory
- [Introduction to Fourier Optics](https://books.google.com.tw/books/about/Introduction_to_Fourier_Optics.html?id=QllRAAAAMAAJ&redir_esc=y) by Joseph W. Goodman is a great book to learn the basics of wave propagation and holography.

### Survey Papers
- [Toward the next-generation VR/AR optics: a review of holographic near-eye displays from a human-centric perspective](https://opg.optica.org/optica/fulltext.cfm?uri=optica-7-11-1563&id=442336) (Chang et al. 2020)
- [Deep learning in holography and coherent imaging](https://www.nature.com/articles/s41377-019-0196-0) (Rivenson et al. 2019)

## Computer Generated Holography (CGH) for Coherent Light

### Heuristic-based Methods
#### Double Phase Encoding
- [Computer-generated double-phase holograms](https://opg.optica.org/ao/abstract.cfm?uri=ao-17-24-3874) (Hsueh et al. 1978) proposed to decompose a complex field into two phase-only components to generate holograms using phase-only SLMs.
- [Holographic Near-Eye Displays for Virtual and Augmented Reality](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/holo_author.pdf) (Maimone et al. 2017) proposed a holographic near-eye display system based on the double phase encoding scheme.

#### Polygon/Mesh-based Methods
- [Computer-generated holograms of 3-D objects composed of tilted planar segments](https://opg.optica.org/ao/abstract.cfm?uri=ao-27-14-3020) (Leseberg et al. 1988)
- [Computer-generated holograms of tilted planes by a spatial frequency approach](https://opg.optica.org/josaa/ViewMedia.cfm?uri=josaa-10-2-299&seq=0&guid=37d8e19b-51f8-478e-936a-7a3c8c405b54) (Tommasi et al. 1993) 
- [Computer-generated holograms for three-dimensional surface objects with shade and texture](https://opg.optica.org/ao/abstract.cfm?uri=ao-44-22-4607) (Matsushima 2005)
- [Extremely high-definition full-parallax computer-generated hologram created by the polygon-based method](https://opg.optica.org/ao/fulltext.cfm?uri=ao-48-34-H54&id=186427) (Matsushima et al. 2009)
- [Silhouette method for hidden surface removal in computer holography and its acceleration using the switch-back technique](https://opg.optica.org/oe/fulltext.cfm?uri=oe-22-20-24450&id=301771) (Matsushima et al. 2014)
- [Computer generated holograms from three dimensional meshes using an analytic light transport model](https://opg.optica.org/ao/abstract.cfm?uri=ao-47-10-1567) (Ahrenberg et al. 2008)
- [Fast and effective occlusion culling for 3D holographic displays by inverse orthographic projection with low angular sampling](https://opg.optica.org/ao/abstract.cfm?uri=ao-53-27-6287) (Jia et al. 2014)

### Iterative Phase Retrieval-based Methods
- [A practical algorithm for the determination of phase from image and diffraction plane pictures](http://www.u.arizona.edu/~ppoon/GerchbergandSaxton1972.pdf) (Gerchberg et al. 1972) proposed the **Gerchberg-Saxton (GS) Algorithm**
- [Mix-and-Match Holography](http://www.cs.ubc.ca/labs/imager/tr/2017/MixMatchHolography/MixMatchHolography_YPeng_SA17_LowRes.pdf) (Peng et al. 2017) proposed a IPR method built upon GS
- [Fresnel ping-pong algorithm for two-plane computer-generated hologram display](https://opg.optica.org/ao/ViewMedia.cfm?uri=ao-33-5-869&seq=0&guid=cd9375f1-824e-4719-a271-624d5c09ccca&html=true) (Dorsch et al. 1994) 

### Optimization-based Methods
- [Multi-depth hologram generation using stochastic gradient descent algorithm with complex loss function](https://opg.optica.org/oe/fulltext.cfm?uri=oe-29-10-15089&id=450644) (Chen et al. 2021)
- [Wirtinger Holography for Near-Eye Displays](https://www.cs.princeton.edu/~fheide/wirtingerholography) (Chakravarthula et al. 2019) optimized the phase-only hologram using closed-form Wirtinger complex derivatives.
- [3D computer-generated holography by non-convex optimization](https://opg.optica.org/optica/fulltext.cfm?uri=optica-4-10-1306&id=375391) (Zhang et al. 2017)


### Data-driven (Learning-based) Methods
- [Neural Holography with Camera-in-the-loop Training](https://www.computationalimaging.org/publications/neuralholography/) (Peng et al. 2020)
- [Neural 3D Holography: Learning Accurate Wave Propagation Models for 3D Holographic Virtual and Augmented Reality Displays](https://www.computationalimaging.org/publications/neuralholography3d/) (Choi et al. 2021)
- [Towards real-time photorealistic 3D holography with deep neural networks](https://cdfg.mit.edu/publications/tensor-holography) (Shi et al. 2021)


- [Learned Hardware-in-the-loop Phase Retrieval for Holographic Near-Eye Displays](https://light.princeton.edu/publication/hil-holography/) (Chakravarthula et al. 2020)
- [DeepCGH: 3D computer-generated holography using deep learning](https://opg.optica.org/oe/fulltext.cfm?uri=oe-28-18-26636&id=437573) (Eybposh et al. 2020)
- [Deep neural network for multi-depth hologram generation and its training strategy](https://opg.optica.org/oe/fulltext.cfm?uri=oe-28-18-27137&id=437709) (Lee et al. 2020)
- [Deep-learning-generated holography](https://opg.optica.org/ao/abstract.cfm?uri=ao-57-14-3859) (Horisaki et al. 2018)
- [Phase recovery and holographic image reconstruction using deep learning in neural networks](https://www.nature.com/articles/lsa2017141) (Rivenson et al. 2018)

## Holographic Display Architectures and Optics
- [Speckle-free holography with partially coherent light sources and camera-in-the-loop calibration](https://www.computationalimaging.org/publications/partiallycoherentholography/) (Peng et al. 2021)
- [Optimizing image quality for holographic near-eye displays with Michelson Holography](https://opg.optica.org/optica/fulltext.cfm?uri=optica-8-2-143&id=446984) (Choi et al. 2021)
- [Holographic Optics for Thin and Lightweight Virtual Reality](https://dl.acm.org/doi/abs/10.1145/3386569.3392416) (Maimone et al. 2020)
- [Holographic display for see-through augmented reality using mirror-lens holographic optical element](https://opg.optica.org/ol/abstract.cfm?uri=ol-41-11-2486) (Li et al. 2016)
- [3D holographic head mounted display using holographic optical elements with astigmatism aberration compensation](https://opg.optica.org/oe/fulltext.cfm?uri=oe-23-25-32025&id=333174) (Yeom et al. 2015)

## Etendue / Eyebox Expansion
- [High Resolution étendue expansion for holographic displays](https://dl.acm.org/doi/abs/10.1145/3386569.3392414) (Kuo et al. 2020)
- [Holographic Near-eye Display with Expanded Eye-box](https://dl.acm.org/doi/10.1145/3272127.3275069) (Jang et al. 2018)