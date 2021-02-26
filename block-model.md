## Властивості блочного елемента

![](box-model-1.png/733x502)

__PADDING__ - внутришній відступ від контента елемента (синє поле) до його межі (border)  
__BORDER__ - межа елемента, за замовчунням дорівнює 0 та не відображається у браузері  
__MARGIN__ - зовнішній відступ елемента, тобто відштовхує його від навколишніх елементів

### можна вказати різні значення для кожной сторони разом

| property | top    | right    | bottom | left     | 
|:-------- |:------:|:--------:|:------:|:--------:|
| padding  | 0      | 0        | 0      | 0        |
| border   | 0      | 0        | 0      | 0        |
| margin   | 0      | 0        | 0      | 0        |


### або окремо 
| property        | value  | property       | value  | property       | value  |
|:----------------|:------:|:-------------- |:------:|:---------------|:------:|
| padding-top:    | 0      | border-top:    | 0      | margin-top:    | 0      |
| padding-right:  | 0      | border-right:  | 0      | margin-right:  | 0      | 
| padding-bottom: | 0      | border-bottom: | 0      | margin-bottom: | 0      | 
| padding-left:   | 0      | border-left:   | 0      | margin-left:   | 0      | 

### також можна парно
| property | Top & Bottom | Left & Right | 
|:-------- |:------------:|:------------:|
| padding  | 0            | 10px         |
| margin   | 0            | auto         |

### або різні зверху і знизу та однакові з боків 
| property | Top  | Left & Right | Bottom |
|:-------- |:----:|:------------:|:------:|
| padding  | 0    | 10px         | 50px   |
| margin   | 0    | auto         | 50px   |
