## white-space

     | New line  |  Spaces and tabs	 |  Text wrapping | browser
 --- | ---       |  ---------------- | ------------  | ---
normal  |	 Collapse	 |   Collapse	         |   Wrap | 
nowrap  |	 Collapse	 |   Collapse	         |   No wrap | 
pre	   |      Preserve	 |    Preserve	    |   No wrap |
pre-wrap |	 Preserve	 |    Preserve	         |   Wrap | IE8
pre-line |	 Preserve	 |    Collapse	         |   Wrap  | IE8


## word-break

value | desc | Browser 
 --- | --- | --- 
normal  | Use the default line break rule. | 
break-all | Word breaks may be inserted between any character for non-CJK (Chinese/Japanese/Korean) text. |
keep-all | Don't allow word breaks for CJK text.  Non-CJK text behavior is same as normal. | Webkit Buging

## word-wrap

value | desc | Browser 
--- | ---| ---
normal | Indicates that lines may only break at normal word break points. | 
break-word(pre-wrap) | Indicates that normally unbreakable words may be broken at arbitrary points if there are no otherwise acceptable break points in the line. | 
