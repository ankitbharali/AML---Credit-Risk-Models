# Python-Credit-Risk-Modeling
 
### What is a credit risk?
•	The likelihood that a borrower would not repay their loan to lender
•	When a borrower fails to replay loan
•	The lender will have to sustain substantial cost in an effort to recover outstanding debt - called collection cost
 
### Risk based pricing 
•	Based on credit risk associated with the particular client, banks decide the % interest rate and size of the collateral
•	Lending to borrowers with high probability default is one of the main reasons of financial crisis. Example 2008, 
o	Factor - high default rate of sub-prime mortgages; low interest rate; loans were provided with 100% or more value of the home; demand for homes increased -> selling rice increased
o	Mortgage backed securities lost value
o	Big banks holding this instruments got affected - Le Mans Brother
 
### Regulatory rule 
•	Lender must assess credit risk associated with each borrower
•	Lenders know certain amount of credit risks is always associated with each/every client
•	It is important to estimate expected loss - amt of money a lender lose by lending to a borrower. 
•	There are many models, but established credit risk model has 3 components
o	PD (Probability of default)
o	LGD (Loss given default)
o	EAD (Exposure at default)
 
#### PD (Probability of default): 
•	The borrower inability to repay his/her debt in full or on-time
•	Estimate of a borrower to likelihood the borrower will default

#### Loss given default (LGD)
•	Loss of an asset due to borrowers’ default
•	The proportion of the total exposure that cannot be recovered by the lender once a default has occurred 

#### EAD (Exposure at default)
•	Total value that a lender is exposed to when a borrower defaults i.e. maximum amount that a bank can lose if a borrower defaults

Example: A borrower wants to buy a house 
Price = $500,000
(Agreement) Bank funds 80% (loan to value) = $400,000
Borrower repaid = $40,000
Outstanding balance = $400,000 - $40,000 = $360,000
When a borrower defaults, total value that a lender is exposed to is $360,000. This is Exposure at default.
Assume that the banks can sell the house is at $342,000, then 
Loss given default = (EAD - $342,000)/EAD
 	Assume that there is an empirical evidence that one in four homeowners have defaulted 
  o	PD = 1/4
 	Expected Loss (EL) = PD * LGD * EAD, i.e. 25% * 5% * $360,000 = $4,500
 
#### Capital Adequacy/Regulations and Basel III accord
•	Govt. regulators impose certain requirements for banks to make sure bank conduct their business without risking the stability of the economy system
•	Regulators set rules
 o	Regulate bank operations & hence reduce bank risky behaviour
 o	Guarantee to the public that banking system is in good health
•	Capital Adequacy: Banks require to hold sufficient capital to absorb capital losses from default. This obligation is called "Capital Requirement"
•	CAR(Capital Adequacy ratio) = Capital / Risk-weighted assets (loans)
•	Basel III accord - primary objective is to ensure capital allocation. Greater the risk the bank exposed to greater amount of capital it needs to hold
o	Three pillars of Basel III - 
o	Market discipline 
o	Supervisory review
o	Minimum Capital Requirement
Two approaches
1.	Standardized approach
2.	Internal ratings based approach (IRB)
•	Foundation internal rating based (F-IRB)
•	Advanced internal rating based (A-IRB)
•	Basel III accord prescribes regulators should allow banks to choose from 3 different approaches to calculate/modelling credit risk i.e. calculating & modelling each of the three components of expected loss
o	Standardized approach
o	Foundation internal rating based (F-IRB)
o	Advanced internal rating based (A-IRB)
•	Capital requirements are calculated differently in 3 approaches
 	SA	F-IRB	A-IRB
PD	External data	Internally  calculated	Internally  calculated
LGD	External data	External data	Internally  calculated
EAD	External data	External data	Internally  calculated
o	External data comes from credit rating agencies such as FICO, S&P, Moody's, Fitch (for firms)
o	Two major credit reporting agency that collects data from FICO
o	Equifax
o	TransUnion
o	Credit score ranges from 300 to 800
o	For firms, credit cards & consumer loans, banks should hold around 75% of the total exposure * CAR (Capital adequacy ratio)
o	For secured residential property, banks should hold around 35% of the total exposure * CAR (Capital adequacy ratio)
 
•	The more precise banks estimate expected -- Less capital is needed to hold -- more new business bank can generate

