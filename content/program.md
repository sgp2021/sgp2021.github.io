---
title: "Program"
layout: "program"
type: "page"
speakers: 
  - name: Lining Yao
    url: https://www.morphingmatter.cs.cmu.edu/
    affiliation: Carnegie Mellon University
    portrait: /images/lyportrait.jpg
    abstract: "Morphing Matter is an interplay of geometry and hidden forces. Lining Yao, the director of Morphing Matter Lab, will share her team's experiences of computing, designing, and fabricating morphing mechanisms that leverage both geometrical and physical knowledge of materials. Lining will unfold a few marriages of geometry and forces in the talk: a conformal map interconnecting beams shrinking and fighting for the lowest entropy, a frustum-shaped groove interfering disks swelling with differential diffusion rate, and a triangulated filler path affecting spacer fabric deforming with biased shear forces. Novel morphing mechanisms and applications also come from these marriages, such as self-assembling furniture, crawling soft robots, and morphing pasta."
    title: "Computing Morphing Matter: the Marriage of Geometry and Hidden Forces"
  - name: Geoffrey Hinton
    url: https://www.cs.toronto.edu/~hinton/
    affiliation: University of Toronto/Google Research
    portrait: /images/ghportrait.jpg
    title: "How to represent part-whole hierarchies in a neural net"
    bio: "Geoffrey Hinton received his BA in Experimental Psychology from Cambridge in 1970 and his PhD in Artificial Intelligence from Edinburgh in 1978. He did postdoctoral work at Sussex University and the University of California San Diego and spent five years as a faculty member in the Computer Science department at Carnegie-Mellon University. He then became a fellow of the Canadian Institute for Advanced Research and moved to the Department of Computer Science at the University of Toronto. He spent three years from 1998 until 2001 setting up the Gatsby Computational Neuroscience Unit at University College London and then returned to the University of Toronto where he is now an emeritus distinguished professor. From 2004 until 2013 he was the director of the program on \"Neural Computation and Adaptive Perception\" which is funded by the Canadian Institute for Advanced Research. Since 2013 he has been working half-time for Google in Mountain View and Toronto. Geoffrey Hinton is a fellow of the Royal Society, the Royal Society of Canada, and the Association for the Advancement of Artificial Intelligence. He is an honorary foreign member of the American Academy of Arts and Sciences and the National Academy of Engineering, and a former president of the Cognitive Science Society. He has received honorary doctorates from the University of Edinburgh, the University of Sussex, and the University of Sherbrooke. He was awarded the first David E. Rumelhart prize (2001), the IJCAI award for research excellence (2005), the  Killam prize for Engineering (2012) , The IEEE James Clerk Maxwell Gold medal (2016), and the  NSERC Herzberg Gold Medal (2010) which is Canada's top award in Science and Engineering. Geoffrey Hinton designs machine learning algorithms. His aim is to discover a learning procedure that is efficient at finding complex structure in large, high-dimensional datasets and to show that this is how the brain learns to see. He was one of the researchers who introduced the back-propagation algorithm and the first to use backpropagation for learning word embeddings. His other contributions to neural network research include Boltzmann machines, distributed representations, time-delay neural nets, mixtures of experts, variational learning, products of experts and deep belief nets.  His research group in Toronto made major breakthroughs in deep learning that have revolutionized speech recognition and object classification."
    abstract: "I will present a single idea about representation which allows advances made by several different groups to be combined into an imaginary system called GLOM. The advances include transformers, neural fields, contrastive representation learning, distillation and capsules. GLOM answers the question: How can a neural network with a fixed architecture parse an image into a part-whole hierarchy which has a different structure for each image? The idea is simply to use islands of identical vectors to represent the nodes in the parse tree. The talk will discuss the many ramifications of this idea.  If GLOM can be made to work, it should significantly improve the interpretability of the representations produced by transformer-like systems when applied to vision or language."
  - name: Bradley Rothenberg
    url: https://www.forbes.com/sites/amyfeldman/2020/10/06/how-this-140-million-design-software-startup-uses-math-to-help-power-the-shift-to-3d-printing/?sh=380a96fb36cc
    affiliation: CEO, nTopology
    title: "Engineering-driven design: a new foundation"
    abstract: "nTopology (nTop) solves some of the most difficult problems in shape design, especially those emerging due to additive manufacturing. In doing so, nTop enables new processes for design -- it empowers engineers to design parts that are impossible with older software. To achieve these goals, we use some interesting technologies that are new to engineering software -- specifically basing our modeling tech on Signed Distance Fields (SDFs). This talk describes the new design problems that engineers today face and the software we have developed for solving them."
    portrait: /images/brportrait.jpg
graduateSchoolCourses:
  - title: Deep Learning on Meshes
    speakers:
      - name: Rana Hanocka
        url: https://www.cs.tau.ac.il/~hanocka/
        affiliation: Tel Aviv University
    abstract: "The irrefutable success of deep learning on structured data (such as images and text) has sparked significant interest in its applicability to problems in geometry processing. In this talk, we will discuss the key challenges and current solutions for using mesh convolutional neural networks on the unstructured mesh representation for problems in geometry processing. We will outline the design choices and implications of (1) learning on different mesh elements (vertices, faces, edges); (2) invariance to rigid transformations; (3) invariance and equivariance to the order of mesh elements; (4) input features, among others. We discuss existing applications of mesh convolutional neural networks, as well as potential promising future directions."
    teaser: /images/gslearning.jpg
  - title: Maps Between Surfaces
    speakers:
      - name: Marcel Campen
        url: "http://graphics.cs.uos.de/"
        affiliation: "Osnabrück University"
      - name: Patrick Schmidt
        url: "https://www.graphics.rwth-aachen.de/person/232/"
        affiliation: "RWTH Aachen University"
    abstract: "Maps between the surfaces of two or more 3D models are a core building block in many geometry processing tasks. They allow transferring data (e.g. textures, labels, annotations, animations) from one object to another, they are used to establish correspondence within a data set (e.g. for machine learning purposes), and they are required when algorithms process multiple shapes at once (e.g. in co-analysis contexts or in co-processing scenarios like compatible remeshing). In this course we dive into theoretical as well as practical aspects of such maps from a computational point of view. Our main focus will be on homeomorphisms: maps that satisfy strict continuity and bijectivity criteria. These avoid any kind of undesirable tears or folds and thus provide a well-defined foundation for reliable algorithms. In three blocks, we will learn (1) how to computationally represent maps, (2) how to initially construct valid maps, in particular homeomorphisms, and (3) how to improve their quality via continuous optimization. In each chapter, we will work our way up from the well-studied case of maps in the plane to the more challenging case of maps between discrete curved surfaces."
    teaser: /images/gsmaps.jpg
  - title: A Quick Introduction to the Laplacian and Bilaplacian Through the Theory of Partial Differential Equations
    speakers:
      - name: Oded Stein
        url: https://odedstein.com/
        affiliation: MIT
    abstract: "In this course we will learn about the Laplacian and Bilaplacian operator, and develop mathematical tools for discussing these two popular operators in geometry processing. We will approach Laplacian and Bilaplacian from the point of view of the mathematical theory of partial differential equations and numerical analysis of finite elements. We will start with a solid mathematical foundation for the definition of Laplacian and Bilaplacian, as well as their associated partial differential equations, and discuss their solvability. Then we will discretize these operators using the finite element and mixed finite element methods, and superficially investigate their convergence. Having implemented the discrete Bilaplacian for triangle meshes, we will explore the application of this discrete operator to a variety of geometry processing problems, from smoothing and surface animation to distance computation.
After completing this course you will be able to define Laplacian and Bilaplacian as operators on Sobolev spaces, comment on their solvability, discretize them with the mixed finite element method, and know of some of the interesting applications for which the Bilaplacian can be used."
    teaser: /images/gslaplacian.jpg
  - title: Projective dynamics/Simulation
    speakers:
      - name: Tiantian Liu
        url: https://tiantianliu.cn/
        affiliation: Microsoft Research Asia
    abstract: "Physically-based simulations have been used more and more in recent interactive applications. In this talk, we will cover the key ideas we have been using to accelerate our simulations,  utilizing the geometric information of the simulated objects. We will start from Projective Dynamics, an acceleration method to simulate mass-spring systems, and some simple finite element models such as the as-rigid-as-possible model. We show that Projective Dynamics can be seen as a quasi-Newton method that approximates the Hessian matrix of the elastic potential with a topological-aware Laplacian matrix. Other than assembling the Laplacian matrices, we can also use the mesh topology to propagate information throughout the entire simulated mesh. We will then show an efficient unstructured Galerkin multigrid algorithm using this idea. We summarize these strategies we used as localizing the nonlinearity and grouping the similars. During this course, we use these strategies as an example of how we use geometric information to accelerate simulations. And we look forward to seeing more geometric-based ideas in accelerated physically-based simulations."
    teaser: /images/gsdynamics.jpg
  - title: Shape Approximation from Captured 3D Data
    speakers:
      - name: Tamy Boubekeur
        url: https://perso.telecom-paristech.fr/boubek/
        affiliation: Adobe Research
  - title: Directional Field Processing
    speakers:
      - name: Amir Vaxman 
        url: https://webspace.science.uu.nl/~vaxma001/
        affiliation: Utrecht University
    teaser: /images/gsfields.png
    abstract: "Directional fields are core objects of geometry processing. They represent movement, flow, alignment, or geometric transformations. Their applications range from fluid simulation, through architectural design, to mesh generation. We will discuss the theoretical and empirical challenges in representing and discretizing directional fields on surfaces and in volumes, and some of their desired properties with relation to the applications; namely, smoothness, integrability, constrained size or symmetry, and more. We will further discuss how recent approaches optimized for these properties. Finally, we will demonstrate some of the common design paradigms for directional fields using the software library Directional."
  - title: Digital Geometry
    abstract: "Digital Geometry is about the processing of topological and geometrical objects defined in regular lattices (e.g. collection of voxels in 3d). Whereas representing quantities on regular, hierarchical or adaptive grids is a classical approach to spatially discretize a domain, processing the geometry of such objects requires us to revisit classical results from continuous or discrete mathematics. In this course, we will review tools and results that have been designed specifically to the geometry processing in Z^d. More precisely, we will present how processing regularly spaced data with integer coordinate embeddings may impact computational geometry algorithms, and how stability results (multigrid convergence) of differential quantities estimators (curvature tensor, Laplace-Beltrami,..) on boundaries of digital objects can be designed. Finally, we will present some elements of discrete calculus on digital surfaces.
Lastly, we will briefly give a demo of the DGtal library (dgtal.org) which contains a wide class of algorithms dedicated to the processing of such specific data."
    teaser: /images/gsdiscrete.jpg
    speakers: 
      - name: David Coeurjolly
        url: https://perso.liris.cnrs.fr/david.coeurjolly/
        affiliation: CNRS
      - name: Jacques-Olivier Lachaud
        url: http://www.lama.univ-savoie.fr/pagesmembres/lachaud/People/LACHAUD-JO/person.html
        affiliation: University of Savoie
  - title: "Geometric Computing with Python"
    teaser: /images/gspython.jpg
    abstract: "In this course, we present an easy-to-use Python-based workflow for applications in geometric computing and visualization. Our libraries have a shallow learning curve while also enable programmers to accomplish a wide variety of complex tasks. Furthermore, we adopt NumPy arrays as a common interface, which greatly simplifies serialization and interoperability with existing scientific computing packages. Finally, our libraries are performant, with most computations in C++ and a minimal overhead interface to Python. In addition, we present a demo on using the libraries to implement a geometry processing algorithm with ease. By the end of the course, attendees will have exposure to a set of simple, composable, and high-performance tools for geometric computing."
    speakers:
      - name: Daniele Panozzo
        url: https://cims.nyu.edu/gcl/daniele.html
        affiliation: NYU
      - name: Zhongshi Jiang
        url: https://cs.nyu.edu/~zhongshi/
        affiliation: NYU
  - title: "An Introduction to Geometry Processing Programming in MATLAB with gptoolbox"
    abstract: "It is easy and convenient to use MATLAB for research and teaching in geometry processing. In this tutorial we will teach you the very basics of geometry processing in MATLAB using the simple library gptoolbox, which implements a plethora of standard geometry processing algorithms.
We will show you how to do basic linear algebra operations in MATLAB, how to manipulate geometric objects, how to display surfaces, and how to do some popular geometry processing operations in MATLAB's powerful interactive environment."
    teaser: /images/gsmatlab.jpg
    speakers: 
      - name: Alec Jacobson
        url: http://www.cs.toronto.edu/~jacobson/
        affiliation: University of Toronto
      - name: Oded Stein
        url: https://odedstein.com/
        affiliation: MIT
      - name: Hsueh-Ti Derek Liu
        url: https://www.dgp.toronto.edu/~hsuehtil/
        affiliation: University of Toronto
      - name: Silvia Sellán
        url: http://dgp.toronto.edu/~sgsellan/
        affiliation: University of Toronto

---
