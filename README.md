ofxImGui_v3
=============================

## Notes by @moebiusSurfing:

![Alt text](screenshot.PNG?raw=true "screenshot")  

**This is a fork from**  
https://github.com/yumataesu/ofxImGui_v3

## Why this fork?
Simpler and easy to update than the `official` addon:  
https://github.com/jvcleave/ofxImGui  
My main idea here is to have a simpler wrapper but with some helper methods useful for openFrameworks, mainly to easy handle `ofParameter/ofParameterGroup`.  
I will try to use `ofxImGuiSimple` or `ofxImGui_v3` to *use the more pure raw code as possible*.  
I will add some interesting links and examples (focused in OF).  

### Updated to  
https://github.com/ocornut/imgui/releases/tag/v1.77  

### Thanks to  
**@yumataesu** -> for the original code!  
And thanks to all the coders of the below links.  

### Tested System  
**OF 0.11** / **Windows10** / **VS2017**  

### TODO
- Collect all helpers and useful examples in the same place.  
- Add node patching repositories with OF examples.  
- Any help about add node pacthing engines will be appreciated!  
- Looking to port guizmo too..  

## Related links  

**WHY A SIMPLER WRAPPER?**  
https://github.com/PlaymodesStudio/ofxImGuiSimple/issues/2  
https://github.com/pjulien21/ofImGuiApp/issues/1  

**OF IMGUI CODE**  
https://github.com/PlaymodesStudio/ofxImGuiSimple -> simple but without helpers  
https://github.com/yasuhirohoshino/ofxPBRHelper -> cool addon that uses ImGui to scene handle and store/recall settings  
https://github.com/sebasobotka/ofxImGui -> Combo and ListBox which can take a vector<string> and customize fonts ( + .otf) 
https://github.com/MacFurax/ofxImGui -> nice theme, custom widgets kind of sound synth device like circular knob...  
https://github.com/pjulien21/ofImGuiApp -> simple but modifiying main.app 
https://github.com/yumataesu/ImGui_Widgets -> kind of vj widgets  
https://github.com/geekowll/imdesigner -> tools to create and deep customize widgets  
https://github.com/katotetsuro/ofxImGui/tree/multiwindow -> simple code to multiwindow/contexts/instances without crash  
https://github.com/memo/ofxMSAControlFreakImGui  
https://github.com/rystylee/ofxImGui-docking    
https://github.com/Akira-Hayasaka/ofxImGui_SplineEditor  

**RAW IMGUI CODE**  
https://github.com/ocornut/imgui_club -> main examples  
https://github.com/aiekick/ImGuiFileDialog  
https://github.com/AirGuanZ/imgui-filebrowser
https://github.com/CedricGuillemet/ImGuizmo  
https://github.com/BrutPitt/imGuIZMO.quat  

**NODE PATCHING**  
https://github.com/thedmd/imgui-node-editor -> looking to port nodes into OF..  
https://github.com/Nelarius/imnodes  
https://github.com/rokups/ImNodes  
https://github.com/JoshuaBatty/ofxNodeGraph -> old OF example  
https://github.com/sphaero/ofNodeEditor -> old OF example  
