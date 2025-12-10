# 👋 Hi, I'm Ethan Seiz

I'm a student at Brown University interested in building tools that help people and improve their daily lives. Before transferring to Brown this year, I was a Freshman at Cornell University, and before that, I grew up in New York City. My research interests lie in computational fabrication, computer vision, deep learning, and application-specific integrated circuits. Outside of research, I also work on Project Teams and individual projects, where I've developed full-stack websites and iOS apps, and design and build robots and assistive technology.

Welcome to my engineering portfolio, where I highlight some of the projects I’ve had the privilege to work on. 

---

# 🔬 Research

## **CeraPiper — Cornell Tech, Matter of Tech Lab, Digital Fabrication**  

<table>
  <tr>
    <td align="center">
      <img src="images/cerapiper/demo_gif.gif" width="90%"><br>
      <em>Rapid prototyping with CeraPiper, demoed at the 2025 ACM Symposium on Computational Fabrication at MIT</em>
    </td>
  </tr>
</table>

**Tech:** JavaScript/HTML/CSS • Flask • Python • WebGL • Computer-Aided Manufacturing  

🔗 **Repo (Private):** https://github.com/matteroftech/CeraPipes  
🔗 **Paper:** https://doi.org/10.1145/3745778.3766644  
🔗 **Try it:** https://cerapipe.matteroftechlab.org/  

**🏆 Recognition:** Accepted to ACM SCF ’25 (MIT) • Awarded $7K Bowers Undergraduate Research Experience Grant • Published as Second Author  

### ⭐ Overview  
CeraPiper is a computer-aided manufacturing (CAM) tool for designing and fabricating ceramic evaporative cooling pipes. I developed the system while interning in Professor Thijs Roumen’s Matter of Tech Lab at Cornell Tech.

### 🔧 Technical Contributions
- Developed browser-based CAM tool with a **Python Flask backend** and **JavaScript/HTML/CSS front end**, including 3D
rendering with **p5.js (WebGL)**, enabling real-time design of programmable ceramic extrusion profiles.
- Implemented backend–device communication by transmitting **serialized JSON over PySerial to Arduino**, parsing commands in
**C++** to drive stepper motors controlling a shape-shifting extrusion die.

<table>
  <tr style="border: none;">
    <td align="center" width="33%" style="border: none;">
      <img src="images/cerapiper/Screenshot 2025-12-10 at 11.51.55 AM.png" width="100%"><br>
      <em>The CeraPiper browser-based CAM tool</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/cerapiper/scf25-1-fig3.jpg" width="100%"><br>
      <em>The CeraPiper machine</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/cerapiper/scf25-1-fig10.jpg" width="100%"><br>
      <em>Custom ceramic pipes produced by CeraPiper</em>
    </td>
  </tr>
  <tr style="border: none;">
    <td align="center" width="25%" style="border: none;">
        <img src="images/cerapiper/IMG_6169.JPG" width="100%"><br>
        <em>Presenting with Ofer Berman (Assistant Professor) at ACM SCF '25</em>
    </td>
    <td align="center" width="33%" style="border: none;">
        <img src="images/cerapiper/software_architecture.png" width="100%"><br>
        <em>Software architecture diagram</em>
    </td>
    <td align="center" width="33%" style="border: none;">
        <img src="images/cerapiper/scf25-1-fig5.jpg" width="100%"><br>
        <em>CAD rendering of controllable die</em>
    </td>
  </tr>
</table>

---

## **FuzzyCAD - Cornell Tech, Matter of Tech Lab, Digital Fabrication**  
 
<table>
  <tr>
    <td align="center">
      <img src="images/fuzzyCAD/demo_imgs/Screenshot 2025-08-06 at 1.36.21 PM.png" width="90%"><br>
      <em>Enables users to attach images and text to parts and visualize what a part might look like with different dimensions.</em>
    </td>
  </tr>
</table>

**Tech:** Onshape Extension • FeatureScript • Glassworks API • Google Gemini • Flask • Python

🔗 **Repo (Private):** https://github.com/matteroftech/fuzzyCAD                                 
🔗 **Try it (limited version):** https://cad.onshape.com/documents/675083deffb7a5bc4cd1e66e/w/2c3c5056863a478c4f4c6939/e/c37bdf8a1762a26ddde6af45  

### ⭐ Overview  
FuzzyCAD is an Onshape extension for collaboration between engineering and non-engineering domain experts, enabling these experts to express, annotate, and visualize uncertainty in CAD assemblies without CADing expertise. I developed the software during my internship at Cornell Tech’s Matter of Tech Lab.

### 🔧 Technical Contributions  
- Built an **Onshape-integrated extension** using FeatureScript + Onshape Glassworks API for attaching images, metadata, and uncertainty bounds to parts.  
- Designed and deployed a **Flask + JavaScript web interface** embedded directly within the Onshape UI.  
- Implemented **real-time tolerance propagation visualization** to support collaborative design review.  
- Integrated the **Google Gemini API** to automatically recommend relevant parts for annotation.  

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" width="50%" style="border: none;">
      <img src="images/fuzzyCAD/demo_imgs/Screenshot 2025-08-07 at 9.19.52 AM.png" width="100%"><br>
      <!-- <em>The CeraPiper browser-based CAM tool</em> -->
    </td>
    <td align="center" width="50%" style="border: none;">
      <img src="images/fuzzyCAD/demo_imgs/Screenshot 2025-08-07 at 9.20.04 AM.png" width="100%"><br>
      <!-- <em>The CeraPiper machine</em> -->
    </td>
  </tr>
  <tr style="border: none;">
    <td align="center" width="50%" style="border: none;">
      <img src="images/fuzzyCAD/demo_imgs/Screenshot 2025-08-07 at 10.02.01 AM.png" width="100%"><br>
      <!-- <em>The CeraPiper browser-based CAM tool</em> -->
    </td>
    <td align="center" width="50%" style="border: none;">
      <img src="images/fuzzyCAD/demo_imgs/Screenshot 2025-08-07 at 9.40.05 AM.png" width="100%"><br>
      <!-- <em>The CeraPiper machine</em> -->
    </td>
    <!-- "images/fuzzyCAD/demo_imgs/Screenshot 2025-08-07 at 10.02.01 AM.png" -->
  </tr>
</table>

---

## **Subchondral Bone Scan Deep Learning Segmentation — Cornell, Estroff Lab, Material Science**  

<table>
  <tr>
    <td align="center">
      <img src="images/estroff/Screenshot 2025-12-10 at 12.36.33 PM.png" width="90%"><br>
      <em>Example multi-ROI segmentation result</em>
    </td>
  </tr>
</table>

**Tech:** Deep Learning • Image Segmentation • Dragonfly 3D • Macros • Image Processing

🔗 Estroff Group: <https://estroff.mse.cornell.edu/>  

### ⭐ Overview 
During my freshman year at Cornell, I joined Lara Estroff's bio-inspired materials synthesis lab in the materials science engineering department.

I contributed to the subchondral bone project investigating how osteocyte networks differ between healthy and osteoarthritic knees. Using datasets of thousands of bonescans we imaged from human bone samples, I helped design the segmentation pipeline for the lacuno-canalicular network (LCN). First, I manually segmented samples in Dragonfly (image processing/analysis software) to create a deep learning training set. Then, I applied the model to make automated segmentation predictions, manually refined these predictions, and conducted image analyses on them by separating lacunae into ROIs for morphological quantification. Our results suggested that osteocytes in osteoarthritic bone exhibit irregular lacunar shapes and reduced canalicular density compared to healthy bone, motivating further analysis of lacunar sphericity, aspect ratio, and spatial orientation across mechanically distinct knee regions.

### 🔧 Technical Contributions  
- Trained a **U-Net–based segmentation model** on **10,000+ microstructure X-ray scans**.  
- Applied **Otsu thresholding** and **Kuwahara filtering** to denoise imaging data, improving segmentation accuracy by **50%**.  
- Built automated preprocessing, augmentation, and inference pipelines.

<table>
  <tr>
    <td align="center" width="33%">
      <img src="images/estroff/IMG_1BC0D7BF9E40-1.jpeg" width="100%"><br>
      <em>Image segmentation pipe</em>
    </td>
    <td align="center" width="33%">
      <img src="images/estroff/IMG_422B951B84E3-1.jpeg" width="100%"><br>
      <em>Human bone samples</em>
    </td>
    <td align="center" width="33%">
      <img src="images/estroff/IMG_2710.jpg" width="100%"><br>
      <em>Processed ROIs ready for morphological analysis</em>
    </td>
  </tr>
</table>

---

## **Tick-Borne Pathogen Sequencing — Cornell, Goodman Lab, Pathogen Genomics**  

🔗 **Paper (Preprint)**: https://doi.org/10.1101/2025.06.08.658352  

**🏆 Recognition:** Co-author of TITAN-RNA: A hybrid-capture sequencing panel detects known and unknown Flaviviridae for diagnostics and vector surveillance

### ⭐ Overview  
During my freshman year at Cornell, I worked in Professor Laura Goodman pathogen genomics lab at Cornell’s College of Veterinary Medicine.

I contributed to the Goodman Lab’s efforts to 1) develop next-generation sequencing (NGS) diagnostics for tick-borne pathogens and 2) understand the presence and range expansion of tick species in New York State (TickBlitz). I processed field-collected tick samples and performed qPCR and RT-PCR assays to detect viral and bacterial agents, generating data used to validate our new TITAN-RNA hybrid-capture sequencing panel. This platform enables comprehensive detection of known and novel Flaviviridae and other RNA viruses from vector samples. My work supported optimization of sample preparation protocols and assay validation.

### 🔧 Technical Contributions  
- Contributed to development of next-generation sequencing (NGS) diagnostics for tick-borne pathogens, using hybrid-capture and
metagenomic methods to improve the accuracy of disease surveillance.
- Processed field-collected tick samples and performed qPCR and RT-PCR assays to detect viral and bacterial pathogens,
contributing to validation of the TITAN-RNA hybrid-capture sequencing panel used for tick-borne virus discovery.

---

## **Physics-Driven Neural Hardware Accelerator — Pioneer Academics**  
**Compute Architecture • ML Simulation • Python**  
🔗 Thesis: <PDF_LINK>  

### ⭐ Overview  
Designed and simulated neural network accelerators using variable resistors to study contrastive learning dynamics.

### 🔧 Technical Contributions  
- Modeled resistor-based physical neural networks in Python.  
- Developed custom **evaluation tasks and accuracy metrics**.  
- Authored a **20-page research thesis**, presented to UPenn postdoc Sam Dillavou.

---

# 🏎️ Project Teams

## **Brown Formula Racing — DRS Algorithms Engineer**  
**C++ • MoTeC ECU • Real-Time Systems**  

### 🔧 Contributions  
- Implementing an autonomous **Drag Reduction System (DRS)** controller triggered by live vehicle telemetry.  
- Writing and validating **real-time C++ control algorithms** on MoTeC’s ECU.

---

## **Full Stack at Brown — Software Engineer**  
**React • TypeScript • Cosmic CMS**  
🔗 Repo: <LINK>  

### 🔧 Contributions  
- Developing a full-stack website for **Project BRYTE**, supporting refugee youth in Providence.  
- Building React + TypeScript components integrated with Cosmic CMS.

---

## **Cornell Assistive Technologies — Software & Electrical Engineer**  
**Python • C++ • ML • Embedded Systems • CAD**  

### 🔧 Contributions  
- Built ML pipelines to detect **sensory overload** from smartwatch sensor data.  
- Helped prototype an **EEG-controlled wheelchair** using brainwave signal processing.  
- Modified toys for children with disabilities through toy-adapting volunteer events.

---

## **Avenues Robotics (FTC) — President & Co-Founder**  
**CAD • Fabrication • Java • Leadership**  

### ⭐ Highlights  
- Led school’s largest engineering club (**90+ members**), mentoring **8 FTC teams**.  
- Competed at the **FIRST Tech Challenge World Championships** (Top 1% of 7,000 teams).  
- Placed **1st overall** at the NYC Championships.  
- Taught **40+ workshops** for low-income students and raised **$4K** to start an FLL team.

---

# 🧪 Independent Projects

## **CeraPiper (Engineering Implementation)**  
**p5.js • Flask • Python • WebGL • Electronics**  
🔗 Repo: <YOUR_LINK>  

### 🔧 Contributions  
- Built the 3D p5.js CAD system used for prototyping extrusion geometry.  
- Implemented the JSON → PySerial → Arduino pipeline controlling the **shape-shifting extrusion die**.

---

## **Tick Spotter — ML Classification System**  
**Python • TensorFlow • Keras • YOLO • OpenCV • Selenium**  
🔗 Repo: <YOUR_LINK>  

### ⭐ Overview  
A multi-class tick identification system trained on a 15,000-image dataset.

### 🔧 Technical Contributions  
- Trained CNN + object detection models (**YOLO, R-CNN, VGG16, ResNet50**) with transfer learning and regularization.  
- Automated dataset collection via **Selenium web scraping** and API polling.  
- Implemented augmentation (rotation, hue thresholding) and optimized training using early stopping + LR scheduling.  
- Achieved **96% classification accuracy**.

---

## **Red Retriever — Full-Stack iOS Lost-and-Found App**  
**Swift • Flask • SQL • REST API • NLP • Figma**  
🔗 Repo: <YOUR_LINK>  

### ⭐ Overview  
A lost-and-found platform for **20,000+ Cornell students**, enabling searchable, matchable item posts.

### 🔧 Technical Contributions  
- Built the iOS app with **Google OAuth**, item posting, matching, and leaderboard features.  
- Developed Flask + SQL backend with REST endpoints and NLP-powered heuristics.  
- Designed UI in Figma and implemented components in UIKit.

---

## **Silicone Heartbeat Simulator**  
**Mechanical Design • Sensors • Prototyping**  
🔗 Project Link: <YOUR_LINK>  

### ⭐ Overview  
A device that generates heartbeat-like pulsations inside a silicone mold for optical sensing tests.

### 🔧 Technical Contributions  
- Designed timing control for pump-driven pressure oscillations.  
- Added a **reflective sensing layer** enabling optical detection of pulsations.

---

## **Onshape Uncertainty Annotation (FuzzyCAD UI Build-Out)**  
**JavaScript • Onshape API • CAD Visualization**  
🔗 Repo: <YOUR_LINK>  

### 🔧 Contributions  
- Built the web UI for interacting with uncertainty metadata in Onshape.  
- Added image viewing, part association, and interactive metadata controls.  
- Integrated seamlessly with the larger FuzzyCAD toolchain.

---

# 📫 Contact

**Email:** ethan_seiz@brown.edu  
**LinkedIn:** https://www.linkedin.com/in/ethan-seiz  
**GitHub:** https://github.com/hawkbsilleee  

Thanks for stopping by — feel free to reach out!
