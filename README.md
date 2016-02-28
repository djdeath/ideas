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

Current UIs :
  * Are the UIs we have today partially a product of the limitations of our
    tools? Do complex layouting models (CSS/GTK+/etc...) shape our UIs and
    bring them back to simpler things because it's too complicated to do
    other things?
