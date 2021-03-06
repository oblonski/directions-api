[Go to overview](./README.md)

## What is one credit?

You can use [the estimator in the dashboard](https://graphhopper.com/dashboard/#/pricing) to easily calculate the necessary credits or get more details of how credits are calculated with the following:

 * one Routing API request costs 1 credit. Every 10 via-points will cost 1 additional credit. E.g. 11 via-points cost 2 credits
 * one Geocoding API request costs 1 credit
 * one Matrix API request with some start locations and some destinations costs `starts * destinations` credits if `starts+destinations < 20` for bigger matrices we use the cheaper formular `(starts + destinations) * 5`. For example you have 2 start locations and 10 destinations the charged credits are `2 * 10 = 20` or for 20 start and 20 destinations it is `(20 + 20) * 5 = 200`
 * the costs for one Optimization API request depends on the number of vehicles and activities and is calculated as `vehicles * activities * 10`

## Can I pay on demand?

It is possible to pay online without delay. But paying for an increased demand is currently not possible, please [let us know](https://graphhopper.com/#contact) of your needs and we can arrange a solution.

## Do you offer discounts?

Yes, you get a discount if you sign up for an annually contract. Also [follow us on Twitter](https://twitter.com/graphhopper) to get the latest campaign.

## How to cancel, upgrade or downgrad my package?

Please [contact us](https://graphhopper.com/#contact)
