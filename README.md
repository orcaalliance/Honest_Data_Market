# ORCA Platform: an Honest Data Market
**Development Stages and Blockchain Requirements by:**

 - *Dmitrij Radin*
 - *Natan Avidan*
 - *Jorge Campos*
 - *Sigitas Saulevicius*
<br/>

## Abstract
ORCA is a personal finance management tool which offers users the ability to securely aggregate their banking and cryptocurrency information. This aggregated data is used to present insights into the user’s financial life and help them make better decisions. However, what makes ORCA unique is its approach to privacy. ORCA does not directly store any of the user’s personal information. Instead, before using any personal data, users have to express consent and be rewarded for allowing information to be used. ORCA utilizes blockchain technology to record permissions and interactions with user’s data, hindering a potential misuse or leak of the sensitive data

**In short, ORCA Platform empowers users to effortlessly manage finances in one place while keeping full control over their personal financial data.**

<br/>

## Development stages
Development and implementation of ORCA Platform is planned to evolve through three stages, which are described below.

### Research and development *(2017/Q4-2018/Q3)*
During the first stage of the project we challenged and explored existing markets. As result we discovered market demands, target customers, current problems and weaknesses. The knowledge acquired was converted into insights, which were then used to construct the core of ORCA’s Platform, from both legal and technological sides. 

**Challenges:**
 - Data Valuation;
 - Data Safety;
 - Data Control; 
 - Technological Challenges;
 - Legal compliance.
<br/>

**Solutions:**
 - Educate people to value data and care more about its usage; 
 - Raise awareness of data control; 
 - Multilayer data encryption, sharding and segmentation; 
 - Data Anonymisation and Personalization on demand;
 - Regulatory (such as GDPR) compliance;
 - Blockchain implementation as a medium of trust and payment rail.
<br/>

**Results:**

We have conducted an extensive market research in order to understand the monetary value of user generated financial data, and, according to its results, we have built a gamified reward system. Data protection challenge has been solved by applying multilayer encryption, sharding and effective anonymised data segmentation. Implementation of distributed ledger technology (DLT) brings an unprecedented layer of trust and transparency into data management process when using ORCA Platform. 

Lastly, we have developed a strategy with the goal to increase the awareness of individuals and, consequently, convert the generated demand to the services provided by ORCA. This goal is achieved by educating people that their data is valuable and can be monetised. ORCA does that by sharing revenue from its user’s data with its users. However, it is essential to point out that data is only monetised with the user’s consent. **_If the user does not consent to it being monetised, no one, not even ORCA, will have access to it._** After users understand the key value that their data holds, they will face a problem: the knowledge that they lack control over their own data. That where ORCA comes in to play.

-----------------------------------------

<br/>

### Proof *(2018/Q4 – 2019/Q2)*
The second stage of the project is called ORCA an Honest Data Broker, because ORCA will act not only as an interface or data aggregator but also as data processor and broker directly. In other words, ORCA will act as a secure and honest intermediate, who shares its revenue with the **Data Producer** a.k.a. **User**. 

**The second stage can be highlighted in three major topics:**
 - Data Aggregation, Encryption, Storing and Processing, 
 - Blockchain Implementation, 
 - Proof of Financial Data Monetisation Algorithms.

During the second stage, we are designing and deploying **ORCA Safe Storage** – an infrastructure for data aggregation, storage, and efficient processing.  Also, our team is implementing an independent blockchain solution called **ORCA Watcher**, which is used to monitor and control all data transactions and interactions. 

<br/>

**Blockchain requirements for Stage #2**

| Requirement  | Weight |
| ------------- | ------------- |
| Javascript or Phyton friendly infrastructure, SDK and frameworks  | HIGH |
| Transaction fee, free or low  | LOW |
| Transaction speed  | LOW |
| Private transactions / data  | LOW |
| Public transaction / Public ledger  | HIGH |
| Smart Contracts / Turing Completeness  | MEDIUM |
| Common identity verification (is wallet assigned to ID)  | LOW |
| Key Vulnerability (is it possible to recover a wallet)  | LOW |
| Maturity (is it mature enough to be stable and secure)  | HIGH |
| Support / Dev. Team  | HIGH |
| Community / Reputation  | MEDIUM |
| Size of the network / Immutability / Fault tolerance  | MEDIUM |
| Decentralization  | MEDIUM |

<br />

**ORCA HDB Architecture**
<p align="center">
  <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_HDB.png" width="100%" title="ORCA HDB Architecture">
</p>

**Stage #2 – ORCA an Honest Data Broker (HDB)**
 - ORCA develops, deploys and maintains needed infrastructure, including but not limited to:
   - **ORCA PYGMY** – frontend environment and interface solution. <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_logo.jpg" width="15px" title="ORCA PYGMY">
   - **ORCA Safe Storage** – secure data storage and encryption architecture. <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_Safe Storage.png" width="15px" title="ORCA Safe">
   - **ORCA Watcher** – transaction and interaction monitoring environment. <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_Watcher.png" width="15px" title="ORCA Watcher">
   - **ORCA Broker** – data processing and distribution/monetisation services. <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_broker.png" width="15px" title="ORCA Broker">
 - ORCA provides convenient interface for both, C2B and B2B users. *(both, WEB and Mobile)*
 - ORCA securely aggregates financial data on behalf of users. *(data aggregation via API from Crypto and Fiat Institutions)*
 - ORCA encrypts and stores user’s data. *(user-centralised, multilevel encryption and secure cloud storage architecture)*
 - ORCA processes and monetises user’s data. *(data mining and marketing campaign)*
-----------------------------------------

<br/>
<br/>

### Implementation *(2019/Q3-2020/Q3)*
Third and final stage of platform development will let ORCA users not only monitor and track their data but also grant access and permissions to any third-party requesters. During this stage ORCA will evolve to an Honest Data Market. The role of the platform will expand from data aggregator and processor to complex data market operator. ORCA will be responsible for participant validation, data flow arbitration, environment maintenance, security and interface provision. 

<br/>

**Blockchain requirements for Stage #3**
Preferred programming languages:
 - Java 
 - Python
 - C++/C#
 - JS

| Requirement  | Weight |
| ------------- | ------------- |
| Open Source projects, with Open or Enterprise governance  | HIGH |
| Javascript or Phyton friendly infrastructure, SDK and frameworks  | HIGH |
| Transaction fee, free or low  | HIGH |
| Transaction speed  | MEDIUM |
| Private transactions / data  | MEDIUM |
| Public transaction / Public ledger  | HIGH |
| P2P node encryption  | LOW |
| Smart Contracts / Turing Completeness  | HIGH |
| No or low transaction and data storage limits  | MEDIUM |
| Cross Chain interoperability  | MEDIUM |
| Sharding  | MEDIUM |
| Permission / Access rights management  | MEDIUM |
| Common identity verification (is wallet assigned to ID)  | HIGH |
| Key Vulnerability (is it possible to recover a wallet)  | HIGH |
| Modularity (is it possible to configure / setup a fork)	  | MEDIUM |
| Possibility to create sub-, side- or off-chain solutions  | MEDIUM |
| Maturity (is it mature enough to be stable and secure)  | HIGH |
| Roadmap  | HIGH |
| Support / Dev. Team  | HIGH |
| Community / Reputation  | HIGH |
| Size of the network / Immutability / Fault tolerance  | HIGH |
| Decentralization  | HIGH |
| Regulatory Risk  | HIGH |


**ORCA HDM Architecture**
<p align="center">  
 <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_HDM2.png" width="100%" title="ORCA HDM Architecture">
 <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_HDM.png" width="100%" title="ORCA HDM Architecture">
</p>

**Stage #3 – ORCA an Honest Data Market (HDM)**
In addition to everything developed for the Stage #2, ORCA will develop, deploy and maintain:
 - **ORCA Data Terminal** – solution to control safe, secure, permission-based data processing by third parties. <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_Data Terminal.png" width="15px" title="ORCA Data Terminal"> 
 - **ORCA Passport** – identification, verification and audition of requesters. <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_Passport.png" width="15px" title="ORCA Passport"> 
 - **ORCA Harvester** – multilevel data aggregation solution. <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_Harvester.png" width="15px" title="ORCA Data Harvester"> 
 - **ORCA Portun** – access and permission management solution based on the blockchain. <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_Portun.png" width="15px" title="ORCA Portun">
 - **ORCA Market** – a convenient platform and framework for data users, requesters and brokers. <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_Market.png" width="15px" title="ORCA Market"> 
 - **ORCA Wallet** – efficient gateway for cross-border payments and reward sharing. <img src="https://github.com/orcaalliance/Honest_Data_Market/blob/master/images/ORCA_Wallet.png" width="15px" title="ORCA Wallet"> 
