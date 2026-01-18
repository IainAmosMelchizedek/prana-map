PranaMap
An Interactive Energy Healing Intake System for Reiki Practitioners

Overview:
PranaMap is a proof of concept application that demonstrates how technology can enhance the practice of Reiki and energy healing. This project showcases an interactive 3D body visualization with chakra mapping, designed to facilitate communication between patients and practitioners before healing sessions begin.
This is not a finished product. It is a functional prototype intended to provoke thought and inspire ideas within the energy healing community about what tools could be built to support their practice.

Purpose:
The goal of PranaMap is to answer a simple question: What if patients could visually communicate their energetic concerns before a session even begins?
By providing a proof of concept, this project aims to:

Demonstrate possibilities — Show practitioners what technology can offer their field
Spark conversation — Invite feedback and ideas for features that would genuinely help
Serve as a foundation — Provide a baseline that can be customized and extended for specific practice needs

If you're a Reiki practitioner and this resonates with you — or if it inspires an entirely different idea — that's exactly the point.

Features:
Current Implementation

3D Human Figure — Rotatable, zoomable anatomical model created with MakeHuman and rendered via Three.js
Seven Primary Chakras — Interactive energy centers positioned anatomically with traditional colors (Root to Crown)
Chakra Selection — Click on the 3D model or sidebar list to select and view chakra details
Intensity Tracking — Slider to indicate the severity of felt imbalance (1-10 scale)
Notes Field — Free-text area for patients to describe their experience
Session Summary — Real-time summary of all marked areas of concern
Lotus Backdrop — Subtle sacred geometry reinforcing the healing context
Acupuncture Correlations — Each chakra includes corresponding acupuncture point references based on bioelectric field research

Planned Features (Roadmap):

Patient Intake Form — Capture patient information with data export capabilities
Session History — View and compare previous intake submissions over time
Body Marking System — Allow patients to click anywhere on the body to mark pain or discomfort locations (not just chakras)
Data Export — Export session data to spreadsheet format (CSV/Excel) for practitioner records
Practitioner Dashboard — Backend view for practitioners to review patient submissions before sessions


Scientific Foundation:
This project draws inspiration from published research on bioelectric field measurements in Reiki healing, particularly:

Kuman, M. (2017). "Measuring Reiki Healing - Mystery, Placebo, or Real Energy Healing?" Acupuncture & Electro-Therapeutics Research, 42, 163-173.

Key findings incorporated into this design:

Energy imbalance can be detected at specific acupuncture points years before physical symptoms appear
The correlation between chakra locations and measurable acupuncture meridian points
The toroidal (donut-shaped) nature of the human electromagnetic field


Technology Stack:
ComponentTechnology3D RenderingThree.js (r128)Human ModelMakeHuman → Blender → GLBFrontendVanilla HTML, CSS, JavaScriptHostingGitHub Pages

Installation & Usage:
View Live Demo
Visit: https://iainamosmelchizedek.github.io/prana-map/
Run Locally

Clone the repository:

bash   git clone https://github.com/IainAmosMelchizedek/prana-map.git

Open index.html in a modern web browser
No build process or dependencies required — it runs entirely client-side


For Reiki Practitioners:
This project is an invitation.
If you see potential here — whether it's exactly this tool, a variation of it, or something entirely different — I'd love to hear from you. The intersection of technology and energy healing is largely unexplored, and the people who understand what practitioners actually need are practitioners themselves.
Questions to consider:

What information do you wish you had before a patient arrives?
How do you currently track patient progress across sessions?
What repetitive tasks could technology handle for you?
What would make your practice more effective or efficient?


Project Structure:
prana-map/
├── index.html              # Main application (HTML, CSS, JS)
├── pranamap-figure.glb     # 3D human model
├── LICENSE                 # Apache 2.0 License
└── README.md               # This file

Contributing:
This is an open proof of concept. Ideas, feedback, and contributions are welcome.
If you're a practitioner with insights, or a developer interested in this space, feel free to:

Open an issue with suggestions or feedback
Fork the repository and experiment
Reach out directly


License:
This project is licensed under the Apache 2.0 License. See LICENSE for details.

Acknowledgments:
MakeHuman Community — Open source human modeling software
Three.js — 3D rendering library
Dr. Maria Kuman — Research on bioelectric field measurements in energy healing


