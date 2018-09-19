# Reviews
![](https://github.com/vinpatel/Reviews/blob/master/The%20Reviews%20App.png)

# Facebook Graph Integration 
Overview

Methods used to interact with the Facebook Graph API.

See github.com/arsduo/koala/wiki/Graph-API for a general introduction to Koala and the Graph API.

The Graph API is made up of the objects in Facebook (e.g., people, pages, events, photos, etc.) and the connections between them (e.g., friends, photo tags, event RSVPs, etc.). Koala provides access to those objects types in a generic way. For example, given an OAuth access token, this will fetch the profile of the active user and the list of the user's friends:

You can see a list of all of the objects and connections supported by the API at developers.facebook.com/docs/reference/api/.

You can obtain an access token via OAuth or by using the Facebook JavaScript SDK. If you're using the JavaScript SDK, you can use the OAuth#get_user_from_cookie method to get the OAuth access token for the active user from the cookie provided by Facebook. See the Koala and Facebook documentation for more information.
