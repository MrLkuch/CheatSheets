# Basics of CSS

### Selectors

- ```*``` general selector
- ```div``` element selector
- ```.``` class selector
- ```#``` id selector

### Combinators

- ```" "``` descendant combinator
- ```>``` child combinator
- ```+``` next sibling combinator
- ```~``` all sibling combinator


### Specificity

`Id` \> `class` \> `elements` \> `*` 

- in line css weight more than any selector
- `!important` pass over any other declaration but still weight less than inline

        You can "calculate" the weight of a selectors by using the table and add 1 on the right column, the highest score means that the selector weight 
        
    Inline/important | ID | Class | Elements  
    --- | --- | --- | --- 
    0 | 0 | 0 | 0


        