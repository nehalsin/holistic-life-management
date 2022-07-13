```
android: (+ 1 2 3)
-> 6
android: (setq x 6)
-> 6
android: (+ (+ 1 x) x)
-> 13
android: (setq x 1 y 2)
-> 2
android: (+ x (+ x y) y)
-> 6
android: (- 80 55)
-> 25
android: (- 55 80)
-> -25
android: (* 80 60)
-> 4800
android: (* 40 (* x y) (+ x y))
-> 240
android: (+ (* x x) (* y y))
-> 5
android: (setq z 3)
-> 3
android: (+ (* x x x) (* y y y) (* z z z))
-> 36
android: (* (+ x y) (+ x y))
-> 9
android: (+ (* x x) (* y y) (* 2 x y))
-> 9
```