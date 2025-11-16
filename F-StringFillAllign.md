```
>>> f'{"text":10}'     # [width]
'text      '
>>> f'{"test":*>10}'   # fill left
'******test'
>>> f'{"test":*<10}'   # fill right
'test******'
>>> f'{"test":*^10}'   # fill center
'***test***'
>>> f'{12345:0>10}'    # fill with numbers
'0000012345'
```
