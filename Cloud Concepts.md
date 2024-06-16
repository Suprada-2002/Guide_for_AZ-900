## What is cloud computing?
- Delivery of computing services across the internet, including servers, storage, database, networking services, etc.
- pay as you use helping lower your operating cost, run infrastructure more efficiently & scale your as business needs change

## Top benefits of cloud computing
1. Cost
- helps optimize IT costs.
- eliminates capital expenses of buying hardware & software & setting up, and running onsite data centers,experts for managing the infrastructure. 
2. Speed
- most cloud computing services are provided self-service & on demand to even vast amounts of resources can be provisioned in minutes.
3. Global scale
- it scales elastically, in cloud it means delivering right amount of IT resources when they are needed (ex- bandwidth, storage, more or less computing power).
4. Productivity
- removes onsite datacenters requirements like hardware setup,software patching & other IT management chores,so IT teams can spend time on morre important goals. 
5. Performance
- reduce network latency for application & greater economic of scale
6. Reliability
- Cloud computing makes data backup, disaster recovery & business continuity easier and less expensive because data can be mirrored at multiple redundant sites on cloud provider's network.
7. Security
- Cloud offers a broad set of policies, technologies & controls to strengthen security posture.

## Types of cloud computing
### 1. Public cloud
- They are owned by a third-party cloud server provider that delivers internet computing services.
- Here all hardware, software & other supporting infrastructure is owned and managed by the cloud provider.
- Users can access these services & manage accounts using a web browser.
- ex: Azure
#### Advantage: 
1. Lower costs - no need to purchase hardware, software & pay only for the service you use.
2. No maintenance - service provider provides maintenance.
3. Near-unlimited scalability - on-demand resources are available to meet business needs.
4. High reliability - a vast network ensures against failure.
### 2. Private cloud
- refers to cloud computing resources used exclusively by a single business or organization.
- Private cloud can be located on company's onsite data center or they can pay third-party service providers to host their private cloud.
- here services & infrastructure are maintained on a private network.
- often used by government agencies, financial institutions & business-critical operations seeking enhanced control over their environment.
#### Advantage:
1. More flexibility - organization can customize its cloud env to meet specific business needs.
2. More control - resources are not shared with others, so higher levels of control & privacy are possible.
3. More scalability - more scalable compared to on-premise infrastructure.
### 3. Hybrid cloud
- Combination of private & public clouds bound together by technology that allows data & applications to be shared between them.
- By allowing data & applications to move between private & public clouds, hybrid cloud gives businesses greater flexibility and more deployment options.
- Helps optimize existing infrastructure, security and compliance.
#### Advantage: 
- Organization can
1. Control - maintain a private infrastructure for sensitive assets or workloads that require low latency.
2. Flexibility - take advantage of additional resources in public cloud when you need them.
3. Cost-effectiveness - with ability to scale to public cloud,pay for the extra computing power only when needed.
4. Ease - transitioning is not overwhelming because users can migrate gradually - phasing in workloads over time.

## Types of Cloud Services
- Also called cloud computing stack because they are build on top of one another.
### 1. Iaas
- most basic category of cloud computing.
- you rent IT infrastructure from a cloud provider on pay-as-you-go basis.
### 2. PaaS
- refers to cloud computing service that supply on on-demand env for developing, testing, delivering & managing software.
- pass is designed to make it easier for developers to quickly create web or mobile apps without worrying about the underlying infrastructure of server storage, network & db needed for development.
### 3. SaaS
- Method of delivering software applications over internet on demand & typically on subscription basis.
- cloud provider host & manage underlying infrastructure, handle any maintenance like software upgrades & patching.
- Users connect to applications over internet, usually web browsers on their PC,table or phone.
### 4. Serverless Computing
- overlapping with PaaS, it focuses on building app functionality without spending time continuously managing the servers & infrastructure required to do so.
- cloud provider handles setup, capacity planning, and server management for you.
- highly scalable & event-driven, only using resources when a specific function or trigger occurs.

## Shared Responsibility Model
![Screenshot 2024-06-16 4 55 37 PM](https://github.com/Suprada-2002/Guide_for_AZ-900/assets/87217681/b825c80b-bcd5-4610-b2eb-5beb4b0ac77c)

- The workload responsibility vary depending on whether the workload is hosted on IaaS,Saas,PaaS or in an on-premises datacenter.
- for all cloud deployment types, user own their data & identities. Regardless of the type of deployment users always retain this responsibility: Data, Endpoints, Account, Access management.

![Screenshot 2024-06-16 7 09 00 PM](https://github.com/Suprada-2002/Guide_for_AZ-900/assets/87217681/26698663-0186-42bb-859d-22b2001fc472)

## Consumption-based Pricing model
- referred to as pay-as-you-go or PAYG
- as the use of your service increase, your revenue increase.
- when you measure consumption,consider simple factors like the amount of data being added to the solution
- Benefit: From customer's perspective, there is minimal upfront investment that's required to use your solution so this model has a low barrier to entry. From your perspective as the service operator, your hosting and management costs increase as your customer's usage and your revenue increase.
- Consumption pricing model works especially well the Azure services that are used in the solution are consumption-based too.
- Complexity & operation cost - Consumption model relies on accurate measurement of usage and on splitting this usage by tenant, this can be challenging, especially in a solution with many distributed components. You need to keep detailed consumption records for billing and auditing as well as providing methods for customer to get access to their consumption data.
- Risks: it can motivate customers to reduce their usage of your system in order to reduce their costs. Also, it results in unpredictable revenue streams.
