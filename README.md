# Awesome Multibody Dynamics Simulation

A curated list of resources for multibody dynamics simulation

## Papers

### 1. Multibody Dynamics Formulation

#### Geometric Formulation

* A Recursive Multibody Dynamics and Sensitivity Algorithm for Branched Kinematic Chains (2001), G Sohl and J. Bobrow. [[pdf](http://gram.eng.uci.edu/~bobrow/papers_files/ASME_Recursive_Garett.pdf)]
* Coordinate-invariant Algorithms for Robot Dynamics (1999), S. Ploen and F. Park. [[pdf](http://robotics.snu.ac.kr/fcp/files/_pdf_files_publications/2_msd/coordinat-invariant_algorithm.pdf)]
* A Lie Group Formulation of Robot Dynamics (1995), F. Park el al. [[pdf](http://roboticslab.snu.ac.kr/fcp/files/_pdf_files_publications/2_msd/a_lie_group_formulation_of_robot_dynamics.pdf)]

#### Geometric Integration

* Geometric Integration on Euclidean Group with Application to Articulated Multibody Systems (2005), J. Park and W.-K. Chung. [[pdf](http://www.ent.mrt.ac.lk/iml/paperbase/TRO%20Collection/TRO/2005/october/7.pdf)]

#### Inverse Dynamics

* Inverse Dynamics with Rigid Contact and Friction (2017), S. Zapolsky and E. Drumwright. [[pdf](https://arxiv.org/pdf/1509.03355.pdf)]

### 2. Contact / Collision

* Posing Multibody Dynamics with Friction and Contact as a Differential Complementarity Problem (2018), D. Negrut et al. [[pdf](http://sbel.wisc.edu/documents/TR-2016-12.pdf)]
* Rigid Body Contact Problems using Proximal Operators (2017), K. Erleben. [[pdf](http://image.diku.dk/kenny/download/erleben.17a.pdf)]
* Making a Meaningful Impact: Modelling Simultaneous Frictional Collisions in Spatial Multibody Systems (2015), T. Uchida et al. [[pdf](http://rspa.royalsocietypublishing.org/content/royprsa/471/2177/20140859.full.pdf)]
* Performance of a Method for Formulating Geometrically Exact Complementarity Constraints in Multibody Dynamic Simulation (2015), D. Flickinger et al. [[pdf](https://www.researchgate.net/profile/Daniel_Flickinger/publication/274874514_Performance_of_a_Method_for_Formulating_Geometrically_Exact_Complementarity_Constraints_in_Multibody_Dynamic_Simulation/links/56b613b308ae44bb3307820a.pdf)]
* What’s Wrong with Collision Detection in Multibody Dynamics Simulation? (2013), D. Flickinger et al. [[pdf](http://twiki.cs.rpi.edu/foswiki/pub/RoboticsWeb/LabPublications/FlickingerICRA2013.pdf)]
* Modeling Contact Friction and Joint Friction in Dynamic Robotic Simulation using the Principle of Maximum Dissipation (2011), E. Drumwright and D. Shell. [[pdf](http://ai2-s2-pdfs.s3.amazonaws.com/f276/e8c072b8ff33ffbaa285af3368f756c9e062.pdf)]
* Staggered Projections for Frictional Contact in Multibody Systems (2008), D. Kaufman et al. [[pdf](https://www.researchgate.net/profile/Doug_James/publication/220183619_Staggered_Projections_for_Frictional_Contact_in_Multibody_Systems/links/09e4150e200433ec26000000.pdf)]
* Velocity-Based Shock Propagation for Multibody Dynamics Animation (2007), K. Erleben. [[pdf](https://www.researchgate.net/profile/Kenny_Erleben/publication/220184619_Velocity-based_shock_propagation_for_multibody_dynamics_animation/links/00b4953c931220d049000000.pdf)]
* An Implicit Time-Stepping Scheme for Rigid Body Dynamics with Inelastic Collisions and Coulomb Friction (1996), D. Stewart and J. Trinkle. [[pdf](http://www.cs.rpi.edu/~trink/Papers/STijnme96.pdf)]
* Impulse-based Simulation of Rigid Bodies (1995), B. Mirtich and J. Canny. [[pdf](https://pdfs.semanticscholar.org/e35b/6f409bb07dbe3407c9d6949330b903d063a8.pdf)]

#### Non-LCP based Methods

* Multi-contact Frictional Rigid Dynamics using Impulse Decomposition (2017), S. Li et al. [[pdf](https://wwwx.cs.unc.edu/~geom/papers/documents/articles/2017/LiSheng_IROS_2017.pdf)]
* Fast Frictional Dynamics for Rigid Bodies (2005), D. Kaufman et al. [[pdf](http://research.cs.rutgers.edu/~tedmunds/publications/FFD-siggraph2005.pdf)]

#### Simultaneous Contact

* All's Well That Ends Well: Guaranteed Resolution of Simultaneous Rigid Body Impact (2017), E. Vouga et al. [[pdf](http://www.cs.utexas.edu/users/evouga/uploads/4/5/6/8/45689883/term-revised.pdf)]
* Quadratic Contact Energy Model for Multi-impact Simulation (2015), T. Zhang et al. [[pdf](http://or.nsfc.gov.cn/bitstream/00001903-5/344688/1/1000014372636.pdf)]
* Reflections on Simultaneous Impact (2012), B. Smith et al. [[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.643.404&rep=rep1&type=pdf)]

#### Non-uniform Coefficient of Restitution Model

* Bounce Maps: An Improved Restitution Model for Real-Time Rigid-Body Impact (2017), J.-H. Wang et al. [[pdf](https://graphics.stanford.edu/projects/bouncemap/assets/restitution_lowres.pdf)] [[video](https://youtu.be/SL9goi6vQG4)]

### 3. Discrete Mechanics / Variational Integrators

#### Core / Overview

* General Techniques for Constructing Variational Integrators (2011), M. Leok and T. Shingel. [[pdf](https://arxiv.org/pdf/1102.2685.pdf)]
* An Overview of Variational Integrators (2003), A. Lew et al. [[pdf](https://authors.library.caltech.edu/20293/1/LeMaOrWe2004a.pdf)]
* Discrete Mechanics and Variational Integrators (2001), J. Marsden and M. West. [[pdf](https://authors.library.caltech.edu/19876/1/MaWe2001.pdf)]

#### Geometric Formulation

* Dual Quaternion Variational Integrator for Rigid Body Dynamic Simulation (2016), J. Xu and K. Halse. [[arXiv](https://arxiv.org/pdf/1611.00616.pdf)]
* Discrete Geometric Optimal Control on Lie Groups (2011), M. Kobilarov and J. Marsden. [[pdf](https://pdfs.semanticscholar.org/d294/0ce9a9bb1e569cb4ebb632e07db8d3255c08.pdf)]

#### High Order Convergence
* Surrogate Lagrangians for Variational Integrators: High Order Convergence with Low Order Schemes (20017), G. Torre and T. Murphey. [[pdf](https://arxiv.org/pdf/1709.03883.pdf)]

#### Constrained Variational Integrators

* Hamilton's Principle as Variational Inequality for Mechanical Systems with Impact (2016), R. Leine et al. [[pdf](https://hal.archives-ouvertes.fr/hal-01352880/document)]
* Study of Newton's Cradle using a New Discrete Approach (2015), A. Rodriguez and A Bowling. [[pdf](https://www.researchgate.net/profile/Adrian_Rodriguez31/publication/267490830_Study_of_the_Stick-Slip_Transition_of_Newton%27s_Cradle_With_Friction/links/57c506fe08aecd451415613a/Study-of-the-Stick-Slip-Transition-of-Newtons-Cradle-With-Friction.pdf)]
* A Propagative Model of Simultaneous Impact: Existence, Uniqueness, and Design Consequences (2014), 
V. Seghete and T. Murphey. [[pdf](https://arxiv.org/pdf/1709.02296.pdf)]
* Variational Solutions to Simultaneous Collisions between Multiple Rigid Bodies (2010), V. Seghete and T. Murphey. [[pdf](https://nxr.northwestern.edu/sites/default/files/publications/murphey-2010ICRAa.pdf)]
* Multiple Instantaneous Collisions in a Variational Framework (2009), V. Seghete and T. Murphey. [[pdf](https://nxr.northwestern.edu/sites/default/files/publications/murphey-2009CDCa.pdf)]
* Variational Collision Integrators and Optimal Control (2008), D Pekarek and J. Marsden. [[pdf](https://authors.library.caltech.edu/20571/1/PeMa2008.pdf)]
* Variational Integrators for Constrained Dynamical Systems (2008), S. Leyendecker et al. [[pdf](http://www.ltd.techfak.fau.de/Team/Leyendecker/Arxiv/Journal/leyendecker07-2.pdf)]
* Nonsmooth Lagrangian Mechanics and Variational Collision Integrators (2003), R. Fetecau et al. [[pdf](http://epubs.siam.org/doi/pdf/10.1137/S1111111102406038)]
* Time-discretized Variational Formulation of Non-smooth Frictional Contact (2002), A. Pandolfi et al. [[pdf](http://ai2-s2-pdfs.s3.amazonaws.com/d336/b0627a7f37f8e7ff1c3db3a34c0351705be3.pdf)]

#### Multibody Dynamics

* A Linear-Time Variational Integrator for Multibody Systems (2016), J. Lee et al. [[pdf](https://arxiv.org/pdf/1609.02898.pdf)]
* Scalable Variational Integrators for Constrained Mechanical Systems in Generalized Coordinates (2009), E. Johnson and T. Murphey. [[pdf](https://nxr.northwestern.edu/sites/default/files/publication-attachments/2009TROJoMu_expanded.pdf)]

#### Adaptive Time-stepping / Asynchronous Integration

* A variational approach to multirate integration for constrained systems (2013), S. Leyendecker and S. Ober-Blobaum. [[pdf](http://www.ltd.tf.fau.de/Team/Leyendecker/Arxiv/LeyendeckerOber-Bloebaum_bookchapter13.pdf)]
* Asynchronous Variational Integrators (2003), A. Lew el al. [[pdf](https://authors.library.caltech.edu/19592/1/LeMaOrWe2003.pdf)]

#### Stochastic Mechanics

* Stochastic Variational Integrators (2008), N. Bou-Rabee and H. Owhadi. [[pdf](https://arxiv.org/pdf/0708.2187.pdf)]

#### Trajectory Optimization / DMOC

* Autonomous Suspended Load Operations via Trajectory Optimization and Variational Integrators (2017), G. Torre et al. [[pdf](https://gerardodelatorredotorg.files.wordpress.com/2015/11/slung1.pdf)]
* On the Benefits of Surrogate Lagrangians in Optimal Control and Planning Algorithms (2016), G. Torre and T. Murphey. [[pdf](https://pdfs.semanticscholar.org/2f86/5363621d0a3c68a2b48c8408220023e0db00.pdf)]

#### ETC

* Modified equations for variational integrators applied to Lagrangians linear in velocities (2017), M. Vermeeren. [[pdf](https://arxiv.org/pdf/1709.09567.pdf)]
* Variational Integrators for Structure-Preserving Filtering (2016), J. Schultz et al.

### 4. Position Based Dynamics

* ADMM ⊇ Projective Dynamics: Fast Simulation of General Constitutive Models (2016), R. Narain et al. [[pdf](http://www-users.cs.umn.edu/~narain/files/admm-pd.pdf)]
* XPBD: Position-Based Simulation of Compliant Constrained Dynamics (2016), M. Macklin et al. [[pdf](http://www.matthias-mueller-fischer.ch/publications/XPBD.pdf)]
* Stable Constrained Dynamics (2015), M. Tournier et al. [[pdf](https://hal.inria.fr/hal-01157835/document)]
* Position-Based Rigid Body Dynamics (2014), C. Deul et al. [[pdf](http://onlinelibrary.wiley.com/doi/10.1002/cav.1614/full)]
* Projective Dynamics: Fusing Constraint Projections for Fast Simulation (2014), S. Bouaziz el al. [[pdf](https://repository.upenn.edu/cgi/viewcontent.cgi?referer=https://scholar.google.com/&httpsredir=1&article=1160&context=hms)]
* Position Based Dynamics (2007), M. Müller et al. [[pdf](http://matthias-mueller-fischer.ch/publications/posBasedDyn.pdf)]

### 5. Deformable Body / Granular / Fluid Simulation

* Towards Real-time Simulation of Hyperelastic Materials (2016), T. Liu et al. [[pdf](https://arxiv.org/pdf/1604.07378.pdf)]
* Interactive Constrained Dynamics for Rigid and Deformable Objects (2015), L. Vezzaro et al. [[pdf](https://iris.univr.it/retrieve/handle/11562/878222/23782/Vezzaro_et_al-2015-Computer_Animation_and_Virtual_Worlds.pdf)]

### 6. Inverse Kinematics

* FABRIK: A Fast, Iterative Solver for the Inverse Kinematics Problem (2011), A. Aristidou and J. Lasenby. [[pdf](https://s3.amazonaws.com/academia.edu.documents/35451443/FABRIK.pdf?AWSAccessKeyId=AKIAIWOWYYGZ2Y53UL3A&Expires=1514061893&Signature=6nnzM3JlrshYXYGvzvrjhAwjUZs%3D&response-content-disposition=inline%3B%20filename%3DFABRIK_A_fast_iterative_solver_for_the_I.pdf)]
* Fast Resolution of Hierarchized Inverse Kinematics with Inequality Constraints (2010), A. Escande et al. [[pdf](https://hal.inria.fr/file/index/docid/484853/filename/2010_icra_escande.pdf)]
* An Inverse Kinematic Architecture Enforcing an Arbitrary Number of Strict Priority Levels (2003), P. Baerlocher and R. Boulic. [[pdf](https://pdfs.semanticscholar.org/6db0/c8614005a3c9fb2b2524c228caf956cea5fd.pdf)]

### 7. Trajectory Optimization

* Motion Planning with Sequential Convex Optimization and Convex Collision Checking (2014), J. Schulman et al. [[pdf](https://cloudfront.escholarship.org/dist/prd/content/qt6km506db/qt6km506db.pdf)] [[more](http://rll.berkeley.edu/trajopt/ijrr/)]
* Newton-Type Algorithms for Dynamics-Based Robot Movement Optimization (2005), S.-H. Lee et al. [[pdf](https://www.cs.cmu.edu/afs/cs.cmu.edu/Web/People/junggon/publications/2005_IEEE_TRO_newton-type_algorithms.pdf)]

### 8. Applications

* SMASH: Physics-guided Reconstruction of Collisions from Videos (2017), A. Monszpart et al. [[pdf](https://arxiv.org/pdf/1603.08984.pdf)] [[video](https://youtu.be/rCZ-1yWJP2Q)]

### 9. Survey

* Interactive Simulation of Rigid Body Dynamics in Computer Graphics (2014), J. Bender et al. [[pdf](https://twiki.cs.rpi.edu/twiki/pub/RoboticsWeb/LabPublications/BETCstar_part1.pdf)]
* A Survey on Position-Based Simulation Methods in Computer Graphics (2014), J. Bender et al. [[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.491.1850&rep=rep1&type=pdf)]

## Thesis

* Discrete Mechanics and Optimal Control for Space Trajectory Design (2011), A. Moore. [[pdf](https://thesis.library.caltech.edu/6441/1/Moore_thesis.pdf)]
* Stable, Robust, and Versatile Multibody Dynamics Animation (2004), K. Erleben. [[pdf](https://www.researchgate.net/profile/Kenny_Erleben/publication/247635853_Stable_Robust_and_Versatile_Multibody_Dynamics_Animation/links/02e7e53c9330597986000000.pdf)]

## Slides / Lectures

* Multibody Dynamics Animation, K. Erleben. [[pdf](https://pdfs.semanticscholar.org/1caa/aac6ddd5ffb0a13b36b10183beaadf1adca9.pdf)]

## Thesis

* Variational Integrators (2004), M. West. [[pdf](https://thesis.library.caltech.edu/2492/1/west_thesis.pdf)]

## Books

* Modern Robotics: Mechanics, Planning, and Control (2017), K. Lynch and F. Park. [[pdf](http://hades.mech.northwestern.edu/images/7/7f/MR.pdf)]
* Numerical Methods for Linear Complementarity Problems in Physics-Based Animation (2015), S. Niebe and K. Erleben. [[pdf](http://image.diku.dk/kenny/download/erleben.13.siggraph.course.notes.pdf)]
* Guide to Dynamic Simulations of Rigid Bodeis and Particle Systems (2012), M. Coutinho. [[web](http://www.springer.com/us/book/9781447144168)]
* Rigid Body Dynamics Algorithms (2008), R. Featherstone. [[pdf](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=4&cad=rja&uact=8&ved=0ahUKEwihkeSup6DYAhUK8WMKHQwVBJ0QFghMMAM&url=ftp%3A%2F%2Fnozdr.ru%2Fbiblio%2Fkolxo3%2FP%2FPC%2FPCtm%2FFeatherstone%2520R.%2520Rigid%2520body%2520dynamics%2520algorithms%2520(Springer%2C%25202007)(ISBN%25200387743146)(280s)_PCtm_.pdf&usg=AOvVaw0jd-1HG_FFvl_mmMQLRHkg)]
* A Mathematical Introduction to Robotic Manipulation (1994), R. Murray et al. [[pdf](http://www.cds.caltech.edu/~murray/books/MLS/pdf/mls94-complete.pdf)]
* The Linear Complementarity Problem (1992), R. Cottle et al. [[web](http://epubs.siam.org/doi/abs/10.1137/1.9780898719000.bm)]

## Relevant Awesome Lists

* [Awesome Robotics (ahundt)](https://github.com/ahundt/awesome-robotics)
* [Awesome Robotics (Kiloreux)](https://github.com/Kiloreux/awesome-robotics)
* [Awesome Robotics Libraries](https://github.com/jslee02/awesome-robotics-libraries)
* [Awesome Collision Detection](https://github.com/jslee02/awesome-collision-detection)
* [Awesome Gazebo](https://github.com/fkromer/awesome-gazebo)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
