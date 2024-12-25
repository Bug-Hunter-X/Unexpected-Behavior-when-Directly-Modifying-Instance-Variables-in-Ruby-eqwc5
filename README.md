# Unexpected Behavior when Directly Modifying Instance Variables in Ruby

This repository demonstrates a common error in Ruby programming: directly modifying instance variables using `instance_variable_set`. While this might seem convenient, it can introduce subtle bugs and makes the code harder to maintain.  The `bug.rb` file shows the issue. The solution, in `bugSolution.rb`, demonstrates a more robust approach using accessors.