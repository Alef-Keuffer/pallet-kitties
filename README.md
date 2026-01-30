## Notes

> In Polkadot, the term "call", "extrinsic", and "dispatchable" all get mixed
> together.
>
> Here is a sentence which should help clarify their relationship, and why they
> are such similar terms:
>
> > Users submit an extrinsic to the blockchain, which is dispatched to a Pallet
> > call.
>
> In this case, "extrinsic" is a more broad term than a "transaction".
>
> An extrinsic is any message from the outside coming to the blockchain. A
> transaction is specifically a signed message coming from the outside.
>
> In this tutorial, we will only deal with transactions, but again, learning
> more about extrinsics can be something to follow up on after you have learned
> the basics.
> 
> &mdash; <cite>1.5.5 Pallet Functions # Terminology</cite>

> For ergonomics, you will normally see callable functions defined in the
> lib.rs, but their logic implemented in a separate impls.rs file. This is
> really up to your preference, but since this is the common practice in the
> Polkadot SDK, the tutorial will use this pattern as well.
>
> &mdash; <cite>1.5.5 Pallet Functions # Callable Functions</cite>

> OneOne important detail for creating a struct to be used in a Pallet is that
> the struct should be marked pub. The compiler will complain if you try to use
> an object in your pallet without marking it pub, because it will be used
> across other modules in your blockchain.
>
> &mdash; <cite>3.1.20 Kitty Struct # Creating a Struct</cite>

> As a rule, you only want to store data in your blockchain which is necessary
> for consensus. Blockchains are extremely slow, low powered, and expensive.
> Blockchains are extremely good at one thing: achieving agreement among a
> decentralized and untrusted set of individuals.
>
> &mdash; <cite>3.4.23 Track Owned Kitties # Redundant Storage</cite>

Wasn't Polkadot about achieving distributed computing?
