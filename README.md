Hijack Worker
=============

Hijack web workers in the browser to stop coin miner.

Try this script on MDN's simple worker page:
http://mdn.github.io/simple-web-worker/

Features
--------

* Hijack browser's `Worker`/`SharedWorker` and ask the user whether to allow them.
* Blacklist/whitelist to always block/allow the worker.

Installation
------------



Compat notes
------------

* This script needs to be executed before other scripts.
* There is no userscript manager which can ensure that the userscript is always executed before page scripts.
* If you are using Tampermonkey, you can change "Config mode" to "Advanced" then change "Inject Mode" to "Instant" in the settings, so the script would be executed faster.
* See [hijack-worker-extension](https://github.com/eight04/hijack-worker-extension) for a better solution.

Changelog
---------

* 0.2.0 (Jan 31, 2018)

  - Add: location.href to confirm message.
  - Remove: page script validation is not reliable.

* 0.1.0 (Jan 30, 2018)

	- First release.
