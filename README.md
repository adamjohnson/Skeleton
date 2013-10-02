# Mobile First Skeleton Framework

A mobile first version of Dave Gamache's Skeleton. Starting at mobile portrait and moving up to 1200px desktop sizes.

## How to implement the Grid System

Nothing has changed here from Dave Gamache's original implementation. Just wrap your page with a `.container` class, then add things like `five` `columns`, et all, to your markup. Eg:

    <div class="container">
  
      <!-- Give column value in word form (one, two..., sixteen) -->
      <div class="sixteen columns">
        <h1>Full Width Column</h1>
      </div> <!-- /.sixteen.columns -->
      
      <!-- You can push over by columns -->
      <div class="five columns offset-by-one"></div>

    </div> <!-- /.container -->

See the provided `index.html` file for a more complete example and to play around.

### Credits
 
 * More information about Skeleton: http://getskeleton.com
 * Originally created by Dave Gamache: http://davegamache.com
 * Made mobile first by Adam Johnson: http://adamjohnsondesign.com
 * Normalize.css v2 by Nicolas Gallagher: http://necolas.github.io/normalize.css/
 * More base styles taken from the HTML5 Boilerplate: https://github.com/h5bp/html5-boilerplate