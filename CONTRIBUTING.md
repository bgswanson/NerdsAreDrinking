# Contribution Guidelines

# Contribution Guidelines

Please branch and issue pull requests to the dev branch to contribute.

## Getting Started

* Add ```192.168.99.12    nerds.dev``` to your hosts file

* Clone this repository
* ```cd /path/to/nerdsaredrinking```
* ```vagrant up```
* ```vagrant ssh```
* ```cd nerds.dev```
* ```php artisan migrate```
* ```php artisan db:seed```
* Browse to [http://nerds.dev](http://nerds.dev)

To run the test suite:

* ```codecept run```

## Vagrant

This vagrant box is built on top of the great work done on [laravel/homestead](https://github.com/laravel/homestead)

## Testing

We use Codeception for testing. Tests should be written to cover as much of our code as possible. We currently rely heavily on acceptance testing but we have Codeception configured for functional and unit tests as well.

## Continuous Deployment

Continuous deployment is always the goal, currently we're configured for continuous integration using Travis-CI.

