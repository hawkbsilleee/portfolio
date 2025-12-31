<p align="center">
  <img src="images/IMG_8552.jpeg" width="160" style="border-radius: 5%;" />
</p>

<h1 align="center">👋 Hi, I'm Ethan Seiz</h1>

<!-- <p align="center">
  Student at Brown University · Computational Fabrication · Computer Vision · DL · ASICs
</p> -->


<!-- # 👋 Hi, I'm Ethan Seiz -->

I'm a student at Brown University interested in building tools that help people and improve their daily lives. Before transferring to Brown, I did my Freshman at Cornell University, and before that, I grew up in New York City. My research interests lie in computational fabrication, computer vision, deep learning, and application-specific integrated circuits. Outside of research, I also work on Project Teams and individual projects, where I've developed full-stack websites and iOS apps, and design and build robots and assistive technology.

Welcome to my engineering portfolio, where I highlight some of the projects I've had the privilege to work on. 

---

<br>

# 🔬 Research

## **CeraPiper — Cornell Tech, Matter of Tech Lab, Digital Fabrication**  

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" style="border: none;">
      <img src="images/cerapiper/demo_gif.gif" width="90%"><br>
      <em>Rapid prototyping with CeraPiper, demoed at the 2025 ACM Symposium on Computational Fabrication at MIT</em>
    </td>
  </tr>
</table>

**JavaScript/HTML/CSS • Flask • Python • WebGL • Computer-Aided Manufacturing**  

🔗 **Repo (Private):** https://github.com/matteroftech/CeraPipes  
🔗 **Paper:** https://doi.org/10.1145/3745778.3766644  
🔗 **Try it:** https://cerapipe.matteroftechlab.org/  
🔗 **Article:** https://news.cornell.edu/stories/2025/12/whats-old-new-customizable-system-sustainable-cooling

**🏆 Recognition:** Accepted to ACM SCF '25 (MIT) • Awarded $7K Bowers Undergraduate Research Experience Grant • Published as Second Author  

### ⭐ Overview  
CeraPiper is a computer-aided manufacturing (CAM) tool for designing and fabricating ceramic evaporative cooling pipes. I developed the system while interning in Professor Thijs Roumen's Matter of Tech Lab at Cornell Tech.

### 🔧 Technical Contributions
- Developed browser-based CAM tool with a **Python Flask backend** and **JavaScript/HTML/CSS front end**, including 3D
rendering with **p5.js (WebGL)**, enabling real-time design of programmable ceramic extrusion profiles.
- Implemented backend–device communication by transmitting **serialized JSON over PySerial to Arduino**, parsing commands in
**C++** to drive stepper motors controlling a shape-shifting extrusion die.

<table>
  <tr style="border: none;">
    <td align="center" width="33%" style="border: none;">
      <img src="images/cerapiper/editor-shot.png" width="100%"><br>
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
        <em>Presenting with Ofer Berman (First Author) at ACM SCF '25</em>
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
 
<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" style="border: none;">
      <img src="images/fuzzyCAD/shot1.png" width="90%"><br>
      <em>Enables users to attach images and text to parts and visualize what a part might look like with different dimensions.</em>
    </td>
  </tr>
</table>

**Onshape Extension • FeatureScript • Glassworks API • Google Gemini • Flask • Python**

🔗 **Repo (Private):** https://github.com/matteroftech/fuzzyCAD                                 
🔗 **Try it (limited version):** https://cad.onshape.com/documents/675083deffb7a5bc4cd1e66e/w/2c3c5056863a478c4f4c6939/e/c37bdf8a1762a26ddde6af45  

### ⭐ Overview  
FuzzyCAD is an Onshape extension for collaboration between engineering and non-engineering domain experts, enabling these experts to express, annotate, and visualize uncertainty in CAD assemblies without CADing expertise. I developed the software during my internship at Cornell Tech's Matter of Tech Lab.

### 🔧 Technical Contributions  
- Built an **Onshape-integrated extension** using FeatureScript + Onshape Glassworks API for attaching images, metadata, and uncertainty bounds to parts.  
- Designed and deployed a **Flask + JavaScript web interface** embedded directly within the Onshape UI.  
- Implemented **real-time tolerance propagation visualization** to support collaborative design review.  
- Integrated the **Google Gemini API** to automatically recommend relevant parts for annotation.  

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" width="50%" style="border: none;">
      <img src="images/fuzzyCAD/shot2.png" width="100%"><br>
      <em>The image annotation tool</em>
    </td>
    <td align="center" width="50%" style="border: none;">
      <img src="images/fuzzyCAD/shot3.png" width="100%"><br>
      <em>Reads API for comments and automatically creates annotations for them</em>
    </td>
  </tr>
  <tr style="border: none;">
    <td align="center" width="50%" style="border: none;">
      <img src="images/fuzzyCAD/shot4.png" width="100%"><br>
      <em>Users can visualize parts in different orientations or dimensions</em>
    </td>
    <td align="center" width="50%" style="border: none;">
      <img src="images/fuzzyCAD/shot5.png" width="100%"><br>
      <em>The bounding box annotation outlines the annotated part in red, indicating uncertainty</em>
    </td>
    <!-- "images/fuzzyCAD/demo_imgs/Screenshot 2025-08-07 at 10.02.01 AM.png" -->
  </tr>
</table>

---

## **Subchondral Bone Scan Deep Learning Segmentation — Cornell, Estroff Lab, Material Science**  

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" style="border: none;">
      <img src="images/estroff/segmentation-result.png" width="90%"><br>
      <em>Example multi-ROI segmentation result</em>
    </td>
  </tr>
</table>

**Deep Learning • Image Segmentation • Dragonfly 3D • Macros • Image Processing**

🔗 Estroff Group: <https://estroff.mse.cornell.edu/>  

### ⭐ Overview 
During my freshman year at Cornell, I joined Lara Estroff's bio-inspired materials synthesis lab in the materials science engineering department.

I contributed to the subchondral bone project investigating how osteocyte networks differ between healthy and osteoarthritic knees. Using datasets of thousands of bonescans we imaged from human bone samples, I helped design the segmentation pipeline for the lacuno-canalicular network (LCN). First, I manually segmented samples in Dragonfly (image processing/analysis software) to create a deep learning training set. Then, I applied the model to make automated segmentation predictions, manually refined these predictions, and conducted image analyses on them by separating lacunae into ROIs for morphological quantification. Our results suggested that osteocytes in osteoarthritic bone exhibit irregular lacunar shapes and reduced canalicular density compared to healthy bone, motivating further analysis of lacunar sphericity, aspect ratio, and spatial orientation across mechanically distinct knee regions.

### 🔧 Technical Contributions  
- Trained a **U-Net–based segmentation model** on **10,000+ microstructure X-ray scans**.  
- Applied **Otsu thresholding** and **Kuwahara filtering** to denoise imaging data, improving segmentation accuracy by **50%**.  
- Built automated preprocessing, augmentation, and inference pipelines.

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" width="33%" style="border: none;">
      <img src="images/estroff/IMG_1BC0D7BF9E40-1.jpeg" width="100%"><br>
      <em>Image segmentation pipeline</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/estroff/IMG_422B951B84E3-1.jpeg" width="100%"><br>
      <em>Human bone samples</em>
    </td>
    <td align="center" width="33%" style="border: none;">
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
During my freshman year at Cornell, I worked in Professor Laura Goodman pathogen genomics lab at Cornell's College of Veterinary Medicine.

I contributed to the Goodman Lab's efforts to 1) develop next-generation sequencing (NGS) diagnostics for tick-borne pathogens and 2) understand the presence and range expansion of tick species in New York State (TickBlitz). I processed field-collected tick samples and performed qPCR and RT-PCR assays to detect viral and bacterial agents, generating data used to validate our new TITAN-RNA hybrid-capture sequencing panel. This platform enables comprehensive detection of known and novel Flaviviridae and other RNA viruses from vector samples. My work supported optimization of sample preparation protocols and assay validation.

### 🔧 Technical Contributions  
- Contributed to development of next-generation sequencing (NGS) diagnostics for tick-borne pathogens, using hybrid-capture and
metagenomic methods to improve the accuracy of disease surveillance.
- Processed field-collected tick samples and performed qPCR and RT-PCR assays to detect viral and bacterial pathogens,
contributing to validation of the TITAN-RNA hybrid-capture sequencing panel used for tick-borne virus discovery.

---

<!-- ## **Physics-Driven Neural Hardware Accelerator — Pioneer Academics**  
**Compute Architecture • ML Simulation • Python**  
🔗 Thesis: <PDF_LINK>  

### ⭐ Overview  
Designed and simulated neural network accelerators using variable resistors to study contrastive learning dynamics.

### 🔧 Technical Contributions  
- Modeled resistor-based physical neural networks in Python.  
- Developed custom **evaluation tasks and accuracy metrics**.  
- Authored a **20-page research thesis**, presented to UPenn postdoc Sam Dillavou. -->

## **VitalHide — Cornell Tech, Matter of Tech Lab, CS+Mechanical Engineering**  

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" width="33%" style="border: none;">
      <img src="images/vitalHide/IMG_5603-ezgif.com-video-to-gif-converter.gif" width="100%"><br>
      <em>TPU 3D-printed prototype inflating</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/vitalHide/IMG_2353.jpeg" width="100%"><br>
      <em>3D-printed mold prototype</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/vitalHide/IMG_3273.jpg" width="100%"><br>
      <em>Silicon prototype tested with ultrasonic sensors</em>
    </td>
  </tr>
</table>


**Fusion360 • 3D-Printing • Laser-Cutting • Silicon-Molding • Python**  

🔗 VitalHide Article: https://tech.cornell.edu/news/vitalhide/ 

### ⭐ Overview  
During my internship in Cornell Tech's Matter of Tech Lab, I helped develop VitalHide, a device that simulates human functions to block unwanted signal transmission. It works by pumping air in and out of silicon structures that inflate in specific patterns. Embedded in the silicon is a reflective material that thwarts adversarial sensors attempting to monitor human vital signs. 

### 🔧 Technical Contributions  
- Designed several silicon molds in Fusion360 and 3D-printed them with PLA and TPU.  
- Used the molds to fabricate the silicon structures and test their effectiveness.  

---

## **Simulating Decentralized, Physics-Driven Learning — Electrical and Computer Engineering** 

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" style="border: none;">
      <img src="images/pioneer/resistor-network-situ.png" width="90%"><br>
      <em>Resistor network in situ</em>
    </td>
  </tr>
</table>

**Circuit Simulation • Python • Literature Review**

🔗 **Report:** [Simulating Decentralized, Physics-Driven Learning](images/pioneer/Simulating%20Decentralized,%20Physics-Driven%20Learning.pdf)


### ⭐ Overview  
I was admitted to the Pioneer Academics Research Program and conducted computer engineering research under Professor Seda Ogrenci of Northwestern University. Through weekly one-on-one mentorship, I developed an independent research project exploring decentralized learning in hardware neural networks.

I designed and simulated networks of variable resistors capable of learning without a central processor, inspired by physics-driven contrastive learning schemes proposed by Sam Dillavou et al. at UPenn. Using Python and circuit simulation tools, I modeled resistor networks as analog neural networks and implemented decentralized optimization to replace traditional gradient descent that is typically handled by a centralized processor. I evaluated the efficiency, scalability, and robustness across different network architectures, demonstrating that these physical systems can approximate machine learning algorithms. My work culminated in a 20-page thesis, and I presented my findings to postdoctoral researcher Sam Dillavou.


<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" width="50%" style="border: none;">
      <img src="images/pioneer/resistor-network.png" width="100%"><br>
      <em>Resistor network constructed in circuit simulation software</em>
    </td>
    <td align="center" width="50%" style="border: none;">
      <img src="images/pioneer/training-circuits.png" width="100%"><br>
      <em>Training and reinforcement learning circuits</em>
    </td>
  </tr>
</table>

---

## **Rapid Concussion Test & Vision Rehabilitation Research — Padula Institute for Vision Rehabilitation**

**Flask • Python • JavaScript • HTML/CSS • Visual Neuroscience**

🔗 **Repo:** https://github.com/hawkbsilleee/Rapid-Concussion-Test

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" width="33%" style="border: none;">
      <img src="images/padula/start.png" width="100%"><br>
      <em>Uses can specify the type of visual test to run</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/padula/middle.png" width="100%"><br>
      <em>This is what a contrast test looks like; line contrast is increased over time in a randomly-chosen quadrant</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/padula/end.png" width="100%"><br>
      <em>Result are provided to the user at the end, measuring their reaction time and accuracy</em>
    </td>
  </tr>
</table>

### ⭐ Overview  
During my summer internship at the Padula Institute for Vision Rehabilitation (June–August 2023), I worked as a Research Intern focusing on vision rehabilitation for patients with neurological conditions. I conducted clinical visual color field tests on patients with traumatic brain injury (TBI), Lyme disease, cerebral palsy, and other neurological conditions, while also designing and conducting experimental research to assess the impact of TBI and Lyme disease on constricting the visual peripheral system.

### 🔧 Technical Contributions  
- **Developed Rapid Concussion Test**, a Flask-based web application hosting a prototype rapid concussion assessment tool using varying sine wave patterns. The application presents two testing modes (thickness test and contrast test) that display sinusoidal patterns varying in thickness or contrast over time, with users focusing on a central target that flashes random numbers.
- Implemented **real-time visual pattern detection** with JavaScript and CSS animations, enabling users to identify and click on the quadrant where they detect the sine wave pattern.
- Designed **experimental research study protocols** to assess visual peripheral system constriction in patients with TBI and Lyme disease, contributing to ongoing research at the institute.
- Ran **clinical visual color field tests** on patients with various neurological conditions, collecting data to support vision rehabilitation research.

---

<br>

# 🏎️ Project Teams

## **Brown Formula Racing — DRS Algorithms Engineer**  

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" width="33%" style="border: none;">
      <img src="images/drs/drs_analysis6.png" width="100%"><br>
      <em>Algorithm's predicted activations based on sensing data</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/drs/simulator.png" width="100%"><br>
      <em>Applied Racing Dynamics Lab Simulator</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/drs/actuator-cad.png" width="100%"><br>
      <em>DRS linear actuator CAD</em>
    </td>
  </tr>
</table>

**C++ • MoTeC ECU • Real-Time Systems**  

I work on the algorithms team of the DRS subteam. My goal is to use data from the onboard sensors (brake sensor and IMU) to determine the optimal time to open and close the DRS flap of the car. 

### 🔧 Contributions  
- Writing **real-time C++ control algorithms** on MoTeC's ECU.
- Use Applied Racing Dynamics lab simulator to simulate the car and determine the validation dataset

---

## **Full Stack at Brown — Software Engineer**  

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" style="border: none;">
      <img src="images/fullstack/landing-page.png" width="70%"><br>
      <em>Landing page of the website we developed for Project BRYTE</em>
    </td>
  </tr>
</table>

**React • TypeScript • Cosmic CMS • Full Stack Development**  

### ⭐ Overview  
Full Stack is club of students who build websites for non-profits, student organizations, and research groups. This semester I helped build a website for Project BRYTE, which matches Brown student tutors with K-12 refugee students in Providence.

### 🔧 Contributions  
- Integrated TypeScript backend with CosmicCMS so that our client could easily edit the content of the website.  
- Programmed React pages that dynamically update content from CosmicCMS backend.
- Built contact, home, and FAQ pages with React and Radix UI components.

---

## **Cornell Assistive Technologies — Software & Electrical Engineer** 

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" width="33%" style="border: none;">
      <img src="images/cornellassist/joystick-hack.png" width="100%"><br>
      <em>"Hacking" a joystick to better accommodate the needs of its owner</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/cornellassist/tactile-blocks.png" width="100%"><br>
      <em>3D-printed tactile coding blocks</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/cornellassist/pcb-watch.png" width="100%"><br>
      <em>Custom PCB for the sensory-overload watch</em>
    </td>
  </tr>
</table>

**Python • C++ • Arduino • ML • Embedded Systems • CAD • PCB Design**

### ⭐ Overview
As a member of the Cornell Assistive Technologies Project Team during my freshman year, I worked on 1) developing a smartwatch to detect sensory overloads in advance, 2) an inexpensive EEG-controlled electric wheelchair for paralyzed individuals, and 3) tactile coding blocks which are 3D-printed physical pieces that teach foundational programming concepts to the visually-impaired. I also volunteered at toy adapting events to modify toys for children with disabilities in Ithaca.

### 🔧 Contributions  
- Programmed ML algorithms to detect sensory overloads and map brainwaves to movement in Python and C++
- Designed and fabricated housing parts for the sensory overload watch using CAD and 3D printers. 
- Designed PCB for the watch using Fusion360 and KiCAD and soldered electrical components of the device onto the board.
- Designed and 3D printed tactile coding blocks.

---

## **Project Nibbler — Avenues Tiger Works R&D Team, Intern**

<table>
  <tr>
    <td align="center">
      <img src="images/nibbler/group.png" width="70%"><br>
      <em>The Nibbler team</em>
    </td>
  </tr>
</table>

**CAD • 3D Printing • Laser Cutting • Python • UV-Activated Resin • Recycling Systems**

🔗 **Article:** https://www.avenues.org/world-of-avenues/the-nibbler-project2         
🔗 **Repo:** https://github.com/hawkbsilleee/Project-Nibbler
🔗 **NASA Award Article:** https://www.nasa.gov/directorates/stmd/prizes-challenges-crowdsourcing-program/center-of-excellence-for-collaborative-innovation-coeci/coeci-news/nasa-names-winners-in-waste-to-base-materials-challenge/
 
**🏆 Recognition:** Won Best in Class in NASA's Waste to Base Materials Challenge, filed US Patent (Application No.: 17/316,887)

### ⭐ Overview  
As an intern with the Avenues Tiger Works R&D Team, I worked on Project Nibbler, developing a household waste converter in collaboration with colleagues in Brazil and across the US. I led the New York team, coordinating with international team members to advance this sustainability initiative.

The Nibbler Machine is capable of building 3D objects like a cup from assembling "pucks" that are made of ground-up recycled materials. This process is made up of three phases: 
1) First, the user feeds trash into the top of the machine, where it is grinded-down into small pieces via a custom made shredder. 
2) Second, the smaller pieces of trash are filled into injection molds in which they are compressed with UV-activate resign to form uniform pucks. 
3) Finally, these pucks are fed into a hoper, which is driven by a stepper motor, outputting the pucks one at a time to the pick-and-place nozzle which assembles these pucks into objects. The pick-and-place machine dips each puck into a reservoir of UV-activated resin before placing them into the build plate, so that when the object is assembled, it solidifies upon exposure to machine's the UV light path. 

### 🔧 Contributions  
- Led the NY team: delegated tasks, applied for grants, recruited members, and coordinated with international team members in Brazil and across the US
- Designed components for the machine in Computer-Aided Design (CAD) and fabricated parts via laser cutting and 3D printing, such as an automatic puck dispenser and an enclosure for mounting UV lights
- Experimented with binders such as UV-activated resin and researched recycling system inefficiencies
- Developed custom slicing software in Python for generating custom 3D printer tool paths

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" width="33%" style="border: none;">
      <img src="images/nibbler/ag6ela.gif" width="100%"><br>
      <em>The Nibbler machine printing</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/nibbler/nibbler_image_1.jpeg" width="100%"><br>
      <em>Printed flower pot</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/nibbler/shredder.jpeg" width="100%"><br>
      <em>Shredder shredding cardboard</em>
    </td>
  </tr>
</table>

---

## **Avenues Robotics (FTC) — President**  

<table>
  <tr>
    <td align="center">
      <img src="images/robotics/IMG_7257.JPG" width="70%"><br>
      <em>Avenues Robotics team at competition</em>
    </td>
  </tr>
</table>

**CAD • Fabrication • Java • Computer Vision**  

🔗 **CV Repo:** https://github.com/hawkbsilleee/FTC-CV         
🔗 **Power-draw Analysis Repo:** https://github.com/hawkbsilleee/FTC-Data-logging

**🏆 Recognition:** Won NYC Championships, advanced to the **FIRST Tech Challenge World Championships** (Top 1% of 7,000 teams); Won several awards at competition including Inspire, Think, Motivate, Connect, and Design

### ⭐ Highlights  
- Led school's largest engineering club (**90+ members**), mentoring **8 FTC teams** in CAD, fabrication, and Java programming.  
- Designed the robot using Fusion360 and Onshape; fabricated components via 3D-printing, laser-cutting, and CNC-milling. 
- Programmed computer-vision algorithm in Java to detect the color of game-elements the robot collected in constant time; programmed data-logging script in Java to analyze the intake speed under different drivetrain power draws. 
- Competed at the **FIRST Tech Challenge World Championships** (Top 1% of 7,000 teams) and placed 1st overall at NYC Championships.  
- Taught **40+ workshops** for low-income students and raised **$4K** to start an FIRST Lego Robotics (FLL) team for the Hudson Guild, a local community center; coached this FLL team (the Hudson Guild heat) during my senior year

<table>
  <tr style="border: none;">
    <td align="center" width="33%" style="border: none;">
      <img src="images/robotics/IMG_3632.jpeg" width="100%"><br>
      <em>Robot in action</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/robotics/stress-test.png" width="900"><br>
      <em>Stress testing our CNC-milled aluminum side plates in Fusion 360</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/robotics/intake.png" width="900"><br>
      <em>Analyzed intake speed during maximum drivetrain power-draw in order to optimize intake capabilities</em>
    </td>
  </tr>
  <tr style="border: none;">
    <td align="center" width="25%" style="border: none;">
        <img src="images/robotics/odometry.png" width="100%"><br>
        <em>3 dead wheels (odometry pods) track the robot's position. We modelled motor dynamics to calculate voltage output for a target velocity. With a PID controller to correct position, our robot could follow paths accurately autonomously.</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/robotics/full-render.png" width="100%"><br>
      <em>I helped design the robot fully in Onshape and rendered it with Fusion 360</em>
    </td>
    <td align="center" width="33%" style="border: none;">
        <img src="images/robotics/april-tag.png" width="100%"><br>
        <em>We used computer vision (OpenCV) to detect in game elements. We also re-localized using the backdrop april tags by transforming the displacement about the heading of the robot.</em>
    </td>
  </tr>
</table>

---

<br>

# 🧪 Independent Projects

## **Tick Spotter — Computer Vision Project**  

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" style="border: none;">
      <img src="images/tickSpotter/landing-page.png" width="70%"><br>
      <em>Example output from the CNN</em>
    </td>
  </tr>
</table>

**Python • TensorFlow • Keras • YOLO • OpenCV**

🔗 Repo: <https://github.com/hawkbsilleee/Tick-Spotter-AI>  

### ⭐ Overview  
A multi-class tick (the insect) identification system trained on a 15,000-image dataset.

### 🔧 Technical Contributions  
- Trained CNN + object detection models (**YOLO, R-CNN, VGG16, ResNet50**) with transfer learning and regularization.  
- Automated dataset collection via **Selenium web scraping** and API polling insect databases.  
- Implemented augmentation (rotation, hue thresholding) and optimized training using early stopping + LR scheduling.  
- Achieved **96% classification accuracy**.

---

## **Red Retriever — Full-Stack iOS Lost-and-Found App**  

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" width="33%" style="border: none;">
      <img src="images/redRetriever/393470813-544ebe78-acac-4937-88ad-41f1a336d94b.jpeg" width="100%"><br>
      <em>Lost item feed</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/redRetriever/393470833-4d8c281c-3b66-4a58-98b0-ad710d9bdbf2.jpeg" width="100%"><br>
      <em>Found item posting</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/redRetriever/393473377-41d711dd-1598-466f-9b13-18bf31fc6be3.png" width="100%"><br>
      <em>Leaderboard feature</em>
    </td>
  </tr>
</table>

**Swift • Flask • SQL • REST API • NLP • Figma**

🔗 Repo: <https://github.com/hawkbsilleee/RedRetriever>  

### ⭐ Overview  
Competed in an iOS development hackathon, creating a lost-and-found platform for **20,000+ Cornell students** to help locate lost items on campus.

### 🔧 Technical Contributions  
- Implemented secure login with **Google OAuth**, and RESTful API backend with item posting, matching, and leaderboard features.  
- Built frontend pages with UIKit to display leaderboards, lost item requests, and found item posts.  

---

## **MintBox — Co-Founder & President**

<table style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <td align="center" width="33%" style="border: none;">
      <img src="images/mintbox/kithomesquare.png" width="100%"><br>
      <em>The Baby Sprout gardening kit</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/mintbox/plasquare.png" width="100%"><br>
      <em>Self-watering gardening planter</em>
    </td>
    <td align="center" width="33%" style="border: none;">
      <img src="images/mintbox/caddingplanter.png" width="100%"><br>
      <em>CAD design for the self-watering gardening planter</em>
    </td>
  </tr>
</table>

🔗 **Website:** https://www.mintboxny.com

**🏆 Recognition:** Won the SeedBank entrepreneurship grant twice and the Lawrenceville Welles Award

### ⭐ Overview  
I co-founded and lead MintBox, a project aimed at democratizing access to fresh produce in NYC through sustainable and easy-to-use gardening products. Since April 2020, MintBox has raised over **$2.5K** from selling gardening kits online and in-person at farmers' markets.

### 🔧 Contributions  
- Co-founded MintBox to make fresh produce accessible through sustainable gardening solutions
- Raised over **$2.5K** from selling gardening kits online and in-person at farmers' markets
- Donated profits to build indoor gardening planters for the Hudson Guild Fulton Center
- Held workshops to teach plant science and nutrition to elementary school students
- Donated gardening kits to the Covenant House youth homeless shelters across NYC

---

---

<br>

# 📫 Contact

<p align="center">
  <strong>Email:</strong> <a href="mailto:ethan_seiz@brown.edu">ethan_seiz@brown.edu</a><br>
  <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/ethan-seiz" target="_blank">linkedin.com/in/ethan-seiz</a><br>
  <strong>GitHub:</strong> <a href="https://github.com/hawkbsilleee" target="_blank">github.com/hawkbsilleee</a>
</p>

<p align="center">
  <em>Thanks for stopping by — feel free to reach out!</em>
</p>

