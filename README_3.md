# Project-Machu Picchu White Paper 2024 - part 3
*(version OCTOBER 2024)*

##	What is Machu Picchu?

Machu Picchu is an open-source, collaborative project focused on leveraging 21st-century technologies to improve the livelihoods of vulnerable populations. [*See Part 1 (pains and solutions) here (link)*](./README.md) and [*Part 2 (acute needs) here (link)*](./README_2.md).

Watch the 10-minute video here: https://youtu.be/z1ylfi60ES0

This is Part 3, describing the use cases of Machu Picchu using 21st century technologies. 

## Humanitarian Use Cases of 21st Century Technologies
How can 21st-century technologies help address the challenges outlined above?

## Use Case 1: Risk mitigation by savings and by solidarity
### Base use case
In this narrative, we revisit the village in Vietnam with Mrs. Nguyên thi Sáu, but now we are in the 21st century.

Mrs. Nguyên thi Sáu continues to cultivate her small rice paddy and care for her five children, aged between 4 and 10. While not wealthy, she manages to save approximately US$1 each month. Her approach to future challenges has evolved as follows:

-	**Basic Literacy and Mobile Communication**: Mrs. Sáu possesses basic reading and writing skills and owns a simple mobile phone, which she usually keeps switched off to conserve battery life. She utilizes this phone to communicate via SMS with local NGO staff who assists her. This staff member has educated her and other villagers (from 10-20 households) on how to obtain real-time market prices for crops and agricultural supplies through SMS.
-	**Unaware use of cryptographic personal profile**: The helper staff regularly engages with Mrs. Sáu to update her household information, assets, and activities. Her responses are collectively signed using cryptographic methods and posted as a personal profile, akin to a decentralized version of LinkedIn. The cryptographic signature is stored on a blockchain, while the profile data resides on the Interplanetary File System (IPFS). Mrs. Sáu is unaware of this.
-	**Central Bank Digital Currency** (CBDC): The Vietnamese government supports a CBDC. Although Mrs. Sáu prefers physical cash, she has been persuaded by her local helper to allocate a portion of her savings into CBDC, facilitated by SMS communication and blockchain technology.
-	**Monetary Incentives for Profile Updates**: Mrs. Sáu receives payments from various organizations—both commercial and non-commercial— whenever she updates her profile with the help of her local NGO staff. This provides her with a financial incentive to maintain her profile actively.
-	**Solidarity Fund**: Mrs. Sáu can access her CBDC savings at any time but has the option to designate a portion as a solidarity fund, which she can withdraw under specific conditions:

- - **Emergency Withdrawals**: She can withdraw her savings without fees if she can justify a family emergency (such as illness, crop failure, or broken tools). This justification must be approved by her "kinship" group through a blockchain-based voting process.
- - **Profile-Based Kinship Determination**: The degree of "kinship" is established through predefined rules that utilize AI-driven "word embedding" functions to assess the relationships between individuals.
-	**Unapproved Withdrawal Possible Against Fees**: If her justification is not accepted, she can still withdraw her funds but will incur a 20% fee, which is redirected to a community solidarity fund.
-	**Community Support**: When a withdrawal request is approved, if it exceeds her personal solidarity fund, the additional amount is sourced from the community solidarity fund and contributed by members of her "kinship," in proportion to their relationship to her. This support can be given as a gift or a loan.
- -	The amount of any support gift is determined by her figure of merit that is calculated by her profile of past contributions. The amount of loan is calculated from her credit rating from previous history.
-	**Smart Contracts and Transparency**: The rules governing these transactions are embedded in smart contracts that are publicly accessible on the blockchain, ensuring transparency for all participants.

Mrs. Nguyên thi Sáu still considers insurance and bank loans for larger amounts. In this case, her digital profile allows banks and insurance companies to access relevant information (for a fee) to refine their risk assessments. This modern approach empowers her to manage her finances more effectively and enhances the support she receives from her community.

### Supporting use case: who runs the infrastructure?
To support the operations described in the previous narrative, several key infrastructure components are necessary:

-	**Telecommunication Services**: Cellular and internet connectivity is provided by local telecommunications companies, enabling Mrs. Nguyên thi Sáu and her community to access digital resources and communicate effectively.
-	**Power Supply**: Electricity is supplied through the local grid, which may also include village solar installations, ensuring a consistent power source for digital devices and local computing infrastructure.
-	**Blockchain Accessibility**: To make blockchain technology user-friendly for individuals with limited literacy, a feature called Account Abstraction is utilized. https://kvutien-yes.medium.com/blockchain-mass-adoption-with-account-abstraction-erc-4337-1-ae13b84ea81f. This allows users to interact with blockchain systems without needing to manage complex cryptographic keys themselves. Such implementations are available as open-source solutions, facilitating easier adoption.
-	**IPFS Data Storage**: The Interplanetary File System (IPFS) serves as a decentralized data storage solution. It does not require widespread infrastructure; instead, one selected station in every few villages can host the local NGO's data. A micro-computer equipped with a 500 GB solid-state disk (SSD) can effectively store profile data for thousands of individuals. This hardware costs less than $100 and consumes under $20 annually in electricity. The design of IPFS ensures resilience to outages, as data is replicated across multiple nodes. https://kvutien-yes.medium.com/machu-picchu-persistent-ipfs-node-on-raspberry-pi3-part-1-fb6fd67e421a. 
-	**Blockchain Nodes**: Similar to IPFS, blockchain nodes can be hosted on low-cost servers. Modern protocols like Polygon are designed to operate efficiently with minimal computing resources, making them suitable for low-cost transactions typical in this context. (https://en.wikipedia.org/wiki/Polygon_(blockchain)). Given the small monetary amounts involved, cybersecurity requirements can be simplified.
-	**Artificial Intelligence** (AI): While some AI processes, such as training Large Language Models (LLMs), demand substantial computing power and energy, the same low-cost micro-computers can utilize pre-trained LLM parameters to analyze relationships between profiles. This enables the calculation of "kinship" degrees among community members, enhancing the personalization of support and services. (https://www.tomshardware.com/raspberry-pi/raspberry-pi-ai-kit-review).

This infrastructure collectively enables the decentralized, technology-driven support system for individuals like Mrs. Nguyên thi Sáu, ensuring they can access financial services and community assistance efficiently and effectively.

## Use Case 2: Accurate Data Reporting for Helpers
###	Base use case
In the 21st century, Mrs. Nguyên thi Sáu can leverage her digital profile on IPFS and blockchain, despite her limited literacy. By regularly updating her profile, she contributes valuable information that can be analyzed using AI techniques to create vectors representing her data. These vectors allow for the measurement of similarity with other profiles, creating a rich pool of insights that can benefit various types of operators:

The information in this profile can interest several types of operators.

-	**International Helper Institutions**: Organizations such as the United Nations Office for the Coordination of Humanitarian Affairs (OCHA) rely on accurate, up-to-date, and standardized information about individuals in need. Currently, OCHA maintains and distributes datasets to support humanitarian efforts across different sectors. However, these datasets often lack timeliness, as they are filtered and harmonized through multiple layers, making it challenging to obtain fresh, granular data at both geographical and functional levels. (https://en.wikipedia.org/wiki/United_Nations_Office_for_the_Coordination_of_Humanitarian_Affairs). 
-	**Governmental Agencies**: Local and regional government entities collect and maintain comprehensive data about populations, including their needs, production capabilities, revenues, and exposure to climate risks. Gathering such information typically involves expensive and extensive surveys, which can be resource-intensive and slow to implement.
-	**Commercial Providers**: Businesses seek to understand their customers better, requiring insights into assets, income levels, credit ratings, and preferences regarding crops and goods. Accurate, real-time data enables them to fine-tune their offerings, improving customer satisfaction and engagement.

These entities recognize the value of precise and current data and are willing to pay for access to this information. By enabling a system where individuals like Mrs. Sáu can contribute to and update their profiles, the framework provides a dynamic and efficient means of gathering vital insights that can drive better decision-making and resource allocation across various sectors. 

###	How can a Person-in-Need monetize her Profile?
In the Machu Picchu initiative, each Person-In-Need retains ownership of their profile and has the autonomy to decide how to sell their data and to whom. However, a significant challenge arises from the IPFS protocol, which is designed purely for storage; each piece of data is identified by its cryptographic hash code (CID, Content ID), allowing anyone with access to the CID to read the corresponding information.

Within the Machu Picchu framework, four smart contracts govern the interactions between two actors managing two types of assets:

-	**DataRequester**: This organization seeks to acquire information about the Person-In-Need.
-	**PersonInNeed**: This individual may be a smallholder farmer, a refugee, or a recipient of assistance. They maintain a profile that is updated on both the blockchain and IPFS with the help of local NGO field staff, utilizing a decentralized infrastructure enabled by Account Abstraction (ERC-4337).
-	**CBDC**: This smart contract manages the DataRequester’s account, denominated in the national digital currency. In the Machu Picchu demonstration, it possesses the characteristics and functionalities of a standard ERC-20 Ethereum blockchain token.
-	**FamilyAssets**: This smart contract oversees the profile of the PersonInNeed. Specifically, it manages multiple datasets within the profile. Each dataset is assigned a price and made accessible by the PersonInNeed to a targeted subset of customers that includes the DataRequester.

![How each person can monetize her profile](./images/03%20Monetizing%20a%20Profile.png)
The sequence of actions ensures the data ownership of the Person-In-Need is safeguarded through the use of IPFS:

1.	The *DataRequester* **subscribes** to blockchain events and receives notifications whenever the *PersonInNeed* updates her *FamilyAssets*.
2.	To obtain the right to access the data, the *DataRequester* **makes a payment**. Following best practices in blockchain, instead of paying the *PersonInNeed* directly, the *DataRequester* authorizes the *PersonInNeed* to call a withdraw function of the agreed amount from *DataRequester* account, minimizing hacking risk.
3.	The *DataRequester* then **requests the retrieval code** from the *PersonInNeed*, proving payment by including the payment authorization from step 2.
4.	Upon receiving the authorization code, the *PersonInNeed* r**etrieves the payment**. Once successful, they prepare the *FamilyAssets* smart contract to accept the data request from the *DataRequester*. This preparation involves indicating, "This is the address that can request data, and here is the nonce (a one-time authorization code) it must present to confirm its legitimacy."
**5**.	The *PersonInNeed* sends the *DataRequester* the nonce and the **authorization** code for data retrieval from *FamilyAssets*.
6.	The *DataRequester* verifies with *FamilyAssets* that it recognizes the impending request and is awaiting the one-time code.
7.	After verification, the *DataRequester* submits the **data request** to *FamilyAssets* along with the nonce.
8.	*FamilyAssets* checks the nonce and responds with the CID (Content Identifier), which serves as the access point to the profile on IPFS.

## Use Case 3: Cash and Voucher Assistance (CVA)
###	Base use case
The use of Central Bank Digital Currency (CBDC) in humanitarian Cash and Voucher Assistance (CVA) programs presents two primary challenges: (1) the complexity for recipients, many of whom are illiterate, and (2) the availability of CBDC. Once a country adopts CBDC, the Machu Picchu system helps overcome these barriers by enabling Persons-In-Need to access the blockchain via basic cellular phones, aided by local field helpers and Account Abstraction, simplifying the process.

CBDC offers several advantages over physical cash, depending on the country’s implementation:

-	**Programmable Money**: Programmable money refers to digital currency that can have specific rules or conditions embedded within it. CBDC can support programmable money, enabling the creation of smart contracts and automated transactions. Blockchain smart contracts are self-executing programs that are triggered with a transaction, automatically executing actions when certain conditions are met. Conditions can be:

- -	**Time-based triggers** (e.g., funds release on a set date),
- -	**Event-based triggers** (e.g., compliance with carbon best practices or completing a gender equality action),
- -	**User-specific restrictions** (e.g., funds designated for certain items).
-	**Financial Ecosystem Integration**: CBDC promotes innovation, allowing Helper Institutions to design CVA solutions that combine the strengths of both cash and vouchers.
- -	**Faster Disbursement**: CBDC enables rapid, efficient distribution of funds, shortening the delay between fund allocation and disbursement.
- -	**Reduced Theft Risk**: Digital fund distribution minimizes the risks associated with handling physical cash.
- -	**Traceable Transactions**: CBDC provides full transparency, ensuring aid reaches its intended recipients without leakage or misappropriation, enhancing accountability.
- -	**Cross-Border Transactions**: CBDC simplifies and reduces the cost of cross-border fund transfers, helping NGOs comply with Anti-Money Laundering (AML) regulations while transferring funds to local entities.

These features of CBDC address the main weaknesses of traditional CVA:
-	**AI Profile Embedding**: Donors can use AI-embedded profiles to target specific types of Persons-In-Need.
-	**Profile Updates**: Cash assistance can be linked to the fees Helper organizations pay to access Person-In-Need profiles, motivating individuals to keep their profiles up to date.
-	**Traceable Cash Assistance**: CBDC enables NGOs to trace and report how cash assistance impacts funding outcomes.
-	**Inclusive CVA Design**: CBDC allows beneficiaries to be selected individually or based on their profile’s similarity to predefined standards.
-	**Mobile Cash Programs**: CBDC facilitates cash programs for mobile populations, including refugees and nomads, as long as they can access a cellular network. Know Your Customer (KYC) challenges are eased by ERC 4337’s multi-signature feature.


-- 

How do we start? [*Read on… (link)*](./README_3.md)