# SCAMP-ASSESSMENT


Function to output a Fibonacci Sequence of a given number. 



<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Fibonacci Series</title>
</head>
<body>

</body>
</html>


var fibonacci_series = function (n) 
{
  if (n===1) 
  {
    return [0, 1];
  } 
  else 
  {
    var s = fibonacci_series(n - 1);
    s.push(s[s.length - 1] + s[s.length - 2]);
    return s;
  }
};

 console.log(fibonacci_series(8));
 
