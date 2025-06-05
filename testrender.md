<!--<div id="my-element2">
  ...or this element will be modified by JavaScript.
</div>
 <div id="myDiv2"></div> -->

<script>
    const element2 = document.getElementById("my-element30");
    var data = [{
        x:  [1, 2, 3],
        y:  [2, 1, 3],
        type:  'bar'
    }];
    Plotly.newPlot(element2, data);

  const element = document.getElementById("my-element");
  const element3 = document.getElementById("my-element2");
  element.textContent = "Modified by JavaScript";


  
  element3.textContent = "Modified by JavaScript! - 2nd attempt";
</script>

test test test test t