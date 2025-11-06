---
title: "Estimation of relative position between objects for robotic insertion of LDOs using classification learning methods"
collection: publications
type: "Thesis"
permalink: /publication/msc-thesis
excerpt: 'M.Sc Thesis completed at the Technion - Israel Institute of Technology, 2024.'
date: 2024-05-19
paperurl: "/files/thesis.pdf"
citation: Hazan, Sher, Anath Fischer, and Technion - Israel Institute of Technology. Faculty of Mechanical Engineering degree granting institution. “Estimation of Relative Position between Objects for Robotic Insertion of LDOs Using Classification Learning Methods / Sher Hazan ; [Supervision - Anath Fisher].” Technion - Israel Institute of Technology, 2024. Web.

---

## Abstract

This work proposes a robust method for evaluating the relative position between both rigid and
non-rigid objects in real-time assembly tasks using computer vision and learning methods.
The proposed approach fuses depth data with RGB images using a classification neural network (CNN) architecture. Several CNNs were tested and compared, including early, late, and
parallel RGB-D fusion architectures.

In order to use classification CNN on a continuous problem, the scene space was divided
into sub-areas as classes. The classification resulted in the prediction of probabilities of each
class. Subsequently, these probabilities were combined using a linear interpolation technique,
resulting in an accurate evaluation of the relative position between the objects.

For the validation process of the proposed method, three Peg-In-Hole tasks were defined,
varying in their complexity. The tasks included: (1) a classic PID with rigid objects; (2) wiring
a 1 mm thick non-rigid wire to a rigid connector; and (3) wiring a non-rigid medical pipe to a
non-rigid connector.

An RGB-D realistic database was created for each task’s CNN. The scenes were captured
using a 3D camera in a real robotic cell at the Technion. Then, pre-processing and augmentation
techniques were applied to the data. Finally, the CNNs were trained separately using the same
setup and hyper-parameters to ensure comparable results.

The method was evaluated by embedding and testing it in the robotic insertion process based
on the following iterative stages:
• Predicting the position probabilities.
• Calculating the relative position between the peg and the hole.
• Correcting the peg position.

Once the peg is aligned with the hole, the insertion process is performed. Furthermore, the
real-world applicability and generalization of the method were validated by embedding it in an
industrial-grade robotic cell without additional training.

The feasibility of the proposed method was demonstrated in several tasks, showing an automatic process with high performance. Consequently, it fits well into the industrial environment
for tasks involving the insertion of linear deformable objects (LDO) within a robotic cell.
