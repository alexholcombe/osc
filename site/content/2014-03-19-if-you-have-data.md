Title: If You Have Data, Use It When Theorizing
Author: Daniel Lakens
Date: 2014-03-19 12:00
Slug: if-you-have-data
Tags: social-priming-and-reproducibility

<!-- PELICAN_BEGIN_SUMMARY -->
There is a reason data collection is part of the empirical cycle. If you have a good theory that allows for what Platt (1964) called ‘strong inferences’, then statistical inferences from empirical data can be used to test theoretical predictions. In psychology, as in most sciences, this testing is not done in a Popperian fashion (where we consider a theory falsified if the data does not support our prediction), but we test ideas in Lakatosian lines of research, which can either be progressive or degenerative (e.g., Meehl, 1990). In (meta-scientific) _theory_, we judge (scientific) theories based on whether they have something going for them.  

In scientific _practice_, this means we need to evaluate research lines. One really flawed way to do this is to use ‘vote-counting’ procedures, where you examine the literature, and say: "Look at all these significant findings! And there are almost no non-significant findings! This theory is the best!” Read Borenstein, Hedges, Higgins, & Rothstein (2006) who explain “Why Vote-Counting Is Wrong” (p. 252 – but read the rest of the book while you’re at it).  

<!-- PELICAN_END_SUMMARY -->
One good way the evaluate lines of research is to perform a meta-analysis. However, there is one way in which meta-analyses suck big time: they suffer from publication bias. Since you only have access to the significant results, you have to try to find non-significant results by asking people whether they have them lying around in file-drawers, and convince these people to share the data (and invest the time to find the data and make them understandable for you) so that there is a substantial possibility you will be able to write an article about how the effect they worked so hard to get published actually does not exist. I’m not saying it is impossible, but there’s a challenge.  

Luckily, Simonsohn, Nelson, and Simmons (2013) worked out a new meta-analytic procedure, called ‘_p_-curve analysis’, which does not suffer from publication bias (hurray for science!). In a _p_-curve analysis you look at the distribution of _p_-values below .05 in the published literature, and test whether the distribution is right-skewed (as it should be if the line of research has something going for it), or uniform (a straight line – and we all know from hospital series on TV that straight lines are not good). There’s a third possibility, namely a left-skewed distribution, which also means there is no evidential value for a line of research (but in addition, that there’s a higher number of just significant results than expected by chance, which can indicate _p_-hacking, Simmons, Nelson, & Simonsohn, 2011).  

The new thing in _p_-curve analyses is that inferences are drawn from a test performed on the distribution. There is nothing new about how _p_-values should be distributed below the .05 level – that was all pretty much known previously (see for example Sellke, Bayarri, & Berger, 2001). But the tests are useful, in that they allow us to judge whether a set of studies (e.g., a line of research) has something going for it, or not. This makes it a perfect tool to evaluate lines of research in the published literature, and thus, evaluate how well theories are doing.  

Stroebe & Strack (2014) recently argued that conceptual replications are the best test of a theory. Subsequently, they point to many successful conceptual replications of elderly priming and professor priming (see below), and suggest this is support for the theoretical idea that inspired these studies. This is basically a vote-counting meta-analytic procedure. Dijksterhuis (2014) does the same thing when he says that "hundreds of papers cannot be erased by the mere flick of a skeptic magic wand". This is also vote-counting, in that you argue for the presence of an effect based on a count of the number of significant effects in the literature. Again: vote-counting is a flawed meta-analytic procedure and should never be used to infer support for a theoretical idea, not even implicitly in theoretical reviews.  

In a recent illustration of how _p_-curve analyses can differentiate between theoretical ideas that have something going for them, and ideas that have not much going for them, [I _p_-curved lines of studies](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2381936) examining two theoretical ideas. The first, elderly priming, predicts that activating the stereotype of elderly will make people behave more slowly. The second, professor priming, predicts that activating the stereotype of a professor will make people work harder and perform better on a trivial pursuit game. My analyses are not yet peer-reviewed (but the data on which it is based is [available on the Open Science Framework](https://osf.io/3urp2/), see also Lakens, 2014) so be critical and draw your own conclusions. The analysis revealed elderly priming had no evidential value (and displayed signs of _p_-hacking, as indicated by the higher percentage of _p_-values just below .05 in the figure), while professor priming had something going for it (as indicated by the relatively higher percentage of _p_-values between .00 and .01 in the figure). This nicely illustrates how it can be inferred that two lines of research that were both discussed in an equivocal manner based on implicit vote-counting procedures by Stroebe and Strack (2014) actually differ in their likelihood when correct meta-analytic procedures are applied.  

<img src="/images/elderly_priming.png" alt="elderly priming" align="center" style="padding-right: 20px;" width="603px" />  
<img src="/images/professor_priming.png" alt="professor priming" align="center" style="padding-right: 20px;" width="603px" />  

I think it is important to realize that theoretic conclusions that do not use the correct meta-analytic procedures have a high risk of being false. I notice that a lot of researchers who review the literature take a vote-counting meta-analytic perspective. They cite and discuss a lot of significant findings, and assume it says something about the probability that the ideas tested in a line of studies are true. You should not be convinced about the likelihood a theoretical idea is true by such theoretical reviews. And if you write a theoretical review, make use of the meta-analytical procedures (such as _p_-curve analyses) you have at your disposal to draw more accurate, data-driven inferences about the likelihood theoretical ideas are true.  

__References__

Borenstein, M., Hedges, L. V., Higgins, J. P., & Rothstein, H. R. (2011). Introduction to meta-analysis. Hoboken, NJ: Wiley.  

Dijksterhuis, A. (2014). Welcome back theory! Perspectives on Psychological Science, 9, 72-75.  

Lakens, D. (2014). Professors are not elderly: Evaluating the evidential value of two social priming effects through p-curve analyses. Available at SSRN: [http://ssrn.com/abstract=2381936](http://ssrn.com/abstract=2381936)  

Meehl, P. E. (1990). Appraising and amending theories: The strategy of Lakatosian defense and two principles that warrant it. Psychological Inquiry, 1(2), 108-141.  

Platt, J. R. (1964). Strong inference. Science, 146(3642), 347-353.  

Sellke, T., Bayarri, M. J., & Berger, J. O. (2001). Calibration of p values for testing precise null hypotheses. The American Statistician, 55(1), 62-71.  

Simmons, J. P., Nelson, L. D., & Simonsohn, U. (2011). False positive psychology: Undisclosed flexibility in data collection and analysis allows presenting anything as significant. Psychological Science, 22, 1359–1366.  

Simonsohn, U., Nelson L, Simmons, J. (2014). P-curve: A key to the file drawer. Journal of Experimental Psychology: General.  

Stroebe, W., & Strack, F. (2014). Welcome back theory! Perspectives on Psychological Science, 9, 59-71. DOI: 10.1177/1745691613514450  
