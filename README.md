## Notes

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
