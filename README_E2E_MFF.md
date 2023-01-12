# E2E_MFF
我们的模型工作基于SwinBERT，论文地址https://openaccess.thecvf.com/content/CVPR2022/papers/Lin_SwinBERT_End-to-End_Transformers_With_Sparse_Attention_for_Video_Captioning_CVPR_2022_paper.pdf。
我们给出了我们的模型代码，主要改进点在于利用最新提出的UniFormerV2视频提取骨干网络代替原文中的Video Swin Transformer，同时采用MBT提出的融合特征策略，将文本特征与视觉特征进行融合，大大减小了模型的复杂性。
MBT论文地址：https://proceedings.neurips.cc//paper/2021/file/76ba9f564ebbc35b1014ac498fafadd0-Paper.pdf。
在我们的代码中，相关改进代码已在提交的源码文件中体现。