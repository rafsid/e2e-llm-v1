# LLM Training Environment Setup

## Overview
This repository contains a comprehensive setup for optimized LLM training environments, featuring accelerated training pipelines, automated Git integration, and real-time feedback systems. The setup includes magic functions for enhanced developer experience and performance monitoring.

## Key Features
- Automated Git integration with timestamped branches
- Visual and audio feedback systems for code execution
- Accelerated training configurations
- Memory optimization techniques
- Cache management systems

## Components

### 1. Git Integration
- Automatic branch creation with timestamp-based naming
- Configurable auto-save intervals
- Branch cleanup automation
- Push/pull operations with error handling

### 2. Feedback Systems
- Visual feedback for code execution status
- Audio feedback system (optional)
- Real-time execution status indicators
- Performance metrics display

### 3. Training Optimizations 
- Accelerator integration
- Memory management
- Cache optimization
- Batch processing configurations

### 4. Environment Management
- Conda library updates
- Package version control
- Dependency management
- Cache cleanup utilities

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/username/llm-training-environment.git
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Configure environment variables:
```bash
export HF_TOKEN="your_hugging_face_token"
```

## Usage

### Git Magic Functions
```python
%%ap1
# Your code here
# Will automatically save and push to a new branch
```

### Visual Feedback
```python
# Visual feedback is automatically enabled for all code execution
# Green dot = Success
# Red dot = Error
```

### Memory Management
```python
# Clear cache
clear_cache()

# Monitor memory usage
print_memory_stats()
```

## Configuration

### Git Settings
- Auto-save interval: 120 seconds (configurable)
- Branch naming format: "DD-MMM-YYYY-HHMM-IST"
- Auto-cleanup of old auto-save branches

### Training Settings
- Default batch size: 2
- Gradient accumulation steps: 4
- Learning rate: 2e-4
- Weight decay: 0.01

## Requirements
- Python 3.8+
- PyTorch 2.0+
- Accelerate
- Transformers
- MLflow
- Git

## Performance Optimization
- Memory usage monitoring
- Cache management
- Batch size optimization
- GPU utilization tracking

## Contributing
Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) for details.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Hugging Face team for transformers library
- Unsloth team for optimization techniques
- PyTorch team for core functionalities
