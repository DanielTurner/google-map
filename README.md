google-map
==========
You came here probably because Google Maps doesn't work with your Polymer 3 build.
This one functions for now, not efficiently but consider it a temporary solution.
Use until Google releases a lit-html version.
[`See the progress here`](https://github.com/justinfagnani/google-map/tree/lit-element)

Forked from the fork that forked this originally...
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/GoogleWebComponents/google-map)

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.min.js"></script>
    <link rel="import" href="google-map.html">
    <style>
      google-map {
        height: 300px;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<google-map fit-to-markers api-key="AIzaSyD3E1D9b-Z7ekrT3tbhl_dy8DCXuIuDDRc">
  <google-map-marker latitude="37.78" longitude="-122.4" draggable="true"></google-map-marker>
</google-map>
```

Breaking changes:
 * Markers added to `<google-map>` must now specify `slot="markers"` to be added correctly.
