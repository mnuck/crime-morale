# Crime Morale

A userscript to show the demoralization effect in Torn Crime 2.0.

This is a fork of [tobytorn/crime-morale](https://github.com/tobytorn/crime-morale), maintained by
WillieMcCoy [2048015]. It differs from the original in the scamming solver:

- The Exp strategy weights payout cells by the scam's level tier, so higher-level targets are worth
  more risk and more turns.
- The solver is rewritten for speed. It uses the same model and gives the same answers.
