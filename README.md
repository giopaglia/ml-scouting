# Machine Learning Libraries

| Language  | Libraries |
| ------------- | ------------- |
| Julia  | Flux, JuliaDB, MLJ, XGBoost  |
| Python    |    Scikit Learn, TensorFlow, PyTorch, Keras, Theano, XGBoost    |
| Java    |    Weka, ADAMS, JavaML, Neuroph    |
| R    |    caret, e1071, PARTY, rpart, randomFOREST, XGBoost    |
| MATLAB    |    Statistics and Machine Learning Toolbox, Deep Learning Toolbox, Computer Vision Toolbox    |
| C++    |    Caffe, TensorFlow, LightGBM, Turi Create, DyNet, XGBoost    |
| JavaScript/TypeScript    |    TensorFlow.js, Brain.js, stdlib-js, machinelearn.js, R-js    |
| C#    |    ML.NET, Accord.NET, ML-Agents    |
| Go    |    GoLearn, Gorgonia    |

Useful sources:
- https://www.codecademy.com/resources/blog/machine-learning-programming-languages/
		
### Scientific references

| Year	|	Entry  | Paper | # Pages | Notes |
| ------------- | ------------- | ------------- | ------------- | ------------- |
|	1994	| Weka (1) |	[Holmes, Geoffrey, Andrew Donkin, and Ian H. Witten. "Weka: A machine learning workbench." Proceedings of ANZIIS'94-Australian New Zealnd Intelligent Information Systems Conference. IEEE, 1994.](https://researchcommons.waikato.ac.nz/bitstream/handle/10289/1138/uow-cs-wp-1994-09.pdf?sequence=1)	|	5	|	Short paper showcasing the GUI, available algorithms and the **applications under investigation**.	|
|	2002	| Torch |	[Collobert, Ronan, Samy Bengio, and Johnny Mariéthoz. Torch: a modular machine learning software library. No. REP_WORK. Idiap, 2002.](https://infoscience.epfl.ch/record/82802/files/rr02-46.pdf)	|	5	|	A very short section **lists broad classes (DataSet, Machine, Trainer, Measurer)**. Another section provides four examples of commonly used models/optimizers, with math expressions. Another section **compares it with other ML libraries (saying there aren't any that are comparable)**.	|
|	2006	| NLTK |	[Bird, Steven. NLTK: the natural language toolkit." Proceedings of the COLING/ACL 2006 Interactive Presentation Sessions. 2006.](https://aclanthology.org/P06-4018.pdf)	|	4	|	Short paper with Introduction and three simple example usages with code. There's a section "Teaching with NLTK".	|
|	2010	| Weka (2) |	[Bouckaert, Remco R., et al. "WEKA---Experiences with a Java Open-Source Project." The Journal of Machine Learning Research 11 (2010): 2533-2541.](https://www.jmlr.org/papers/volume11/bouckaert10a/bouckaert10a.pdf)	|	9	|	Lists functionalities (Data preprocessing, Classification, Clustering, Attribute selection, Data visualization). Doesn't go into implementation details, but rather review the history of the library and its **design principles**.	|
|	2011	| Scikit-learn |	[Pedregosa, Fabian, et al. "Scikit-learn: Machine learning in Python." the Journal of machine Learning research 12 (2011): 2825-2830.](https://www.jmlr.org/papers/volume12/pedregosa11a/pedregosa11a.pdf)	|	5	|	High-level description of the code, no implementation details but rather discusses the project 6 sections: Introduction, **Project Vision**, **Underlying Technologies**, **Code Design**, **High-level yet Efficient**, Conclusion. Note that scikit learn's history starts in 2007, and this paper is from 2011.	|
|	2012	| Theano |	[Bastien, Frédéric, et al. "Theano: new features and speed improvements." arXiv preprint arXiv:1211.5590 (2012).](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=71fd0f03a01cf8adb4919d2b1fe7b0a25ad0ca90)	|	4	|	**Section showcasing an example workflow** "Theano by Example: Logistic Regression". Note that this is a preprint of Journal of Machine Learning Research, but appears to have never been published.	|
|	2014	| Caffe |	[Jia, Yangqing, et al. "Caffe: Convolutional architecture for fast feature embedding." Proceedings of the 22nd ACM international conference on Multimedia. 2014.](https://arxiv.org/pdf/1408.5093)	|	4	|	**Comparison with other frameworks**, pros (**modularity**, **separation of representation and implementation**, **test coverage**, ...). **Section "Architecture" with few-paragraphs subsections explaing how the library models neural layers, networks, and the training phase.	Section "Applications And Examples" with paragraphs summarizing the achievements: "Object Classification", "Learning Semantic Features", "Object Detection", "Beginners’ Guides".** |
|	2016	| TensorFlow (1)	|	[Abadi, Martín, et al. "TensorFlow: a system for Large-Scale machine learning." 12th USENIX symposium on operating systems design and implementation (OSDI 16). 2016.](https://www.usenix.org/system/files/conference/osdi16/osdi16-abadi.pdf)	|	19	|	Long paper with Background, motivation, related work, **design principles**, and **evaluation at different tasks**. (And other stuff like "execution model" and "**extensibility** case studies")	|
|	2016	| XGBoost |	[Chen, Tianqi, and Carlos Guestrin. "XGBoost: A scalable tree boosting system." Proceedings of the 22nd acm sigkdd international conference on knowledge discovery and data mining. 2016.](https://dl.acm.org/doi/pdf/10.1145/2939672.2939785)	|	10	|	Long article with **theoretical (algorithms, time complexity), and practical (cache-aware implementation) contributions**. Related work and evaluation.	|
|	2017	| DifferentialEquations |	[Rackauckas, Christopher, and Qing Nie. "Differentialequations. jl–a performant and feature-rich ecosystem for solving differential equations in julia." Journal of open research software 5.1 (2017).](https://www.researchgate.net/profile/Chris-Rackauckas/publication/317162482_DifferentialEquationsjl_-_A_Performant_and_Feature-Rich_Ecosystem_for_Solving_Differential_Equations_in_Julia/links/5927e554a6fdcc4443511412/DifferentialEquationsjl-A-Performant-and-Feature-Rich-Ecosystem-for-Solving-Differential-Equations-in-Julia.pdf)	|	10 | (Note: not a ML library but still relevant.) **Highlights extensive use of multiple dispatch**. **Limitations and Future Development Plans.**	|
|	2018	| Flux |	[Innes, Mike. "Flux: Elegant machine learning with Julia." Journal of Open Source Software 3.25 (2018): 602.](https://joss.theoj.org/papers/10.21105/joss.00602.pdf)	|	1	|	A single abstract of three paragraphs (Proceedings di JuliaCon pubblicati su JOSS).	|
|	2020	| TensorFlow (2)	|	[Pang, Bo, Erik Nijkamp, and Ying Nian Wu. "Deep learning with tensorflow: A review." Journal of Educational and Behavioral Statistics 45.2 (2020): 227-248.](https://journals.sagepub.com/doi/abs/10.3102/1076998619872761)	|	22	|	Section "Background and Notation" (neural networks and gradient descent). Core Section containing, among others, core design concepts, and an example workflow (with a lot of code).	|
|	2020	| MLJ |	[Blaom, Anthony D., et al. "MLJ: A Julia package for composable machine learning." arXiv preprint arXiv:2007.12285 (2020).](https://arxiv.org/pdf/2007.12285)	|	7	|	TODO	|

<!-- |	2015	| Caret |	[Kuhn, Max. "Caret: classification and regression training." Astrophysics Source Code Library (2015): ascl-1505.](https://ui.adsabs.harvard.edu/abs/2015ascl.soft05003K/abstract)	| -->

### Candidate journals for publishing frameworks

- [Journal of Machine Learning Research](https://exaly.com/journal/139808/journal-of-machine-learning-research) ([sjr](https://www.scimagojr.com/journalsearch.php?q=20969&tip=sid&clean=0))
- [Journal of Open Source Software](https://exaly.com/journal/106890/journal-of-open-source-software/)
- [Journal of Information and Software Technology](https://exaly.com/journal/15898/information-and-software-technology/) ([sjr](https://www.scimagojr.com/journalsearch.php?q=18732&tip=sid&clean=0))
- [Algorithms](https://exaly.com/journal/21293/algorithms/) ([sjr](https://www.scimagojr.com/journalsearch.php?q=21100199795&tip=sid&clean=0))
- [Applied Computing and Informatics](https://exaly.com/journal/32829/applied-computing-and-informatics) ([sjr](https://www.scimagojr.com/journalsearch.php?q=21100862637&tip=sid&clean=0))
