---
title: "Program"
layout: "program"
type: "page"
speakers: 
  - name: Lining Yao
    url: https://www.morphingmatter.cs.cmu.edu/
    affiliation: Carnegie Mellon University
    portrait: /images/lyportrait.jpg
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
    portrait: /images/brportrait.jpg
graduateSchoolCourses:
  - title: Deep Learning on Meshes
    speakers:
      - name: Rana Hanocka
        url: https://www.cs.tau.ac.il/~hanocka/
        affiliation: Tel Aviv University
  - title: Inter-surface Mapping
    speakers:
      - name: Marcel Campen
        url: "http://graphics.cs.uos.de/"
        affiliation: "Osnabrück University"
      - name: Patrick Schmidt
        url: "https://www.graphics.rwth-aachen.de/person/232/"
        affiliation: "RWTH Aachen University"
  - title: A Quick Introduction to the Laplacian and Bilaplacian Through the Theory of Partial Differential Equations
    speakers:
      - name: Oded Stein
        url: https://odedstein.com/
        affiliation: MIT
    abstract: "In this course we will learn about the Laplacian and Bilaplacian operator, and develop mathematical tools for discussing these two popular operators in geometry processing. We will approach Laplacian and Bilaplacian from the point of view of the mathematical theory of partial differential equations and numerical analysis of finite elements. We will start with a solid mathematical foundation for the definition of Laplacian and Bilaplacian, as well as their associated partial differential equations, and discuss their solvability. Then we will discretize these operators using the finite element and mixed finite element methods, and superficially investigate their convergence. Having implemented the discrete Bilaplacian for triangle meshes, we will explore the application of this discrete operator to a variety of geometry processing problems, from smoothing and surface animation to distance computation.
After completing this course you will be able to define Laplacian and Bilaplacian as operators on Sobolev spaces, comment on their solvability, discretize them with the mixed finite element method, and know of some of the interesting applications for which the Bilaplacian can be used."
  - title: Projective dynamics/Simulation
    speakers:
      - name: Tiantian Liu
        url: https://tiantianliu.cn/
        affiliation: Microsoft Research Asia
  - title: Shape Approximation from Captured 3D Data
    speakers:
      - name: Tamy Boubekeur
        url: https://perso.telecom-paristech.fr/boubek/
        affiliation: Adobe Research
  - title: Vector/direction field processing
    speakers:
      - name: Amir Vaxman 
        url: https://webspace.science.uu.nl/~vaxma001/
        affiliation: Utrecht University
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
