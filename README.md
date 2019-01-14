
## setup & install
```
% sudo pacman -S rlwrap clojure
```

## run
###repl
```
% clj --main cljs.main --compile hello-clojurescript.core --repl
```

###'prod'
```
% clj -m cljs.main --optimizations advanced -c hello-clojurescript.core
% clj -m cljs.main --serve
```



## reload from repl
```
cljs.user=>  (require '[hello-clojurescript.core :as hello] :reload)
```
