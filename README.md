# Tiny-Playable-Ad
> A Unity project can have any number of Tiny projects but only one can opened in the editor at a time. Tiny projects use ECS scripting and have different modules as compared to Unity.   
\
Right now Tiny projects can be exported as 2D HTML games or playable ads only. You also need to setup Node.js on your system

Steps to create a Playable ad for Unity using Project Tiny

1. Create a new Unity Project of any type
1. Go to **Window > Package Manager** 
1. Go to **Advanced** option and enable **Show Preview Packages**. 
> Tiny Mode is the package we are looking for and it is in preview
4. Now Search for the Package **TextMesh Pro** and downgrade it to **Version 1.3.0**
1. Open project in Explorer and open the file **Packages > manifest.json** and in the **dependencies** add the package 
    ```json
     "com.unity.properties" : "0.4.0-preview"
    ```
1. Go back to package manager and search for **Tiny Mode** preview package and install **Version 0.14.1**
2. Option for Tiny will appear in the Toolbar. Goto **Tiny > Import Samples**. You can find the imported Tiny projects in **Assets > TinySample**.
1. To open any project go to **Tiny > Open Project** then navigate to TinySamples and a project of your choice and open the file with **.utproject** extension. You can double click it to open as well.
