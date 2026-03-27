# A Comparative AI Approach to Feminist Urban Design in the Global South

## Overview
This repository contains the research, methodology, and supporting materials for the paper: “A comparative AI approach to feminist urban design of public spaces of the Global South.” The project proposes an integrative methodology combining Artificial Intelligence and feminist urban design principles to analyze safety and inclusion in peripheral neighborhoods across South America and Southeast Asia. It focuses on micro-public spaces around bus stops (350m radius)—critical yet often overlooked sites where gendered and class-based inequalities become visible.

Aquí tienes todo el README en el formato que pediste, limpio y listo para copiar en Markdown:

---

## Repository Structure

```bash
├── AISegmentation/       # AI models and object detection analysis
├── DataExtraction/       # Scripts for data collection (OSMnx + Street View API)
├── SuperResolution/      # Image enhancement using Real-ESRGAN
├── FeministFramework/    # Classification logic for urban design principles
├── results/              # Outputs, maps, and comparative analysis
└── paper/                # Research paper and supporting materials
```

## Methodology

1. **Data Collection**: Street-level images were systematically collected around bus stops (350m radius) using Google Street View API and OSMnx-derived nodes
2. **Image Enhancement**: Implemented Real-ESRGAN super-resolution model to improve image quality and feature visibility
3. **Feature Detection**: Applied YOLO-World open-vocabulary object detection model to identify urban features
4. **Analysis**: Categorized features according to six feminist urban design principles:

   * Safety
   * Proximity
   * Diversity
   * Autonomy
   * Vitality
   * Representativeness

## Key Findings

* Safety-related features: 56.4%
* Proximity features: 22.5%
* Autonomy features: 9.7%
* Vitality features: 6.4%
* Diversity features: 4.9%
* Representativeness features: 0.2%

## Requirements

* Python 3.8+
* PyTorch
* YOLO-World
* Real-ESRGAN
* OSMnx
* Google Street View API access
* Additional dependencies listed in `requirements.txt`

## Usage

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run data collection scripts in `DataExtraction/`
4. Apply super-resolution in `SuperResolution/`
5. Execute detection models in `AISegmentation/`
6. Analyze outputs and visualizations in `results/`

## Authors

Medina, A., Mosquera, D., & Gallegos, F. (2026)

## Acknowledgements

Special thanks to collaborators and contributors supporting data collection, validation, and analysis processes.

## Citation

```bibtex
@article{
  title={A comparative AI approach to feminist urban design of public spaces of the Global South},
  author={Medina, A. Mosquera, D. Gallegos, F. Mosquera, K. Vásconez, J.},
  year={2026}
}
```
