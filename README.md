# KludgeCounter-Simulation

This repository contains Python code for a simulation modelling developers' behaviours, which is a part of my final year research at UCL (MEng Computer Science).


## Abstract

Pressurized by close deadlines, developers have an incentive to commit quick code implementations instead of proper fixes which require longer development time. This introduces long term quality deteriorations and high maintenance costs, and is commonly known as ”technical debt”. The concept is not new and this paper investigates how quick patches affect long running open-source projects.

A simulation model was built, named ”KludgeCounter”. ”Kludge- Counter” gathers commit quality information from Git repositories and identifies bug reports using a linter tool. In this report, it was applied to the Apache Ant project using PMD to assess the quality of individual commits. Additionally, it collects JSON data from Bugzilla to identify the timeline of each bug creation and resolution. The data gathered is analyzed and probability distributions are modelled. These are used in the simulation model, allowing to further explore how different parame- ters of the simulation affect the total number of resolved bugs, and what are the chances of having a quick patch or a deeper fix. Developers are analyzed in terms of their commitment to submit deep fixes. For instance, it was discovered that in the Apache Ant Project, 27% of all developers submitted at least 1 commit with a PMD alert in it, but only about 10% of all commits have the alert. Finally, the simulation is used to model the real-world situations, and some hypothetical: worst- and best-case scenarios.

Overall, ”KludgeCounter” is part of an ongoing project where a game- theoretic model is used in empirical analysis of open-source projects. ”KludgeCounter” is a valuable tool for analyzing the impact of quick patches on the code base quality, supporting theoretical concepts by the data collected online.

