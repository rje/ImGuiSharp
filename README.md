# ImGuiSharp AS-IS

Near completion of most of the port for ImGui to .NET. I would say I'm around the 90% mark and I'm currently working on the demo side to finish off any pieces I missed along the way. Here are some random points of interest.
- Currently targeting MonoGame but I will remove this requirement to keep it in line with ImGui
- Ported stb_textedited, may be useful for others looking for text input logic for .NET
- Switched from stb truetype to freetype2
- The screen shot below is rendering around 0.7ms in release mode (albeit on a higher end pc).
- Still issues with input editing for sliders
- ~~Pixel snapping issues causing things to appear blurry~~
- Minor issue with treeviews and retaining their state open properties when selecting other nodes
- Appears to be an issue with the scaling to the window
- Code will be put up on GitHub in the near future

![image](https://cloud.githubusercontent.com/assets/6292318/14368012/1b62d372-fce9-11e5-9801-6e54d326f2c1.png)
