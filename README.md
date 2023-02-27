<h1>Python Notes</h1>

<table id="customers">
  <tr>
    <td>Number</td>
    <td>Problems</td>
    <td>Answer</td>
  </tr>
  
  <tr>
    <td>1</td>
    <td>What does -1 mean in numpy reshape?</td>
    <td>
      it is an unknown dimension and we want numpy to figure it out.
      <a href="https://stackoverflow.com/questions/18691084/what-does-1-mean-in-numpy-reshape">more details</a>
    </td>
  </tr>
  
  <tr>
    <td>2</td>
    <td>numpy.squeeze()</td>
    <td>
      function is used when we want to remove single-dimensional entries from the shape of an array.
      <a href="https://www.geeksforgeeks.org/numpy-squeeze-in-python/">more details</a>
    </td>
  </tr>
  
  <tr>
    <td>3</td>
    <td>Deep Copy and Shallow Copy</td>
    <td>
      to create “real copies” or “clones” of objects.
      <a href="https://www.geeksforgeeks.org/copy-python-deep-copy-shallow-copy/">more details</a>
    </td>
  </tr>
  
  <tr align="center">
    <td colspan="3">
      Understanding Different Underscores in Python <br>
      youtube link :- 
      <a href="https://www.youtube.com/watch?v=M8-aCSeYzkc">here</a>
    </td>
  </tr>
  
  <tr>
    <td>4</td>
    <td>_</td>
    <td>
      Use for variable name or temo variable
    </td>
  </tr>
  
  <tr>
    <td>5</td>
    <td>_x as variable</td>
    <td>
      use as private varibale in method but acutely not a private variable
    </td>
  </tr>
  
  <tr>
    <td>6</td>
    <td>_x as method</td>
    <td>
      from modul1 *<br>
      _method1()  ->> not accessible <br>
      ------------------------------<br>
      import modul1 <br>
      modul1._method1()  ->> accessible
    </td>
  </tr>
  
  <tr>
    <td>7</td>
    <td>x_</td>
    <td>
      use for reverse python keyword <br>
      example:-<br>
      def_ or class_ 
    </td>
  </tr>
  
  <tr>
    <td>8</td>
    <td>__x</td>
    <td>
      name <a href="https://www.geeksforgeeks.org/name-mangling-in-python/">Mangling</a> when used in class context
    </td>
  </tr>
  
  <tr>
    <td>9</td>
    <td>__x__</td>
    <td>
      special method, Dunder method or Magic method
    </td>
  </tr>
  
  <tr>
    <td>10</td>
    <td>  import sys<br>
          sys.executable
    </td>
    <td>
      How to know which Python is running in Jupyter notebook?
    </td>
  </tr>
  
  <tr>
    <td>11</td>
    <td>np.where(condition)[0]</td>
    <td>
      a = np.random.random([12,])<br>
      print(a)<br>
      b = np.where(0.5 &lt; a)[0] <br>
      in this b where expect from (a < 0.5)''s index value return
    </td>
  </tr>
  
   <tr>
    <td>12</td>
    <td>connect arduino to edge impluse</td>
    <td>
      edge-impulse-daemon<br>
      for connect new project when it's connect to diffrent project <br>
      edge-impulse-daemon --clean
    </td>
  </tr>
  
</table>
