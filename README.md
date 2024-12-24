# xupengboo-faker

目录结构：

```text
xupengboo-faker/
├── README.md                # 项目说明文件
├── requirements.txt         # 项目依赖库
├── xupengboo_faker/         # 项目源代码文件夹
│   ├── __init__.py          # 初始化文件
│   ├── generator.py         # 假数据生成主逻辑
│   ├── db_connector.py      # 数据库连接模块
│   ├── faker_config.py      # 配置文件，包含生成假数据的规则和数量
│   └── utils.py             # 辅助工具函数，如数据格式化、批量生成等
├── tests/                   # 单元测试文件夹
│   ├── __init__.py          # 初始化文件
│   ├── test_generator.py    # 假数据生成器单元测试
│   └── test_db_connector.py # 数据库连接器单元测试
├── data/                    # 测试用假数据存放目录
├── scripts/                 # 脚本文件夹，包含命令行工具、批处理等
│   └── generate_data.py     # 用于从数据库字段生成假数据的脚本
├── config/                  # 配置文件目录
│   └── config.json          # 项目配置文件（如数据库连接配置、生成数据规则等）
└── .gitignore               # Git 忽略的文件/文件夹
```

