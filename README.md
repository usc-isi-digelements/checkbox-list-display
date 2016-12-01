# checkbox-list-display

An element used to display checkboxes for filtering (and can also be used along with elastic-checkbox-list-filter).

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
