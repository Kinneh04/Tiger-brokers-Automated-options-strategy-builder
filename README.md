# Tiger brokers Automated options strategy builder

# Disclaimer and Dev Notes
**DISCLAIMER: This software is for demonstration and testing purposes ONLY! Usage of this software for any financial purposes is highly unrecommended and not within the original intention of the project. The software may encounter bugs that affect the outcome of the trade. I am not a financial expert. This is not financial advice. USE AT YOUR OWN RISK**

Also dont worry about it being malicious. I have no use for your data anyways :)

**The project will also not receive updates**

## Overview
Option Strategy refers to a combination of positions in an account with a hedging relationship, typically a combination of options and underlying stocks. Tiger will apply some margin relief to the Option Strategy in consideration of the fact that the option strategy mitigates the relevant risks.

## Problem
Currently, You cannot send options combo strategies straight to tiger brokers, instead needing to purchase each leg in the strategy seperately in order for the combo to be recgonized and the margin relief to take place. This costs time and potential lost profits due to price fluctuations.
Clients also need to meet the corresponding conditions and have opened the option strategy permissions in order to have risks mitigated. 

## Solution
This application aims to solve that problem by allowing users to build their own custom options strategy, and then purchasing all legs at once at the current market price, allowing any user to purchase a combo strategy without needing to buy each leg seperately, saving valuable time. The application also tracks prices, shows potential gains and losses, and implements buying power checks to make sure you dont go over budget.

## Features
* Simple, easy to use command line interface
* Requires no priror programming / software experience
* Hand holding style instructions
* Gains and Losses calculations

## Pre requisites
The application needs a few requisites before you can use it. All these requisites are free
* A valid tiger brokers account with Developer access (For your account ID).  [Sign up as a Tiger developer](https://quant.itigerup.com)
* A 1024 length RSA key for security [Generate RSA Key](https://cryptotools.net/rsagen)
* A TDAmeritrade developer account (to pull stock prices for calculation) [Sign up as a TDAmeritrade Developer](https://developer.tdameritrade.com)

# Instructions on how to use
## Disclaimer
Again, I recommend only using your developer demo account for this.

## Steps
1. In the folder, there are 3 files. as shown below:
   
  ![Instructions_1](https://github.com/Kinneh04/Tiger-brokers-Automated-options-strategy-builder/assets/82500628/5ebb708f-2b31-417f-973d-5fcf5cc5679b)
2. Open up CustomCfg.Config in Notepad or VSCode and enter in your tiger ID and account ID


  ![Instructions_2](https://github.com/Kinneh04/Tiger-brokers-Automated-options-strategy-builder/assets/82500628/a65b4811-20d4-4240-959b-0a234c8c4a36)

3. Save, close and open config.py in notepad or VSCode. Insert your TDAmeritrade Consumer Key, private key and AmeritradeID into the fields, as below:

   ![Instructions_4](https://github.com/Kinneh04/Tiger-brokers-Automated-options-strategy-builder/assets/82500628/0bd4ac2e-3a75-48b0-8410-ae647f69f0ee)

4. Save, close and create a new text file called Key.pem, inside the same directory as the config file
5. Open it using notepad and insert your public RSA key.

![Instructions_3](https://github.com/Kinneh04/Tiger-brokers-Automated-options-strategy-builder/assets/82500628/1e32f11d-a9b5-4694-be82-d6ea1a5dab2f)
5. Save, and open the Application exe. Follow the instructions and you should be done!

![Capture](https://github.com/Kinneh04/Tiger-brokers-Automated-options-strategy-builder/assets/82500628/6787c0ca-2f10-43ba-9b05-c01a7c523bba)


## Screenshots

![Capture3](https://github.com/Kinneh04/Tiger-brokers-Automated-options-strategy-builder/assets/82500628/0ad7741a-a482-403c-a86e-c54ee15c0926)
![Capture2](https://github.com/Kinneh04/Tiger-brokers-Automated-options-strategy-builder/assets/82500628/4a6b242f-8333-4d0f-85a5-592a3700faed)
![Capture_1](https://github.com/Kinneh04/Tiger-brokers-Automated-options-strategy-builder/assets/82500628/94833121-c866-4008-adb7-b2430dc65969)
![Capture4](https://github.com/Kinneh04/Tiger-brokers-Automated-options-strategy-builder/assets/82500628/c9fb2f53-d806-4886-bc93-29c5533644b5)
