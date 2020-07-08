---
layout: post
title: How Ledger Vault enables custodians to work hand-in-hand with their customers
author: Vincent Debast
summary: Exchanges & hedge funds need to put their digital asset under custody, but it doesn’t come with less control thanks to Ledger Vault
featured-img: custody
categories: Vault
---

# How Ledger Vault enables custodians to work hand-in-hand with their customers

According to PwC’s [2020 Crypto Hedge Fund Report (1)](#1) the total assets under management (AUM) for crypto hedge funds increased from an average of USD 21.9 million by 2018 year-end to USD 44.4 million last year.

Likewise, PwC estimates that the total AUM of all hedge funds more than doubled between this same period, climbing from ~ USD 1 billion in 2018 up to over USD 2 billion in 2020. 

Overall, **cryptocurrency exchanges** are responsible for the safekeeping of a significant chunk of circulating cryptocurrencies, but consumer trust for these platforms continues to deteriorate due to the perceived risk of loss as a result of the numerous [exchange hacks and thefts (2)](#2) that have occurred in recent years.

To ameliorate this, provide a better standard of service to their users, and restore their client’s trust in the platform, exchanges and other firms with a significant custodial role have begun to employ secure **third-party custody solutions** to separate asset custody from their general business services.

Nonetheless, many cryptocurrency exchanges and hedge funds still continue to self-custody user funds—largely due to the misconception that third-party custody solutions are slow, incapable of scaling, and prohibitively expensive.

**As such, custody providers are now doing what they can to meet the needs of their rapidly scaling crypto business customers, by providing them with flexibility and secure control over their digital assets with [Ledger Vault]( https://vaultplatform.ledger.com/).**

## Ledger Vault Capabilities

Briefly, Ledger Vault is a secure digital asset management solution that allows firms that regularly store and manage digital assets to do so with an unprecedented level of security and control. Through the use of hardware security modules (HSMs), a secure channel, and Ledger’s proprietary personal security devices (PSDs), Vault customers are able to set up robust operational controls that determine how funds can be spent or managed on the Vault.

This process is controlled by two main user types. Administrators are responsible for creating the governance rules and assigning another type of user known operators to accounts. Each account has its own set of governance rules and can only be accessed by operators directly assigned to it. These operators are responsible for creating and approving transactions that adhere to the conditions set out by the administrators. This can include restricting transfers to only whitelisted addresses, setting a minimum or maximum transfer limit, and enforcing additional controls for high-value transactions.


The flexibility of this system allows Vault users to create highly secure, scalable transaction flows that can be adapted to practically any business process. Moreover, although many custodians maintain full control and ownership of their custody solution, custodians using Ledger Vault can securely provide their customers with access to the Vault through the use of its unique PSD-based authentication system. **By doing so, custodians can provide a range of additional services to their customers, allowing them to easily manage their own assets while benefiting from the security of the solution.**

Unlike clients that interact with their custody solution over a non-secure channel, Ledger Vault is protected from end-to-end by an ECDH secure channel. This ensures that any information transmitted between the user and the Vault cannot be tampered with—effectively eliminating the risk of a [man-in-the-middle attack (3)](#3).  
<br/>
<center>
<img src="/assets/custody/end_to_end.png" style="width:500px;">
</center>  
<br/>

**This system allows both the custodian and their customers to interact with the Vault using their PSD**. The PSD offers the strongest authentication mechanism on the market and allows operators to initiate transactions, which are validated using the device’s [trusted display (4)](#4). Ledger remains the only business in the digital asset management space with expertise in secure hardware.

## Security and Flexibility for Custodian Customers

Although the security and flexibility of Ledger Vault lends it to a wide variety of use cases, the customers most likely to benefit from its features are those that need to securely store, but regularly access or manage a significant portfolio of digital assets. This is particularly the case for firms that need to enforce strict operational controls over these funds.  

<br/>
<center>
<img src="/assets/custody/rules.png" style="width:500px;">
</center>  
<br/>

**Custodians that provide their customers with direct access to Ledger vault by providing them with operator PSDs essentially enable firms of all types and sizes to benefit from arguably the most feature-complete digital asset custody solution on the market — each custodian customer benefits from their own segregated accounts on the Vault, which can be controlled by any mix of custodian and customer operators.**

**This system allows custodians to provide an additional layer of security to their customers, by allowing them to directly access their assets on the Vault solution. By bridging the custody gap with their customers, custodians can help their customers secure more fruitful partnerships and arrangements with their own clients — helping them grow their user base, secure investment, and boost user trust.**

Custodian customers avoid the operational and regulatory challenges that come with self-custody, making their offerings more attractive to institutional investors and helping to ease any security qualms current customers may have. This has the knock-on effect of also making custodian services more attractive to crypto businesses.

**This ensures custodian customers can focus more on their day-to-day operations and other business practices, while providing their investors and users with the peace of mind that can only be granted by an independent custody solution thanks to minimized counterparty risks. This setup also enables custodian customers to streamline their audit process, since this task can be easily offloaded to the custodian, improving transparency and providing a simple means for customers to prove they are both legitimate and have speedy, secure access to funds.**  

<br/>
<center>
<img src="/assets/custody/compare.png" style="width:500px;">
</center>  
<br/>

Custodians can offer a direct access setup to practically any organization that stands to benefit from highly-scalable custody services, including but not limited to:

**Cryptocurrency exchanges and brokers:** Many cryptocurrency exchanges are faced with overcoming a significant trust divide with users. By working with their custody provider, these platforms can offer the security and speed their customers expect, while eliminating the costs involved in developing or maintaining their own bespoke custody solution.

**Hedge funds:** Cryptocurrency hedge funds are faced with the challenges of attracting investment, while managing potentially significant sums that need to be accessed regularly by their fund managers. These represent ideal customers for Vault custodians, since Vault offers the flexibility and robust security hedge funds need to attract sizable investors.

**Foundations:** Many cryptocurrency companies operate as a foundation, which generally entails a non-profit, ethical business model. Cryptocurrency foundations are usually tasked with developing a blockchain ecosystem and ensuring favorable growth for its users. Foundations set up on the vault with operator accounts can easily demonstrate how they’ve managed their finances, and better focus on growing their community.

## Custodians Can Onboard Customers Easily

**As we previously touched on, Ledger Vault allows custodians to securely provide their customers with direct access to the custody solution, without risking the co-mingling of funds or increasing the risk of a breach. This is achieved thanks to the unique properties of the Ledger PSD, which allows Vault users to securely authenticate themselves.**

The process custodians use to onboard their customers to the Vault is identical to that used for setting up a standard operator—but in this case, the operator PSD is distributed to the customer, rather than a member of the custodian team. Extending the PSD to the custodian customer provides them with a variety of benefits, including:

**Authentication: Customers do not need to manually verify their identity with the custodian each time they interact with the Vault.** This is automatically achieved prior to each action thanks to the unique identity generated by and stored in the PSD. This eliminates the need for the custodian to manually verify the identity of each Vault user for each operation. In less advanced solutions, the authentication process would often require a video link or a call — a process rendered completely obsolete by the Vault authentication system.

**Confidentiality & Integrity:** The secure agreement protocol employed by the secure channel encrypts sensitive data, preventing leakage even when used to communicate information over a relatively insecure medium like the internet. The information transmitted over the secure channel cannot be tampered with.

**Non-repudiation:** Because each PSD has a unique identifier, requests made by each operator can be linked to its owner thanks to the request signature process. This attribute makes it impossible for operators to deny that a request came from their PSD—simultaneously ensuring authenticity and traceability. This property is essential for crypto firms with significant assets under management.

**Auditability:** Each PSD is unique and linked to a single user, whereas each action that is signed by each user using their PSD is meticulously logged within the Vault. Thanks to this granular process, administrators can be certain of the origin of each action, ensuring everything can be audited quickly and easily

Onboarding a customer as an operator on the Vault is a one-time process that can easily be carried out remotely:

**Vault Customer Setup Flow**

1. Vault client (custodian) reaches out to its customer.
2. The custodian sends PSDs for each customer operator.
3. The PSDs are distributed to the individuals in the customer firm responsible for managing interactions with the Vault. These users initialize their devices and each creates a unique seed used to identify their device. This seed is rendered into a unique ID shown on the [trusted display (5)](#5) of each device.
4. Users securely communicate their ID to the custodian through a video or voice call—or any other method that allows the custodian to securely verify the identity of the device owner. This is the only time the identity of the PSD holder needs to be manually confirmed.
5. Using these IDs, the custodian Administrator generates an invitation URL for each user, which they can then use to register as an operator on the Vault.
6. The newly registered users then need to be approved by a quorum of other custodian administrators based on the [admin rule (6)](#6).
7. Customer operators can then be added to new and/or pre-existing accounts.

All-in-all, once the PSD has been delivered to the designated customer, getting them started on the Vault should take just minutes. And with the potential to support potentially tens of thousands of operators and accounts, this setup can support business operations of practically any size.

For many setups, custodians will assign their customers as operators on their Vault instance, managing accounts that are controlled only by individuals in the customer firm. Whereas for other setups, some of the operators involved in processing transactions may work with the custodian.

Once this is organized, specific rules can be implemented to minimize the risk of errors and increase security. Two example workflows might look something like this:

**Workflow 1:**

Customer operator initiates a low value transaction to a trusted address from the whitelist: only one custodian operator is required to review and approve it.

**Workflow 2:**

Customer operator initiates a high value transaction to a new address: Approval is required from two custodian operators.
  

<br/>
<center>
<img src="/assets/custody/schemavault.png" style="width:500px;">
</center>  
_<center>Different workflows can be implemented</center>_
<br/>  


See the [Create an account (7)](#7) section of the Ledger Vault Help Center for a more complete overview of the range of parameters that are defined in the transaction rules.

## With Ledger Vault, focus on what’s essential

Ledger Vault is designed to act as a secure hub for digital asset management, and as a bridge that custodians can use to forge a more trusting relationship with their customers by providing a direct-access custody solution.

«We at Ledger believe that Vault represents a simple path towards uncompromising security for both custodians and their customers.»— Ledger CEO, Pascal Gauthier.

If you would like to see how Ledger Vault can be applied to your use case, schedule a 1:1 demo [here](https://vaultplatform.ledger.com/request-a-demo/).

{% include signatures/vincent.html %}


#### References

1.	<a name="1"></a> [2020 Crypto Hedge Fund Report - PWC](https://www.pwc.com/gx/en/financial-services/pdf/pwc-elwood-annual-crypto-hedge-fund-report-may-2020.pdf)
2.	<a name="2"></a> [Hack Timeline – Ledger Blog](https://www.ledger.com/academy/crypto/hacks-timeline)
3.	<a name="3"></a> [What is a man in the middle Attack - Norton](https://us.norton.com/internetsecurity-wifi-what-is-a-man-in-the-middle-attack.html)
4.	<a name="4"></a> [The Importance of Trusted Displays - Hackernoon](https://hackernoon.com/the-importance-of-the-trusted-display-and-secure-execution-1l7e3249)
5.	<a name="5"></a> [Trusted Display – Ledger Blog](https://blog.ledger.com/trusted-display/)
6.	<a name="6"></a> [Add admin rule – Vault Help Center](https://help.vault.ledger.com/Content/adminrule/addrule_edit.html)
7.	<a name="7"></a> [Create an account – Vault Help Center](https://help.vault.ledger.com/Content/accounts/acc_create.html)
