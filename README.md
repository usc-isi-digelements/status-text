# status-text

A polymer web component that shows status text.  Initially created to show the status of database queries.  Uses the amount of data, an error message, and whether the data is loading.

Example:
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
