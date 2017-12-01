# Subway Tracker

Subway-tracker is a Rails backend/Vanilla JS frontend project project.

Using the MTA's API, the app pulls the current location of numbered trains (1-6), and plots their locations on Google maps. A dropdown allows a user to filter for a specific line. It also has clickable markers for all Subway stations in NYC.

## Getting Started

The easiest way to ensure that you have adequate environment is to use RVM.

### Prerequisites

Using Rails v. 5.1.4 and  Ruby v. 2.3.1. 


### Installing

First run: bundle install

```
$ bundle install
```

Create the database and run the migrations: 

```
$ rails db:create
$ rails db:migrate
```

Seed the database:

```
$ rails db:seed
```

## Deployment

If there is nothing else running on port 3000, simply run:
```
$ rails s
```

Then open index.html in the root directory.


## Built With

* Ruby on Rails
* Postgresql
* Vanilla JS
* Google Maps
* The Metropolitan Transportation Authority's API

## Versioning

Latest version is always available under the master branch in this repository. 

## Authors

* Zali Perlow
* Joe Cha - https://github.com/bother7

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
