Util
====

[![Build Status](https://travis-ci.org/clippings/util.png?branch=master)](https://travis-ci.org/clippings/util)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/clippings/util/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/clippings/util/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/clippings/util/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/clippings/util/?branch=master)
[![Latest Stable Version](https://poser.pugx.org/clippings/util/v/stable.png)](https://packagist.org/packages/clippings/util)

General purpose helper methods

Array Helpers
-------------

- __toAssoc__ - convert a random array to a strict structure - every entry has a string key
- __invoke__ - if the array holds only objects, aggregate the results of a method call on all the objects
- __pluckProperty__ - aggregate the value of a property of each object in the array
- __pluckUniqueProperty__ - aggregate the value of a property of each object in the array, only unique values
- __pluck__ - aggregate all the values of entries with a given key
- __flatten__ - flatten all the values of nested arrays
- __groupBy__ - group by result of callback

SplObjectStorage Helpers
------------------------
- __combineArrays__ - combine two arrays into an SplObjectStorage, based on a callback
- __groupCombineArrays__ - combine two arrays into an SplObjectStorage, based on a callback, multiple entries are combined into an array
- __addNested__ - used by groupCombineArrays
- __index__ - convert an SplObjectStorage to an array, for a given property value of the objects as a key
- __invoke__ - aggregate the results of a method call on all the objects
- __filter__ - similar to array_filter, but for SplObjectStorage
- __toArray__ - convert SplObjectStorage into an array
- __groupBy__ - change SplObjectStorage where the "key" object is the result of a callback, and all the other objects are grouped by them

## License

Copyright (c) 2014, Clippings Ltd. Developed by Ivan Kerin

Under BSD-3-Clause license, read LICENSE file.
