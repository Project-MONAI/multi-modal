# MONAI Multi-modal

MONAI Multi-modal is a comprehensive, domain-specific framework for developing, validating, and deploying Vision Language Models (VLMs) that leverages the MONAI community. Our framework integrates diverse healthcare data types through specialized I/O components, supporting DICOM for medical imaging (CT, MRI, etc.), EHR systems for structured and unstructured clinical data, video streams for surgical recordings and dynamic imaging, WSI for large high-resolution pathology images, as well as various text formats for clinical notes and standard image formats (PNG, JPEG, TIFF) for pathology slides or static images.

This open ecosystem enables seamless integration and management of agentic workflows and state-of-the-art VLMs across research and clinical applications, supporting reasoning capabilities while allowing for the integration of custom models and Hugging Face components.

## Repository Structure

This master repository provides access to the following specialized agentic frameworks and foundation models:

- **[VLM-Radiology-Agent-Framework](https://github.com/project-monai/VLM-Radiology-Agent-Framework)** - Multi-modal agentic framework for radiology and medical imaging analysis (VILA-M3)
- **[VLM-Surgical-Agent-Framework](https://github.com/project-monai/VLM-Surgical-Agent-Framework)** - Multi-modal agentic framework for surgical procedures
- **[CT-CHAT](https://github.com/ibrahimethemhamamci/CT-CHAT)** - Vision-language foundational chat model for 3D chest CT volumes
- **[RadViLLA](https://www.radimagenet.com/)** - 3D vision-language model for radiology covering chest, abdomen, and pelvis

## Agentic Framework Overviews

### VLM-Radiology-Agent-Framework

A radiology-focused framework that combines medical images with text data to assist radiologists in diagnosis and interpretation.

**Key Features:**

- Integrates 3D imaging with patient records
- Leverages LLMs and VLMs for comprehensive analysis
- Access specialized expert models on-demand (VISTA3D, MONAI BRATS, TorchXRayVision)

For details, see the [VLM-Radiology-Agent-Framework repository](https://github.com/project-monai/VLM-Radiology-Agent-Framework) or the [VILA-M3 Paper](https://arxiv.org/pdf/2411.12915).

------

### VLM-Surgical-Agent-Framework

A comprehensive framework providing end-to-end support for surgical workflows through a multi-agent system.

**Key Features:**

- Real-time speech transcription
- Specialized agents for query routing, Q&A, documentation, annotation, and reporting
- Computer vision integration for image analysis
- Optional voice response capabilities

For implementation details, see the [VLM-Surgical-Agent-Framework repository](https://github.com/project-monai/VLM-Surgical-Agent-Framework).

## Foundation Models

### CT-CHAT

A cutting-edge vision-language foundational chat model developed by the University of Zurich, specifically designed to enhance the interpretation and diagnostic capabilities of 3D chest CT imaging.

**Key Features:**

- Trained on 2.7M+ question-answer pairs from CT-RATE
- Supports multiple LLM backends (Llama 3.1, Vicuna, Mistral)

For implementation details and access to CT-CHAT, please visit the [official GitHub repository](https://github.com/ibrahimethemhamamci/CT-CHAT).

------

### RadViLLA

A 3D vision-language model for radiology developed by [RadImageNet](https://www.radimagenet.com/), [The BioMedical Engineering and Imaging Institute at Mount Sinai's Icahn School of Medicine](https://icahn.mssm.edu/research/bmeii), and NVIDIA.

**Key Features:**

- Trained on 75,000 CT scans and 1M+ question-answer pairs
- Uses two-stage training to integrate 3D scans with text
- Optimized for clinical query response with superior accuracy metrics

## Getting Started

Each repository contains specific installation and usage instructions. Please refer to the individual repositories for detailed setup guides.
