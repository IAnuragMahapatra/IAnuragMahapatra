```python
from mcp.server.fastmcp import FastMCP

mcp: FastMCP = FastMCP("User Memory Server")


@mcp.tool()
def user_profile() -> str:
    """
    Returns everything known about Anurag Mahapatra for context-aware agents.
    """
    return """
    Name: Anurag Mahapatra
    Email: anurag2005om@gmail.com
    Phone: 9937736153
    Location: Sambalpur, Odisha, India
    Languages: English, Hindi, Odia (Read/Write/Speak)

    Education:
    - College: VSSUT (Veer Surendra Sai University of Technology)
    - Degree: B.Tech in Computer Science & Engineering (CSE)
    - CGPA: 8.9
    - Current Status: Between 4th and 5th semester (summer break)

    Current Goals:
    - Master MLOps and agentic systems during the summer
    - Build end-to-end ML pipelines (data ➝ model ➝ serve ➝ deploy)
    - Develop intelligent agents using MCP

    Technical Skills:
    - Languages: Python, Java, C++, C, HTML, CSS, JavaScript
    - Frameworks & Libraries: TensorFlow, Keras, LangChain, OpenCV, React (basic), Pygame
    - MLOps & DevOps Tools: Docker, Git, Linux, MLflow, DVC, FastAPI, Kubernetes (Minikube)
    - Core Concepts: OOP, DSA (CLRS), Computer Networks, Computer Organization, DBMS, OS, Compiler Design
    - AI/ML Extras: Prompt Engineering (Lee Boonstra), Accelerated Computing (CUDA, Numba)

    Certifications:
    - Fundamentals of Accelerated Computing with CUDA Python (NVIDIA)
    - IBM SkillsBuild: Data Analysis Bootcamp

    Projects:
    - RAG System (Retrieval-Augmented Generation)
    - End-to-End MLOps Pipeline (in progress)
    - Modular LangChain Agent for Research Reasoning (in progress)
    - Fine-tuned VGG16 for Cats vs. Dogs Classification
    - Single Address ISA Simulator
    - Flappy Bird AI (NEAT algorithm)
    - Pygame + OpenCV Space Invaders
    - Minimax Tic Tac Toe AI
    - Virtual Marker with MediaPipe + TouchDesigner
    - Normal Distribution Simulator
    - Fractal Viewer (Java)
    - Telegram File Sharing Bot (QR-based)
    - API-integrated AI chatbots and utilities

    LinkedIn: linkedin.com/in/anurag-mahapatra-7336892b0

    Ideal Roles:
    - Freelance AI Developer – open to contract work in ML, MLOps, or agent development
    - MLOps Engineer (Entry-Level) – building and maintaining ML pipelines
    - AI Infrastructure Engineer (Junior) – working on systems that support AI/ML
    - Agentic AI Developer (Junior) – building tool-using autonomous agents
    """


if __name__ == "__main__":
    mcp.run()
```
