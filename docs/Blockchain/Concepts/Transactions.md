---
layout: default
title: Transactions
parent: Concepts
grand_parent: BD-WAN
nav_order: 3
---

# Transactions
**Transaction is a block exchange process. Block itself contains data that we want to transfer to other nodes.**
{: .mt-6 .fs-5 .fw-300}
There are some different approaches to transaction a [Block](https://docs.substrate.io/main-docs/fundamentals/transaction-types/) in [Substrate](https://docs.substrate.io/) framework. There are:
{: .mt-6 .fs-5 .fw-300}
- **Signed transactions**
- Unsigned transactions
- Inherent transactions
{: .mt-6 .fs-5 .fw-300}

We are usually using the **Signed** transactions. Because we have to **validate** the transaction, to prove, that it is not a fraud and you are who you are. Key based security mechanisms are used to guarantee data sharing protectness. Each transaction, must be signed by end user, and the certificate has to be known by system. Only in this scenario transaction can be validated.
{: .mt-6 .fs-5 .fw-300}
![Actions](https://user-images.githubusercontent.com/107935539/177149090-1f5aeac6-c7d4-4338-ab30-5b44974b395e.png)

## Transaction lifecycle
You can see a diagram about transaction lifecycle taken from [Substrate](https://docs.substrate.io/) website. You can take a look how Validating, Queuing, prioritazing and invalid transaction handling are happening [here](https://docs.substrate.io/main-docs/fundamentals/transaction-lifecycle/).
{: .mt-6 .fs-5 .fw-300}
![Transaction lifecycle](https://docs.substrate.io/static/05e81b6aa161457fbf3aec95141f90a2/0fe02/transaction-lifecycle.avif)

## Substrate Details
Substrate is a very powerful and versatile tool we are modyfing for our needs. To understand it more we are suggesting to take a look on the [documentation](https://docs.substrate.io/main-docs/fundamentals/transaction-types/).
{: .mt-6 .fs-5 .fw-300}