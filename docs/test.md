``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

Lorem ipsum dolor sit amet, (1) consectetur adipiscing elit.
{ .annotate }

1.  :man_raising_hand: I'm an annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be expressed in Markdown.

> [!info] Test
> Do obsidian callouts auto convert to admonitions?


!!! note "title"
	Test test test



\<div class="grid cards" markdown>

\- :fontawesome-brands-html5: __HTML__ for content and structure
\- :fontawesome-brands-js: __JavaScript__ for interactivity
\- :fontawesome-brands-css3: __CSS__ for text running out of boxes
\- :fontawesome-brands-internet-explorer: __Internet Explorer__ ... huh?

\</div>

