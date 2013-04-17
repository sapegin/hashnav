# HashNav

Simplest JavaScript hash navigation.


## API

### HashNav.initial(value)

- value {String | undefined}

Get/set default hash. Default hash is a hash that will never visible in URL. It’s a default state of a page.

### HashNav.change(value)

- value {String | Function}

Set/execute change handler. `HashNav.change('foo')` will set page has to `#foo` and execute all handlers added via `HashNav.change(function(hash) { ... })`.


## Example

See `demo.html`.

---

## License

The MIT License, see the included `License.md` file.