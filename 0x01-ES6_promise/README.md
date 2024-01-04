This project contains tasks for learning to use Promises in ECMAScript 2015 (ES6).

Tasks To Complete
 0. Keep every promise you make and only make promises you can keep
0-promise.js contains a script that exports a function with the prototype function getResponseFromAPI(), which returns a Promise.

 1. Don't make a promise...if you know you can't keep it
1-promise.js contains a script that exports a function with the prototype getFullResponseFromAPI(success), which returns a Promise. The parameter (success) is a boolean.

 2. Catch me if you can!
2-then.js contains a script that exports a function with the prototype function handleResponseFromAPI(promise), which appends three handlers to the promise argument.

 3. Handle multiple successful promises
3-all.js contains a script that meets the following requirements.

 4. Simple promise
4-user-promise.js contains a script that exports a function with the prototype function signUpUser(firstName, lastName), which returns a resolved promise with the object shown below.

 5. Reject the promises
5-photo-reject.js contains a script that exports a function with the prototype function uploadPhoto(filename), which returns a Promise rejecting with an Error and the string $fileName cannot be processed, where fileName is a string.

 6. Handle multiple promises
6-final-user.js contains a script that meets the following requirements.

 7. Load balancer
7-load_balancer.js contains a script that exports a function with the prototype function loadBalancer(chinaDownload, USDownload), which returns the value returned by the promise that resolved the first, where chinaDownload and USDownload are Promises.

 8. Throw error / try catch
8-try.js contains a script that meets the following requirements.

 9. Throw an error
9-try.js contains a script that meets the following requirements.

 10. Await / Async
100-await.js contains a script that meets the following requirements.
