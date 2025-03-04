# Kaggle_Toxic-Comment-Classification-Challenge

## 竞赛链接
[Jigsaw Toxic Comment Classification Challenge](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/overview)

## 项目目标
本方案旨在复现该竞赛的 金牌方案，以此练习机器学习在多标签二分类问题中的应用，加深对文本分类任务的理解和实践能力。
原方案链接：[Classifying multi-label comments (0.9741 lb)]([https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/overview](https://www.kaggle.com/code/rhodiumbeng/classifying-multi-label-comments-0-9741-lb?scriptVersionId=2284297])
## 数据集描述
你会得到大量维基百科评论，这些评论已经由人工评级者针对有毒行为进行了标注。毒性类型如下：
- `toxic`：一般性的有毒评论
- `severe_toxic`：严重的有毒评论
- `obscene`：淫秽、下流的评论
- `threat`：包含威胁性质的评论
- `insult`：带有侮辱性的评论
- `identity_hate`：基于身份的仇恨言论评论

你需要构建一个模型，为每条评论预测上述每种毒性类型出现的概率。

### 文件说明
- **`train.csv`**：训练集文件，其中包含评论内容以及对应的二进制标签，用于模型训练。
- **`test.csv`**：测试集文件，你要为这里面的评论预测毒性概率。需要注意的是，为了防止人工标注，测试集中有部分评论不会用于最终评分。
- **`sample_submission.csv`**：一个示例提交文件，展示了正确的提交格式，方便你参考。
- **`test_labels.csv`**：测试数据的标签文件。其中值为 -1 表示该条评论不会用于评分。（注意：此文件是在竞赛结束后添加的）

## 数据使用许可
数据集遵循 CC0 许可，而评论的底层文本受维基百科的 CC - SA - 3.0 许可约束。
