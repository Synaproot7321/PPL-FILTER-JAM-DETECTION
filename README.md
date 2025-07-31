# PPL Filter Blockage Detection with Computer Vision

<p align="justify">
  <em>NOTE: During my experience in the mining sector, I participated in the development of a visual inspection system using machine vision to detect blockages in filters. Out of respect for confidentiality, no images or technical details of the actual system are included. The documentation presented here is a representative simulation developed by me for demonstration purposes.</em>
</p>

This project focuses on reducing inspection time for PPL (Pressure Plate Leaf) filter blockages in mineral processing plants using visual analysis.
## 🚀 Project Overview

Traditional inspection of filter blockages is time-consuming and often exposes operators to harsh environments. To address this, I developed a computer vision system capable of detecting clogging in PPL filters automatically.

By integrating image processing techniques and real-time image processing, the system achieved a **reduction in inspection time**, improving operational safety and maintenance efficiency.

## 📌 Problem Statement

In mining and industrial filtration processes, PPL filters play a crucial role in separating solids from liquids. Blockages in these filters can lead to process inefficiencies, equipment wear, and unexpected downtime. Manual inspection is often slow, imprecise, and exposes personnel to high-risk environments. That's why it's so important to know as quickly as possible when these blockages occur.

## 🎯 Project Objective

To develop and deploy a **computer vision solution** that automatically detects blockages in PPL filters using real-time image analysis, thereby:

- Reducing inspection time 
- Improving safety and performance by minimizing the need for manual inspection
- Enabling predictive maintenance with early anomaly detection
  
## 🔧 Technologies Used

- Python
- OpenCV
- Industrial camera 

## 🧠 How It Works

1. **Analysis Start**: The process begin after each discharge.

   > Simulated image.

<div align="center">

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/eb7b7042-322d-4ba7-87a1-55b98ee92c9c" width="300"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Discharging</strong></td>
  </tr>
</table>

</div>


3. **Image Acquisition**: Captures images of the PPL filter surface in operation.
4. **Preprocessing**: Enhances image quality and isolates relevant features.
5. **Make Inferences**: Using mathematical operations and image processing techniques, an inference is generated.

      > Simulated images.

<div align="center">

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/0b77e204-6683-44e8-88e8-14e94b84ca74" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/9237a1d5-9aae-4e1b-ba37-99f6a197da85" width="300"/></td>
  </tr>
  <tr>
    <td align="center"><strong>Clogged Filter</strong></td>
    <td align="center"><strong>Unclogged Filter</strong></td>
  </tr>
</table>

</div>



## 📊 Impact

- ⏱️ Reduced inspection time
- 🔧 Improved maintenance scheduling
- 🧯 Enhanced operator safety by minimizing manual inspections
- ⚠️ Prevented excessive clogging







 [<img width="826" height="310" alt="image" src="https://github.com/user-attachments/assets/5494c027-64db-416a-92b6-4acae8911554" />]: #
