---
id: beginners-guide
title: Beginner's Guide
---
Simple example in brawser


<script src="https://cdnjs.cloudflare.com/ajax/libs/bluebird/3.3.4/bluebird.min.js"></script>
<script>
'use strict';
var promise = new Promise(function(resolve) {
    setTimeout(function() {
        resolve("result");
    }, 1000);
});
promise.then(function(result) {
    alert("Fulfilled: " + result);
}, function(error) {
    alert("Rejected: " + error);
});
</script>
[beginners-guide](unfinished-article)
