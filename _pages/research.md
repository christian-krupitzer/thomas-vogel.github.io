---
title: Research
permalink: research.html
layout: page
---

My research focuses on developing methods and techniques that support understanding, engineering, and assuring intelligent/autonomous software systems, especially systems that act upon themselves or the environment based on automated decisions (cf. self-aware and self-adaptive software systems).
In my work, I combine software engineering research with model-driven engineering, control theory, artificial and computational intelligence, and (mathematical) optimization.

My Ph.D. research was about [model-driven engineering of self-adaptive software](publications/phd) where models and model-driven engineering techniques are exceedingly leveraged at run-time to achieve a higher degree of flexibility in the design, evolution, and operation of such software systems than the state of the art (cf. [EUREMA](#projects) and [MORISIA](#projects) projects).

Especially in my postdoctoral studies I broadened my research along three lines:

### (1) Methods and techniques to cope with the increasing level of autonomy of self-adaptive systems
We observe an increasing level of autonomy of self-adaptive systems that operate in uncertain environments, which requires novel means to engineer such systems. In this context, I research optimization, learning, assurance, control-inspired, and architectural methods and techniques for self-adaptive systems such as:

* learning and optimization techniques to identify optimal system configurations, adaptation rules, and adaptation decisions ([SASO'19](publications/2019-SASO), [SEAMS'18](publications/2018-SEAMSb), [ICAC'17](publications/2017-ICAC))
* assurance techniques to validate and verify self-adaptation ([SEAMS'19](publications/2019-SEAMS), [SEAMS'18](publications/2018-SEAMSb), [SEfSAS'17a](publications/2017-SEFSAS3a), [SEfSAS'17b](publications/2017-SEFSAS3b))
* control to systematically engineer self-adaptive systems with guarantees (see [TAAS'17](publications/2017-TAAS), [CASaS'17](publications/2017-CASaS))
* architectures for the design of self-aware computing systems  (see [SACS'17a](publications/2017-SACSa), [SACS'17b](publications/2017-SACSb), [SACS'17c](publications/2017-SACSc))

### (2) Understanding intelligent methods and making intelligent methods self-adaptive
Methods from computational and artificial intelligence are typically black-box and therefore arcane for software engineers, which impedes an understanding why certain methods work well and others do not for a specific problem. For this purpose, my goal is to develop explanations that enable such an understanding.

Particularly, I develop explanations of the difficulty of optimization problems in search-based software engineering by analyzing the fitness landscape and thus, the interaction of methods from computational intelligence (esp. evolutionary algorithms) with the related search spaces. The explanations enable a better understanding of the search problems and methods (cf. [FLASH](#projects) project). One example is:
* a fitness landscape analysis for the search problem of generating test suites for mobile applications, which is solved by evolutionary algorithms, which identified a lack of diversity of test suites during the search potentially causing a stagnation of the search process ([SSBSE'19](publications/2019-SSBSE)).

<br />
The gained understanding could then help in configuring a method to yield better results for a specific problem. In this context, I envision _self-adaptive intelligent methods_ that automatically and dynamically configure themselves at run-time. For instance:
* I transferred self-adaptation principles to the generation test suites for mobile applications, particularly by equipping the evolutionary algorithm for generating test suites with a feedback loop that automatically and dynamically adapts the search strategy if the diversity of test suites decreases ([SSBSE'19](publications/2019-SSBSE) and research project [_Self-Adaptive Search for Sapienz_](#projects)).

<br />
Since the techniques to develop explanations are generic, they can be also applied to optimization problems in self-adaptive software systems such as finding optimal adaptation plans and system configurations.

### (3) Practical and explainable verification of software systems
Given the increasing level of autonomy, large configuration spaces, or uncertainty of software systems, assuring such systems has become a major challenge ([SEfSAS'17a](publications/2017-SEFSAS3a), [SE4Science'19](publications/2019-SE4Science)). The use of formal methods (e.g., model checking), and the interpretation of the results of such methods (e.g., a counterexample) are often difficult, error-prone, and costly. My goal is to make such methods practically usable, for instance by:
* following a model-based approach to tame the complexity of safety analysis ([IMBSA'19](publications/2019-IMBSA))
* integrating natural language-based property specification patterns (cf. [Safe.Spec](#projects) project)
* improving the explainability of counterexamples (cf. project on [_Specification and Verification of Requirements and Safety Contracts_](#projects))


# Projects

## Self-Adaptive Search for Sapienz
Transferring self-adaptation principles to the search process of Sapienz, a search-based test suite generation tool for
mobile applications (funded by the 2018 Facebook Testing and Verification Research Award).

## FLASH: Fitness landscape analysis to improve search-based software engineering
Analyzing and understanding the search space and search methods for software engineering problems to improve state-of-the-art search
heuristics to solve these problems
(funded by DFG, [project website](https://www.informatik.hu-berlin.de/en/forschung-en/gebiete/se/research/ongoingprojects/flash){:target="_blank"}).

## Specification and Verification of Requirements and Safety Contracts
Developing a domain-specific language for specifying and verifying requirements and safety contracts in the
automotive industry, and techniques for explaining counter examples of the verification process (in cooperation with BOSCH Research).

## Safe.Spec: Quality Assurance for Requirements Specifications
Developing a user-friendly, model-driven approach to specify, compose, and verify scenario-based requirements. This includes the pattern-based specification of scenarios using sequence diagrams, composing scenarios to automaton-based specifications, and integrating natural language-based property specification patterns with UPPAAL. (in cooperation with TWT GmbH, funded by BMBF, [project website](https://www.informatik.hu-berlin.de/en/forschung-en/gebiete/se/research/ongoingprojects/safespec){:target="_blank"}).

## EUREMA: Executable Runtime Megamodels
A model-driven engineering approach to specify, execute, adapt, and evolve feedback loops in self-adaptive software systems ([project website](https://www.hpi.uni-potsdam.de/giese/public/mdelab/mdelab-projects/software-engineering-for-self-adaptive-systems/eurema/){:target="_blank"}).

## MORISIA: Models at Runtime for Self-Adaptive Software
Researching runtime models for feedback loops in self-adaptive software systems to realize self-awareness and self-adaptation ([project website](https://www.hpi.uni-potsdam.de/giese/public/mdelab/mdelab-projects/software-engineering-for-self-adaptive-systems/morisia/){:target="_blank"}).

## mRUBiS: modular Rice University Bidding System
An exemplar for model-based architectural self-healing and self-optimization of an information system. See [paper](publications/2018-SEAMSa) and [artifact at GitHub](https://github.com/thomas-vogel/mRUBiS){:target="_blank"}.
