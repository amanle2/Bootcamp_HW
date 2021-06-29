## HW 14 - Project Questions
---
1. Which model has a lower loss? - The LTSM model which references a 10 day window of closing prices for BTC to predict the 11th days price. Overall loss is substantially lower in this model as shown by the 0.0061 loss when the model is evaluated.

2. Which model tracks the actual values better over time? - This is easily the model which references the 10 day window of BTC closing prices. The other model which relies on the FNG has almost no ability to track with the actual values, and stays within a band from 6,000 to 8,000 typically.  It does tend to follow the up and down trend somewhat, but actual values are not close in this model.

3. Which window size works best for the model? - The largest window size of 10(the suggested range was 1 to 10) ended up being the best for loss minimization, although the differences between them seemed negligible.
