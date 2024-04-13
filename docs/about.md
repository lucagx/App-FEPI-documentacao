## Sobre
 
Testes


```python
def fn():
    pass
```


**Strong**  or __Strong__ (Command-B)  
*Emphasize* : `*AAAAA*` or _Emphasize_ [^emphasize] (Command-I)

The background color is `#ffffff` for light mode and `#000000` for dark mode.
aaa

==test123==


<div class="mermaid">
  erDiagram
  CUSTOMER ||--o{ ORDER : places
  ORDER ||--|{ LINE-ITEM : contains
  LINE-ITEM {
    string name
    int pricePerUnit
  }
  CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
</div>

<div class="mermaid">
  xychart-beta
    title "Sales Revenue"
    x-axis [jan, feb, mar, apr, may, jun, jul, aug, sep, oct, nov, dec]
    y-axis "Revenue (in $)" 4000 --> 11000
    bar [5000, 6000, 7500, 8200, 9500, 10500, 11000, 10200, 9200, 8500, 7000, 6000]
    line [5000, 6000, 7500, 8200, 9500, 10500, 11000, 10200, 9200, 8500, 7000, 6000]
</div>

<div style="background-color: white" class="mermaid">
    sequenceDiagram
        Alice->>Bob: Hello Bob, how are you ?
        Bob->>Alice: Fine, thank you. And you?
        create participant Carl
        Alice->>Carl: Hi Carl!
        create actor D as Donald
        Carl->>D: Hi!
        destroy Carl
        Alice-xCarl: We are too many
        destroy Bob
        Bob->>Alice: I agree
</div>
