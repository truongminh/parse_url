parse_url
=========

A fast url parser for nodejs based on pattern from Javascript: The Good Parts

Example:

var parser = require('parse_url');

var url = 'www.google.com/hello?q#npm';

var result = parser(url);
