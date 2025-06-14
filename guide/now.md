# 项目进展状况小结

## 项目名称
无人机+鱼眼+视觉识别

## 项目背景与目标
[cite_start]为响应国家低空经济号召并规避复杂空中飞行条例，本项目将无人机飞行高度设定在真高 2-3m。无人机将以斜上方角度稳定跟拍目标，并在识别到特定姿态动作时作出相应反应 [cite: 1]。

**主要使用场景**:
* [cite_start]滑雪跟拍 [cite: 1]
* [cite_start]运动会陪跑抓拍 [cite: 1]
* [cite_start]户外旅行记录 [cite: 1]

**优势**:
* [cite_start]配备鱼眼摄像头可有效扩大取景范围 [cite: 1]
* [cite_start]减少对摄影师（特别是需要特殊技能的场景，如滑雪）的需求 [cite: 1]
* [cite_start]通过姿态识别控制无人机，简化拍摄操作 [cite: 1]
* [cite_start]增强趣味性与科技感 [cite: 1]

**最终研究目标**:
[cite_start]研究基于鱼眼摄像头的无人机手势指令识别与视觉功能优化问题 [cite: 1]。

## 项目流程设计
项目目标拆解为三个小阶段：

* [cite_start]**第一阶段**: 在单人场景内利用直线摄像头实现姿态识别（目前正在推进并已取得成果） [cite: 1]。
* [cite_start]**第二阶段**: 在多人场景内识别出跟随对象，利用直线摄像头实现姿态识别 [cite: 1]。
* [cite_start]**第三阶段**: 在第二阶段基础上，将直线摄像头替换为鱼眼摄像头，并优化畸变和环境干扰的矫正 [cite: 1]。

## 现阶段进展

**现阶段目标**:
[cite_start]实现在单人场景内利用直线摄像头实现姿态识别，分为框定人形进行骨骼点识别和姿势识别两部分 [cite: 1]。

**框定人形**:
* [cite_start]选取特定高度和角度范围的图片作为数据集，训练骨骼点锚定 [cite: 1]。
* [cite_start]使用 YOLO 和 MediaPipe 两种算法，均能对人形进行有效的实时框定（后续选择待定） [cite: 1]。

**姿势识别**:
* [cite_start]已完成部分静态动作的姿势识别录入，使用 YOLO 和 MediaPipe 方法 [cite: 1]。
* [cite_start]动态姿势识别方面，有相关论文使用时空双流法，考虑复刻但尚未实施 [cite: 1]。

**硬件部分**:
* [cite_start]已组装好一台无人机 [cite: 1]。
* [cite_start]已着手编辑无人机运动决策程序，使其在正常飞行模式中能稳定在跟拍对象一定高度和角度的位置，并在执行升降、远近等运动指令后能校准回原有相对位置[cite: 1].

## 经费使用情况和经费安排计划

**经费使用方向**:
1.  [cite_start]无人机相关配件 [cite: 1]
2.  [cite_start]镜头类配件 [cite: 1]
3.  [cite_start]算力平台 [cite: 1]
4.  [cite_start]项目推进所需的学习/办公资源 [cite: 1]

**目前已购买**:
* [cite_start]机架、电机等无人机配件 [cite: 1]
* [cite_start]伸缩手机立架（模仿无人机拍摄图集） [cite: 1]

**下一步主要经费花销用途**:
* [cite_start]算力平台的购买租借 [cite: 1]
* [cite_start]无人机材料补充 [cite: 1]
* [cite_start]不同种类的鱼眼镜头 [cite: 1]

## 项目存在的问题及解决方案

**存在问题**:
* [cite_start]无人机飞行角度的确定 [cite: 1]
* [cite_start]个人特征的选取 [cite: 1]
* [cite_start]图像处理如何实时反馈给无人机 [cite: 1]
* [cite_start]无人机及拍摄环境引入的抖动、噪声 [cite: 1]
* [cite_start]低空在雪地里全身穿戴严实可能无法准确识别，考虑用xx代替 [cite: 1]

## 项目下一步计划

* [cite_start]期末结束后，先着力于第一阶段的完善，即将软件部分的视频图像处理与硬件部分的无人机相结合 [cite: 1]。
* [cite_start]第一阶段成果顺利取得后进入第二阶段 [cite: 1]。
* [cite_start]第二阶段将引入特征识别模块，目前参考论文讨论出特殊颜色衣服等配饰的识别以及面容识别两种思路 [cite: 1]。
* [cite_start]设计手势 [cite: 1]
* [cite_start]实现完整的识别流程（非简化版） [cite: 1]
* [cite_start]鱼眼摄像头替换几何摄像头 [cite: 1]