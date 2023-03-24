---
layout: post
title: Spring Boot Native.md
subtitle: Spring Boot Native.md
date: 2021-12-19
author: Yano
catalog: true
tags:
    - Spring
---


# 环境准备

- JDK：17
- GraalVM：[GraalVM Community Edition 21.3.0](https://github.com/graalvm/graalvm-ce-builds/releases/tag/vm-21.3.0)

## 说明

如果是 macOS Catalina 或更高版本，需要先运行一下命令，才能够正常使用 GraalVM：

```c
sudo xattr -r -d com.apple.quarantine path/to/graalvm/folder/
```



# 参考链接

- [https://docs.spring.io/spring-native/docs/current/reference/htmlsingle/#overview](https://docs.spring.io/spring-native/docs/current/reference/htmlsingle/#overview)
- [https://github.com/graalvm/graalvm-ce-builds/releases/tag/vm-21.3.0](https://github.com/graalvm/graalvm-ce-builds/releases/tag/vm-21.3.0)
