# Legacy Code and Technical Debt
## A model to help decide to refactor or rewrite

After years of passionate investment into an application, there comes a time when you will be challenged
to push on and refactor a problematic platform or to rewrite it.  This is a difficult and scary proposition.

Being an engineer, I wanted to create a model that could help with the decision process.  Included here
is a simple model you can take and modify to enhance your own analysis.  

Note, there are MANY intertwined factors that should influence your decision, and this analysis is only a small part.
Its accuracy is limited, but the mental model and the thought process that goes into applying it to your
situation can be very valuable in the process.

The Excell based model is here: [Rebuild-analysis-model.xlsx](Rebuild-analysis-model.xlsx)

Please comment or provide feedback if you use it.  

### Development Velocity comparison for a rewrite
![Rebuild vs. Rewrite velocity](feature-velocity.png)

### Relative Costs of development over time
<a href="https://danjamk.github.io/app-rewrite-analysis/feature_cost_curve.html" target="_blank">Interactive Relative cost chart</a>

![Relative Cost](relative-costs.png)


# References

## Technical Debt and Development Cost Research

1. **TinyMCE White Paper: Opportunity Cost of Technical Debt** (2023)  
   URL: https://www.tiny.cloud/technical-debt-whitepaper/  
   *Discusses the magnitude of technical debt issues, citing Microsoft's 2017 study showing 58% of developer time spent on code comprehension, and McKinsey's finding that 30% of CIOs believe more than 20% of technical budget is diverted to tech debt resolution.*

2. **Sonar: Cost of Technical Debt - New Research** (July 19, 2023)  
   URL: https://www.sonarsource.com/blog/new-research-from-sonar-on-cost-of-technical-debt/  
   *Original research examining 200+ projects over 12 months, calculating technical debt cost at $306,000 per year for a project of one million Lines of Code, equivalent to 5,500 developer hours spent on remediation.*

3. **CodeScene: The Business Costs of Technical Debt** (PDF)  
   URL: https://codescene.com/hubfs/calculate-business-costs-of-technical-debt.pdf  
   *Provides metrics linking code quality to business impact and automated code review methodologies.*

4. **Wikipedia: Technical Debt** (Updated May 1, 2025)  
   URL: https://en.wikipedia.org/wiki/Technical_debt  
   *Comprehensive overview of technical debt concept, including Ward Cunningham's original definition and Manny Lehman's architectural metaphor from 1980.*

5. **arXiv: Technical Debt Management - The Road Ahead for Successful Software Delivery** (2024)  
   URL: https://arxiv.org/html/2403.06484v1  
   *Academic paper providing industry perspectives on technical debt management from Boeing, Department of Defense, QAware, and CGI, summarizing 532 unique primary studies.*

6. **McKinsey: Breaking Technical Debt's Vicious Cycle to Modernize Your Business** (April 25, 2023)  
   URL: https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/breaking-technical-debts-vicious-cycle-to-modernize-your-business  
   *Research showing companies pay additional 10-20% to address tech debt, with tech debt accounting for 40% of IT balance sheets and 20-40% of technology estate value.*

7. **ScienceDirect: How Do Software Development Teams Manage Technical Debt? – An Empirical Study** (2016)  
   URL: https://www.sciencedirect.com/science/article/pii/S016412121630053X  
   *Empirical study of eight software development teams examining technical debt management strategies and maturity levels.*

8. **ScienceDirect: Prevalence, Common Causes and Effects of Technical Debt** (2021)  
   URL: https://www.sciencedirect.com/science/article/abs/pii/S0164121221002119  
   *Family of surveys with IT industry showing on average 25% of development effort is spent on technical debt-caused issues.*

9. **Gartner: Reduce and Manage Technical Debt**  
   URL: https://www.gartner.com/en/infrastructure-and-it-operations-leaders/topics/technical-debt  
   *Industry insights for infrastructure and IT operations executives on technical debt management.*

10. **Software Improvement Group: Technical Debt and Its Impact on IT Budgets** (March 26, 2025)  
    URL: https://www.softwareimprovementgroup.com/technical-debt-and-it-budgets/  
    *Analysis showing 10-20% of IT budgets redirected to dealing with technical debt, with legacy systems requiring specialized knowledge increasing maintenance complexity.*

## Software Maintenance and Development Costs

11. **PMC: Which Factors Affect Software Projects Maintenance Cost More?** (2013)  
    URL: https://pmc.ncbi.nlm.nih.gov/articles/PMC3610582/  
    *Study of medical software maintenance costs identifying 32 factors affecting maintenance expenses, with project characteristics ranked as most influential.*

12. **Mad Devs: Software Maintenance Costs - Factors & Ways to Reduce** (February 16, 2023)  
    URL: https://maddevs.io/customer-university/software-maintenance-costs/  
    *Practical guide showing software maintenance costs around $5,000 per month or $60,000 per year, with factors affecting pricing and reduction strategies.*

13. **The Register: Everyone Cites That 'Bugs Are 100x More Expensive to Fix in Production' Research, But the Study Might Not Even Exist** (July 22, 2021)  
    URL: https://www.theregister.com/2021/07/22/bugs_expense_bs/  
    *Investigation into the oft-cited IBM Systems Science Institute study, questioning the existence of the original research behind widely quoted bug cost statistics.*

14. **TestDevLab: The True Cost of Software Development** (2024)  
    URL: https://www.testdevlab.com/blog/cost-of-software-development  
    *Analysis showing maintenance costs ranging from 40% to over 90% of total software lifecycle costs, with one study finding only 21% of five-year costs were initial development.*

15. **SCIRP: On the Relationship Between Software Complexity and Maintenance Costs** (2013)  
    URL: https://www.scirp.org/journal/paperinformation?paperid=51631  
    *Academic paper exploring correlation between lines of code, bugs, and software maintenance expenses.*

16. **ScienceSoft: Software Maintenance Costs - How to Estimate and Optimize** (2024)  
    URL: https://www.scnsoft.com/software-development/maintenance-and-support/costs  
    *Industry guide showing complex on-premises enterprise software can consume 70-90% of total cost of ownership, while cloud-based apps typically demand 30-60%.*

17. **Dev Technosys: How To Analyze Software Maintenance Costs Accurate In 2024?** (November 1, 2024)  
    URL: https://devtechnosys.com/insights/software-maintenance-costs/  
    *Current analysis showing software maintenance services cost around 20-25% of license cost per year, with costs potentially reaching three times higher if not maintained regularly.*

18. **IT Jungle: Big Blue Raises IBM i Software Maintenance Fees Modestly** (March 1, 2020)  
    URL: https://www.itjungle.com/2020/03/02/big-blue-raises-ibm-i-software-maintenance-fees-modestly/  
    *Industry analysis of IBM software maintenance pricing showing enterprise software maintenance typically costs 20-25% of license price annually.*

19. **Baytech Consulting: Budgeting for Software Maintenance** (2024)  
    URL: https://www.baytechconsulting.com/blog/projecting-costs-in-software-maintenance  
    *Technical guide to COCOMO model and Function Point analysis for estimating software maintenance costs, including Annual Change Traffic calculations.*

20. **SoftwareOne: Brace Yourself for a 24% Price Hike on IBM Software** (August 16, 2023)  
    URL: https://www.softwareone.com/en/blog/articles/2023/08/16/latest-price-update-on-ibm-software  
    *Analysis showing IBM software prices increased 17-42% across regions over four years, with significant impact on IT budgets and business profitability.*

## Developer Velocity and Performance Research

21. **McKinsey: Developer Velocity - How Software Excellence Fuels Business Performance** (April 20, 2020)  
    URL: https://www.mckinsey.com/industries/technology-media-and-telecommunications/our-insights/developer-velocity-how-software-excellence-fuels-business-performance  
    *Comprehensive study of 440 large enterprises showing top-quartile Developer Velocity Index scores correlate with 4-5x faster revenue growth and 60% higher shareholder returns.*

22. **FullScale: How to Maintain Software Development Velocity Without Sacrificing Quality** (April 14, 2025)  
    URL: https://fullscale.io/blog/maintain-software-development-velocity/  
    *Research showing teams with high technical debt experience 25% slower development velocity, with organizations implementing comprehensive CI/CD seeing 21% higher velocity and 44% fewer production defects.*

23. **QSM: Long Term Trends from 40 Years of Completed Software Project Data** (December 12, 2022)  
    URL: https://www.qsm.com/articles/long-term-trends-40-years-completed-software-project-data  
    *Longitudinal study of 10,000+ projects showing developers today deliver about 40% as much new code per project as 40 years ago, with median project sizes declining significantly.*

24. **ResearchGate: Why Software Product Startups Fail and What to Do About It** (February 1, 2002)  
    URL: https://www.researchgate.net/publication/3970483_Why_software_product_startups_fail_and_what_to_do_about_it_Evolution_of_software_product_development_in_startup_companies  
    *Systematic mapping study of software development in startup companies, analyzing 43 primary studies and 213 software engineering work practices.*

25. **DesignLi: 7 Reasons Legacy Systems Are Holding Your Enterprise Back** (April 24, 2024)  
    URL: https://designli.co/blog/legacy-systems-hold-you-back  
    *Industry analysis of how legacy systems impact efficiency, security, and innovation in enterprise environments.*

26. **FrogSlayer: Software Development Velocity & How to Address It** (February 5, 2025)  
    URL: https://frogslayer.com/blog/velocity-software-development/  
    *Analysis of software development velocity challenges and the risks of using velocity as a primary performance metric.*

27. **Mechanical Orchard: $1.14 Trillion to Keep the Lights On - Legacy's Drag on Productivity** (2024)  
    URL: https://www.mechanical-orchard.com/insights/1-14-trillion-to-keep-the-lights-on-legacys-drag-on-productivity  
    *Comprehensive analysis showing 88% of businesses are hampered by legacy technologies, with 60-80% of IT budgets allocated to maintaining existing systems and 70% of digital transformation projects failing.*

28. **Michael's Coding Spot: Development Slowness in Big and Legacy Applications** (2024)  
    URL: https://michaelscodingspot.com/slow-development-in-big-companies/  
    *Practical analysis of why large enterprise applications move slowly, covering convoluted architecture, compliance concerns, and technical debt accumulation.*

29. **Develocity: Developer Velocity - How Software Excellence Fuels Business Performance (Study Review)** (March 13, 2023)  
    URL: https://develocity.io/developer-velocity-how-software-excellence-fuels-business-performance/  
    *Review of McKinsey study emphasizing disconnect between what leaders think drives software success versus actual factors, focusing on tools, culture, and talent management.*

30. **ResearchGate: Analysis of Legacy System in Software Application Development - A Comparative Survey** (February 1, 2016)  
    URL: https://www.researchgate.net/publication/298848237_Analysis_of_Legacy_System_in_Software_Application_Development_A_Comparative_Survey  
    *Systematic literature review of legacy system evolution toward Service-Oriented Architecture, analyzing 121 primary studies from 2000-2011.*

---

**Note:** The specific numerical progressions shown in the cost curves (e.g., 1x → 7.5x → 18x multipliers) represent synthesized patterns based on these research findings rather than direct empirical measurements from a single study. The research consistently shows that technical debt significantly increases development costs over time, but specific quantitative progressions vary by organization and context.