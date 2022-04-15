# Various gotcha's

## h1 inside a section is rendered as h2
> In HTML5, an &lt;h1&gt; inside sections nested n levels deep is treated like &lt;h(n+1)&gt; instead. So an &lt;h1&gt; inside a single &lt;section&gt; is semantically &gt; equivalent to an &lt;h2&gt; and is rendered as such. In this context "sections" means any of &lt;section&gt;, &lt;article&gt;, &lt;nav&gt;, or &lt;aside&gt;.

https://stackoverflow.com/a/6854147
https://html.spec.whatwg.org/multipage/sections.html#headings-and-sections

