>>Which of the following will print the <code>String</code> "Hello"? <<

( )<code> String varOne = "Hello World!"; System.out.println(varOne.trim()); </code> {{Incorrect because it prints "Hello World!".}}
( )<code> String varOne = " Hello Hello "; System.out.println(varOne.trim()); </code> {{Incorrect because it prints "Hello Hello".}}
( )<code> String varOne = " H e l l o "; System.out.println(varOne.trim()); </code> {{Incorrect because it prints "H e l l o".}}
(x)<code> String varOne = "   Hello   "; System.out.println(varOne.trim()); </code> {{Correct because it prints the <code>String</code> "Hello!" without any spaces at the start and end of the <code>String</code>.}}

||The <code>trim()</code> method only removes the spaces at the start and the end of the <code>String</code>. ||
