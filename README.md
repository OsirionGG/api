# osirion public api
> the api for fortnite match data 💚

the osirion public api makes it easy to access match data from uploaded client replays and server replays (tournament matches), without needing an up-to-date parser of your own.

## prerequisites

to use the api, you need to:

- create an osirion account on [our website](https://osirion.gg)
- generate an api key under [account settings](https://osirion.gg/app/settings)
- load up on some api credits under [account settings](https://osirion.gg/app/settings)

once done, you can use the api via REST endpoints or via the [``@osirion/api`` npm package (for JS/TS)](https://www.npmjs.com/package/@osirion/api).

each api call costs credits, and 1000 credits is about equal to €1.

- uploading replays costs 20 credits (~€0.02).
- ping costs 1 credit per request (0.001€).
- every other request is charged based on a pay-as-you-go compute model. credits are charged per second of compute used, with a 10-second minimum.
- match event endpoints are charged the same way, but scaled with the number of events being requested. with a maximum of 8 events being charged.

note that this is subject to change as we develop the api further.


## docs and endpoints

for now, you can find endpoints in this [Postman collection](https://documenter.getpostman.com/view/23177710/2s9YeHarB1).


## have you got feedback or issues?

create a new issue in the "issues" tab, and let us know!

