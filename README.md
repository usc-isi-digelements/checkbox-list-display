# checkbox-list-display

A Polymer Element showing labeled checkboxes for filtering.  Can be used with the [elastic-checkbox-list-filter](https://github.com/DigElements/elastic-checkbox-list-filter) element to create elasticsearch filters.

### Example
```html
<checkbox-list-display
  buckets="[[countryResult.aggregations.countryAgg.countryAgg.buckets]]"
  facet-selection="{{countryFacetSelection}}"
  facets="{{countryFacets}}"
  category="Country">
</checkbox-list-display>
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

