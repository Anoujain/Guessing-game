```mermaid
graph TD;
    Start-->secret number;
    secret number-->pick from range;
    pick from range-->guess 1;
    guess 1-->wrong
    wrong-->guess 2
    guess 2-->right
    right-->end
```
