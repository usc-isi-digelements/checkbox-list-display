# checkbox-list-display

An element used to display checkboxes for filtering (used along with elastic-checkbox-list-filter).

Example:
```html
    <checkbox-list-display
      buckets="[[countryResult.aggregations.countryAgg.countryAgg.buckets]]"
      facet-selection="{{countryFacetSelection}}"
      facets="{{countryFacets}}"
      category="Country">
    </checkbox-list-display>
```

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install