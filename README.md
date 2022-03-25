# tenmo[README.md](https://github.com/SpenceWalker/tenmo/files/8353113/README.md)


Required use cases
You should attempt to complete all of the following required use cases.


[COMPLETE] As a user of the system, I need to be able to register myself with a username and password.

A new registered user starts with an initial balance of 1,000 TE Bucks.
The ability to register has been provided in your starter code.



[COMPLETE] As a user of the system, I need to be able to log in using my registered username and password.

Logging in returns an Authentication Token. I need to include this token with all my subsequent interactions with the system outside of registering and logging in.
The ability to log in has been provided in your starter code.


As an authenticated user of the system, I need to be able to see my Account Balance.
As an authenticated user of the system, I need to be able to send a transfer of a specific amount of TE Bucks to a registered user.

I should be able to choose from a list of users to send TE Bucks to.
I must not be allowed to send money to myself.
A transfer includes the User IDs of the from and to users and the amount of TE Bucks.
The receiver's account balance is increased by the amount of the transfer.
The sender's account balance is decreased by the amount of the transfer.
I can't send more TE Bucks than I have in my account.
I can't send a zero or negative amount.
A Sending Transfer has an initial status of Approved.


As an authenticated user of the system, I need to be able to see transfers I have sent or received.
As an authenticated user of the system, I need to be able to retrieve the details of any transfer based upon the transfer ID.


Optional use cases
If you complete all of the required use cases and are looking for additional challenge, complete as many of the following optional use cases as you can.

As an authenticated user of the system, I need to be able to request a transfer of a specific amount of TE Bucks from another registered user.

I should be able to choose from a list of users to request TE Bucks from.
I must not be allowed to request money from myself.
I can't request a zero or negative amount.
A transfer includes the User IDs of the from and to users and the amount of TE Bucks.
A Request Transfer has an initial status of Pending.
No account balance changes until the request is approved.
The transfer request should appear in both users' list of transfers (use case #5).


As an authenticated user of the system, I need to be able to see my Pending transfers.
As an authenticated user of the system, I need to be able to either approve or reject a Request Transfer.

I can't "approve" a given Request Transfer for more TE Bucks than I have in my account.
The Request Transfer status is Approved if I approve, or Rejected if I reject the request.
If the transfer is approved, the requester's account balance is increased by the amount of the request.
If the transfer is approved, the requestee's account balance is decreased by the amount of the request.
If the transfer is rejected, no account balance changes.
