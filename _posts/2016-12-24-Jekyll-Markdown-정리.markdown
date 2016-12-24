---
layout: post
title:  "Jekyll Markdown 정리"
date:   2016-12-24 19:04:00 +0900
categories: jekyll update
---

[Reference](https://kramdown.gettalong.org/syntax.html#emphasis)

# Links

```
[바로가기](https://inhochoi.github.io)
```

[바로가기](https://inhochoi.github.io)

# Paragraphs

```
This⋅para⋅line⋅starts⋅at⋅the⋅first⋅column.⋅However,
⋅⋅⋅⋅⋅⋅the⋅following⋅lines⋅can⋅be⋅indented⋅any⋅number⋅of⋅spaces/tabs.
⋅⋅⋅The⋅para⋅continues⋅here.

⋅⋅This⋅is⋅another⋅paragraph,⋅not⋅connected⋅to⋅the⋅above⋅one.⋅But⋅⋅
with⋅a⋅hard⋅line⋅break.⋅\\
And⋅another⋅one.
```

This⋅para⋅line⋅starts⋅at⋅the⋅first⋅column.⋅However,
⋅⋅⋅⋅⋅⋅the⋅following⋅lines⋅can⋅be⋅indented⋅any⋅number⋅of⋅spaces/tabs.
⋅⋅⋅The⋅para⋅continues⋅here.

⋅⋅This⋅is⋅another⋅paragraph,⋅not⋅connected⋅to⋅the⋅above⋅one.⋅But⋅⋅
with⋅a⋅hard⋅line⋅break.⋅\\
And⋅another⋅one.

# Header

```
First level header
==================

Second level header
------

   Other first level header
=
```

First level header
==================

Second level header
------

   Other first level header
=

# Emphasis

```
*some text*

_some text_

**some text**

__some text__
```

*some text*

_some text_

**some text**

__some text__

# Code Blocks

```
~~~
#include<stdio.h>

void main(){
  printf("Hello World");
}
~~~
{: .language-c}
```
~~~
#include<stdio.h>

void main(){
  printf("Hello World");
}
~~~
{: .language-c}

#List

```
* kram
+ down
- now

1. kram
2. down
3. now
```

* kram
+ down
- now

1. kram
2. down
3. now
