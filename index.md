---
layout: default
---

## Overview

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

## Features

Features for our alpha release include:

* [Bone and nerve selection](https://youtu.be/qJFSeH6n0QE?t=1m41s): users can identify a bone or nerve by clicking on it. FastSlice will fill in the rest.

Features for our beta release include:

* [Multi-slice support](https://www.youtube.com/watch?v=DYjxMnqFd-Y): users can click once and have their annotation marked across dozens of slices.
* [Full-limb support](https://www.youtube.com/watch?v=RRTbvi0riAI): in addition to selecting just bone or nerve, users can select an entire limb by changing a few values. 

Features for our omega release include:
* [A new UI](https://youtu.be/TSEpF9ZIL9Q?t=9s): users can toggle quickly between tissue mode and bone/nerve mode, and can click the "Visit Website" button for quick access to documentation.
* [Outline preview](https://youtu.be/TSEpF9ZIL9Q?t=26s): users can preview what an annotation will look like before committing to it, eliminating the need to click the undo button.
* Smoother edges: an enhanced annotation algorithm makes outlines less choppy.
* [Status bar](https://youtu.be/TSEpF9ZIL9Q?t=1m15s): users can see annotation progress when multi-slice support is enabled.
* An output console: users are informed whenever an error occurs.

## Installation

To start using FastSlice, follow the [installation instructions](https://fastslice.github.io/install).

## Contribute

We welcome pull requests on the [FastSlice repository](https://github.com/FastSlice/FastSlice).