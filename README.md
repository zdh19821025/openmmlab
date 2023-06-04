# openmmlab-2-mmpose-mmdetection
题目：基于RTMPose的耳朵穴位关键点检测

背景：根据中医的“倒置胎儿”学说，耳朵的穴位反映了人体全身脏器的健康，耳穴按摩可以缓解失眠多梦、内分泌失调等疾病。耳朵面积较小，但穴位密集，涉及耳舟、耳轮、三角窝、耳甲艇、对耳轮等三维轮廓，普通人难以精准定位耳朵穴位。

任务
1.Labelme标注关键点检测数据集（子豪兄已经帮你完成了）
2.划分训练集和测试集（子豪兄已经帮你完成了）
3.Labelme标注转MS COCO格式（子豪兄已经帮你完成了）
4.使用MMDetection算法库，训练RTMDet耳朵目标检测算法，提交测试集评估指标
5.使用MMPose算法库，训练RTMPose耳朵关键点检测算法，提交测试集评估指标
6.用自己耳朵的图像预测，将预测结果发到群里
7.用自己耳朵的视频预测，将预测结果发到群里
需提交的测试集评估指标（不能低于baseline指标的50%）

训练RTMDet耳朵目标检测算法，测试集评估指标
![de](https://github.com/zdh19821025/openmmlab/assets/54253071/e141d987-ff12-4d35-a44b-3ed841e66dd7)
具体见：rtmdet_tiny_ear 20230604_085915.log


训练RTMPose耳朵目标检测算法，测试集评估指标
![rt](https://github.com/zdh19821025/openmmlab/assets/54253071/6f708d3e-b63e-453f-853e-9a07093584db)

具体见：rtmpose-s-ear-20230603_204428.log

自己耳朵的图像预测
![IMG_20230604_211848](https://github.com/zdh19821025/openmmlab/assets/54253071/b01a3ccc-2553-495a-a0b1-1e55b64ff807)
![rtmpose-s-ear](https://github.com/zdh19821025/openmmlab/assets/54253071/af45659b-9276-43b1-9379-7e0e4ce65b1a)

