# project introduction

This library is an example library, the main purpose is to record the file directory structure of the library, no actual code.

```
project_name/
├── src/                 # 源代码
│   ├── core/            # 核心代码
│   ├── platform/        # 平台相关代码
│   └── utils/           # 工具类代码
├── include/             # 头文件: .h  .hpp
│   ├── project_name/    # 库公共接口
│   └── detail/          # 内部实现
│   └── depend_name/     # 依赖库头文件
├── build/               # 构建文件
│   └── temp             # 构建临时文件目录
│   └── CMakeLists.txt   # 构建配置
│   └── build.sh         # 构建脚本
│   └── makefile         # 构建脚本
│   └── makefile         # 其他CI自动化构建脚本
├── test/                # 测试代码
│   ├── unit/            # 单元测试
│   └── integration/     # 集成测试
│   └── mock/            # 模拟测试
├── docs/                # 文档
│   ├── api/             # API 文档
│   └── guides/          # 使用指南
│	└── examples/        # 示例代码
├── tools/               # 工具和脚本
│   └── build.sh         # 构建脚本
├── third_party/         # 第三方依赖
│   ├── boost/           # Boost 库
│   └── protobuf/        # Protocol Buffers
├── lib /                # 库文件
│   ├── project_name.a   # 静态库
│   └── project_name.so  # 动态库
├── bin /                # 可执行文件目录
│   └── project_name     # 可执行文件
├── LICENSE              # 开源许可证
├── README.md            # 项目简介
└── VERSION              # 项目版本
```

