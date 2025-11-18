---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

## Job Market Paper

**<a href="/files/QRCS.pdf" target="_blank">Quantile Regression with Censored Selection and Many Controls</a>**  
(with Songnian Chen and Junlong Feng)

<details class="no-border">
<summary>Abstract</summary>
<div class="abstract-content">
<p>This paper develops a quantile regression model with censored selection in a high-dimensional setting (HD-QRCS). We introduce a semiparametric nonlinear least squares type estimator for the copula parameters as an alternative to the estimator based on the conventional method-of-moments criterion. Our approach is based on the quantile selection model proposed by Arellano and Bonhomme (2017) to correct for sample selection. This method ensures convergence to the global minimum and avoids iterative procedures. Our estimation procedures consist of three steps: the first two employ \(\ell_1\)-penalized quantile regression and hard-thresholding in order to mitigate estimation bias and achieve oracle rate of convergence. Lastly, we obtain copula parameters and coefficients of interest. We establish uniform convergence rates for the proposed estimators and discuss the properties of variable selection. Monte Carlo simulations show that our estimators perform well under many controls. We apply our method to American Community Survey (ACS) data from 2001 to 2023 to study wage inequality.</p>
</div>
</details>

## Working Paper

<div class="working-paper-section">
**Semiparametric Estimation of the Copula Parameter in a Quantile Selection Model**  
(with Songnian Chen and Junlong Feng)  
*Status: Reject and resubmit, Journal of Econometrics*

<details class="no-border">
<summary>Abstract</summary>
<div class="abstract-content">
<p>Arellano and Bonhomme (2017) (henceforth AB) developed a quantile selection framework and proposed a two-step semiparametric estimator for the copula parameter, which characterizes the extent of sample selection bias. In this paper, we propose a new semiparametric nonlinear least squares type estimator for the copula parameter. Our approach differs from that of AB in two distinct ways. First, unlike AB where they first estimate the copula parameter and the slope coefficients in the outcome equation iteratively since the latter depends on the former, our approach breaks such dependence via a novel reparameterization scheme and avoids such iteration. This greatly simplifies implementation and improves numerical results. Second, while the quantile selection framework is characterized by a set of conditional moment restrictions, AB's estimator of the copula parameter is based on a finite number unconditional moment restrictions. In practice, moment based estimator could encounter the global identification problem, leading to possibly poor finite sample performance. In contrast, we take a semiparametric nonlinear least squares type approach, which works with conditional moments directly, essentially making use of an infinite number of unconditional moment conditions. Our identification requirement is consequently common in traditional nonlinear regression analysis, and our identification result is expected to be more robust than identification based on a finite number of moment conditions employed by AB. We show that our estimator is consistent and asymptotically normal. Simulation results suggest superior performance of our estimator over AB's estimator.</p>
</div>
</details>
</div>

<div class="third-paper-section">
**<a href="/files/CFQR.pdf" target="_blank">Endogenous High-Dimensional Quantile Regression: A Control Function Approach</a>**

<details class="no-border">
<summary>Abstract</summary>
<div class="abstract-content">
<p>This paper presents a double selection estimator based on the Control Function approach for estimating a high-dimensional Quantile Regression model with endogeneity (CFQR). We have several advantages over the Instrumental Quantile Treatment Effect model (henceforth IVQR), which was proposed by Chernozhukov and Hansen (2005). First, our model is computationally simpler than high-dimensional IVQR under general conditions. IVQR relies on a hypothesized value for coefficients of interest in the first step of estimation. The iterative nature of this process is costly, especially when dealing with big data. In contrast, our methods use the function of residuals obtained from the previous step as an additional exogenous control, which is more practical for application. Furthermore, we provide inference methods for the coefficients of interest in endogenous high-dimensional quantile regression models based on orthogonal score functions, which mitigate the effects of moderate selection errors. Monte Carlo simulations also show that our estimator performs well under high-dimensional controls. In addition, we could accommodate more than one endogenous treatment depending on different economic settings. Finally, we employ our model to investigate the impact of compulsory schooling on earnings using 1530 instruments for education based on Angrist and Krueger (1991)'s research. We find that high-dimensional quantile estimates are smaller than 2SLS and OLS estimates. Schooling returns appear to be lower than in previous studies.</p>
</div>
</details>

<details class="no-border">
<summary>Presentation</summary>
<div class="abstract-content">
<p>
  <a href="/files/CFQR_Presentation.pdf" target="_blank">IAAE-Turin 2025</a>, 
  Seminar in SUFE 2024, 
  Workshop in HKUST 2024
</p>
</div>
</details>
</div>

<style>
details.no-border {
    margin: 8px 0;
    border: none;
    background: transparent;
}
details.no-border summary {
    font-weight: 600;
    cursor: pointer;
    padding: 6px 0;
    color: #2c3e50;
    background: transparent;
    border: none;
    transition: color 0.2s ease;
}
details.no-border summary:hover {
    color: #4285f4;
}
.abstract-content {
    padding: 8px 0;
    line-height: 1.6;
}
.abstract-content p {
    margin: 0;
    color: #555;
    text-align: justify;
}
a[target="_blank"] {
    color: #1a0dab;
    text-decoration: none;
}
a[target="_blank"]:hover {
    color: #1a0dab;
    text-decoration: underline;
}
.abstract-content a {
    color: #1a0dab;
    text-decoration: none;
}
.abstract-content a:hover {
    color: #1a0dab;
    text-decoration: underline;
}
.working-paper-section {
    margin-bottom: 30px;
}
.third-paper-section {
    margin-top: 25px;
}
</style>
