# hugo-ruby
Hugo Component for the HTML tag `<ruby>`.

More information about `<ruby>` from MDN: [<ruby>: The Ruby Annotation element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ruby)

Not to be confused with [the Ruby programming language](https://www.ruby-lang.org/en/).

# Syntax
```
{{< ruby rb="明日" rt="あした">}}
{{< ruby 明日 あした>}}
```

Both generate the following HTML: 
```html
<ruby>
    明日
    <rp>(</rp>
    <rt>あした</rt>
    <rp>)</rp>
</ruby>
```
