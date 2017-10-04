# prompted
A React component interface to LocalStorage

## Example
This is a no frills example of using `prompted` for a user name.
```js
  <LocalStorageProvider
    item="name"
    render={(name = "Guest", update) => (
      <h1>Hi {name}!</h1>
      <input
        onChange={e => update(e.target.value)}
        type="text"
      />
    )}
  />
```

## Installation
### Node
```npm i prompted --save```
or
```yarn add prompted```

### Browser
Exports `Prompted` on `window`.

```js
<script
  crossorigin
  src="https://unpkg.com/prompted"
></script>
```

## Code Quality
[Learn React](#https://learnreact.com) open source, is intended for education.
Source should be singularly focus and readable above all.

## License
MIT License
Copyright &copy; Michael Chan 2017
