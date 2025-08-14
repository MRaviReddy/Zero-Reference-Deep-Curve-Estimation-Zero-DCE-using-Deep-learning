Zero-DCE 

Proposed by Guo et al. (CVPR 2020), Zero-DCE estimates pixel-wise, image-specific enhancement curves using a lightweight CNN (DCE-Net). 

No reference (paired/unpaired) data is required. 

Uses non-reference loss functions: spatial consistency, exposure control, color constancy, and illumination smoothness. 

Real-time performance with ~0.0025s/image on GPU. 

 APPLICATION TO LOW LIGHT IMAGE ENHANCEMENT AND OBJECT DETECTION  

Zero-Reference Deep Curve Estimation (Zero-DCE) has emerged as a robust solution for low-light image enhancement, particularly in applications demanding real-time visual understanding under suboptimal lighting. Its zero-reference training approach removes the dependency on paired datasets, enhancing generalization across diverse environments. This makes it highly suitable for deployment on resource-constrained edge devices such as NVIDIA Jetson Nano and Raspberry Pi, which are often used in mobile or embedded systems. In the context of assistive technologies for blind and visually impaired (BVI) individuals, Zero-DCE significantly improves the clarity and contrast of images captured in dimly lit environments—such as streets at night, tunnels, or indoor areas during power outages. When integrated with object detection models like YOLOv8 or Faster R-CNN, it enhances detection accuracy and enables more reliable real-time feedback via audio or haptic modalities. Additionally, Zero-DCE finds critical relevance in defence and surveillance scenarios where operations are conducted under extreme low-light or covert conditions. It enables passive visual enhancement for drones, night patrols, and reconnaissance missions without the need for infrared lighting, preserving operational stealth. Applications range from intruder detection at borders to terrain analysis in urban warfare zones and post-conflict rescue. Compared to methods like EnlightenGAN, Zero-DCE offers lower computational cost, faster processing, and better integration with object detection pipelines, establishing itself as a preferred choice for safety-critical vision systems in both civilian and military deployments. 
