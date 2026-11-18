# AI Engineering

A structured learning and development repository focused on **Artificial Intelligence Engineering, Generative AI, Large Language Models (LLMs), AI Agents, and Multimodal AI**.

This repository documents my journey from foundational concepts to building practical, production-oriented AI applications.

## 🎯 Objectives

- Build a strong foundation in AI Engineering.
- Understand Machine Learning and Deep Learning workflows.
- Explore Large Language Models (LLMs) and Generative AI.
- Learn Retrieval-Augmented Generation (RAG).
- Develop AI Agents using LangChain and LangGraph.
- Build AI-powered APIs using FastAPI.
- Explore Multimodal AI applications.
- Develop and document practical AI projects.

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming | Python |
| Deep Learning | PyTorch |
| Data Science | NumPy, Pandas, SciPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Computer Vision | OpenCV |
| LLM Ecosystem | Hugging Face Transformers, Datasets |
| AI Agents | LangChain, LangGraph |
| API Development | FastAPI, Uvicorn, Pydantic |
| Development | VS Code, JupyterLab, Git, GitHub |

## 📁 Repository Structure

```text
AI-Engineering/
│
├── notebooks/       # Experiments and learning notebooks
├── projects/        # Practical AI engineering projects
├── src/             # Reusable Python source code
├── docs/            # Documentation and learning notes
│
├── .gitignore
├── requirements.txt
├── README.md
└── LICENSE
```

## ⚙️ Development Environment

- Operating System: Windows 11
- Python: 3.13
- IDE: Visual Studio Code
- Deep Learning Framework: PyTorch 2.7.1
- CUDA Build: 12.6
- GPU: NVIDIA GeForce MX330 (2GB VRAM)

**Note:** GPU availability does not guarantee that every model will fit into the available VRAM. Large-model experiments may require quantization, CPU offloading, or cloud GPU resources.

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/marufjamil333/AI-Engineering.git
cd AI-Engineering
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

### 3. Activate the Environment (Windows PowerShell)

```powershell
.\.venv\Scripts\Activate.ps1
```

### 4. Install PyTorch with CUDA 12.6

```bash
python -m pip install torch==2.7.1 torchvision==0.22.1 torchaudio==2.7.1 --index-url https://download.pytorch.org/whl/cu126
```

### 5. Install Other Dependencies

```bash
python -m pip install -r requirements.txt
```

### 6. Verify PyTorch and CUDA

```python
import torch

print("PyTorch:", torch.__version__)
print("CUDA Available:", torch.cuda.is_available())

if torch.cuda.is_available():
    print("GPU:", torch.cuda.get_device_name(0))
```

## 📚 Learning Roadmap

- [ ] Python for AI Engineering
- [ ] Mathematics and Data Science Foundations
- [ ] Machine Learning
- [ ] Deep Learning with PyTorch
- [ ] Computer Vision
- [ ] Natural Language Processing
- [ ] Generative AI and LLMs
- [ ] Prompt Engineering
- [ ] Embeddings and Vector Databases
- [ ] Retrieval-Augmented Generation (RAG)
- [ ] AI Agent Development
- [ ] Multimodal AI
- [ ] Model Deployment and MLOps
- [ ] Production-Ready AI Applications

## 📂 Projects

Practical projects and experiments will be documented here as development progresses.

## 📈 Progress

This repository is actively maintained as part of my continuous AI Engineering learning and development journey.

## 👨‍💻 Author

**MD. MARUF JAMIL**

- GitHub: [@marufjamil333](https://github.com/marufjamil333)

---

⭐ If you find this repository useful, feel free to explore and follow my progress.