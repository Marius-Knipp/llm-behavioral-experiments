# LLMs in Behavioral Research: A Dashboard for Experimentation

## Introduction

This project was developed during the Winter Term 2023/24 as part of the Data Science Project course at the University of Tübingen by Benjamin Herzberger and myself. It explores the fascinating intersection of behavioral economics and artificial intelligence by leveraging Large Language Models (LLMs) to replicate well-established human decision-making patterns.

The revolutionary potential of this approach lies in its efficiency and cost-effectiveness. If LLMs consistently exhibit human-like preferences and biases, such as Loss Aversion, the Decoy Effect, and the Sunk Cost Fallacy, they could become powerful tools for simulating human behavior in behavioral research and market analysis. This would allow researchers to conduct complex experiments quickly and affordably, minimizing the need for large-scale human trials while still generating reliable insights. Additionally, researchers could use LLMs to identify previously unknown biases and phenomena, which could then be validated through more expensive studies involving human participants, paving the way for groundbreaking discoveries in behavioral science.

The project presents a series of experiments aimed at comparing LLM outputs with traditional behavioral economics findings, highlighting whether these models reflect the same tendencies observed in humans. A key innovation of this project is the dashboard, which enables users to design and run their own experiments with LLMs, making this tool versatile and user-driven.

---

## Dashboard Overview and Features

The dashboard for this project is live [here](https://llm-experiments.onrender.com/). Please note that it may take up to 2 minutes for the website to load upon initial access. Designed as an interactive platform, the dashboard empowers users to explore behavioral economics through experiments with Large Language Models (LLMs).

### Important Note:
To run experiments, users must provide their own API keys for OpenAI and Replicate. These keys enable access to the LLMs but incur usage costs based on the number of queries or tokens processed. 

### Key Features:
1. **Experiment Customization**: Users can select from predefined experiments—such as Prospect Theory, Loss Aversion, and the Decoy Effect—or create their own by modifying parameters like prompts, temperature, and iterations.
2. **Parameter Configuration**: Easily adjust the number of iterations, temperature settings, and model selection (e.g., GPT-3.5, GPT-4, or LLaMA-2) to tailor the experiment to your goals.
3. **Interactive Visualization**: Results are visualized in real-time using graphs and tables, making it straightforward to analyze outcomes.
4. **Multiple LLM Support**: The dashboard supports GPT-3.5, GPT-4, and LLaMA-2, enabling comparative experimentation.
5. **CSV Export**: Download raw data in CSV format for detailed offline analysis or documentation.
6. **Built-in Chatbot**: A chatbot feature allows quick interactions with LLMs, enabling users to experiment with prompts and observe how model responses vary based on temperature and token settings.

---

## How It Works:

1. **Select or Create an Experiment**: Choose from predefined experiments or design a custom one tailored to your research objectives.
2. **Configure Parameters**: Define settings such as iterations, temperature, and model selection.
3. **Run the Experiment**: Execute the experiment and gather responses from the selected LLM.
4. **Analyze the Results**: Visualize outcomes directly in the dashboard or download the data for deeper analysis.

---

## Technologies Used

This project utilizes a modern tech stack to ensure scalability, interactivity, and ease of use:
- **Backend**: Python with Dash for managing app logic and interactivity.
- **Frontend**: Dash components and Plotly for creating dynamic, user-friendly visualizations.
- **Data Processing**: Pandas and NumPy for handling and analyzing experimental data.
- **LLMs**: OpenAI (GPT-3.5/4) and Replicate API (LLaMA-2) for generating responses in experiments.
- **Hosting**: Render.com for deployment and accessibility.

---

## Results and Insights

The experiments conducted as part of this project reveal intriguing insights into the behavior of Large Language Models (LLMs). Preliminary findings indicate that LLMs exhibit some of the same biases observed in humans, such as Loss Aversion and the Decoy Effect. This suggests that LLMs might serve as effective surrogates for human participants in behavioral economics experiments. If these findings hold consistently, using LLMs could significantly reduce the time and costs associated with traditional research methods.

Beyond their implications for research, these insights open doors to broader applications. For instance, in **market research**, LLMs could be asked which type of advertising or promotional offer would most likely nudge them to purchase a product, simulating consumer preferences at scale. In **educational contexts**, educators could leverage LLMs to test which teaching methods, explanations, or materials are perceived as more understandable or engaging, helping to design more effective learning strategies. The ability of LLMs to mirror human-like biases and reasoning highlights their potential as a practical and efficient resource in fields requiring behavioral analysis, enabling innovations in how we approach problem-solving and decision-making in various domains.

It is important to note that the models used in this project, GPT-4 and LLaMA-2, represented the state-of-the-art during the Winter Term 2023/24. While newer, more advanced models may outperform them, the results remain valuable as they demonstrate the capabilities of LLMs during this period and their potential as tools for behavioral economics research.

---

## References
- Brand, James and Israeli, Ayelet and Ngwe, Donald, Using GPT for Market Research (March 21, 2023). Harvard Business School Marketing Unit Working Paper No. 23-062, Available at SSRN: [https://ssrn.com/abstract=4395751](https://ssrn.com/abstract=4395751)
- Dominguez-Olmedo, Ricardo et al. “Questioning the Survey Responses of Large Language Models.” ArXiv abs/2306.07951 (2023): n. pag.
- Gati Aher, Rosa I. Arriaga, and Adam Tauman Kalai. 2023. Using large language models to simulate multiple humans and replicate human subject studies. In Proceedings of the 40th International Conference on Machine Learning (ICML'23), Vol. 202. JMLR.org, Article 17, 337–371.
- Hagendorff, Thilo et al. “Human-like intuitive behavior and reasoning biases emerged in large language models but disappeared in ChatGPT.” Nature computational science vol. 3,10 (2023): 833-838. doi:10.1038/s43588-023-00527-x
- John J. Horton, 2023. "Large Language Models as Simulated Economic Agents: What Can We Learn from Homo Silicus?," NBER Working Papers 31122, National Bureau of Economic Research, Inc.
