This is a mirror of the Twilio.js client side Javascript code, published to
NPM. For whatever reason, Twilio has neglected to publish this themselves.

Note that the current Twilio code has side effects simply be requiring it. I'm
not kidding. Simply loading this library will attempt to read window.location
and loop over all script tags in the DOM. Because of this poor design, this
library cannot currently be used in Node (server side builds). I hope to
address this in a later release.

### Version

1.3.16

### Original CDN URL

You can verify the contents of this package against the official Twilio bundle:

[http://media.twiliocdn.com/sdk/js/client/releases/1.3.16/twilio.js](http://media.twiliocdn.com/sdk/js/client/releases/1.3.16/twilio.js)

### Documentation

[https://www.twilio.com/docs/api/client/twilio-js-13](https://www.twilio.com/docs/api/client/twilio-js-13)

### Javascript Client Overview

[https://www.twilio.com/docs/api/client/twilio-js](https://www.twilio.com/docs/api/client/twilio-js)
