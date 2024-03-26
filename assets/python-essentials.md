## Intro
- high-level, interpreted, strongly-typed (no implicit data type conversion) language;
- breakpoints using raise SystemExit:

```
age = 17
if age <= 18:
raise SystemExit('You must be older than 18!')
```
- syntax/parsing errors are the most common errors;
- logic errors are the most difficult to fix: using wrong var name, incorrectly indenting code, wrong number types or out-by-one error;

## None

- None is a Python keyword used to define when there is no value at all;
- not the same as 0 or the boolean False or an empty string; those do have values of 0, False and “” respectively;
- None is a signal object used in Python to signify ‘empty’ or ‘no value here’;
- there are no empty variables in Python; therefore if you have a variable, it has a value, and if you want to remove that value, you can reassign the variable to None;
- None has the data type of NoneType, which is a built-in data type just like int or float;
- you cannot create new instances of None or assign it a value as semantically; it only represents the absence of a value;
- None is immutable;
- None is used in Python functions if you do not specify an explicit return statement will return None; this is a way Python guarantees that a function will always return something which makes for simplified programming;
- None can be used if you have a variable with a value and you wish to remove it;
- None is a little like the concept of <i>undefined</i> in JavaScript. They are both objects that can be used to signal when something has an absence of a value.
- also None as part of a comparison;
- None has no value so you cannot use the equality operators like == but you can use the identity operators like is not.