# Privacy Cards Resource List

## (Central) Differential Privacy

### General Audiences

D. Desfontaines, ["A friendly, non technical introduction to differential privacy"](https://desfontain.es/blog/friendly-intro-to-differential-privacy.html), last updated 2023

S. Garfinkel, [*Differential Privacy*](https://direct.mit.edu/books/book/5935/Differential-Privacy) (The MIT Press Essential Knowledge Series). Cambridge, MA, USA: MIT, 2025.

[NIST's Differential Privacy Blog Series](https://www.nist.gov/itl/applied-cybersecurity/privacy-engineering/collaboration-space/blog-series/differential-privacy) (particularly Posts 1-6)

J. Near, D. Darais and N. Lefkovitz, ["Guidelines for Evaluating Differential Privacy Guarantees"](https://www.nist.gov/publications/guidelines-evaluating-differential-privacy-guarantees), National Institute for Standards and Technology, Gaithersburg, MD, USA, Rep. Special Publication (NIST SP) - 880-226, Mar. 2025. 

A. Wood, M. Altman, A. Bembenek, M. Bun, M. Gaboardi, J. Honaker, K. Nissim, D. O'Brien, T. Steinke, and S. Vadhan, ["Differential Privacy: A Primer for a Non-Technical Audience"](https://scholarship.law.vanderbilt.edu/jetlaw/vol21/iss1/4/ ), in *21 Vanderbilt Journal of Entertainment and Technology Law 209*, 2020.

### For Programmers

### Academic Papers

C. Dwork and A. Roth, ["The Algorithmic Foundations of Differential Privacy"](https://dl.acm.org/doi/10.1561/0400000042) in *Foundations and Trends in Theoretical Computer Science, Volume 9, Issue 3-4*, August 2014. (access a PDF [here](https://projects.iq.harvard.edu/files/privacytools/files/the_algorithmic_foundations_of_differential_privacy.pdf)) 

C. Dwork, A. Smith, T. Steinke and J. Ullman, ["Exposed! A Survey of Attacks on Private Data"](https://www.annualreviews.org/content/journals/10.1146/annurev-statistics-060116-054123) in *Annual Review of Statistics and Its Applications, Volume 4*, Mar. 2017, pp. 61-84.

## Local Differential Privacy

### General Audiences

C. Canonne, ["Trust Models, and Notions of Privacy"](https://differentialprivacy.org/trustmodels/), differentialprivacy.org, 2020

OpenDP's ["Differential Privacy Deployments Registry"](https://registry.oblivious.com/), 2024 
- A continually updated list of systems that have been deployed with differential privacy. It outlines the specific model they used (e.g. local or central), as well as the value of epsilon, so practictioners can learn from how some of the leading tech companies are deploying differential privacy for their data releases.

### For Programmers

### Academic Papers

S. Vadhan, ["The Complexity of Differential Privacy"](https://link.springer.com/chapter/10.1007/978-3-319-57048-8_7), in *Tutorials on the Foundations of Cryptography*, Y. Lindell, Ed., 2017, pp. 347-450 (access a PDF [here](https://salil.seas.harvard.edu/publications/complexity-differential-privacy))

S. P. Kasiviswanathan, H. K. Lee, K. Nissim, S. Raskhodnikova and A. Smith, ["What Can We Learn Privately?"](https://epubs.siam.org/doi/10.1137/090756090) in *SIAM Journal on Computing Volume 40, Issue 3, 2011. 

J. C. Duchi, M. I. Jordan and M. J. Wainwright, ['Local Privacy and Statistical Minimax Rates'](https://www.computer.org/csdl/proceedings-article/focs/2013/5135a429/12OmNBqMDpF) in *2013 IEEE 54th Annual Symposium on Foundations of Computer Science (FOCS)*, Berkeley, CA, USA, 2013, pp. 429-438 (access a PDF [here](https://arxiv.org/pdf/1302.3203v2))

S. L. Warner, ["Randomized Response: A Survey Technique For Eliminating Evasive Answer Bias"](https://www.jstor.org/stable/2283137?seq=1) in *Journal of the American Statistical Association, Vol 60, No. 309, Mar. 1965, pp. 63-69 

## K-Anonymity

### General Audiences

A. Gadotti, L. Rocher, F. Houssiau, A. Cretu and Y. De Montjoye, ["Anonymization: The Imperfect Science of Using Data While Preserving Privacy"](https://www.science.org/doi/10.1126/sciadv.adn7053) in *Science Advances, Vol. 10, No. 29*, London, UK, Jul. 2024.  

I. Wagner and D. Eckhoff, ["Technical privacy Metrics: A Systematic Survey"](https://dl.acm.org/doi/abs/10.1145/3168389) in *ACM Computing Surveys (CSUR), Volume 51, Issue 3*, New York, NY, USA, Jun. 2018, pp. 1-38 
- Only the section about k-anonymity is relevant, but this paper also contains great short summaries of other prominent privacy preserving techniques 

### For Programmers

Mondrian, Incognito, sequential release

### Academic Papers

L. Sweeney, ["k-anomymity: A Model for Protecting Privacy"](https://dl.acm.org/doi/10.1142/S0218488502001648) in *International journal of Uncertainty, Fuzziness and Knowledge-Based Systems, Volume 10, Issue 5*, NJ, USA, Oct. 2002, p. 557-570. (access a PDF [here](https://epic.org/wp-content/uploads/privacy/reidentification/Sweeney_Article.pdf)

C. C. Aggarwal, ["On k-anonymit and the Curse of Dimensionality"](https://dl.acm.org/doi/10.5555/1083592.1083696) in *VLDB '05: Proceedings of the 31st International Conference on Very Large Data Bases*, Trondheim, Norway, Aug. 2005, pp. 901-909. 

## Secure Multi-Party Computation (MPC)

### General Audiences

[NIST's post about using cryptographic methods to complement differential privacy](https://www.nist.gov/blogs/cybersecurity-insights/privacy-enhancing-cryptography-complement-differential-privacy) 

### For Programmers

### Academic Papers

D. Chaum, C. Crepeau and I. Damgard, ["Multiparty Unconditionally Secure Protocols"](https://dl.acm.org/doi/10.1145/62212.62214) in *STOC '88: Proceedings of the Twentieth Annual ACM Symposium on Theory of Computing*, New York, NY, USA, Jan. 1988, pp. 11-19. 

M. Pettai, P. Laud, ["Combining Differential Privacy and Secure Multiparty Computation"](https://dl.acm.org/doi/10.1145/2818000.2818027) in *ACSAC '15: Proceedings of the 31st Annual Computer Security Applications Conference*, Los Angeles, CA, USA, Dec. 2015, pp. 421-430. 

## Demographic Coherence Enforcement (DCE)

### General Audiences

Palak Jain ["Enforcing Demographic Coherence: A Harms-Aware Framework for Reasoning about Private Data Release"](https://sites.google.com/view/tcsplus/welcome/past-talks/2024-2025?authuser=0#h.pu1si0na2uta)
- A good presentation about Demographic Coherence Enforcement (with slides available)

### Academic Papers

M. Bun, M. Carmosino, P. Jain, G. Kaptchuk and S. Sivakumar, ["Enforcing Demographic Coherence: A Harms Aware Framework for Reasoning about Private Data Release"](https://arxiv.org/abs/2502.02709), Feb. 2025.
