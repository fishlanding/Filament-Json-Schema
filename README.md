# Filament-Json-Schema

为 [Filament Mod](https://modrinth.com/mod/filament) 提供 JSON Schema 支持，帮助开发者更轻松地编写和验证 Filament 数据包。

## 功能

- 提供完整的 JSON Schema 定义，支持 Filament 的各种配置类型
- 在支持 JSON Schema 的编辑器中实现自动补全和验证
- 减少配置错误，提高开发效率

## 包含的 Schema 文件

- `block.json` - 自定义方块配置
- `decoration.json` - 自定义装饰配置
- `entity.json` - 自定义实体配置
- `item-groups.json` - 物品组配置
- `item.json` - 自定义物品配置

## 使用说明

1. 将本仓库添加到你的 Filament 数据包根目录（即 `pack.mcmeta` 所在目录）中
2. 编辑数据包时，编辑器将自动提供智能提示和验证

## 项目结构

```
├─.vscode
│      settings.json
│
└─filament-schema
    │  block.json
    │  decoration.json
    │  entity.json
    │  item-groups.json
    │  item.json
    │
    └─other
            component.json
            text_component.json
```

欢迎贡献和改进这些 Schema 定义！
