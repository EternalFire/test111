---
title: "About"
date: 2021-12-20T04:20:14+08:00
---

# about what ?

what? what! hahaha...

### use hugo

- Get hugo: https://gohugo.io/getting-started/quick-start/
- Find Theme: https://themes.gohugo.io/

1. Create site folder:

```sh
hugo new site BlogDir
```

2. Copy `theme project` to theme directory and modify `site-path/config.toml`:

```toml
baseURL = 'http://example.org/'
languageCode = 'en-us'
title = 'My New Hugo Site'


theme = "hyde" #or other theme name
```

3. Create article

```sh
hugo new "path1/article-name/index.md"
```

4. Test blog

```sh
hugo server
```

5. Build

```sh
# build the site
hugo
```

-----

```
??????????? placeholder ???????????
```

`ya-bai-yo.c`

```c
#include <stdio.h>
#define N 23
#define ASCII '\\'

int main(int argc, char** argv) {
    int i = 0;
    unsigned char space[N+1] = {0};

    for (;;) {
        space[i] = ASCII;
        printf("%s牙白哟!%s x%d\n", space, space, i+1);

        if (i++ == N-1) break;
    }

    return 0;
}
```

`gcc ya-bai-yo.c;./a.out`

```
\牙白哟!\ x1
\\牙白哟!\\ x2
\\\牙白哟!\\\ x3
\\\\牙白哟!\\\\ x4
\\\\\牙白哟!\\\\\ x5
\\\\\\牙白哟!\\\\\\ x6
\\\\\\\牙白哟!\\\\\\\ x7
\\\\\\\\牙白哟!\\\\\\\\ x8
\\\\\\\\\牙白哟!\\\\\\\\\ x9
\\\\\\\\\\牙白哟!\\\\\\\\\\ x10
\\\\\\\\\\\牙白哟!\\\\\\\\\\\ x11
\\\\\\\\\\\\牙白哟!\\\\\\\\\\\\ x12
\\\\\\\\\\\\\牙白哟!\\\\\\\\\\\\\ x13
\\\\\\\\\\\\\\牙白哟!\\\\\\\\\\\\\\ x14
\\\\\\\\\\\\\\\牙白哟!\\\\\\\\\\\\\\\ x15
\\\\\\\\\\\\\\\\牙白哟!\\\\\\\\\\\\\\\\ x16
\\\\\\\\\\\\\\\\\牙白哟!\\\\\\\\\\\\\\\\\ x17
\\\\\\\\\\\\\\\\\\牙白哟!\\\\\\\\\\\\\\\\\\ x18
\\\\\\\\\\\\\\\\\\\牙白哟!\\\\\\\\\\\\\\\\\\\ x19
\\\\\\\\\\\\\\\\\\\\牙白哟!\\\\\\\\\\\\\\\\\\\\ x20
\\\\\\\\\\\\\\\\\\\\\牙白哟!\\\\\\\\\\\\\\\\\\\\\ x21
\\\\\\\\\\\\\\\\\\\\\\牙白哟!\\\\\\\\\\\\\\\\\\\\\\ x22
\\\\\\\\\\\\\\\\\\\\\\\牙白哟!\\\\\\\\\\\\\\\\\\\\\\\ x23
```
