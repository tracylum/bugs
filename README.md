# Footnote HTML output from cmark-gfm

<p>This is some text!<sup class="footnote-ref"><a href="#fn-1" id="fnref-1" data-footnote-ref>1</a></sup>. Other text.<sup class="footnote-ref"><a href="#fn-footnote" id="fnref-footnote" data-footnote-ref>2</a></sup>.</p>
<p>Here's a thing<sup class="footnote-ref"><a href="#fn-other-note" id="fnref-other-note" data-footnote-ref>3</a></sup>.</p>
<p>And another thing<sup class="footnote-ref"><a href="#fn-codeblock-note" id="fnref-codeblock-note" data-footnote-ref>4</a></sup>.</p>
<p>This doesn't have a referent[^nope].</p>
<p>Hi!</p>
<section class="footnotes" data-footnotes>
<ol>
<li id="fn-1">
<p>Some <em>bolded</em> footnote definition. <a href="#fnref-1" class="footnote-backref" data-footnote-backref aria-label="Back to content">↩</a></p>
</li>
<li id="fn-footnote">
<blockquote>
<p>Blockquotes can be in a footnote.</p>
</blockquote>
<pre><code>as well as code blocks
</code></pre>
<p>or, naturally, simple paragraphs. <a href="#fnref-footnote" class="footnote-backref" data-footnote-backref aria-label="Back to content">↩</a></p>
</li>
<li id="fn-other-note">
<p>no code block here (spaces are stripped away) <a href="#fnref-other-note" class="footnote-backref" data-footnote-backref aria-label="Back to content">↩</a></p>
</li>
<li id="fn-codeblock-note">
<pre><code>this is now a code block (8 spaces indentation)
</code></pre>
<a href="#fnref-codeblock-note" class="footnote-backref" data-footnote-backref aria-label="Back to content">↩</a>
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
