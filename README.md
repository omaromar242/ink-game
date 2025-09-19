local G2L = {};

-- CoreGui.omarInkGame
G2L["1"] = Instance.new("ScreenGui", game:GetService("CoreGui"))
G2L["1"].DisplayOrder = 9999
G2L["1"].Name = "omarInkGame"
G2L["1"].ZIndexBehavior = Enum.ZIndexBehavior.Sibling
G2L["1"].ResetOnSpawn = false


-- StarterGui.omarInkGame.Controls
G2L["2"] = Instance.new("LocalScript", G2L["1"]);
G2L["2"]["Name"] = [[Controls]];


-- StarterGui.omarInkGame.Changer
G2L["3"] = Instance.new("LocalScript", G2L["1"]);
G2L["3"]["Name"] = [[Changer]];


-- StarterGui.omarInkGame.Info
G2L["4"] = Instance.new("Frame", G2L["1"]);
G2L["4"]["Active"] = true;
G2L["4"]["ZIndex"] = 100000;
G2L["4"]["BorderSizePixel"] = 0;
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["Size"] = UDim2.new(0.35232, 0, 0.04556, 0);
G2L["4"]["Position"] = UDim2.new(0.31101, 0, 0.21012, 0);
G2L["4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["Name"] = [[Info]];


-- StarterGui.omarInkGame.Info.drag localscript
G2L["5"] = Instance.new("LocalScript", G2L["4"]);
G2L["5"]["Name"] = [[drag localscript]];


-- StarterGui.omarInkGame.Info.UICorner
G2L["6"] = Instance.new("UICorner", G2L["4"]);
G2L["6"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.UIStroke
G2L["7"] = Instance.new("UIStroke", G2L["4"]);
G2L["7"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["7"]["Thickness"] = 0;


-- StarterGui.omarInkGame.Info.GameName
G2L["8"] = Instance.new("TextLabel", G2L["4"]);
G2L["8"]["TextWrapped"] = true;
G2L["8"]["ZIndex"] = 1000000000;
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["TextSize"] = 14;
G2L["8"]["TextScaled"] = true;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["8"]["TextColor3"] = Color3.fromRGB(219, 219, 219);
G2L["8"]["BackgroundTransparency"] = 1;
G2L["8"]["Size"] = UDim2.new(0.66565, 0, 0.94601, 0);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Text"] = [[Ink Game v0.1]];
G2L["8"]["Name"] = [[GameName]];
G2L["8"]["Position"] = UDim2.new(-0.13908, 0, -0.03235, 0);


-- StarterGui.omarInkGame.Info.minimize
G2L["9"] = Instance.new("ImageButton", G2L["4"]);
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["ZIndex"] = 100000;
G2L["9"]["Image"] = [[rbxassetid://73326636016913]];
G2L["9"]["Size"] = UDim2.new(0.06928, 0, 0.6257, 0);
G2L["9"]["BackgroundTransparency"] = 1;
G2L["9"]["Name"] = [[minimize]];
G2L["9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9"]["Position"] = UDim2.new(0.83874, 0, 0.1414, 0);


-- StarterGui.omarInkGame.Info.XButton
G2L["a"] = Instance.new("ImageButton", G2L["4"]);
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["ZIndex"] = 100000;
G2L["a"]["Image"] = [[rbxassetid://103344771690872]];
G2L["a"]["Size"] = UDim2.new(0.04077, 0, 0.65806, 0);
G2L["a"]["BackgroundTransparency"] = 1;
G2L["a"]["Name"] = [[XButton]];
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["Position"] = UDim2.new(0.93261, 0, 0.1414, 0);


-- StarterGui.omarInkGame.Info.sigma
G2L["b"] = Instance.new("Frame", G2L["4"]);
G2L["b"]["Active"] = true;
G2L["b"]["ZIndex"] = 0;
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["b"]["Size"] = UDim2.new(0.98697, 0, 11.01718, 0);
G2L["b"]["Position"] = UDim2.new(0.00451, 0, 0.92467, 0);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Name"] = [[sigma]];
G2L["b"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarInkGame.Info.sigma.UICorner
G2L["c"] = Instance.new("UICorner", G2L["b"]);
G2L["c"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.EspFrame
G2L["d"] = Instance.new("Frame", G2L["b"]);
G2L["d"]["Visible"] = false;
G2L["d"]["Active"] = true;
G2L["d"]["ZIndex"] = 0;
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(47, 47, 47);
G2L["d"]["Size"] = UDim2.new(0.78204, 0, 1.00699, 0);
G2L["d"]["Position"] = UDim2.new(0.21796, 0, 0, 0);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["Name"] = [[EspFrame]];
G2L["d"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Main
G2L["e"] = Instance.new("LocalScript", G2L["d"]);
G2L["e"]["Name"] = [[Main]];


-- StarterGui.omarInkGame.Info.sigma.EspFrame.UICorner
G2L["f"] = Instance.new("UICorner", G2L["d"]);
G2L["f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.playerimage
G2L["10"] = Instance.new("ImageLabel", G2L["d"]);
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["Image"] = [[rbxasset://textures/ui/GuiImagePlaceholder.png]];
G2L["10"]["Size"] = UDim2.new(0.27217, 0, 0.29805, 0);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["BackgroundTransparency"] = 1;
G2L["10"]["Name"] = [[playerimage]];
G2L["10"]["Position"] = UDim2.new(0.01103, 0, 0.06069, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.playerimage.UICorner
G2L["11"] = Instance.new("UICorner", G2L["10"]);
G2L["11"]["CornerRadius"] = UDim.new(10, 10);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Welcom
G2L["12"] = Instance.new("TextLabel", G2L["d"]);
G2L["12"]["TextWrapped"] = true;
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["TextSize"] = 14;
G2L["12"]["TextScaled"] = true;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["TextDirection"] = Enum.TextDirection.LeftToRight;
G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["12"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["BackgroundTransparency"] = 1;
G2L["12"]["Size"] = UDim2.new(0.63963, 0, 0.12589, 0);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Text"] = [[WELCOM]];
G2L["12"]["Name"] = [[Welcom]];
G2L["12"]["Position"] = UDim2.new(0.31615, 0, 0.17866, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.credits
G2L["13"] = Instance.new("TextLabel", G2L["d"]);
G2L["13"]["TextWrapped"] = true;
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["TextSize"] = 14;
G2L["13"]["TextScaled"] = true;
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["13"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["BackgroundTransparency"] = 1;
G2L["13"]["Size"] = UDim2.new(0.97655, 0, 0.17498, 0);
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["Text"] = [[Credits: omar: /dev/owner/designer/scripter]];
G2L["13"]["Name"] = [[credits]];
G2L["13"]["Position"] = UDim2.new(-0, 0, 0.44647, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy
G2L["14"] = Instance.new("TextButton", G2L["d"]);
G2L["14"]["TextWrapped"] = true;
G2L["14"]["BorderSizePixel"] = 0;
G2L["14"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["TextSize"] = 14;
G2L["14"]["TextScaled"] = true;
G2L["14"]["BackgroundColor3"] = Color3.fromRGB(137, 137, 137);
G2L["14"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["14"]["Size"] = UDim2.new(0.16083, 0, 0.10082, 0);
G2L["14"]["Name"] = [[Copy]];
G2L["14"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["14"]["Text"] = [[COPY]];
G2L["14"]["Position"] = UDim2.new(0.76289, 0, 0.85019, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.LocalScript
G2L["15"] = Instance.new("LocalScript", G2L["14"]);



-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.soundclick
G2L["16"] = Instance.new("LocalScript", G2L["14"]);
G2L["16"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.UICorner
G2L["17"] = Instance.new("UICorner", G2L["14"]);
G2L["17"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.UIStroke
G2L["18"] = Instance.new("UIStroke", G2L["14"]);
G2L["18"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["18"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy
G2L["19"] = Instance.new("TextButton", G2L["d"]);
G2L["19"]["TextWrapped"] = true;
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["TextSize"] = 14;
G2L["19"]["TextScaled"] = true;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(137, 137, 137);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["19"]["Size"] = UDim2.new(0.14722, 0, 0.09403, 0);
G2L["19"]["Name"] = [[Copy]];
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[COPY]];
G2L["19"]["Position"] = UDim2.new(0.82933, 0, 0.70494, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.LocalScript
G2L["1a"] = Instance.new("LocalScript", G2L["19"]);



-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.soundclick
G2L["1b"] = Instance.new("LocalScript", G2L["19"]);
G2L["1b"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.UICorner
G2L["1c"] = Instance.new("UICorner", G2L["19"]);
G2L["1c"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.UIStroke
G2L["1d"] = Instance.new("UIStroke", G2L["19"]);
G2L["1d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["1d"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Link
G2L["1e"] = Instance.new("TextLabel", G2L["d"]);
G2L["1e"]["TextWrapped"] = true;
G2L["1e"]["BorderSizePixel"] = 0;
G2L["1e"]["TextSize"] = 14;
G2L["1e"]["TextScaled"] = true;
G2L["1e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1e"]["BackgroundTransparency"] = 1;
G2L["1e"]["Size"] = UDim2.new(0.78978, 0, 0.11608, 0);
G2L["1e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1e"]["Text"] = [[ discord: https://discord.gg/HJSfaPTDCX]];
G2L["1e"]["Name"] = [[Link]];
G2L["1e"]["Position"] = UDim2.new(0.01233, 0, 0.68098, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.subto
G2L["1f"] = Instance.new("TextLabel", G2L["d"]);
G2L["1f"]["TextWrapped"] = true;
G2L["1f"]["BorderSizePixel"] = 0;
G2L["1f"]["TextSize"] = 14;
G2L["1f"]["TextScaled"] = true;
G2L["1f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1f"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1f"]["BackgroundTransparency"] = 1;
G2L["1f"]["Size"] = UDim2.new(0.70246, 0, 0.12617, 0);
G2L["1f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1f"]["Text"] = [[Channel: omargamer8198]];
G2L["1f"]["Name"] = [[subto]];
G2L["1f"]["Position"] = UDim2.new(0.04627, 0, 0.82173, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Toggle
G2L["20"] = Instance.new("TextButton", G2L["d"]);
G2L["20"]["TextWrapped"] = true;
G2L["20"]["BorderSizePixel"] = 0;
G2L["20"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["20"]["TextSize"] = 14;
G2L["20"]["TextScaled"] = true;
G2L["20"]["BackgroundColor3"] = Color3.fromRGB(69, 69, 69);
G2L["20"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["20"]["Size"] = UDim2.new(0.18468, 0, 0.0741, 0);
G2L["20"]["Name"] = [[Toggle]];
G2L["20"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["20"]["Text"] = [[Hide]];
G2L["20"]["Visible"] = false;
G2L["20"]["Position"] = UDim2.new(0.53122, 0, 0.0765, 0);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Toggle.UICorner
G2L["21"] = Instance.new("UICorner", G2L["20"]);
G2L["21"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.EspFrame.Toggle.UIStroke
G2L["22"] = Instance.new("UIStroke", G2L["20"]);
G2L["22"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["22"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.Selection
G2L["23"] = Instance.new("Frame", G2L["b"]);
G2L["23"]["Active"] = true;
G2L["23"]["ZIndex"] = 0;
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(36, 36, 36);
G2L["23"]["Size"] = UDim2.new(0.2198, 0, 1.00699, 0);
G2L["23"]["Position"] = UDim2.new(0, 0, 0, 0);
G2L["23"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["23"]["Name"] = [[Selection]];


-- StarterGui.omarInkGame.Info.sigma.Selection.Esp
G2L["24"] = Instance.new("TextButton", G2L["23"]);
G2L["24"]["TextWrapped"] = true;
G2L["24"]["BorderSizePixel"] = 0;
G2L["24"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["24"]["TextSize"] = 14;
G2L["24"]["TextScaled"] = true;
G2L["24"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["24"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["24"]["Size"] = UDim2.new(0.77026, 0, 0.12599, 0);
G2L["24"]["Name"] = [[Esp]];
G2L["24"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["24"]["Text"] = [[Home]];
G2L["24"]["Position"] = UDim2.new(0.1103, 0, 0.05268, 0);


-- StarterGui.omarInkGame.Info.sigma.Selection.Esp.UICorner
G2L["25"] = Instance.new("UICorner", G2L["24"]);
G2L["25"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.Selection.Esp.UIStroke
G2L["26"] = Instance.new("UIStroke", G2L["24"]);
G2L["26"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["26"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.Selection.UICorner
G2L["27"] = Instance.new("UICorner", G2L["23"]);
G2L["27"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.Selection.Main
G2L["28"] = Instance.new("TextButton", G2L["23"]);
G2L["28"]["TextWrapped"] = true;
G2L["28"]["BorderSizePixel"] = 0;
G2L["28"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["TextSize"] = 14;
G2L["28"]["TextScaled"] = true;
G2L["28"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["28"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["28"]["Size"] = UDim2.new(0.77025, 0, 0.11457, 0);
G2L["28"]["Name"] = [[Main]];
G2L["28"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["28"]["Text"] = [[Main]];
G2L["28"]["Position"] = UDim2.new(0.1103, 0, 0.21603, 0);


-- StarterGui.omarInkGame.Info.sigma.Selection.Main.UICorner
G2L["29"] = Instance.new("UICorner", G2L["28"]);
G2L["29"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.Selection.Main.UIStroke
G2L["2a"] = Instance.new("UIStroke", G2L["28"]);
G2L["2a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2a"]["Thickness"] = 2;


-- StarterGui.omarInkGame.Info.sigma.Selection.Misc
G2L["2b"] = Instance.new("TextButton", G2L["23"]);
G2L["2b"]["TextWrapped"] = true;
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["TextSize"] = 14;
G2L["2b"]["TextScaled"] = true;
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(51, 94, 33);
G2L["2b"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2b"]["Size"] = UDim2.new(0.77025, 0, 0.11457, 0);
G2L["2b"]["Name"] = [[Misc]];
G2L["2b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["Text"] = [[Misc]];
G2L["2b"]["Position"] = UDim2.new(0.11, 0, 0.364, 0);


-- StarterGui.omarInkGame.Info.sigma.Selection.Misc.UICorner
G2L["2c"] = Instance.new("UICorner", G2L["2b"]);
G2L["2c"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.Selection.Misc.UIStroke
G2L["2d"] = Instance.new("UIStroke", G2L["2b"]);
G2L["2d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2d"]["Thickness"] = 2;


-- StarterGui.omarInkGame.Info.sigma.MiscFrame
G2L["2e"] = Instance.new("Frame", G2L["b"]);
G2L["2e"]["Visible"] = false;
G2L["2e"]["Active"] = true;
G2L["2e"]["ZIndex"] = 0;
G2L["2e"]["BorderSizePixel"] = 0;
G2L["2e"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["2e"]["Size"] = UDim2.new(0.7802, 0, 1.00699, 0);
G2L["2e"]["Position"] = UDim2.new(0.2198, 0, 0, 0);
G2L["2e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["Name"] = [[MiscFrame]];
G2L["2e"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.UIStroke
G2L["2f"] = Instance.new("UIStroke", G2L["2e"]);
G2L["2f"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["2f"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.UICorner
G2L["30"] = Instance.new("UICorner", G2L["2e"]);
G2L["30"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third
G2L["31"] = Instance.new("TextButton", G2L["2e"]);
G2L["31"]["TextWrapped"] = true;
G2L["31"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["31"]["BorderSizePixel"] = 0;
G2L["31"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["31"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["31"]["TextSize"] = 14;
G2L["31"]["TextScaled"] = true;
G2L["31"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["31"]["Size"] = UDim2.new(0.75106, 0, 0.08456, 0);
G2L["31"]["Name"] = [[third]];
G2L["31"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["31"]["Text"] = [[Auto Skip Dialogue]];
G2L["31"]["Position"] = UDim2.new(0.09635, 0, 0.07166, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.soundclick
G2L["32"] = Instance.new("LocalScript", G2L["31"]);
G2L["32"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.LocalScript
G2L["33"] = Instance.new("LocalScript", G2L["31"]);



-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.UICorner
G2L["34"] = Instance.new("UICorner", G2L["31"]);
G2L["34"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.UIStroke
G2L["35"] = Instance.new("UIStroke", G2L["31"]);
G2L["35"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["35"]["Thickness"] = 1.7;
G2L["35"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.fingerprint
G2L["36"] = Instance.new("ImageLabel", G2L["31"]);
G2L["36"]["BorderSizePixel"] = 0;
G2L["36"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["36"]["Image"] = [[rbxassetid://12333784627]];
G2L["36"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["36"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["36"]["BackgroundTransparency"] = 1;
G2L["36"]["Name"] = [[fingerprint]];
G2L["36"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.UIPadding
G2L["37"] = Instance.new("UIPadding", G2L["31"]);
G2L["37"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four
G2L["38"] = Instance.new("TextButton", G2L["2e"]);
G2L["38"]["TextWrapped"] = true;
G2L["38"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["38"]["BorderSizePixel"] = 0;
G2L["38"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["38"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["38"]["TextSize"] = 14;
G2L["38"]["TextScaled"] = true;
G2L["38"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["38"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["38"]["Size"] = UDim2.new(0.75106, 0, 0.08456, 0);
G2L["38"]["Name"] = [[four]];
G2L["38"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["38"]["Text"] = [[Inf Jump]];
G2L["38"]["Position"] = UDim2.new(0.09635, 0, 0.22913, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.soundclick
G2L["39"] = Instance.new("LocalScript", G2L["38"]);
G2L["39"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.LocalScript
G2L["3a"] = Instance.new("LocalScript", G2L["38"]);



-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.UICorner
G2L["3b"] = Instance.new("UICorner", G2L["38"]);
G2L["3b"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.UIStroke
G2L["3c"] = Instance.new("UIStroke", G2L["38"]);
G2L["3c"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3c"]["Thickness"] = 1.7;
G2L["3c"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.fingerprint
G2L["3d"] = Instance.new("ImageLabel", G2L["38"]);
G2L["3d"]["BorderSizePixel"] = 0;
G2L["3d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3d"]["Image"] = [[rbxassetid://12333784627]];
G2L["3d"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["3d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3d"]["BackgroundTransparency"] = 1;
G2L["3d"]["Name"] = [[fingerprint]];
G2L["3d"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.UIPadding
G2L["3e"] = Instance.new("UIPadding", G2L["38"]);
G2L["3e"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.five
G2L["3f"] = Instance.new("TextButton", G2L["2e"]);
G2L["3f"]["TextWrapped"] = true;
G2L["3f"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["3f"]["BorderSizePixel"] = 0;
G2L["3f"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["3f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["3f"]["TextSize"] = 14;
G2L["3f"]["TextScaled"] = true;
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3f"]["Size"] = UDim2.new(0.75106, 0, 0.08456, 0);
G2L["3f"]["Name"] = [[five]];
G2L["3f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["Text"] = [[unlock Dash]];
G2L["3f"]["Position"] = UDim2.new(0.09635, 0, 0.36328, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.five.soundclick
G2L["40"] = Instance.new("LocalScript", G2L["3f"]);
G2L["40"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.five.LocalScript
G2L["41"] = Instance.new("LocalScript", G2L["3f"]);



-- StarterGui.omarInkGame.Info.sigma.MiscFrame.five.UICorner
G2L["42"] = Instance.new("UICorner", G2L["3f"]);
G2L["42"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.five.UIStroke
G2L["43"] = Instance.new("UIStroke", G2L["3f"]);
G2L["43"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["43"]["Thickness"] = 1.7;
G2L["43"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.five.fingerprint
G2L["44"] = Instance.new("ImageLabel", G2L["3f"]);
G2L["44"]["BorderSizePixel"] = 0;
G2L["44"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["44"]["Image"] = [[rbxassetid://12333784627]];
G2L["44"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["44"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["44"]["BackgroundTransparency"] = 1;
G2L["44"]["Name"] = [[fingerprint]];
G2L["44"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MiscFrame.five.UIPadding
G2L["45"] = Instance.new("UIPadding", G2L["3f"]);
G2L["45"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame
G2L["46"] = Instance.new("Frame", G2L["b"]);
G2L["46"]["Visible"] = false;
G2L["46"]["Active"] = true;
G2L["46"]["ZIndex"] = 0;
G2L["46"]["BorderSizePixel"] = 0;
G2L["46"]["BackgroundColor3"] = Color3.fromRGB(53, 53, 53);
G2L["46"]["Size"] = UDim2.new(0.7802, 0, 1.00699, 0);
G2L["46"]["Position"] = UDim2.new(0.2198, 0, 0, 0);
G2L["46"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["46"]["Name"] = [[MainFrame]];
G2L["46"]["BackgroundTransparency"] = 0.2;


-- StarterGui.omarInkGame.Info.sigma.MainFrame.Green Red Light
G2L["47"] = Instance.new("LocalScript", G2L["46"]);
G2L["47"]["Name"] = [[Green Red Light]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.GameMode Chooser
G2L["48"] = Instance.new("LocalScript", G2L["46"]);
G2L["48"]["Name"] = [[GameMode Chooser]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1
G2L["49"] = Instance.new("TextButton", G2L["46"]);
G2L["49"]["TextWrapped"] = true;
G2L["49"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["49"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["49"]["TextSize"] = 14;
G2L["49"]["TextScaled"] = true;
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["49"]["Size"] = UDim2.new(0.71832, 0, 0.11259, 0);
G2L["49"]["Name"] = [[blue1]];
G2L["49"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["Text"] = [[Go safe Place]];
G2L["49"]["Visible"] = false;
G2L["49"]["Position"] = UDim2.new(0.1339, 0, 0.32873, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.soundclick
G2L["4a"] = Instance.new("LocalScript", G2L["49"]);
G2L["4a"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.realone
G2L["4b"] = Instance.new("LocalScript", G2L["49"]);
G2L["4b"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.UICorner
G2L["4c"] = Instance.new("UICorner", G2L["49"]);
G2L["4c"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.UIStroke
G2L["4d"] = Instance.new("UIStroke", G2L["49"]);
G2L["4d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["4d"]["Thickness"] = 1.7;
G2L["4d"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.UIPadding
G2L["4e"] = Instance.new("UIPadding", G2L["49"]);
G2L["4e"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2
G2L["4f"] = Instance.new("TextButton", G2L["46"]);
G2L["4f"]["TextWrapped"] = true;
G2L["4f"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["4f"]["BorderSizePixel"] = 0;
G2L["4f"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["4f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["4f"]["TextSize"] = 14;
G2L["4f"]["TextScaled"] = true;
G2L["4f"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4f"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4f"]["Size"] = UDim2.new(0.71832, 0, 0.0941, 0);
G2L["4f"]["Name"] = [[blue2]];
G2L["4f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4f"]["Text"] = [[Esp Red Team]];
G2L["4f"]["Visible"] = false;
G2L["4f"]["Position"] = UDim2.new(0.1339, 0, 0.47685, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.soundclick
G2L["50"] = Instance.new("LocalScript", G2L["4f"]);
G2L["50"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.realone
G2L["51"] = Instance.new("LocalScript", G2L["4f"]);
G2L["51"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.UICorner
G2L["52"] = Instance.new("UICorner", G2L["4f"]);
G2L["52"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.UIStroke
G2L["53"] = Instance.new("UIStroke", G2L["4f"]);
G2L["53"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["53"]["Thickness"] = 1.7;
G2L["53"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.UIPadding
G2L["54"] = Instance.new("UIPadding", G2L["4f"]);
G2L["54"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.UIStroke
G2L["55"] = Instance.new("UIStroke", G2L["46"]);
G2L["55"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["55"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.MainFrame.UICorner
G2L["56"] = Instance.new("UICorner", G2L["46"]);
G2L["56"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1
G2L["57"] = Instance.new("TextButton", G2L["46"]);
G2L["57"]["TextWrapped"] = true;
G2L["57"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["57"]["BorderSizePixel"] = 0;
G2L["57"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["57"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["57"]["TextSize"] = 14;
G2L["57"]["TextScaled"] = true;
G2L["57"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["57"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["57"]["Size"] = UDim2.new(0.71832, 0, 0.08816, 0);
G2L["57"]["Name"] = [[first1]];
G2L["57"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["57"]["Text"] = [[Teleport To the End]];
G2L["57"]["Visible"] = false;
G2L["57"]["Position"] = UDim2.new(0.1339, 0, 0.17856, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.soundclick
G2L["58"] = Instance.new("LocalScript", G2L["57"]);
G2L["58"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.realone
G2L["59"] = Instance.new("LocalScript", G2L["57"]);
G2L["59"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.UICorner
G2L["5a"] = Instance.new("UICorner", G2L["57"]);
G2L["5a"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.UIStroke
G2L["5b"] = Instance.new("UIStroke", G2L["57"]);
G2L["5b"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["5b"]["Thickness"] = 1.7;
G2L["5b"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.UIPadding
G2L["5c"] = Instance.new("UIPadding", G2L["57"]);
G2L["5c"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.fingerprint
G2L["5d"] = Instance.new("ImageLabel", G2L["57"]);
G2L["5d"]["BorderSizePixel"] = 0;
G2L["5d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5d"]["Image"] = [[rbxassetid://8903957093]];
G2L["5d"]["Size"] = UDim2.new(0.10287, 0, 0.9265, 0);
G2L["5d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5d"]["BackgroundTransparency"] = 1;
G2L["5d"]["Name"] = [[fingerprint]];
G2L["5d"]["Position"] = UDim2.new(0.89603, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.Chooser
G2L["5e"] = Instance.new("TextLabel", G2L["46"]);
G2L["5e"]["TextWrapped"] = true;
G2L["5e"]["BorderSizePixel"] = 0;
G2L["5e"]["TextSize"] = 14;
G2L["5e"]["TextScaled"] = true;
G2L["5e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5e"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["BackgroundTransparency"] = 1;
G2L["5e"]["Size"] = UDim2.new(0.84057, 0, 0.10832, 0);
G2L["5e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["Text"] = [[Waiting For The Gamemode...]];
G2L["5e"]["Name"] = [[Chooser]];
G2L["5e"]["Position"] = UDim2.new(0.07297, 0, 0.02528, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.help1
G2L["5f"] = Instance.new("TextBox", G2L["46"]);
G2L["5f"]["Visible"] = false;
G2L["5f"]["Name"] = [[help1]];
G2L["5f"]["PlaceholderColor3"] = Color3.fromRGB(194, 0, 0);
G2L["5f"]["BorderSizePixel"] = 0;
G2L["5f"]["TextWrapped"] = true;
G2L["5f"]["TextSize"] = 14;
G2L["5f"]["TextColor3"] = Color3.fromRGB(212, 0, 0);
G2L["5f"]["TextScaled"] = true;
G2L["5f"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5f"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5f"]["PlaceholderText"] = [[Type Your Target PlayerName]];
G2L["5f"]["Size"] = UDim2.new(0.94976, 0, 0.12682, 0);
G2L["5f"]["Position"] = UDim2.new(0.02962, 0, 0.42868, 0);
G2L["5f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5f"]["Text"] = [[]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.help1.UICorner
G2L["60"] = Instance.new("UICorner", G2L["5f"]);
G2L["60"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.help1.UIStroke
G2L["61"] = Instance.new("UIStroke", G2L["5f"]);
G2L["61"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["61"]["Thickness"] = 3;


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first2
G2L["62"] = Instance.new("TextButton", G2L["46"]);
G2L["62"]["TextWrapped"] = true;
G2L["62"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["62"]["BorderSizePixel"] = 0;
G2L["62"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["62"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["62"]["TextSize"] = 14;
G2L["62"]["TextScaled"] = true;
G2L["62"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["62"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["62"]["Size"] = UDim2.new(0.48635, 0, 0.12024, 0);
G2L["62"]["Name"] = [[first2]];
G2L["62"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["62"]["Text"] = [[Help Player]];
G2L["62"]["Visible"] = false;
G2L["62"]["Position"] = UDim2.new(0.02907, 0, 0.6189, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first2.soundclick
G2L["63"] = Instance.new("LocalScript", G2L["62"]);
G2L["63"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first2.UICorner
G2L["64"] = Instance.new("UICorner", G2L["62"]);
G2L["64"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first2.UIStroke
G2L["65"] = Instance.new("UIStroke", G2L["62"]);
G2L["65"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["65"]["Thickness"] = 1.7;
G2L["65"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first2.UIPadding
G2L["66"] = Instance.new("UIPadding", G2L["62"]);
G2L["66"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first3
G2L["67"] = Instance.new("TextButton", G2L["46"]);
G2L["67"]["TextWrapped"] = true;
G2L["67"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["67"]["BorderSizePixel"] = 0;
G2L["67"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["67"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["67"]["TextSize"] = 14;
G2L["67"]["TextScaled"] = true;
G2L["67"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["67"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["67"]["Size"] = UDim2.new(0.44265, 0, 0.12607, 0);
G2L["67"]["Name"] = [[first3]];
G2L["67"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["67"]["Text"] = [[Kill Player]];
G2L["67"]["Visible"] = false;
G2L["67"]["Position"] = UDim2.new(0.53039, 0, 0.6189, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first3.soundclick
G2L["68"] = Instance.new("LocalScript", G2L["67"]);
G2L["68"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first3.UICorner
G2L["69"] = Instance.new("UICorner", G2L["67"]);
G2L["69"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first3.UIStroke
G2L["6a"] = Instance.new("UIStroke", G2L["67"]);
G2L["6a"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["6a"]["Thickness"] = 1.7;
G2L["6a"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first3.UIPadding
G2L["6b"] = Instance.new("UIPadding", G2L["67"]);
G2L["6b"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.second1
G2L["6c"] = Instance.new("TextLabel", G2L["46"]);
G2L["6c"]["TextWrapped"] = true;
G2L["6c"]["BorderSizePixel"] = 0;
G2L["6c"]["TextSize"] = 14;
G2L["6c"]["TextScaled"] = true;
G2L["6c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6c"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6c"]["TextColor3"] = Color3.fromRGB(241, 0, 0);
G2L["6c"]["BackgroundTransparency"] = 1;
G2L["6c"]["Size"] = UDim2.new(0.84206, 0, 0.14957, 0);
G2L["6c"]["Visible"] = false;
G2L["6c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6c"]["Text"] = [[Sorry Dalgona is not Supported]];
G2L["6c"]["Name"] = [[second1]];
G2L["6c"]["Position"] = UDim2.new(0.07297, 0, 0.32901, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1
G2L["6d"] = Instance.new("TextButton", G2L["46"]);
G2L["6d"]["TextWrapped"] = true;
G2L["6d"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["6d"]["BorderSizePixel"] = 0;
G2L["6d"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["6d"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["6d"]["TextSize"] = 14;
G2L["6d"]["TextScaled"] = true;
G2L["6d"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6d"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6d"]["Size"] = UDim2.new(0.71832, 0, 0.12316, 0);
G2L["6d"]["Name"] = [[third1]];
G2L["6d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6d"]["Text"] = [[Go safe Place]];
G2L["6d"]["Visible"] = false;
G2L["6d"]["Position"] = UDim2.new(0.1339, 0, 0.28645, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.soundclick
G2L["6e"] = Instance.new("LocalScript", G2L["6d"]);
G2L["6e"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.realone
G2L["6f"] = Instance.new("LocalScript", G2L["6d"]);
G2L["6f"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.UICorner
G2L["70"] = Instance.new("UICorner", G2L["6d"]);
G2L["70"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.UIStroke
G2L["71"] = Instance.new("UIStroke", G2L["6d"]);
G2L["71"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["71"]["Thickness"] = 1.7;
G2L["71"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.UIPadding
G2L["72"] = Instance.new("UIPadding", G2L["6d"]);
G2L["72"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1
G2L["73"] = Instance.new("TextButton", G2L["46"]);
G2L["73"]["TextWrapped"] = true;
G2L["73"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["73"]["BorderSizePixel"] = 0;
G2L["73"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["73"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["73"]["TextSize"] = 14;
G2L["73"]["TextScaled"] = true;
G2L["73"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["73"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["73"]["Size"] = UDim2.new(0.71832, 0, 0.12316, 0);
G2L["73"]["Name"] = [[four1]];
G2L["73"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["73"]["Text"] = [[Auto Win]];
G2L["73"]["Visible"] = false;
G2L["73"]["Position"] = UDim2.new(0.1339, 0, 0.2398, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.soundclick
G2L["74"] = Instance.new("LocalScript", G2L["73"]);
G2L["74"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.realone
G2L["75"] = Instance.new("LocalScript", G2L["73"]);
G2L["75"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.UICorner
G2L["76"] = Instance.new("UICorner", G2L["73"]);
G2L["76"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.UIStroke
G2L["77"] = Instance.new("UIStroke", G2L["73"]);
G2L["77"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["77"]["Thickness"] = 1.7;
G2L["77"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.UIPadding
G2L["78"] = Instance.new("UIPadding", G2L["73"]);
G2L["78"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.fingerprint
G2L["79"] = Instance.new("ImageLabel", G2L["73"]);
G2L["79"]["BorderSizePixel"] = 0;
G2L["79"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["79"]["Image"] = [[rbxassetid://8903957093]];
G2L["79"]["Size"] = UDim2.new(0.10287, 0, 0.9265, 0);
G2L["79"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["79"]["BackgroundTransparency"] = 1;
G2L["79"]["Name"] = [[fingerprint]];
G2L["79"]["Position"] = UDim2.new(0.89603, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third2
G2L["7a"] = Instance.new("TextLabel", G2L["46"]);
G2L["7a"]["TextWrapped"] = true;
G2L["7a"]["BorderSizePixel"] = 0;
G2L["7a"]["TextSize"] = 14;
G2L["7a"]["TextScaled"] = true;
G2L["7a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7a"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7a"]["TextColor3"] = Color3.fromRGB(53, 241, 0);
G2L["7a"]["BackgroundTransparency"] = 1;
G2L["7a"]["Size"] = UDim2.new(0.84206, 0, 0.14957, 0);
G2L["7a"]["Visible"] = false;
G2L["7a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7a"]["Text"] = [[Alive xx]];
G2L["7a"]["Name"] = [[third2]];
G2L["7a"]["Position"] = UDim2.new(0.07864, 0, 0.51564, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.third2.tracker
G2L["7b"] = Instance.new("LocalScript", G2L["7a"]);
G2L["7b"]["Name"] = [[tracker]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2
G2L["7c"] = Instance.new("TextButton", G2L["46"]);
G2L["7c"]["TextWrapped"] = true;
G2L["7c"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["7c"]["BorderSizePixel"] = 0;
G2L["7c"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["7c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["7c"]["TextSize"] = 14;
G2L["7c"]["TextScaled"] = true;
G2L["7c"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7c"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7c"]["Size"] = UDim2.new(0.71832, 0, 0.1079, 0);
G2L["7c"]["Name"] = [[five2]];
G2L["7c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7c"]["Text"] = [[Glass Vision]];
G2L["7c"]["Visible"] = false;
G2L["7c"]["Position"] = UDim2.new(0.1339, 0, 0.43518, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.soundclick
G2L["7d"] = Instance.new("LocalScript", G2L["7c"]);
G2L["7d"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.realone
G2L["7e"] = Instance.new("LocalScript", G2L["7c"]);
G2L["7e"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.UICorner
G2L["7f"] = Instance.new("UICorner", G2L["7c"]);
G2L["7f"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.UIStroke
G2L["80"] = Instance.new("UIStroke", G2L["7c"]);
G2L["80"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["80"]["Thickness"] = 1.7;
G2L["80"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.UIPadding
G2L["81"] = Instance.new("UIPadding", G2L["7c"]);
G2L["81"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.fingerprint
G2L["82"] = Instance.new("ImageLabel", G2L["7c"]);
G2L["82"]["BorderSizePixel"] = 0;
G2L["82"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["82"]["Image"] = [[rbxassetid://12333784627]];
G2L["82"]["Size"] = UDim2.new(0.13479, 0, 0.9265, 0);
G2L["82"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["82"]["BackgroundTransparency"] = 1;
G2L["82"]["Name"] = [[fingerprint]];
G2L["82"]["Position"] = UDim2.new(0.83573, 0, 0.05474, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five3
G2L["83"] = Instance.new("TextLabel", G2L["46"]);
G2L["83"]["TextWrapped"] = true;
G2L["83"]["BorderSizePixel"] = 0;
G2L["83"]["TextSize"] = 14;
G2L["83"]["TextScaled"] = true;
G2L["83"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["83"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["83"]["TextColor3"] = Color3.fromRGB(0, 73, 241);
G2L["83"]["BackgroundTransparency"] = 1;
G2L["83"]["Size"] = UDim2.new(0.81013, 0, 0.14957, 0);
G2L["83"]["Visible"] = false;
G2L["83"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["83"]["Text"] = [[Timer XX]];
G2L["83"]["Name"] = [[five3]];
G2L["83"]["Position"] = UDim2.new(0.09283, 0, 0.59438, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five3.tracker
G2L["84"] = Instance.new("LocalScript", G2L["83"]);
G2L["84"]["Name"] = [[tracker]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1
G2L["85"] = Instance.new("TextButton", G2L["46"]);
G2L["85"]["TextWrapped"] = true;
G2L["85"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["85"]["BorderSizePixel"] = 0;
G2L["85"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["85"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["85"]["TextSize"] = 14;
G2L["85"]["TextScaled"] = true;
G2L["85"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["85"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["85"]["Size"] = UDim2.new(0.71832, 0, 0.1079, 0);
G2L["85"]["Name"] = [[five1]];
G2L["85"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["85"]["Text"] = [[Teleport To the End]];
G2L["85"]["Visible"] = false;
G2L["85"]["Position"] = UDim2.new(0.1339, 0, 0.21355, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.soundclick
G2L["86"] = Instance.new("LocalScript", G2L["85"]);
G2L["86"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.realone
G2L["87"] = Instance.new("LocalScript", G2L["85"]);
G2L["87"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.UICorner
G2L["88"] = Instance.new("UICorner", G2L["85"]);
G2L["88"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.UIStroke
G2L["89"] = Instance.new("UIStroke", G2L["85"]);
G2L["89"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["89"]["Thickness"] = 1.7;
G2L["89"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.UIPadding
G2L["8a"] = Instance.new("UIPadding", G2L["85"]);
G2L["8a"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1
G2L["8b"] = Instance.new("TextButton", G2L["46"]);
G2L["8b"]["TextWrapped"] = true;
G2L["8b"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["8b"]["BorderSizePixel"] = 0;
G2L["8b"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["8b"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["8b"]["TextSize"] = 14;
G2L["8b"]["TextScaled"] = true;
G2L["8b"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8b"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8b"]["Size"] = UDim2.new(0.724, 0, 0.10027, 0);
G2L["8b"]["Name"] = [[six1]];
G2L["8b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8b"]["Text"] = [[Power Hold No Miss 100%]];
G2L["8b"]["Visible"] = false;
G2L["8b"]["Position"] = UDim2.new(0.13802, 0, 0.21311, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.soundclick
G2L["8c"] = Instance.new("LocalScript", G2L["8b"]);
G2L["8c"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.realone
G2L["8d"] = Instance.new("LocalScript", G2L["8b"]);
G2L["8d"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.UICorner
G2L["8e"] = Instance.new("UICorner", G2L["8b"]);
G2L["8e"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.UIStroke
G2L["8f"] = Instance.new("UIStroke", G2L["8b"]);
G2L["8f"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["8f"]["Thickness"] = 1.7;
G2L["8f"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.UIPadding
G2L["90"] = Instance.new("UIPadding", G2L["8b"]);
G2L["90"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1Label
G2L["91"] = Instance.new("TextLabel", G2L["46"]);
G2L["91"]["TextWrapped"] = true;
G2L["91"]["BorderSizePixel"] = 0;
G2L["91"]["TextSize"] = 14;
G2L["91"]["TextScaled"] = true;
G2L["91"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["91"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["91"]["TextColor3"] = Color3.fromRGB(178, 0, 0);
G2L["91"]["BackgroundTransparency"] = 1;
G2L["91"]["Size"] = UDim2.new(0.961, 0, 0.15324, 0);
G2L["91"]["Visible"] = false;
G2L["91"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["91"]["Text"] = [[Only Works if the Target is Injured And not Carried By another player]];
G2L["91"]["Name"] = [[first1Label]];
G2L["91"]["Position"] = UDim2.new(0.01645, 0, 0.81148, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.seven1
G2L["92"] = Instance.new("TextLabel", G2L["46"]);
G2L["92"]["TextWrapped"] = true;
G2L["92"]["BorderSizePixel"] = 0;
G2L["92"]["TextSize"] = 14;
G2L["92"]["TextScaled"] = true;
G2L["92"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["92"]["FontFace"] = Font.new([[rbxasset://fonts/families/FredokaOne.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["92"]["TextColor3"] = Color3.fromRGB(241, 234, 233);
G2L["92"]["BackgroundTransparency"] = 1;
G2L["92"]["Size"] = UDim2.new(0.84206, 0, 0.11522, 0);
G2L["92"]["Visible"] = false;
G2L["92"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["92"]["Text"] = [[Team is xx]];
G2L["92"]["Name"] = [[seven1]];
G2L["92"]["Position"] = UDim2.new(0.07297, 0, 0.17746, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2
G2L["93"] = Instance.new("TextButton", G2L["46"]);
G2L["93"]["TextWrapped"] = true;
G2L["93"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["93"]["BorderSizePixel"] = 0;
G2L["93"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["93"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["93"]["TextSize"] = 14;
G2L["93"]["TextScaled"] = true;
G2L["93"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["93"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["93"]["Size"] = UDim2.new(0.71832, 0, 0.11486, 0);
G2L["93"]["Name"] = [[red2]];
G2L["93"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["93"]["Text"] = [[Esp Blue Team]];
G2L["93"]["Visible"] = false;
G2L["93"]["Position"] = UDim2.new(0.13948, 0, 0.29022, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.soundclick
G2L["94"] = Instance.new("LocalScript", G2L["93"]);
G2L["94"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.realone
G2L["95"] = Instance.new("LocalScript", G2L["93"]);
G2L["95"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.UICorner
G2L["96"] = Instance.new("UICorner", G2L["93"]);
G2L["96"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.UIStroke
G2L["97"] = Instance.new("UIStroke", G2L["93"]);
G2L["97"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["97"]["Thickness"] = 1.7;
G2L["97"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.UIPadding
G2L["98"] = Instance.new("UIPadding", G2L["93"]);
G2L["98"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3
G2L["99"] = Instance.new("TextButton", G2L["46"]);
G2L["99"]["TextWrapped"] = true;
G2L["99"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["99"]["BorderSizePixel"] = 0;
G2L["99"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["99"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["99"]["TextSize"] = 14;
G2L["99"]["TextScaled"] = true;
G2L["99"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["99"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["99"]["Size"] = UDim2.new(0.71832, 0, 0.11486, 0);
G2L["99"]["Name"] = [[red3]];
G2L["99"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["99"]["Text"] = [[Bigger Hitbox Close PPL]];
G2L["99"]["Visible"] = false;
G2L["99"]["Position"] = UDim2.new(0.13948, 0, 0.43973, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.soundclick
G2L["9a"] = Instance.new("LocalScript", G2L["99"]);
G2L["9a"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.realone
G2L["9b"] = Instance.new("LocalScript", G2L["99"]);
G2L["9b"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.UICorner
G2L["9c"] = Instance.new("UICorner", G2L["99"]);
G2L["9c"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.UIStroke
G2L["9d"] = Instance.new("UIStroke", G2L["99"]);
G2L["9d"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["9d"]["Thickness"] = 1.7;
G2L["9d"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.UIPadding
G2L["9e"] = Instance.new("UIPadding", G2L["99"]);
G2L["9e"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red4
G2L["9f"] = Instance.new("TextButton", G2L["46"]);
G2L["9f"]["TextWrapped"] = true;
G2L["9f"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["9f"]["BorderSizePixel"] = 0;
G2L["9f"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["9f"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["9f"]["TextSize"] = 14;
G2L["9f"]["TextScaled"] = true;
G2L["9f"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9f"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9f"]["Size"] = UDim2.new(0.71832, 0, 0.11486, 0);
G2L["9f"]["Name"] = [[red4]];
G2L["9f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9f"]["Text"] = [[inf stamina]];
G2L["9f"]["Visible"] = false;
G2L["9f"]["Position"] = UDim2.new(0.13948, 0, 0.57857, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red4.soundclick
G2L["a0"] = Instance.new("LocalScript", G2L["9f"]);
G2L["a0"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red4.realone
G2L["a1"] = Instance.new("LocalScript", G2L["9f"]);
G2L["a1"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red4.UICorner
G2L["a2"] = Instance.new("UICorner", G2L["9f"]);
G2L["a2"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red4.UIStroke
G2L["a3"] = Instance.new("UIStroke", G2L["9f"]);
G2L["a3"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["a3"]["Thickness"] = 1.7;
G2L["a3"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.red4.UIPadding
G2L["a4"] = Instance.new("UIPadding", G2L["9f"]);
G2L["a4"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3
G2L["a5"] = Instance.new("TextButton", G2L["46"]);
G2L["a5"]["TextWrapped"] = true;
G2L["a5"]["TextTruncate"] = Enum.TextTruncate.AtEnd;
G2L["a5"]["BorderSizePixel"] = 0;
G2L["a5"]["TextColor3"] = Color3.fromRGB(240, 240, 240);
G2L["a5"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["a5"]["TextSize"] = 14;
G2L["a5"]["TextScaled"] = true;
G2L["a5"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a5"]["FontFace"] = Font.new([[rbxasset://fonts/families/ComicNeueAngular.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a5"]["Size"] = UDim2.new(0.71832, 0, 0.0941, 0);
G2L["a5"]["Name"] = [[blue3]];
G2L["a5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a5"]["Text"] = [[inf stamina]];
G2L["a5"]["Visible"] = false;
G2L["a5"]["Position"] = UDim2.new(0.13957, 0, 0.59642, 0);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.soundclick
G2L["a6"] = Instance.new("LocalScript", G2L["a5"]);
G2L["a6"]["Name"] = [[soundclick]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.realone
G2L["a7"] = Instance.new("LocalScript", G2L["a5"]);
G2L["a7"]["Name"] = [[realone]];


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.UICorner
G2L["a8"] = Instance.new("UICorner", G2L["a5"]);
G2L["a8"]["CornerRadius"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.UIStroke
G2L["a9"] = Instance.new("UIStroke", G2L["a5"]);
G2L["a9"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["a9"]["Thickness"] = 1.7;
G2L["a9"]["Color"] = Color3.fromRGB(155, 155, 155);


-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.UIPadding
G2L["aa"] = Instance.new("UIPadding", G2L["a5"]);
G2L["aa"]["PaddingLeft"] = UDim.new(0, 10);


-- StarterGui.omarInkGame.Controls
local function C_2()
local script = G2L["2"];
	local TweenService = game:GetService("TweenService")
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	local gui = game:GetService("CoreGui"):WaitForChild("omarInkGame")
	
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
-- StarterGui.omarInkGame.Changer
local function C_3()
local script = G2L["3"];
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
task.spawn(C_3);
-- StarterGui.omarInkGame.Info.drag localscript
local function C_5()
local script = G2L["5"];
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
task.spawn(C_5);
-- StarterGui.omarInkGame.Info.sigma.EspFrame.Main
local function C_e()
local script = G2L["e"];
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
task.spawn(C_e);
-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.LocalScript
local function C_15()
local script = G2L["15"];
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
task.spawn(C_15);
-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.soundclick
local function C_16()
local script = G2L["16"];
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
task.spawn(C_16);
-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.LocalScript
local function C_1a()
local script = G2L["1a"];
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
task.spawn(C_1a);
-- StarterGui.omarInkGame.Info.sigma.EspFrame.Copy.soundclick
local function C_1b()
local script = G2L["1b"];
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
task.spawn(C_1b);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.soundclick
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
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.third.LocalScript
local function C_33()
local script = G2L["33"];
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
task.spawn(C_33);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.soundclick
local function C_39()
local script = G2L["39"];
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
task.spawn(C_39);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.four.LocalScript
local function C_3a()
local script = G2L["3a"];
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
task.spawn(C_3a);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.five.soundclick
local function C_40()
local script = G2L["40"];
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
task.spawn(C_40);
-- StarterGui.omarInkGame.Info.sigma.MiscFrame.five.LocalScript
local function C_41()
local script = G2L["41"];
	-- Put this LocalScript inside your TextButton
	local button       = script.Parent
	local stroke       = button:FindFirstChildOfClass("UIStroke")
	local fingerprint  = button:FindFirstChild("fingerprint")
	local player       = game:GetService("Players").LocalPlayer
	local boostsFolder = player:WaitForChild("Boosts")
	local boostValue   = boostsFolder:WaitForChild("Faster Sprint")
	
	-- state & backups
	local active               = false
	local originalStrokeColor  = stroke      and stroke.Color
	local originalImageColor   = fingerprint and fingerprint.ImageColor3
	local originalWalkSpeed
	
	-- toggle function
	local function onToggle()
		active = not active
	
		if active then
			-- turn UI green
			if stroke      then stroke.Color      = Color3.fromRGB(0,255,0) end
			if fingerprint then fingerprint.ImageColor3 = Color3.fromRGB(0,255,0) end
	
			-- get humanoid & backup WalkSpeed
			local char     = player.Character or player.CharacterAdded:Wait()
			local humanoid = char:WaitForChild("Humanoid")
			originalWalkSpeed = humanoid.WalkSpeed
	
			-- set boost to 5
			boostValue.Value = 5
	
		else
			-- restore UI
			if stroke      and originalStrokeColor then stroke.Color      = originalStrokeColor end
			if fingerprint and originalImageColor  then fingerprint.ImageColor3 = originalImageColor end
	
			-- reset boost & WalkSpeed
			boostValue.Value = 0
			if player.Character and originalWalkSpeed then
				local h = player.Character:FindFirstChild("Humanoid")
				if h then h.WalkSpeed = originalWalkSpeed end
			end
		end
	end
	
	button.MouseButton1Click:Connect(onToggle)
	
end;
task.spawn(C_41);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.Green Red Light
local function C_47()
local script = G2L["47"];
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
	
	-- fireproximityprompt: fires a specific prompt once and SETS its HoldDuration to 0 (persistently)
	local function fireproximityprompt(Obj)
		if not Obj or Obj.ClassName ~= "ProximityPrompt" then
			warn("[HelpAction] Expected ProximityPrompt, got", Obj)
			return false
		end
		-- permanently set HoldDuration to 0 so it always triggers instantly
		Obj.HoldDuration = 0
		-- trigger the prompt once
		Obj:InputHoldBegin()
		Obj:InputHoldEnd()
		print("[HelpAction] ProximityPrompt fired and HoldDuration set to 0 for ", Obj.Parent.Name)
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
	
		-- teleport to target and wait briefly so physics/replication settles
		myHrp.CFrame = CFrame.new(model.HumanoidRootPart.Position + Vector3.new(0,1,0))
		wait(0.25)
	
		-- fire this prompt once and set its HoldDuration to 0
		local fired = fireproximityprompt(prompt)
		if not fired then
			notify("Failed to fire prompt.")
			if stroke then stroke.Color = oldCol end
			active = false
			return
		end
		notify("ProximityPrompt fired! (HoldDuration now 0)")
	
		-- wait so action registers before moving
		wait(0.45)
	
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
	
	-- bind to first2 (help flow) - updated help position
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
			helpBox:ReleaseFocus()
		end
	end)
end;
task.spawn(C_47);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.GameMode Chooser
local function C_48()
local script = G2L["48"];
	-- LocalScript inside MainFrame
	
	local RunService = game:GetService("RunService")
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	local gui = script.Parent -- MainFrame
	
	-- Helper to safely get UI objects (may be nil)
	local function G(name)
		return gui:FindFirstChild(name)
	end
	
	-- UI references (may be missing in some setups; we handle nil)
	local chooserLabel = G("Chooser")
	local firstBtn1 = G("first1")
	local firstBtn2 = G("first2")
	local firstBtn3 = G("first3")
	local help1 = G("help1")
	local second1 = G("second1")
	local third1 = G("third1")
	local third2 = G("third2")
	local four1 = G("four1")
	local five1 = G("five1")
	local five2 = G("five2")
	local five3 = G("five3")
	local six1 = G("six1")
	local seven1 = G("seven1")
	local red2 = G("red2")
	local red3 = G("red3")
	local red4 = G("red4")
	local blue1 = G("blue1")
	local blue2 = G("blue2")
	local blue3 = G("blue3")
	-- TextLabel specifically requested earlier (support either separate label or first1 being a TextLabel)
	local firstTextLabel = G("first1Label") or (firstBtn1 and firstBtn1:IsA("TextLabel") and firstBtn1) or nil
	
	-- value source (try to get it reliably)
	local valuesFolder = workspace:FindFirstChild("Values")
	local gameValueObj = valuesFolder and valuesFolder:FindFirstChild("CurrentGame")
	if not gameValueObj then
		local ok, v = pcall(function() return workspace:WaitForChild("Values", 3) end)
		if ok and v then
			gameValueObj = v:FindFirstChild("CurrentGame") or v:WaitForChild("CurrentGame", 3)
		end
	end
	
	-- valid modes
	local validModes = {
		RedLightGreenLight = true,
		Dalgona = true,
		LightsOut = true,
		TugOfWar = true,
		GlassBridge = true,
		Mingle = true,
		HideAndSeek = true,
	}
	
	-- state
	local isWaiting = false
	local animConn = nil
	local liveListeners = {}
	
	-- helpers
	local function show(obj)
		if obj and obj:IsA("GuiObject") then obj.Visible = true end
	end
	local function hide(obj)
		if obj and obj:IsA("GuiObject") then obj.Visible = false end
	end
	
	local function hideAll()
		-- NOTE: chooserLabel intentionally NOT hidden here so it remains visible
		local list = {
			firstBtn1, firstBtn2, firstBtn3, firstTextLabel, help1,
			second1, third1, third2, four1,
			five1, five2, five3, six1,
			seven1, red2, red3, red4, blue1, blue2, blue3
		}
		for _, o in ipairs(list) do
			if o and o:IsA("GuiObject") then o.Visible = false end
		end
	end
	
	-- waiting animation (cycles ".", "..", "...")
	local function startWaiting()
		if isWaiting then return end
		isWaiting = true
		if chooserLabel and chooserLabel:IsA("GuiObject") then
			chooserLabel.Visible = true
			chooserLabel.Text = "Waiting for gamemode"
		end
		animConn = RunService.Heartbeat:Connect(function()
			if not isWaiting then
				if animConn then animConn:Disconnect() animConn = nil end
				return
			end
			if not chooserLabel then return end
			local dots = (math.floor(tick() * 2) % 3) + 1
			chooserLabel.Text = "Waiting for gamemode" .. string.rep(".", dots)
		end)
	end
	
	local function stopWaiting()
		if not isWaiting then return end
		isWaiting = false
		if animConn then animConn:Disconnect() animConn = nil end
	end
	
	-- Vest detection & listeners for HideAndSeek
	local function clearLiveListeners()
		for _, c in ipairs(liveListeners) do
			pcall(function() c:Disconnect() end)
		end
		liveListeners = {}
	end
	
	local function detectVestForPlayer()
		-- hide vest UI first
		hide(seven1)
		hide(red2); hide(red3); hide(red4)
		hide(blue1); hide(blue2); hide(blue3)
	
		local liveFolder = workspace:FindFirstChild("Live")
		if not liveFolder then return end
		local model = liveFolder:FindFirstChild(player.Name)
		if not model then return end
	
		if model:FindFirstChild("RedVest") then
			if seven1 then
				seven1.Text = "Team is Red"
				seven1.TextColor3 = Color3.fromRGB(255,0,0)
				show(seven1)
			end
			show(red2); show(red3); show(red4)
		elseif model:FindFirstChild("BlueVest") then
			if seven1 then
				seven1.Text = "Team is Blue"
				seven1.TextColor3 = Color3.fromRGB(0,0,255)
				show(seven1)
			end
			show(blue1); show(blue2); show(blue3)
		end
	end
	
	local function startLiveWatch()
		clearLiveListeners()
		local liveFolder = workspace:FindFirstChild("Live")
		if not liveFolder then return end
	
		table.insert(liveListeners, liveFolder.ChildAdded:Connect(function(child)
			if child.Name == player.Name then
				detectVestForPlayer()
				local model = child
				table.insert(liveListeners, model.ChildAdded:Connect(function() detectVestForPlayer() end))
				table.insert(liveListeners, model.ChildRemoved:Connect(function() detectVestForPlayer() end))
			end
		end))
	
		table.insert(liveListeners, liveFolder.ChildRemoved:Connect(function(child)
			if child.Name == player.Name then
				detectVestForPlayer()
			end
		end))
	
		local existingModel = liveFolder:FindFirstChild(player.Name)
		if existingModel then
			table.insert(liveListeners, existingModel.ChildAdded:Connect(function() detectVestForPlayer() end))
			table.insert(liveListeners, existingModel.ChildRemoved:Connect(function() detectVestForPlayer() end))
		end
	end
	
	-- main update
	local function updateUI()
		local v = (gameValueObj and gameValueObj.Value) or ""
	
		stopWaiting()
		hideAll()
	
		-- always ensure chooser remains visible
		if chooserLabel and chooserLabel:IsA("GuiObject") then chooserLabel.Visible = true end
	
		if not validModes[v] then
			startWaiting()
			clearLiveListeners()
			return
		end
	
		stopWaiting()
		if chooserLabel and chooserLabel:IsA("GuiObject") then chooserLabel.Text = v end
	
		if v == "RedLightGreenLight" then
			show(firstBtn1); show(firstBtn2); show(firstBtn3); show(help1); show(firstTextLabel)
			clearLiveListeners()
		elseif v == "Dalgona" then
			show(second1); clearLiveListeners()
		elseif v == "LightsOut" then
			show(third1); show(third2); clearLiveListeners()
		elseif v == "TugOfWar" then
			show(four1); clearLiveListeners()
		elseif v == "GlassBridge" then
			show(five1); show(five2); show(five3); clearLiveListeners()
		elseif v == "Mingle" then
			show(six1); clearLiveListeners()
		elseif v == "HideAndSeek" then
			detectVestForPlayer(); startLiveWatch()
		else
			clearLiveListeners()
		end
	end
	
	-- connect and init
	if gameValueObj then
		gameValueObj:GetPropertyChangedSignal("Value"):Connect(updateUI)
	else
		workspace.ChildAdded:Connect(function(c)
			if c.Name == "Values" and not gameValueObj then
				local ok, val = pcall(function() return c:WaitForChild("CurrentGame", 5) end)
				if ok and val then
					gameValueObj = val
					gameValueObj:GetPropertyChangedSignal("Value"):Connect(updateUI)
					updateUI()
				end
			end
		end)
	end
	
	updateUI()
	
end;
task.spawn(C_48);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.soundclick
local function C_4a()
local script = G2L["4a"];
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
task.spawn(C_4a);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue1.realone
local function C_4b()
local script = G2L["4b"];
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
task.spawn(C_4b);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.soundclick
local function C_50()
local script = G2L["50"];
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
task.spawn(C_50);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue2.realone
local function C_51()
local script = G2L["51"];
	-- LocalScript inside your TextButton
	local button        = script.Parent
	local uiStroke      = button:WaitForChild("UIStroke")
	local originalColor = uiStroke.Color
	local espOn         = false
	
	local liveFolder    = workspace:WaitForChild("Live")
	local espColor      = Color3.fromRGB(255, 0, 0) -- red ESP
	
	-- Function to add/remove ESP highlights
	local function setESP(on)
		for _, model in pairs(liveFolder:GetChildren()) do
			if model:IsA("Model") then
				local vest = model:FindFirstChild("RedVest")
				local existing = model:FindFirstChild("ESPHighlight")
				if on and vest then
					if not existing then
						local hl = Instance.new("Highlight")
						hl.Name        = "ESPHighlight"
						hl.Adornee     = model
						hl.Parent      = model
						hl.FillColor   = espColor
						hl.OutlineColor= espColor
					else
						existing.FillColor = espColor
						existing.OutlineColor = espColor
					end
				elseif existing then
					existing:Destroy()
				end
			end
		end
	end
	
	-- When a new model is added
	liveFolder.ChildAdded:Connect(function(child)
		if child:IsA("Model") then
			local vest = child:FindFirstChild("RedVest")
			if espOn and vest then
				if not child:FindFirstChild("ESPHighlight") then
					local hl = Instance.new("Highlight")
					hl.Name        = "ESPHighlight"
					hl.Adornee     = child
					hl.Parent      = child
					hl.FillColor   = espColor
					hl.OutlineColor= espColor
				end
			end
	
			-- Track vest removal in this model
			child.DescendantRemoving:Connect(function(desc)
				if desc.Name == "RedVest" and desc.Parent == child then
					local existing = child:FindFirstChild("ESPHighlight")
					if existing then existing:Destroy() end
				end
			end)
		end
	end)
	
	-- Also handle when vest is added to existing models
	liveFolder.DescendantAdded:Connect(function(desc)
		if desc.Name == "RedVest" and desc.Parent:IsA("Model") then
			if espOn then
				local model = desc.Parent
				if not model:FindFirstChild("ESPHighlight") then
					local hl = Instance.new("Highlight")
					hl.Name        = "ESPHighlight"
					hl.Adornee     = model
					hl.Parent      = model
					hl.FillColor   = espColor
					hl.OutlineColor= espColor
				end
			end
		end
	end)
	
	-- Toggle button click
	button.MouseButton1Click:Connect(function()
		espOn = not espOn
		if espOn then
			uiStroke.Color = Color3.fromRGB(0, 255, 0) -- green button when on
			setESP(true)
		else
			uiStroke.Color = originalColor
			setESP(false)
		end
	end)
	
	-- Keep ESP persistent even if button is hidden
	button:GetPropertyChangedSignal("Visible"):Connect(function()
		if not button.Visible and espOn then
			uiStroke.Color = Color3.fromRGB(0, 255, 0)
			setESP(true)
		end
	end)
	
end;
task.spawn(C_51);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.soundclick
local function C_58()
local script = G2L["58"];
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
task.spawn(C_58);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.first1.realone
local function C_59()
local script = G2L["59"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		local player = game.Players.LocalPlayer
		local character = player.Character or player.CharacterAdded:Wait()
		local humanoidRootPart = character:WaitForChild("HumanoidRootPart")
	
		humanoidRootPart.CFrame = CFrame.new(-46, 1025, 138)
	end)
	
end;
task.spawn(C_59);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.first2.soundclick
local function C_63()
local script = G2L["63"];
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
task.spawn(C_63);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.first3.soundclick
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
-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.soundclick
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
-- StarterGui.omarInkGame.Info.sigma.MainFrame.third1.realone
local function C_6f()
local script = G2L["6f"];
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
				character:MoveTo(Vector3.new(193, 145, -119))
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
task.spawn(C_6f);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.soundclick
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
-- StarterGui.omarInkGame.Info.sigma.MainFrame.four1.realone
local function C_75()
local script = G2L["75"];
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
task.spawn(C_75);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.third2.tracker
local function C_7b()
local script = G2L["7b"];
	local textLabel = script.Parent
	local currentAlive = workspace:WaitForChild("Values"):WaitForChild("CurrentAlive")
	
	-- Keep updating every 0.1 seconds
	while true do
		textLabel.Text = "Alive: " .. currentAlive.Value
		task.wait(0.1)
	end
	
end;
task.spawn(C_7b);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.soundclick
local function C_7d()
local script = G2L["7d"];
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
task.spawn(C_7d);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.five2.realone
local function C_7e()
local script = G2L["7e"];
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
task.spawn(C_7e);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.five3.tracker
local function C_84()
local script = G2L["84"];
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
task.spawn(C_84);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.soundclick
local function C_86()
local script = G2L["86"];
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
task.spawn(C_86);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.five1.realone
local function C_87()
local script = G2L["87"];
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		local player = game.Players.LocalPlayer
		local character = player.Character or player.CharacterAdded:Wait()
		local humanoidRootPart = character:WaitForChild("HumanoidRootPart")
	
		humanoidRootPart.CFrame = CFrame.new(-195, 521, -1535)
	end)
	
end;
task.spawn(C_87);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.soundclick
local function C_8c()
local script = G2L["8c"];
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
task.spawn(C_8c);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.six1.realone
local function C_8d()
local script = G2L["8d"];
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
task.spawn(C_8d);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.soundclick
local function C_94()
local script = G2L["94"];
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
task.spawn(C_94);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.red2.realone
local function C_95()
local script = G2L["95"];
	-- LocalScript inside your TextButton
	local button        = script.Parent
	local uiStroke      = button:WaitForChild("UIStroke")
	local originalColor = uiStroke.Color
	local espOn         = false
	
	local liveFolder    = workspace:WaitForChild("Live")
	local espColor      = Color3.fromRGB(0, 0, 255) -- blue ESP
	
	-- Function to add/remove ESP highlights
	local function setESP(on)
		for _, model in pairs(liveFolder:GetChildren()) do
			if model:IsA("Model") then
				local vest = model:FindFirstChild("BlueVest")
				local existing = model:FindFirstChild("ESPHighlight")
				if on and vest then
					if not existing then
						local hl = Instance.new("Highlight")
						hl.Name        = "ESPHighlight"
						hl.Adornee     = model
						hl.Parent      = model
						hl.FillColor   = espColor
						hl.OutlineColor= espColor
					else
						existing.FillColor = espColor
						existing.OutlineColor = espColor
					end
				elseif existing then
					existing:Destroy()
				end
			end
		end
	end
	
	-- When a new model is added
	liveFolder.ChildAdded:Connect(function(child)
		if child:IsA("Model") then
			local vest = child:FindFirstChild("BlueVest")
			if espOn and vest then
				if not child:FindFirstChild("ESPHighlight") then
					local hl = Instance.new("Highlight")
					hl.Name        = "ESPHighlight"
					hl.Adornee     = child
					hl.Parent      = child
					hl.FillColor   = espColor
					hl.OutlineColor= espColor
				end
			end
	
			-- Track vest removal in this model
			child.DescendantRemoving:Connect(function(desc)
				if desc.Name == "BlueVest" and desc.Parent == child then
					local existing = child:FindFirstChild("ESPHighlight")
					if existing then existing:Destroy() end
				end
			end)
		end
	end)
	
	-- Also handle when vest is added to existing models
	liveFolder.DescendantAdded:Connect(function(desc)
		if desc.Name == "BlueVest" and desc.Parent:IsA("Model") then
			if espOn then
				local model = desc.Parent
				if not model:FindFirstChild("ESPHighlight") then
					local hl = Instance.new("Highlight")
					hl.Name        = "ESPHighlight"
					hl.Adornee     = model
					hl.Parent      = model
					hl.FillColor   = espColor
					hl.OutlineColor= espColor
				end
			end
		end
	end)
	
	-- Toggle button click
	button.MouseButton1Click:Connect(function()
		espOn = not espOn
		if espOn then
			uiStroke.Color = Color3.fromRGB(0, 255, 0) -- green button when on
			setESP(true)
		else
			uiStroke.Color = originalColor
			setESP(false)
		end
	end)
	
	-- Keep ESP persistent even if button is hidden
	button:GetPropertyChangedSignal("Visible"):Connect(function()
		if not button.Visible and espOn then
			uiStroke.Color = Color3.fromRGB(0, 255, 0)
			setESP(true)
		end
	end)
	
end;
task.spawn(C_95);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.soundclick
local function C_9a()
local script = G2L["9a"];
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
task.spawn(C_9a);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.red3.realone
local function C_9b()
local script = G2L["9b"];
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
task.spawn(C_9b);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.red4.soundclick
local function C_a0()
local script = G2L["a0"];
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
task.spawn(C_a0);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.red4.realone
local function C_a1()
local script = G2L["a1"];
	local button   = script.Parent
	local uiStroke = button:FindFirstChildOfClass("UIStroke")
	if not uiStroke then
		warn("No UIStroke found on button!")
		return
	end
	
	local originalColor = uiStroke.Color
	local isOn = false
	local loopConnection
	
	-- Finds the first Model under workspace.Live that has a NumberValue named “StaminaVal”
	local function getTargetModel()
		local liveFolder = workspace:FindFirstChild("Live")
		if not liveFolder then return nil end
		for _, child in ipairs(liveFolder:GetChildren()) do
			if child:IsA("Model") and child:FindFirstChild("StaminaVal") then
				return child
			end
		end
		return nil
	end
	
	-- Starts the heartbeat loop to reset StaminaVal to 100 every 0.1s
	local function startStaminaLoop()
		loopConnection = game:GetService("RunService").Heartbeat:Connect(function()
			if not isOn or not button.Visible then
				-- turn off if state flipped or button hidden
				isOn = false
				uiStroke.Color = originalColor
				loopConnection:Disconnect()
				loopConnection = nil
				return
			end
	
			local model = getTargetModel()
			if model then
				local sv = model:FindFirstChild("StaminaVal")
				if sv and typeof(sv.Value) == "number" then
					sv.Value = 100
				end
			end
	
			task.wait(0.1)
		end)
	end
	
	-- Toggle on click
	button.MouseButton1Click:Connect(function()
		isOn = not isOn
	
		if isOn then
			uiStroke.Color = Color3.fromRGB(0, 255, 0)
			startStaminaLoop()
		else
			uiStroke.Color = originalColor
			if loopConnection then
				loopConnection:Disconnect()
				loopConnection = nil
			end
		end
	end)
	
end;
task.spawn(C_a1);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.soundclick
local function C_a6()
local script = G2L["a6"];
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
task.spawn(C_a6);
-- StarterGui.omarInkGame.Info.sigma.MainFrame.blue3.realone
local function C_a7()
local script = G2L["a7"];
	local button   = script.Parent
	local uiStroke = button:FindFirstChildOfClass("UIStroke")
	if not uiStroke then
		warn("No UIStroke found on button!")
		return
	end
	
	local originalColor = uiStroke.Color
	local isOn = false
	local loopConnection
	
	-- Finds the first Model under workspace.Live that has a NumberValue named “StaminaVal”
	local function getTargetModel()
		local liveFolder = workspace:FindFirstChild("Live")
		if not liveFolder then return nil end
		for _, child in ipairs(liveFolder:GetChildren()) do
			if child:IsA("Model") and child:FindFirstChild("StaminaVal") then
				return child
			end
		end
		return nil
	end
	
	-- Starts the heartbeat loop to reset StaminaVal to 100 every 0.1s
	local function startStaminaLoop()
		loopConnection = game:GetService("RunService").Heartbeat:Connect(function()
			if not isOn or not button.Visible then
				-- turn off if state flipped or button hidden
				isOn = false
				uiStroke.Color = originalColor
				loopConnection:Disconnect()
				loopConnection = nil
				return
			end
	
			local model = getTargetModel()
			if model then
				local sv = model:FindFirstChild("StaminaVal")
				if sv and typeof(sv.Value) == "number" then
					sv.Value = 100
				end
			end
	
			task.wait(0.1)
		end)
	end
	
	-- Toggle on click
	button.MouseButton1Click:Connect(function()
		isOn = not isOn
	
		if isOn then
			uiStroke.Color = Color3.fromRGB(0, 255, 0)
			startStaminaLoop()
		else
			uiStroke.Color = originalColor
			if loopConnection then
				loopConnection:Disconnect()
				loopConnection = nil
			end
		end
	end)
	
end;
task.spawn(C_a7);

return G2L["1"], require;
