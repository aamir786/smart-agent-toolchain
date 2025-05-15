# Self-Evolving Smart Agents for Intelligent Task Automation

This repository hosts the reference implementation and supporting materials for  
**“Self-Evolving Smart Agents for Intelligent Task Automation: A Framework for Tool Construction and Chaining”**  
—a PhD dissertation under review—featuring three core modules:

1. **Agent-π**: Multimodal interaction recorder and symbolic tool constructor  
2. **ContextMate**: Context-aware tool-chaining framework for multi-application workflows  
3. **CAD-Copilot**: Self-evolving automation in CAD design via intrinsic and extrinsic feedback  

> **Note:** Module code and data will be populated here following our upcoming journal and conference publications.

## Repository Structure

```

smart-agent-toolchain/
├── agent\_pi/             # Agent-π: Tool construction module
├── contextmate/          # ContextMate: Context-aware chaining module
├── cad\_copilot/          # CAD-Copilot: Self-evolution in CAD
├── data/                 # Sample datasets
├── scripts/              # Evaluation and benchmark scripts
├── docs/                 # Architecture diagrams & extended documentation
├── requirements.txt      # Python dependencies
└── README.md             # This overview

````

## Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/<your-org>/smart-agent-toolchain.git
   cd smart-agent-toolchain
````

2. **Create a virtual environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

> *Detailed usage instructions will be provided per module once the relevant artifacts are released.*

### Agent-π (Google Chrome Extension, JavaScript source code)

```bash
cd agent_pi
```

### ContextMate (Python source code)

```bash
cd contextmate
streamlit run ui.py
```

### CAD-Copilot (C++ source code)

```bash
cd cad_copilot
```

## Citation

If you use any part of this code in your work, please cite:

```bibtex
@phdthesis{akjadoon2025self,
  title = {Self-Evolving Smart Agents for Intelligent Task Automation: A Framework for Tool Construction and Chaining},
  author = {Aamir Khan Jadoon},
  year = {2025},
  institution = {Tsinghua University, Beijing}
}
```

## Contributing

We welcome contributions, issues, and feature requests.
Please open an issue or pull request against the appropriate module directory.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.


**Next Steps:**  
Once our related publications are accepted, we will populate each module folder with detailed code examples, sample data, and extended documentation for immediate reproducibility.

