
# setup & install
```
% sudo pacman -S rlwrap clojure
```

# run & reload
## repl
```
% clj --main cljs.main --compile hello-clojurescript.core --repl
```

## reload from repl
```
cljs.user=>  (require '[hello-clojurescript.core :as hello] :reload)
```

## 'prod'
```
% clj -m cljs.main --optimizations advanced -c hello-clojurescript.core
% clj -m cljs.main --serve
```



