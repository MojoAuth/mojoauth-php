<p align="center">
  <a href="https://www.mojoauth.com">
    <img alt="MojoAuth" src="https://mojoauth.com/assets/images/logo.svg" width="200" />
  </a>
</p>

<h1 align="center">
  PHP SDK
</h1>

## Introduction

MojoAuth PHP is a wrapper which provides access to MojoAuth Platform APIs.

MojoAuth provides a secure and delightful experience to your customer with passwordless.
Here, you'll find comprehensive guides and documentation to help you to start working with MojoAuth APIs.

Please visit [here](http://www.mojoauth.com/) for more information.

## PHP SDK Demo

This demo allows you to authentication using Email Magic Link. Checkout the example [here](https://mojoauth.com/docs/guides/php/#example) for other authentication methods.

## Configuration

Download the demo, mojoauth-php/demo from php sdk repo or clone the whole repo.

Update the configurations

```
define('MOJOAUTH_APIKEY','MojoAuth API KEY');//update your mojoauth account's APIKey
define('MOJOAUTH_LANG','en'); // Check out the localization document below for other supported languages.
define('MOJOAUTH_TOKEN_HANDLER','http://localhost/mojoauth-php-demo/tokenhandler.php');  // Change the path as per your folder structure
define('MOJOAUTH_REDIRECTION_URL','http://localhost/mojoauth-php-demo/profile.php');   // Change the path as per your folder structure
session_start();
```

Run the demo

[PHP SDK Documentation](https://mojoauth.com/docs/guides/php/)

[Localization](https://mojoauth.com/docs/configurations/localization/)