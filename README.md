# Ruby Getter Method Modification Bug
This repository demonstrates an unexpected behavior in Ruby when attempting to modify an object's attribute using its getter method.  The code in `bug.rb` showcases the issue, while `bugSolution.rb` provides the correct approach.

The bug stems from the misconception that the getter method provides a modifiable reference to the object's attribute.  Instead, it returns a copy of the attribute's value, rendering direct modifications ineffective.

The solution uses a setter method to properly modify the object's internal state.