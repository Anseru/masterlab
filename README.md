# Masterlab

MasterLab是用php开发的基于项目管理和缺陷跟踪的软件，参考了Jira和Gitlab一些优秀特性发展而来，
主要功能有组织 项目 事项 敏捷Backlog Kanban 工作流 自定义字段等

## 一、第一个里程碑Todo

### 1.1 事项功能点
1. 事项列表的复制，删除            √   
2. 事项列表加入到 Backlog Sprint   √
3. 事项列表，可以在右侧弹出详情
4. 事项子任务                     √    
5. 事项列表的搜索优化
6. 事项详情的操作按钮功能(编辑 复制 自定义字段 关注 状态 解决结果 附件 删除)     √
7. 事项的协作人               √

### 1.2 项目功能点
1. 列表优化显示,参考 https://www.processon.com/diagrams/new#temp-system
2. 项目设置

### 1.3 敏捷功能点
1. Backlog, Sprint, Kanban √
2. UI √
3. backlog和sprint 实现了排序方法

### 1.4 系统
1. 系统中的各种设置项的应用(时间 公告 附件 UI)
2. 备份和恢复 doing
3. 导入                                          推迟
4. 操作日志
5. 错误日志
6. Sql慢查询日志                                 推迟
7. 监听器                                        推迟
8. 网络钩子                                      推迟

### 1.5 服务程序
1. 服务器端
2. worker
3. client
4. 定时执行 推迟

### 1.6 其他
1. 系统中的各种设置项的应用     
2. 权限控制的应用              
3. 用户资料功能点      
4. 首页显示定义和实现
5. 动态的定义和显示
6. 统一的语言(中文)
7. 快捷键
8. 使用帮助和提示

## 二、UI和交互改进

### 全局
1. logo(蝴蝶),包含动画类似gitlab的狐狸脑袋
2. Loading 动画, 无数据插画, 错误的友好提示

### 事项模块
1. 事项弹出层滚动优化
2. 事项弹出层表单行间距调小
3. 事项列表根据选项可直接右侧浮出详情
4. 事项表单上传组件高度调小
5. 事项详情的主题和描述位置调整
6. 事项详情的右侧面板，折叠后显示不一致
7. 修复系统的界面设置不能拖拽

### 敏捷模块
1. Backlog页面左侧菜单UI美化
2. Backlog页面的Sprint子面板增加描述UI
3. Backlog页面


### 项目
1. 项目列表首页优化 
2. 项目表单设计


## 第二次里程碑Todo

1. 跟进不同角色有不通的 UI和交互
2. 首页可以自定义面板
3. 创建事项时,提供描述模板让用户选择


