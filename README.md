# Tiger brokers Automated options strategy builder

# Disclaimer
**DISCLAIMER: This software is for demonstration and testing purposes ONLY! Usage of this software for any financial purposes is highly unrecommended and not within the original intention of the project. The software may encounter bugs that affect the outcome of the trade. I am not a financial expert. This is not financial advice. USE AT YOUR OWN RISK**

## Overview
Option Strategy refers to a combination of positions in an account with a hedging relationship, typically a combination of options and underlying stocks. Tiger will apply some margin relief to the Option Strategy in consideration of the fact that the option strategy mitigates the relevant risks.

# Developers note:
This project has been created for testing and educational purposes related to the Tiger Brokers and TDAmeritrade APIs in Python.
**The project will also not receive updates**


## Problem
In the past, You could not send options combo strategies straight to tiger brokers, instead needing to purchase each leg in the strategy seperately. This costs time and potentially wastes profits due to price fluctuations.
Clients also need to meet the corresponding conditions and have opened the option strategy permissions in order to have risks mitigated. 

## Solution
This application aims to solve that problem by building your own custom options strategy, and then purchasing all legs at once at the current market price, allowing any user to purchase a combo strategy without needing to buy each leg seperately, saving valuable time.

## Features
* Simple, easy to use command line interface
* Requires no priror programming / software experience
* Hand holding style instructions
