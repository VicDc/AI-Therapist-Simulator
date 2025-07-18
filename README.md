# AI-Therapist-Simulator
# Mental D0C 🧠: An AI Simulator for Psychotherapy Research
https://huggingface.co/uruz7/Mental_Healthcare_LLM/tree/main
[![Hugging Face Model](https://img.shields.io/badge/🤗%20Hugging%20Face-Model-blue)]([https://huggingface.co/your-username/your-model-name](https://huggingface.co/uruz7/Mental_Healthcare_LLM))
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

Welcome to **Mental D0C**, a project that's less about replacing your therapist and more about exploring what makes them tick! We've created a Large Language Model (LLM) that simulates conversations between a psychotherapist and a patient. Think of it as a digital sandbox for research, prototyping, and maybe figuring out why we all have commitment issues with our gym memberships.

This project is built for researchers, developers, and anyone curious about the intersection of AI and psychology. It provides a controlled, ethical environment to study conversational dynamics, test therapeutic approaches, and build the next generation of empathetic AI.

<!-- INSERT YOUR SCREENSHOT HERE -->
![Project Screenshot](https://github.com/VicDc/AI-Therapist-Simulator/blob/f9093e74dc63c15fb6be682271eeaa0951962ad3/mental%20D0c/mentalD0c_1.png)
*(A sample conversation generated by the model)*

## 🎯 Project Goal

The main goal is to provide a robust, open-source tool for simulating therapeutic dialogues. We want to empower researchers to explore psychological dynamics and help developers prototype conversational agents with a touch more humanity. We’re not building a digital Freud (he’d probably have a lot to say about our code), but we are creating a space for safe and insightful experimentation.

## ✨ Key Highlights

* 🧠 **Realistic Dialogue:** Fine-tuned on a large dataset of therapeutic conversations to generate dialogues that are empathetic and context-aware.
* ⚡️ **Blazing Fast & Efficient:** Built with **Unsloth**, enabling you to load and fine-tune massive models like Qwen3 up to 2x faster and with significantly less memory.
* 🔧 **Highly Customizable:** Easily modify the prompts and fine-tuning process in the provided Jupyter Notebook to steer the model's therapeutic style. Want a more Socratic or a humanistic approach? Go for it!
* 🔬 **Research-Ready:** Perfect for academic or independent research in computational psychology, NLP, and human-computer interaction.

## 🚀 Getting Started

Ready to start the session? Follow these steps to get the project up and running.

### Technical Requirements

* **GPU:** A CUDA-enabled GPU is highly recommended. A NVIDIA T4 (16GB VRAM) is a good starting point, but for faster fine-tuning, an A100 (40GB VRAM) is ideal.
* **Python:** Python 3.9+
* **Libraries:** All required Python libraries are listed in the Jupyter Notebook and can be installed via `pip`. Key libraries include `torch`, `unsloth`, `transformers`, and `datasets`.

### Setup and Usage

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/Mental-D0C.git](https://github.com/your-username/Mental-D0C.git)
    cd Mental-D0C
    ```

2.  **Set up the Environment:**
    It's recommended to use a virtual environment.
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install Dependencies:**
    The simplest way is to run the first cell of the included Jupyter Notebook (`OK_Fine_tuning_di_un_LLM_Terapeuta_con_Qwen3.ipynb`), which handles the installation of all necessary packages.

4.  **Run the Notebook:**
    Launch Jupyter and open the notebook:
    ```bash
    jupyter notebook OK_Fine_tuning_di_un_LLM_Terapeuta_con_Qwen3.ipynb
    ```
    Follow the steps inside the notebook to load the dataset, fine-tune the model, and run inference to simulate conversations.

## ⚠️ Ethical Disclaimer

> ### **Important: This is a Research Simulation**
>
> Welcome! Before you begin, please understand that you are interacting with an **AI model, not a human therapist.**
>
> This tool is designed for **educational and research purposes only**. It can make mistakes, generate incorrect information, and does not have the understanding or qualifications to provide real therapeutic advice.
>
> ### **This AI is NOT a substitute for professional mental health care.**
>
> If you are seeking help, please contact a qualified healthcare provider or a crisis hotline. Your well-being is what truly matters.

## 🤝 Contributing

We'd love your help in making this project even better! Whether you're fixing a bug, improving the documentation, or proposing a new feature, your contributions are welcome.

To contribute:
1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-amazing-idea`).
3.  Make your changes and commit them (`git commit -m 'Add some amazing feature'`).
4.  Push to the branch (`git push origin feature/your-amazing-idea`).
5.  Open a Pull Request.

## 📚 References

This project stands on the shoulders of giants. A huge thank you to:
* The **Qwen Team** for their powerful family of models.
* The creators of **Unsloth** for making high-performance LLM fine-tuning accessible to everyone.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details. You're free to use, modify, and distribute it, but please remember the ethical disclaimer!
