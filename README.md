# MONAI Multi-modal

MONAI Multi-modal is a comprehensive, domain-specific framework for developing, validating, and deploying Vision Language Models (VLMs) that leverages the MONAI community. Our framework integrates diverse healthcare data types through specialized I/O components, supporting DICOM for medical imaging (CT, MRI, etc.), EHR systems for structured and unstructured clinical data, video streams for surgical recordings and dynamic imaging, WSI for large high-resolution pathology images, as well as various text formats for clinical notes and standard image formats (PNG, JPEG, TIFF) for pathology slides or static images.

This open ecosystem enables seamless integration and management of agentic workflows and state-of-the-art VLMs across research and clinical applications, supporting reasoning capabilities while allowing for the integration of custom models and Hugging Face components.

## Repository Structure

This master repository provides access to the following specialized agentic frameworks:

- [VLM-Radiology-Agent-Framework](https://github.com/project-monai/VLM-Radiology-Agent-Framework) - Multi-modal agentic framework for radiology and medical imaging analysis (VILA-M3)
- [VLM-Surgical-Agent-Framework](https://github.com/project-monai/VLM-Surgical-Agent-Framework) - Multi-modal agentic framework for surgical procedures

## Agentic Framework Overviews

### VLM-Radiology-Agent-Framework

The VLM-Radiology-Agent-Framework (VILA-M3) is a radiology-focused framework that combines medical images with text data to assist radiologists in diagnosis and interpretation. 

**Key Features:**

- Integrates 3D imaging with patient records
- Leverages LLMs and VLMs for comprehensive analysis
- Access specialized expert models on-demand (VISTA3D, MONAI BRATS, TorchXRayVision) For details, see the [VLM-Radiology-Agent-Framework repository](https://github.com/project-monai/VLM-Radiology-Agent-Framework) or the [VILA-M3 Paper](https://arxiv.org/pdf/2411.12915).

### VLM-Surgical-Agent-Framework

The VLM-Surgical-Agent-Framework provides end-to-end support for surgical workflows through a multi-agent system. 

**Key Features:**

- Real-time speech transcription
- Specialized agents for query routing, Q&A, documentation, annotation, and reporting
- Computer vision integration for image analysis
- Optional voice response capabilities For implementation details, see the [VLM-Surgical-Agent-Framework repository](https://github.com/project-monai/VLM-Surgical-Agent-Framework).

## Getting Started

Each repository contains specific installation and usage instructions. Please refer to the individual repositories for detailed setup guides.
