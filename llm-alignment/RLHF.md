








RLHF





收集人类偏好数据的质量和数量决定了 RLHF 系统性能的上限。RLHF 系统需要两种人类偏好数据：人工生成的文本和对模型输出的偏好标签。生成高质量回答需要雇佣兼职人员 (而不能依赖产品用户和众包) 。
另一方面，训练 RM 需要的奖励标签规模大概是 50k 左右，所以并不那么昂贵 (当然远超了学术实验室的预算) 。
另一个挑战来自标注者的偏见。几个人类标注者可能有不同意见，导致了训练数据存在一些潜在差异。