# status-text

A Polymer Element showing status text as loading, error, empty (no data), or blank (no status).  Initially created to show the status of database queries.  Uses the amount of data, an error message, and whether the data is loading.

### Example
```html
<status-text
  count="[[queryResults.length]]"
  error="[[queryError]]"
  loading="[[queryLoading]]">
</status-text>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

