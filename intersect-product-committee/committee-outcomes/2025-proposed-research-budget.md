---
description: This page gives details to the proposed Research budget
---

# 2025 Proposed Research Budget

## Overview

The product committee agreed to break down the research budget bucket into 4 sub buckets:

* Academic research: This is aimed at funding all the mid and long-term academic forward-looking research. This will be useful in providing long-term direction to the ecosystem
* Product research: This is aimed at funding all the short and mid-term user and market research. This will be useful in providing concrete insights into user needs and problems, market gaps and opportunities, as well as collecting data to inform the 2025 proposed goals and the 5year vision
* Vision creation: This is aimed at funding all the work, effort, and expenses needed to create and facilitate the first version of an open and transparent process to create a dynamic 5-year vision for the Cardano ecosystem, effectively creating a structured community lead 'replacement' for the role that Charles Hoskinson had so far
* Product committee: This is aimed at funding the work and overhead this committee will have in supporting and managing the activities above

***

## Academic Research sub-bucket

### Overview

The Academic research bucket aims to fund all research activities that can provide long-term insights into the Cardano ecosystem. This will be guided by a five-year Strategic Research Agenda which adheres to an "evidence-based engineering" methodology focusing on scalability, sustainability, and interoperability. The methodology from initial design through to engineering implementation ensures a funnel of high-quality, efficient, and proven products and features that deliver long-term fundamental value to the Cardano ecosystem.\
To continue to position itself as a leading third-generation blockchain, Cardano requires a robust five-year research agenda that focuses on sustainability, scalability, and interoperability. This vision builds on Cardano's track record of 100% uptime, ensuring continuous improvement and maintaining its position at the forefront of blockchain technology. To achieve this, advances in certain focus areas are required including consensus algorithms, such as Ouroboros Omega, zero-knowledge proofs, quantum-resistant cryptography, and enhanced smart contract functionality. The goal is to reinforce Cardano's positioning and leadership that addresses global and societal challenges while driving innovation and maintaining high security and efficiency standards.

The impact of this planned approach is severalfold; a targeted and ever-growing presence in a global research community, and direct outputs in the form of papers, technical recommendations, and validated prototypes. Commercializing deep technologies such as Web3 cannot just be demand-led. Scientific and technical excellence, a prerequisite in Cardano's case, can take years to achieve by which time opportunities can be lost. Strategic investments in research areas with high potential for future innovation not only establish a strong foundation for growth but also create a competitive advantage through accelerating time to market. This enables opportunities to be seized in a timely manner and enables the resulting economic, societal, and environmental impact to be realized.

### Expected outcomes

The Vision and Impact plan for Cardano is committed to ensuring Cardano is able to meet and exceed the blockchain industry's aspirations. The plan is informed by impact assessments and extensive stakeholder consultations, reflecting on lessons learned over the past five years.&#x20;

RWG proposes 9 thematic focus areas, each outlining specific R\&D directions that will position Cardano as a global blockchain leader for the next decade and beyond. Within each focus area, we detail the motivation, technical challenges, and benefits for Cardano, demonstrating how each direction aligns with specific blockchain tenets and Product Committee goals. These thematic focus areas provide a roadmap for research and development, ensuring that efforts are not only innovative but also relevant to the Cardano mission. Each thematic focus area is chosen to tackle critical issues, drive technological advancements, and ultimately enhance the platform's capabilities, sustainability, and global impact.

Over the next five years, these directions should be thoroughly explored, leading to their integration as functional components and extensions of the Cardano platform. They serve as strategic pillars that guide advancement and development and concentrate on specific, high-impact challenges and opportunities, ensuring that research efforts are aligned with long-term goals and needs. By defining clear thematic focus areas, resources can be effectively directed toward exploring cutting-edge solutions, fostering innovation, and addressing key technical and societal challenges.

Each R\&D direction or workstream within the 2025 workplan is designed with a clear motivation, identifying the technical challenges it aims to overcome and the benefits it will bring to Cardano. The objectives of each work plan are clearly defined, focusing on creating specific deliverables such as enhanced protocols, improved tokenomics, or new functionalities for DApp developers. The tasks and deliverables are structured to meet minimal requirements essential for successful implementation, with considerations for staffing, cost, references, and timelines. This structured approach allows for efficient resource allocation and progress tracking, ensuring that each workstream contributes effectively to Cardano's long-term vision of a robust, secure, and scalable blockchain platform.&#x20;

Given the early-stage nature of research and the inherent uncertainties that come with pioneering new developments, it is essential to remain adaptable and responsive to changing circumstances. To this end, a 'portfolio approach' to the management and allocation of research resources and the prioritization of specific research workstreams is requested. This ensures funds are optimally allocated across thematic focus areas and workstreams and that resources are directed where they can have the most significant impact.

### High-level skillset and expertise required

Achieving correctness, security, and reliability is inherently challenging. It requires examining a system under all possible circumstances, which is an infeasible task given that this cannot be demonstrated experimentally. This is particularly relevant for distributed, decentralized systems which are run by volunteer community members, on a global scale, on public infrastructure.

For precisely this reason, mathematical models, proofs, and formal methods are required to obtain high assurance. To achieve this a methodology rooted in peer-reviewed science and the application of evidence-based engineering best practices is advised. This ensures a strong connection between design and implementation throughout the research and innovation process and leads to high-quality systems that we can confidently continue to build on and evolve over the longer term.\
Despite being rigorous, an approach should be inherently flexible and iterative. This is in contrast to a rigid, linear process like the waterfall model. In a static, linear process, bugs or feature requests could disrupt the entire chain of evidence and undermine the system's integrity. The flexibility ensures a development process that is adaptive, allowing the produced artifacts and software to evolve over time. It identifies roadblocks as early as possible in the process and optimizes how time and resources are allocated. This agile, iterative approach allows IOR to address issues dynamically, ensuring continuous improvement and seamless integration without compromising the overall system integrity.

#### Research: Artifact Formalization (up to SRL2)

Researchers should develop and formalize ideas that go beyond the state of the art. The goal of this process is to find the right requirements, possibly identifying inherent tradeoffs or limitations, meaningful mathematical models, well-defined design goals, and a technical proposal/solution along with rigorous security proofs.

Once the core idea is defined and its expected benefits specified, researchers proceed with pseudocode formalization as part of a technical report. The goal is to produce a scientific artifact---a paper to undergo peer review---that provides all the scientific evidence demonstrating that the proposed solutions are mathematically sound based on well-defined assumptions.

Our objective is to develop innovative solutions to open research problems that are of interest to Cardano or specific parts of its ecosystem. The duration of this process can vary depending on the research topic and requirements. Initially, this process may be carried out exclusively by researchers or researchers in interaction with problem stakeholders and engineers. This reflects the fact that requirements may need to be extracted depending on the problem or use case. As the solution matures, the research team may formalize it, potentially employing formal method tools to verify that certain properties hold. If necessary, formal method engineers may assist in this formalization.

The formalization process can result in various artifacts, typically including at least a technical report or a research paper (finalized or in draft form) and possibly a formal specification. These deliverables mark the transition to the prototyping stage. To expedite this transition, researchers are encouraged to share their work early, favoring technical reports over research papers when appropriate.

* Problem Statement\
  The first step in our research methodology involves clearly identifying the problem we aim to solve and defining the requirements, both functional and non-functional. This involves extracting and articulating the core issue and the associated requirements, ensuring a thorough understanding of what needs to be addressed. The requirements help shape the direction of the research by establishing clear goals and constraints that guide subsequent steps.
* Problem Abstraction and Formal Modeling\
  We then abstract the problem and build a formal mathematical model, focusing on relevant details while ignoring irrelevant ones to gain a clearer understanding of the problem's nature. This model, which must be precisely documented, defines the assumptions and boundaries within which the problem can be explored. It allows us to determine what is feasible and understand potential impossibilities under given assumptions. If the model leads to a dead end, we refine our assumptions or problem statement to better align with the requirements.
* Solution Design and Proving Security\
  Third, we design a solution within a formal framework and provide a proof of security. This step involves articulating all assumptions precisely and mathematically proving that the proposed solution satisfies the desired properties. The proof serves as evidence that others can review to verify the conclusions. This step also includes assessing feasibility and exploring ways to address any identified impossibilities by refining the model or introducing new assumptions.
* Documentation and Peer Review\
  The final step is to document the entire process in a structured research paper, which is then subjected to peer review. This ensures adherence to standard research practices and allows experts in the field to evaluate the validity and robustness of the proposed solution. Peer review enhances confidence in the results by providing an external assessment of the problem, model, and solution, ensuring they are sound and reliable. Once published, communication can occur through Cardano Improvement Proposals (CIPs) and relevant touchpoints in Intersect working groups.

#### Innovation: Prototype Validation (up to SRL4-6)

The innovation process is a crucial development phase that bridges the gap between research and implementation, involving collaboration from multiple stakeholders including engineering, product and finance. Over 6-12 months the innovation phase verifies that the research assumptions hold in practical environments and define the technical specifications for the solution to be deployed in a target environment. Each innovation workstream collaborates closely with research to gain clarity on the artifact and provide feedback based on their experiments, especially when limitations in the original design are uncovered. This feedback loop is essential for refining or reevaluating the solution, with the research team providing timelines for adjustments.

This structured process ensures effective collaboration, with reference documents maintained in the same repository as prototypes produced by the innovation team. The implementation team, or any related stakeholders, are involved when raising integration concerns and assessing the effort required for final implementation. Their input helps prepare for a seamless integration of the solution into its target environment.

The prototyping phase should yield the following documents: (i) a formally proven reference implementation verifying key properties of the solution (ii) a test prototype for simulated or test environment validation (iii) conformance tests and benchmarks derived from formal specifications or handcrafted to test the prototype (iv) a requirement document outlining what needs to be implemented and why (v) and a Cardano Improvement Proposal (CIP) presenting the solution and next implementation steps to the Cardano community.

Once the required SRL is achieved as agreed with the respective implementation team, whether that be Input Output and/or co-ordinated through Intersect with other Cardano community stakeholders, the documentation produced by the innovation team can be followed to integrate the solution into the target environment. This includes conducting conformance testing and validating the solution in a test environment before deploying it live.

Once the specifications are implemented, the artifact's properties are validated in the final environment, with the software running in production. If any discrepancies arise at this stage, the research and innovation teams are able to support their validation with stakeholders, and if the discrepancies are deemed acceptable the final solution may diverge from the original requirements to better suit the operational environment.

* Formal Methods\
  The ultimate goal is to ensure that the specification provides a precise, unambiguous description of the design, ideally capturing the properties necessary for functional correctness, security and timeliness. The specification should be executable, facilitating its use in continuous testing and verification processes. For consensus protocols, this includes proving key properties such as safety and liveness, along with correctness and, in some cases, security properties.
* Prototypes and Simulations\
  Prototypes are developed to explore the design and address practical issues as early as possible. Prototypes may be general purpose or may address a particular hypothesis or test. Additionally they may run in a 'laboratory setting' where the real environment is simulated . A good prototype should uncover practical tradeoffs leading to discussions with the implementation team but should demonstrate that there is a clear and de-risked path to implementation. They should be connected to the formal model via conformance testing using property based testing and should demonstrate promising performance characteristics via simulations and benchmarks.
* Specifications and CIPs\
  The outcomes of the formal models, prototypes and simulation are evidence to suggest the viability of the design and the practicality of implementation. Another key aspect is communication - specifications are intended to be read and discussed and are developed to ensure there is a definitive description of the design. Formal specifications are detailed and technical, and can also serve as the acceptance criteria for the implementation. Cardano Improvement Proposals (CIPs) are technical but less detailed, and justify the need for the change and approval by the community. CIPs are supported by prototypes, formalizations, specifications, simulations and benchmarks.
* Tooling\
  Suitable tools, techniques, and languages are important to ensure that individual team members are not held up in their work and that there is good communication between the interdisciplinary elements of projects. In some cases, off-the-shelf tooling is available, or we can use tools similar to those used by the production teams (e.g., Haskell, Rust, or Agda). In other cases, tools and libraries may need to be developed ourselves or contribute to the development of cutting-edge tooling, especially when it comes to expanding reach into earlier stages of research or new areas. Examples of the tooling we use include Agda, agda2hs, agda2rust, DeltaQ, Quickcheck dynamic, Lean, netsim.

### Broad acceptance criteria

Each year RWG's goal is to generate a robust pipeline of at least 20 research opportunities at SRL2, underpinned by comprehensive research papers and technical reports. From this funnel, we aim to validate and prioritize 6 key innovation opportunities for implementation that have been thoroughly validated through a multidisciplinary team across engineering, product development, customer engagement as well as research.&#x20;

This funnel approach is designed to lay a strong foundation for Cardano, ensuring a continuous pipeline of high-impact and strategic opportunities with global ambitions that address the most significant challenges in the blockchain space. The outputs and deliverables outlined below are focused on reinforcing and advancing Cardano's leadership in the blockchain industry.

#### Research

Papers published within this context can vary significantly in terms of length, complexity, and strategic importance, with the average paper taking at least two years to publish. This timeline is influenced by the peer review process, which can extend over several months and often requires multiple submission cycles, reflecting the high standards of academic publishing.&#x20;

The landscape of research conferences is also evolving, becoming increasingly competitive, particularly in key areas relevant to blockchain and cryptography. This heightened competition underscores the need for quality and excellence in research outputs. Given this variability, we are committed to maintaining a consistent output of at least 20 research papers and technical reports per year across the research workstream portfolio, ensuring that we continue to contribute meaningfully to both the global research community and more specifically the Cardano ecosystem.

In addition to producing high-quality research, RWG recognizes the importance of visibility and impact within the academic and broader technology communities. Citations are a key measure of a paper's influence, and we are actively working to increase the reach and recognition of our research. To support this, we are enhancing our marketing efforts, ensuring that our work is not only published but also disseminated effectively across the relevant channels. By doing so, we aim to foster greater engagement with our research, amplifying its impact and solidifying Cardano's position as a leader in blockchain innovation.

#### Innovation

The innovation deliverables include the creation and dissemination of 6 prototypes, technical reports, and Community Improvement Proposals (CIPs) as a result of these workstreams. Please note workstreams starting in the second half of the year will be delivered the following year.

These technical reports will provide in-depth analyses and documentation of each emerging technology and supporting methodologies that are critical to the continued advancement of the solution by product teams within the Cardano ecosystem. Each report will serve as a foundation for future development and inform the community and stakeholders of the requirement for implementation. The prototypes developed alongside these reports will demonstrate the practical application of these innovations, providing tangible examples of how theoretical advancements can be translated into real-world solutions.

In addition to the technical reports and prototypes, Community Improvement Proposals (CIPs) are a key component of our innovation strategy. CIPs are vital for fostering collaboration and transparency within the Cardano community, allowing for community-driven enhancements to the platform. By submitting well-researched and strategically important CIPs, we aim to address specific needs and challenges within the ecosystem, ensuring that Cardano remains at the forefront of blockchain innovation.

### Proposed items

More details can also be found in the research working group [page](https://committees.docs.intersectmbo.org/groups-overview/working-groups/research)

#### Academic Research

Full details and descriptions can be found [here](https://docs.google.com/spreadsheets/d/13k3Mps2HSy2G6ggMLyp6T8e75US7b6zgGDTZ9zfcs-U/edit?usp=sharing)

* State-Machine Contract Environment
* Location-based services and smart contracts
* Ouroboros Peras (Vision)
* Ouroboros Leios
* Fair transaction processing
* Multi-resource consensus - Minotaur
* Proofs of useful work&#x20;
* Congestion control
* Tokenomics design
* Rewards sharing and transaction fees
* Decentralized identity and reputation management
* Next-level governance protocols
* Governance incentives
* Hydra Tail
* Hydra Inter-Head
* Optimization tools
* Auditing tools
* Light client infrastructure
* Partnerchains Tokenomics - pending further info
* Consensus Innovation

#### Academic innovation

Full details and descriptions can be found [here](https://docs.google.com/spreadsheets/d/11rya68hBIqX36kdJPYBM9H_0QTXPkNL2Fj4E9KtCvCA/edit?usp=sharing)

* Leios
* Anti-Grinding
* fastBFT
* RSnarks
* Proof of Restake
* Proof of Useful Work
* BitCoin OS

### Requested Budget

We propose a budget of $13.42M. The total budget proposed is to finance all supplier activities across both academic research and innovation with a total of 56.1 FTEs. This equates to an average of circa $239k per FTE (or $1,030 per day based on 232 working days per year) including all costs as outlined below. This includes a shared services allocation of 15% (below industry standards of 20-25%) as well as all other costs including equipment, software licenses, server costs, any sub-contracting that may be required (for example to academic partners or third-party engineers), travel costs, events and program and portfolio management.

#### Research Streams

The research departmental budget is circa $5.895M for a total of 27.5 FTEs in terms of labor resources. This is approximately $295k per workstream per year, at an average of circa 1.3 FTE, where it takes on average 2 years or more to publish a research paper, and includes:

* an average of $180k per FTE
* all sub-contracting and strategic partnerships with universities
* $175k team travel budget to attend conferences
* 15% shared services allocation

Each of the research workstreams requires a mix of academic experience that can include distributed systems, consensus, protocol design and security, applied cryptography, game theory, and formal specifications/verification. The resources allocated to each workstream can vary from 2-6 team members, and typically include the following roles:

* Chief Scientist - oversees research strategy, drives innovation, and academic excellence
* Professors - world-renowned experts in their field
* Senior Research Fellow - leads advanced research projects, mentors researchers, and publishes findings.
* Research Fellow - conducts specialized research, collaborates on projects, and contributes to publications.
* Researcher (Associates and PhDs) -  pursues doctoral research, assists in studies, and develops expertise.
* Engineers - Research, Formal Method or Software - develops and implements technical solutions, supports research, and ensures software quality. At the start of a research workstream the FTE scope can be very wide due to the high level of uncertainty, and as the workstream develops this is then narrowed as investigative directions are realized.\
  Innovation Streams

#### The innovation departmental budget is $7,525,000 for a total of 28.6 FTEs in terms of labor resources. This is approximately $1.25M per innovation workstream for 6-12 months of intensive effort and includes:

* an average $200k per FTE
* 2 on-site workshops per year costing $60k that facilitate planning, knowledge sharing, and collaboration sessions
* 15% shared services allocation

Each of the 6 innovation workstreams requires specific dedicated skill sets which might vary depending on development requirements (for example, not all require cryptographic knowledge). The resources allocated to each workstream typically range from 4.6 - 6 FTEs and include the following roles:

(a) Product manager / Developer relationship - Develops product discovery, market fit, builds the use cases, and identifies supporting customers

(b) Technical Architect - define and provide inputs on the prototype/target environment

(c) Prototyping engineer (software) - Prototyping, Modeling and Simulation Engineer(s)

(d) Applied Cryptographer - define and provide inputs on the cryptographic primitives implementation and benchmark

(e) Researcher liaison - author and support the team on additional research and paper publications

(f) Formal methods engineer - define formal models, specifications, and executable models to be used in performance testing.

***

## Product Research sub-bucket

### Overview

The product research bucket aims to fund all research activities that can provide user needs and market insights into the Cardano ecosystem. This research will be conducted with rigorous standards, following user and market research best practices. It will provide direct insights and direction to the ecosystem, as well as to projects within the ecosystem.

### Expected outcomes

For year 1, 2025, the research conducted in this sub-bucket aims to provide insights into the direction and refinement of the proposed goals for 2025 and support other committees with information on user needs. In addition to this short-term need, the insights from this first year will directly inform the Cardano strategy in the short term (2025 and 2026) and help create a longer-term vision. The outcome of this research will also lead to clear problem statements which will be documented as Cardano Problem Statements (CPSs).&#x20;

### High-level Skillset and expertise required

#### User research&#x20;

1. Interviewing and Moderation
   1. Requirements: 5+ years of experience in qualitative interviewing and moderating user sessions, with a focus on gaining actionable insights.
   2. Preferred Expertise: Background in behavioral science, with experience in blockchain projects or similar innovative tech environments.
   3. Evidence of Success: Proven track record of previous research, documented and published; clear documentation of how insights influenced product decisions and user experiences.
2. Survey Design and Analysis
   1. Requirements: Extensive experience (3-5 years) in survey design for user research, with a focus on quantitative data collection.
   2. Preferred Expertise: Familiarity with designing surveys for emerging technologies (e.g., blockchain), and understanding of statistical rigor in research.
   3. Evidence of Success: Published work or internal documentation showing survey impact on product insights; reports demonstrating improvement in user experience due to survey findings.
3. Usability Testing
   1. Requirements: Minimum of 5 years conducting usability tests across various platforms, including mobile, desktop, and emerging tech.
   2. Preferred Expertise: Experience running usability tests within blockchain or fintech products.
   3. Evidence of Success: Portfolio of usability test reports, with case studies on how findings optimized user flows and enhanced the user journey.
4. Journey Mapping and Persona Creation
   1. Requirements: 3-5 years of experience in creating user personas and journey maps, with the ability to illustrate user pain points and opportunities.
   2. Preferred Expertise: Background in psychology or behavioral science, experience crafting personas in complex domains like blockchain.
   3. Evidence of Success: Portfolio showcasing user journey maps and personas that directly influenced product features; documented cases where personas improved user engagement.
5. Ethnographic and Observational Research
   1. Requirements: 3+ years conducting observational research, preferably in contexts where users are interacting with cutting-edge technology.
   2. Preferred Expertise: Understanding of ethnographic methods; experience with real-world observations and contextual inquiries in blockchain applications.
   3. Evidence of Success: Detailed case studies or reports documenting ethnographic research impact, showing how findings led to targeted product enhancements.

#### Market research

1. Competitive Analysis
   1. Requirements: At least 5 years of experience in conducting competitive analysis, with a focus on rapidly evolving tech markets.
   2. Preferred Expertise: Background in blockchain or adjacent fields, with strong familiarity with market positioning and competitor landscape.
   3. Evidence of Success: Proven competitive analysis reports with documented impacts on strategic direction; and demonstrable cases of product pivots based on competitive insights.
2. Industry and Trend Analysis
   1. Requirements: 5+ years of experience in industry trend analysis, ideally with a focus on emerging tech or disruptive innovation.
   2. Preferred Expertise: Background in market analysis within blockchain, AI, or other technology-driven fields.
   3. Evidence of Success: Published market trend reports or internal documentation showing how trends influenced product roadmap or strategy.
3. Market Segmentation
   1. Requirements: 3-5 years of expertise in segmentation, with a focus on identifying and understanding user groups within emerging tech spaces.
   2. Preferred Expertise: Experience applying segmentation to blockchain or fintech markets, with knowledge of demographic, psychographic, and behavioral segmentation.
   3. Evidence of Success: Proven track record of segmentation analyses that improved targeting; documented impact of segmentation on marketing or product development.
4. Quantitative Market Research
   1. Requirements: 5+ years in quantitative market research, with experience in large-scale data collection and analysis.
   2. Preferred Expertise: Expertise in forecasting, market sizing, and quantitative methods within the blockchain or tech industries.
   3. Evidence of Success: Published or documented quantitative research with clear metrics showing impact on market strategy or feature prioritization.
5. Data Analysis and Interpretation
   1. Requirements: 5 years of experience in data interpretation, with the ability to synthesize complex findings into actionable insights.
   2. Preferred Expertise: Proficiency in data analysis software (e.g., SPSS, R, Python) and experience with emerging tech markets.
   3. Evidence of Success: Case studies or reports detailing how data interpretation shaped product decisions or market positioning.

### Broad acceptance criteria

* Because this data will be used to influence and inform the whole Cardano ecosystem, by being shared with committees and anyone working on Cardano as well as being made public and available for everyone to use, this research needs to be conducted by expert user and market researchers following best practices. Requires rigorous standards and a structured approach which needs to be published ahead of the research itself starting
* Insights need to be shared and documented in a timely manner in order to be used to inform decisions&#x20;
* Any assumption or question that needs to be informed or validated via this research needs to be reviewed by such experts, challenged and properly structured before a tender of any size is published
* It is not necessary for any of this research to be run from scratch. Existing data need to be always taken into account either to provide the insights needed or to act as a foundation for further investigation
* The work, approved to be conducted after review, can either be paid in ADA or be given to volunteers (perhaps even from the product committee), with a preference to funding organizations that are already in or connected to the ecosystem
* The proposed items, the progress, and the outcomes, including all the insights and learnings, need to be published in a consolidated space for easy fruition and so to allow the ecosystem to take advantage of them

### Proposed items

#### To inform and refine [2025 goals](https://productcommittee.docs.intersectmbo.org/committee-outcomes/2025-cardanos-roadmap/2025-proposed-cardano-goals)

*   **To inform the broad topic: Get more Usage**\
    _&#x47;oal_: Attract dApps and users - product market fit\
    Problem to solve: How Might We attract more dApps, users, and protocols to Cardano (to increase transaction activity which will ultimately fund the treasury)?\
    \
    _&#x51;uestions_:

    * What are the existing Cardano use cases (of any size)? Which ones have been successful and which ones have not? What are the reasons behind this?
    * What are the existing use cases that have been tried on blockchains?
    * Identify defi use case opportunities for Cardano (e.g. inter-chain transfer) and identify the product gaps for Cardano with respect to these use cases.
    * Create a feasible list of target businesses with actionable scopes and product fit already established.
    * How easy is it to find companies with the expertise to build on Cardano for businesses outside of the ecosystem?
    * Where do transactions in competitor chains come from? Which one might we be interested in depending on other research?&#x20;
    * What is the relationship between transaction fee/settlement speed and bots activity? Is bot activity good for the chain overall?
    * Transaction and TX price modeling: Model the number of transactions required to keep Cardano sustainable (and sensitivity to Tx price)
    * Is there a need/opportunity for settling other chains' transactions into Cardano's L1
    * How many people participate in the Cardano community at different levels?

    \
    _&#x47;oal_: Easier to build on and to use Cardano\
    Problem to solve: How Might We reduce barriers and simplify processes for using and building on the Cardano blockchain?\
    \
    _&#x51;uestions_:

    * What are the limitations, barriers, and issues of the existing tooling to build on Cardano?
    * What are the existing barriers and limitations to build on Cardano L2?
    * What is the current developer onboarding process? What are the barriers to entry about that? What are the differences between different geographies?&#x20;
    * What are the most popular developer tools that we should integrate with and what are the barriers to achieving that?
    * Which tools and SDKs could simplify and speed up building on Cardano?



    _Goal_: Cardano competitive option\
    Problem to solve: How Might We make Cardano meet the needs of apps that want to build on it (in terms of speed of transactions and speed of development), so being competitive with other options and getting more users?\
    \
    _&#x51;uestions_:&#x20;

    * What are the L2 potential use cases for transactions that settle on Cardano?
    * What customers could benefit from Cardano's current qualities/value?
    * How interesting is 'security' as USP for Cardano?
    * Which web2 applications can directly benefit from blockchain, and identify tech gaps / market gaps / barriers relevant to enabling opportunities for market penetration?
    * Why do so few interoperability solutions target Cardano? How can we improve it?
    * What is the critical missing infrastructure to meet crypto-wide standards?&#x20;
    * What are the barriers to making Cardano and Cardano Native Tokens a viable product for exchanges to list?
    * What use cases will interoperability open? What are the barriers to achieving interoperability?
    * Which elements make us competitive and which make us weak?



    _Goal_: Clear funding mechanisms\
    Problem to solve: How might we develop effective funding mechanisms for Cardano projects and businesses (both from inside and outside the ecosystem)?\
    \
    _&#x51;uestions_:

    * What are the existing funding mechanisms in Cardano? What are the limitations and barriers of entry to those?
    * Are existing projects and businesses aware of these existing funding mechanisms? How easy and clear it is to access them?
    * Which types of projects need funding and at which stages? What needs do these projects have?
    * What other funding mechanisms do other ecosystems have and which one could match Cardano's project needs?
    * What are the potential funding avenues outside of Cardano and which ones are viable? Also, what are the best ways to inform the community about them?
    * What are the current challenges in talent acquisition and talent retention?
    * How might we build a commercial partnership with a star enterprise (specific use case scope)



    _Goal_: Make Cardano more recognizable\
    Problem to solve: How might we increase the recognition and reputation of the Cardano ecosystem and ADA token?\
    \
    _&#x51;uestions_:

    * How much awareness does the general public have of Cardano and its core qualities? And how much awareness do businesses that can benefit from Cardano have of it?
    * What is the public perception of Cardano?
    * Which brands can we partner with to increase our reputation and recognition?
    * Which use cases should we market to increase awareness?



*   **To inform the broad topic: Governance**\
    \
    _&#x47;oal_: Reliable decentralized governance\
    Problem to solve: How Might We make the new Cardano governance strong enough to support the newly formed Cardano government?\
    \
    _&#x51;uestions_:

    * What is the right level of participation in governance? What should we expect and what should we aim for?
    * What are the existing barriers to participation in Cardano's governance?
    * What are the needs that need to further be supported by tooling?
    * How many people in the community know about Cardano's governance? How much do they understand of it?
    * How easy is it to find documentation about governance? How easy is it to use that?
    * How can we make governance simpler, is there a way to create engagement around it, what have other chains done well (Wallet integrations, standalone apps, participation, etc.)


* **To inform the broad topic: Business as usual**\
  _&#x47;oal_: Maintain Cardano's current qualities\
  Problem to solve: How might we ensure Cardano remains trustworthy, reliable, and competitive?\
  \
  _&#x51;uestions_:
  * What are Cardano's core qualities? Which of these are unique? Which one is also our USP and makes us competitive?<br>
* **To inform the broad topic: Vision**\
  _&#x47;oal_: Process for a shared community-driven vision\
  Problem to solve: How might we create the next path to move Cardano forward as a community?\
  \
  _&#x51;uestions_:
  * What other ecosystems have run a process like this? What can we learn from that?
  * What other processes similar to this have we run in our ecosystem? What can we learn from those?&#x20;
  * What frameworks should we leverage?

#### To inform long-term vision

_Questions_:

* What are the existing insights from academic research that can inform this process?
* Where does the current community think Cardano should be in 2030?
* Based on the insights to inform 2025 what are the key customers we should focus on (businesses and projects that have value building on Cardano and that get us closer to our goals)?
* Which one are the key personas Cardano should focus on and what are their key 'jobs-to-be-done'?

### Requested Budget

The product committee requests an overall budget of $200k to get insights related to the research above, plus any other questions that will be brought to the committee from other committees in 2025, as well as to cover costs for managing the process and making the outcome easily accessible to the community.

***

## Vision Creation sub-bucket

### Overview

The vision creation bucket aims to fund all activities needed to facilitate the first version of a community-led open and transparent process to create an evolving 5-year vision for the Cardano ecosystem.

### Expected outcomes

For year 1, the work conducted in this sub-bucket aims to provide a first-tested process for the Cardano community to brainstorm, set, track, and evolve its own vision and roadmap. The outcome of that process is the first version of a 5-year Cardano vision and a 2026 roadmap based on that.

### Broad acceptance criteria

* A process has been defined to create as a community a 5year vision
* The broader community had many opportunities to provide insights to inform the vision proposal and as many opportunities to feedback and adjust the proposal itself before being submitted to vote
* A proposal for the 5year (at least) Cardano vision has been submitted on-chain for approval with at least the following characteristics:
  * Key objectives Cardano aims to have achieved by the year 2030 (at least) providing for each objective context and rationale
  * The broad steps to achieve the objectives are divided into eras. For each era explain what broad key deliverables are expected, how they get us closer to the objectives, and the dependencies to previous or future eras
  * References the insights used to inform the proposal itself (coming from community, users or customer interviews, from existing research, from the market and SWOT analysis, etc)

### Proposed items

The current proposed process steps include:

1. Insights collection\
   Collect insights into where the community thinks we need to be by 2030 based on pain points and opportunities&#x20;
2. Proposal drafting
   1. Based on the insights collected in the previous step, and data from user research and academic research, any data from the market and SWOT analysis draft a proposal following the acceptance criteria above
   2. After the Product Committee review start the second series of virtual workshops to critique and adjust the proposal as well as propose names for the eras
3. Info action submission
   1. Based on the feedback adjust the final draft and submit it on-chain as an info action for community ratification

Some examples of what this budget will cover include but are not limited to:

* Defining a set of key data points to collect
* Properly analyzing, documenting, and storing the supporting data for the vision proposal
* Creating a framework for remote and in-person workshops to collect insights and direction from the community
* This might also include translations

### Requested Budget

We're budgeting for up to 100 workshops (in-person and remote) supported by Intersect hubs, coming to a total of $200k requests for vision creation with a commitment to return the remaining funds at the end of the vision creation process if the funds are not fully spent. We don't see a need for professional services as we're going to be developing this in an open-source volunteer fashion.

***

## Product Committee Overhead sub-bucket

### Overview and Expected Outcomes

This sub-bucket aims to cover any overhead the product committee itself might have in facilitating and managing the three buckets above as well as delivering against its core objectives (support vision and roadmap creation as well as keeping track of its progress)

### Potential Proposed items

(This list is subject to change and adjustments as more data are collected and become available the list will get refined too)

Examples of items that might be covered with this small overhead budget are:

* Academic Research tenders proposals review
* Product research tenders proposals review
* Vision creation process coordination and management
* Product research analysis
* ...&#x20;

### Requested Budget

Considering an estimation to cover the examples above, plus anything small that is currently unforeseen the committee asks $100k
