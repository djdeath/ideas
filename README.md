# ideas

Flapjax : http://www.flapjax-lang.org/
  * split program with part FP function and part dataflow :
    ```
      function someComputation() {
        ....
      }
      
      function moreStuff() {
      }
      
      dataflow plop() {
        var dropEE = $E(elt,"mouseup").mapE(function(mu) {
          return oneE({ drop: elt,
                        left: mu.clientX,
                        top: mu.clientY })});
                      
      }
    ```
