<h1 align="center">
    <a href="https://dreamfactory.com/">
    <img src="https://raw.githubusercontent.com/dreamfactorysoftware/dreamfactory/master/readme/vertical-logo-fullcolor.png" alt="DreamFactory" width="250" /></a>
</h1>

<p align="center">
    <strong>Instant APIs without code</strong>
</p>

<p align="center">
    <a href="https://wiki.dreamfactory.com">Docs</a> ∙ <a href="https://genie.dreamfactory.com">Try Online</a> ∙ <a href="https://github.com/dreamfactorysoftware/dreamfactory/blob/master/CONTRIBUTING.md">Contribute</a> ∙ <a href="http://community.dreamfactory.com/">Community Support</a> ∙ <a href="http://guide.dreamfactory.com/">Get Started Guide</a>
</p>

<p align="center">
    <a href="https://twitter.com/dfsoftwareinc?lang=en"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/dfsoftwareinc.svg?style=social"></a>
</p>

<p align="center">
<a href="https://heroku.com/deploy?template=https://github.com/dreamfactorysoftware/dreamfactory">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>


[Sign up](https://genie.dreamfactory.com/register) for a DreamFactory account and visit our [Developer Hub](https://developers.DreamFactory.com) for even more content.

#  DreamFactory API

Postman Collection demonstrating how to use the [DreamFactory MYSQL](https://guide.dreamfactory.com/docs/chapter03.html#generating-a-mysql-backed-api) REST API.
More information about the API can be found on the [DreamFactory Guide](https://developers.DreamFactory.com/api/)

## Installation

To use the latest published version, click the following button to import the DreamFactory API as a collection:

[![Run in Postman](https://s3.amazonaws.com/postman-static/run-button.png)](https://www.getpostman.com/collections/a01fb99056769a35df72)

You can also download the collection file from this repo, then import directly into Postman.

### Prerequisites

- *Postman* The collection is for use by the Postman app. Postman is a utility that allows you to quickly test and use REST APIs. More information can be found at [getpostman.com](https://www.getpostman.com/).
- *DreamFactory API key* To use our API, you must have an API key with permissions enabled for which resource you want to use.

## Usage

The collection is arranged in folders according to the API endpoints.

All requests require a valid DreamFactory API key.  The collection requests have a placeholder variable called `X-DreamFactory-Api-Key` for this.
This should be set in your [Postman environment](https://learning.postman.com/docs/postman/variables-and-environments/variables/#understanding-variables-and-environments) i.e. outside the collection itself.

A collection-scope variable `BASE_URL` points to the host. For the purpose of this collection we have created a demo server `https://demo.dreamfactory.com/api/v2/mysql-playground/`.


More information on managing Postman environments and variables can be found [here](https://www.getpostman.com/docs/v6/postman/environments_and_globals/variables).

|Variable  |Default value               |Set in         |
|----------|----------------------------|---------------|
|`API_KEY` |b261acacd426fb9ef8ef5825d57d4470c7a14fd4ca5350b00dd015bb3bdcd6e6                          |Collection    |-                |-      |
|`BASE_URL`|`https://demo.dreamfactory.com/api/v2/mysql-playground/` |Collection     |Environment      |



## See Also

[DreamFactory Guide](https://guide.dreamfactory.com/docs/)

[DreamFactory Blog](https://blog.dreamfactory.com/)

[Postman API development tool](https://www.getpostman.com/)
