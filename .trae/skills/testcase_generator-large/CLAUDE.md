# 测试用例生成器配置（大文档版）

## 基本配置
- output_format: markdown  # 仅支持 markdown
- template: default  # 使用默认模板
- language: zh-CN  # 支持 zh-CN、en-US
- enable_split_by_points: true  # 启用按测试点拆分

## 高级配置
- enable_test_data_generation: true  # 启用智能测试数据生成
- enable_quality_assessment: true  # 启用测试用例质量评估
- parallel_generation: true  # 启用并行生成（多个测试点并行）
- enable_image_parsing: true  # 启用需求文档图片解析
- image_parsing_types:  # 要解析的图片类型
  - interface  # 界面设计图
  - flowchart  # 流程图
  - architecture  # 架构图
  - screenshot  # 示例截图
- keep_temp_files: false  # 是否保留测试点临时文件

## 自定义字段
- custom_fields:
  - 模块
  - 子模块
  - 相关需求
  - 测试环境
