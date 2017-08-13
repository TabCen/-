#一、Swift基础


## 1、类型别名

```swift
typealias <#type name#> = <#type expression#>

//将NUMType定义同Int一样属于Int类型
typealias NUMType = Int

```

## 2、if条件判断

```

if <#condition#> {
    <#code#>
}

//if 条件判断语句{
//		(逻辑内容)
//}
		
``` 

## 3、元组

```
let http404error = (404,"Not Found")
//http404error 的类型是（Int,String）

```

- 元组分解	
	- 可声明元组内部值
	- 亦可通过下标的方式
		
	

```
1、声明元组内部值
let (code,statusStr) = http404error

print("状态码为\(code)")
print("失败信息为\(statusStr)")

//可用_来代替不想取的值，

let (_,statusStr) = http404error
print("失败信息为\(statusStr)")


2、通过下标的方式

let message = http404error.1


```

## 4、可选类型





























