# Haptics-Illusion-in-Mixed-Reality
## Background ##
Head-mounted mixed-reality devices can overlay realistic 3D content onto the
physical surfaces, enabling a wealth of interactive possibilities with virtual content overlayed to
physical surfaces. Current-generation commercial mixed reality devices, like Microsoft HoloLens or
Meta 2, are primarily driven by in-air hand gesturing, gaze and voice. While convenient, these
indirect input modalities are not particularly precise or rapid and cause fatigue. For example, typing
on virtual keyboard in air is hard and error-prone. Instead overlaying 3D keyboard on a physical
surface provides natural haptic response to users.
## goals ##
Spatial understanding of physical surfaces, and precise virtual content overlays on the surface
## deliverables ##
* Implement software for spatial understanding of physical surfaces
* Overlay 3D virtual content (e.g. buttons of keyboard) at precise location
* Analyze haptic illusion for the virtual content
## system blocks ##
the system contains two blocks. One is hardware access block, which is responsible to handling all the interaction with MR headset
including but not limited to get sensing and location info form the headset,  actuating the headset,  and rendering objects on the view of headset
the other one is model calculation block, which keeps calculaing and maintaining the platfrom and keybroad 3D model within the space, also implement the logic 
of deciding whether the user's finger made a touch with some keybroad in the platform and determine which exactly key it is. it also make use of the functions 
provided by the hardware access block to interact with the headset.
![image](https://user-images.githubusercontent.com/32824406/194563808-d5602f25-cc65-4123-b778-055dd42049c8.png)
## hardware and software requirement ##
a microsoft hololen MR headset, and PCs(the project may require developing under Windows, currently the only two PCs with Windows OS are in model group, but the hardware group may use computers in the school)
## team member and responsibilities ##
Shiqin Shen and Exiang Zhou are in the model group
Jiahao Zhao and Huiyu Tao are in the hardware group
each group is also responsible to writing their own sectors in the final paper.
and since the work involved in model group is heavier than hardware group, the hardware group is also responsiable for integrating the program 
and summarizing and organizing the paper.
## project timeline ##
we would like to finishing everything before the December(by the time we are expecting to get busy with perparing for the finals), so excluding one week for perparing the midterm, we only have __7 weeks__ or so to finish the project. And we like to have __2 weeks__ to write the paper and ready for the presentation.
Program integration and whole system debuging would need other __1.5 weeks__(we should have frequent communications between two group, about the input and 
output of APIs the unit and coordinate system we use in the program, along with other integrating issues, so as to minimum the future trouble we have in the integration phase). for developing the core functionality of each block, we will only have __3 weeks__ to do so. we leave the rest of __0.5 weeks__ in case of any unexpectations.
## references ##
R. Xiao, J. Schwarz, N. Throm, A. D. Wilson and H. Benko, "MRTouch: Adding Touch Input to Head-Mounted Mixed Reality," in IEEE Transactions on Visualization and Computer Graphics, vol. 24, no. 4, pp. 1653-1660, April 2018, doi: 10.1109/TVCG.2018.2794222.





