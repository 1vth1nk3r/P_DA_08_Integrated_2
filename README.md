# Exploring food-selling startup users' behaviour patterns
This is the second integrated project of the Practicum DA/DS course, combining Business Analytics, Making Business Decisions Based on Data and How to Tell a Story Using Data sprints.

## Description
Here we have a dataset on a startup that sells food products. We want to explore users' behaviour patterns. 

First, we should do some data preprocessing: clean the data, fill in the missing values (if any), and change data types. Also, we need to add some new columns to help our analysis. After doing so, we could explore our data.

## Conclusion
After preprocessing, we checked that we didn't have any users in several groups simultaneously and made the group value human-readable.

Investigating the data, we found that our logs start on 2019-07-25, but part of the data before 2019-08-01 looks incomplete. So we excluded about 25% of the events.

Also, judging from the data, we concluded that the `Tutorial` didn't belong to the event funnel and excluded it.

While 47% of users made the entire journey from `MainScreenAppear` to `PaymentScreenSuccessful`, we lost the most share (38%) between the `MainScreenAppear` and `OffersScreenAppear`.

We failed to see any significant difference between the groups plotting the event funnel and running tests on the proportions.
Changing the font didn't make any difference; all three groups belong to the same statistical population.

Since after the `MainScreenAppear` we lost almost twice as many users as after `OffersScreenAppear`, I suggest looking for possible improvements on the main screen. For example, adding special offers (instead of the dedicated screen) could boost purchases.