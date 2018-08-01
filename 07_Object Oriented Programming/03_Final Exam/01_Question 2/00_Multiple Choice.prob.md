>>Consider the following class declarations:</p>
<pre><code class="java language-java">public class Earth {
  // methods not shown
}
</code></pre>
<pre><code class="java language-java">public class Land extends Earth {
  // methods not shown
}
</code></pre>
<pre><code class="java language-java">public class Ocean extends Earth {
  // methods not shown
}
</code></pre>
<pre><code class="java language-java">public class Countries extends Land {
  // methods not shown
}
</code></pre>
<p>Also consider the following variable declarations:
<code>Earth varOne;</code>
<code>Land varTwo;</code>
<code>Ocean varThree;</code>
<code>Countries varFour;</code></p>
<p>Which of the following code segments will not result in a compile time error? <<

( ) A. <code>varTwo = new Ocean();</code> {{A is incorrect because <code>Ocean</code> is a subclass of <code>Earth</code>, so a reference to <code>Ocean</code> cannot be assigned to <code>Land</code> object .}}
( ) B. <code>varThree = new Land();</code> {{B is incorrect because <code>Land</code> is a subclass of <code>Earth</code>, so a reference to <code>Land</code> cannot be assigned to <code>Ocean</code> object.}}
( ) C. <code>varTwo = new Earth();</code> {{C is incorrect because <code>Earth</code> is not a subclass of <code>Land</code>.}}
( ) D. <code>varFour = new Land();</code> {{D is incorrect because <code>Land</code> is not a subclass of <code>Countries</code>.}}
(x) E. <code>varOne = new Land();</code> {{E is correct because <code>Land</code> is a subclass of <code>Earth</code>.}}

||<code>Ocean</code> and <code>Land</code> are subclasses of <code>Earth</code> and cannot be assigned to objects of class <code>Earth</code>. ||
