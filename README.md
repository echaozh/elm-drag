elm-drag
========

Drag'n'drop support for Elm. Exposed API:

```
Drag.lastPosition : Time.Time -> Signal (Maybe (Int, Int))
Drag.start        : Signal (Maybe (Int, Int))
Drag.drop         : Signal (Maybe ((Int, Int), (Int, Int)))
```
