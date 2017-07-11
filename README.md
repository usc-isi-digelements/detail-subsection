# detail-subsection

A Polymer Element showing a detail subsection of a given field.

### Example
```html
<detail-subsection
  entity-id="[[offer.id]]"
  classification-manager="[[classificationManager]]"
  icon-style-class-property="styleClass"
  extractions="[[offer.extraction]]">
</detail-subsection>
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

