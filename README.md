 ![image](https://github.com/user-attachments/assets/d47074e4-40ad-477e-8418-2583ebbba92f)


## About
[GoCodeGreen](https://gocode.green/) is a ClimateTech company focused on helping to decarbonise the digital world in which we all now live. We have created an award-winning calculation and decisioning engine that supports the creation of a Digital Carbon Reduction Plan™, all built on the standards set by the [Greenhouse Gas Protocol ICT Sector Guidance](https://ghgprotocol.org/sites/default/files/2023-03/GHGP-ICTSG%20-%20ALL%20Chapters.pdf) (GHGP-ICTSG), [Product](https://ghgprotocol.org/sites/default/files/standards/Product-Life-Cycle-Accounting-Reporting-Standard_041613.pdf) and [Scope 3](https://ghgprotocol.org/sites/default/files/standards/Corporate-Value-Chain-Accounting-Reporing-Standard_041613_2.pdf) Standards. We offer a cohesive, fully integrated, and connected approach and methodology with API-based solutions for clients who are ‘data ready’ to support a scaled decarbonisation of ICT and digital. For many digital-first organisations committed to achieving their net-zero target, their use of ICT can be one of their largest contributors to their Scope 3 emissions. 

This document provides an overview of corporate carbon accounting and outlines how GoCodeGreen (GCG) implements the GHG Protocol's Guidance and ISO Standard's Software Carbon Intensity (SCI) specification.

Click [here](https://gocode.green/) to find out more. For enquiries, contact us [here](https://gocode.green/contact-us/).

# Introduction to Carbon Measurement
GCG is focused on helping organisations measure and reduce the carbon emissions produced by their ICT and digital products. This process includes defining the boundaries of carbon emissions across Scope 1, 2, and 3 outlined by the GHG Protocol, with Scope 3 being the most challenging as it involves indirect emissions from the value chain. Therefore, GCG utilises assessment data inputs from infrastructure, hardware and software screening, digital product life cycle analysis (LCA), and functional unit calculation to measure the carbon footprint of ICT products and services, addressing the complexity of calculating services, supply chains, and shared resources. This enables measurement, ratings, benchmarking, and actionable insights for reduction and efficiency improvements to inform the creation of a client-specific Digital Carbon Reduction Plan (DCRP)™.

The GCG approach adheres to the [Greenhouse Gas Protocol ICT Sector Guidance](https://ghgprotocol.org/sites/default/files/2023-03/GHGP-ICTSG%20-%20ALL%20Chapters.pdf) (GHGP-ICTSG), [Product](https://ghgprotocol.org/sites/default/files/standards/Product-Life-Cycle-Accounting-Reporting-Standard_041613.pdf) and [Scope 3](https://ghgprotocol.org/sites/default/files/standards/Corporate-Value-Chain-Accounting-Reporing-Standard_041613_2.pdf) Standards ensuring full coverage across all ICT categories. This consists of Desktop Managed Services, Telecoms and Network Services, Cloud and Data Centre Services, and Software. The general approach for calculating GHG emissions, defined by the GHGP-ICTSG, is to describe the service's definition and boundaries and enumerate the constituent elements that make it up. With elements assessed individually, the total impact can be assessed by summing the impact of all the individual building blocks. Thus, the equation for GHG impact is to multiply the activity data by the appropriate emission factor:

  _**GHG Impact (kg CO2e) = Activity Data (unit) × Emission Factor (kg CO2e/unit)**_

Additionally, GCG’s Software Carbon Intensity (SCI) measurement methodology fully complies with the [ISO/IEC 21031:2024 Information Technology Standard for SCI Specification](https://www.iso.org/standard/86612.html#:~:text=This%20document%20describes%20a%20methodology,of%20an%20application's%20sustainability%20credentials.), where calculations for operational emissions, embodied emissions, and functional unit conversion are used to generate an SCI score. This is placed against a baseline comparison that GCG can track and improve over time. The equation used to calculate the SCI value of a software system is:

_**SCI = C per R**_

Where **C** is the total amount of carbon the software causes to be emitted and all the elements in the SCI equation scale by the same functional unit of **R** (e.g., carbon emissions per additional user, API-call, or ML training run).

_“The most rigorous approach to identifying priority activities is to use initial GHG estimation (or screening) methods to determine which scope 3 activities are expected to be most significant in size. A quantitative approach gives the most accurate understanding of the relative magnitudes of various scope 3 activities.”_
-	GHG Protocol Scope 3 FAQ

  [![image](https://github.com/user-attachments/assets/732a1031-95c3-4f76-a7b6-a72384ef1a15)](https://gocode.green/our-services-digital-decarbonisation/)

 **Click the image to visit Our Services**

# The Greenhouse Gas Protocol – ICT Sector Guidance

The [Greenhouse Gas Protocol ICT Sector Guidance (GHGP-ICTSG)](https://ghgprotocol.org/sites/default/files/2023-03/GHGP-ICTSG%20-%20ALL%20Chapters.pdf) provides guidance and accounting methods for the calculation of greenhouse gas (GHG) emissions for information and communication technology (ICT) products, with a focus on ICT services. In the Sector Guidance, ICT follows the OECD definition:

_“ICT products must primarily be intended to fulfil or enable the function of information processing and communication by electronic means, including transmission and display.”_

The Guidance aims to provide a practical approach to the GHG assessment of ICT products by providing a consistent and pragmatic approach. While this Sector Guidance is in conformance with the Product Standard it provides more details and specificity relevant to the ICT sector. The GHG Protocol [Product](https://ghgprotocol.org/sites/default/files/standards/Product-Life-Cycle-Accounting-Reporting-Standard_041613.pdf) and [Scope 3](https://ghgprotocol.org/sites/default/files/standards/Corporate-Value-Chain-Accounting-Reporing-Standard_041613_2.pdf) Standard both take a value chain or life cycle approach to GHG accounting and were developed simultaneously. The Scope 3 Standard accounts for value chain emissions at the corporate level, while the Product Standard accounts for life cycle emissions at the individual product level. Therefore, ICT Sector Guidance supplements the Product Standard, similarly following a life cycle approach to the assessment of ICT products and services. The methodologies presented are also applicable to the categories of the Scope 3 Standard that relate specifically to products.


[![Screenshot 2024-08-22 at 12 43 52](https://github.com/user-attachments/assets/f4be38e8-5b6c-465b-94c2-4db73c9316d0)](https://ghgprotocol.org/sites/default/files/2023-03/GHGP-ICTSG%20-%20ALL%20Chapters.pdf)

**Click the image to visit the Sector Guidance**

# The ISO Standard

The [ISO/IEC 21031:2024 Information Technology Standard for SCI Specification](https://www.iso.org/standard/86612.html#:~:text=This%20document%20describes%20a%20methodology,of%20an%20application's%20sustainability%20credentials.) is a document that describes a methodology for calculating the rate of carbon emissions for a software system – its SCI score. As a score rather than a total, lower numbers are better than higher numbers and reaching 0 is impossible. The purpose of this score is to increase awareness and transparency of an application’s sustainability credentials. The score will help software practitioners make better, evidence-based decisions during system design, development, and deployment, that will ultimately minimise carbon emissions. A reliable, consistent, fair and comparable measure allows targets to be defined during development and progress to be tracked.

Alongside the GHGP-ICTSG, Product and Scope 3 Standards, this is a standardised measurement for ICT carbon emissions calculations which GCG has adopted as the standardised measure for SCI, Function Point analysis and associated International Organisation for Standardisation. Ultimately, the SCI specification is used to define the methodology for calculating the rate of carbon emissions for a software system.


![Screenshot 2024-08-20 at 16 03 07](https://github.com/user-attachments/assets/9030cc9d-4435-4708-be35-9a808594962e)



# The Importance of Measurement

_“If you can't measure it, you can't improve it.”_
-	Peter Drucker

Accurate carbon measurement and accounting are the first steps on the net-zero journey. With GCG’s standards-based calculation methodology, you can quickly uncover meaningful emissions insights. Those insights will form a clear roadmap for short-term wins and long-term success and are all clearly presented in detailed product-level reports and an overall aggregated DCRP™. The purpose is to help users and developers make informed choices about which tools, approaches, architectures, and services they use in the future.

Carbon accounting is significant due to ICT's potential for avoiding GHG emissions through the ‘enabling effect’. Thus the Guidance addresses this in the following points:
* Multiple components for ICT equipment
* Complex and long supply chains for ICT equipment
* Complex nature of ICT services across their life cycle
* Often bespoke and tailored characteristics of ICT services to meet specific customer requirements
* Allocation of resource use to ICT services, which typically share resources 
* Significant in-use stage of ICT products 
* Uncertainty surrounding the measurement of the use stage
* Enabling effect of ICT products

# GCG Methodology

![image](https://github.com/user-attachments/assets/aeaa51b6-f3de-4f97-a6bf-39b5da9ea385)

All mapping is linked to Stage E to ensure appropriate GCGIDs are linked.

## A.	Screening Mapping
* Client-specific ICT screening data mapped to the appropriate ICT service category and hardware device types by specification, location, quantity, and where relevant, workload profiles and operational activities. In addition, usage patterns, hardware retention duration, and service availability are used as controlling variables and supplied to the calculation engine as input.

## B.	Software Lifecycle Mapping
* Client and software product-specific data are mapped to the appropriate life cycle stage alongside associated hardware, network, hosting characteristics, workload patterns, software engineering factors, and people-related data. Consumer usage patterns, service requirements, availability, and location are used as controlling variables and supplied to the calculation engine as input.

## C.	Map Activity Metrics
* Activity metrics related to ICT category usage and software product development and use are mapped, covering factors such as developer effort, utilisation levels of compute resources, usage patterns, and location and duration of activities within each relevant ICT service category or product life cycle stage.

## D.	Map Calculation Parameters and Variables
* Once screening and product- and activity-related data inputs are mapped to the ICT category and product life cycle stage, they are mapped to the appropriate calculations. The calculations require mapped parameters and variables captured by the client assessment to accurately align the data input to the correct calculation. There are currently c.1000 parameters and variables across the different ICT screening categories and different product life cycle stages that are mapped within the calculation engine.

## E.	Map to GCGID Taxonomy
* The GoCodeGreen Identifier, or GCGID, is used to create a common taxonomy against which all data inputs and calculated outputs are mapped. The taxonomy is used to connect linked GCGIDs and action to ensure that reduction and efficiency opportunities can be tracked and traced from the product to the ICT category and also to the relevant emission scope category. This GCGID taxonomy also drives the data structure for our API inbound and outbound services.

## F.	Convert Units
* Once a GCGID is assigned to an activity that is being calculated, the GoCodeGreen engine has to check that the activity’s physical unit matches the emission factor or expected variables of the calculation that goes with the GCGID.

If the activity provided is expressed in the default unit of that specific activity category, e.g. tCO2e/kWh for an electricity-related activity, this quantity can be directly used in combination with the matched emission factor. If the unit provided for an activity deviates from the default, it first has to be converted into the equivalent default unit, e.g., converting kilograms into tonnes or days into months.

## G.	Calculation Engine
* The GoCodeGreen calculation methodology sits within an ‘engine’ that processes defined input formats related to ICT and digital activity data captured during the assessment process.

This enables the calculation of all possible energy and activity flows related to the use of ICT and the digital products and services that utilise the hardware and devices within each relevant category of ICT. This is calculated over the course of a reporting period (for example, days in each release cycle) and yields the most granular view of the ICT and digital product carbon footprint. 

At the highest level, the calculation of the carbon emissions for an activity follows the formula below: 

**E [tCO2e] = Q [unit] * EF or AV [tCO2e/unit]**

Where, **E**: Emissions; **Q**: Quantity representing the activity; **EF**: Emission Factor or **AV**: Activity Variable(s) 

Therefore, calculating emissions is equivalent to multiplying the quantity of an activity with an emission factor or activity variable(s) that represents the emissions per unit of activity. Because emission factors are not readily available across ICT and digital activities, additional calculations are performed to derive the emissions impact using supplier-specific and research-based data. These calculated emissions are combined to form the estimated screened results at the ICT category level or the in-life cycle stage emissions for software products. 

The calculation engine is made up of a series of interconnected models, and the main components have the following tasks: 
* Calculate Impact
* Calculate Actions
* Identify and Map Functional Units
* Calculate Ratings
* Calculate Benchmark
* Calculate Carbon Intensity / Carbon Efficiency
* Biodiversity Impact Indicator

## H.	Map to Scope 1, 2, and 3
* One of the calculation engines’ primary tasks is accurate mapping of activities and the resulting calculated impact and action data. The mapping establishes whether the reporting company directly or indirectly owns each activity based on the assessment data collected during pre-calculation. The use of ICT and digital can be complex and involve a long chain of direct and indirectly attributable processes that are specific to the technology choices made by a client. This mapping exercise ensures that the appropriate scope alignment, particularly the categories of scope 3, is completed as accurately as possible.

## I.	Build ICT Screening and Software Product LCA Reports
* The data output from the calculation engine is used to generate client-facing reports covering each screened ICT category and each software product assessment completed.

Reports for Cloud and Data Centre Services are separated for 'on-premise' data centres vs. public cloud-provisioned hosting services (with four variants covering AWS, Azure, GCP, and OCI). Reports for software product life cycle assessments cover the baseline measurement and actionable insights for each life cycle stage. GoCodeGreen provides further analysis, advisory services, and recommended prioritisation of action based on their experience in technology and software development.

For clients that are ‘data-ready’ and choose to use our API services, the option of receiving calculated data, ratings, benchmark results, and actions directly via the outbound API is available. To help clients understand their ‘data readiness’ the GoCodeGreen assessment process captures the source data point for each parameter and variable required by the calculation engine so that full analysis can be completed during an initial ‘discovery’ phase. 

## J.	Build a Digital Carbon Reduction Plan
* The data from the ICT Screening estimates and multiple software product assessments is aggregated in this final phase to generate a Digital Carbon Reduction Plan (DCRP)™. This is completed in accordance with the technical guidance PPN 06/21. 

Core to generating the DCRP™ are the following calculations: 
1.	The baseline year for GHG emissions related to ICT and digital across each ICT category and software products.
2.	Scope 1, 2, and 3 mapping with alignment to the specified scope 3 categories identified by PPN 06/21.
3.	Target setting: calculated data is mapped to (currently) six major aggregated decarbonisation levers and, using client-determined percentage reduction targets, mapped over a time horizon ending in 2030.

The DCRP™ brings all of the calculated output together to create the context for decarbonising ICT and digital, establishing an independently assessed baseline in accordance with the GHGP-ICTSG, and identifying product-level action through software. This can form the basis of an organisation-level sustainable IT strategy and provides the process for reassessment on an annual basis to meet new reporting standards.

GoCodeGreen has direct experience adhering to [PPN 06/21](https://assets.publishing.service.gov.uk/media/62066d5ae90e077f7dec749e/PPN-0621-Taking-account-of-Carbon-Reduction-Plans-Jan22__1_.pdf), having published our organisation-level CRP for the last two years. Our independently assessed CRP has enabled us to achieve our TechZero commitments as verified in 2021/22 and 2022/23.

# A Proven Solution
GCG’s solutions have identified emission reduction opportunities ranging from 26-53% and achieved operational cost efficiencies in range 15-25% across the approx. 40 private and public sector organisations we have worked with so far.

Click [here](https://gocode.green/) to find out more. For enquiries, contact us [here](https://gocode.green/contact-us/).

![image](https://github.com/user-attachments/assets/d80434c3-83ef-4644-8f74-7d7cb6ea8c57)
