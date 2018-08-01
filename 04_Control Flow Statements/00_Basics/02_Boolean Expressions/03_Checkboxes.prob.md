>>Given three variables and their values below, which of the following boolean expressions evaluate to true?
<code>boolean varOne = false;</code>
<code>int varTwo  = 2;</code>
<code>int varThree = 20;</code> <<

[x] <code>varThree &gt; Two</code> {{ selected: Correct because 20 is greater than 2.}, { unselected: Correct because 20 is greater than 2.}}
[ ] <code>varTwo &gt; varThree</code> {{ selected: Incorrect because 2 is not greater than 20.}, { unselected: Incorrect because 2 is not greater than 20.}}
[x] <code>!varOne</code> {{ selected: Correct because the logical complement(!) changes false to true.}, { unselected: Correct because the logical complement(!) changes false to true.}}
[ ] <code>varThree + varTwo &gt; varOne</code> {{ selected: Incorrect because you cannot compare <code>boolean</code> and <code>int</code> values using '&lt;'.}, { unselected: Incorrect because you cannot compare <code>boolean</code> and <code>int</code> values using '&lt;'.}}
[ ] <code>!varTwo</code> {{ selected: Incorrect because you cannot use the logical complement(!) on an <code>int</code> value.}, { unselected: Incorrect because you cannot use the logical complement(!) on an <code>int</code> value.}}

||You cannot compare <code>int</code> values with <code>boolean</code> values using relational operators. ||
