# object-assign for browsers

[a-x-/object-assign](//github.com/a-x-/object-assign) is fork (for browsers) of the [sindresorhus/object-assign](//github.com/sindresorhus/object-assign) — ES6 Object.assign() ponyfill for Node.JS ( CommonJS module style)

## ES6 and polyfills explanation...

> ES6 [`Object.assign()`](http://www.2ality.com/2014/01/object-assign.html) ponyfill

> Ponyfill: A polyfill that doesn't overwrite the native method

## Install
1. Download 
2. Include in the document


## Usage

```js

Object.assign({foo: 0}, {bar: 1});
//=> {foo: 0, bar: 1}

// multiple sources
Object.assign({foo: 0}, {bar: 1}, {baz: 3});
//=> {foo: 0, bar: 1, baz: 2}

// ignores null and undefined sources
Object.assign({foo: 0}, null, {bar: 1}, undefined);
//=> {foo: 0, bar: 1, baz: 2}
```


## API

### Object.assign(target, source, [source, ...])

Assigns enumerable own properties of `source` objects to the `target` object and returns the `target` object. 
Additional `source` objects will overwrite previous ones.

Returns modified target.

## Resources

- [ES6 spec - Object.assign](https://people.mozilla.org/~jorendorff/es6-draft.html#sec-object.assign)
- [paulmillr/es6-shim](https://github.com/paulmillr/es6-shim) — full ES6 shims set

## License

MIT
