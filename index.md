---
layout: default
---

# Overview

Prosthetics are a product in high demand. With an estimated 70,000 prosthetics designed every year, each ranging from $5,000 to $50,000, one would expect a single prosthetic to last their owner a long time. In reality, prosthetics get replaced every 3-5 years.

Why so short a lifetime? Because the current prosthetic design process is riddled with errors:

1. **It's imprecise**. Most prosthetists physically touch amputated limbs to develop a molding.
2. **It's laborious**. Patients have to wait weeks or months to receive their prosthetic.
3. **It's ineffective**. Even when patients receive their limb, it may become uncomfortable due to changes in the body's shape and size.

## A Better Way

A new design process being developed by researchers at the University of Michigan is trying to fix these problems by creating a reconfigurable prosthetic socket. The benefits are numerous:
  
* **Greater comfort**. Prosthetics can be adjusted according to how a patient's body changes.
* **Lower cost**. Longer prosthetic lifetimes and fewer visits to the prosthetist makes for a happier patient.
* **Faster delivery time**. A computerized design process gets patients their prosthetics quicker than ever.

## 3DSlicer and FastSlice

At the heart of the design process for the reconfigurable prosthetic socket is [3DSlicer](https://www.slicer.org/), an open-source software program that helps turn limb scans into precise 3D models. These 3D models are then used to help fit the patient with a custom prosthetic socket.

The problem with 3DSlicer is that it's laborious: researchers must manually mark off nerves and bones on thousands of cross-sections of a given limb. This annotation process alone takes 5-6 hours.

The solution? FastSlice, an extension custom-built for 3DSlicer and the prosthetic design process. Using FastSlice, prosthetists can quickly select nerve and bone in patient CT scans, reducing the time needed to complete the annotation process by 80%.

To view a demonstration, watch [this YouTube video](https://youtu.be/qJFSeH6n0QE).