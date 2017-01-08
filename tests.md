#Tests

###Unit tests

* [Ava](https://github.com/sindresorhus/ava) - Futuristic test runner - `npm install --global ava`
    
    ```ecmascript
    import test from 'ava';
    
    test(t => {
        t.deepEqual([1, 2], [1, 2]);
    });
    ```
    
    ![](https://github.com/sindresorhus/ava/raw/master/screenshot-mini-reporter.gif)

* [Tape](https://github.com/substack/tape) - tap-producing test harness for node and browsers

    ```javascript
    var test = require('tape');
    
    test('timing test', function (t) {
        t.plan(2);
    
        t.equal(typeof Date.now, 'function');
        var start = Date.now();
    
        setTimeout(function () {
            t.equal(Date.now() - start, 100);
        }, 100);
    });
    ```
    
* [Test'em](https://github.com/testem/testem) - `npm install testem -g`

* [Unit Testing ui-router Configuration](http://nikas.praninskas.com/angular/2014/09/27/unit-testing-ui-router-configuration/)

###Tests services

* [Testling](https://ci.testling.com/) - run your browser tests on every push
