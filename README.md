# MONAI Multi-modal

This repository serves as the central hub for MONAI's multi-modal medical agentic frameworks. Our multi-modal approach integrates diverse healthcare data types including medical imaging (CT, MRI, X-ray, ultrasound), electronic health records, clinical documentation, DICOM standards, video streams, whole slide imaging, and more to enable comprehensive analysis and support across the clinical workflow.

## Repository Structure

This master repository provides access to the following specialized agentic frameworks:

- [VLM-VILA-M3](https://github.com/project-monai/VLM-VILA-M3) - Multimodal Radiology Agentic Framework for comprehensive medical imaging analysis and interpretation
- [VLM-VILA-SURG](https://github.com/project-monai/VLM-VILA-SURG) - Multimodal Surgical Agentic Framework for end-to-end surgical workflow support

## Agentic Framework Overviews

### VLM-VILA-M3

VILA-M3 is a radiology-focused framework that combines medical images with text data to assist radiologists in diagnosis and interpretation.

**Key Features:**

- Integrates 3D imaging with patient records
- Leverages LLMs and VLMs for comprehensive analysis
- Access specialized expert models on-demand (VISTA3D, MONAI BRATS, TorchXRayVision)

For details, see the [VLM-VILA-M3 repository](https://github.com/project-monai/VLM-VILA-M3) or the [VILA-M3 Paper](https://arxiv.org/pdf/2411.12915).

### VLM-VILA-SURG

VILA-SURG provides end-to-end support for surgical workflows through a multi-agent system.

**Key Features:**

- Real-time speech transcription
- Specialized agents for query routing, Q&A, documentation, annotation, and reporting
- Computer vision integration for image analysis
- Optional voice response capabilities

For implementation details, see the [VLM-VILA-SURG repository](https://github.com/project-monai/VLM-VILA-SURG).

## Getting Started

Each repository contains specific installation and usage instructions. Please refer to the individual repositories for detailed setup guides.
