![PYCAD](https://capsule-render.vercel.app/api?type=soft&color=ffc800&text=PYCAD%20-%20Redefining%20Medical%20Imaging&fontSize=40&animation=twinkling)

[![Static Badge](https://img.shields.io/badge/PYCAD-Chatbot-%23018c54?logoColor=ffc800&link=https%3A%2F%2Fgithub.com%2Famine0110%2Fpycad%2Ftree%2Fmain%2Fdocs)](https://pycad-chatbot.streamlit.app/)
 [![Static Badge](https://img.shields.io/badge/PYCAD-Blog-%23ffc800?logoColor=ffc800&link=https%3A%2F%2Fpycad.co%2F)](https://pycad.co/) [![Static Badge](https://img.shields.io/badge/PYCAD-Docs-blue?logoColor=ffc800&link=https%3A%2F%2Fgithub.com%2Famine0110%2Fpycad%2Ftree%2Fmain%2Fdocs)](https://github.com/amine0110/pycad/tree/main/docs) [![Static Badge](https://img.shields.io/badge/PYCAD-Tutorials-green?logoColor=ffc800&link=https%3A%2F%2Fgithub.com%2Famine0110%2Fpycad%2Ftree%2Fmain%2Fdocs)](https://github.com/amine0110/pycad/tree/main/tutorials) [![Static Badge](https://img.shields.io/badge/PYCAD-YouTube-%23e80202?logoColor=ffc800&link=https%3A%2F%2Fgithub.com%2Famine0110%2Fpycad%2Ftree%2Fmain%2Fdocs)](https://www.youtube.com/channel/UCdYyILlPlehK4fKS5DiuMXQ) [![Static Badge](https://img.shields.io/badge/PYCAD-Courses-%23d600e6?logoColor=ffc800&link=https%3A%2F%2Fgithub.com%2Famine0110%2Fpycad%2Ftree%2Fmain%2Fdocs)](https://pycad.co/courses/) [![Static Badge](https://img.shields.io/badge/PYCAD-Services-%23000000?logoColor=ffc800&link=https%3A%2F%2Fgithub.com%2Famine0110%2Fpycad%2Ftree%2Fmain%2Fdocs)](https://pycad.co/services/) [![Static Badge](https://img.shields.io/badge/PYCAD-Portfolio-%23eb5d10?logoColor=ffc800&link=https%3A%2F%2Fgithub.com%2Famine0110%2Fpycad%2Ftree%2Fmain%2Fdocs)](https://pycad.co/portfolio/)


Welcome to PYCAD, a comprehensive library designed to simplify and streamline medical imaging tasks. From data preprocessing to advanced visualization, PYCAD empowers professionals, researchers, and enthusiasts to harness the power of modern algorithms and techniques with ease.


## Installation

1. **Clone the repository**:
   
   ```bash
   pip install pycad-medic
   ```

For more installation instructions, please see [this](https://github.com/amine0110/pycad/blob/main/docs/getting_started.md).

## Features & Usage

- **Image File Conversion**: Between NIFTI and DICOM formats.
- **Visualization**: Upcoming feature to visualize medical imaging data.
- **Data Preprocessing**: Including data splitting and annotation conversion.
- **Dataset Creation**: Configurations for YOLOv8.

For detailed usage and examples, refer to the [tutorials](./tutorials) directory and [documentation](./docs).

## What is New?
The latest release `0.0.8` contains a new feature which is the possibility to download one of over 120 different datasets (more datasets will be added in the next releases). Here is an example of use:

```Python
from pycad.dataset.segmentation.TotalSegmentator import AutochthonLeftDataset

autochthon_left_dataset = AutochthonLeftDataset()
autochthon_left_dataset.info()  # Print dataset information
autochthon_left_dataset.download('100')  # Download and extract subgroup 100
```

This feature is useful for people who wants to experiment with the medical imaging dataset and needs a small batch to test or they need to download the dataset to a specific server without the need to use the UI. Everything is on your terminal and it is fast!

## Contributions & Support

We value contributions from the community! If you find a bug, want to propose a feature, or simply have a question, feel free to open an issue on our GitHub repository.

For deeper insights and support, consider booking a [premium session](https://pycad.co/services) with us.

## License

`PYCAD` is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

## Connect with Us
Stay updated with our latest advancements:

- 📹 [YouTube](https://www.youtube.com/c/pycad)
- 📖 [Blog](https://pycad.co/)
- 📧 [Newsletter](https://pycad.co/join-us/)
- 💼 [Premium Sessions](https://pycad.co/services/)

## Contact & Inquiries

For business inquiries, please reach out to us at:

📧 [contact@pycad.co](mailto:contact@pycad.co)


---
<p align="center"> 
  Visitor count<br>
  <img src="https://profile-counter.glitch.me/amine0110%2Fpycad/count.svg" />
</p>
