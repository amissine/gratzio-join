# 👷 Reviving Gratzio, the Stellar-based Help Exchange

## The Pitch

Need a ride, but there's no Uber or Lift in the vicinity? No problem! Use Gratzio - make a request! Selling your place and no Zillow in your area? No problem! Use Gratzio - make an offer! Have some fresh catch to share with your neighbors? Use Gratzio - make an offer! With Gratzio, you can exchange help offers/requests with your neighbors as easily, as around the world. And it is SAFE.

## The Details

The project's goal is to establish a Distributed Autonomous Organization (DAO), whose members (**user**s) exchange help offers/requests with each other. The DAO is [Stellar](https://stellar.org/)-based. A DAO user can be either self-paid or sponsored. To become a sponsored user, go to our (TESTNET) website [https://gratzio.alec-missine.workers.dev](https://gratzio.alec-missine.workers.dev) and accept our invite. This results in a request for the **agent** to:

- create a Stellar account for the user;
- create a trustline from this account to the project's **GRAT issuer**;
- fund the account with the initial amount of the project's asset **GRAT**.

If you already have a Stellar account and want to become a self-paid user, create a trustline from this account to the project's GRAT issuer, then buy some GRAT (either by using our utilities or by going to Stellar DEX). To create a trustline, you can go to our website and enter the public key of your Stellar account.

When the account is funded, its holder can assist other users for more GRAT, and/or send GRAT to other accounts in exchange of help from their holders.

When a user makes a help request, the description of the request is being broadcast to all other users who are listening for requests at the moment. Those who want to take the request, bid on the request and then wait for the requestor to accept the bid. One or more accepted bidders provide help and receive the gratitude (some amount of GRAT).

If the requestor, who already sent the gratitude to the bidder, does not get help from the bidder, the requestor opens the dispute case with the agent. If the bidder is unable to prove to the agent that help has actually been provided, the agent confiscates the gratitude from the bidder and sends it back to the requestor.

When a user makes a help offer, the description of the offer is being broadcast to all other users who are listening for offers at the moment. Those who want to take the offer, ask for the offer and then wait for the offerer to fulfill the ask. One or more fulfilled askers get the help offered and send the gratitude to the offerer.

If the asker, who already sent the gratitude to the offerer, does not get the offered help from the offerer, the asker opens the dispute case with the agent. If the offerer is unable to prove to the agent that help has actually been provided, the agent confiscates the gratitude from the offerer and sends it back to the asker.

Requestors make requests, offerers make offers; hence they are makers. Accepted bidders take requests, fulfilled askers take offers; hence they are takers. The Gratzio user can be a maker and/or a taker. Or she can be idle.

### The Make Flowcharts

![Make Flowcharts](./make-flowcharts.png "Shoot 1")

## Frequently Asked Questions

### How to become a sponsored Gratzio user?

To become a sponsored user:

- go to our website;
- select '**Request a special invite**'
- type your greeting and email, then hit '**Continue**'.

We will send you the invite in an email. You will have to go to our website again, select '**Accept the invite**', copy and paste it, then hit '**Continue**'. We will create your Stellar account and fund it with some initial amount of GRAT. You can now use Gratzio Help Exchange!

### What is the difference between sponsored and self-paid users?

A sponsored user does not pay Stellar fees for her transactions. The Gratzio Agent pays them for her. The flip side of it is Agent's becoming a bottleneck under a heavy load from many users. Also, a sponsored user can use only one device (computer or smartphone) for her transactions.

A self-paid user maintains her Stellar account herself and does not require Agent's signature for all her transactions. Interactions between self-paid users are the fastest. Also, a self-paid user can use more than one device for her transactions.

### How to become a self-paid Gratzio user?

To become a self-paid user:

- go to our website;
- select '**Store your Stellar Secret Key on this device**';
- type your greeting and email;
- copy and paste your SSK;
- hit '**Continue**'.

### Can a sponsored user become a self-paid one in the future?

Yes, as soon as she has enough XLM to pay for her Stellar transactions.

### Where is my Stellar Secret Key located?

Your SSK never leaves the device (computer or smartphone) you used to become a Gratzio user.

## See also

[GDF Mandate](https://github.com/amissine/gratzio-join/blob/main/GDF.md)

[Gratzio TESTNET Demo Part 1, silent video recording](https://youtu.be/_lPtvGTF7yo)

[Gratzio TESTNET Demo Part 2, silent video recording](https://youtu.be/RX0DNZQNDdA)

[Gratzio TESTNET Demo Part 3, silent video recording](https://youtu.be/l8jKvAos-KE)
