# Starbuck Customer Analysis
Capstone project for udacity data science nano degree.
## Motivation
The main goal of this project is to predict wheter the offer will be successful or not according to the demographic and transaction data.
## Dataset description
The dataset contains 3 following files:  
- **portfolio.json** - containing offer ids and data regarding the offer: duration, difficutlty and type.
- **profile.json**  data containing demographic information for each customer.
- **transcript.json** - data containing every record for transaction, offers recieved, offers reviewed and offers completed.

**Portfolio.json**
- offer_id (string) - offer id
- offer type (string) - the type of offer: Informational, Discount, BOGO.
- difficulty (int) - minimum required to spend to complete an offer.
- reward (int) - the reward is given for completing the offer.
- duration (int) - time for the offer to be open in days.
- channels (list of strings)

**Profile.json**
- age (int) - age of the user
- become_member_on (int) - integer referring to the date the customer created an account.
- gender (string) - gender of the customer (Male, Female, Other)
- id (str) - customer id
- income (float) - customers income

**Transcript.json**
- event (string) - record description (transaction, offer received, offer completed, offer viewed)
- person (string) - customer_id
- time (int) - time in hours since the start of the test. 
- value (dictionary of strings) - contains offer id, amount or reward depending on the event.

## Blog
The project article can be accesse [here](https://medium.com/@mfuzail1991/starbucks-capstone-challenge-4b74427062f6)