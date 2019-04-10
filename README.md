# contentIo
A blockchain cloud plaform for content review

As social media grow, the content inseted on that surpass millions of billions of data, and unfortunatelly the review of their contents are unaccurate.
We can see a lot of users complaining that their content were demonetized, deleted or their account blocked. In order to take content review to a new level , a new approach for this issue needs to be approached.

## Goal

To create a blockchain notary book where the content to be reviewed will be issued, reviewed and the result recorded , using digital signature and third party reviewers.


## Process

1 .The **Issuer**: a company like Facebook , request to the blockchain a content to be reviewed , issuing a value to be paid for that content.

2. The **Reviewer**: The first `n` users connected to the platform who selfAssign the review lock the analisis of that content and give their result , based on the issuer internal policies. The users can't know each others , so that the system works a non-trustfull nodes.

3. The **Witness**: once the **Reviews** are issued, node algorithms take the reviewers result, and record the content result on the blockchain, working as a notarybook for consultation by the Issuer. Therefor the value are divided by the Reviers and credit on their account, which will be paid montlhy/weekly

4. **Appealling** : users/reporters can appeal te result of the review and a new request are issued. `n` appeals can be granted by review, defined by the **Issuer**


## Pros
Companys can use the platform where the pool of nodes to be reviewed can give more returns for the content **Reviewers**
Platform can be `onPrem` or `onCloud`.
**Reviews** can be more reliable.

## Cons
Develop how the platform will recieve the content from the **Issuer** for **Review** 

Define how a appeal must be accepeted by a **Reviewer**. A `punitive proof-of-stake` must be implemented to enforce the need of the reviewer be trustfull on his/her review(also can work for managing the user behaviour)