---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

## Job Market Paper

**<a href="/files/QRCS.pdf" target="_blank">Quantile Regression with Censored Selection and Many Controls</a>**  
(with Songnian Chen and Junlong Feng)

<details>
<summary>Abstract</summary>
<div class="abstract-content">
<p>This paper develops a quantile regression model with censored selection in a high-dimensional setting (HD-QRCS). We introduce a semiparametric nonlinear least squares type estimator for the copula parameters as an alternative to the estimator based on the conventional method-of-moments criterion. Our approach is based on the quantile selection model proposed by Arellano and Bonhomme (2017) to correct for sample selection. This method ensures convergence to the global minimum and avoids iterative procedures. Our estimation procedures consist of three steps: the first two employ \(\ell_1\)-penalized quantile regression and hard-thresholding in order to mitigate estimation bias and achieve oracle rate of convergence. Lastly, we obtain copula parameters and coefficients of interest. We establish uniform convergence rates for the proposed estimators and discuss the properties of variable selection. Monte Carlo simulations show that our estimators perform well under many controls. We apply our method to American Community Survey (ACS) data from 2001 to 2023 to study wage inequality.</p>
</div>
</details>

## Working Paper

**Semiparametric Estimation of the Copula Parameter in a Quantile Selection Model**  
(with Songnian Chen and Junlong Feng)  
*Status: Reject and resubmit, Journal of Econometrics*

<details>
<summary>Abstract</summary>
<div class="abstract-content">
<p>Arellano and Bonhomme (2017) (henceforth AB) developed a quantile selection framework and proposed a two-step semiparametric estimator for the copula parameter, which characterizes the extent of sample selection bias. In this paper, we propose a new semiparametric nonlinear least squares type estimator for the copula parameter. Our approach differs from that of AB in two distinct ways. First, unlike AB where they first estimate the copula parameter and the slope coefficients in the outcome equation iteratively since the latter depends on the former, our approach breaks such dependence via a novel reparameterization scheme and avoids such iteration. This greatly simplifies implementation and improves numerical results. Second, while the quantile selection framework is characterized by a set of conditional moment restrictions, AB's estimator of the copula parameter is based on a finite number unconditional moment restrictions. In practice, moment based estimator could encounter the global identification problem, leading to possibly poor finite sample performance. In contrast, we take a semiparametric nonlinear least squares type approach, which works with conditional moments directly, essentially making use of an infinite number of unconditional moment conditions. Our identification requirement is consequently common in traditional nonlinear regression analysis, and our identification result is expected to be more robust than identification based on a finite number of moment conditions employed by AB. We show that our estimator is consistent and asymptotically normal. Simulation results suggest superior performance of our estimator over AB's estimator.</p>
</div>
</details>

**<a href="/files/CFQR.pdf" target="_blank">Endogenous High-Dimensional Quantile Regression: A Control Function Approach</a>**

<details>
<summary>Abstract</summary>
<div class="abstract-content">
<p>This paper presents a double selection estimator based on the Control Function approach for estimating a high-dimensional Quantile Regression model with endogeneity (CFQR). We have several advantages over the Instrumental Quantile Treatment Effect model (henceforth IVQR), which was proposed by Chernozhukov and Hansen (2005). First, our model is computationally simpler than high-dimensional IVQR under general conditions. IVQR relies on a hypothesized value for coefficients of interest in the first step of estimation. The iterative nature of this process is costly, especially when dealing with big data. In contrast, our methods use the function of residuals obtained from the previous step as an additional exogenous control, which is more practical for application. Furthermore, we provide inference methods for the coefficients of interest in endogenous high-dimensional quantile regression models based on orthogonal score functions, which mitigate the effects of moderate selection errors. Monte Carlo simulations also show that our estimator performs well under high-dimensional controls. In addition, we could accommodate more than one endogenous treatment depending on different economic settings. Finally, we employ our model to investigate the impact of compulsory schooling on earnings using 1530 instruments for education based on Angrist and Krueger (1991)'s research. We find that high-dimensional quantile estimates are smaller than 2SLS and OLS estimates. Schooling returns appear to be lower than in previous studies.</p>
</div>
</details>

<details>
<summary>Presentation</summary>
<div class="abstract-content">
<p>
  <a href="/files/CFQR_Presentation.pdf" target="_blank">IAAE-Turin 2025</a>, 
  Seminar in SUFE 2024, 
  Workshop in HKUST 2024
</p>
</div>
</details>

<style>
details {
    margin: 15px 0;
    border: 1px solid #e1e8ed;
    border-radius: 8px;
    background: #fafbfc;
    transition: all 0.3s ease;
}
details:hover {
    border-color: #4285f4;
    box-shadow: 0 2px 8px rgba(66, 133, 244, 0.1);
}
details summary {
    font-weight: 600;
    cursor: pointer;
    padding: 12px 16px;
    color: #2c3e50;
    background: #fff;
    border-radius: 8px;
    transition: background 0.2s ease;
}
details summary:hover {
    background: #f8f9fa;
}
details[open] summary {
    border-bottom: 1px solid #e1e8ed;
    margin-bottom: 0;
    border-radius: 8px 8px 0 0;
}
.abstract-content {
    padding: 16px;
    background: #fff;
    border-radius: 0 0 8px 8px;
    line-height: 1.6;
}
.abstract-content p {
    margin: 0;
    color: #555;
}
.paper-links {
    margin: 10px 0 15px 0;
}
.paper-links .btn {
    margin-right: 8px;
    margin-bottom: 5px;
}
.btn--info {
    background-color: #17a2b8;
    border-color: #17a2b8;
}
.btn--info:hover {
    background-color: #138496;
    border-color: #117a8b;
}
a[target="_blank"] {
    color: #4285f4;
    text-decoration: none;
}
a[target="_blank"]:hover {
    text-decoration: underline;
}
</style>


