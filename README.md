# Overview 
This is repository is dedicated to upgrading Trossen Robotics ALOHA v1 to ALOHA v2. Bimanual manipulation is an important part of robotics for development of humanoid robots. An enhanced Low cost Open-source HArdware (ALOHA) offers hardware capable of performing bimanual manipulation tasks with a precision of 5-8mm with the ability to collect data via real-time teleoperation. Because of its affordable price many labs  all over the world have bought it from Trossen robotics. But soon after that the team developing ALOHA has released ALOHA v2 to mitigate couple problems that now ALOHA v1 had. The upgrades include new cameras, changed frame, gravity compensation supports for the teleoperator side leader robots and redesigned grippers for low-friction to reduce latency. In this repository you can find different ways you can upgrade the ALOHA v1, the material bill for each of the parts and a zip file that  includes . 

# Details 
The upgrade for ALOHA v2 can be done in 3 stages and these stages are independent of each other and can be done in any order based on the requirement and budget. All the items required for the upgrade are mentioned in the ALOHA 2 upgrade kit excel file the prices are dated as of 10/31/2024. All the cad models required for 3d printing are present in the aloha2 cad models directory.

Stage I - Camera upgrades : This upgrade can be done simply by 3d printing the camera mounts found in the cad models directory and replacing the existing logitech c922x Pro webcams to the new Realsense d405 depth cameras. Optionally if the PC connected to ALOHA doesn't have enough USB ports a 4 port USB Interface PCIe card can installed to the cpu since the cameras need to be connected directly to the motherboard and not the usb hub. This upgrade offers the ability to collect depth, point cloud and voxels data with some processing. 

Stage II - Gripper upgrades : This is the most expensive upgrade in ALOHA 2. This step requires precise 3d prints of both the follower and leader gripper, for its need to be low friction. To build the grippers follow the steps mentioned in the Google's ALOHA 2 Build Instrucitons google doc. And the gripper motors are replaced with the new dynamixel XC430-W150 motors.This upgrade offers better latency during teleoperation. 

Stage III - frame upgrade : This is the most time taking upgrade. This can be done in two approaches 1. Money efficient, 2. Time efficient.  For Money efficient approach we reuse the frame from ALOHA 1, by cutting the frame in required dimensions, by choosing this method you can save $205(USD). In depth tutorial for this will be uploaded soon. For the time efficient upgrade the extrusion bars mentioned in the ALOHA2 upgrade kit can be bought and install it using the procedure mentioned in the Google's ALOHA2 Build Instructions doc. This upgrade offers better frame stability and much better gravity compensation compared to ALOHA v1.

# Notice
All the cad models and the work related to the upgrade belong to the Google'2 ALOHA 2 team. The work in this repository only include a condensed and neat approach to upgrade ALOHA v1 to ALOHA v2 considering both cost and time efficient approaches,  and provide all resources required for the upgrade in one place. 