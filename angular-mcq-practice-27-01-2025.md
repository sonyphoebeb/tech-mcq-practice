<h1>📘 Angular MCQ Practice — 27 Jan 2025</h1>

<p><strong>Source:</strong> W3Schools Angular Quiz<br>
<strong>Your Score:</strong> 13 / 25 (52%)</p>

<p>This file stores my answers, correct answers, and learning notes for revision.</p>

<h2>Quiz Summary</h2>

<table>
  <thead>
    <tr>
      <th>Metric</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Total Questions</td><td>25</td></tr>
    <tr><td>Correct Answers</td><td>13</td></tr>
    <tr><td>Score</td><td>52%</td></tr>
    <tr><td>Attempt</td><td>1st Attempt</td></tr>
  </tbody>
</table>

<h2>📚 Detailed Questions & Answers</h2>

<hr>

<h3>1. What is Angular?</h3>
<strong>✅ Correct Answer:</strong> A framework for building client applications</p>

<hr>

<h3>2. Which function bootstraps a standalone Angular application?</h3>
<p><strong>❌ My Answer:</strong> bootstrapModule()<br>
<strong>✅ Correct Answer:</strong> bootstrapApplication()</p>
<pre>📝 Standalone apps do not use modules.</pre>

<hr>

<h3>3. Which decorator defines a component?</h3>
<p><strong>✅ Correct Answer:</strong> @Component</p>

<hr>

<h3>4. How do you mark a component as standalone?</h3>
<p><strong>✅ Correct Answer:</strong> standalone: true</p>

<hr>

<h3>5. Which template syntax shows a value as text?</h3>
<p><strong>✅ Correct Answer:</strong> {{ value }}</p>

<hr>

<h3>6. Which syntax listens to a click event?</h3>
<p><strong>✅ Correct Answer:</strong> (click)</p>

<hr>

<h3>7. Which syntax sets a DOM property?</h3>
<p><strong>✅ Correct Answer:</strong> [prop]</p>

<hr>

<h3>8. Which is the two-way binding syntax for forms?</h3>
<p><strong>✅ Correct Answer:</strong> [(ngModel)]</p>

<hr>

<h3>9. Which module is required for [(ngModel)]?</h3>
<p><strong>❌ My Answer:</strong> CommonModule<br>
<strong>✅ Correct Answer:</strong> FormsModule</p>

<hr>

<h3>10. Which modern template syntax iterates over a list?</h3>
<p><strong>❌ My Answer:</strong> *ngFor<br>
<strong>✅ Correct Answer:</strong> @for</p>
<pre>📝 Angular 17+ introduces new control flow syntax.</pre>

<hr>

<h3>11. How do you provide a stable identity for items in @for?</h3>
<p><strong>❌ My Answer:</strong> Use index as id<br>
<strong>✅ Correct Answer:</strong> Use track it.id</p>

<hr>

<h3>12. Which element is used for content projection?</h3>
<p><strong>❌ My Answer:</strong> &lt;router-outlet&gt;<br>
<strong>✅ Correct Answer:</strong> &lt;ng-content&gt;</p>

<hr>

<h3>13. Which decorator marks an input property?</h3>
<p><strong>✅ Your Answer:</strong> @Input<br>
<strong>✅ Correct Answer:</strong> @Input</p>

<hr>

<h3>14. Which decorator is used to emit events to a parent component?</h3>
<p><strong>❌ My Answer:</strong> @Event<br>
<strong>✅ Correct Answer:</strong> @Output</p>

<hr>

<h3>15. Which class is commonly used with @Output to emit events?</h3>
<p><strong>✅ Your Answer:</strong> EventEmitter&lt;T&gt;<br>
<strong>✅ Correct Answer:</strong> EventEmitter&lt;T&gt;</p>

<hr>

<h3>16. Which pipe subscribes to Observables and unsubscribes automatically?</h3>
<p><strong>✅ Your Answer:</strong> async<br>
<strong>✅ Correct Answer:</strong> async</p>

<hr>

<h3>17. When does the async pipe unsubscribe from an Observable?</h3>
<p><strong>❌ My Answer:</strong> When you call destroy()<br>
<strong>✅ Correct Answer:</strong> When the view is destroyed</p>

<hr>

<h3>18. Which Angular service is used for HTTP requests?</h3>
<p><strong>✅ Your Answer:</strong> HttpClient<br>
<strong>✅ Correct Answer:</strong> HttpClient</p>

<hr>

<h3>19. In standalone apps, which function enables HttpClient?</h3>
<p><strong>❌ My Answer:</strong> HttpClientModule<br>
<strong>✅ Correct Answer:</strong> provideHttpClient()</p>

<hr>

<h3>20. How do you set an attribute when no corresponding property exists?</h3>
<p><strong>❌ My Answer:</strong> [class.*]<br>
<strong>✅ Correct Answer:</strong> [attr.*]</p>

<hr>

<h3>21. What is the modern control flow syntax for conditionals in templates?</h3>
<p><strong>❌ My Answer:</strong> *ngIf<br>
<strong>✅ Correct Answer:</strong> @if</p>

<hr>

<h3>22. Which symbol introduces a local template reference?</h3>
<p><strong>✅ Your Answer:</strong> #var<br>
<strong>✅ Correct Answer:</strong> #var</p>

<hr>

<h3>23. Where does the root component render in index.html by default?</h3>
<p><strong>✅ Your Answer:</strong> &lt;app-root&gt;<br>
<strong>✅ Correct Answer:</strong> &lt;app-root&gt;</p>

<hr>

<h3>24. Which package exports bootstrapApplication?</h3>
<p><strong>❌ My Answer:</strong> @angular/router<br>
<strong>✅ Correct Answer:</strong> @angular/platform-browser</p>

<hr>

<h3>25. To use *ngIf and *ngFor in a standalone component, import:</h3>
<p><strong>❌ My Answer:</strong> FormsModule<br>
<strong>✅ Correct Answer:</strong> CommonModule</p>

