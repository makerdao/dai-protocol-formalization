# Overview

This repository contains a formal description of the DAI protocol (or perhaps multiple such descriptions, at various levels of detail, or in different formalisms--still under construction).

To give some motivation: the DAI protocol, at a very high level, utilizes economic mechanisms to produce a synthetic asset ("DAI") that is valued by the market at an approximately constant price in some
reference asset. At least two reasonably successful, and non-triviially different, versions of the protocol have been implemented on the Ethereum blockchain: single-collateral DAI (the "SAI protocol", or SCD) 
and multi-collateral DAI ("MCD"). There should be a "highest-level" definition or formalization that recognizes both of these systems as instantiations (or near-representations). Below this level, there should
also exist a generalized MCD that can continue to describe the on-chain system as it evolves, or be used to help instantiate the protocol on other chains in the future.
