# checkbox-list-display

A Polymer Element showing labeled checkboxes for filtering.

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
