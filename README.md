# Bank-app
Fun little bank application to practise my JavaScript coding. I have hard coded 2 accounts with some data in it, just to get started with and give it more realistic vibe. In this application you can transfer money between accounts which will be automatically updated to both accounts log and UI. There is many functionalitys which you can spot by testing and playing with the app.

Some rules, if you want to get loan, you have have atleast 10% the amount of loan in your current bank account.
You can't transfer money over the amount you have currently on your bank account.
You will be logged off if you are inactive for 5 minutes.
The first account's currency is in EUR and second's currency USD, when you transfer money between these account's the currency rate will be automatically counted before adding it to receivers log. Both of these accounts interest-rate are hard coded, so it wont be maybe accurate to the real world's rate.

Username for the first account is, 'as' and password '1111'

Username for the second account is, 'ml' and password '2222'

You can change these usernames in JS script by giving new 'owner' value in the accounts object. The username will be automatically generated by firstname's first letter to lower case and lastnames first letter to lowercase
