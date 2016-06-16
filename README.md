##&lt;elastic-aggregation&gt;

`elastic-aggregation` is an element which creates an elastic aggregatgion object
and captures the aggregation returned from elastic-search


Example:
```html
    <elastic-aggregation
      ejs-agg-snippet="ejs.TermsAggregation('city_agg').field('city').size(10)"
      all-results="[[esResults]]"
      agg-results="{{cityAggResults}}"
      aggregations="{{esAggregations}}"
      >
    </elastic-aggregation>
```



