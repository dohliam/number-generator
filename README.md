# Number generator - Generate an arbitrarily-long list of sequential numbers

It is sometimes necessary to generate aribtrarily-long lists of sequential numbers outside of a context (programming, spreadsheet editing, the command-line, etc.) where it would normally be trivial to do so. This comes up often enough that I was motivated to make this generator, so perhaps it might also be useful for others.

A command-line is not always available, but a web browser usually is. And it is much easier to jump to a new URL than to fire up an entire spreadsheet program or write a throwaway script just to generate some numbers.

The other thing is that there could be quite a lot of numbers needed in a given list. If it were 10 or 20 it might of course be easier to just enter them manually, but if we're talking about 100 or more it no longer seems reasonable to do by hand.

Also, numbers may frequently need to be padded with zeros to a certain number of digits. This is absurdly simple, so long as it's not being done manually. But opening up a spreadsheet all the time for something so simple also seems wrong. This simple number generator solves that.

## Usage

Enter a number in the `from` and `to` fields and click on __Generate Numbers__.

Optionally, add a number of digits to pad with zeros in the `Zero padding` field and generate numbers as normal.

If the zero padding field is set to `0` or `1`, no padding will be used. If it is set to `2`, then the sequence from 1-10 will look like this: `01 02 03 04 05 06 07 08 09 10`. If it is set to `3` the same sequence will look like this: `001 002 003 004 005 006 007 008 009 010`.

The numbers in the list can be separated by any string of characters (including newlines `\n`, tabs `\t`, commas, spaces, etc.) by adjusting the value in the `Field separator` box.

## To implement

~~* Arbitrary field separators~~
* Prepend to list

## See also

"Number generator" is part of the [**tiny tools**](https://dohliam.github.io/tiny_tools/) series, a collection of small mobile-friendly JavaScript tools for performing common tasks in the browser.

Other tools for working with columns of data that might also be of interest:

* [Elements of _a_ in _b_](https://github.com/dohliam/elements)
* [Sort columns](https://github.com/dohliam/sort-columns)
* [Sum columns](https://github.com/dohliam/sum-columns)
* [Compare columns](https://github.com/dohliam/compare-columns)

## Credits

* [milligram](https://github.com/milligram/milligram) CSS by @cjpatoilo, prototyped using [dropin-minimal-css](https://github.com/dohliam/dropin-minimal-css)
* [github-corners](https://github.com/tholman/github-corners) by @tholman

## License

MIT.
