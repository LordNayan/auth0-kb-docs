# Logging - Auth0

Auth0 provides various functionalities/triggers that has to be configured in Auth0 itself like,
- Custom Database Action [Scripts](https://auth0.com/docs/authenticate/database-connections/custom-db/templates)
- Actions - These are trigger scripts that run after 
    - Login
    - Credential Exchange
    - Password Reset 
    - Post user Registration
    - etc.

    Explore more [Actions](https://auth0.com/docs/customize/actions/flows-and-triggers)

All these scripts are in JavaScript so you might want to get some logs for development purpose. You can put console.log in the scripts and then those logs can be observed in real time by installing the below extension.

[Real-time Webtask Logs Extension](https://auth0.com/docs/customize/extensions/real-time-webtask-logs)

