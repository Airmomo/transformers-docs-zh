# transformers-docs-zh【日更｜持续更新中】

Transformers 学习笔记及演示示例，支持 Jupyter Notebook，主要内容来自 🤗 Hugging Face 中关于 Transformers 的教材文档。

本教程在官方文档的基础上修改了部分示例的代码，补充在运行过程中遇到的问题和对应的解决方案，同时也对代码中重要的函数和参数都增加了更为详细的解释。

一起来学习 Transformers 吧！

# 目录

- [安装 🤗 Transformers (windows & macos))](./docs/started/0_installation.ipynb)
- [🤗 Transformers 快速上手](./docs/started/1_quick_tour.ipynb)
- 教程
  - [使用 pipelines 进行推理](./docs/tutorials/2_pipeline.ipynb)
  - [使用 AutoClass 加载预训练实例](./docs/tutorials/3_autoclass.ipynb)
  - [预处理数据](./docs/tutorials/4_preprocess_data.ipynb)
  - [微调预训练模型](./docs/tutorials/5_fine_tune_pretrained_model.ipynb)
  - [使用脚本进行训练](./docs/tutorials/6_train_with_script.ipynb)
  - [使用 🤗 Accelerate 进行分布式训练](./docs/tutorials/7_distributed_training_with_accelerate.ipynb)
  - [使用 🤗 PEFT 加载和训练 adapters](./docs/tutorials/8_load_adapters_with_PEFT.ipynb)
  - [如何分享模型](./docs/tutorials/9_share_model.ipynb)
  - [🤗 Transformers Agents 快速上手](./docs/tutorials/10_agents.ipynb)
  - [使用 LLMs 进行生成](./docs/tutorials/11_generation_with_llms.ipynb)
  - [ Agents and Tools 介绍和指南](./docs/tutorials/12_agents_and_tools.ipynb)
- 任务指南
  - 自然语言处理
    - [文本分类](./docs/guide/13_text_classification.ipynb)
    - [标记分类（实体分类）](./docs/guide/14_token_classification.ipynb)
    - [因果语言模型（CLM）](./docs/guide/28_causal_language_modeling.ipynb)
    - [遮蔽语言模型（MLM）](./docs/guide/29_masked_language_modeling.ipynb)
    - [文本翻译](./docs/guide/30_translation.ipynb)
    - [文本摘要（文本总结）](./docs/guide/31_summarization.ipynb)
    - [问题解答任务(问答任务)](./docs/guide/33_question_answering.ipynb)
    - [多项选择任务](./docs/guide/32_mutil_choice.ipynb)
  - 音频处理
    - [音频分类](./docs/guide/34_audio_classification.ipynb)
    - [自动语音识别 (ASR, Automatic speech recognition)](./docs/guide/16_automatic_speech_recognition.ipynb)
  - 计算机视觉
    - [图像分类](./docs/guide/25_image_classification.ipynb)
    - [图像分割](./docs/guide/26_image_segmentation.ipynb.ipynb)
    - [视频分类](./docs/guide/35_video_classification.ipynb)
    - [目标检测](./docs/guide/36_object_detection.ipynb)
    - [零样本目标检测](./docs/guide/37_Zero-shot_object_detection.ipynb)
    - [零样本图像分类](./docs/guide/38_Zero-shot_image_classification.ipynb)
    - [单目深度估计(单图像深度估计)](./docs/guide/39_monocular_depth_estimation.ipynb)
    - [以图生图（图像增强、图像修复等图像处理任务）](./docs/guide/27_image_to_image.ipynb)
    - [图像特征提取](./docs/guide/40_Image_Feature_Extraction.ipynb)
    - [图像掩码生成](./docs/guide/41_Mask_Generation.ipynb)
    - [关键点检测(图像特征点检测)](./docs/guide/42_Keypoint_Detection.ipynb)
    - [知识蒸馏在计算机视觉中的应用](./docs/guide/43_Knowledge_Distillation_for_Computer_Vision.ipynb)
  - 多模态
    - [图像描述生成](./docs/guide/22_image_captioning.ipynb)
    - [文本转语音 (TTS, Text-to-speech)](./docs/guide/17_text_to_speech.ipynb)
    - [图像-视觉多模态理解模型 (VLM with image-input, Image-text-to-text)](./docs/guide/18_image_text_to_text.ipynb)
    - [视频-视觉多模态理解模型 (VLM with video-input, Video-text-to-text)](./docs/guide/21_video_text_to_text.ipynb.ipynb)
    - [文档问答 (DQA, Document Question Answering)](./docs/guide/20_document_question_answering.ipynb)
    - [视觉问答 (VQA, Visual Question Answering)](./docs/guide/19_visual_question_answering.ipynb)
  - 生成策略
    - [（自定义）文本生成策略](./docs/guide/24_text_generation_strategies.ipynb.ipynb)
    - [使用缓存优化生成的最佳实践](./docs/guide/23_best_practices_for_generation_with_cache.ipynb)
  - 提示技术
    - [LLM 提示指南](./docs/guide/15_llm_prompt_guide.ipynb)
