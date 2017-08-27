# stringedToFixed
my answer to accounting.toFixed challenge (beasts challenge 6 @ watchandcode.com)

The solution overcomes the issues of native .toFixed() method (e.g. 0.615.toFixed(2) returns '0.61', when it should actually be '0.62'), as well as issues of accounting.toFixed() method (e.g. accounting.toFixed(1.005, 2) returns '1.00' instead of '1.01');

The solution is mostly focused on using string manipulation to come to a correct rounded result.
