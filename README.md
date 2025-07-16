# 🪨 Generative AI with Amazon Bedrock – Claude, LLaMA3 & Stable Diffusion

This project demonstrates how to leverage **Amazon Bedrock** to interact with multiple foundation models, including **Anthropic Claude**, **Meta LLaMA3**, and **Stable Diffusion**, using Python and the Bedrock SDK.

---

## 📁 Project Structure

```
AWS-Bedrock/
├── app.py                   # Entry point for running models
├── claude.py                # Claude model integration
├── llama3.py                # LLaMA3 integration via Bedrock
├── stablediffusion.py       # Text-to-Image generation using Bedrock
├── requirements.txt         # Python dependencies
├── test.json                # Sample prompt payload
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🚀 Features

✅ Unified Python interface to interact with:
- **Claude** (Anthropic)
- **LLaMA3** (Meta via Bedrock)
- **Stable Diffusion** (Text-to-Image)

✅ Uses **Amazon Bedrock SDK** for fast inference  
✅ Ready-to-use scripts and sample prompts  
✅ Modular files per model for clean extensibility  

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Aparna-k246/AWS-Bedrock.git
cd AWS-Bedrock
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure AWS CLI

Ensure your Bedrock access is enabled and credentials are set:

```bash
aws configure
```

### 4. Run Model Scripts

Run the app (which internally uses the model of your choice):

```bash
python app.py
```

Or directly run individual model files like:

```bash
python claude.py
python llama3.py
python stablediffusion.py
```

---

## 🔐 Prerequisites

- AWS account with Bedrock enabled  
- IAM role/user with access to invoke models  
  - Permissions: `AmazonBedrockFullAccess`, `BedrockInvokeModel`
- AWS CLI credentials configured locally

---

## 📦 Models Used

| Model            | Task Type         | Provider    |
|------------------|-------------------|-------------|
| Claude           | Chat/QA           | Anthropic   |
| LLaMA3           | Chat/QA           | Meta        |
| Stable Diffusion | Text-to-Image     | Stability AI|

---

## 🧪 Sample Prompt File

`test.json` contains example prompts for direct input testing.

---

## 🧰 Tech Stack

- **Amazon Bedrock**
- **Python (boto3 / bedrock-runtime)**
- **Claude, LLaMA3, Stable Diffusion**

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♀️ Author

**Aparna K**  
🔗 [LinkedIn](https://www.linkedin.com/in/aparna-k-628005167)  
💻 [GitHub](https://github.com/Aparna-k246)

---

## 🔗 Related Repos

- [Generative-AI-with-cloud](https://github.com/Aparna-k246/Generative-AI-with-cloud)  
- [GENAI-Projects-Langchain](https://github.com/Aparna-k246/GENAI-Projects-Langchain)
