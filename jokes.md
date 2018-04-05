Let me drop on you some String Honesty: 

```haskell
"I doesn't care"
```

Let me drop on you some Concatenated Honesty: 
```haskell
"I" ++ "doesn't" ++ "care"
```

Let me drop on you some Intercalated Honesty: 
```haskell
import qualified Data.List as L
doesntCare :: [String]
doesntCare = ["I", "doesn't", "care"]
L.intercalate " ", doesntCare
```

Let me drop on you some Monadic Honesty: 
(this one needs some work but IO() is the joke)
```haskell

IO() Doesn't Care

```

Let me drop on you some Right Folded Honesty: 

Let me drop on you some Mapped Honesty: 
