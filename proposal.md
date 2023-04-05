# Community Software Analysis Proposal
Please edit this file and push to your repository.

## Software: *Scipy*

*The SciPy project is a collection of open-source software tools for scientific computing in Python. One of the core modules of the SciPy project is scipy.optimize, which provides functions for numerical optimization of a variety of functions. The module includes several optimization algorithms, such as gradient-based and derivative-free methods, as well as algorithms for constrained optimization and least-squares fitting. The primary audience for the scipy.optimize module includes scientists, engineers, and other researchers who need to solve optimization problems as part of their work. The module is widely used in a variety of fields, including physics, engineering, economics, and biology, among others. Its user-friendly interface and comprehensive documentation make it an accessible and powerful tool for a wide range of users.*

### Stats

| Description | Your answer |
|---------|-----------|
| Repository URL |    |
| Main/documentation website |    |
| Year project was started |   |
| Number of contributors in the past year | `git shortlog -se --since=2022-03-01` may be useful |
| Number of contributors in the lifetime of the project |   |
| Number of distinct affiliations | 1, 2-5, 5-10, >10 |
| Where do development discussions take place? | e.g., GitHub/GitLab issues, mailing list, Slack, etc.  |
| Typical number of emails/comments per week? |   |
| Typical number of commits per week? |  |
| Typical commit size | `git log --shortstat` may be useful |
| How does the project accept contributions? | e.g., pull requests, patches on mailing lists   |
| Does the project have an automated test suite? | yes/no |
| Does the project use continuous integration? | yes/no |
| Are any legal/licensing steps required to contribute? | no or explain below |


- Repository URL

https://github.com/scipy/scipy

- Main /documentation website

The main documentation website for SciPy is https://docs.scipy.org.

- Year project was started

SciPy was first released in 2001.


- Number of contributors in the past year

47 (git command: git shortlog -se --since=2022-03-01)

- Number of contributors in the lifetime of the project

1299

- Number of distinct affiliations????


 #> 10

 - Where do development discussions take place e.g Github/Gitlab issues,mailing list,slack

Development discussions for SciPy take place primarily on the project's GitHub repository.

- Typical number of emails /comments per week

average of around 100-150 per week.

- Typical number of commits per week

average of around 10-20 commits per week

- Typical commit size

average of around 50-100 lines per commit 

- How does the project accept contributions e.g pull requests ,patches on mailing lists

Scipy accepts contributions through pull requests on GitHub.

- Does the project have an automated test suite ? yes /no

Yes, the Scipy project has an automated test suite.

- Does the project use continuos integration ? yes /no

Yes, the Scipy project uses continuous integration

- Are any legal /licensing steps required to contribute

Yes, contributors to the Scipy project are required to follow the project's Contributor Code of Conduct, which outlines expected behavior and requires contributors to ensure that their contributions are properly licensed. It uses the BSD 3-Clause "New" or "Revised" License, and all contributions must be made under this license.


### Install and run

Check the following boxes when complete or add a note below if you
encountered a problem.

- [*] I have installed the software
- [*] I have run at least one example
- [*] I have run the test suite
- [*] The test suite passes

import scipy
scipy.test()


### Notes/concerns/risks

Please comment on any anomalies or known risks to following this
project, if you were unable to answer any questions above, or
otherwise have concerns about the appropriateness of the software.  If
the project requires a contributor license agreement or other
procedural steps, please explain here.  "None at this time" is
acceptable for this question.


- Please comment on any anomalies or known risks to following this
project

one potential risk is that the project may not be suitable for all use cases or may have limitations in certain areas. For example, the scipy.optimize module may not be optimized for very large-scale optimization problems 

another risk is that the project may have dependencies or compatibility issues with other software tools or environments

- If the project requires a contributor license agreement or other
procedural steps, please explain here.  "None at this time" is
acceptable for this question.

contributing to the SciPy project, including the scipy.optimize module, requires agreeing to the project's Contributor License Agreement (CLA). The CLA is a legal document that grants the project permission to use the contributed code and ensures that the code can be licensed under the project's chosen license (the BSD license).


#### Note on copyright
Students retain copyright on any work done in completion of a CU
course, so you are authorized to sign a [contributor license
agreement (CLA)](https://en.wikipedia.org/wiki/Contributor_License_Agreement),
affirm a [developer's certificate of
origin (DCO)](https://en.wikipedia.org/wiki/Developer_Certificate_of_Origin),
etc.  If you have concerns about this, please note them and/or reach
out to Jed directly.
