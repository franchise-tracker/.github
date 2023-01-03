# 🖖 Franchise Buddy [Currently in heavy development] 

Did you ever want to watch the entire MCU and wondered where to begin?

Franchise Buddy will help you with that.

Franchise Buddy is an app that gives you a roadmap on how to watch all movies and series of MCU in order. Thanks to Franchise Buddy you will understand all ester eggs and awesome details about the Marvel universe. (And others in future)

## 🛠️ Tech stack:

The mobile app is built with [React Native](https://reactnative.dev/).

On the backend, we used [GraphQL Federation](https://www.apollographql.com/docs/federation/) to securely expose all microservices through one single endpoint.

Currently, we have three microservices :

- Frontend api - Graphql Federation 
- Content api - Providing content (Movies and series)
- Progress api - Storing progress of watching.

All services are deployed using [k3s](https://www.k3s.io/). All details could be found in the __provision__ repository.
We are using [Grafana](https://grafana.com/) for monitoring.

## 🤓 Creators:
[Nikodem Wrona](https://github.com/nikodem-wrona)
[Adam Gołąb](https://github.com/adam-golab)
