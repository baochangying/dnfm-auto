## 基于yolov5模型实现布万家自动化搬砖

### 已实现功能
– 识别图像中人物、怪物、材料、门等物体
– 自动寻路、过图
- 固定人物攻击逻辑
- 根据怪物数量攻击逻辑
- 识别狮子头房间
- 开局使用buff技能
- 拾取材料等掉落物（粉装未进行训练）
- 自动再次挑战
- 

#### 待优化
1. 寻路箭头在脚底时，移动方向有误
2. 大量怪物贴脸围殴时，需要尝试触发后撤步脱离
3. 效率较低，需要配置人物固定房间、固定打法
4. 模型识别不够精确，训练集数量过少

##### 本项目不参与商业用途，仅供学习参考
##### 如果有好的建议和方案，欢迎找我讨论，绿色泡泡：yosaaqwq
