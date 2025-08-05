---
layout: post
author: Abhinav Saxena
tags: [overview, moonwalk]
---

Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit. Pellentesque vel lacinia neque. Praesent nulla quam, ullamcorper in sollicitudin ac, molestie sed justo. Cras aliquam, sapien id consectetur accumsan, augue magna faucibus ex, ut ultricies turpis tortor vel ante. In at rutrum tellus.

# Sample heading 1
## Sample heading 2
### Sample heading 3
#### Sample heading 4
##### Sample heading 5
###### Sample heading 6

Mauris viverra dictum ultricies. Vestibulum quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Etiam id nisl ut lorem gravida euismod.

## Lists

Unordered:

- Fusce non velit cursus ligula mattis convallis vel at metus[^2].
- Sed pharetra tellus massa, non elementum eros vulputate non.
- Suspendisse potenti.

Ordered:

1. Quisque arcu felis, laoreet vel accumsan sit amet, fermentum at nunc.
2. Sed massa quam, auctor in eros quis, porttitor tincidunt orci.
3. Nulla convallis id sapien ornare viverra.
4. Nam a est eget ligula pellentesque posuere.

## Blockquote

The following is a blockquote:

> Suspendisse tempus dolor nec risus sodales posuere. Proin dui dui, mollis a consectetur molestie, lobortis vitae tellus.

## Thematic breaks (<hr>)

Mauris viverra dictum ultricies[^3]. Vestibulum quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Etiam id nisl ut lorem gravida euismod. **You can put some text inside the horizontal rule like so.**

---
{: data-content="hr with text"}

Mauris viverra dictum ultricies. Vestibulum quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Etiam id nisl ut lorem gravida euismod. **Or you can just have an clean horizontal rule.**

---

Mauris viverra dictum ultricies. Vestibulum quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Etiam id nisl ut lorem gravida euismod. Or you can just have an clean horizontal rule.

## Code

Now some code:

```python
# --- Syntax Highlighting Test Snippet ---

import os
import re

@my_decorator
class SyntaxTest(BaseClass):
    """
    This is a docstring, which is a multi-line string.
    It should be highlighted correctly. Escape sequences like \n work here.
    """
    
    # Class-level variables and constants
    SOME_CONSTANT = 1_234_567.89
    IS_ACTIVE = True
    HEX_VALUE = 0xDEADBEEF
    
    def __init__(self, name: str, value: int = 42):
        # f-string and raw string examples
        self.name = f"Test-{name}"
        self.path = r'C:\Users\Test\Path'
        self.value = value
    
    async def run_operation(self, factor=1.5e-2):
        """An async function with type hints and default arguments."""
        # Keywords like 'if', 'else', 'for', 'in', 'try', 'except'
        if self.value > 0 and self.name is not None:
            try:
                # A for loop and list comprehension
                results = [i ** 2 for i in range(self.value)]
                
                # A regular expression
                regex = re.compile(r'(\d{3,5})\s+(test|final)?')
                match = regex.search("12345 test")
                
                print(f"Match found: {match}")
                
            except ValueError as e:
                # Handle a specific exception
                print(f"Error: {e}")
        else:
            # A pass statement
            pass
            
# Standalone function with a lambda
def get_operator(op_type):
    if op_type == "add":
        return lambda x, y: x + y
    return None
```

And here is some `inline code`!

## Tables

Now a table:

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## Images

![theme logo](http://www.abhinavsaxena.com/images/abhinav.jpeg)

This is an image[^4]

---
{: data-content="footnotes"}

[^1]: this is a footnote. You should reach here if you click on the corresponding superscript number.
[^2]: hey there, don't forget to read all the footnotes!
[^3]: this is another footnote.
[^4]: this is a very very long footnote to test if a very very long footnote brings some problems or not; hope that there are no problems but you know sometimes problems arise from nowhere.
