![image_squidhome@2x.png](http://i.imgur.com/RIvu9.png) 

# Parse API Adapter

Integrate Sails.js with Parse API.

## Getting started
1. Add sails-parse to your Sails.js project dependencies.
2. Run <code>npm install</code>.
2. Set up your Parse configuration at <code>config/adpters.js</code> as following:
<code>
parse: {
    module: 'sails-parse',
    appId: 'LueX7LyLu0ngWmEzqk4ge8emkQqgPi1RCeDx5Gm9',
    masterKey: '1B174DCGWCBO19tHxtj9Yei15TJgTLqfqLi1J9mA'
}
</code>

## How to test your adapter
Not implemented yet. Sorry :(

## Submitting your adapter
1. Do a pull request to this repository (make sure you attribute yourself as the author set the license in the package.json to "MIT")  Please let us know about any special instructions for usage/testing.
2. We'll run the tests one last time.  If there are any issues, we'll let you know.
3. When it's ready, we'll update the documentation with information about your new adapter
4. Then we'll tweet and post about it on our blog, adoring you with lavish praises.
5. Mike will send you jelly beans.


## About Sails.js and Waterline
http://SailsJs.com

Waterline is a new kind of storage and retrieval engine for Sails.js.  It provides a uniform API for accessing stuff from different kinds of databases, protocols, and 3rd party APIs.  That means you write the same code to get users, whether they live in mySQL, LDAP, MongoDB, or Facebook.
