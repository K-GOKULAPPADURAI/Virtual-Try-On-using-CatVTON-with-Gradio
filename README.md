# Virtual-Try-On-using-CatVTON-with-Gradio
# CatVTON - Virtual Try-On Model

This repository is a reference implementation of the **CatVTON** virtual try-on model based on diffusion techniques. It provides a way to generate realistic virtual clothing try-ons using deep learning models.

## About This Repository

This repository is a modified version of the original open-source CatVTON project. The main implementation remains the same, and all credits for the original work go to the respective authors. This repo serves as a reference and an alternative setup for users who want to explore the project in a different environment.

### Original Repository

For the official implementation and documentation, please visit the [original CatVTON repository] by 
Zheng-Chong and eltociear (https://github.com/Zheng-Chong/CatVTON/).

## Setup and Installation

To use this project, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-github-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Model**

   ```bash
   python app.py --output_dir="resource/demo/output" --mixed_precision="bf16" --allow_tf32
   ```

## Gradio UI Integration

This application includes a **Gradio UI** for a user-friendly virtual try-on experience. The interface allows users to:
- Upload images of clothing and a person.
- Process the virtual try-on with the deep learning model.
- Preview and download the final generated image.

To launch the **Gradio UI**, run:

```bash
python gradio_app.py
```

Once started, Gradio will provide a local and public URL where you can interact with the model through a web-based UI.

## Performance & Hardware Requirements

- **GPU Used**: NVIDIA RTX 3060 (6GB VRAM)
- **Processing Time**: Takes approximately **3 to 5 minutes** for generating a single image.
- **Installation and Setup**: Requires cloning the repository and installing dependencies via `requirements.txt`.

## Contact & Support

For any doubts or queries, feel free to reach out:

- **Email**: [k.gokulappaduraikjgv@gmail.com](mailto:k.gokulappaduraikjgv@gmail.com)
- **Phone**: 9025421765

---

This repository is intended for learning and experimentation purposes, with reference to the original CatVTON project.

