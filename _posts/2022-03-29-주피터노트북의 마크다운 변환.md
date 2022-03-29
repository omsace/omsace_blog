---
toc: true
layout: post
description: form .ipynb to .md
categories: [blog]
title: 주피터노트북 파일(ipynb)을 마크다운파일(md)로 변환하는 마법과 같은 코드
---

주피터노트북 파일(.ipynb)을 마크다운(.md)파일로 변환하는 마법과 같은 주문



```terminal(MAC)
jupyter nbconvert --to markdown [변환할 노트북 파일명].ipynb
```



해당 폴더에 가서,  터미널을 연 다음 

```
(base) ******@MacbookPro python % jupyter nbconvert --to markdown 00_DevEnviron.ipynb
```



참고 : https://rollingsnowball.tistory.com/129
