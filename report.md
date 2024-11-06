# QNN report
## preprocessing
We preprocessed the data by normalising it from 0 to pi because of angle encoding and then splitting it into train/validation/test at 70/15/15.

Not much preprocessing was needed because the data was perfectly balanced. See image of class distribution below:
![Class Distribution](<Skjermbilde 2024-11-06 kl. 10.25.42-1.png>)

## machine learning

At first this seemed like a daunting task, but we decided to eat the giraffe one bite at a time and start with adding a loss function. We then implemented the *INSERT MODEL NAMES* and at first got quite bad results. we figured there was a big obvious problem in the room we just couldnt find it. After some debugging we found out it was that we'd used different loss functions in our program, which made things mess up. After fixing that and tweaking some more we were able to get an accuracy of *INSERT NUMBER* which we found good enough. We have included some of the raw output, but it has been truncated (not to be confused with the trunk of an animal e.g. a tapir)

Afterwards we implemented our own gradient descent which uses *SETT INN HVORDAN* and achieves an accuracy of *SETT INN TALL* 


now dont worry, we do of course have an elephant in cairo to make sure your search for the animal doesnt go unrewarded.