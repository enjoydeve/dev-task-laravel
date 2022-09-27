### Development Task

US Information Group LLC is a data company at heart, we generate data reports for consumers and businesses via a subscription billing model. Our business model allows us to expand into new markets very quickly, some of the markets we currently operate in include:
* Vehicle Reports
* Property/Adress Records
* Marriage/Divorce Records
* Public Records

Before we explore a new market, we like to create what we call a vertical ad test, it’s essentially a dummy site that has no real functionality, customers are never charged, we don’t take their payment details or even generate a report (we usually just say “an error occurred”. We do this so we can gain insight into the potential marketing costs for a market.

Typically we can get these ad test sites done in a few days, there’s no high expectation of test coverage or anything, it’s purely to assess the potential success of a market in a timely manor.

For this ad test, we’re looking into DMV records, we’re in the middle of sourcing our data provider for this vertical. All of our sites follow a very similar structure in terms of how the customer flow works, some of our websites are:

https://carlookup.com

https://vehiclehistory.us.org

https://searchfinder.com

You’ll notice there’s plenty of fake progress bars, loaders etc that generate confidence with the user.

An example of a DMV records report site would be:

https://www.dmvrecords.us.org/

Requirements:
* This must be done in Laravel (Mainly to assess your laravel skills)
* No requirement to use a front-end JS framework (React, Vue etc), our sites are purely static HTML with some vanilla JS for the fake loaders
* The only data that needs to be stored is just the customers name, email, phone etc. Don’t store any payment info.
* When the user checks out display redirect them to a /error page which will we use as a conversion tracking page
