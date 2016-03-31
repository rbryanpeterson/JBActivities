copied from https://github.com/salesforce-marketingcloud/http-request


# Journey Builder Custom Activities
## Contains Master, Call Center Branch, and Direct Mail branch

**NOTE:** Deploy individual branches via multiple Heroku apps.

### Heroku Config Vars

* ACTIVITY_DESCRIPTION - description of activity
* ACTIVITY_NAME - name of activity that will be shown in JB
* APP_NAME - name of heroku app
* CLIENT_ID - client id from app center
* CLIENT_SECRET - client secrect from app center
* KEY - key of JB activity created in app center
* REQUEST_BODY - {"key":"value"}
* REQUEST_HEADERS - Content-type,application/json
* REQUEST_METHOD - GET
* REQUEST_URL - https://www.exacttargetapis.com/platform/v1/tokenContext
