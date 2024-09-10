
[Open CASCADE Technology: Visualization](https://dev.opencascade.org/doc/overview/html/occt_user_guides__visualization.html)

# Introduction


separation of 
- **want to display and select:** the data which stores the geometry and topology of the entities
- **what you see and select:** its **presentation** and **selection**


## Key concepts and packages in visualization

schematic overview of the relations between the key concepts and packages
![[Key concepts and packages in visualization.png]]

**Application Interactive Services** (AIS)

- create links between an application GUI viewer and the **packages** used to manage selection and presentation
- makes management of these functionalities in 3D more intuitive and consequently, more transparent

**packages** are used to display 3D objects as well as 2D objects:
- _AIS_;
- _StdPrs_;
- _Prs3d_;
- _PrsMgr_;
- _V3d_;
- _Graphic3d_.

 **Interactive Object** (Presentable Object and Selectable Objects)
 - a displayable and selectable entity
 - represents an element from the application data.

==selection filters==


==Sensitive Primitive==


==Presentable Object.==


 **User's Guide**
- If the 3D services proposed in AIS meet your requirements, you need only read chapter 3 [AIS: Application Interactive Services](https://dev.opencascade.org/doc/overview/html/occt_user_guides__visualization.html#occt_visu_3).
- If you need more detail, for example, a selection filter on another type of entity – you should read chapter 2 [Fundamental Concepts](https://dev.opencascade.org/doc/overview/html/occt_user_guides__visualization.html#occt_visu_2), chapter 3 [AIS: Application Interactive Services](https://dev.opencascade.org/doc/overview/html/occt_user_guides__visualization.html#occt_visu_3), and 4 [3D Presentations](https://dev.opencascade.org/doc/overview/html/occt_user_guides__visualization.html#occt_visu_4). You may want to begin with the chapter presenting AIS.