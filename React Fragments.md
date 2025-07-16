<h1>🧩 What is a React Fragment?</h1>
<h3>In React, a Fragment lets you group multiple elements without adding extra nodes to the DOM (like unnecessary div tags).</h3>
<br>
<h1 class="heading">✅ Why Use `<React.Fragment>` or `<> </>`?</h1>

<p ><li>Avoids extra HTML wrappers.</li><p>
<p><li>Helps in cleaner DOM structure.</li></h3>
<p><li>Good for semantic HTML and styling (avoids layout issues caused by div nesting).</li></p>
<br>
<h1>Why cant we return multipal elements at the same time?</h1>

<p><li>as after JSX is compiled it is converted to normal javascript object, you cant return multipal javscriipt object at the same time.</li><p>
<p><li>return ( jsx(...) ),( jsx(...) );</li></p>
 