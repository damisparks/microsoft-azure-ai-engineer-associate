# Overview of predict costs and optimize spending for Azure

Azure products and services are arranged by categories with various option to provision depending on your requirments since your account is billed on what you use. 

## Usage Meters. 
When you provision an Azure resource, meter instance(s) is created to track the resource usage and generate a usage record that is used to calculate the bill. 

At the end of each monthly billing cycle, the usage values will be charged to your payment method and the meters are reset. 

> ## Key Point
> The key takeaway is that resources are always charged based on usage. 

# Factors affecting costs. 
Primary factors includes : 
* resource type,
* services
* the user's location
* the billing zone.

## Resource type 
Costs are resource-specific, so the usage that a meter tracks and the number of meters associated with a resource depend on the resource type.

## Services
Azure usage rates and billing periods can differ between Enterprise, Web Direct, and Cloud Solution Provider (CSP) customers. Some subscription types also include usage allowances, which affect costs.

## Location 
Since Azure has datacenters all over the world, usage costs vary between locations that offer particular Azure products, services, and resources based on popularity, demand, and local infrastructure costs.

# Azure pricing calculator
## Check your knowledge
1. Which tab of the Azure pricing calculator will you use to put together your estimate?
    * Estimate
    * **Products** (_correct answer_) 
    >This tab has all the Azure services listed and is where you'll add or remove services to get your estimate.

2. True or false: You can share your estimate through an Excel spreadsheet or through a URL.
    * **True** (_correct answer_)
    > Clicking Export at the bottom of the estimate will export an Excel spreadsheet that you can share, or you can click Share to get a URL link that you can share with your team.
    * False

# Cost Management and Azure Advisor
## Check your knowledge 
1. Azure Advisor provides recommendations for _________.
    * Costs only
    * **High availability, security, performance, and cost** (_correct answer_) 
    > Azure Advisor provides recommendations on high availability, security, performance, and cost.
    * High availability, performance, and cost

2. Azure Cost Management allows you to _________.
    * **See historical breakdowns of what services you are spending your money on.** (_correct answer_) 
    > Cost Management analyzes where you are historically spending your money and can track it against budgets you have set.
    * See estimates of what your services might cost if you make a change.

# Save on infrastructure costs 
## Check your knowledge 
1. Which one of these is not a cost-saving solution?
    * Deallocate virtual machines during off hours.
    * Use Azure Reserved Virtual Machine Instances.
    * **Load balance your virtual machines for incoming messages.** (_CORRECT ANSWER_)
    > Load balancing is used for performance optimization not cost savings.
    * Right-size underutilized virtual machines.
2. True or false: PaaS is generally less expensive than IaaS.
    * **True** (_CORRECT ANSWER_)
    > IaaS requires Azure to dedicate resources while PaaS give Azure more flexibility in how services are delivered. This means Azure can fill and operate hardware efficiently and therefore offer PaaS services at a savings over IaaS.
    * False

# Save on licensing costs
## Check your knowledge
1. True or false: If you already have Windows Server licenses, you have to pay for them again on Azure.
    * True
    * **False** (_CORRECT ANSWER_)
    > Under certain circumstances, you can utilize the hybrid benefit for Windows Server and pay only the Linux rate.

2. True or false: Azure has money-saving options for test and development servers.
    * **True** (_CORRECT ANSWER_)
    > The Azure Enterprise Dev/Test and Azure Pay-As-You-Go Dev/Test benefits give you several discounts, most notably for Windows workloads, eliminating license charges and billing you only at the Linux rate for virtual machines. This also applies to SQL Server and any other Microsoft software that is covered under a Visual Studio subscription.
    * False

# Summary 
## Check your knowledge 
1. Which one of the following systems is used to determine Azure costs for each billing period?

    * The Azure website
    * Number of created virtual machines
    * The Azure pricing calculator
    * **Usage meters** (_CORRECT ANSWER_)
    > Correct. Azure is billed according to your consumption based on monthly usage meters.
2. Which of the fllowing factors affects costs?

    * Global infrastructure
    * **Location** (_CORRECT ANSWER_)
    The location you place your resources will vary the price for the resource.
    * Availability zone
3. Complete the following sentence. As an Azure customer, Azure Reservations offer discounted prices if you _________

    * **Make upfront commitments on compute capacity** (_CORRECT ANSWER_)
    > Azure Reservations offer discounted prices on certain Azure products and resources. To get a discount, you reserve products and resources through an upfront commitment. You can then either prepay or pay monthly for one or three years of usage of certain Azure resources.
    * Provision many resources
    * Have a free account
    * Set Spending Limit

> **NOTE**
> This is just a summary of my learning of this module. More like a reflection. 

For reference : Please visit the official page : 
* 👉🏾[Predict costs and optimize spending for Azure](https://docs.microsoft.com/en-us/learn/modules/predict-costs-and-optimize-spending/)

Thank you for reading 👍🏾 Keep learning 🚀