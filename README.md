# Footnote HTML output from cmark-gfm

<p>This is some text!<sup class="footnote-ref"><a href="#fn1" id="fnref1" data-footnote-ref aria-describedby="footnote-label">1</a></sup>. Other text.<sup class="footnote-ref"><a href="#fn2" id="fnref2" data-footnote-ref aria-describedby="footnote-label">2</a></sup>.</p>
<p>Here's a thing<sup class="footnote-ref"><a href="#fn3" id="fnref3" data-footnote-ref aria-describedby="footnote-label">3</a></sup>.</p>
<p>And another thing<sup class="footnote-ref"><a href="#fn4" id="fnref4" data-footnote-ref aria-describedby="footnote-label">4</a></sup>.</p>
<p>This doesn't have a referent[^nope].</p>
<p>Hi!</p>
<section class="footnotes" data-footnotes>
<ol>
<li id="fn1">
<p>Some <em>bolded</em> footnote definition. <a href="#fnref1" class="footnote-backref" aria-label="Back to content" data-footnote-backref>↩</a></p>
</li>
<li id="fn2">
<blockquote>
<p>Blockquotes can be in a footnote.</p>
</blockquote>
<pre><code>as well as code blocks
</code></pre>
<p>or, naturally, simple paragraphs. <a href="#fnref2" class="footnote-backref" aria-label="Back to content" data-footnote-backref>↩</a></p>
</li>
<li id="fn3">
<p>no code block here (spaces are stripped away) <a href="#fnref3" class="footnote-backref" aria-label="Back to content" data-footnote-backref>↩</a></p>
</li>
<li id="fn4">
<pre><code>this is now a code block (8 spaces indentation)
</code></pre>
<a href="#fnref4" class="footnote-backref" aria-label="Back to content" data-footnote-backref>↩</a>
</li>
</ol>
</section>







__ 
# Markdown Footnote
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.
