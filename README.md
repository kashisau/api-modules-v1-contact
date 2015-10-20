# Contact module
## Requires website API
Previously integrated into the source of [Kashi's Website API](https://bitbucket.org/KashiS/website-api/), this module facilitates the contact form microservice API for validating input data and sending messages.

The current implementation performs submission validation for a set number of fields `name`, `email` & `body`. The response from the module (and thus the website API microservice) has a basic implementation of of the [JSON API](http://jsonapi.org/) spec.

## Development roadmap
To be implemented is unit-testing for the validation and contact model, as well as HTTP-based testing of routes and API behaviours.