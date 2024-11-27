---
title: "Publications"
permalink: /publications/
author_profile: true
---

## Overview

This page contains a list of my publications. My early work focused on stochastic control theory and observability of Hidden Markov Models. Namely, given “bad” initial information, can a decision maker correct this mistake with the arrival of new information and make good control decisions after enough observation of the system. This topic relates to filter stability and robust control.

In my recent work in my PhD, I have continued in the vein of stochastic processes, but I am now more interested in Markov Chain Monte Carlo (MCMC), optimal transport, and generative models- various methods to produce data from a given distribution. Ultimately, I would like to apply a stochastic approach to train neural networks not using back propagation but treating the parameters as a sampling problem. Namely, can we sample weights proportional to the exponential of the negative loss function, thus producing weights with low loss with high probability. This converts a non-convex optimization problem into a non-log concave sampling problem, which has more freedom to explore the state space and not get stuck in local minima. In my recent 2024 ISIT publication I explore how posterior sampling for neural networks can be written as a series of log concave sampling problems, thus amenable to rapid MCMC sampling methods.

I have also had the opportunity to collaborate on several data science projects. These include natural language processing projects with colleagues in social science. Using sentiment analysis and topic modeling, we analysed the text in large collections of social media posts to gauge user civility in conversations as well as response to COVID-19 vaccine information. Aditionally, data analysis for orthopedic knee surgery research measuring a novel metric for measuring knee health.


## Publications

### Preprints

* ***McDonald, C.***, Barron, A. *Rapid Bayesian Computation and Estimation for Neural Networks via Mixture Distributions*. November, 2024. [Link]

### Journal Articles

* ***McDonald, C.***, Yuksel, S. *Stochastic Observability and Filter Stability under Several Criteria*. IEEE Trans. Automatic Control. vol. 69, no. 5, pp. 2931-2946, May 2024. [Link](https://ieeexplore.ieee.org/abstract/document/10209206) 

* ***McDonald, C.***, Yuksel, S. *Robustness to incorrect priors and controlled filter stability in partially observed stochastic control*. Siam Journal on Control and Optimization. vol 60, issue 22 . April 2022. [Link](https://epubs.siam.org/doi/abs/10.1137/21M1417442)

* ***McDonald, C***., Yuksel, S. *Exponential filter stability via Dobrushin's coeffcient*. Electronic Communications in Probability. vol 20, no. 53. pp. 1-13. August 2020. [Link](https://projecteuclid.org/journals/electronic-communications-in-probability/volume-25/issue-none/Exponential-filter-stability-via-Dobrushins-coefficient/10.1214/20-ECP333.full)

* ***McDonald, C.***, Alajaji, F., Yuksel, S. *Two-Way Gaussian Networks with a Jammer and Decentralized Control*. IEEE Transactions on Control of Network Systems. vol. 7, no. 1, pp. 446-457, March 2020. [Link](https://ieeexplore.ieee.org/document/8737761)

### Conference Papers

* ***McDonald, C.***, Barron, A. (2024). *Log-Concave Coupling for Sampling Neural Net Posteriors*. 2024 IEEE International Symposium on Information Theory (ISIT). [Link](https://arxiv.org/abs/2407.18802).

* ***McDonald, C.***, Barron, A. (2022) *Proposal of a Score Based Approach to Sampling Using Monte Carlo Estimation of Score and Oracle Access to Target Density*. NeurIPS
2022 Conference Workshop on Score Based Methods. [Link](https://openreview.net/forum?id=ez2cB__DaTV)

* ***McDonald, C.***, Yuksel, S. (2019) *Observability and Filter Stability for Partially Observed Markov Processes*. 2019 IEEE 58th Conference on Decision and Control (CDC). pp. 1623-1628. [Link](https://ieeexplore.ieee.org/document/9029775)
  
* ***McDonald, C.***, Yuksel, S. (2018) *Stability of Non-Linear Filters, Observability and Relative Entropy*. 2018 56th Annual Allerton Conference on Communication, Control, and Computing (Allerton). pp 110 - 114. [Link](https://proceedings.allerton.csl.illinois.edu/2018/)

* ***McDonald, C.***, Alajaji, F., Yuksel, S. (2018) *Two-Way Gaussian Channels with an Intelligent Jammer*. 2018 Annual American Control Conference (ACC). pp. 1784- 1789. [Link](https://ieeexplore.ieee.org/document/8430803)

### Data Science Applications

* Sieberer J. M., Park N., Manafzadeh A. R., Desroches S. T., Brennan K., ***McDonald C.***, Tommasini S. M., Wiznia D. H., Fulkerson J. P. *Visualization of Trochlear Dysplasia Using 3-Dimensional Curvature Analysis in Patients With Patellar Instability Facilitates Understanding and Improves the Reliability of the Entry Point to Trochlea Groove Angle*. Arthroscopy, Sports Medicine, and Rehabilitation. September, 2024.[Link](https://www.sciencedirect.com/science/article/pii/S2666061X24001470)

* Sieberer J. M., Park N., Rancu A. L., Desroches S. T., ***McDonald C.***, Manafzadeh A. R., Tommasini S. M., Wiznia D. H., Fulkerson J. P. *Analyzing Alignment Error in Tibial Tuberosity–Trochlear Groove Distance in Clinical Scans Using 2D and 3D Methods*. The American Journal of Sports Medicine. September, 2024. [Link](https://journals.sagepub.com/doi/abs/10.1177/03635465241279852) 

* Beitler B. G., Sieberer J., Islam W., ***McDonald C.***, Yu K., Tommasini S. M., Fulkerson J. P. *The Morphologic Patella Entry Point Into The Proximal Trochlea Is More Lateral in Recurrent Dislocators Than Controls as Measured by Entry Point-Trochlear Groove Angle*. Arthroscopy: The Journal of Arthroscopic and Related Surgery. May, 2024. [Link](https://www.sciencedirect.com/science/article/pii/S074980632400308)


* Kim, J., ***McDonald, C.***, Meosky, P., Katsaros, M., Tyler, T. *Promoting Online Civility Through Platform Architecture*. Journal of Online Trust and Safety. vol 1, issue 4. September 2022. [Link](https://tsjournal.org/index.php/jots/article/view/54)

* Kumar N., Corpus I., Hans M., Harle N., Yang N., ***McDonald C.***, Nakamura Sakai S., Janmohamed K., Chen K., Altice F. L., Tang W., Schwartz J. L., Jones-Jang S. M., Saha K., Memon S. A., Bauch C. T., Choudhury M. D., Papakyriakopoulos O., Tucker J. D., Goyal A., Tyagi A., Khoshnood K., Omer S. *COVID-19 vaccine perceptions in the initial phases of US vaccine roll-out: an observational study on reddit*. BMC Public Health. vol 22, issue 1, March 2022. [Link](https://bmcpublichealth.biomedcentral.com/articles/10.1186/s12889-022-12824-7)

### Dissertations

* ***Mcdonald, Curtis James***. *Filter Stability, Observability and Robustness for Partially Observed Stochastic Dynamical Systems*. Diss. Queen's University (Canada), 2019. [Link](https://qspace.library.queensu.ca/handle/1974/26466)



