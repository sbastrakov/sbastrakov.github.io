# Sergei Bastrakov
_Computational scientist and software developer based in Dresden, Germany_ <br>

[Email](mailto:sergey.bastrakov@gmail.com) / [GitHub](https://github.com/sbastrakov/) / [Google Scholar](https://scholar.google.com/citations?user=2QaTN3wAAAAJ&hl=en) / [LinkedIn](https://www.linkedin.com/in/sbastrakov/)

Researcher and C++ developer, working on advanced software for large scale plasma simulation for 10+ years.
Currently a core developer and maintainer of particle-in-cell code [PIConGPU](https://github.com/ComputationalRadiationPhysics/picongpu) preparing it to [run on world's first exascale supercomputer](https://www.olcf.ornl.gov/caar/frontier-caar/).
Very experienced in modern C++ and parallel computing including GPUs, with a solid background in math and computer science.

My professional life has so far been connected to academia and scientific computing, however mostly towards the software side.
I would self-describe the nature of my work for last 6 years as a research software engineer, though not by job title.
Now I am planning to switch to industry and looking for a job as a senior software developer or a position combining software development and research.
Open to move within Germany, would like to start in Q4 2022.
Most of my recent work is available [on GitHub](https://github.com/sbastrakov/), and a detailed job and education record is presented below.

## 👨‍💻 Scientific and Software Experience

- **Postdoctoral researcher** @ [Helmholtz-Zentrum Dresden-Rossendorf](https://www.hzdr.de/db/Cms?pNid=0) _(Jan 2018 - present)_
  - A core developer and maintainer of C++ exascale particle-in-cell code [PIConGPU](https://github.com/ComputationalRadiationPhysics/picongpu)
  - Implementing and extending core particle-in-cell routines, including state-of-the-art numerics for incident lasers and field absorbers
  - Preparing and tuning PIConGPU to [run on exascale supercomputers](https://www.olcf.ornl.gov/caar/frontier-caar/)
  - Largely contributing to [refactoring and modernization](https://github.com/ComputationalRadiationPhysics/picongpu/pulls?q=is%3Apr+author%3Asbastrakov+label%3Arefactoring) of code base and [documentation](https://github.com/ComputationalRadiationPhysics/picongpu/pulls?q=is%3Apr+author%3Asbastrakov+label%3Adocumentation)
  - Maintaining and contributing to underlying parallel programming libraries [alpaka](https://github.com/alpaka-group/alpaka) and [cupla](https://github.com/alpaka-group/cupla)
 
- **Software developer** @ [University of Nizhni Novgorod](http://eng.unn.ru/) _(March 2016 - Dec 2017)_
  - Further led development of C++ particle-in-cell code [PICADOR](http://hpc-education.unn.ru/en/research/overview/laser-plasma)
  - Oversaw code architecture, assisted other developers, co-supervised students
  - Designed performant parallel primitives for expression of core particle-in-cell operations and extensions
  - Enhanced concepts and implementation of [PIC-MDK interface for portable particle-in-cell extensions](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.92.023305), applied it for [advanced QED extensions](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.7.041003)
  - Led development of a new [kernel library for particle-in-cell simulations](https://github.com/pictools/pica) based on experience gained in PICADOR

- **Junior researcher** @ [University of Nizhni Novgorod](http://eng.unn.ru/) _(Jul 2012 - Dec 2015)_
  - Led development of particle-in-cell code [PICADOR](http://hpc-education.unn.ru/en/research/overview/laser-plasma)
  - Implemented advanced particle-in-cell numerics, including charge-conserving current deposition, incident lasers, absorbing boundaries
  - Developed a suite of integration and system tests, set up nightly builds
  - Contributed to initial design of [PIC-MDK interface for portable particle-in-cell extensions](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.92.023305), implemented it for PICADOR
  - Co-developed a [novel particle-in-cell implementation for Intel Xeon Phi](https://www.sciencedirect.com/science/article/abs/pii/S0010465516300194?via%3Dihub)

- Part-time **Assistant** @ [University of Nizhni Novgorod](http://eng.unn.ru/) _(Nov 2010 - Jun 2012)_
  - Participated in initial development of particle-in-cell code [PICADOR](http://hpc-education.unn.ru/en/research/overview/laser-plasma)
  - Largely contributed to initial design, implemented most core particle-in-cell numerics
  - Led heterogeneous implementation with OpenCL, that was [among the first published](https://www.sciencedirect.com/science/article/abs/pii/S1877750312001019) fully GPU-capable particle-in-cell codes

- **Summer school intern** @ [Intel](https://www.intel.com) _(Jul 2008 - Aug 2008; Jul 2009 - Aug 2009)_
  - Implemented and optimized basic financial math primitives for option pricing _(Jul 2008 - Aug 2008)_
  - Implemented a broad phase collision detection algorithm based on octrees _(Jul 2009 - Aug 2009)_

## 👨‍🏫 Teaching Experience

_Part-time in parallel to other job commitments, all_ @ [University of Nizhni Novgorod](http://eng.unn.ru/):

- Assisted on linear programming class as part of PhD studies _(Jan 2014 - May 2014)_
- Co-developed a suite of test problems and automatic verification system for parallel numerical methods class _(Jan 2013 - May 2014)_
- Taught algorithms and data structures for international students in English _(Sep 2013 - Dec 2017)_
- Assisted on introduction to C++ programming class for international students in English _(Sep 2012 - May 2013)_
- Textbook contributions (all in Russian):
  - Authored computational geometry chapter of a 2018 [textbook](https://www.fmllib.ru/uchebnaya-literatura/vysoproizvoditelnye-parallelnye-vychisleniya-100-zadaniy-dlya-rasshirennogo-laboratornogo-praktikuma/) on parallel programming problems
  - Authored computer arithmetic chapter of a 2013 [textbook](http://hpc-education.unn.ru/ru/%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5/%D1%83%D1%87%D0%B5%D0%B1%D0%BD%D0%B8%D0%BA%D0%B8) on parallel numerical methods
  - Co-authored CUDA chapter of a 2010 [textbook](https://msupress.com/catalogue/books/book/tekhnologii-parallelnogo-programmirovaniya-dlya-protsessorov-novykh-arkhitektur/) on programming for modern architectures

## 🏆 Accomplishments

- **Presidential scholarship** [for outstanding young scientists](https://grants.extech.ru/grants/res/winners.php?OZ=5&TZ=U&year=2016)  _(2016 - 2017)_
- **Best paper award** at Russian Supercomputing Days 2015
  - For a [performance study (in Russian)](http://www.mathnet.ru/php/archive.phtml?wshow=paper&jrnid=vmp&paperid=558&option_lang=rus) of realistic particle-in-cell applications on Xeon Phi
- **Razuvaev scholarship** for PhD students _(2013 - 2015)_
- Contributions featured **in press**:
  - *AMD* on [preparing PIConGPU for Frontier supercomputer](https://www.amd.com/system/files/documents/oak-ridge-national-laboratory-picongpu.pdf) - I am a core developer of PIConGPU and work on features needed for large-scale simulations on Frontier
  - *The register* on [100 GLOPS/s performance of PICADOR on Xeon Phi](https://www.theregister.com/2016/08/09/hot_iron_knights_landing_hits_100_gflops_in_plasma_physics_benchmark/) - I was lead developer of PICADOR and co-developed implementation for Xeon Phi
  - *R&D world* on [large-scale PICADOR simulations on Xeon Phi enabling studies of nonlinear vacuum](https://www.rdworldonline.com/particle-in-cell-plasma-simulation-using-supercomputers-enhances-computational-physics/) - I was lead developer of PICADOR and co-developed implementation for Xeon Phi, also co-developed QED-PIC extensions featured

## 💬 Languages

- **English**: Advanced, ≈ C1
- **Russian**: Native
- **German**: Beginner, ≈ A1

## 👨‍🎓 Education

- **PhD in Theoretical Computer Science** (Russian candidate of science)<br>
@ [University of Nizhni Novgorod](http://eng.unn.ru/) - Nizhni Novgorod, Russia _(Sep 2012 - Oct 2016)_
  - Was done in parallel to the jobs described above (as typical for PhD studies in Russia)
  - My PhD studies dealt with polyhedral computation in general dimension case, namely with incremental algorithms for vertex and facet enumeration to compute dual description of convex polyhedra.
  - Developed a new modification of the double description method combining it with some features of the Quickhull algorithm and obtained complexity bounds for the new algorithm.
  - Proposed an algorithmical improvement to Fourier-Motzkin elimination - a faster way of checking conditions for Chernikov rules / Imbert's acceleration theorems.
  - For a related problem of incrementally removing vertices/constraints considered a special case and proposed a new algorithm based on reverting iterations of the double description method and proved its polynomiality for this case.
  - [Thesis summary (in Russian)](https://diss.unn.ru/files/2016/614/autoref-614.pdf).

- **MSc in Applied Mathematics and Computer Science** with excellence<br>
@ [University of Nizhni Novgorod](http://eng.unn.ru/) - Nizhni Novgorod, Russia _(Sep 2010 - Jun 2012)_ <br>
  - Diploma work on implementation and properties of [general dimension Quickhull algorithm](https://www.cise.ufl.edu/~ungor/courses/fall06/papers/QuickHull.pdf)

- **BSc in Applied Mathematics and Computer Science** with excellence<br>
@ [University of Nizhni Novgorod](http://eng.unn.ru/) - Nizhni Novgorod, Russia _(Sep 2006 - Jun 2010)_ <br>
  - In 2007 - 2010 also did extracurricular studies and student projects in parallel programming @ [ITLab](http://eng.itlab.unn.ru/)

## ♟️ Hobbies

* Table tennis - recreational but passionate club player for Dresden Neustadt
* Competitive card games player in Legends of Runeterra, previously in Mythgard and Artifact
* Online chess
