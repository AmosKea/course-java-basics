>>Consider the following class declarations:</p>
<pre><code class="java language-java">public class Vehicle
{
  private int varOne;
  public Vehicle(){ 
    varOne = 0; 
  }
  public Vehicle (int paramOne){ 
    varOne = paramOne; 
  }
}
</code></pre>
<pre><code class="java language-java">public class Car extends Vehicle
{
  public Car(){ 
    super(0); 
  }
}
</code></pre>
<p>Which of the following statements will NOT compile? <<

( ) <code>Vehicle vehicleOne = new Vehicle();</code> {{incorrect because <code>Vehicle</code> has a constructor that takes in no parameters.}}
( ) <code>Vehicle vehicleTwo = new Vehicle(5);</code> {{incorrect because <code>Vehicle</code> also has a constructor that takes an integer as a parameter.}}
( ) <code>Vehicle carOne = new Car();</code> {{incorrect because <code>Car</code> is a subclass of <code>Vehicle</code>.}}
(x) <code>Car carTwo = new Car(5);</code> {{correct because the class <code>Car</code> does not have a constructor that takes in an integer as a parameter.}}
( ) <code>Car carThree = new Car();</code> {{incorrect because <code>Car</code> has a constructor that takes in no parameters.}}

||<code>Car</code> is a subclass of <code>Vehicle</code> and is at the bottom of the class hierarchy. ||
