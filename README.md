# **Project Name**:  

ATM App


# **Description**: 

The ATM app allows a user to deposit money into an account and withdraw money from an account. (Please note that this is not a truly functioning app that connects to a real live bank account; it is a simulation.) 

An account balance is displayed. The balance begins at zero and changes with each submit button press. The account balance will never go below zero, due to validation in the code.

There is a multi-choice selection between Deposit and Withdrawal UI, which allows the user to switch between Deposit, Withdrawal, and a null option (the initial position). This is coded in a <select> input element below Account Balance. Once Deposit or Withdraw mode is selected, content will be displayed below the multiple choice selection. There is an input field for numbers and a submit button for the user to render a transaction.

The ATM app project is an example of my ability to create a React app, employ Babel transpiler, and my JSX, Javascript, HTML5, and css coding capabilities, and as such, it is one component of my professional portfolio. This particular project is based off of similar activities I worked on in August of 2023 in module 15 of the MIT xPro via Emeritus bootcamp I was enrolled in called "Professional Certificate in Coding: Full Stack Development with MERN."

**I changed the original course task in the following ways:**
* Added a start mode where the users first course of action is to select between deposit and withdrawal modes, which then removed the need for a Deposit and Withdrawal buttons. This distinction changes the screen so the user is less likely to accidentally deposit or withdraw by mistake when intending to select the opposite choice.
* The submit button does not work (it is greyed out & has no onClick powers) unless a new number has been entered in the input. 
* The submit button does not work if the withdrawal amount is greater than the account balance.


# **Installation and Usage**: 

To run my project on your machine, download the files onto your machine or clone the repo. Navigate to the project directory in terminal. Install the necessary dependencies by typing the command prompt: npm install. Start the server by typing the command prompt: npm start.

If you are having issues, ensure the version of Node.js you are using is compatible.


# **Dependencies**: 

The project relies on the following dependencies: React, Google Fonts, Bootstrap, Babel


# **Support**: 

Please contact me via email at krentmeester@uwalumni.com.


# **Roadmap**: 

Future fixes or improvements that would be helpful to a user:

* Add an error message when user attempts to withdraw amounts greater than account balance, to further alert the user of why they cannot complete a transaction. 

* Change the background color to charcoal for the initial ATM mode. Change the background color to green for deposit mode and red for withdrawal mode.

* Add sound effects for each transaction type.

* Add a welcome message.
 
* Add a bank logo.

* Add a feature so that upon starting the app, the account balance does not start at zero, but rather it remembers the previous transactions and carries over the account balance to the next session of deploying the app.


# **Contributing**: 

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


# **License**: 

MIT License

Copyright (c) 2023 Kerri Rentmeester

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.