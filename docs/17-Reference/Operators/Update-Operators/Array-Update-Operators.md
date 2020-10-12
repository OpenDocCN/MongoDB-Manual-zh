# [ ](#)数组更新运算符

[]()

在本页面

*   [更新运算符](#update-operators)
*   [更新运算符修饰符](#update-operator-modifiers)

> **注意**
>
> 有关特定运算符的详细信息，包括语法和示例，请单击特定运算符以转到其参考页。

## <span id="update-operators">更新运算符</span>

| 名称                  | 描述                                                         |
| --------------------- | ------------------------------------------------------------ |
| [`$`]()               | 充当占位符，以更新与查询条件匹配的第一个元素。               |
| [`$[]`]()             | 充当占位符，以更新匹配查询条件的文档的数组中的所有元素。     |
| [`$[<identifier>]`]() | 充当占位符，以更新`arrayFilters`与查询条件匹配的文档中所有与条件匹配的元素。 |
| [`$addToSet`]()       | 仅当元素不存在于集合中时才将它们添加到数组中。               |
| [`$pop`]()            | 删除数组的第一项或最后一项。                                 |
| [`$pull`]()           | 删除与指定查询匹配的所有数组元素。                           |
| [`$push`]()           | 将项目添加到数组。                                           |
| [`$pullAll`]()        | 从数组中删除所有匹配的值。                                   |

## <span id="update-operator-modifiers">更新运算符修饰符</span>

| 名称            | 描述                                                       |
| --------------- | ---------------------------------------------------------- |
| [`$each`]()     | 修改`$push`和`$addToSet`运算符以附加多个项以进行数组更新。 |
| [`$position`]() | 修改`$push`运算符以指定要添加元素的数组中的位置。          |
| [`$slice`]()    | 修改`$push`运算符以限制更新数组的大小。                    |
| [`$sort`]()     | 修改`$push`运算符以对存储在数组中的文档重新排序。          |



译者：李冠飞

校对：