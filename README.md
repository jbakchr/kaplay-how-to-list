# List of "How-to's" for KAPLAY

## Scenes

### Make 'Flash' screen
If you want to make a screen flash then this code could do it:

```javascript
import kaplay from "kaplay";
import "kaplay/global"; // uncomment if you want to use without the k. prefix

kaplay();

scene("main", () => {
  onLoad(() => {
    flash(BLACK, 0.7);
  });
});

go("main");
```
