# Generative_AI

# Generative AI With Cloud

This repository explores the integration of generative AI models using cloud services, focusing on AWS SageMaker and Falcon-40B for blog content generation.


## 🧠 Project Overview

This project contains:
- **Jupyter notebooks** to deploy and interact with Falcon-40B using AWS SageMaker.
- A **Flask-based application** that enables end-users to generate blogs via a simple web interface.

## 📊 Architecture

![Architecture for Blog Generation](./diagram.png)
### Flow Description

1. **User** interacts with the web UI.
2. **Flask App** processes the input and sends a prompt to AWS SageMaker.
3. **AWS SageMaker** runs the Falcon-40B model to generate content.
4. The response is passed back and displayed to the user.

## 🛠️ Setup Instructions

### Prerequisites

- Python 3.8+
- AWS Account with SageMaker access
- Virtual environment (recommended)

### Clone the Repository

```bash
git clone https://github.com/<your-username>/Generative-AI-With-Cloud.git
cd Generative-AI-With-Cloud


