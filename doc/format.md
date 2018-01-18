# Format
## Binary Representation

> ##### `<T>` Type section (16b):
> - 0x00
>   → Type Space
>
> - 0x00
>   → Type
> 
> ##### `<O>` Object section (32b):
> - 0x00-00
>   → Object Space
> 
> - 0x00-00
>   → Object
> 
> ##### `<K>` Key section (16b):
> - 0x00
>   → Region
> 
> - 0x00
>   → Index


### `<T>`

- 0x12
  → Numeric Value

    - 0x34
      → Int (24)

    - 0xf1
      → Float (32 + 16)

- 0xab
  → Alphabetic Character
    
    - 0xe9
      → European


### `<O>`
#### Object Spaces
Maybe, at some point, organizations maintaining character sets can obtain their own object space(s);
so that they can work on their set(s) independently.

- 0x92-0b
  → `probit Labs`
