# STT465: Bayesian Statistical Methods (MSU)


* **Instructor:** Gustavo de los Campos ( gustavoc@msu.edu )
* **Time/Place:** MW 10:20am-11:40am A120 Wells Hall (WH)   
* **[Syllabus](https://github.com/gdlc/STT465/blob/master/STT465_Syllabus.pdf)**
* **[Required textbook](http://www.stat.washington.edu/people/pdhoff/book.php)**
* **[R-software](http://www.r-project.org/)**
* **[Syllabus](https://github.com/gdlc/STT465/blob/master/STT465_Syllabus.pdf)**
* **[Tentative Schedule](https://github.com/gdlc/STT465/blob/master/SCHEDULE.pdf)**

## Homework
 * **[HW 1](https://www.dropbox.com/s/xj5uf9540udtdje/HW1_STT465.pdf?dl=0)** (Due W Sept 14 in class).
 * **HW 2**: Problems 3.3, 3.7 and 3.9 from the book (due  Wednesday, Sept 28th in class).
 
## Chapter 2. Belief, probability and exchangeability

 * Sections: 2.1-2.8, tpics covered:
  * Beliefs and properties of belief functions
  * Rules of probability
   * Total probability
   * Marginal probability
   * Bayes Rule
  * Probability functions as a way of describing beliefs
  * Independence
  * Conditional independence
  * Discrete RV (definition, pdf, probability of events, examples, includin Bernoulli, Binomial and Poisson)
  * Contionous RV (definition, CDF, pdf, examples: Normal)
  * Descriptors of Distributions: Expectation, Variance, quantiles.
  * Joint Marginal and Conditional Distributions (both for discrete and contionous)
  * The joint distribution of independent and IID RV
  * Exchangeability (definiton and example: Bernoulli)
  * Conditional independence (example: Bernoulli model)
  * De Finetty's Theorem (theorem and implications for building Bayesian models)
 
## Chapter 3. One Parameter Models
 * For the Beta-Binomial and Poisson-Gamma models we will cover:
    * Sampling Model
    * Maximum Likelihood Estimation
    * Large sample distribution of MLE
    * Large sample Frequentist CI (computation and interpretation)
    * Prior
    * Posterior
    * Bayesian inference
      * Maximum a posteriori
      * Posterior mean
      * Bayesian Credibility Regions

## Chapter 4. Monte Carlo Approximation
  * The method
  * Inference of arbitrary functions
  * The predictive distribution
    * In the Beta-Biomial model
    * In the Poisson-Gamma model

## Chapter 5. The Normal Model
  * The normal distribution: parameters, and properties
  * Likelihood for nomal model
    * MLE estimate of the mean and variance
    * Bias and variance of the MLE estimates
  * Bayesian model for the mean with known variance
    * Likelihood
    * Normal prior for the mean
    * Posterior distribution for the mean
    * The Bayesian estimate as a compromise between the information provided by the likelihood (MLE estiamate) and that conveyed by the prior.
    * Bayesian model for the mean and the variance
     * The scaled-inverse Chi-square
     * The fully conditional distribution
     * A Gibbs sampler fro the normal model.
