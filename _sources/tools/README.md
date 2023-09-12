## Създаване на речник с българските думи

```text
aspell --lang bg dump master | aspell --lang bg expand | tr ' ' '\n' > bulgarian.dic
```