# Docs

## kotlin 指南


### 变量

```kotlin
// 可变变量 (有 get/set 方法)
var a: Int = 1

// 不可变变量 (仅有 get 方法)
val b: Int = 1

// 常量 (必须直接赋值)
const val C: Int = 1
```

### 定义枚举

```kotlin
enum class MyEnum(
    val value1: String,
    val value2: String,
) {
    ITEM1("item1-value1", "item1-value2"),
    ITEM2("item2-value1", "item2-value2"),
    ITEM3("item3-value1", "item3-value2")
}
```

### 类型判断

```kotlin
// 是
if (obj is String) {
    ...
}

// 否
if (obj !is String) {
    ...
}
```
