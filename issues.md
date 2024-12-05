- VS 2022 version: 17.11.4 + win10



## error C2065: 'UDatasmithObjectTemplate': undeclared identifier (for UE5.3.2 source build)

https://forums.unrealengine.com/t/unreal-engine-5-4-4-building-from-source-error/2000667/3

https://www.reddit.com/r/unrealengine/comments/16esone/cant_createbuild_any_c_project_with_ue53_please/

Operation logs:

- remove the latest version of MSVC v143
- use v14.38
- then I clicked the suggestions shown on VS 2022 to install these items.
  - after that, compiling will show this warning: `Detected compiler newer than Visual Studio 2022, please update min version checking in WindowsPlatformCompilerSetup.h` 

![image-20241205185920529](.\issues.assets\image-20241205185920529.png)

- 

