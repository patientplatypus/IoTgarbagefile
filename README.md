# Issue with http://www.oracle.com/webfolder/technetwork/tutorials/obe/cloud/iot/quickstart/QuickStart_JS/qs_iot_js.html

- Note that I've ignored my provisioning file in the repo, but have it in my original.
- Running `npm install && sh run-device-node-sample.sh app.js provisioning superdupersecretpass`results in the following error:

`executing run-device-node-sample.sh from .
module.js:487
    throw err;
    ^

Error: Cannot find module 'device-library.node.js'
    at Function.Module._resolveFilename (module.js:485:15)
    at Function.Module._load (module.js:437:25)
    at Module.require (module.js:513:17)
    at require (internal/module.js:11:18)
    at Object.<anonymous> (/Users/patientplatypus/Documents/Oracle/IoT/nodeApp/app.js:56:7)
    at Module._compile (module.js:569:30)
    at Object.Module._extensions..js (module.js:580:10)
    at Module.load (module.js:503:32)
    at tryModuleLoad (module.js:466:12)
    at Function.Module._load (module.js:458:3)`
