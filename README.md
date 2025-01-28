# Machine Learning for Physics and Astronomy
**[Davide Gerosa](https://davidegerosa.com/)** (module lead) - davide.gerosa@unimib.it  
**Giulia Fumagalli** (teaching assistant) - g.fumagalli47@campus.unimib.it 

University of Milano-Bicocca, 2025. [BSc in Artificial Intelligence](https://www.unimib.it/undergraduate/artificial-intelligence).

## Aims

Machine learning and data mining are quickly becoming essential techniques in the field of (astro)physics. Such powerful tools provide precious insights into the laws governing natural processes and shed light on the information contained in experimental datasets. This lab provides a quick introduction to such topics, equipping students with some essential background to apply their data-science knowledge to core physical problems.

## Lectures

1. **[Probability](lectures/L01_probability.ipynb)** Probability theory. Bayes theorem. Descriptive statistics (*E: Monty Hall*)
2. **[Sampling](lectures/L02_sampling.ipynb)** Bayesian vs frequentist statistics. From the pdf to the samples: inverse transform, acceptance/rejection (*E: Black holes*)
3. **[Density estimation](lectures/L03_densityestimation.ipynb)** From the samples to the pdf: histograms, Kernel Density Estimation. (*E: Exoplanets*)
4. **[Markow chains](lectures/L04_Markovchains.ipynb)** Monte Carlo integrations. Markow chains. (*E: Weather forecast, N-dimensional balls*)
5. **[MCMC](lectures/L05_MCMC.ipynb)** Metropolis Hastings. MCMC diagnostics. Modern samplers. (*E: Time transients*)
6. **[Model selection](lectures/L06_modelselection.ipynb)** Bayesian model selection. Savage-Dickey density ratio. (*E: Higgs Boson*)
7. **[Nested sampling](lectures/L07_nestedsampling.ipynb)** Computing the evidence. Nested sampling. Modern samples. (*E: Time transients & Higgs Boson*)
8. **[Project](lectures/L08_project.ipynb)** (*E: The expansion of the Universe*)

## Resources

Here are some useful textbooks. The first one is easier, the second one is amazing, the third is short and sweet, the fourth and fifth ones are for the true Bayesians...

 - ["Machine Learning for Physics and Astronomy"](https://press.princeton.edu/books/paperback/9780691206417/machine-learning-for-physics-and-astronomy), Acquaviva, Princeton University Press, 2023.
- ["Statistics, Data Mining, and Machine Learning in Astronomy"](https://press.princeton.edu/books/hardcover/9780691198309/statistics-data-mining-and-machine-learning-in-astronomy), Željko, Andrew, Jacob, and Gray. Princeton University Press, 2012.
- ["Statistical Data Analysis"](https://global.oup.com/academic/product/statistical-data-analysis-9780198501558?cc=fr&lang=en&), Cowan. Oxford Science Publications, 1997.
- ["Data Analysis: A Bayesian Tutorial"](https://global.oup.com/academic/product/data-analysis-9780198568322?cc=fr&lang=en&), Sivia and Skilling. Oxford Science Publications, 2006.
- ["Bayesian Data Analysis",](http://www.stat.columbia.edu/~gelman/book/) Gelman, Carlin, Stern, Dunson, Vehtari, and Rubin. Chapman & Hall, 2013. Free!

We will make heavy use of the python programming language. If you need to refresh your python skills, here are some catch-up resources and online tutorials. 

- ["Python for Scientific Computing"](https://sbu-python-class.github.io/python-science/Introduction.html), M. Zingale
- ["Lectures on scientific computing with Python"](https://github.com/jrjohansson/scientific-python-lectures), R. Johansson et al.  
- [Python Programming for Scientists"](https://astrofrog.github.io/py4sci/), T. Robitaille et al.
- ["Learning Scientific Programming with Python"](https://www.cambridge.org/core/books/learning-scientific-programming-with-python/3D264483BC7B380A3059B3861C661237), Hill, Cambridge University Press, 2020. Supporting code: [scipython.com](https://scipython.com/).

## 2025 Class schedule

Classes will take place on the Bicocca campus, on Wednesdays from 8.30am to 12.30pm, for a total of 36 hours. Here is our timetable:

1. **Mar 5**. Lab U9-910
2. **Mar 12**. Lab U9-910
3. **Mar 19**. Lab U9-910
- Mar 26, Davide is away for research
4. **Apr 2**. Lab U9-910
5. **Apr 9**. Lab U9-910
6. **Apr 16**. Lab U9-910
7. **Apr 23**. Lab U9-910
8. **Apr 30**. Lab U5-531
9. **May 7**. Lab U5-531
- May 14, backup slot
- May 21, backup slot
- May 28, backup slot

## Setup

Each class will be about 1h of lecture and about 3h of coding. You will need to run python, see [here for instructions](pythonsetup.md).

## Exams

Each lecture has an exercise at the end (actually, most of the time in class is dedicated to completing these problems!). At the end of the class, you will have to submit your codes showcasing what you've done on these problems. There will not be oral exams. The outcome will be provided as a passed / not passed statement (no numbers).

To submit your codes, register on github.com, create a new **private** repository called `machinelearning4physics_bicocca_2024_solutions`, upload your files, and share it with the two of us (usernames `dgerosa` and `gfumagalli`). See [here for detailed instructions](examsubmission.md).

Exams will be cleared according to the nominal calendar available on the student service website. 

## Careful...

<p align="center">
  <img src="https://imgs.xkcd.com/comics/here_to_help_2x.png" width="800" />
</p>

Credit: [xkcd 1831](https://xkcd.com/1831/).
