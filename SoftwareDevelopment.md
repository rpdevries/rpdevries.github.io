---
layout: page
title: Software Development
permalink: /01_SoftwareDeveloper/
description: Software development to assist paleontological research.
---

## *FossilScope*

### Fossil Restoration

For over 200 years, paleontologists have been restoring the skeletons of extinct vertebrates based on fossil bones in varying states of preservation. These composite restorations involve the scaling of bones to accommodate specimens of different sizes, the completion of partial elements, and the restoration of missing elements. Completed skeletal restorations have been presented as 2D images in scientific reports (Fig 1a) or as 3D skeletal mounts in museum displays (Fig 1b). 

In the last 50 years, skeletal mounts based on fragile fossil material have been largely replaced by cast skeletons with internal mounting, and in the last 20 years, advances in imaging (CT scans, laser surface scans, stereophotogrammetry) have allowed for the manipulation and restoration of skeletons as 3D digital models. 

However, neither historical nor recent skeletal restoration methods adequately document the myriad decisions underlying the final skeletal restoration.

| <img src="/assets/Marsh_Stegosaurus.png" alt="Skeletal reconstruction of Stegosaurus ungulatus by O.C. Marsh." width=380px> | <img src="/assets/Dromaeosaurus_Manus.png" alt="Dromaeosaurus manus reconstruction." width=80px> |
|:--:|:--:|
| <sup> **Fig 1a.** Skeletal reconstruction of *Stegosaurus ungulatus* by O.C. Marsh. </sup> | <sup> **Fig 1b.** *Dromaeosaurus* manus reconstruction. </sup> |

### *FossilScope*

<img align=right src="/assets/Digital_Restoration_Process.png" alt="Steps of the digital restoration process." width=230px>

Three-dimensional digital restoration is central to paleontological research today, facilitated by advances in both hardware and software. The workflow for digital restoration of a fossil is as follows (right):

1. Digitization via CT, surface scanning, or photogrammetry.
2. Delineation through thresholding or masking.
3. Brittle or plastic retrodeformation to repair fractures and warps. 
4. Reconstruction of missing parts and smoothing to repair bone. 
5. Video animation of the restoration process.

More details on digital restoration [**here**](https://doi.org/10.3389/feart.2022.833379).

## Replace this link when live!
[**here**](https://doi.org/10.3389/feart.2022.833379)

Each of these steps can involve numerous decisions and manipulations that are largely undocumented and difficult to reproduce. The digital files for fossil specimens and their manipulations during the restoration process need to be efficiently linked to their representation in the final digital model.

We introduce *FossilScope*, a free application that will allow the user to interact with a 3D digital mesh skeleton and its associated restoration data quickly and intuitively. On a digital skeletal restoration, one may click to select a bone (e.g., femur, Fig 2) or click-drag to select a bone complex (e.g., skull) to access relevant information: descriptions and images of the fossil specimens involved, an outline of the restorative steps taken, or a video that animates the restorative process. *FossilScope* is a new and intuitive way to document and bring transparency to the process of digital restoration.

| <img src="/assets/FossilScope_MainFig.png" alt="Click-to-select in FossilScope." width=1000px> |
|:--:|
| <sup> **Fig 2.** Clicking to select a bone (left femur of *Spinosaurus*) for inspection in *FossilScope*. </sup> |
