---
layout: actmfps
---

# ACT &amp; MFPS List of Talks

## Joint ACT &amp; MFPS keynote

<!-- [Andrew Pitts](https://www.cl.cam.ac.uk/~amp12/) (University of Cambridge) &mdash; _Toposes of Finitely Supported M-Sets_-->
* <details><summary><a href="https://www.cl.cam.ac.uk/~amp12/">Andrew Pitts</a> (University of Cambridge) &mdash; <a><i>Toposes of Finitely Supported M-Sets</i></a></summary>
For at least the last 25 years several toposes of finitely supported
M-sets (for various monoids M) have played an important role in my
work on logic and computer science, but in apparently unconnected
ways. I feel that this kind of topos is trying to get my attention. So
I will use this talk to tell you what they are; some of their nice
(and not so nice) properties; and a little about the contexts in which
they have arisen for me, namely the mathematics of syntax involving
binders and the semantics of univalent type theories. My hope is that
you will also find them useful, or be able to tell me something about
them that I don't know. For example, I do not know an abstract
characterisation of this class of topos. [<a href="https://oxford24.github.io/assets/slides/ACT-MFPS-2024.pdf">slides</a>]</details>


## Joint ACT &amp; MFPS special session in memory of Phil Scott

Organiser: [Rick Blute](https://www.uottawa.ca/faculty-science/professors/richard-blute) (University of Ottawa). Chair: Andrew Pitts.

* <details><summary><a href="https://www.uottawa.ca/faculty-science/professors/richard-blute">Rick Blute</a> (University of Ottawa) &mdash; <a><i>Proofs, Types and Hexagons</i></a></summary>
Phil’s book with Jim Lambek “Introduction to Higher-Order Categorical Logic” is a seminal work in category theory. It cemented in the minds of many of us working in the field the idea that the best approach to studying logical systems was to form a category whose objects are formulas and arrows are proofs of entailments. Extensions of this idea are an obsession of the categorical logic community to this day.<br>One of the most interesting extensions involves representing formulas as multivariant functors and thus proofs become dinatural transformations, the hexagons of the title. The problem/challenge that arises is that these transformations need not compose.  This has led to a great deal of interesting category theory, much of which Phil contributed to. I’ll review some of these results, especially those relating to linear logic. [<a href="https://oxford24.github.io/assets/slides/Phil-MFPS.pdf">slides</a>]</details>
* <details><summary><a href="https://www.cs.ox.ac.uk/people/samson.abramsky/">Samson Abramsky</a> (University of Oxford) &mdash; <a><i>Retracing GoI with Phil</i></a></summary>
I will describe  my collaboration with Phil Scott and Esfandiar Haghverdi on categorical semantics of Geometry of Interaction. I will say something about the context of this work, and where it led. [<a href="https://oxford24.github.io/assets/slides/retracing_PJS.pdf">slides</a>]</details>
* <details><summary><a href="http://pages.cpsc.ucalgary.ca/~robin/">Robin Cockett</a> (University of Calgary) &mdash; <a><i>Phil Scott and Occam's Razor</i></a></summary>
.In Phil's book with Lambek the authors confess they have ​"axes to grind".  One of these
is "We decry over zealous application of  Occam's razor."
Despite this, the book deploys Occam's razor to good effect in order to describe how models of the untyped lambda calculus can be derived.  The talk traces these ideas forward leading into how they influenced the speaker's work. </details>
* <details><summary><a href="https://researchportal.hw.ac.uk/en/persons/mark-lawson">Mark Lawson</a> (Heriot-Watt University) &mdash; 
<a><i>Co-ordinatizing an MV-algebra by a Boolean inverse monoid</i></a></summary>
Both MV-algebras (which arise from multiple valued logic)
and Boolean inverse monoids (which partake in a generalization of classical Stone duality)
are generalizations of Boolean algebras.
The question is: how are they related?
Phil Scott and I proved that every countable MV-algebra can be co-ordinatized
by a suitable Boolean inverse monoid (in a sense analogous to classical work by von Neumann).
I shall assume no prior exposure to MV-algebras or Boolean inverse monoids
in my talk.</details>

(Phil's obituary in the [CMS Notes](https://notes.math.ca/en/article/in-memoriam-phil-scott-1947-2023/).)

## MFPS invited speakers

* <details><summary><a href="https://bentnib.org">Bob Atkey</a> (University of Strathclyde) &mdash; <a><i>Polynomial Time and Dependent Types</i></a></summary>
 Dependent Type Theory is inherently computational. Constructions and
proofs in Type Theory are programs that can be executed to produce
results. However, all these programs and explanations are built with
no regard for computational complexity within the theory, meaning that
constructions cannot reason or rely on complexity bounds, and
arguments that rely on complexity restrictions lie outwith the grasp
of Type Theory. To address this, I will talk about combining
techniques from Implicit Computational Complexity with Dependent Type
Theory to attempt to bring resource consciousness to Type Theory. </details>
* <details><summary><a href="http://www.doc.ic.ac.uk/~pg/">Philippa Gardner</a>   (Imperial College, London, UK) &mdash; <a><i>Computational Symbolic Execution for Over-approximating and Under-approximating Reasoning</i></a></summary>
A relatively recent challenge has been to develop symbolic-execution techniques and tools that are <i>functionally</i> compositional with simple function specifications that can be used in broader calling contexts. The technical break-through came with the introduction of separation logics for reasoning about <i>partial</i> mutable state, leading to compositional symbolic execution tools being developed in academia and industry. Many of these tools have been grounded on a formal foundation, but either the function specifications are validated with respect to the underlying symbolic semantics of the engine, with no meaning outside the tool, or there is a large gulf between the theory and the implementations of the tools. In this talk, I will introduce a formal compositional symbolic execution engine which creates and uses function specifications from an underlying separation logic and provides a sound theoretical foundation for, and indeed was partially inspired by, the Gillian platform.  This is achieved by providing an <i>axiomatic interface</i> which describes the properties of the consume and produce functions for updating the symbolic state when calling function specifications, a technique used by VeriFast, Viper and Gillian but not previously characterised independently of the tool. A surprising property is that our semantics provides a common foundation for both correctness and incorrectness reasoning, with the difference in the underlying engine only amounting to the choice to use satisfiability or validity.  We use this insight to extend the Gillian platform with incorrectness reasoning, developing automatic true bug-finding using incorrectness bi-abduction, which our engine incorporates by creating fixes from missing-resource errors. We have shown that the Gillian implementation of the consumer and producer functions satisfy the properties described by our axiomatic interface, and evaluate our new Gillian platform by using the Gillian instantiation to C.  This instantiation is the first tool to support both correctness and incorrectness reasoning, as well as being grounded on a common formal compositional symbolic execution engine. (Authors: Andreas Lööw, Daniele Nantes Sobrinho, Sacha-Elie Ayoun, Caroline Cronjäger, Petar Maksimović and Philippa Gardner.)   </details>
* <details><summary><a href="https://denotational.co.uk">Ohad Kammar</a> (University of Edinburgh) &mdash; <a><i>Semantic foundations for type-driven probabilistic modelling</i></a></summary>
The last few years have seen several breakthroughs in the semantic
foundations of probabilistic and statistical modelling. Types show
clear promise in organising intricate models and the inference
algorithms we use to fit them to data. I will present a type-rich and
straightforward model, the quasi Borel space, and survey recent and
ongoing developments in this area. [<a href="https://oxford24.github.io/assets/slides/kammar-slides.pdf">slides</a>]</details>
* <details><summary><a href="http://www.lix.polytechnique.fr/~catuscia/">Catuscia Palamidessi</a> (INRIA Saclay & LIX, France) &mdash; <a><i>Information Structures for Privacy and Fairness</i></a></summary>
The increasingly pervasive use of big data and machine learning is raising various ethical issues, in particular privacy and fairness.
In this talk, I will discuss some frameworks to understand and mitigate the issues, focusing on iterative methods coming from information theory and statistics.
In the area of privacy protection, differential privacy (DP) and its variants are the most successful approaches to date. One of the fundamental issues of DP is how to reconcile the loss of information that it implies with the need to preserve the utility of the data. In this regard, a useful tool to recover utility is the Iterative Bayesian Update (IBU), an instance of the famous Expectation-Maximization method from Statistics. I will show that the IBU, combined with the metric version of DP, outperforms the state-of-the art, which is based on algebraic methods combined with the Randomized Response mechanism, widely adopted by the Big Tech industry (Google, Apple, Amazon, ...). Furthermore I will discuss a surprising duality between the IBU and one of the methods used to enhance metric DP, that is the Blahut-Arimoto algorithm from Rate-Distortion Theory. Finally, I will discuss the issue of biased decisions in machine learning, and will show that the IBU can be applied also in this domain to ensure a fairer treatment of disadvantaged groups.</details>


## MFPS special session on the semantics of non-wellfounded and circular proofs

Organisers: [Anupam Das](https://www.anupamdas.com) and [Abhishek De](https://sites.google.com/view/abhishekde) (University of Birmingham). Chair: Abishek De.

* <details><summary><a href="https://sites.google.com/site/farzadjafarrahmani/home">Farzad Jafarrahmani</a> (LMCRC, Huawei) &mdash; <a><i>Focused orthogonality as denotations of circular and non-wellfounded proofs</i></a></summary>
This talk investigates the question of denotational invariants of non-wellfounded and circular proofs of the linear logic with least and greatest fixpoints. While non-wellfounded and circular proof theory has made significant progress in the last twenty years, the corresponding denotational semantics is still underdeveloped. First, we explore a theory of fixpoint constructions in focused orthogonality categories and present a lifting theorem for initial algebras and final coalgebras. These constructions crucially hinge on the insight that focused orthogonality categories are relational fibrations. We then demonstrate that assuming a CPO structure on our category allows the focused orthogonality construction to provide a model for non-wellfounded proofs. Several properties of the semantics will be discussed, including its soundness, the relationship between totality (orthogonality) and validity, and the semantic content involved in translating finitary proofs to circular proofs. Finally, the talk focuses on circular proofs, aiming to leverage their regularity to define the interpretation function inductively. We argue why the usual validity condition is too general for this purpose, while a fragment of circular proofs—strongly valid proofs—constitutes a well-behaved class for such an inductive interpretation.</details>
* <details><summary><a href="http://gauss.cs.iit.edu/~fderakhshan/">Farzaneh Derakhshan</a> (Illinois Tech) &mdash; <a><i>Session-Typed Recursive Processes and Infinitary Proofs</i></a></summary>
Session types describe the communication behavior of interacting processes. Binary session types, in which each channel has two endpoints, corresponds to intuitionistic linear logic by a Curry-Howard interpretation of propositions as types, proofs as programs, and cut reduction as communication. This interpretation provides a solid foundation for reasoning about the behavior of session-typed processes. For example, termination of a process can be inferred from the cut elimination property of its underlying proof. However, as soon as we add recursive session types, we abandon this correspondence and lose our solid ground. From the programming perspective, it means that we can no longer exploit the cut elimination property to guarantee termination. In this talk, I show how we can revitalize the logical foundation for recursive binary session-typed processes by using infinitary proof systems for linear logic. We show that if we refine recursive types as least and greatest fixed points and impose a guard condition on recursive processes, we can still guarantee meaningful communication, ensuring that a program always terminates either in an empty configuration or one attempting to communicate along external channels.</details>
* <details><summary><a href="https://gianlucacurzi.com/">Gianluca Curzi</a> (University of Gothenburg) &mdash; <a><i>Computational aspects of cyclic and non-wellfounded proofs</i></a></summary>
Non-wellfounded proof theory studies a more permissive notion of proof seen as a possibly infinite (but finitely branching) tree structure. Cyclic proofs are special non-wellfounded proofs whose underlying tree is regular, thereby they admit a finite presentation in terms of finite (possibly cyclic) graphs. Over the years, cyclic and non-wellfounded proofs have received growing interest, especially given their capability of subsuming various forms of (co)inductive reasoning and, under a computational reading, (co)recursion mechanisms. This talk is meant to provide a bird's eye view of the state-of-the-art research around the computational analysis of cyclic and non-wellfounded proof systems, with special attention to the speaker's contribution on the topic. More specifically, the talk will examine a number of systems, spanning from those expressing complex forms of ordinal and higher-order recursion down to those implementing quickly converging recursion schemes suitable for complexity-theoretic considerations.</details>




## Contributed talks

Jump to [ACT contributed talks](#act-contributed-talks) or [MFPS contributed talks](#mfps-contributed-talks).

### ACT contributed talks

* Convergence of martingales via enriched dagger categories &mdash; <i>Paolo Perrone, Ruben Van Belle</i> [<a href='https://oxford24.github.io/assets/act-papers/27_convergence_of_martingales_via.pdf'>pdf</a>]
* The Aldous-Hoover Theorem in Categorical Probability &mdash; <i>Leihao Chen, Tobias Fritz, Tomáš Gonda, Andreas Klingler, Antonio Lorenzin</i> [<a href='https://oxford24.github.io/assets/act-papers/34_the_aldous_hoover_theorem_in_c.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/34_the_aldous_hoover_theorem.pdf'>slides</a>]
* A Category Theoretic Approach to Approximate Game Theory &mdash; <i>Neil Ghani</i> [<a href='https://oxford24.github.io/assets/act-papers/62_a_category_theoretic_approach_.pdf'>pdf</a>]
* Copy-composition for probabilistic graphical models &mdash; <i>Toby St Clere Smithe</i> [<a href='https://oxford24.github.io/assets/act-papers/35_copy_composition_for_probabili.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/slides.pdf'>slides</a>]
* Combs, Causality and Contractions in Atomic Markov Categories &mdash; <i>Dario Maximilian Stein, Márk Széles</i> [<a href='https://oxford24.github.io/assets/act-papers/47_combs_causality_and_contractio.pdf'>pdf</a>]
* Representing Knowledge and Querying Data using Double-Functorial Semantics &mdash; <i>Michael Lambert, Evan Patterson</i> [<a href='https://oxford24.github.io/assets/act-papers/22_representing_knowledge_and_que.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/ACT2024_Presentation.pdf'>slides</a>]
* Partial and Relational Algebraic Theories &mdash; <i>Chad Nester</i> [<a href='https://oxford24.github.io/assets/act-papers/26_partial_and_relational_algebra.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/26.pdf'>slides</a>]
* Fibrational perspectives on determinization of finite- state automata &mdash; <i>Thea Li</i> [<a href='https://oxford24.github.io/assets/act-papers/36_fibrational_perspectives_on_de.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/36.pdf'>slides</a>]
* Presenting Profunctors &mdash; <i>Gabriel Goren Roig, Joshua Meyers, Emilio Minichiello</i> [<a href='https://oxford24.github.io/assets/act-papers/38_presenting_profunctors.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/Goren Roig - Presenting Profunctors.pdf'>slides</a>]
* Proqueries and Praqueries &mdash; <i>Gabriel Goren Roig, Joshua Meyers, Emilio Minichiello, Ryan Wisnesky</i> [<a href='https://oxford24.github.io/assets/act-papers/42_proqueries_and_praqueries.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/ACT Pres Proqueries and Praqueries (5).pdf'>slides</a>]
* Pattern runs on matter: The free monad monad as a module over the cofree comonad comonad &mdash; <i>Sophie Libkind, David Spivak</i> [<a href='https://oxford24.github.io/assets/act-papers/63_pattern_runs_on_matter_the_fre.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/ACT2024-2.pdf'>slides</a>]
* Organizing physics with open energy-driven systems &mdash; <i>Owen Lynch, David Spivak, Matteo Capucci</i> [<a href='https://oxford24.github.io/assets/act-papers/57_organizing_physics_with_open_e.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/ACT Organizing Physics.pdf'>slides</a>]
* Compositional statistical mechanics, entropy and variational free energy &mdash; <i>Grégoire Sergeant-Perthuis</i> [<a href='https://oxford24.github.io/assets/act-papers/14_compositional_statistical_mech.pdf'>pdf</a>]
* ModelCollab: Software for Compositional Modeling &mdash; <i>John Carlos Baez, Xiaoyan Li, Nathaniel D. Osgood</i> [<a href='https://oxford24.github.io/assets/act-papers/60_modelcollab_software_for_compo.pdf'>pdf</a>]
* ViCAR: Visualizing Categories with Automated Rewriting in Coq &mdash; <i>Bhakti Shah, William Spencer, Laura Zielinski, Ben Caldwell, Adrian Lehmann, Robert Rand</i> [<a href='https://oxford24.github.io/assets/act-papers/55_vicar_visualizing_categories_w.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/ViCAR Presentation Slides.pdf'>slides</a>]
* Towards a Unified Theory of Time-Varying Data &mdash; <i>Benjamin Merlin Bumpus, James Fairbanks, Martti Karvonen, Wilmer Leal, Frédéric Simard</i> [<a href='https://oxford24.github.io/assets/act-papers/67_towards_a_unified_theory_of_ti.pdf'>pdf</a>]
* Overview of progress &mdash; <i>Adjoint School</i> [<a href=''>pdf</a>]
* Inference on poset-shaped diagrams in the category of Markov kernels &mdash; <i>Grégoire Sergeant-Perthuis, Nils Ruet</i> [<a href='https://oxford24.github.io/assets/act-papers/17_inference_on_poset_shaped_diag.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/Presentation_ACT_2_Sergeant-Perthuis.pdf'>slides</a>]
* Categorical Decision Theory &mdash; <i>Marcus Pivato</i> [<a href='https://oxford24.github.io/assets/act-papers/12_categorical_decision_theory.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/12-slides-categorical-decision-theory.pdf'>slides</a>]
* How Nice is this Functor? Two Squares and Some Homology go a Long Way &mdash; <i>Benjamin Merlin Bumpus, Daniel Rosiak, Caterina Puca, Fabrizio Romano Genovese, James Fairbanks</i> [<a href='https://oxford24.github.io/assets/act-papers/20_how_nice_is_this_functor_two_s.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/Paper20RosiakHowNiceisThisFunctor(ACT2024).pdf'>slides</a>]
* Expansion of the (category) theory of metric spaces and fuzzy simplicial sets and their applications to data analysis &mdash; <i>Lukas Barth, Jürgen Jost, Thomas Jan Mikhail, Janis Keck, Parvaneh Joharinad, Fatemeh Hannaneh Fahimi Sheyjani</i> [<a href='https://oxford24.github.io/assets/act-papers/54_talk_proposal_expansion_of_the.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/isumap.pdf'>slides</a>]
* Homotopical characterization of strong contextuality &mdash; <i>Aziz Kharoof, Cihan Okay</i> [<a href='https://oxford24.github.io/assets/act-papers/77_homotopical_characterization_o-2.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/ACT talk.pdf'>slides</a>]
* Categorified Path Calculus &mdash; <i>Simon Burton</i> [<a href='https://oxford24.github.io/assets/act-papers/64_categorified_path_calculus.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/Burton_64.pdf'>slides</a>]
* Effectful streams &mdash; <i>Filippo Bonchi, Elena Di Lavore, Mario Román</i> [<a href='https://oxford24.github.io/assets/act-papers/13_effectful_streams.pdf'>pdf</a>]
* Monoidal Streams and Probabilistic Dataflow with DisCoPy &mdash; <i>Alexis Toumi, Richie Yeung, Boldizsár Poór, Giovanni de Felice</i> [<a href='https://oxford24.github.io/assets/act-papers/46_monoidal_streams_and_probabili.pdf'>pdf</a>]
* Equivariant stochastic neural networks in Markov categories &mdash; <i>Rob Cornish</i> [<a href='https://oxford24.github.io/assets/act-papers/52_equivariant_stochastic_neural_.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/52.pdf'>slides</a>]
* Generalized Gradient Descent is a Hypergraph Functor &mdash; <i>Tyler E Hanks, Matthew Klawonn, James Fairbanks</i> [<a href='https://oxford24.github.io/assets/act-papers/41_generalized_gradient_descent_i.pdf'>pdf</a>]
* CatGrad: A Categorical Compiler for Deep Learning &mdash; <i>Paul W Wilson</i> [<a href='https://oxford24.github.io/assets/act-papers/65__textsc_catgrad_a_categorical_.pdf'>pdf</a>]
* A Convenient Topological Setting for Higher-Order Probability Theory &mdash; <i>Benedikt Peterseim</i> [<a href='https://oxford24.github.io/assets/act-papers/7_a_convenient_topological_setti.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/act_benedikt_peterseim.pdf'>slides</a>]
* No-go theorems: Polynomial comonads that do not distribute over distribution monads &mdash; <i>Nihil Shah, Amin Karamlou</i> [<a href='https://oxford24.github.io/assets/act-papers/37_no_go_theorems_polynomial_como.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/ACT.pdf'>slides</a>]
* High schoolers excel at Oxford post-graduate quantum exam: experimental evidence in support of quantum picturalism &mdash; <i>Bob Coecke, Aleks Kissinger, Stefano Gogioso, Selma Dundar- Coecke, Caterina Puca, Lia Yeh, Muhammad Hamza Waseem, Vincent Wang-Mascianica, Sieglinde Pfaendler, Thomas Cervoni, Ferdi Tomassini, Vincent Anandraj, Peter Sigrist</i> [<a href='https://oxford24.github.io/assets/act-papers/49_high_schoolers_excel_at_oxford.pdf'>pdf</a>]
* Graphical Symplectic Algebra &mdash; <i>Robert I Booth, Titouan Carette, Cole Comfort</i> [<a href='https://oxford24.github.io/assets/act-papers/28_extended_abstract_graphical_sy.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/cole_comfort_28.pdf'>slides</a>]
* Complete equational theories for classical and quantum Gaussian relations &mdash; <i>Robert I Booth, Titouan Carette, Cole Comfort</i> [<a href='https://oxford24.github.io/assets/act-papers/29_extended_abstract_complete_equ.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/cole_comfort_29.pdf'>slides</a>]
* A Profunctorial Semantics for Quantum Supermaps &mdash; <i>James Hefford, Matt Wilson</i> [<a href='https://oxford24.github.io/assets/act-papers/18_a_profunctorial_semantics_for_.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/presentation.pdf'>slides</a>]
* A Coalgebraic Model of Quantum Bisimulation &mdash; <i>Lorenzo Ceragioli, Elena Di Lavore, Giuseppe Lomurno, Gabriele Tedeschi</i> [<a href='https://oxford24.github.io/assets/act-papers/78_a_coalgebraic_model_of_quantum.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/presentazione.pdf'>slides</a>]
* Completeness of graphical languages for finite dimensional Hilbert spaces &mdash; <i>Razin A. Shaikh, Boldizsár Poór, Quanlong Wang</i> [<a href='https://oxford24.github.io/assets/act-papers/71_completeness_of_graphical_lang.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/presentaiton.pdf'>slides</a>]
* An operadic approach to convexity &mdash; <i>Redi Haderi</i> [<a href='https://oxford24.github.io/assets/act-papers/15_an_operadic_approach_to_convex.pdf'>pdf</a>]
* Universal recursive preference structures &mdash; <i>Marcus Pivato</i> [<a href='https://oxford24.github.io/assets/act-papers/10_universal_recursive_preference.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/10-slides-universal-recursive-preference-structures.pdf'>slides</a>]
* Partial Combinatory Algebras for Intensional Type Theory &mdash; <i>Sam Speight</i> [<a href='https://oxford24.github.io/assets/act-papers/4_partial_combinatory_algebras_f.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/speight-pcas-for-itt.pdf'>slides</a>]
* The Grothendieck construction for delta lenses &mdash; <i>Bryce Clarke</i> [<a href='https://oxford24.github.io/assets/act-papers/40_the_grothendieck_construction_.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/2024-06-ACT2024.pdf'>slides</a>]
* Abstract Kleisli structures on 2-categories &mdash; <i>Adrian Miranda</i> [<a href='https://oxford24.github.io/assets/act-papers/16_abstract_kleisli_structures_on.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/Abstract Kleisli Structures on 2-Categories_240616_143659 (2).pdf'>slides</a>]
* Learners are Almost Free Compact Closed &mdash; <i>Mitchell Riley</i> [<a href='https://oxford24.github.io/assets/act-papers/39_learners_are_almost_free_compa.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/39.pdf'>slides</a>]
* Monoidal Optics are Universal &mdash; <i>Matt Earnshaw, James Hefford, Mario Román</i> [<a href='https://oxford24.github.io/assets/act-papers/11_monoidal_optics_are_universal-1.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/monoidal-optics.pdf'>slides</a>]
* Reinforcement Learning in Categorical Cybernetics &mdash; <i>Jules Hedges, Riu Rodriguez Sakamoto</i> [<a href='https://oxford24.github.io/assets/act-papers/19_reinforcement_learning_in_cate.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/19_slides_handout.pdf'>slides</a>]
* A Compositional Framework for First-Order Optimization &mdash; <i>Tyler E Hanks, Matthew Klawonn, Matthew Hale, Evan Patterson, James Fairbanks</i> [<a href='https://oxford24.github.io/assets/act-papers/56_a_compositional_framework_for_.pdf'>pdf</a>]
* Reverse Faà di Bruno's Formula &mdash; <i>JS Pacaud Lemay, Aaron Biggin</i> [<a href='https://oxford24.github.io/assets/act-papers/01_reverse_fa_di_bruno_s_formula-2.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/ACT2024.pdf'>slides</a>]
* A Fully Compositional Theory of Sequential Digital Circuits &mdash; <i>George Kaye, Dan Ghica, David Sprunger</i> [<a href='https://oxford24.github.io/assets/act-papers/09_a_fully_compositional_theory_o.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/09-act-kaye.pdf'>slides</a>]
* Higher-Order DisCoCat (Peirce-Lambek-Montague semantics) &mdash; <i>Alexis Toumi, Giovanni de Felice</i> [<a href='https://oxford24.github.io/assets/act-papers/45_higher_order_discocat_peirce_l.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/higher-order-discocat.html.pdf'>slides</a>]
* Disconnection Rules are Complete for Chemical Reactions &mdash; <i>Leo Lobski, Fabio Zanasi, Ella Melissa Gale</i> [<a href='https://oxford24.github.io/assets/act-papers/44_disconnection_rules_are_comple.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/act24-pres.pdf'>slides</a>]
* Towards Compositional Interpretability for XAI &mdash; <i>Sean Tull, Robin Lorenz, Stephen Clark, Bob Coecke</i> [<a href='https://oxford24.github.io/assets/act-papers/31_towards_compositional_interpre.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/Sean Tull - Towards CI for XAI .pdf'>slides</a>]

### MFPS contributed talks

* Inferentialist Resource Semantics &mdash; <i>Alexander Gheorghiu, Tao Gu and David Pym</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-14.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/Inferentialist_Resource_Semantics (Slides).pdf'>slides</a>]
* Amortized Analysis via Coalgebra &mdash; <i>Harrison Grodin and Robert Harper</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-12.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/MFPS24-Slides-12.pdf'>slides</a>]
* On Kleisli extensions and decorated trace semantics &mdash; <i>Daniel Luckhardt, Harsh Beohar and Sebastian Küpper</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-16.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/MFPS_2024_16.pdf'>slides</a>]
* Typed Non-determinism in Concurrent Calculi: The Eager Way &mdash; <i>Bas van den Heuvel, Daniele Nantes-Sobrinho, Joseph Paulus and Jorge A — Pérez</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-9.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/MFPS24.pdf'>slides</a>]
* Linear Arboreal Categories &mdash; <i>Samson Abramsky, Yoàv Montacute and Nihil Shah</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-6.pdf'>pdf</a>]
* An Ultrametric for Cartesian Differential Categories for Taylor Series Convergence &mdash; <i>Jean-Simon Lemay</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-7.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/MFPS2024.pdf'>slides</a>]
* On a fibrational construction for optics, lenses, and Dialectica categories &mdash; <i>Matteo Capucci, Bruno Gavranovic, Abdullah Malik, Francisco Rios and Jonathan Weinberger</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-36.pdf'>pdf</a>]
* Implicit automata in λ-calculi III: affine planar string-to-string functions &mdash; <i>Cécilia Pradic and Ian Price</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-20.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/mfps-implicit-automata.pdf'>slides</a>]
* The Functional Machine Calculus III: Choice (Early Announcement) &mdash; <i>Willem Heijltjes</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-17.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/heijltjes.pdf'>slides</a>]
* Parametricity via Cohesion &mdash; <i>C.B - Aberlé</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-34.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/MFPS24-34.pdf'>slides</a>]
* Relational parametricity in the presence of GADTs (Early Announcement) &mdash; <i>Pierre Cagne and Patricia Johann</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-35.pdf'>pdf</a>]
* Compositional models for imprecise probability (Early Announcement) &mdash; <i>Jack Liell-Cock and Sam Staton</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-25.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/25.pdf'>slides</a>]
* A strong nominal semantics for fixed-point constraints &mdash; <i>Ali Khan Caires Ribeiro, Maribel Fernandez and Daniele Nantes-Sobrinho</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-26.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/ACTMFPS - Ali Khan.pdf'>slides</a>]
* Continuous Domains for Function Spaces Using Spectral Compactification &mdash; <i>Amin Farjudian and Achim Jung</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-1.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/MFPS24-1.pdf'>slides</a>]
* Cost-sensitive computational adequacy of higher-order recursion in synthetic domain theory &mdash; <i>Yue Niu, Jonathan Sterling and Robert Harper</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-24.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/mfps-24-talk.pdf'>slides</a>]
* Algebraic Reasoning over Relational Structures &mdash; <i>Jan Jurka, Stefan Milius and Henning Urbat</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-15.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/mfps2024_jurka_presentation.pdf'>slides</a>]
* GATlab: Modeling and Programming with Generalized Algebraic Theories &mdash; <i>Owen Lynch, Kris Brown, James Fairbanks and Evan Patterson</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-11.pdf'>pdf</a>]
* Polynomials in homotopy type theory as a Kleisli category &mdash; <i>Elies Harington and Samuel Mimram</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-10.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/10.pdf'>slides</a>]
* CaTT contexts are finite computads &mdash; <i>Thibaut Benjamin, Ioannis Markakis and Chiara Sarti</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-8.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/slides_thibaut_benjamin.pdf'>slides</a>]
* Two-dimensional Kripke Semantics II: Stability and Completeness &mdash; <i>Alex Kavvos</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-4.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/2dks-mfps.pdf'>slides</a>]
* A Semantic Proof of Generalised Cut Elimination for Deep Inference &mdash; <i>Robert Atkey and Wen Kokke</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-22.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/slides-2.pdf'>slides</a>]
* Positive Focusing is Directly Useful &mdash; <i>Beniamino Accattoli and Jui-Hsuan Wu</i> [<a href='https://oxford24.github.io/assets/mfps-papers/MFPS24-27.pdf'>pdf</a>] [<a href='https://oxford24.github.io/assets/slides/MFPS24-Wu.pdf'>slides</a>]


## Additional sessions

* ACT Industry Session 
* ACT session for reporting from the [Adjoint School](https://adjointschool.com)

There will also be a meeting of the [Southern Logic Seminar](https://t-powell.github.io/southern_logic_seminar/sls.html) in Oxford during this week. (Separate sign-up required for this.) 
