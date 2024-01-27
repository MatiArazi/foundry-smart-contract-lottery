# Proveable Random Raffle Contracts

## About

This code is to create a proveably random smart contract lottery using Foundry and Chainlink.

## What we want it to do?

1. Users can enter by paying for a ticket
   1. The ticket fees are going to go to the winner during the draw
2. After X perios of time, the lottery will automayically draw a winner
   1. An this will be done programatically
3. Using Chainlink VRF & Chainlink Automation
   1. Chainlink VRF -> Randomness
   2. Chainlink Automation -> Time based trigger
