--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 163 | Scripts: 42 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.omarInkGame
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["DisplayOrder"] = 9999;
G2L["1"]["Name"] = [[omarInkGame]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.omarInkGame.Controls
G2L["2"] = Instance.new("LocalScript", G2L["1"]);
G2L["2"]["Name"] = [[Controls]];


-- StarterGui.omarInkGame.Info
G2L["3"] = Instance.new("Frame", G2L["1"]);
G2L["3"]["Active"] = true;
G2L["3"]["ZIndex"] = 100000;
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Size"] = UDim2.new(0.35232, 0, 0.04556, 0);
G2L["3"]["Position"] = UDim2.new(0.31101, 0, 0.21012, 0);
G2L["3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Name"] = [[Info]];


-- StarterGui.omarInkGame.Info.UICorner
G2L["4"] = Instance.new("UICorner", G2L["3"]);
G2L["4"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.UIStroke
G2L["5"] = Instance.new("UIStroke", G2L["3"]);
G2L["5"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["5"]["Thickness"] = 0;


-- StarterGui.omarInkGame.Info.GameName
G2L["6"] = Instance.new("TextLabel", G2L["3"]);
G2L["6"]["TextWrapped"] = true;
G2L["6"]["ZIndex"] = 1000000000;
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["TextSize"] = 14;
G2L["6"]["TextScaled"] = true;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["6"]["TextColor3"] = Color3.fromRGB(219, 219, 219);
G2L["6"]["BackgroundTransparency"] = 1;
G2L["6"]["Size"] = UDim2.new(0.66565, 0, 0.94601, 0);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Text"] = [[Ink Game v0.1]];
G2L["6"]["Name"] = [[GameName]];
G2L["6"]["Position"] = UDim2.new(-0.13908, 0, -0.03235, 0);


-- StarterGui.omarInkGame.Info.minimize
G2L["7"] = Instance.new("ImageButton", G2L["3"]);
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["ZIndex"] = 100000;
G2L["7"]["Image"] = [[rbxassetid://73326636016913]];
G2L["7"]["Size"] = UDim2.new(0.06928, 0, 0.6257, 0);
G2L["7"]["BackgroundTransparency"] = 1;
G2L["7"]["Name"] = [[minimize]];
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Position"] = UDim2.new(0.83874, 0, 0.1414, 0);


-- StarterGui.omarInkGame.Info.XButton
G2L["8"] = Instance.new("ImageButton", G2L["3"]);
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["ZIndex"] = 100000;
G2L["8"]["Image"] = [[rbxassetid://103344771690872]];
G2L["8"]["Size"] = UDim2.new(0.04077, 0, 0.65806, 0);
G2L["8"]["BackgroundTransparency"] = 1;
G2L["8"]["Name"] = [[XButton]];
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Position"] = UDim2.new(0.93261, 0, 0.1414, 0);


-- StarterGui.omarInkGame.Info.sigma
G2L["9"] = Instance.new("Frame", G2L["3"]);
G2L["9"]["Active"] = true;
G2L["9"]["ZIndex"] = 0;
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["9"]["Size"] = UDim2.new(0.98697, 0, 11.01718, 0);
G2L["9"]["Position"] = UDim2.new(0.00451, 0, 0.92467, 0);
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Name"] = [[sigma]];
G2L["9"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarInkGame.Info.sigma.UICorner
G2L["a"] = Instance.new("UICorner", G2L["9"]);
G2L["a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.EspFrame
G2L["b"] = Instance.new("Frame", G2L["9"]);
G2L["b"]["Visible"] = false;
G2L["b"]["Active"] = true;
G2L["b"]["ZIndex"] = 0;
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(47, 47, 47);
G2L["b"]["Size"] = UDim2.new(0.78204, 0, 1.00699, 0);
G2L["b"]["Position"] = UDim2.new(0.21796, 0, 0, 0);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Name"] = [[EspFrame]];
G2L["b"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarInkGame.Info.sigma.EspFrame.UICorner
G2L["c"] = Instance.new("UICorner", G2L["b"]);
G2L["c"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.playerimage
G2L["d"] = Instance.new("ImageLabel", G2L["b"]);
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["Image"] = [[rbxasset://textures/ui/GuiImagePlaceholder.png]];
G2L["d"]["Size"] = UDim2.new(0.27217, 0, 0.29805, 0);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["BackgroundTransparency"] = 1;
G2L["d"]["Name"] = [[playerimage]];
G2L["d"]["Position"] = UDim2.new(0.01103, 0, 0.06069, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.playerimage.UICorner
G2L["e"] = Instance.new("UICorner", G2L["d"]);
G2L["e"]["CornerRadius"] = UDim.new(10, 10);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Welcom
G2L["f"] = Instance.new("TextLabel", G2L["b"]);
G2L["f"]["TextWrapped"] = true;
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["TextSize"] = 14;
G2L["f"]["TextScaled"] = true;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["TextDirection"] = Enum.TextDirection.LeftToRight;
G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["f"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["BackgroundTransparency"] = 1;
G2L["f"]["Size"] = UDim2.new(0.63963, 0, 0.12589, 0);
G2L["f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f"]["Text"] = [[WELCOM]];
G2L["f"]["Name"] = [[Welcom]];
G2L["f"]["Position"] = UDim2.new(0.31615, 0, 0.17866, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.credits
G2L["10"] = Instance.new("TextLabel", G2L["b"]);
G2L["10"]["TextWrapped"] = true;
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["TextSize"] = 14;
G2L["10"]["TextScaled"] = true;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["10"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["BackgroundTransparency"] = 1;
G2L["10"]["Size"] = UDim2.new(0.97655, 0, 0.17498, 0);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Text"] = [[Credits: omar: /dev/owner/designer/scripter]];
G2L["10"]["Name"] = [[credits]];
G2L["10"]["Position"] = UDim2.new(-0, 0, 0.44647, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy
G2L["11"] = Instance.new("TextButton", G2L["b"]);
G2L["11"]["TextWrapped"] = true;
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["TextSize"] = 14;
G2L["11"]["TextScaled"] = true;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(137, 137, 137);
G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["11"]["Size"] = UDim2.new(0.16083, 0, 0.10082, 0);
G2L["11"]["Name"] = [[Copy]];
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Text"] = [[COPY]];
G2L["11"]["Position"] = UDim2.new(0.76289, 0, 0.85019, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.UICorner
G2L["12"] = Instance.new("UICorner", G2L["11"]);
G2L["12"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.UIStroke
G2L["13"] = Instance.new("UIStroke", G2L["11"]);
G2L["13"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["13"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.LocalScript
G2L["14"] = Instance.new("LocalScript", G2L["11"]);



-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.soundclick
G2L["15"] = Instance.new("LocalScript", G2L["11"]);
G2L["15"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy
G2L["16"] = Instance.new("TextButton", G2L["b"]);
G2L["16"]["TextWrapped"] = true;
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["TextSize"] = 14;
G2L["16"]["TextScaled"] = true;
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(137, 137, 137);
G2L["16"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["16"]["Size"] = UDim2.new(0.14722, 0, 0.09403, 0);
G2L["16"]["Name"] = [[Copy]];
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Text"] = [[COPY]];
G2L["16"]["Position"] = UDim2.new(0.82933, 0, 0.70494, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.UICorner
G2L["17"] = Instance.new("UICorner", G2L["16"]);
G2L["17"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.UIStroke
G2L["18"] = Instance.new("UIStroke", G2L["16"]);
G2L["18"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["18"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.LocalScript
G2L["19"] = Instance.new("LocalScript", G2L["16"]);



-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.soundclick
G2L["1a"] = Instance.new("LocalScript", G2L["16"]);
G2L["1a"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Link
G2L["1b"] = Instance.new("TextLabel", G2L["b"]);
G2L["1b"]["TextWrapped"] = true;
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["TextSize"] = 14;
G2L["1b"]["TextScaled"] = true;
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["BackgroundTransparency"] = 1;
G2L["1b"]["Size"] = UDim2.new(0.78978, 0, 0.11608, 0);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1b"]["Text"] = [[ discord: https://discord.gg/HJSfaPTDCX]];
G2L["1b"]["Name"] = [[Link]];
G2L["1b"]["Position"] = UDim2.new(0.01233, 0, 0.68098, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.subto
G2L["1c"] = Instance.new("TextLabel", G2L["b"]);
G2L["1c"]["TextWrapped"] = true;
G2L["1c"]["BorderSizePixel"] = 0;
G2L["1c"]["TextSize"] = 14;
G2L["1c"]["TextScaled"] = true;
G2L["1c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1c"]["BackgroundTransparency"] = 1;
G2L["1c"]["Size"] = UDim2.new(0.70246, 0, 0.12617, 0);
G2L["1c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1c"]["Text"] = [[Channel: omargamer8198]];
G2L["1c"]["Name"] = [[subto]];
G2L["1c"]["Position"] = UDim2.new(0.04627, 0, 0.82173, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Main
G2L["1d"] = Instance.new("LocalScript", G2L["b"]);
G2L["1d"]["Name"] = [[Main]];


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Toggle
G2L["1e"] = Instance.new("TextButton", G2L["b"]);
G2L["1e"]["TextWrapped"] = true;
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["TextSize"] = 14;
G2L["1e"]["TextScaled"] = true;
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(69, 69, 69);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1e"]["Size"] = UDim2.new(0.18468, 0, 0.0741, 0);
G2L["1e"]["Name"] = [[Toggle]];
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Text"] = [[Hide]];
G2L["1e"]["Visible"] = false;
G2L["1e"]["Position"] = UDim2.new(0.53122, 0, 0.0765, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Toggle.UICorner
G2L["1f"] = Instance.new("UICorner", G2L["1e"]);
G2L["1f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Toggle.UIStroke
G2L["20"] = Instance.new("UIStroke", G2L["1e"]);
G2L["20"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["20"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.Selection
G2L["21"] = Instance.new("Frame", G2L["9"]);
G2L["21"]["Active"] = true;
G2L["21"]["ZIndex"] = 0;
G2L["21"]["BorderSizePixel"] = 0;
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(36, 36, 36);
G2L["21"]["Size"] = UDim2.new(0.2198, 0, 1.00699, 0);
G2L["21"]["Position"] = UDim2.new(0, 0, 0, 0);
G2L["21"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["Name"] = [[Selection]];


-- StarterGui.omarInkGame.Info.sigma.Selection.Esp
G2L["22"] = Instance.new("TextButton", G2L["21"]);
G2L["22"]["TextWrapped"] = true;
G2L["22"]["BorderSizePixel"] = 0;
G2L["22"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["TextSize"] = 14;
G2L["22"]["TextScaled"] = true;
G2L["22"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["22"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["22"]["Size"] = UDim2.new(0.77026, 0, 0.12599, 0);
G2L["22"]["Name"] = [[Esp]];
G2L["22"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["22"]["Text"] = [[Home]];
G2L["22"]["Position"] = UDim2.new(0.1103, 0, 0.05268, 0);


-- StarterGui.omarInkGame.Info.sigma.Selection.Esp.UICorner
G2L["23"] = Instance.new("UICorner", G2L["22"]);
G2L["23"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.Selection.Esp.UIStroke
G2L["24"] = Instance.new("UIStroke", G2L["22"]);
G2L["24"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["24"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.Selection.UICorner
G2L["25"] = Instance.new("UICorner", G2L["21"]);
G2L["25"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.Selection.Main
G2L["26"] = Instance.new("TextButton", G2L["21"]);
G2L["26"]["TextWrapped"] = true;
G2L["26"]["BorderSizePixel"] = 0;
G2L["26"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["TextSize"] = 14;
G2L["26"]["TextScaled"] = true;
G2L["26"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["26"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["26"]["Size"] = UDim2.new(0.77025, 0, 0.11457, 0);
G2L["26"]["Name"] = [[Main]];
G2L["26"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["26"]["Text"] = [[Main]];
G2L["26"]["Position"] = UDim2.new(0.1103, 0, 0.21603, 0);


-- StarterGui.omarInkGame.Info.sigma.Selection.Main.UICorner
G2L["27"] = Instance.new("UICorner", G2L["26"]);
G2L["27"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.Selection.Main.UIStroke
G2L["28"] = Instance.new("UIStroke", G2L["26"]);
G2L["28"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["28"]["Thickness"] = 2;


-- StarterGui.omarInkGame.Info.sigma.Selection.Misc
G2L["29"] = Instance.new("TextButton", G2L["21"]);
G2L["29"]["TextWrapped"] = true;
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["TextSize"] = 14;
G2L["29"]["TextScaled"] = true;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["29"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["29"]["Size"] = UDim2.new(0.77025, 0, 0.11457, 0);
G2L["29"]["Name"] = [[Misc]];
G2L["29"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["Text"] = [[Misc]];
G2L["29"]["Position"] = UDim2.new(0.11, 0, 0.364, 0);


-- StarterGui.omarInkGame.Info.sigma.Selection.Misc.UICorner
G2L["2a"] = Instance.new("UICorner", G2L["29"]);
G2L["2a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.Selection.Misc.UIStroke
G2L["2b"] = Instance.new("UIStroke", G2L["29"]);
G2L["2b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2b"]["Thickness"] = 2;


-- StarterGui.omarInkGame.Info.sigma.MainFrame
G2L["2c"] = Instance.new("Frame", G2L["9"]);
G2L["2c"]["Active"] = true;
G2L["2c"]["ZIndex"] = 0;
G2L["2c"]["BorderSizePixel"] = 0;
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["2c"]["Size"] = UDim2.new(0.7802, 0, 1.00699, 0);
G2L["2c"]["Position"] = UDim2.new(0.2198, 0, 0, 0);
G2L["2c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2c"]["Name"] = [[MainFrame]];
G2L["2c"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarInkGame.Info.sigma.MainFrame.UIStroke
G2L["2d"] = Instance.new("UIStroke", G2L["2c"]);
G2L["2d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2d"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.MainFrame.UICorner
G2L["2e"] = Instance.new("UICorner", G2L["2c"]);
G2L["2e"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1
G2L["2f"] = Instance.new("TextButton", G2L["2c"]);
G2L["2f"]["TextWrapped"] = true;
G2L["2f"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["2f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["2f"]["TextSize"] = 14;
G2L["2f"]["TextScaled"] = true;
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2f"]["Size"] = UDim2.new(0.71832, 0, 0.08816, 0);
G2L["2f"]["Name"] = [[first1]];
G2L["2f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2f"]["Text"] = [[Teleport To the End]];
G2L["2f"]["Visible"] = false;
G2L["2f"]["Position"] = UDim2.new(0.1339, 0, 0.17856, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.UICorner
G2L["30"] = Instance.new("UICorner", G2L["2f"]);
G2L["30"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.UIStroke
G2L["31"] = Instance.new("UIStroke", G2L["2f"]);
G2L["31"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["31"]["Thickness"] = 1.7;
G2L["31"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.soundclick
G2L["32"] = Instance.new("LocalScript", G2L["2f"]);
G2L["32"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.UIPadding
G2L["33"] = Instance.new("UIPadding", G2L["2f"]);
G2L["33"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.realone
G2L["34"] = Instance.new("LocalScript", G2L["2f"]);
G2L["34"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.fingerprint
G2L["35"] = Instance.new("ImageLabel", G2L["2f"]);
G2L["35"]["BorderSizePixel"] = 0;
G2L["35"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["35"]["Image"] = [[rbxassetid://8903957093]];
G2L["35"]["Size"] = UDim2.new(0.10287, 0, 0.9265, 0);
G2L["35"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["35"]["BackgroundTransparency"] = 1;
G2L["35"]["Name"] = [[fingerprint]];
G2L["35"]["Position"] = UDim2.new(0.89603, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.Chooser
G2L["36"] = Instance.new("TextLabel", G2L["2c"]);
G2L["36"]["TextWrapped"] = true;
G2L["36"]["BorderSizePixel"] = 0;
G2L["36"]["TextSize"] = 14;
G2L["36"]["TextScaled"] = true;
G2L["36"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["36"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["36"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["36"]["BackgroundTransparency"] = 1;
G2L["36"]["Size"] = UDim2.new(0.84057, 0, 0.10832, 0);
G2L["36"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["36"]["Text"] = [[Waiting For The Gamemode...]];
G2L["36"]["Name"] = [[Chooser]];
G2L["36"]["Position"] = UDim2.new(0.07297, 0, 0.02528, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.help1
G2L["37"] = Instance.new("TextBox", G2L["2c"]);
G2L["37"]["Visible"] = false;
G2L["37"]["Name"] = [[help1]];
G2L["37"]["PlaceholderColor3"] = Color3.fromRGB(194, 0, 0);
G2L["37"]["BorderSizePixel"] = 0;
G2L["37"]["TextWrapped"] = true;
G2L["37"]["TextSize"] = 14;
G2L["37"]["TextColor3"] = Color3.fromRGB(212, 0, 0);
G2L["37"]["TextScaled"] = true;
G2L["37"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["37"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["37"]["PlaceholderText"] = [[Type Your Target PlayerName]];
G2L["37"]["Size"] = UDim2.new(0.94976, 0, 0.12682, 0);
G2L["37"]["Position"] = UDim2.new(0.02962, 0, 0.42868, 0);
G2L["37"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["37"]["Text"] = [[]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.help1.UICorner
G2L["38"] = Instance.new("UICorner", G2L["37"]);
G2L["38"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.help1.UIStroke
G2L["39"] = Instance.new("UIStroke", G2L["37"]);
G2L["39"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["39"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first2
G2L["3a"] = Instance.new("TextButton", G2L["2c"]);
G2L["3a"]["TextWrapped"] = true;
G2L["3a"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["3a"]["BorderSizePixel"] = 0;
G2L["3a"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["3a"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["3a"]["TextSize"] = 14;
G2L["3a"]["TextScaled"] = true;
G2L["3a"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3a"]["Size"] = UDim2.new(0.48635, 0, 0.12024, 0);
G2L["3a"]["Name"] = [[first2]];
G2L["3a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["Text"] = [[Help Player]];
G2L["3a"]["Visible"] = false;
G2L["3a"]["Position"] = UDim2.new(0.02907, 0, 0.6189, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first2.UICorner
G2L["3b"] = Instance.new("UICorner", G2L["3a"]);
G2L["3b"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first2.UIStroke
G2L["3c"] = Instance.new("UIStroke", G2L["3a"]);
G2L["3c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3c"]["Thickness"] = 1.7;
G2L["3c"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first2.soundclick
G2L["3d"] = Instance.new("LocalScript", G2L["3a"]);
G2L["3d"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first2.UIPadding
G2L["3e"] = Instance.new("UIPadding", G2L["3a"]);
G2L["3e"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first3
G2L["3f"] = Instance.new("TextButton", G2L["2c"]);
G2L["3f"]["TextWrapped"] = true;
G2L["3f"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["3f"]["BorderSizePixel"] = 0;
G2L["3f"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["3f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["3f"]["TextSize"] = 14;
G2L["3f"]["TextScaled"] = true;
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3f"]["Size"] = UDim2.new(0.44265, 0, 0.12607, 0);
G2L["3f"]["Name"] = [[first3]];
G2L["3f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["Text"] = [[Kill Player]];
G2L["3f"]["Visible"] = false;
G2L["3f"]["Position"] = UDim2.new(0.53039, 0, 0.6189, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first3.UICorner
G2L["40"] = Instance.new("UICorner", G2L["3f"]);
G2L["40"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first3.UIStroke
G2L["41"] = Instance.new("UIStroke", G2L["3f"]);
G2L["41"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["41"]["Thickness"] = 1.7;
G2L["41"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first3.soundclick
G2L["42"] = Instance.new("LocalScript", G2L["3f"]);
G2L["42"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first3.UIPadding
G2L["43"] = Instance.new("UIPadding", G2L["3f"]);
G2L["43"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.Green Red Light
G2L["44"] = Instance.new("LocalScript", G2L["2c"]);
G2L["44"]["Name"] = [[Green Red Light]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.second1
G2L["45"] = Instance.new("TextLabel", G2L["2c"]);
G2L["45"]["TextWrapped"] = true;
G2L["45"]["BorderSizePixel"] = 0;
G2L["45"]["TextSize"] = 14;
G2L["45"]["TextScaled"] = true;
G2L["45"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["45"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["45"]["TextColor3"] = Color3.fromRGB(241, 0, 0);
G2L["45"]["BackgroundTransparency"] = 1;
G2L["45"]["Size"] = UDim2.new(0.84206, 0, 0.14957, 0);
G2L["45"]["Visible"] = false;
G2L["45"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["45"]["Text"] = [[Sorry Dalgona is not Supported]];
G2L["45"]["Name"] = [[second1]];
G2L["45"]["Position"] = UDim2.new(0.07297, 0, 0.32901, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1
G2L["46"] = Instance.new("TextButton", G2L["2c"]);
G2L["46"]["TextWrapped"] = true;
G2L["46"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["46"]["BorderSizePixel"] = 0;
G2L["46"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["46"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["46"]["TextSize"] = 14;
G2L["46"]["TextScaled"] = true;
G2L["46"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["46"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["46"]["Size"] = UDim2.new(0.71832, 0, 0.12316, 0);
G2L["46"]["Name"] = [[third1]];
G2L["46"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["46"]["Text"] = [[Go safe Place]];
G2L["46"]["Visible"] = false;
G2L["46"]["Position"] = UDim2.new(0.1339, 0, 0.28645, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.UICorner
G2L["47"] = Instance.new("UICorner", G2L["46"]);
G2L["47"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.UIStroke
G2L["48"] = Instance.new("UIStroke", G2L["46"]);
G2L["48"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["48"]["Thickness"] = 1.7;
G2L["48"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.soundclick
G2L["49"] = Instance.new("LocalScript", G2L["46"]);
G2L["49"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.UIPadding
G2L["4a"] = Instance.new("UIPadding", G2L["46"]);
G2L["4a"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.realone
G2L["4b"] = Instance.new("LocalScript", G2L["46"]);
G2L["4b"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1
G2L["4c"] = Instance.new("TextButton", G2L["2c"]);
G2L["4c"]["TextWrapped"] = true;
G2L["4c"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["4c"]["BorderSizePixel"] = 0;
G2L["4c"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["4c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["4c"]["TextSize"] = 14;
G2L["4c"]["TextScaled"] = true;
G2L["4c"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4c"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4c"]["Size"] = UDim2.new(0.71832, 0, 0.12316, 0);
G2L["4c"]["Name"] = [[four1]];
G2L["4c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4c"]["Text"] = [[Auto Win]];
G2L["4c"]["Visible"] = false;
G2L["4c"]["Position"] = UDim2.new(0.1339, 0, 0.2398, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.UICorner
G2L["4d"] = Instance.new("UICorner", G2L["4c"]);
G2L["4d"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.UIStroke
G2L["4e"] = Instance.new("UIStroke", G2L["4c"]);
G2L["4e"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["4e"]["Thickness"] = 1.7;
G2L["4e"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.soundclick
G2L["4f"] = Instance.new("LocalScript", G2L["4c"]);
G2L["4f"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.UIPadding
G2L["50"] = Instance.new("UIPadding", G2L["4c"]);
G2L["50"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.realone
G2L["51"] = Instance.new("LocalScript", G2L["4c"]);
G2L["51"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.fingerprint
G2L["52"] = Instance.new("ImageLabel", G2L["4c"]);
G2L["52"]["BorderSizePixel"] = 0;
G2L["52"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["52"]["Image"] = [[rbxassetid://8903957093]];
G2L["52"]["Size"] = UDim2.new(0.10287, 0, 0.9265, 0);
G2L["52"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["52"]["BackgroundTransparency"] = 1;
G2L["52"]["Name"] = [[fingerprint]];
G2L["52"]["Position"] = UDim2.new(0.89603, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.GameMode Chooser
G2L["53"] = Instance.new("LocalScript", G2L["2c"]);
G2L["53"]["Name"] = [[GameMode Chooser]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third2
G2L["54"] = Instance.new("TextLabel", G2L["2c"]);
G2L["54"]["TextWrapped"] = true;
G2L["54"]["BorderSizePixel"] = 0;
G2L["54"]["TextSize"] = 14;
G2L["54"]["TextScaled"] = true;
G2L["54"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["54"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["54"]["TextColor3"] = Color3.fromRGB(53, 241, 0);
G2L["54"]["BackgroundTransparency"] = 1;
G2L["54"]["Size"] = UDim2.new(0.84206, 0, 0.14957, 0);
G2L["54"]["Visible"] = false;
G2L["54"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["54"]["Text"] = [[Alive xx]];
G2L["54"]["Name"] = [[third2]];
G2L["54"]["Position"] = UDim2.new(0.07864, 0, 0.51564, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third2.tracker
G2L["55"] = Instance.new("LocalScript", G2L["54"]);
G2L["55"]["Name"] = [[tracker]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2
G2L["56"] = Instance.new("TextButton", G2L["2c"]);
G2L["56"]["TextWrapped"] = true;
G2L["56"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["56"]["BorderSizePixel"] = 0;
G2L["56"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["56"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["56"]["TextSize"] = 14;
G2L["56"]["TextScaled"] = true;
G2L["56"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["56"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["56"]["Size"] = UDim2.new(0.71832, 0, 0.1079, 0);
G2L["56"]["Name"] = [[five2]];
G2L["56"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["56"]["Text"] = [[Glass Vision]];
G2L["56"]["Visible"] = false;
G2L["56"]["Position"] = UDim2.new(0.1339, 0, 0.43518, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.UICorner
G2L["57"] = Instance.new("UICorner", G2L["56"]);
G2L["57"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.UIStroke
G2L["58"] = Instance.new("UIStroke", G2L["56"]);
G2L["58"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["58"]["Thickness"] = 1.7;
G2L["58"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.soundclick
G2L["59"] = Instance.new("LocalScript", G2L["56"]);
G2L["59"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.UIPadding
G2L["5a"] = Instance.new("UIPadding", G2L["56"]);
G2L["5a"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.realone
G2L["5b"] = Instance.new("LocalScript", G2L["56"]);
G2L["5b"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.fingerprint
G2L["5c"] = Instance.new("ImageLabel", G2L["56"]);
G2L["5c"]["BorderSizePixel"] = 0;
G2L["5c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5c"]["Image"] = [[rbxassetid://12333784627]];
G2L["5c"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["5c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5c"]["BackgroundTransparency"] = 1;
G2L["5c"]["Name"] = [[fingerprint]];
G2L["5c"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five3
G2L["5d"] = Instance.new("TextLabel", G2L["2c"]);
G2L["5d"]["TextWrapped"] = true;
G2L["5d"]["BorderSizePixel"] = 0;
G2L["5d"]["TextSize"] = 14;
G2L["5d"]["TextScaled"] = true;
G2L["5d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5d"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5d"]["TextColor3"] = Color3.fromRGB(0, 73, 241);
G2L["5d"]["BackgroundTransparency"] = 1;
G2L["5d"]["Size"] = UDim2.new(0.81013, 0, 0.14957, 0);
G2L["5d"]["Visible"] = false;
G2L["5d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5d"]["Text"] = [[Timer XX]];
G2L["5d"]["Name"] = [[five3]];
G2L["5d"]["Position"] = UDim2.new(0.09283, 0, 0.59438, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five3.tracker
G2L["5e"] = Instance.new("LocalScript", G2L["5d"]);
G2L["5e"]["Name"] = [[tracker]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1
G2L["5f"] = Instance.new("TextButton", G2L["2c"]);
G2L["5f"]["TextWrapped"] = true;
G2L["5f"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["5f"]["BorderSizePixel"] = 0;
G2L["5f"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["5f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["5f"]["TextSize"] = 14;
G2L["5f"]["TextScaled"] = true;
G2L["5f"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5f"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5f"]["Size"] = UDim2.new(0.71832, 0, 0.1079, 0);
G2L["5f"]["Name"] = [[five1]];
G2L["5f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5f"]["Text"] = [[Teleport To the End]];
G2L["5f"]["Visible"] = false;
G2L["5f"]["Position"] = UDim2.new(0.1339, 0, 0.21355, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.UICorner
G2L["60"] = Instance.new("UICorner", G2L["5f"]);
G2L["60"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.UIStroke
G2L["61"] = Instance.new("UIStroke", G2L["5f"]);
G2L["61"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["61"]["Thickness"] = 1.7;
G2L["61"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.soundclick
G2L["62"] = Instance.new("LocalScript", G2L["5f"]);
G2L["62"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.UIPadding
G2L["63"] = Instance.new("UIPadding", G2L["5f"]);
G2L["63"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.realone
G2L["64"] = Instance.new("LocalScript", G2L["5f"]);
G2L["64"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1
G2L["65"] = Instance.new("TextButton", G2L["2c"]);
G2L["65"]["TextWrapped"] = true;
G2L["65"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["65"]["BorderSizePixel"] = 0;
G2L["65"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["65"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["65"]["TextSize"] = 14;
G2L["65"]["TextScaled"] = true;
G2L["65"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["65"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["65"]["Size"] = UDim2.new(0.724, 0, 0.10027, 0);
G2L["65"]["Name"] = [[six1]];
G2L["65"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["65"]["Text"] = [[Power Hold No Miss 100%]];
G2L["65"]["Visible"] = false;
G2L["65"]["Position"] = UDim2.new(0.13802, 0, 0.21311, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.UICorner
G2L["66"] = Instance.new("UICorner", G2L["65"]);
G2L["66"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.UIStroke
G2L["67"] = Instance.new("UIStroke", G2L["65"]);
G2L["67"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["67"]["Thickness"] = 1.7;
G2L["67"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.soundclick
G2L["68"] = Instance.new("LocalScript", G2L["65"]);
G2L["68"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.UIPadding
G2L["69"] = Instance.new("UIPadding", G2L["65"]);
G2L["69"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.realone
G2L["6a"] = Instance.new("LocalScript", G2L["65"]);
G2L["6a"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2
G2L["6b"] = Instance.new("TextButton", G2L["2c"]);
G2L["6b"]["TextWrapped"] = true;
G2L["6b"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["6b"]["BorderSizePixel"] = 0;
G2L["6b"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["6b"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["6b"]["TextSize"] = 14;
G2L["6b"]["TextScaled"] = true;
G2L["6b"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6b"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6b"]["Size"] = UDim2.new(0.71832, 0, 0.0941, 0);
G2L["6b"]["Name"] = [[blue2]];
G2L["6b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6b"]["Text"] = [[Esp Red Team]];
G2L["6b"]["Visible"] = false;
G2L["6b"]["Position"] = UDim2.new(0.1339, 0, 0.47685, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.UICorner
G2L["6c"] = Instance.new("UICorner", G2L["6b"]);
G2L["6c"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.UIStroke
G2L["6d"] = Instance.new("UIStroke", G2L["6b"]);
G2L["6d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["6d"]["Thickness"] = 1.7;
G2L["6d"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.soundclick
G2L["6e"] = Instance.new("LocalScript", G2L["6b"]);
G2L["6e"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.UIPadding
G2L["6f"] = Instance.new("UIPadding", G2L["6b"]);
G2L["6f"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.realone
G2L["70"] = Instance.new("LocalScript", G2L["6b"]);
G2L["70"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1
G2L["71"] = Instance.new("TextButton", G2L["2c"]);
G2L["71"]["TextWrapped"] = true;
G2L["71"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["71"]["BorderSizePixel"] = 0;
G2L["71"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["71"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["71"]["TextSize"] = 14;
G2L["71"]["TextScaled"] = true;
G2L["71"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["71"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["71"]["Size"] = UDim2.new(0.71832, 0, 0.11259, 0);
G2L["71"]["Name"] = [[blue1]];
G2L["71"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["71"]["Text"] = [[Go safe Place]];
G2L["71"]["Visible"] = false;
G2L["71"]["Position"] = UDim2.new(0.1339, 0, 0.32873, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.UICorner
G2L["72"] = Instance.new("UICorner", G2L["71"]);
G2L["72"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.UIStroke
G2L["73"] = Instance.new("UIStroke", G2L["71"]);
G2L["73"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["73"]["Thickness"] = 1.7;
G2L["73"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.soundclick
G2L["74"] = Instance.new("LocalScript", G2L["71"]);
G2L["74"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.UIPadding
G2L["75"] = Instance.new("UIPadding", G2L["71"]);
G2L["75"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.realone
G2L["76"] = Instance.new("LocalScript", G2L["71"]);
G2L["76"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.seven1
G2L["77"] = Instance.new("TextLabel", G2L["2c"]);
G2L["77"]["TextWrapped"] = true;
G2L["77"]["BorderSizePixel"] = 0;
G2L["77"]["TextSize"] = 14;
G2L["77"]["TextScaled"] = true;
G2L["77"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["77"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["77"]["TextColor3"] = Color3.fromRGB(241, 234, 233);
G2L["77"]["BackgroundTransparency"] = 1;
G2L["77"]["Size"] = UDim2.new(0.84206, 0, 0.11522, 0);
G2L["77"]["Visible"] = false;
G2L["77"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["77"]["Text"] = [[Team is xx]];
G2L["77"]["Name"] = [[seven1]];
G2L["77"]["Position"] = UDim2.new(0.07297, 0, 0.17746, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3
G2L["78"] = Instance.new("TextButton", G2L["2c"]);
G2L["78"]["TextWrapped"] = true;
G2L["78"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["78"]["BorderSizePixel"] = 0;
G2L["78"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["78"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["78"]["TextSize"] = 14;
G2L["78"]["TextScaled"] = true;
G2L["78"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["78"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["78"]["Size"] = UDim2.new(0.71832, 0, 0.0941, 0);
G2L["78"]["Name"] = [[red3]];
G2L["78"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["78"]["Text"] = [[Bigger Hitbox Close PPL]];
G2L["78"]["Visible"] = false;
G2L["78"]["Position"] = UDim2.new(0.1339, 0, 0.59933, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.UICorner
G2L["79"] = Instance.new("UICorner", G2L["78"]);
G2L["79"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.UIStroke
G2L["7a"] = Instance.new("UIStroke", G2L["78"]);
G2L["7a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["7a"]["Thickness"] = 1.7;
G2L["7a"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.soundclick
G2L["7b"] = Instance.new("LocalScript", G2L["78"]);
G2L["7b"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.UIPadding
G2L["7c"] = Instance.new("UIPadding", G2L["78"]);
G2L["7c"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.realone
G2L["7d"] = Instance.new("LocalScript", G2L["78"]);
G2L["7d"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3
G2L["7e"] = Instance.new("TextButton", G2L["2c"]);
G2L["7e"]["TextWrapped"] = true;
G2L["7e"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["7e"]["BorderSizePixel"] = 0;
G2L["7e"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["7e"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["7e"]["TextSize"] = 14;
G2L["7e"]["TextScaled"] = true;
G2L["7e"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7e"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7e"]["Size"] = UDim2.new(0.71832, 0, 0.0941, 0);
G2L["7e"]["Name"] = [[blue3]];
G2L["7e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7e"]["Text"] = [[Esp Exit]];
G2L["7e"]["Visible"] = false;
G2L["7e"]["Position"] = UDim2.new(0.13957, 0, 0.59642, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.UICorner
G2L["7f"] = Instance.new("UICorner", G2L["7e"]);
G2L["7f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.UIStroke
G2L["80"] = Instance.new("UIStroke", G2L["7e"]);
G2L["80"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["80"]["Thickness"] = 1.7;
G2L["80"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.soundclick
G2L["81"] = Instance.new("LocalScript", G2L["7e"]);
G2L["81"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.UIPadding
G2L["82"] = Instance.new("UIPadding", G2L["7e"]);
G2L["82"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.realone
G2L["83"] = Instance.new("LocalScript", G2L["7e"]);
G2L["83"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red1
G2L["84"] = Instance.new("TextButton", G2L["2c"]);
G2L["84"]["TextWrapped"] = true;
G2L["84"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["84"]["BorderSizePixel"] = 0;
G2L["84"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["84"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["84"]["TextSize"] = 14;
G2L["84"]["TextScaled"] = true;
G2L["84"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["84"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["84"]["Size"] = UDim2.new(0.71832, 0, 0.11259, 0);
G2L["84"]["Name"] = [[red1]];
G2L["84"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["84"]["Text"] = [[Auto Attack 1 blue]];
G2L["84"]["Visible"] = false;
G2L["84"]["Position"] = UDim2.new(0.1339, 0, 0.32873, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red1.UICorner
G2L["85"] = Instance.new("UICorner", G2L["84"]);
G2L["85"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red1.UIStroke
G2L["86"] = Instance.new("UIStroke", G2L["84"]);
G2L["86"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["86"]["Thickness"] = 1.7;
G2L["86"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red1.soundclick
G2L["87"] = Instance.new("LocalScript", G2L["84"]);
G2L["87"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red1.UIPadding
G2L["88"] = Instance.new("UIPadding", G2L["84"]);
G2L["88"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red1.realone
G2L["89"] = Instance.new("LocalScript", G2L["84"]);
G2L["89"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2
G2L["8a"] = Instance.new("TextButton", G2L["2c"]);
G2L["8a"]["TextWrapped"] = true;
G2L["8a"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["8a"]["BorderSizePixel"] = 0;
G2L["8a"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["8a"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["8a"]["TextSize"] = 14;
G2L["8a"]["TextScaled"] = true;
G2L["8a"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8a"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8a"]["Size"] = UDim2.new(0.71832, 0, 0.0941, 0);
G2L["8a"]["Name"] = [[red2]];
G2L["8a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8a"]["Text"] = [[Esp Blue Team]];
G2L["8a"]["Visible"] = false;
G2L["8a"]["Position"] = UDim2.new(0.1339, 0, 0.47685, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.UICorner
G2L["8b"] = Instance.new("UICorner", G2L["8a"]);
G2L["8b"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.UIStroke
G2L["8c"] = Instance.new("UIStroke", G2L["8a"]);
G2L["8c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["8c"]["Thickness"] = 1.7;
G2L["8c"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.soundclick
G2L["8d"] = Instance.new("LocalScript", G2L["8a"]);
G2L["8d"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.UIPadding
G2L["8e"] = Instance.new("UIPadding", G2L["8a"]);
G2L["8e"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.realone
G2L["8f"] = Instance.new("LocalScript", G2L["8a"]);
G2L["8f"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1Label
G2L["90"] = Instance.new("TextLabel", G2L["2c"]);
G2L["90"]["TextWrapped"] = true;
G2L["90"]["BorderSizePixel"] = 0;
G2L["90"]["TextSize"] = 14;
G2L["90"]["TextScaled"] = true;
G2L["90"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["90"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["90"]["TextColor3"] = Color3.fromRGB(178, 0, 0);
G2L["90"]["BackgroundTransparency"] = 1;
G2L["90"]["Size"] = UDim2.new(0.961, 0, 0.15324, 0);
G2L["90"]["Visible"] = false;
G2L["90"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["90"]["Text"] = [[Only Works if the Target is Injured And not Carried By another player]];
G2L["90"]["Name"] = [[first1Label]];
G2L["90"]["Position"] = UDim2.new(0.01645, 0, 0.81148, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame
G2L["91"] = Instance.new("Frame", G2L["9"]);
G2L["91"]["Visible"] = false;
G2L["91"]["Active"] = true;
G2L["91"]["ZIndex"] = 0;
G2L["91"]["BorderSizePixel"] = 0;
G2L["91"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["91"]["Size"] = UDim2.new(0.7802, 0, 1.00699, 0);
G2L["91"]["Position"] = UDim2.new(0.2198, 0, 0, 0);
G2L["91"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["91"]["Name"] = [[MiscFrame]];
G2L["91"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.UIStroke
G2L["92"] = Instance.new("UIStroke", G2L["91"]);
G2L["92"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["92"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.UICorner
G2L["93"] = Instance.new("UICorner", G2L["91"]);
G2L["93"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third
G2L["94"] = Instance.new("TextButton", G2L["91"]);
G2L["94"]["TextWrapped"] = true;
G2L["94"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["94"]["BorderSizePixel"] = 0;
G2L["94"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["94"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["94"]["TextSize"] = 14;
G2L["94"]["TextScaled"] = true;
G2L["94"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["94"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["94"]["Size"] = UDim2.new(0.75106, 0, 0.08456, 0);
G2L["94"]["Name"] = [[third]];
G2L["94"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["94"]["Text"] = [[Auto Skip Dialogue]];
G2L["94"]["Position"] = UDim2.new(0.09635, 0, 0.07166, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.UICorner
G2L["95"] = Instance.new("UICorner", G2L["94"]);
G2L["95"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.UIStroke
G2L["96"] = Instance.new("UIStroke", G2L["94"]);
G2L["96"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["96"]["Thickness"] = 1.7;
G2L["96"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.soundclick
G2L["97"] = Instance.new("LocalScript", G2L["94"]);
G2L["97"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.fingerprint
G2L["98"] = Instance.new("ImageLabel", G2L["94"]);
G2L["98"]["BorderSizePixel"] = 0;
G2L["98"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["98"]["Image"] = [[rbxassetid://12333784627]];
G2L["98"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["98"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["98"]["BackgroundTransparency"] = 1;
G2L["98"]["Name"] = [[fingerprint]];
G2L["98"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.UIPadding
G2L["99"] = Instance.new("UIPadding", G2L["94"]);
G2L["99"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.LocalScript
G2L["9a"] = Instance.new("LocalScript", G2L["94"]);



-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four
G2L["9b"] = Instance.new("TextButton", G2L["91"]);
G2L["9b"]["TextWrapped"] = true;
G2L["9b"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["9b"]["BorderSizePixel"] = 0;
G2L["9b"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["9b"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["9b"]["TextSize"] = 14;
G2L["9b"]["TextScaled"] = true;
G2L["9b"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9b"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9b"]["Size"] = UDim2.new(0.75106, 0, 0.08456, 0);
G2L["9b"]["Name"] = [[four]];
G2L["9b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9b"]["Text"] = [[Inf Jump]];
G2L["9b"]["Position"] = UDim2.new(0.09635, 0, 0.22913, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.UICorner
G2L["9c"] = Instance.new("UICorner", G2L["9b"]);
G2L["9c"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.UIStroke
G2L["9d"] = Instance.new("UIStroke", G2L["9b"]);
G2L["9d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["9d"]["Thickness"] = 1.7;
G2L["9d"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.soundclick
G2L["9e"] = Instance.new("LocalScript", G2L["9b"]);
G2L["9e"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.fingerprint
G2L["9f"] = Instance.new("ImageLabel", G2L["9b"]);
G2L["9f"]["BorderSizePixel"] = 0;
G2L["9f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9f"]["Image"] = [[rbxassetid://12333784627]];
G2L["9f"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["9f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9f"]["BackgroundTransparency"] = 1;
G2L["9f"]["Name"] = [[fingerprint]];
G2L["9f"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.UIPadding
G2L["a0"] = Instance.new("UIPadding", G2L["9b"]);
G2L["a0"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.LocalScript
G2L["a1"] = Instance.new("LocalScript", G2L["9b"]);



-- StarterGui.omarInkGame.Info.drag localscript
G2L["a2"] = Instance.new("LocalScript", G2L["3"]);
G2L["a2"]["Name"] = [[drag localscript]];


-- StarterGui.omarInkGame.Changer
G2L["a3"] = Instance.new("LocalScript", G2L["1"]);
G2L["a3"]["Name"] = [[Changer]];


-- StarterGui.omarInkGame.Controls
local function C_2()
local script = G2L["2"];
	local TweenService = game:GetService("TweenService")
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	local gui = player:WaitForChild("PlayerGui"):WaitForChild("omarInkGame")
	
	local info = gui:WaitForChild("Info") -- Header
	local sigma = info:WaitForChild("sigma") -- Content under header
	
	local minimizeBtn = info:WaitForChild("minimize")
	local xButton = info:WaitForChild("XButton")
	
	local isMinimized = false
	local tweenTime = 0.35
	
	local function minimize()
		-- Just hide sigma without tweening position (since it's inside Info)
		sigma.Visible = false
	end
	
	local function maximize()
		-- Make sigma visible again
		sigma.Visible = true
	end
	
	minimizeBtn.MouseButton1Click:Connect(function()
		if not isMinimized then
			minimize()
		else
			maximize()
		end
		isMinimized = not isMinimized
	end)
	
	xButton.MouseButton1Click:Connect(function()
		for _, descendant in ipairs(gui:GetDescendants()) do
			if descendant:IsA("TextButton") or descendant:IsA("ImageButton") or descendant:IsA("TextLabel") then
				for _, child in ipairs(descendant:GetChildren()) do
					if child:IsA("LocalScript") then
						child.Disabled = true
					end
				end
			end
		end
	
		wait(0.2)
		gui:Destroy()
	end)
	
end;
task.spawn(C_2);
-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.LocalScript
local function C_14()
local script = G2L["14"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		if setclipboard then
			setclipboard("omargamer8198")
			game.StarterGui:SetCore("SendNotification", {
				Title = "Success!",
				Text = "Copied Youtube Link",
				Duration = 3
			})
		else
			warn("Clipboard function not available.")
		end
	end)
	
end;
task.spawn(C_14);
-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.soundclick
local function C_15()
local script = G2L["15"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_15);
-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.LocalScript
local function C_19()
local script = G2L["19"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		if setclipboard then
			setclipboard("https://discord.gg/HJSfaPTDCX")
			game.StarterGui:SetCore("SendNotification", {
				Title = "Success!",
				Text = "Copied Discord Link",
				Duration = 3
			})
		else
			warn("Clipboard function not available.")
		end
	end)
	
end;
task.spawn(C_19);
-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.soundclick
local function C_1a()
local script = G2L["1a"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_1a);
-- StarterGui.omarInkGame.Info.sigma.EspFrame.Main
local function C_1d()
local script = G2L["1d"];
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	
	-- UI references
	local gui = script.Parent
	local textLabel = gui:WaitForChild("Welcom")
	local playerImage = gui:WaitForChild("playerimage")
	local toggleButton = gui:WaitForChild("Toggle")
	
	-- Headshot image
	playerImage.Image = "https://www.roblox.com/headshot-thumbnail/image?userId=" .. player.UserId .. "&width=420&height=420&format=png"
	
	-- Enable RichText
	textLabel.RichText = true
	toggleButton.Visible = false -- Hide toggle at start
	
	local welcomeText = "Welcome " .. player.Name
	
	-- Function to type text with optional color
	local function typeText(text, speed, color)
		for i = 1, #text do
			local part = text:sub(1, i)
			if color then
				textLabel.Text = "<font color='" .. color .. "'>" .. part .. "</font>"
			else
				textLabel.Text = part
			end
			wait(speed)
		end
	end
	
	-- Function to delete text while keeping color
	local function deleteRichText(text, speed, color)
		for i = #text, 0, -1 do
			local part = text:sub(1, i)
			if color then
				textLabel.Text = "<font color='" .. color .. "'>" .. part .. "</font>"
			else
				textLabel.Text = part
			end
			wait(speed)
		end
	end
	
	-- MAIN SEQUENCE
	
	-- Step 1: Type in RED
	typeText(welcomeText, 0.1, "rgb(255,0,0)")
	wait(1)
	
	-- Step 2: Delete in RED
	deleteRichText(welcomeText, 0.05, "rgb(255,0,0)")
	wait(0.5)
	
	-- Step 3: Type again in normal color
	typeText(welcomeText, 0.1, nil)
	wait(0.5)
	
	-- Step 4: Show the Toggle button
	toggleButton.Visible = true
	toggleButton.Text = "Hide"
	
	-- Step 5: Toggle behavior
	local visible = true
	
	toggleButton.MouseButton1Click:Connect(function()
		visible = not visible
		textLabel.Visible = visible
		toggleButton.Text = visible and "Hide" or "Show"
	end)
	
end;
task.spawn(C_1d);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.soundclick
local function C_32()
local script = G2L["32"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_32);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.realone
local function C_34()
local script = G2L["34"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		local player = game.Players.LocalPlayer
		local character = player.Character or player.CharacterAdded:Wait()
		local humanoidRootPart = character:WaitForChild("HumanoidRootPart")
	
		humanoidRootPart.CFrame = CFrame.new(-46, 1025, 138)
	end)
	
end;
task.spawn(C_34);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.first2.soundclick
local function C_3d()
local script = G2L["3d"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_3d);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.first3.soundclick
local function C_42()
local script = G2L["42"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_42);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.Green Red Light
local function C_44()
local script = G2L["44"];
	-- LocalScript (put this under MainFrame)
	local Players       = game:GetService("Players")
	local Replicated    = game:GetService("ReplicatedStorage")
	local StarterGui    = game:GetService("StarterGui")
	local LocalPlayer   = Players.LocalPlayer
	
	local mainFrame     = script.Parent
	local helpBox       = mainFrame:WaitForChild("help1")
	local btn2          = mainFrame:WaitForChild("first2")
	local btn3          = mainFrame:WaitForChild("first3")
	local clickedRem    = Replicated:WaitForChild("Remotes"):WaitForChild("ClickedButton")
	
	local active = false
	
	-- fireproximityprompt: fires a specific prompt once, with HoldDuration=0
	local function fireproximityprompt(Obj)
		if not Obj or Obj.ClassName ~= "ProximityPrompt" then
			warn("[HelpAction] Expected ProximityPrompt, got", Obj)
			return false
		end
		local originalHold = Obj.HoldDuration
		Obj.HoldDuration = 0
		Obj:InputHoldBegin()
		Obj:InputHoldEnd()
		Obj.HoldDuration = originalHold
		print("[HelpAction] ProximityPrompt fired for ", Obj.Parent.Name)
		return true
	end
	
	-- strip all whitespace
	local function stripSpaces(s)
		return s:gsub("%s+", "")
	end
	
	-- find player by partial match
	local function findPlayer(part)
		part = part:lower()
		for _, p in ipairs(Players:GetPlayers()) do
			local n = p.Name:lower()
			local d = (p.DisplayName and p.DisplayName:lower()) or ""
			if n:sub(1,#part) == part or d:sub(1,#part) == part then
				return p
			end
		end
		return nil
	end
	
	-- on-screen notification
	local function notify(text)
		StarterGui:SetCore("SendNotification", {
			Title    = "HelpAction",
			Text     = text,
			Duration = 3,
		})
	end
	
	-- core routine: button, destination, fail message
	local function doHelp(button, destPos, failMsg)
		if active then return end
		active = true
	
		-- prepare input
		local raw = helpBox.Text or ""
		local txt = stripSpaces(raw)
		if #txt < 2 then
			notify("Please enter at least 2 characters.")
			active = false
			return
		end
	
		-- lookup player
		local targetP = findPlayer(txt)
		if not targetP then
			notify("Player not found.")
			active = false
			return
		end
	
		-- find live model
		local liveF = workspace:FindFirstChild("Live")
		local model = liveF and liveF:FindFirstChild(targetP.Name)
		if not model or not model:FindFirstChild("HumanoidRootPart") then
			notify("Player model not found.")
			active = false
			return
		end
	
		-- find CarryPrompt
		local prompt = model.HumanoidRootPart:FindFirstChild("CarryPrompt")
		if not prompt then
			notify(failMsg)
			active = false
			return
		end
	
		-- turn button stroke green
		local stroke = button:FindFirstChildOfClass("UIStroke")
		local oldCol = stroke and stroke.Color
		if stroke then stroke.Color = Color3.fromRGB(0,255,0) end
	
		-- ensure our character
		local char  = LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()
		local myHrp = char:WaitForChild("HumanoidRootPart")
	
		-- teleport to target and wait
		myHrp.CFrame = CFrame.new(model.HumanoidRootPart.Position + Vector3.new(0,1,0))
		wait(0.2)
	
		-- fire this prompt once
		local fired = fireproximityprompt(prompt)
		if not fired then
			notify("Failed to fire prompt.")
			if stroke then stroke.Color = oldCol end
			active = false
			return
		end
		notify("ProximityPrompt fired!")
	
		-- wait so action registers before moving
		wait(0.4)
	
		-- teleport to fixed spot
		myHrp.CFrame = CFrame.new(destPos)
		wait(0.1)
	
		-- fire the remote after teleport
		clickedRem:FireServer({ tryingtoleave = true })
		print("[HelpAction] Remote fired after teleport.")
	
		-- cleanup UI
		wait(0.1)
		if stroke then stroke.Color = oldCol end
		notify("Help sequence complete.")
		active = false
	end
	
	-- bind to first2 (help flow)
	btn2.MouseButton1Click:Connect(function()
		doHelp(btn2, Vector3.new(-46, 1025, 138), "You can’t help this Target.")
	end)
	
	-- bind to first3 (kill flow)
	btn3.MouseButton1Click:Connect(function()
		doHelp(btn3, Vector3.new(-96, 1023, -671), "Can’t kill this Target.")
	end)
	
	-- autocomplete on Enter and release focus
	helpBox.FocusLost:Connect(function(enterPressed)
		if not enterPressed then return end
		local txt = stripSpaces(helpBox.Text or "")
		if #txt < 2 then return end
		local p = findPlayer(txt)
		if p then
			helpBox.Text = p.Name
			helpBox.CursorPosition = #p.Name + 1
			-- release focus so the user is out of the textbox
			helpBox:ReleaseFocus()
		end
	end)
	
end;
task.spawn(C_44);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.soundclick
local function C_49()
local script = G2L["49"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_49);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.realone
local function C_4b()
local script = G2L["4b"];
	local button = script.Parent
	local uistroke = button:WaitForChild("UIStroke")
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local isOn = false
	local originalColor = uistroke.Color
	
	button.MouseButton1Click:Connect(function()
		isOn = not isOn
	
		if isOn then
			uistroke.Color = Color3.fromRGB(0, 255, 0) -- Green
			if character and character:FindFirstChild("HumanoidRootPart") then
				character:MoveTo(Vector3.new(198, 83, -93))
			end
		else
			uistroke.Color = originalColor
			local alivePlayers = {}
	
			for _, otherPlayer in pairs(Players:GetPlayers()) do
				if otherPlayer ~= player and otherPlayer.Character then
					local humanoid = otherPlayer.Character:FindFirstChildOfClass("Humanoid")
					if humanoid and humanoid.Health > 0 then
						table.insert(alivePlayers, otherPlayer)
					end
				end
			end
	
			if #alivePlayers > 0 then
				local randomPlayer = alivePlayers[math.random(1, #alivePlayers)]
				if randomPlayer.Character and randomPlayer.Character:FindFirstChild("HumanoidRootPart") then
					character:MoveTo(randomPlayer.Character.HumanoidRootPart.Position + Vector3.new(0, 5, 0)) -- tp above
				end
			end
		end
	end)
	
end;
task.spawn(C_4b);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.soundclick
local function C_4f()
local script = G2L["4f"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_4f);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.realone
local function C_51()
local script = G2L["51"];
	-- LocalScript inside the TextButton
	local button = script.Parent
	local stroke = button:FindFirstChild("UIStroke")
	local on = false
	local loopConnection
	local lastColor = stroke and stroke.Color or Color3.fromRGB(255, 255, 255) -- default white if nil
	
	button.MouseButton1Click:Connect(function()
		on = not on
	
		if on then
			if stroke then
				lastColor = stroke.Color
				stroke.Color = Color3.fromRGB(0, 255, 0) -- Green
			end
	
			-- Start loop
			loopConnection = game:GetService("RunService").RenderStepped:Connect(function(dt)
				if tick() % 0.5 < dt then
					local args = {
						{
							QTEGood = true
						}
					}
					game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("TemporaryReachedBindable"):FireServer(unpack(args))
				end
			end)
	
		else
			if stroke then
				stroke.Color = lastColor
			end
	
			-- Stop loop
			if loopConnection then
				loopConnection:Disconnect()
				loopConnection = nil
			end
		end
	end)
	
end;
task.spawn(C_51);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.GameMode Chooser
local function C_53()
local script = G2L["53"];
	-- LocalScript inside MainFrame
	
	local RunService = game:GetService("RunService")
	local Players    = game:GetService("Players")
	
	local player = Players.LocalPlayer
	local gui    = script.Parent  -- MainFrame
	
	-- UI references
	local chooserLabel     = gui:WaitForChild("Chooser")
	-- Buttons
	local firstBtn1        = gui:WaitForChild("first1")
	local firstBtn2        = gui:WaitForChild("first2")
	local firstBtn3        = gui:WaitForChild("first3")
	local help1            = gui:WaitForChild("help1")
	local second1          = gui:WaitForChild("second1")
	local third1           = gui:WaitForChild("third1")
	local third2           = gui:WaitForChild("third2")
	local four1            = gui:WaitForChild("four1")
	local five1            = gui:WaitForChild("five1")
	local five2            = gui:WaitForChild("five2")
	local five3            = gui:WaitForChild("five3")
	local six1             = gui:WaitForChild("six1")
	local seven1           = gui:WaitForChild("seven1")
	local red1, red2, red3 = gui:WaitForChild("red1"), gui:WaitForChild("red2"), gui:WaitForChild("red3")
	local blue1, blue2, blue3 = gui:WaitForChild("blue1"), gui:WaitForChild("blue2"), gui:WaitForChild("blue3")
	-- TextLabel specifically for RedLightGreenLight
	local firstLabel1       = gui:WaitForChild("first1Label")
	
	-- Value to track
	local gameValue = workspace:WaitForChild("Values"):WaitForChild("CurrentGame")
	
	-- Valid modes
	local validModes = {RedLightGreenLight=true,Dalgona=true,LightsOut=true,TugOfWar=true,GlassBridge=true,Mingle=true,HideAndSeek=true}
	
	-- Helper to hide all
	local function hideAll()
		firstBtn1.Visible, firstBtn2.Visible, firstBtn3.Visible = false, false, false
		help1.Visible = false
		second1.Visible = false
		third1.Visible, third2.Visible = false, false
		four1.Visible = false
		five1.Visible, five2.Visible = false, false
		five3.Visible = false
		six1.Visible = false
		seven1.Visible = false
		red1.Visible, red2.Visible, red3.Visible = false, false, false
		blue1.Visible, blue2.Visible, blue3.Visible = false, false, false
		firstLabel1.Visible = false
	end
	
	-- Waiting animation
	local isWaiting, conn = false, nil
	local function startWaiting()
		if isWaiting then return end
		isWaiting = true
		conn = RunService.Heartbeat:Connect(function()
			if not isWaiting then conn:Disconnect() return end
			local dots = (math.floor(tick()*2)%3)+1
			chooserLabel.Text = "Waiting for gamemode"..string.rep(".",dots)
		end)
	end
	local function stopWaiting()
		if conn then conn:Disconnect() end
		isWaiting = false
	end
	
	-- Vest detection
	local function detectVest()
		local live = workspace:FindFirstChild("Live")
		local mdl = live and live:FindFirstChild(player.Name)
		if not mdl then return end
		if mdl:FindFirstChild("RedVest") then
			seven1.Text = "Team is Red"
			seven1.TextColor3 = Color3.new(1,0,0)
			red1.Visible, red2.Visible, red3.Visible = true, true, true
		elseif mdl:FindFirstChild("BlueVest") then
			seven1.Text = "Team is Blue"
			seven1.TextColor3 = Color3.new(0,0,1)
			blue1.Visible, blue2.Visible, blue3.Visible = true, true, true
		end
		seven1.Visible = true
	end
	
	-- Update UI
	local function updateUI()
		local v = gameValue.Value or ""
		hideAll()
		stopWaiting()
		if not validModes[v] then
			chooserLabel.Text = "Waiting for gamemode"
			startWaiting()
		else
			chooserLabel.Text = v
			if v=="RedLightGreenLight" then
				firstBtn1.Visible, firstBtn2.Visible, firstBtn3.Visible = true, true, true
				help1.Visible = true
				firstLabel1.Visible = true
			elseif v=="Dalgona" then
				second1.Visible = true
			elseif v=="LightsOut" then
				third1.Visible, third2.Visible = true, true
			elseif v=="TugOfWar" then
				four1.Visible = true
			elseif v=="GlassBridge" then
				five1.Visible, five2.Visible, five3.Visible = true, true, true
			elseif v=="Mingle" then
				six1.Visible = true
			elseif v=="HideAndSeek" then
				detectVest()
			end
		end
	end
	
	gameValue:GetPropertyChangedSignal("Value"):Connect(updateUI)
	updateUI()
	
end;
task.spawn(C_53);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.third2.tracker
local function C_55()
local script = G2L["55"];
	local textLabel = script.Parent
	local currentAlive = workspace:WaitForChild("Values"):WaitForChild("CurrentAlive")
	
	-- Keep updating every 0.1 seconds
	while true do
		textLabel.Text = "Alive: " .. currentAlive.Value
		task.wait(0.1)
	end
	
end;
task.spawn(C_55);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.soundclick
local function C_59()
local script = G2L["59"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_59);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.realone
local function C_5b()
local script = G2L["5b"];
	-- LocalScript under your TextButton
	local button       = script.Parent
	local uiStroke     = button:FindFirstChildWhichIsA("UIStroke")
	local imgLabel     = button:FindFirstChild("fingerprint")
	
	local clicked = false
	
	button.MouseButton1Click:Connect(function()
		if clicked then return end
		clicked = true
	
		-- Turn the button visuals green
		if uiStroke then
			uiStroke.Color = Color3.fromRGB(0, 255, 0)
		end
		if imgLabel then
			imgLabel.ImageColor3 = Color3.fromRGB(0, 255, 0)
		end
	
		-- Your GlassBridge loop
		local bridge = workspace:WaitForChild("GlassBridge")
		local holder = bridge:WaitForChild("GlassHolder")
	
		for _, clonedPanel in ipairs(holder:GetChildren()) do
			if clonedPanel:IsA("Model") and clonedPanel.Name:match("^ClonedPanel") then
				for _, glassModel in ipairs(clonedPanel:GetChildren()) do
					if glassModel:IsA("Model") and (glassModel.Name == "glassmodel1" or glassModel.Name == "glassmodel2") then
						for _, part in ipairs(glassModel:GetDescendants()) do
							if part:IsA("BasePart") then
								local attrs = part:GetAttributes()
								local attrCount = 0
								local hasGlassPartTrue = false
	
								for name, value in pairs(attrs) do
									attrCount += 1
									if name == "GlassPart" and value == true then
										hasGlassPartTrue = true
									end
								end
	
								if attrCount == 1 and hasGlassPartTrue then
									part.Color = Color3.fromRGB(0, 255, 0)
								end
							end
						end
					end
				end
			end
		end
	end)
	
end;
task.spawn(C_5b);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.five3.tracker
local function C_5e()
local script = G2L["5e"];
	local textLabel = script.Parent
	
	-- Path to the source TextLabel
	local timerTextLabel = workspace:WaitForChild("GlassBridge"):WaitForChild("End")
		:WaitForChild("TimerPart"):WaitForChild("SurfaceGui"):WaitForChild("TextLabel")
	
	-- Update loop
	while true do
		textLabel.Text = "Timer " .. timerTextLabel.Text
		wait(0.2) -- Update every 0.2 seconds (can adjust as needed)
	end
	
end;
task.spawn(C_5e);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.soundclick
local function C_62()
local script = G2L["62"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_62);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.realone
local function C_64()
local script = G2L["64"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		local player = game.Players.LocalPlayer
		local character = player.Character or player.CharacterAdded:Wait()
		local humanoidRootPart = character:WaitForChild("HumanoidRootPart")
	
		humanoidRootPart.CFrame = CFrame.new(-195, 521, -1535)
	end)
	
end;
task.spawn(C_64);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.soundclick
local function C_68()
local script = G2L["68"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_68);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.realone
local function C_6a()
local script = G2L["6a"];
	local button       = script.Parent
	local stroke       = button:FindFirstChildOfClass("UIStroke")
	assert(stroke, "UIStroke not found on the button!")
	
	local originalColor = stroke.Color
	local toggled       = false
	local running       = false
	
	local function loopFire()
		running = true
		while running do
			game:GetService("Players")
				.LocalPlayer
				.Character:WaitForChild("RemoteForQTE")
				:FireServer()
			task.wait(0.1)
		end
	end
	
	button.MouseButton1Click:Connect(function()
		toggled = not toggled
		if toggled then
			stroke.Color = Color3.fromRGB(0, 255, 0)  -- turn green
			task.spawn(loopFire)
		else
			stroke.Color = originalColor             -- revert color
			running = false                          -- stop loop
		end
	end)
	
end;
task.spawn(C_6a);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.soundclick
local function C_6e()
local script = G2L["6e"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_6e);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.realone
local function C_70()
local script = G2L["70"];
	-- LocalScript inside your TextButton
	local button       = script.Parent
	local uiStroke     = button:WaitForChild("UIStroke")
	local originalColor = uiStroke.Color
	local espOn        = false
	
	local liveFolder   = workspace:WaitForChild("Live")
	
	-- Function to add/remove ESP highlights
	local function setESP(on)
		for _, model in pairs(liveFolder:GetChildren()) do
			-- Only target Models with a RedVest part
			if model:IsA("Model") and model:FindFirstChild("RedVest") then
				if on then
					if not model:FindFirstChild("ESPHighlight") then
						local hl = Instance.new("Highlight")
						hl.Name     = "ESPHighlight"
						hl.Adornee  = model
						hl.Parent   = model
					end
				else
					local existing = model:FindFirstChild("ESPHighlight")
					if existing then existing:Destroy() end
				end
			end
		end
	end
	
	-- Handle dynamic additions (if new players/models join while ESP is on)
	liveFolder.ChildAdded:Connect(function(child)
		if espOn and child:IsA("Model") and child:FindFirstChild("RedVest") then
			local hl = Instance.new("Highlight")
			hl.Name     = "ESPHighlight"
			hl.Adornee  = child
			hl.Parent   = child
		end
	end)
	
	-- Toggle button click
	button.MouseButton1Click:Connect(function()
		espOn = not espOn
		if espOn then
			uiStroke.Color = Color3.fromRGB(0, 255, 0)
			setESP(true)
		else
			uiStroke.Color = originalColor
			setESP(false)
		end
	end)
	
	-- If the button gets hidden, turn ESP off
	button:GetPropertyChangedSignal("Visible"):Connect(function()
		if not button.Visible and espOn then
			espOn = false
			uiStroke.Color = originalColor
			setESP(false)
		end
	end)
	
end;
task.spawn(C_70);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.soundclick
local function C_74()
local script = G2L["74"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_74);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.realone
local function C_76()
local script = G2L["76"];
	local button = script.Parent
	local uistroke = button:WaitForChild("UIStroke")
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local isOn = false
	local originalColor = uistroke.Color
	local lastPosition = nil -- To store the last position before teleport
	
	button.MouseButton1Click:Connect(function()
		character = player.Character or player.CharacterAdded:Wait()
		local rootPart = character:FindFirstChild("HumanoidRootPart")
		if not rootPart then return end
	
		isOn = not isOn
	
		if isOn then
			uistroke.Color = Color3.fromRGB(0, 255, 0) -- Green
			lastPosition = rootPart.Position -- Save the last position
			rootPart.CFrame = CFrame.new(178, 1053, 43)
		else
			uistroke.Color = originalColor
			if lastPosition then
				rootPart.CFrame = CFrame.new(lastPosition) -- Return to last saved position
			end
		end
	end)
	
end;
task.spawn(C_76);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.soundclick
local function C_7b()
local script = G2L["7b"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_7b);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.realone
local function C_7d()
local script = G2L["7d"];
	local button = script.Parent
	local player = game.Players.LocalPlayer
	local UIS = game:GetService("UserInputService")
	local RunService = game:GetService("RunService")
	
	-- UI elements
	local uiStroke = button:FindFirstChildOfClass("UIStroke")
	local imageLabel = button:FindFirstChild("fingerprint")
	
	-- Store original colors
	local originalStrokeColor = uiStroke and uiStroke.Color or Color3.new(1, 1, 1)
	local originalImageColor = imageLabel and imageLabel.ImageColor3 or Color3.new(1, 1, 1)
	
	-- Config
	local HITBOX_SIZE = Vector3.new(15, 15, 15)
	local HITBOX_TRANSPARENCY = 0.9
	local DEFAULT_SIZE = Vector3.new(2, 2, 1)
	local PROXIMITY_RADIUS = 10 -- only affect players within 50 studs
	
	-- Toggle state
	local hitboxEnabled = false
	local teamCheck = false -- optional team filter
	
	-- Function to apply or reset hitboxes
	local function updateHitboxes()
		local myChar = player.Character
		local myRoot = myChar and myChar:FindFirstChild("HumanoidRootPart")
		if not myRoot then return end
	
		for _, target in ipairs(game.Players:GetPlayers()) do
			if target ~= player and target.Character and target.Character:FindFirstChild("HumanoidRootPart") then
				local root = target.Character.HumanoidRootPart
				local sameTeam = (player.Team == target.Team)
				local distance = (myRoot.Position - root.Position).Magnitude
	
				if hitboxEnabled and distance <= PROXIMITY_RADIUS and (not teamCheck or not sameTeam) then
					pcall(function()
						root.Size = HITBOX_SIZE
						root.Transparency = HITBOX_TRANSPARENCY
						root.BrickColor = BrickColor.new("Really black")
						root.Material = Enum.Material.Neon
						root.CanCollide = false
					end)
				else
					pcall(function()
						root.Size = DEFAULT_SIZE
						root.Transparency = 1
						root.BrickColor = BrickColor.new("Medium stone grey")
						root.Material = Enum.Material.Plastic
						root.CanCollide = false
					end)
				end
			end
		end
	end
	
	-- Run hitbox updates on a loop while active
	RunService.RenderStepped:Connect(function()
		if hitboxEnabled then
			updateHitboxes()
		end
	end)
	
	-- On character respawn, restore hitbox state
	player.CharacterAdded:Connect(function()
		if hitboxEnabled then
			task.wait(1)
			updateHitboxes()
		end
	end)
	
	-- Button click toggles hitbox and UI
	button.MouseButton1Click:Connect(function()
		hitboxEnabled = not hitboxEnabled
	
		if uiStroke then
			uiStroke.Color = hitboxEnabled and Color3.fromRGB(0, 255, 0) or originalStrokeColor
		end
	
		if imageLabel then
			imageLabel.ImageColor3 = hitboxEnabled and Color3.fromRGB(0, 255, 0) or originalImageColor
		end
	end)
	
end;
task.spawn(C_7d);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.soundclick
local function C_81()
local script = G2L["81"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_81);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.realone
local function C_83()
local script = G2L["83"];
	local button      = script.Parent
	local uiStroke    = button:WaitForChild("UIStroke")
	local mapFolder   = workspace:WaitForChild("HideAndSeekMap"):WaitForChild("NEWFIXEDDOORS")
	local isOn        = false
	local originalCol = uiStroke.Color
	local highlights  = {}
	
	-- Collect all ExitSign parts
	local function getExitSigns()
		local parts = {}
		for _, floor in ipairs(mapFolder:GetChildren()) do
			if floor:IsA("Folder") and (floor.Name == "Floor1" or floor.Name == "Floor2" or floor.Name == "Floor3") then
				local exits = floor:FindFirstChild("EXITDOORS")
				if exits then
					for _, doorModel in ipairs(exits:GetChildren()) do
						if doorModel:IsA("Model") then
							local sign = doorModel:FindFirstChild("ExitSign")
							if sign and sign:IsA("BasePart") then
								table.insert(parts, sign)
							end
						end
					end
				end
			end
		end
		return parts
	end
	
	-- Turn ESP on: create a Highlight for each ExitSign
	local function enableESP()
		for _, part in ipairs(getExitSigns()) do
			local hl = Instance.new("Highlight")
			hl.Adornee          = part
			hl.FillTransparency  = 1
			hl.OutlineColor      = Color3.new(1, 1, 0)   -- yellow
			hl.OutlineTransparency = 0
			-- parent locally so it only appears for this player
			hl.Parent = game:GetService("CoreGui")
			table.insert(highlights, hl)
		end
	end
	
	-- Turn ESP off: destroy all highlights
	local function disableESP()
		for _, hl in ipairs(highlights) do
			if hl and hl.Parent then
				hl:Destroy()
			end
		end
		highlights = {}
	end
	
	-- Toggle function
	local function toggle()
		isOn = not isOn
		if isOn then
			uiStroke.Color = Color3.fromRGB(0, 255, 0)
			enableESP()
		else
			uiStroke.Color = originalCol
			disableESP()
		end
	end
	
	button.MouseButton1Click:Connect(toggle)
	
	-- If button goes invisible while ESP is on, clear it
	button:GetPropertyChangedSignal("Visible"):Connect(function()
		if not button.Visible and isOn then
			isOn = false
			uiStroke.Color = originalCol
			disableESP()
		end
	end)
	
end;
task.spawn(C_83);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.red1.soundclick
local function C_87()
local script = G2L["87"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_87);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.red1.realone
local function C_89()
local script = G2L["89"];
	-- LocalScript: Place this inside a TextButton
	
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local player = Players.LocalPlayer
	local button = script.Parent
	local uiStroke = button:FindFirstChildOfClass("UIStroke")
	
	-- Movement speed for interpolation
	local MOVE_SPEED = 100 -- studs per second
	
	-- State variables
	local originalStrokeColor = uiStroke and uiStroke.Color or Color3.new(1,1,1)
	local isOn = false
	local lastCFrame = nil
	local followConnection = nil
	
	-- Utility: Find closest alive target model in Workspace.Live with a child named "BlueVest"
	local function findClosestTarget()
		local liveFolder = workspace:FindFirstChild("Live")
		if not liveFolder or not player.Character then return nil end
		local hrpPlayer = player.Character:FindFirstChild("HumanoidRootPart")
		if not hrpPlayer then return nil end
	
		local closestModel = nil
		local shortestDist = math.huge
	
		for _, model in ipairs(liveFolder:GetDescendants()) do
			if model:IsA("Model") and model:FindFirstChild("BlueVest") then
				local targetHRP = model:FindFirstChild("HumanoidRootPart")
				local humanoid = model:FindFirstChildOfClass("Humanoid")
				if targetHRP and humanoid and humanoid.Health > 0 then
					local dist = (targetHRP.Position - hrpPlayer.Position).Magnitude
					if dist < shortestDist then
						shortestDist = dist
						closestModel = model
					end
				end
			end
		end
		return closestModel
	end
	
	-- Disable or enable collisions on character parts
	local function setCollisions(enabled)
		if not player.Character then return end
		for _, part in ipairs(player.Character:GetDescendants()) do
			if part:IsA("BasePart") then
				part.CanCollide = enabled
			end
		end
	end
	
	-- Start following the target by interpolation (moves through walls)
	local function startFollow(targetModel)
		if not targetModel then return end
		local character = player.Character
		if not character then return end
		local hrp = character:FindFirstChild("HumanoidRootPart")
		if not hrp then return end
	
		-- Disable collisions so you can pass through walls
		setCollisions(false)
	
		followConnection = RunService.RenderStepped:Connect(function(dt)
			if not targetModel.Parent then
				stopFollow()
				return
			end
			local targetHRP = targetModel:FindFirstChild("HumanoidRootPart")
			local targetHumanoid = targetModel:FindFirstChildOfClass("Humanoid")
			if not targetHRP or not targetHumanoid or targetHumanoid.Health <= 0 then
				stopFollow()
				return
			end
	
			-- Compute desired CFrame directly behind target
			local targetCFrame = targetHRP.CFrame
			local desiredPos = targetCFrame.Position - targetCFrame.LookVector * 0
			local desiredCFrame = CFrame.new(desiredPos, targetCFrame.Position)
	
			-- Interpolate towards desired CFrame
			hrp.CFrame = hrp.CFrame:Lerp(desiredCFrame, math.clamp(MOVE_SPEED * dt / (hrp.Position - desiredPos).Magnitude, 0, 1))
		end)
	end
	
	-- Stop following, restore position and collisions
	function stopFollow()
		if followConnection then
			followConnection:Disconnect()
			followConnection = nil
		end
		isOn = false
		if uiStroke then
			uiStroke.Color = originalStrokeColor
		end
		-- Re-enable collisions
		setCollisions(true)
		-- Restore last position
		if lastCFrame and player.Character then
			local hrp = player.Character:FindFirstChild("HumanoidRootPart")
			if hrp then
				hrp.CFrame = lastCFrame
			end
		end
	end
	
	-- Toggle function
	local function toggle()
		isOn = not isOn
		if uiStroke then
			uiStroke.Color = isOn and Color3.fromRGB(0, 255, 0) or originalStrokeColor
		end
	
		if isOn then
			-- Remember last position
			local hrp = player.Character and player.Character:FindFirstChild("HumanoidRootPart")
			if hrp then
				lastCFrame = hrp.CFrame
			end
	
			-- Acquire closest target and start following
			local target = findClosestTarget()
			if target then
				startFollow(target)
			else
				warn("No valid target found.")
				stopFollow()
			end
		else
			stopFollow()
		end
	end
	
	-- Button click handler
	button.MouseButton1Click:Connect(toggle)
	
	-- Hide button disables script
	button:GetPropertyChangedSignal("Visible"):Connect(function()
		if not button.Visible and isOn then
			stopFollow()
		end
	end)
	
end;
task.spawn(C_89);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.soundclick
local function C_8d()
local script = G2L["8d"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_8d);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.realone
local function C_8f()
local script = G2L["8f"];
	-- LocalScript inside your TextButton
	local button        = script.Parent
	local uiStroke      = button:WaitForChild("UIStroke")
	local originalColor = uiStroke.Color
	local espOn         = false
	
	local liveFolder    = workspace:WaitForChild("Live")
	
	-- Function to add/remove ESP highlights
	local function setESP(on)
		for _, model in pairs(liveFolder:GetChildren()) do
			if model:IsA("Model") and model:FindFirstChild("BlueVest") then
				if on then
					if not model:FindFirstChild("ESPHighlight") then
						local hl = Instance.new("Highlight")
						hl.Name         = "ESPHighlight"
						hl.Adornee      = model
						-- make highlight blue
						hl.FillColor    = Color3.fromRGB(0, 0, 255)
						hl.OutlineColor = Color3.fromRGB(0, 0, 255)
						hl.Parent       = model
					end
				else
					local existing = model:FindFirstChild("ESPHighlight")
					if existing then existing:Destroy() end
				end
			end
		end
	end
	
	-- Handle dynamic additions
	liveFolder.ChildAdded:Connect(function(child)
		if espOn and child:IsA("Model") and child:FindFirstChild("BlueVest") then
			local hl = Instance.new("Highlight")
			hl.Name         = "ESPHighlight"
			hl.Adornee      = child
			hl.FillColor    = Color3.fromRGB(0, 0, 255)
			hl.OutlineColor = Color3.fromRGB(0, 0, 255)
			hl.Parent       = child
		end
	end)
	
	-- Toggle button click
	button.MouseButton1Click:Connect(function()
		espOn = not espOn
		if espOn then
			uiStroke.Color = Color3.fromRGB(0, 255, 0)  -- stroke still green when on
			setESP(true)
		else
			uiStroke.Color = originalColor
			setESP(false)
		end
	end)
	
	-- Auto‑off if button is hidden
	button:GetPropertyChangedSignal("Visible"):Connect(function()
		if not button.Visible and espOn then
			espOn = false
			uiStroke.Color = originalColor
			setESP(false)
		end
	end)
	
end;
task.spawn(C_8f);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.soundclick
local function C_97()
local script = G2L["97"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_97);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.LocalScript
local function C_9a()
local script = G2L["9a"];
	local button = script.Parent
	local uistroke = button:FindFirstChildOfClass("UIStroke")
	local fingerprint = button:FindFirstChild("fingerprint")
	
	local originalStrokeColor = uistroke.Color
	local originalImageColor = fingerprint.ImageColor3
	
	local isOn = false
	local loopThread = nil
	
	local function toggle()
		isOn = not isOn
	
		if isOn then
			uistroke.Color = Color3.fromRGB(0, 255, 0)
			fingerprint.ImageColor3 = Color3.fromRGB(0, 255, 0)
	
			loopThread = task.spawn(function()
				while isOn do
					local args = { "Skipped" }
					game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("DialogueRemote"):FireServer(unpack(args))
					task.wait(1)
				end
			end)
		else
			uistroke.Color = originalStrokeColor
			fingerprint.ImageColor3 = originalImageColor
		end
	end
	
	button.MouseButton1Click:Connect(toggle)
	
end;
task.spawn(C_9a);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.soundclick
local function C_9e()
local script = G2L["9e"];
	local btn = script.Parent
	local soundService = game:GetService("SoundService")
	
	-- Click sound asset ID
	local clickSound = Instance.new("Sound")
	clickSound.SoundId = "rbxassetid://1673280232"  -- Your click sound asset ID
	clickSound.Parent = btn  -- Set the sound as a child of the button
	
	-- Play click sound when button is clicked
	btn.MouseButton1Click:Connect(function()
		-- Play the sound
		clickSound:Play()
	end)
	
end;
task.spawn(C_9e);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.LocalScript
local function C_a1()
local script = G2L["a1"];
	local button = script.Parent
	local uistroke = button:WaitForChild("UIStroke")
	local fingerprint = button:WaitForChild("fingerprint")
	local player = game:GetService("Players").LocalPlayer
	local humanoid
	
	-- Store original colors
	local originalStrokeColor = uistroke.Color
	local originalImageColor = fingerprint.ImageColor3
	
	-- Infinite jump state
	local isOn = false
	local connection
	
	button.MouseButton1Click:Connect(function()
		isOn = not isOn
	
		if isOn then
			-- Turn UI green
			uistroke.Color = Color3.fromRGB(0, 255, 0)
			fingerprint.ImageColor3 = Color3.fromRGB(0, 255, 0)
	
			-- Infinite jump logic
			connection = game:GetService("UserInputService").JumpRequest:Connect(function()
				local character = player.Character
				if character then
					humanoid = character:FindFirstChildOfClass("Humanoid")
					if humanoid then
						humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
					end
				end
			end)
	
		else
			-- Restore original colors
			uistroke.Color = originalStrokeColor
			fingerprint.ImageColor3 = originalImageColor
	
			-- Disconnect jump connection
			if connection then
				connection:Disconnect()
				connection = nil
			end
		end
	end)
	
end;
task.spawn(C_a1);
-- StarterGui.omarInkGame.Info.drag localscript
local function C_a2()
local script = G2L["a2"];
	local frame = script.Parent
	local UIS = game:GetService("UserInputService")
	
	local dragging = false
	local dragStart
	local startPos
	local activeInput -- Used only for touch
	
	-- Update frame position
	local function update(input)
		local delta = input.Position - dragStart
		frame.Position = UDim2.new(
			startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y
		)
	end
	
	frame.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = frame.Position
			activeInput = input
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	frame.InputChanged:Connect(function(input)
		if dragging then
			if input.UserInputType == Enum.UserInputType.Touch and input == activeInput then
				update(input)
			elseif input.UserInputType == Enum.UserInputType.MouseMovement then
				update(input)
			end
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if dragging then
			if input.UserInputType == Enum.UserInputType.Touch and input == activeInput then
				update(input)
			elseif input.UserInputType == Enum.UserInputType.MouseMovement then
				update(input)
			end
		end
	end)
	
end;
task.spawn(C_a2);
-- StarterGui.omarInkGame.Changer
local function C_a3()
local script = G2L["a3"];
	-- LocalScript: UISelectionController (Esp & Misc Only)
	print("[UISelectionController] Script initializing...")
	
	-- Find the parent ScreenGui
	local screenGui = script:FindFirstAncestorWhichIsA("ScreenGui")
	if not screenGui then
		warn("[UISelectionController] ERROR: Not inside a ScreenGui!")
		return
	end
	print("[UISelectionController] Found ScreenGui: " .. screenGui.Name)
	
	-- Grab Info and Sigma
	local info = screenGui:FindFirstChild("Info")
	if not info then
		warn("[UISelectionController] ERROR: Info frame not found under ScreenGui")
		return
	end
	print("[UISelectionController] Found Info: " .. info.Name)
	
	local sigma = info:FindFirstChild("sigma")
	if not sigma then
		warn("[UISelectionController] ERROR: Sigma frame not found under Info")
		return
	end
	print("[UISelectionController] Found Sigma: " .. sigma.Name)
	
	-- Grab Selection
	local selection = sigma:FindFirstChild("Selection")
	if not selection then
		warn("[UISelectionController] ERROR: Selection frame not found under Sigma")
		return
	end
	print("[UISelectionController] Found Selection: " .. selection.Name)
	
	-- Define active tabs only: Esp and Misc
	local tabs = {
		Esp  = {buttonName = "Esp",  frameName = "EspFrame"},
		Misc = {buttonName = "Misc", frameName = "MiscFrame"},
		Main = {buttonName = "Main", frameName = "MainFrame"},
	}
	
	-- Prepare storage
	local activeKey
	local defaultStrokes = {}
	
	-- Initialize each tab
	for key, def in pairs(tabs) do
		local btn = selection:FindFirstChild(def.buttonName)
		if not btn or not btn:IsA("TextButton") then
			warn(string.format("[UISelectionController] ERROR: %s button '%s' not found or not a TextButton", key, def.buttonName))
		else
			print(string.format("[UISelectionController] Found button '%s' for %s", def.buttonName, key))
		end
	
		local frm = sigma:FindFirstChild(def.frameName)
		if not frm or not frm:IsA("Frame") then
			warn(string.format("[UISelectionController] ERROR: %s frame '%s' not found or not a Frame", key, def.frameName))
		else
			print(string.format("[UISelectionController] Found frame '%s' for %s", def.frameName, key))
		end
	
		local stroke = btn:FindFirstChildOfClass("UIStroke") or Instance.new("UIStroke", btn)
		defaultStrokes[key] = stroke.Color
	
		if frm then frm.Visible = false end
	
		def.button = btn
		def.frame  = frm
		def.stroke = stroke
	end
	
	-- Tab switch function
	local function switchTo(key)
		print("[UISelectionController] switchTo called for " .. key)
		if activeKey and tabs[activeKey].stroke then
			tabs[activeKey].stroke.Color = defaultStrokes[activeKey]
			if tabs[activeKey].frame then tabs[activeKey].frame.Visible = false end
			print("[UISelectionController] Hiding frame for " .. activeKey)
		end
	
		local current = tabs[key]
		if not current then
			warn("[UISelectionController] ERROR: No tab definition for key " .. key)
			return
		end
		current.stroke.Color = Color3.new(1, 0, 0)
		if current.frame then current.frame.Visible = true end
		print("[UISelectionController] Showing frame for " .. key)
		activeKey = key
	end
	
	-- Connect tab buttons
	for key, def in pairs(tabs) do
		if def.button then
			def.button.Activated:Connect(function()
				print("[UISelectionController] Button " .. def.buttonName .. " activated")
				switchTo(key)
			end)
			print("[UISelectionController] Connected Activated for " .. def.buttonName)
		end
	end
	
	-- Auto-open Esp tab
	switchTo("Esp")
	
end;
task.spawn(C_a3);

return G2L["1"], require;
