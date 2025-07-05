--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 125 | Scripts: 30 | Modules: 0 | Tags: 0
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
G2L["2c"]["Visible"] = false;
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
G2L["37"]["Size"] = UDim2.new(0, 384, 0, 48);
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


-- StarterGui.omarInkGame.Info.sigma.MiscFrame
G2L["6b"] = Instance.new("Frame", G2L["9"]);
G2L["6b"]["Active"] = true;
G2L["6b"]["ZIndex"] = 0;
G2L["6b"]["BorderSizePixel"] = 0;
G2L["6b"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["6b"]["Size"] = UDim2.new(0.7802, 0, 1.00699, 0);
G2L["6b"]["Position"] = UDim2.new(0.2198, 0, 0, 0);
G2L["6b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6b"]["Name"] = [[MiscFrame]];
G2L["6b"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.UIStroke
G2L["6c"] = Instance.new("UIStroke", G2L["6b"]);
G2L["6c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["6c"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.UICorner
G2L["6d"] = Instance.new("UICorner", G2L["6b"]);
G2L["6d"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third
G2L["6e"] = Instance.new("TextButton", G2L["6b"]);
G2L["6e"]["TextWrapped"] = true;
G2L["6e"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["6e"]["BorderSizePixel"] = 0;
G2L["6e"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["6e"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["6e"]["TextSize"] = 14;
G2L["6e"]["TextScaled"] = true;
G2L["6e"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6e"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6e"]["Size"] = UDim2.new(0.75106, 0, 0.08456, 0);
G2L["6e"]["Name"] = [[third]];
G2L["6e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6e"]["Text"] = [[Auto Skip]];
G2L["6e"]["Position"] = UDim2.new(0.09635, 0, 0.07166, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.UICorner
G2L["6f"] = Instance.new("UICorner", G2L["6e"]);
G2L["6f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.UIStroke
G2L["70"] = Instance.new("UIStroke", G2L["6e"]);
G2L["70"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["70"]["Thickness"] = 1.7;
G2L["70"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.soundclick
G2L["71"] = Instance.new("LocalScript", G2L["6e"]);
G2L["71"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.fingerprint
G2L["72"] = Instance.new("ImageLabel", G2L["6e"]);
G2L["72"]["BorderSizePixel"] = 0;
G2L["72"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["72"]["Image"] = [[rbxassetid://12333784627]];
G2L["72"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["72"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["72"]["BackgroundTransparency"] = 1;
G2L["72"]["Name"] = [[fingerprint]];
G2L["72"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.UIPadding
G2L["73"] = Instance.new("UIPadding", G2L["6e"]);
G2L["73"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.LocalScript
G2L["74"] = Instance.new("LocalScript", G2L["6e"]);



-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four
G2L["75"] = Instance.new("TextButton", G2L["6b"]);
G2L["75"]["TextWrapped"] = true;
G2L["75"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["75"]["BorderSizePixel"] = 0;
G2L["75"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["75"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["75"]["TextSize"] = 14;
G2L["75"]["TextScaled"] = true;
G2L["75"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["75"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["75"]["Size"] = UDim2.new(0.75106, 0, 0.08456, 0);
G2L["75"]["Name"] = [[four]];
G2L["75"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["75"]["Text"] = [[Inf Jump]];
G2L["75"]["Position"] = UDim2.new(0.09635, 0, 0.22913, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.UICorner
G2L["76"] = Instance.new("UICorner", G2L["75"]);
G2L["76"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.UIStroke
G2L["77"] = Instance.new("UIStroke", G2L["75"]);
G2L["77"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["77"]["Thickness"] = 1.7;
G2L["77"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.soundclick
G2L["78"] = Instance.new("LocalScript", G2L["75"]);
G2L["78"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.fingerprint
G2L["79"] = Instance.new("ImageLabel", G2L["75"]);
G2L["79"]["BorderSizePixel"] = 0;
G2L["79"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["79"]["Image"] = [[rbxassetid://12333784627]];
G2L["79"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["79"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["79"]["BackgroundTransparency"] = 1;
G2L["79"]["Name"] = [[fingerprint]];
G2L["79"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.UIPadding
G2L["7a"] = Instance.new("UIPadding", G2L["75"]);
G2L["7a"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.LocalScript
G2L["7b"] = Instance.new("LocalScript", G2L["75"]);



-- StarterGui.omarInkGame.Info.drag localscript
G2L["7c"] = Instance.new("LocalScript", G2L["3"]);
G2L["7c"]["Name"] = [[drag localscript]];


-- StarterGui.omarInkGame.Changer
G2L["7d"] = Instance.new("LocalScript", G2L["1"]);
G2L["7d"]["Name"] = [[Changer]];


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
	
		humanoidRootPart.CFrame = CFrame.new(-97, 1023, 83)
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
		doHelp(btn2, Vector3.new(-97, 1023, 83), "You can’t help this Target.")
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
	
	local gui = script.Parent  -- MainFrame
	
	-- UI references
	local chooserLabel = gui:WaitForChild("Chooser")
	local first1 = gui:WaitForChild("first1")
	local first2 = gui:WaitForChild("first2")
	local first3 = gui:WaitForChild("first3")
	local help1  = gui:WaitForChild("help1")
	local second1 = gui:WaitForChild("second1")
	local third1  = gui:WaitForChild("third1")
	local third2  = gui:WaitForChild("third2")
	local four1   = gui:WaitForChild("four1")
	local five1   = gui:WaitForChild("five1")
	local five2   = gui:WaitForChild("five2")
	local five3   = gui:WaitForChild("five3")
	local six1    = gui:WaitForChild("six1")
	
	-- Value to track
	local gameValue = workspace:WaitForChild("Values"):WaitForChild("CurrentGame")
	
	-- List of valid modes
	local validModes = {
		RedLightGreenLight = true,
		Dalgona            = true,
		LightsOut          = true,
		TugOfWar           = true,
		GlassBridge        = true,
		Mingle             = true,
	}
	
	-- Utility to hide everything
	local function hideAll()
		first1.Visible, first2.Visible, first3.Visible = false, false, false
		help1.Visible   = false
		second1.Visible = false
		third1.Visible, third2.Visible = false, false
		four1.Visible   = false
		five1.Visible, five2.Visible = false, false
		five3.Visible = false
		six1.Visible = false
	end
	
	-- Waiting animation control
	local isWaiting, animConn = false, nil
	
	local function startWaitingAnimation()
		if isWaiting then return end
		isWaiting = true
		animConn = RunService.Heartbeat:Connect(function()
			if not isWaiting then
				animConn:Disconnect()
				return
			end
			local dots = (math.floor(tick() * 2) % 3) + 1
			chooserLabel.Text = "Waiting for gamemode" .. string.rep(".", dots)
		end)
	end
	
	local function stopWaitingAnimation()
		if not isWaiting then return end
		isWaiting = false
		if animConn then
			animConn:Disconnect()
			animConn = nil
		end
	end
	
	-- Main UI update
	local function updateUI()
		local v = gameValue.Value or ""
	
		-- if not a valid mode, treat as waiting
		if not validModes[v] then
			hideAll()
			stopWaitingAnimation()
			chooserLabel.Text = "Waiting for gamemode"
			startWaitingAnimation()
			return
		end
	
		-- valid mode
		stopWaitingAnimation()
		chooserLabel.Text = v
		hideAll()
	
		if v == "RedLightGreenLight" then
			first1.Visible, first2.Visible, first3.Visible = true, true, true
			help1.Visible = true
	
		elseif v == "Dalgona" then
			second1.Visible = true
	
		elseif v == "LightsOut" then
			third1.Visible = true
			third2.Visible = true
	
		elseif v == "TugOfWar" then
			four1.Visible = true
	
		elseif v == "GlassBridge" then
			five1.Visible = true
			five2.Visible = true
			five3.Visible = true
	
		elseif v == "Mingle" then
			six1.Visible = true
		end
	end
	
	-- Connect change listener
	gameValue:GetPropertyChangedSignal("Value"):Connect(updateUI)
	
	-- Initial call
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
	local button = script.Parent
	local stroke = button:FindFirstChildOfClass("UIStroke")
	local player = game:GetService("Players").LocalPlayer
	local remote = player.Character:WaitForChild("RemoteForQTE")
	
	local originalColor = stroke.Color
	local toggled = false
	local running = false
	
	local function startLoop()
		running = true
		while running do
			remote:FireServer()
			wait(0.5)
		end
	end
	
	button.MouseButton1Click:Connect(function()
		toggled = not toggled
	
		if toggled then
			stroke.Color = Color3.fromRGB(0, 255, 0) -- Green
			task.spawn(startLoop)
		else
			stroke.Color = originalColor
			running = false
		end
	end)
	
end;
task.spawn(C_6a);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.soundclick
local function C_71()
local script = G2L["71"];
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
task.spawn(C_71);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.LocalScript
local function C_74()
local script = G2L["74"];
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
task.spawn(C_74);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.soundclick
local function C_78()
local script = G2L["78"];
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
task.spawn(C_78);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.LocalScript
local function C_7b()
local script = G2L["7b"];
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
task.spawn(C_7b);
-- StarterGui.omarInkGame.Info.drag localscript
local function C_7c()
local script = G2L["7c"];
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
task.spawn(C_7c);
-- StarterGui.omarInkGame.Changer
local function C_7d()
local script = G2L["7d"];
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
task.spawn(C_7d);

return G2L["1"], require;
