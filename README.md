# Ample

A simple C style runtime that allows for safe evaluation of user-input expressions.

# Usage

    var Ample = require('ample');

    var ample = new Ample();

    ample.evaluate("1"); // -> 1

    ample.evaluate("1 + 1"); // -> 2

    ample.evaluate("1 / 2"); // -> 0.5