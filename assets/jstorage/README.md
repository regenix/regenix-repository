#	jStorage
>	<http://www.jstorage.info/>

**jStorage** is a cross-browser key-value store database to store data locally in the browser - jStorage supports all major browsers, both in **desktop** (yes - even Internet Explorer 6) and in **mobile**.

Additionally jStorage is library agnostic, it works well with any other JavaScript library on the same webpage, be it jQuery, Prototype, MooTools or something else. Though you still need to have either a third party library (Prototype, MooTools) or [JSON2](https://github.com/douglascrockford/JSON-js/blob/master/json2.js) on the page to support older IE versions.

jStorage supports storing Strings, Numbers, JavaScript objects, Arrays and even native XML nodes which kind of makes it a JSON storage. jStorage also supports setting TTL values for auto expiring stored keys and - best of all - notifying other tabs/windows when a key has been changed, which makes jStorage also a local PubSub platform for web applications.

jStorage is pretty small, about 7kB when minified, 3kB gzipped.