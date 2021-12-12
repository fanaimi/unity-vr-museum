# unity-vr-museum
developed during a workshop at CS

* package manager > gear icon >  advanced projects settings > enable preview packages 
* import XR INTERACTION TOOLKIT
* under XR interaction toolkit > import DEFAULT INPUT ACTIONS
* XR PLUG-IN MANAGEMENT
    * Project settings > XR plugin management > PC> oculus and Windows mixed reality
    * Project settings > XR plugin management > ANDROID > oculus
* create an action based RIG
* add Default Input Actions for LEFT and RIGHT controllers
* on XR-rig > add component > Input Action Manager
    * under Input Action Manager > Action assets > size: 1 - Element 0: XRI Default Input Actions
* LeftHand Controller > remove component "XR Controller"
    *under Assets > samples > XR Interaction toolkit > v.v.v > Default Input actions, drag "" into LeftHand Controller
* repeat for RightHand Controller
