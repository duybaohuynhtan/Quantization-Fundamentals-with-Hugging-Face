# Quantization Fundamentals with Hugging Face

[![DeepLearning.AI](https://img.shields.io/badge/DeepLearning.AI-Short%20Course-blue)](https://www.deeplearning.ai/short-courses/quantization-fundamentals-with-hugging-face)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Transformer-yellow)](https://huggingface.co)

This repository contains materials and exercises from the DeepLearning.AI short course "Quantization Fundamentals with Hugging Face", instructed by Younes Belkada and Marc Sun.

## 📚 Course Overview

Generative AI models, especially large language models, often exceed the capabilities of consumer-grade hardware and are expensive to run. This course teaches you how to make these models more efficient, faster, and accessible through quantization techniques, allowing them to run on a wide variety of devices with minimal performance degradation.

## 🎯 What You'll Learn

- How to compress models using the Hugging Face Transformers library and the Quanto library
- Fundamentals of linear quantization, a simple yet effective method for compressing models
- Practical experience quantizing open source multimodal and language models
- Applying "downcasting" quantization with the Transformers library to load models in half their normal size using BFloat16 data type

## 🗂️ Course Structure

This course consists of 7 lessons with 3 code examples:

1. **Introduction**
   - Course overview and importance of model compression

2. **Handling Big Models**
   - Challenges with large-scale AI models
   - Introduction to compression techniques

3. **Data Types and Size**
   - Understanding different numerical precision (FP32, BF16, INT8, etc.)
   - Impact of data types on model size and performance

4. **Loading Models by Data Type**
   - Using Transformers library to load models with different data types
   - Practical exercise on model downcasting

5. **Quantization Theory**
   - Mathematical foundations of quantization
   - Understanding quantization parameters
   - Implementation with the Quanto library

6. **Quantization of LLMs**
   - Overview of Quantization Methods for LLMs

7. **Conclusion**
   - Best practices and future directions

## 💻 Code Examples

The repository includes hands-on code examples:

1. **Downcasting with Transformers**
   - Loading models in BFloat16 format to reduce memory usage

2. **Linear Quantization Implementation**
   - Step-by-step implementation of linear quantization

3. **Quantizing Open Source Models**
   - Practical examples of quantizing various model architectures

## 🚀 Getting Started

### Prerequisites

```bash
# Clone the repository
git clone https://github.com/duybaohuynhtan/Quantization-Fundamentals-with-Hugging-Face.git
cd Quantization-Fundamentals-with-Hugging-Face

# Install required packages
pip install -r requirements.txt
```

### Running the Examples

Each code example is contained in its own Jupyter notebook. To run them:

```bash
jupyter notebook
```

Then navigate to the notebooks directory and open the desired example.

## 📋 Requirements

- Python 3.9.18
- Accelerate 0.26.1
- Ipython 8.18.1
- Ipywidgets 8.1.2
- Numpy 1.23.5
- Pillow 9.4.0
- Quanto 0.0.11
- Torch 2.1.1
- Transformers 4.35.0
- Sentencepiece 0.2.0

## 🔗 Additional Resources

- [DeepLearning.AI Short Course Link](https://www.deeplearning.ai/short-courses/quantization-fundamentals-with-hugging-face)
- [Hugging Face Transformers Documentation](https://huggingface.co/docs/transformers/index)
- [Hugging Face Quanto Library Documentation](https://huggingface.co/docs/transformers/v4.46.2/en/quantization/quanto)

## 👨‍🏫 Instructors

- **Younes Belkada** - Machine Learning Engineer at Hugging Face
- **Marc Sun** - Machine Learning Engineer at Hugging Face

## 🙏 Acknowledgments

Special thanks to DeepLearning.AI and Hugging Face for making this educational content available.