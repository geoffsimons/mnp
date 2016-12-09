# mnp
## Monday Night Pinball

Welcome to the Monday Night Pinball (MNP) source repository. The goal of this project is to provide the means to run a pinball league similar to http://www.mondaynightpinball.com or with some extensions, other types of pinball events.

## Phase 1 - API

MNP is based on a RESTful API. The core model includes players, machines, venues, games, matches, teams, and seasons. We will be describing each of these in more detail.

## Phase 2 - API Server

The plan is to use ExpressJS for our route logic and Mongo for storage (or possibly Firebase), although we will likely use an abstraction for storage to be able to plug n play different solutions.

## Phase 3 - Angular Web App

It may end up where we build the front and back end at the same time if we have the resources to make that happen. Otherwise, we'll build an angular app when the API server is ready.



