Medical Image Annotation Portfolio

A collection of my manual annotations and segmentation work on CT and X-ray datasets.
This portfolio demonstrates hands-on experience with:

✔ Lung segmentation on CT slices (CVAT)

✔ Bounding box annotations on X-ray images

✔ Comparison of my annotations vs. RSNA ground truth

✔ Understanding of radiological anatomy & pathology

✔ Preparing datasets for AI model training (COCO format)


Project Structure

medical_image_annotation_portfolio/
│
├── CT_segmentations/
│   ├── annotated_image_01.png
│   ├── annotated_image_02.png
│   └── ...
│
├── Xray_QA/
│   ├── image01_qa.png
│   ├── image02_qa.png
│   ├── ...
│
└── README.md


CT Lung Segmentations (CVAT)

Below are examples of manually segmented lung fields on CT axial slices.

Each image includes green mask  my manual segmentation and labels which i have used.
Sample images are stored in:
/CT_segmentations/

X-ray Bounding Box Annotations (RSNA)
I performed bounding box QA on pneumonia detection X-rays.
Each image shows:
Green boxes → my corrections
Red boxes → original RSNA labels

Samples are in:
/Xray_QA/

Skills Demonstrated
Manual segmentation (polygons)
Diagnostic image interpretation
Bounding box QA
Annotation quality control
Using CVAT for medical imaging tasks
Preparing datasets for AI model training

Quality Assurance Using Python

For the chest X-ray bounding box annotations, I developed a small Python script to:

load original X-ray images
load RSNA ground-truth annotations (COCO format)
overlay green boxes (my annotations)
overlay red boxes (ground truth)
visualize mismatches and validate annotation accuracy


About Me

Radiology technologist focused on diagnostic imaging and AI in radiology.
Experience with CT, X-ray, MRI, and medical image annotation workflows.




