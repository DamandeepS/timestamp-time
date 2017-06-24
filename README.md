# \<timestamp-time\>

use timestamp to display time


`timestamp-time`
use timestamp to display date/time

usage `<timestamp-time></timestamp-time>`

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="timestamp-time.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<timestamp-time timestamp="1498312215357"></timestamp-time>
```
## Attributes

| Attribute |Datatype| Description |
|-----------|--------|-------------|
| utc _(optional)_ | `Boolean` | `true` if you want to get UTC date/time, else Local date/time |
| type _(optional)_ | `String` | `date` or `time`, if we want Date or Time, else Full String|
|timestamp *Required*| `Number`| Timestamp you want to convert, Or else it'll take current time |
