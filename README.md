# WARNING !
For safety reasons. As of January 1, 2020, the use of HTTP protocol will no longer be available.

Please use HTTPS protocol from now.

# Welcome !

The Delcampe API allows you to communicate easily with the Delcampe.net services. It allows you to start sales, close them, be informed when items are sold, etc.

This site is aimed for developpers. If you are a collectible company and are looking for information over the API, please contact Delcampe.net.

You will find here all the needed information to begin with the new Delcampe API REST (easy to use with PHP, Java, Ruby, .net, Python, Perl, etc.). 

## Delcampe's API REST, what for ?

With the Delcampe's API REST, you could perform the following actions :

* put an item on sale (auction or fixed price)
* have a list of all your items on sale
* modify an item (data and images)
* close an item
* manage your notifications settings
* get Delcampe's category list
* etc. 

Use the Wiki tab of this site, to find :

* Documentation to set up your own API client.
* Documentation to set up your application using our API client.
* Few samples. 

As the API is based on REST, you basically need this information:

1. Your API key. Contact the Delcampe API support to get yours
2. When you have your API key, call [/seller](https://github.com/Delcampe/delcampe-apirest-client/wiki/sellerPost) with POST HTTPS method to get your personal token. 

In order to help you, we propose, for each API resource, code samples in PHP. We'll try to add also other language helpers in the future: Java, Ruby, .net, Python, Perl, ... 

## Documentation

* [How to start](https://github.com/Delcampe/delcampe-apirest-client/wiki/How-to-start)
* [List of Delcampe's API resource](https://github.com/Delcampe/delcampe-apirest-client/wiki/List-of-Delcampe%27s-API-resource)
* There is an [API forum on the Delcampe's website](https://www.delcampe.net/en_GB/forum/api-users).
* Fair use policy: a maximum of 500 000 image update using API calls is allowed per day. 

## User rate limit

The user rate limit is the number of requests that can be made by any user on the Delcampe API.
The maximum authorized request per minute is 180 any subsequent requests will fail with an HTTP code 429.

On 1st december 2022, the default limit for adding new items will be set at 10.000 calls/day, which our data shows should suffice for most businesses on Delcampe. 
Should your volume exceed that or increase, please contact our Customer Support team en@delcampe-support.com so we can review your use case so we can verify that your application is adhering to Delcampe’s Terms & Conditions, and that you've made the most efficient use of the tools you've implemented.

## Warranty

The Delcampe API, Services and all related parts thereof are provided on an “as is” and “as available” basis and with “best effort” support, but without any warranties of any kind either expressed or implied. This includes but is not limited to any warranties of merchantability, fitness for a particular purpose, flawless and uninterrupted functioning and reliability.

## Feedback and contact

* [Contact Delcampe](https://github.com/Delcampe/delcampe-apirest-client/wiki/Contact-Delcampe)
