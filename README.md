# Gen-Prompt-Studio

**版本**: 0.0.1

一个基于Claude Code的Prompt管理与优化工作台，专注于创建、管理和优化高质量的AI提示词。

## 项目概述

本项目是一个专业的prompt管理平台，通过结构化的目录组织和Claude Code工具集，辅助用户创建和优化具体的prompt子工程。每个prompt工程都包含独立的文档、相关资料和测试数据，实现prompt的系统化管理。

## 项目结构

```
gen-prompt-studio/
├── README.md                 # 项目说明文档
├── .claude/                  # Claude Code配置和记忆文件
│   └── memory.md             # AI助手记忆和设定
├── prompts/                  # Prompt工程目录
│   ├── example-project/      # 示例prompt工程
│   │   ├── example-project.md # 主prompt文档
│   │   ├── resources/        # 相关资料
│   │   └── tests/           # 测试数据
│   └── your-project/        # 你的prompt工程
└── tools/                   # 辅助工具和脚本
```

## 核心功能

### 🎯 Prompt工程管理
- **结构化组织**: 每个prompt工程独立目录，包含同名MD文件
- **资源整合**: 集中管理相关资料、测试数据和示例
- **版本控制**: Git友好的文件结构，便于版本管理

### 🔧 Claude Code集成
- **智能辅助**: 内置prompt大师设定，提供专业指导
- **优化流程**: 标准化的prompt创建和优化流程
- **质量评估**: 基于最佳实践的prompt质量标准

### 📋 工作流程
1. **创建工程**: 在`prompts/`目录下创建新的子目录
2. **编写Prompt**: 创建同名MD文件，编写核心prompt内容
3. **组织资料**: 添加相关资源、示例和测试数据
4. **迭代优化**: 使用Claude Code工具进行prompt优化

## 使用指南

### 创建新的Prompt工程

1. 在`prompts/`目录下创建新文件夹：
```bash
mkdir prompts/your-project-name
```

2. 创建主prompt文档：
```bash
touch prompts/your-project-name/your-project-name.md
```

3. 按照标准模板编写prompt内容

### Prompt工程模板

每个prompt工程建议包含：
- **主文档** (`project-name.md`): 核心prompt内容
- **资源目录** (`resources/`): 参考资料、链接等
- **测试目录** (`tests/`): 测试用例和验证数据

## 最佳实践

### Prompt设计原则
- **明确性**: 清晰定义任务和期望输出
- **结构化**: 使用统一的格式和模板
- **可测试**: 提供验证标准和测试用例
- **可维护**: 便于版本控制和团队协作

### 文件命名规范
- 使用小写字母和连字符：`project-name`
- 主文档与目录同名：`project-name/project-name.md`
- 资源文件语义化命名

## 贡献指南

1. Fork项目仓库
2. 创建新的prompt工程
3. 遵循项目结构和命名规范
4. 提交Pull Request

## 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

---

**开始使用**: 查看 [`prompts/`](prompts/) 目录探索现有的prompt工程，或创建你自己的第一个prompt工程！
