+++
title = 'Markdown 渲染测试'
date = '2026-10-07'
draft = false
tags = ['Hugo', 'Markdown']
categories = ['Blog']
+++

# Markdown 渲染测试

这是一个用于测试 Hugo Markdown 渲染效果的页面。

## 1. 文本

这是普通文本。

这里有 **粗体**、*斜体*、`inline code`。

## 2. 列表

- C++
- Linux
- CMake
- OpenGL
- Vulkan

有序列表：

1. 编译
2. 链接
3. 运行

## 3. 引用

> Hugo 使用 Goldmark 处理 Markdown。

## 4. C++代码

```cpp
#include <iostream>

int main()
{
    std::cout << "Hello Hugo!" << std::endl;
    return 0;
}
```

## 5. CMake代码

```cmake
cmake_minimum_required(VERSION 3.20)

project(Hello)

add_executable(Hello main.cpp)
```

## 6. 表格

| API | 平台 | 类型 |
|---|---|---|
| OpenGL | 跨平台 | Graphics API |
| Vulkan | 跨平台 | Graphics API |
| DirectX | Windows | Graphics API |

## 7. 链接

这是一个[GitHub链接](https://github.com/)。

## 8. 图片

以后可以这样插入图片：

```markdown
![图片说明](/images/example.png)
```