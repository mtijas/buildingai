# Money Saver AI
Money Saver AI is my AI idea for [Building AI](https://buildingai.elementsofai.com) course. 

## Summary

Money Saver AI basically an automatic spending tracker with meaningful notifications and spending reporting based on machine learned spending habits from actual expense/income data fetched from the user's bank. The basic idea is to help people save money in a fun and easy way.

## Background

The problem I'm trying to solve with this idea is visualizing one's spending habits and providing meaningful and easy controls (notifications, visualizations etc.) to help reduce (unnecessary) spending. I believe this is something almost all of us need to consider at some point in our lives, thus having a huge potential for improving our spending habits long-time.

## Data and AI techniques

The data would probably be customer's own banking data fetched automatically from the bank's API, with additional (manual and automatic) categorization and commenting of the data (both in general categories and if the expense is mandatory or not). The user should also be able to manually enter expenses and income information to the system.

At first when an user begins using this service, they should probably do some assisted manual categorization of the fetched data. The AI should of course help there (as it probably has learned something from other users data already), but to better suit to the current user's data, some hints about spending should probably be given manually.

After a few weeks of collecting and analyzing user's data, the AI/service should become more and more automatic in determining meaningful patterns in the spending habits (in relation to income as well). There could also be targets for saving money, and tools like that to make saving money more interesting task.

I think that the AI could employ some deep learning techniques on categorization of expenses, but some simpler methods, like vector distances, could also be used to determine if any single expense is mandatory (e.g. child's food) or not (e.g. cheap beer) (note: some might consider beer to be more important, and that should be ok esp. if the user doesn't have children). 

## How is it used?

This idea could be implemented as a web service or even as part of the bank's own service portfolio. The user could be basically almost anyone, since more and more people use internet banking and have access to their banking data in digital form. Of course this would be an additional service for those interested in saving money, even if it would be provided by the bank.

## Challenges

The first challenge to consider is quite obviously privacy, as it could be catastrophic to lose one's banking data into the public. Banking data is considered sensitive information and should be handled with utmost care. Earning potential user's trust is hard (especially in this context) and the service should provide a meaningful amount of "tangible" value (money saved) to be considered "worth the risk".

Of course the AI (and notifications, report, visualizations etc. derived from that) should have hight precision and usability to be meaningful, which means the implementation should be carefully considered both in what data we actually could use, and in which way it should be done.

## What next?

A simpler proof-of-concept service could be built for testing different kind of AI implementations and to showcase the benefits to potential investors. Privacy concerns should also be addressed by considering all the laws and regulations, additional concerns of potential users, and concerns of potential investors.

## Acknowledgments

This idea was inspired by:
- [Money Lover](https://moneylover.me/)
- [OP Mobile](https://www.op.fi/private-customers/digital-services/op-mobile)
