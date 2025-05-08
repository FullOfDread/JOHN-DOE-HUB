local G2L = {};

-- StarterGui.DREADED_HUB
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["IgnoreGuiInset"] = true;
G2L["1"]["DisplayOrder"] = 999999999;
G2L["1"]["ScreenInsets"] = Enum.ScreenInsets.DeviceSafeInsets;
G2L["1"]["Name"] = [[DREADED_HUB]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;
G2L["1"]["ResetOnSpawn"] = false;


-- StarterGui.DREADED_HUB.WholeThang
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2"]["ClipsDescendants"] = true;
G2L["2"]["Size"] = UDim2.new(0.35, 0, 0.4, 0);
G2L["2"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[WholeThang]];
G2L["2"]["BackgroundTransparency"] = 0.25;


-- StarterGui.DREADED_HUB.WholeThang.ToggleScript
G2L["3"] = Instance.new("LocalScript", G2L["2"]);
G2L["3"]["Name"] = [[ToggleScript]];


-- StarterGui.DREADED_HUB.WholeThang.UIAspectRatioConstraint
G2L["4"] = Instance.new("UIAspectRatioConstraint", G2L["2"]);
G2L["4"]["AspectRatio"] = 1.66667;


-- StarterGui.DREADED_HUB.WholeThang.UIStroke
G2L["5"] = Instance.new("UIStroke", G2L["2"]);
G2L["5"]["Thickness"] = 5;


-- StarterGui.DREADED_HUB.WholeThang.UICorner
G2L["6"] = Instance.new("UICorner", G2L["2"]);



-- StarterGui.DREADED_HUB.WholeThang.Draggot
G2L["7"] = Instance.new("Frame", G2L["2"]);
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7"]["Size"] = UDim2.new(0.99906, 0, 0.11973, 0);
G2L["7"]["Position"] = UDim2.new(0.50047, 0, 0.05987, 0);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Name"] = [[Draggot]];
G2L["7"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Draggot.DREADED_HUB_TXT
G2L["8"] = Instance.new("TextLabel", G2L["7"]);
G2L["8"]["TextWrapped"] = true;
G2L["8"]["TextStrokeTransparency"] = 0;
G2L["8"]["BorderSizePixel"] = 0;
G2L["8"]["TextSize"] = 60;
G2L["8"]["TextScaled"] = true;
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["8"]["BackgroundTransparency"] = 1;
G2L["8"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["8"]["Size"] = UDim2.new(1.0015, 0, 1.30623, 0);
G2L["8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8"]["Text"] = [[JOHN DOE HUB]];
G2L["8"]["Name"] = [[DREADED_HUB_TXT]];
G2L["8"]["Position"] = UDim2.new(0.50047, 0, 0.47327, 0);


-- StarterGui.DREADED_HUB.WholeThang.Draggot.DREADED_HUB_TXT.UIGradient
G2L["9"] = Instance.new("UIGradient", G2L["8"]);
G2L["9"]["Rotation"] = 90;
G2L["9"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Draggot.DREADED_HUB_TXT.UIStroke
G2L["a"] = Instance.new("UIStroke", G2L["8"]);
G2L["a"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Draggot.JP_L
G2L["b"] = Instance.new("ImageLabel", G2L["7"]);
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["b"]["Image"] = [[rbxassetid://105494565898698]];
G2L["b"]["ImageRectSize"] = Vector2.new(-1024, 1024);
G2L["b"]["Size"] = UDim2.new(0.28686, 0, 1.11334, 0);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["BackgroundTransparency"] = 1;
G2L["b"]["ImageRectOffset"] = Vector2.new(1024, 0);
G2L["b"]["Name"] = [[JP_L]];
G2L["b"]["Position"] = UDim2.new(0.14249, 0, 0.55667, 0);


-- StarterGui.DREADED_HUB.WholeThang.Draggot.JP_R
G2L["c"] = Instance.new("ImageLabel", G2L["7"]);
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["c"]["Image"] = [[rbxassetid://105494565898698]];
G2L["c"]["Size"] = UDim2.new(0.28663, 0, 1.11334, 0);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["BackgroundTransparency"] = 1;
G2L["c"]["Name"] = [[JP_R]];
G2L["c"]["Position"] = UDim2.new(0.85669, 0, 0.55667, 0);


-- StarterGui.DREADED_HUB.WholeThang.Draggot.UIDrag
G2L["d"] = Instance.new("LocalScript", G2L["7"]);
G2L["d"]["Name"] = [[UIDrag]];


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone
G2L["e"] = Instance.new("ScrollingFrame", G2L["2"]);
G2L["e"]["Active"] = true;
G2L["e"]["BorderSizePixel"] = 0;
G2L["e"]["CanvasSize"] = UDim2.new(0, 0, 1.25, 0);
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["Name"] = [[ScrollBone]];
G2L["e"]["VerticalScrollBarPosition"] = Enum.VerticalScrollBarPosition.Left;
G2L["e"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["e"]["Size"] = UDim2.new(0.29161, 0, 0.84618, 0);
G2L["e"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["Position"] = UDim2.new(0.1458, 0, 0.57691, 0);
G2L["e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["ScrollBarThickness"] = 10;
G2L["e"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.ButtonHandler
G2L["f"] = Instance.new("LocalScript", G2L["e"]);
G2L["f"]["Name"] = [[ButtonHandler]];


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.UIListLayout
G2L["10"] = Instance.new("UIListLayout", G2L["e"]);
G2L["10"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["10"]["Padding"] = UDim.new(0.025, 0);
G2L["10"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Dashboard
G2L["11"] = Instance.new("TextButton", G2L["e"]);
G2L["11"]["TextWrapped"] = true;
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["11"]["TextSize"] = 14;
G2L["11"]["TextScaled"] = true;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["11"]["Size"] = UDim2.new(0.85, 0, 0.14, 0);
G2L["11"]["Name"] = [[Dashboard]];
G2L["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["11"]["Text"] = [[Dashboard]];
G2L["11"]["Position"] = UDim2.new(0, 1, 0, 1);


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Dashboard.UICorner
G2L["12"] = Instance.new("UICorner", G2L["11"]);



-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Dashboard.UIGradient
G2L["13"] = Instance.new("UIGradient", G2L["11"]);
G2L["13"]["Rotation"] = 90;
G2L["13"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Dashboard.UIStroke
G2L["14"] = Instance.new("UIStroke", G2L["11"]);
G2L["14"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Player
G2L["15"] = Instance.new("TextButton", G2L["e"]);
G2L["15"]["TextWrapped"] = true;
G2L["15"]["BorderSizePixel"] = 0;
G2L["15"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["15"]["TextSize"] = 14;
G2L["15"]["TextScaled"] = true;
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(26, 26, 26);
G2L["15"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["15"]["Size"] = UDim2.new(0.85, 0, 0.14, 0);
G2L["15"]["Name"] = [[Player]];
G2L["15"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["15"]["Text"] = [[Player]];
G2L["15"]["Position"] = UDim2.new(0, 1, 0, 1);


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Player.UICorner
G2L["16"] = Instance.new("UICorner", G2L["15"]);



-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Player.UIGradient
G2L["17"] = Instance.new("UIGradient", G2L["15"]);
G2L["17"]["Rotation"] = 90;
G2L["17"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Player.UIStroke
G2L["18"] = Instance.new("UIStroke", G2L["15"]);
G2L["18"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Players
G2L["19"] = Instance.new("TextButton", G2L["e"]);
G2L["19"]["TextWrapped"] = true;
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["19"]["TextSize"] = 14;
G2L["19"]["TextScaled"] = true;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(26, 26, 26);
G2L["19"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["19"]["Size"] = UDim2.new(0.85, 0, 0.14, 0);
G2L["19"]["Name"] = [[Players]];
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[Players]];
G2L["19"]["Position"] = UDim2.new(0, 1, 0, 1);


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Players.UICorner
G2L["1a"] = Instance.new("UICorner", G2L["19"]);



-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Players.UIGradient
G2L["1b"] = Instance.new("UIGradient", G2L["19"]);
G2L["1b"]["Rotation"] = 90;
G2L["1b"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Players.UIStroke
G2L["1c"] = Instance.new("UIStroke", G2L["19"]);
G2L["1c"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Combat
G2L["1d"] = Instance.new("TextButton", G2L["e"]);
G2L["1d"]["TextWrapped"] = true;
G2L["1d"]["BorderSizePixel"] = 0;
G2L["1d"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["1d"]["TextSize"] = 14;
G2L["1d"]["TextScaled"] = true;
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(26, 26, 26);
G2L["1d"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1d"]["Size"] = UDim2.new(0.85, 0, 0.14, 0);
G2L["1d"]["Name"] = [[Combat]];
G2L["1d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1d"]["Text"] = [[Combat]];
G2L["1d"]["Position"] = UDim2.new(0, 1, 0, 1);


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Combat.UICorner
G2L["1e"] = Instance.new("UICorner", G2L["1d"]);



-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Combat.UIGradient
G2L["1f"] = Instance.new("UIGradient", G2L["1d"]);
G2L["1f"]["Rotation"] = 90;
G2L["1f"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Combat.UIStroke
G2L["20"] = Instance.new("UIStroke", G2L["1d"]);
G2L["20"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Miscellaneous
G2L["21"] = Instance.new("TextButton", G2L["e"]);
G2L["21"]["TextWrapped"] = true;
G2L["21"]["BorderSizePixel"] = 0;
G2L["21"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["21"]["TextSize"] = 14;
G2L["21"]["TextScaled"] = true;
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(26, 26, 26);
G2L["21"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["21"]["Size"] = UDim2.new(0.85, 0, 0.14, 0);
G2L["21"]["Name"] = [[Miscellaneous]];
G2L["21"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["21"]["Text"] = [[Miscellaneous]];
G2L["21"]["Position"] = UDim2.new(0, 1, 0, 1);


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Miscellaneous.UICorner
G2L["22"] = Instance.new("UICorner", G2L["21"]);



-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Miscellaneous.UIGradient
G2L["23"] = Instance.new("UIGradient", G2L["21"]);
G2L["23"]["Rotation"] = 90;
G2L["23"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Miscellaneous.UIStroke
G2L["24"] = Instance.new("UIStroke", G2L["21"]);
G2L["24"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Script Hubs
G2L["25"] = Instance.new("TextButton", G2L["e"]);
G2L["25"]["TextWrapped"] = true;
G2L["25"]["BorderSizePixel"] = 0;
G2L["25"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["25"]["TextSize"] = 14;
G2L["25"]["TextScaled"] = true;
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(26, 26, 26);
G2L["25"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["25"]["Size"] = UDim2.new(0.85, 0, 0.14, 0);
G2L["25"]["Name"] = [[Script Hubs]];
G2L["25"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["25"]["Text"] = [[Script Hubs]];
G2L["25"]["Position"] = UDim2.new(0, 1, 0, 1);


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Script Hubs.UICorner
G2L["26"] = Instance.new("UICorner", G2L["25"]);



-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Script Hubs.UIGradient
G2L["27"] = Instance.new("UIGradient", G2L["25"]);
G2L["27"]["Rotation"] = 90;
G2L["27"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.Script Hubs.UIStroke
G2L["28"] = Instance.new("UIStroke", G2L["25"]);
G2L["28"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat
G2L["29"] = Instance.new("Frame", G2L["2"]);
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["29"]["Size"] = UDim2.new(0.69949, 0, 0.86284, 0);
G2L["29"]["Position"] = UDim2.new(0.64833, 0, 0.56858, 0);
G2L["29"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["29"]["Name"] = [[Meat]];
G2L["29"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.UIStroke
G2L["2a"] = Instance.new("UIStroke", G2L["29"]);
G2L["2a"]["Thickness"] = 5;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame
G2L["2b"] = Instance.new("ScrollingFrame", G2L["29"]);
G2L["2b"]["Active"] = true;
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["CanvasSize"] = UDim2.new(0, 0, 2.5, 0);
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["Size"] = UDim2.new(1.00012, 0, 0.98069, 0);
G2L["2b"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["Position"] = UDim2.new(0.00263, 0, 0.01931, 0);
G2L["2b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2b"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder
G2L["2c"] = Instance.new("Frame", G2L["2b"]);
G2L["2c"]["BorderSizePixel"] = 0;
G2L["2c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2c"]["Size"] = UDim2.new(1.00187, 0, 295.52985, 0);
G2L["2c"]["Position"] = UDim2.new(0, 0, -0.2517, 0);
G2L["2c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2c"]["Name"] = [[Holder]];
G2L["2c"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard
G2L["2d"] = Instance.new("Folder", G2L["2c"]);
G2L["2d"]["Name"] = [[Dashboard]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.ImageLabel
G2L["2e"] = Instance.new("ImageLabel", G2L["2d"]);
G2L["2e"]["BorderSizePixel"] = 0;
G2L["2e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2e"]["ScaleType"] = Enum.ScaleType.Fit;
G2L["2e"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2e"]["Size"] = UDim2.new(0.48035, 0, 0.00083, 0);
G2L["2e"]["Visible"] = false;
G2L["2e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2e"]["BackgroundTransparency"] = 1;
G2L["2e"]["Position"] = UDim2.new(0.5, 0, 0.00097, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.ImageLabel.LocalScript
G2L["2f"] = Instance.new("LocalScript", G2L["2e"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.WelcomeText
G2L["30"] = Instance.new("TextLabel", G2L["2d"]);
G2L["30"]["TextWrapped"] = true;
G2L["30"]["TextStrokeTransparency"] = 0;
G2L["30"]["BorderSizePixel"] = 0;
G2L["30"]["TextSize"] = 60;
G2L["30"]["TextScaled"] = true;
G2L["30"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["30"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["30"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["30"]["BackgroundTransparency"] = 1;
G2L["30"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["30"]["Size"] = UDim2.new(0.90293, 0, 0.00048, 0);
G2L["30"]["Visible"] = false;
G2L["30"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["30"]["Text"] = [[WELCOME]];
G2L["30"]["Name"] = [[WelcomeText]];
G2L["30"]["Position"] = UDim2.new(0.5, 0, 0.00007, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.WelcomeText.UIGradient
G2L["31"] = Instance.new("UIGradient", G2L["30"]);
G2L["31"]["Rotation"] = 90;
G2L["31"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.WelcomeText.UIStroke
G2L["32"] = Instance.new("UIStroke", G2L["30"]);
G2L["32"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.WelcomeText.UITextSizeConstraint
G2L["33"] = Instance.new("UITextSizeConstraint", G2L["30"]);
G2L["33"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.WelcomeText.LocalScript
G2L["34"] = Instance.new("LocalScript", G2L["30"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.ServerRegion
G2L["35"] = Instance.new("TextLabel", G2L["2d"]);
G2L["35"]["TextWrapped"] = true;
G2L["35"]["TextStrokeTransparency"] = 0;
G2L["35"]["BorderSizePixel"] = 0;
G2L["35"]["TextSize"] = 40;
G2L["35"]["TextScaled"] = true;
G2L["35"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["35"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["35"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["35"]["BackgroundTransparency"] = 1;
G2L["35"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["35"]["Size"] = UDim2.new(2.021, 0, 0.00044, 0);
G2L["35"]["Visible"] = false;
G2L["35"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["35"]["Text"] = [[Region: Unknown]];
G2L["35"]["Name"] = [[ServerRegion]];
G2L["35"]["Position"] = UDim2.new(0.5, 0, 0.00022, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.ServerRegion.UIGradient
G2L["36"] = Instance.new("UIGradient", G2L["35"]);
G2L["36"]["Rotation"] = 90;
G2L["36"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.ServerRegion.UIStroke
G2L["37"] = Instance.new("UIStroke", G2L["35"]);
G2L["37"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.ServerRegion.UITextSizeConstraint
G2L["38"] = Instance.new("UITextSizeConstraint", G2L["35"]);
G2L["38"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.ServerRegion.ServerRegionScript
G2L["39"] = Instance.new("LocalScript", G2L["35"]);
G2L["39"]["Name"] = [[ServerRegionScript]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.PlayerCount
G2L["3a"] = Instance.new("TextLabel", G2L["2d"]);
G2L["3a"]["TextWrapped"] = true;
G2L["3a"]["TextStrokeTransparency"] = 0;
G2L["3a"]["BorderSizePixel"] = 0;
G2L["3a"]["TextSize"] = 40;
G2L["3a"]["TextScaled"] = true;
G2L["3a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3a"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3a"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["3a"]["BackgroundTransparency"] = 1;
G2L["3a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["3a"]["Size"] = UDim2.new(2.02106, 0, 0.00081, 0);
G2L["3a"]["Visible"] = false;
G2L["3a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3a"]["Text"] = [[Player Count: 69]];
G2L["3a"]["Name"] = [[PlayerCount]];
G2L["3a"]["Position"] = UDim2.new(0.5, 0, 0.00041, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.PlayerCount.UIGradient
G2L["3b"] = Instance.new("UIGradient", G2L["3a"]);
G2L["3b"]["Rotation"] = 90;
G2L["3b"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.PlayerCount.UIStroke
G2L["3c"] = Instance.new("UIStroke", G2L["3a"]);
G2L["3c"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.PlayerCount.UITextSizeConstraint
G2L["3d"] = Instance.new("UITextSizeConstraint", G2L["3a"]);
G2L["3d"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.PlayerCount.PlayerCountScript
G2L["3e"] = Instance.new("LocalScript", G2L["3a"]);
G2L["3e"]["Name"] = [[PlayerCountScript]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.Time
G2L["3f"] = Instance.new("TextLabel", G2L["2d"]);
G2L["3f"]["TextWrapped"] = true;
G2L["3f"]["TextStrokeTransparency"] = 0;
G2L["3f"]["BorderSizePixel"] = 0;
G2L["3f"]["TextSize"] = 40;
G2L["3f"]["TextScaled"] = true;
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3f"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3f"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["3f"]["BackgroundTransparency"] = 1;
G2L["3f"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["3f"]["Size"] = UDim2.new(2.021, 0, 0.00118, 0);
G2L["3f"]["Visible"] = false;
G2L["3f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3f"]["Text"] = [[Time: 9:20]];
G2L["3f"]["Name"] = [[Time]];
G2L["3f"]["Position"] = UDim2.new(0.5, 0, 0.00059, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.Time.UIGradient
G2L["40"] = Instance.new("UIGradient", G2L["3f"]);
G2L["40"]["Rotation"] = 90;
G2L["40"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.Time.UIStroke
G2L["41"] = Instance.new("UIStroke", G2L["3f"]);
G2L["41"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.Time.UITextSizeConstraint
G2L["42"] = Instance.new("UITextSizeConstraint", G2L["3f"]);
G2L["42"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.Time.TimeScript
G2L["43"] = Instance.new("LocalScript", G2L["3f"]);
G2L["43"]["Name"] = [[TimeScript]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player
G2L["44"] = Instance.new("Folder", G2L["2c"]);
G2L["44"]["Name"] = [[Player]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Infinite Jump
G2L["45"] = Instance.new("TextButton", G2L["44"]);
G2L["45"]["TextWrapped"] = true;
G2L["45"]["BorderSizePixel"] = 0;
G2L["45"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["45"]["TextSize"] = 40;
G2L["45"]["TextScaled"] = true;
G2L["45"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["45"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["45"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["45"]["BackgroundTransparency"] = 1;
G2L["45"]["Name"] = [[Infinite Jump]];
G2L["45"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["45"]["Text"] = [[Infinite Jump]];
G2L["45"]["Visible"] = false;
G2L["45"]["Position"] = UDim2.new(0, 0, 0.00138, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Infinite Jump.UIGradient
G2L["46"] = Instance.new("UIGradient", G2L["45"]);
G2L["46"]["Rotation"] = 90;
G2L["46"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Infinite Jump.UIStroke
G2L["47"] = Instance.new("UIStroke", G2L["45"]);
G2L["47"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Infinite Jump.UITextSizeConstraint
G2L["48"] = Instance.new("UITextSizeConstraint", G2L["45"]);
G2L["48"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Infinite Jump.Online
G2L["49"] = Instance.new("TextBox", G2L["45"]);
G2L["49"]["Visible"] = false;
G2L["49"]["Active"] = false;
G2L["49"]["Name"] = [[Online]];
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["TextEditable"] = false;
G2L["49"]["TextWrapped"] = true;
G2L["49"]["TextSize"] = 14;
G2L["49"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["TextScaled"] = true;
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["49"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["49"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["49"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["49"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["49"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["49"]["Text"] = [[OFF]];
G2L["49"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Infinite Jump.Online.UITextSizeConstraint
G2L["4a"] = Instance.new("UITextSizeConstraint", G2L["49"]);
G2L["4a"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Infinite Jump.Jump_67fd97
G2L["4b"] = Instance.new("LocalScript", G2L["45"]);
G2L["4b"]["Name"] = [[Jump_67fd97]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Click TP
G2L["4c"] = Instance.new("TextButton", G2L["44"]);
G2L["4c"]["TextWrapped"] = true;
G2L["4c"]["BorderSizePixel"] = 0;
G2L["4c"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["4c"]["TextSize"] = 40;
G2L["4c"]["TextScaled"] = true;
G2L["4c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4c"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4c"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["4c"]["BackgroundTransparency"] = 1;
G2L["4c"]["Name"] = [[Click TP]];
G2L["4c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4c"]["Text"] = [[Click TP]];
G2L["4c"]["Visible"] = false;
G2L["4c"]["Position"] = UDim2.new(0, 0, 0.00167, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Click TP.UIGradient
G2L["4d"] = Instance.new("UIGradient", G2L["4c"]);
G2L["4d"]["Rotation"] = 90;
G2L["4d"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Click TP.UIStroke
G2L["4e"] = Instance.new("UIStroke", G2L["4c"]);
G2L["4e"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Click TP.UITextSizeConstraint
G2L["4f"] = Instance.new("UITextSizeConstraint", G2L["4c"]);
G2L["4f"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Click TP.LocalScript
G2L["50"] = Instance.new("LocalScript", G2L["4c"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Click TP.Online
G2L["51"] = Instance.new("TextBox", G2L["4c"]);
G2L["51"]["Visible"] = false;
G2L["51"]["Active"] = false;
G2L["51"]["Name"] = [[Online]];
G2L["51"]["BorderSizePixel"] = 0;
G2L["51"]["TextEditable"] = false;
G2L["51"]["TextWrapped"] = true;
G2L["51"]["TextSize"] = 14;
G2L["51"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["51"]["TextScaled"] = true;
G2L["51"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["51"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["51"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["51"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["51"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["51"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["51"]["Text"] = [[OFF]];
G2L["51"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Click TP.Online.UITextSizeConstraint
G2L["52"] = Instance.new("UITextSizeConstraint", G2L["51"]);
G2L["52"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.ButtonHandler
G2L["53"] = Instance.new("LocalScript", G2L["44"]);
G2L["53"]["Name"] = [[ButtonHandler]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity
G2L["54"] = Instance.new("TextLabel", G2L["44"]);
G2L["54"]["TextWrapped"] = true;
G2L["54"]["Active"] = true;
G2L["54"]["BorderSizePixel"] = 0;
G2L["54"]["TextSize"] = 40;
G2L["54"]["TextScaled"] = true;
G2L["54"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["54"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["54"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["54"]["BackgroundTransparency"] = 1;
G2L["54"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["54"]["Visible"] = false;
G2L["54"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["54"]["Text"] = [[Gravity:]];
G2L["54"]["Selectable"] = true;
G2L["54"]["Name"] = [[Gravity]];
G2L["54"]["Position"] = UDim2.new(0, 0, 0.0011, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.UITextSizeConstraint
G2L["55"] = Instance.new("UITextSizeConstraint", G2L["54"]);
G2L["55"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.UIStroke
G2L["56"] = Instance.new("UIStroke", G2L["54"]);
G2L["56"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.UIGradient
G2L["57"] = Instance.new("UIGradient", G2L["54"]);
G2L["57"]["Rotation"] = 90;
G2L["57"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.TextBox
G2L["58"] = Instance.new("TextBox", G2L["54"]);
G2L["58"]["BorderSizePixel"] = 0;
G2L["58"]["TextWrapped"] = true;
G2L["58"]["TextSize"] = 40;
G2L["58"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["58"]["TextYAlignment"] = Enum.TextYAlignment.Bottom;
G2L["58"]["TextScaled"] = true;
G2L["58"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["58"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["58"]["Selectable"] = false;
G2L["58"]["Size"] = UDim2.new(0.3, 0, 1, 0);
G2L["58"]["Position"] = UDim2.new(0.75, 0, 0, 0);
G2L["58"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["58"]["Text"] = [[196.2]];
G2L["58"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.TextBox.UITextSizeConstraint
G2L["59"] = Instance.new("UITextSizeConstraint", G2L["58"]);
G2L["59"]["MaxTextSize"] = 50;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.TextBox.UIStroke
G2L["5a"] = Instance.new("UIStroke", G2L["58"]);
G2L["5a"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.TextBox.UIGradient
G2L["5b"] = Instance.new("UIGradient", G2L["58"]);
G2L["5b"]["Rotation"] = 90;
G2L["5b"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.TextBox.TextBoxScript
G2L["5c"] = Instance.new("LocalScript", G2L["58"]);
G2L["5c"]["Name"] = [[TextBoxScript]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.TextBox.TextBoxScript.Gravity
G2L["5d"] = Instance.new("TextBox", G2L["5c"]);
G2L["5d"]["Visible"] = false;
G2L["5d"]["Name"] = [[Gravity]];
G2L["5d"]["BorderSizePixel"] = 0;
G2L["5d"]["TextWrapped"] = true;
G2L["5d"]["TextSize"] = 14;
G2L["5d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5d"]["TextScaled"] = true;
G2L["5d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5d"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["5d"]["Size"] = UDim2.new(0.807, 0, 1.525, 0);
G2L["5d"]["Position"] = UDim2.new(28.106, 0, 148.836, 0);
G2L["5d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5d"]["Text"] = [[]];
G2L["5d"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.TextBox.Value
G2L["5e"] = Instance.new("TextBox", G2L["58"]);
G2L["5e"]["Active"] = false;
G2L["5e"]["Name"] = [[Value]];
G2L["5e"]["BorderSizePixel"] = 0;
G2L["5e"]["TextEditable"] = false;
G2L["5e"]["TextWrapped"] = true;
G2L["5e"]["TextSize"] = 14;
G2L["5e"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["TextScaled"] = true;
G2L["5e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5e"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["5e"]["Size"] = UDim2.new(0.0001, 0, 0.00001, 0);
G2L["5e"]["Position"] = UDim2.new(1112.88721, 0, 21.57368, 0);
G2L["5e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5e"]["Text"] = [[]];
G2L["5e"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.TextBox.Value.UITextSizeConstraint
G2L["5f"] = Instance.new("UITextSizeConstraint", G2L["5e"]);
G2L["5f"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Jump Height
G2L["60"] = Instance.new("TextLabel", G2L["44"]);
G2L["60"]["TextWrapped"] = true;
G2L["60"]["Active"] = true;
G2L["60"]["BorderSizePixel"] = 0;
G2L["60"]["TextSize"] = 40;
G2L["60"]["TextScaled"] = true;
G2L["60"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["60"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["60"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["60"]["BackgroundTransparency"] = 1;
G2L["60"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["60"]["Visible"] = false;
G2L["60"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["60"]["Text"] = [[Jump Height:]];
G2L["60"]["Selectable"] = true;
G2L["60"]["Name"] = [[Jump Height]];
G2L["60"]["Position"] = UDim2.new(0, 0, 0.00082, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Jump Height.UITextSizeConstraint
G2L["61"] = Instance.new("UITextSizeConstraint", G2L["60"]);
G2L["61"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Jump Height.UIStroke
G2L["62"] = Instance.new("UIStroke", G2L["60"]);
G2L["62"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Jump Height.UIGradient
G2L["63"] = Instance.new("UIGradient", G2L["60"]);
G2L["63"]["Rotation"] = 90;
G2L["63"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Jump Height.TextBox
G2L["64"] = Instance.new("TextBox", G2L["60"]);
G2L["64"]["BorderSizePixel"] = 0;
G2L["64"]["TextWrapped"] = true;
G2L["64"]["TextSize"] = 40;
G2L["64"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["64"]["TextYAlignment"] = Enum.TextYAlignment.Bottom;
G2L["64"]["TextScaled"] = true;
G2L["64"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["64"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["64"]["Selectable"] = false;
G2L["64"]["Size"] = UDim2.new(0.3, 0, 1, 0);
G2L["64"]["Position"] = UDim2.new(0.75, 0, 0, 0);
G2L["64"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["64"]["Text"] = [[7.2]];
G2L["64"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Jump Height.TextBox.UITextSizeConstraint
G2L["65"] = Instance.new("UITextSizeConstraint", G2L["64"]);
G2L["65"]["MaxTextSize"] = 50;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Jump Height.TextBox.UIStroke
G2L["66"] = Instance.new("UIStroke", G2L["64"]);
G2L["66"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Jump Height.TextBox.UIGradient
G2L["67"] = Instance.new("UIGradient", G2L["64"]);
G2L["67"]["Rotation"] = 90;
G2L["67"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Jump Height.TextBox.TextBoxScript
G2L["68"] = Instance.new("LocalScript", G2L["64"]);
G2L["68"]["Name"] = [[TextBoxScript]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Jump Height.TextBox.Value
G2L["69"] = Instance.new("TextBox", G2L["64"]);
G2L["69"]["Active"] = false;
G2L["69"]["Name"] = [[Value]];
G2L["69"]["BorderSizePixel"] = 0;
G2L["69"]["TextEditable"] = false;
G2L["69"]["TextWrapped"] = true;
G2L["69"]["TextSize"] = 14;
G2L["69"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["69"]["TextScaled"] = true;
G2L["69"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["69"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["69"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["69"]["Size"] = UDim2.new(0.0001, 0, 0.00001, 0);
G2L["69"]["Position"] = UDim2.new(1112.88721, 0, 21.57368, 0);
G2L["69"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["69"]["Text"] = [[]];
G2L["69"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Jump Height.TextBox.Value.UITextSizeConstraint
G2L["6a"] = Instance.new("UITextSizeConstraint", G2L["69"]);
G2L["6a"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Walkspeed
G2L["6b"] = Instance.new("TextLabel", G2L["44"]);
G2L["6b"]["TextWrapped"] = true;
G2L["6b"]["Active"] = true;
G2L["6b"]["BorderSizePixel"] = 0;
G2L["6b"]["TextSize"] = 40;
G2L["6b"]["TextScaled"] = true;
G2L["6b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6b"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6b"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["6b"]["BackgroundTransparency"] = 1;
G2L["6b"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["6b"]["Visible"] = false;
G2L["6b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6b"]["Text"] = [[Walkspeed:]];
G2L["6b"]["Selectable"] = true;
G2L["6b"]["Name"] = [[Walkspeed]];
G2L["6b"]["Position"] = UDim2.new(0, 0, 0.00054, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Walkspeed.UITextSizeConstraint
G2L["6c"] = Instance.new("UITextSizeConstraint", G2L["6b"]);
G2L["6c"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Walkspeed.UIStroke
G2L["6d"] = Instance.new("UIStroke", G2L["6b"]);
G2L["6d"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Walkspeed.UIGradient
G2L["6e"] = Instance.new("UIGradient", G2L["6b"]);
G2L["6e"]["Rotation"] = 90;
G2L["6e"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Walkspeed.TextBox
G2L["6f"] = Instance.new("TextBox", G2L["6b"]);
G2L["6f"]["BorderSizePixel"] = 0;
G2L["6f"]["TextWrapped"] = true;
G2L["6f"]["TextSize"] = 40;
G2L["6f"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["6f"]["TextYAlignment"] = Enum.TextYAlignment.Bottom;
G2L["6f"]["TextScaled"] = true;
G2L["6f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6f"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6f"]["Selectable"] = false;
G2L["6f"]["Size"] = UDim2.new(0.3, 0, 1, 0);
G2L["6f"]["Position"] = UDim2.new(0.75, 0, 0, 0);
G2L["6f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6f"]["Text"] = [[16]];
G2L["6f"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Walkspeed.TextBox.UITextSizeConstraint
G2L["70"] = Instance.new("UITextSizeConstraint", G2L["6f"]);
G2L["70"]["MaxTextSize"] = 50;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Walkspeed.TextBox.UIStroke
G2L["71"] = Instance.new("UIStroke", G2L["6f"]);
G2L["71"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Walkspeed.TextBox.UIGradient
G2L["72"] = Instance.new("UIGradient", G2L["6f"]);
G2L["72"]["Rotation"] = 90;
G2L["72"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Walkspeed.TextBox.TextBoxScript
G2L["73"] = Instance.new("LocalScript", G2L["6f"]);
G2L["73"]["Name"] = [[TextBoxScript]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Walkspeed.TextBox.Value
G2L["74"] = Instance.new("TextBox", G2L["6f"]);
G2L["74"]["Active"] = false;
G2L["74"]["Name"] = [[Value]];
G2L["74"]["BorderSizePixel"] = 0;
G2L["74"]["TextEditable"] = false;
G2L["74"]["TextWrapped"] = true;
G2L["74"]["TextSize"] = 14;
G2L["74"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["74"]["TextScaled"] = true;
G2L["74"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["74"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["74"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["74"]["Size"] = UDim2.new(0.0001, 0, 0.00001, 0);
G2L["74"]["Position"] = UDim2.new(1112.88721, 0, 21.57368, 0);
G2L["74"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["74"]["Text"] = [[]];
G2L["74"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Walkspeed.TextBox.Value.UITextSizeConstraint
G2L["75"] = Instance.new("UITextSizeConstraint", G2L["74"]);
G2L["75"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Flight
G2L["76"] = Instance.new("TextButton", G2L["44"]);
G2L["76"]["TextWrapped"] = true;
G2L["76"]["BorderSizePixel"] = 0;
G2L["76"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["76"]["TextSize"] = 40;
G2L["76"]["TextScaled"] = true;
G2L["76"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["76"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["76"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["76"]["BackgroundTransparency"] = 1;
G2L["76"]["Name"] = [[Flight]];
G2L["76"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["76"]["Text"] = [[Flight]];
G2L["76"]["Visible"] = false;
G2L["76"]["Position"] = UDim2.new(0, 0, -0.00004, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Flight.UIGradient
G2L["77"] = Instance.new("UIGradient", G2L["76"]);
G2L["77"]["Rotation"] = 90;
G2L["77"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Flight.UIStroke
G2L["78"] = Instance.new("UIStroke", G2L["76"]);
G2L["78"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Flight.UITextSizeConstraint
G2L["79"] = Instance.new("UITextSizeConstraint", G2L["76"]);
G2L["79"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Flight.Online
G2L["7a"] = Instance.new("TextBox", G2L["76"]);
G2L["7a"]["Visible"] = false;
G2L["7a"]["Active"] = false;
G2L["7a"]["Name"] = [[Online]];
G2L["7a"]["BorderSizePixel"] = 0;
G2L["7a"]["TextEditable"] = false;
G2L["7a"]["TextWrapped"] = true;
G2L["7a"]["TextSize"] = 14;
G2L["7a"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7a"]["TextScaled"] = true;
G2L["7a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7a"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["7a"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["7a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7a"]["Text"] = [[OFF]];
G2L["7a"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Flight.Online.UITextSizeConstraint
G2L["7b"] = Instance.new("UITextSizeConstraint", G2L["7a"]);
G2L["7b"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Flight.Speed
G2L["7c"] = Instance.new("TextBox", G2L["76"]);
G2L["7c"]["Visible"] = false;
G2L["7c"]["Active"] = false;
G2L["7c"]["Name"] = [[Speed]];
G2L["7c"]["BorderSizePixel"] = 0;
G2L["7c"]["TextEditable"] = false;
G2L["7c"]["TextWrapped"] = true;
G2L["7c"]["TextSize"] = 14;
G2L["7c"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7c"]["TextScaled"] = true;
G2L["7c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["7c"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["7c"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["7c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7c"]["Text"] = [[10]];
G2L["7c"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Flight.Speed.UITextSizeConstraint
G2L["7d"] = Instance.new("UITextSizeConstraint", G2L["7c"]);
G2L["7d"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Flight.TextBoxScript
G2L["7e"] = Instance.new("LocalScript", G2L["76"]);
G2L["7e"]["Name"] = [[TextBoxScript]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fly Speed
G2L["7f"] = Instance.new("TextLabel", G2L["44"]);
G2L["7f"]["TextWrapped"] = true;
G2L["7f"]["Active"] = true;
G2L["7f"]["BorderSizePixel"] = 0;
G2L["7f"]["TextSize"] = 40;
G2L["7f"]["TextScaled"] = true;
G2L["7f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7f"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7f"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["7f"]["BackgroundTransparency"] = 1;
G2L["7f"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["7f"]["Visible"] = false;
G2L["7f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7f"]["Text"] = [[Fly Speed:]];
G2L["7f"]["Selectable"] = true;
G2L["7f"]["Name"] = [[Fly Speed]];
G2L["7f"]["Position"] = UDim2.new(0, 0, 0.00025, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fly Speed.UITextSizeConstraint
G2L["80"] = Instance.new("UITextSizeConstraint", G2L["7f"]);
G2L["80"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fly Speed.UIStroke
G2L["81"] = Instance.new("UIStroke", G2L["7f"]);
G2L["81"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fly Speed.UIGradient
G2L["82"] = Instance.new("UIGradient", G2L["7f"]);
G2L["82"]["Rotation"] = 90;
G2L["82"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fly Speed.TextBox
G2L["83"] = Instance.new("TextBox", G2L["7f"]);
G2L["83"]["BorderSizePixel"] = 0;
G2L["83"]["TextWrapped"] = true;
G2L["83"]["TextSize"] = 40;
G2L["83"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["83"]["TextYAlignment"] = Enum.TextYAlignment.Bottom;
G2L["83"]["TextScaled"] = true;
G2L["83"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["83"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["83"]["Selectable"] = false;
G2L["83"]["Size"] = UDim2.new(0.3, 0, 1, 0);
G2L["83"]["Position"] = UDim2.new(0.75, 0, 0, 0);
G2L["83"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["83"]["Text"] = [[10]];
G2L["83"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fly Speed.TextBox.UITextSizeConstraint
G2L["84"] = Instance.new("UITextSizeConstraint", G2L["83"]);
G2L["84"]["MaxTextSize"] = 50;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fly Speed.TextBox.UIStroke
G2L["85"] = Instance.new("UIStroke", G2L["83"]);
G2L["85"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fly Speed.TextBox.UIGradient
G2L["86"] = Instance.new("UIGradient", G2L["83"]);
G2L["86"]["Rotation"] = 90;
G2L["86"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fly Speed.TextBox.TextBoxScript
G2L["87"] = Instance.new("LocalScript", G2L["83"]);
G2L["87"]["Name"] = [[TextBoxScript]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.TextBoxHandler
G2L["88"] = Instance.new("LocalScript", G2L["44"]);
G2L["88"]["Name"] = [[TextBoxHandler]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Refresh
G2L["89"] = Instance.new("TextButton", G2L["44"]);
G2L["89"]["TextWrapped"] = true;
G2L["89"]["BorderSizePixel"] = 0;
G2L["89"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["89"]["TextSize"] = 40;
G2L["89"]["TextScaled"] = true;
G2L["89"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["89"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["89"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["89"]["BackgroundTransparency"] = 1;
G2L["89"]["Name"] = [[Refresh]];
G2L["89"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["89"]["Text"] = [[Refresh]];
G2L["89"]["Visible"] = false;
G2L["89"]["Position"] = UDim2.new(0, 0, 0.00308, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Refresh.UIGradient
G2L["8a"] = Instance.new("UIGradient", G2L["89"]);
G2L["8a"]["Rotation"] = 90;
G2L["8a"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Refresh.UIStroke
G2L["8b"] = Instance.new("UIStroke", G2L["89"]);
G2L["8b"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Refresh.UITextSizeConstraint
G2L["8c"] = Instance.new("UITextSizeConstraint", G2L["89"]);
G2L["8c"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Refresh.Online
G2L["8d"] = Instance.new("TextBox", G2L["89"]);
G2L["8d"]["Visible"] = false;
G2L["8d"]["Active"] = false;
G2L["8d"]["Name"] = [[Online]];
G2L["8d"]["BorderSizePixel"] = 0;
G2L["8d"]["TextEditable"] = false;
G2L["8d"]["TextWrapped"] = true;
G2L["8d"]["TextSize"] = 14;
G2L["8d"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8d"]["TextScaled"] = true;
G2L["8d"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8d"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["8d"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["8d"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["8d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["8d"]["Text"] = [[OFF]];
G2L["8d"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Refresh.Online.UITextSizeConstraint
G2L["8e"] = Instance.new("UITextSizeConstraint", G2L["8d"]);
G2L["8e"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Refresh.LocalScript
G2L["8f"] = Instance.new("LocalScript", G2L["89"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Invisible
G2L["90"] = Instance.new("TextButton", G2L["44"]);
G2L["90"]["TextWrapped"] = true;
G2L["90"]["BorderSizePixel"] = 0;
G2L["90"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["90"]["TextSize"] = 40;
G2L["90"]["TextScaled"] = true;
G2L["90"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["90"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["90"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["90"]["BackgroundTransparency"] = 1;
G2L["90"]["Name"] = [[Invisible]];
G2L["90"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["90"]["Text"] = [[Invisible]];
G2L["90"]["Visible"] = false;
G2L["90"]["Position"] = UDim2.new(0, 0, 0.00223, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Invisible.UIGradient
G2L["91"] = Instance.new("UIGradient", G2L["90"]);
G2L["91"]["Rotation"] = 90;
G2L["91"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Invisible.UIStroke
G2L["92"] = Instance.new("UIStroke", G2L["90"]);
G2L["92"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Invisible.UITextSizeConstraint
G2L["93"] = Instance.new("UITextSizeConstraint", G2L["90"]);
G2L["93"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Invisible.Online
G2L["94"] = Instance.new("TextBox", G2L["90"]);
G2L["94"]["Visible"] = false;
G2L["94"]["Active"] = false;
G2L["94"]["Name"] = [[Online]];
G2L["94"]["BorderSizePixel"] = 0;
G2L["94"]["TextEditable"] = false;
G2L["94"]["TextWrapped"] = true;
G2L["94"]["TextSize"] = 14;
G2L["94"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["94"]["TextScaled"] = true;
G2L["94"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["94"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["94"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["94"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["94"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["94"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["94"]["Text"] = [[OFF]];
G2L["94"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Invisible.Online.UITextSizeConstraint
G2L["95"] = Instance.new("UITextSizeConstraint", G2L["94"]);
G2L["95"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Invisible.LocalScript
G2L["96"] = Instance.new("LocalScript", G2L["90"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Noclip
G2L["97"] = Instance.new("TextButton", G2L["44"]);
G2L["97"]["TextWrapped"] = true;
G2L["97"]["BorderSizePixel"] = 0;
G2L["97"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["97"]["TextSize"] = 40;
G2L["97"]["TextScaled"] = true;
G2L["97"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["97"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["97"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["97"]["BackgroundTransparency"] = 1;
G2L["97"]["Name"] = [[Noclip]];
G2L["97"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["97"]["Text"] = [[Noclip]];
G2L["97"]["Visible"] = false;
G2L["97"]["Position"] = UDim2.new(0, 0, 0.00195, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Noclip.UIGradient
G2L["98"] = Instance.new("UIGradient", G2L["97"]);
G2L["98"]["Rotation"] = 90;
G2L["98"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Noclip.UIStroke
G2L["99"] = Instance.new("UIStroke", G2L["97"]);
G2L["99"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Noclip.UITextSizeConstraint
G2L["9a"] = Instance.new("UITextSizeConstraint", G2L["97"]);
G2L["9a"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Noclip.Online
G2L["9b"] = Instance.new("TextBox", G2L["97"]);
G2L["9b"]["Visible"] = false;
G2L["9b"]["Active"] = false;
G2L["9b"]["Name"] = [[Online]];
G2L["9b"]["BorderSizePixel"] = 0;
G2L["9b"]["TextEditable"] = false;
G2L["9b"]["TextWrapped"] = true;
G2L["9b"]["TextSize"] = 14;
G2L["9b"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9b"]["TextScaled"] = true;
G2L["9b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["9b"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["9b"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["9b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9b"]["Text"] = [[OFF]];
G2L["9b"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Noclip.Online.UITextSizeConstraint
G2L["9c"] = Instance.new("UITextSizeConstraint", G2L["9b"]);
G2L["9c"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Noclip.TextBoxScript
G2L["9d"] = Instance.new("LocalScript", G2L["97"]);
G2L["9d"]["Name"] = [[TextBoxScript]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Dashing
G2L["9e"] = Instance.new("TextButton", G2L["44"]);
G2L["9e"]["TextWrapped"] = true;
G2L["9e"]["BorderSizePixel"] = 0;
G2L["9e"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["9e"]["TextSize"] = 40;
G2L["9e"]["TextScaled"] = true;
G2L["9e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9e"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9e"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["9e"]["BackgroundTransparency"] = 1;
G2L["9e"]["Name"] = [[Dashing]];
G2L["9e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["9e"]["Text"] = [[Dashing]];
G2L["9e"]["Visible"] = false;
G2L["9e"]["Position"] = UDim2.new(0, 0, 0.00251, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Dashing.UIGradient
G2L["9f"] = Instance.new("UIGradient", G2L["9e"]);
G2L["9f"]["Rotation"] = 90;
G2L["9f"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Dashing.UIStroke
G2L["a0"] = Instance.new("UIStroke", G2L["9e"]);
G2L["a0"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Dashing.UITextSizeConstraint
G2L["a1"] = Instance.new("UITextSizeConstraint", G2L["9e"]);
G2L["a1"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Dashing.Online
G2L["a2"] = Instance.new("TextBox", G2L["9e"]);
G2L["a2"]["Visible"] = false;
G2L["a2"]["Active"] = false;
G2L["a2"]["Name"] = [[Online]];
G2L["a2"]["BorderSizePixel"] = 0;
G2L["a2"]["TextEditable"] = false;
G2L["a2"]["TextWrapped"] = true;
G2L["a2"]["TextSize"] = 14;
G2L["a2"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a2"]["TextScaled"] = true;
G2L["a2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a2"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a2"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["a2"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["a2"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["a2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a2"]["Text"] = [[OFF]];
G2L["a2"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Dashing.Online.UITextSizeConstraint
G2L["a3"] = Instance.new("UITextSizeConstraint", G2L["a2"]);
G2L["a3"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Dashing.Dash
G2L["a4"] = Instance.new("LocalScript", G2L["9e"]);
G2L["a4"]["Name"] = [[Dash]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fling
G2L["a5"] = Instance.new("TextButton", G2L["44"]);
G2L["a5"]["TextWrapped"] = true;
G2L["a5"]["BorderSizePixel"] = 0;
G2L["a5"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["a5"]["TextSize"] = 40;
G2L["a5"]["TextScaled"] = true;
G2L["a5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a5"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a5"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["a5"]["BackgroundTransparency"] = 1;
G2L["a5"]["Name"] = [[Fling]];
G2L["a5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a5"]["Text"] = [[Fling]];
G2L["a5"]["Visible"] = false;
G2L["a5"]["Position"] = UDim2.new(0, 0, 0.0028, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fling.UIGradient
G2L["a6"] = Instance.new("UIGradient", G2L["a5"]);
G2L["a6"]["Rotation"] = 90;
G2L["a6"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fling.UIStroke
G2L["a7"] = Instance.new("UIStroke", G2L["a5"]);
G2L["a7"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fling.UITextSizeConstraint
G2L["a8"] = Instance.new("UITextSizeConstraint", G2L["a5"]);
G2L["a8"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fling.Online
G2L["a9"] = Instance.new("TextBox", G2L["a5"]);
G2L["a9"]["Visible"] = false;
G2L["a9"]["Active"] = false;
G2L["a9"]["Name"] = [[Online]];
G2L["a9"]["BorderSizePixel"] = 0;
G2L["a9"]["TextEditable"] = false;
G2L["a9"]["TextWrapped"] = true;
G2L["a9"]["TextSize"] = 14;
G2L["a9"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a9"]["TextScaled"] = true;
G2L["a9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a9"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["a9"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["a9"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["a9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a9"]["Text"] = [[OFF]];
G2L["a9"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fling.Online.UITextSizeConstraint
G2L["aa"] = Instance.new("UITextSizeConstraint", G2L["a9"]);
G2L["aa"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fling.LocalScript
G2L["ab"] = Instance.new("LocalScript", G2L["a5"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players
G2L["ac"] = Instance.new("Folder", G2L["2c"]);
G2L["ac"]["Name"] = [[Players]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.UIListLayout
G2L["ad"] = Instance.new("UIListLayout", G2L["ac"]);
G2L["ad"]["HorizontalAlignment"] = Enum.HorizontalAlignment.Center;
G2L["ad"]["Padding"] = UDim.new(-0, 0);
G2L["ad"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.Searchbar
G2L["ae"] = Instance.new("TextBox", G2L["ac"]);
G2L["ae"]["Visible"] = false;
G2L["ae"]["Name"] = [[Searchbar]];
G2L["ae"]["BorderSizePixel"] = 0;
G2L["ae"]["TextWrapped"] = true;
G2L["ae"]["TextSize"] = 100;
G2L["ae"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["ae"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["ae"]["TextScaled"] = true;
G2L["ae"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ae"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Italic);
G2L["ae"]["Selectable"] = false;
G2L["ae"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["ae"]["Size"] = UDim2.new(0.959, 0, 0.00003, 0);
G2L["ae"]["Position"] = UDim2.new(0, 156, 0, 24);
G2L["ae"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ae"]["Text"] = [[Search...]];
G2L["ae"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.Searchbar.UITextSizeConstraint
G2L["af"] = Instance.new("UITextSizeConstraint", G2L["ae"]);
G2L["af"]["MaxTextSize"] = 50;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.Searchbar.UIStroke
G2L["b0"] = Instance.new("UIStroke", G2L["ae"]);
G2L["b0"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.Searchbar.UIGradient
G2L["b1"] = Instance.new("UIGradient", G2L["ae"]);
G2L["b1"]["Rotation"] = 90;
G2L["b1"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.LocalScript
G2L["b2"] = Instance.new("LocalScript", G2L["ac"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.Demo
G2L["b3"] = Instance.new("Frame", G2L["ac"]);
G2L["b3"]["Visible"] = false;
G2L["b3"]["Active"] = true;
G2L["b3"]["BorderSizePixel"] = 0;
G2L["b3"]["BackgroundColor3"] = Color3.fromRGB(26, 26, 26);
G2L["b3"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["b3"]["Size"] = UDim2.new(0.959, 0, 0.00003, 0);
G2L["b3"]["Position"] = UDim2.new(0, 156, 0, 75);
G2L["b3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b3"]["Name"] = [[Demo]];
G2L["b3"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.Demo.Username
G2L["b4"] = Instance.new("TextButton", G2L["b3"]);
G2L["b4"]["TextWrapped"] = true;
G2L["b4"]["BorderSizePixel"] = 0;
G2L["b4"]["TextColor3"] = Color3.fromRGB(164, 163, 166);
G2L["b4"]["TextSize"] = 14;
G2L["b4"]["TextScaled"] = true;
G2L["b4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b4"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b4"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["b4"]["Size"] = UDim2.new(0.56117, 0, 0.885, 0);
G2L["b4"]["BackgroundTransparency"] = 1;
G2L["b4"]["Name"] = [[Username]];
G2L["b4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b4"]["Text"] = [[Player1]];
G2L["b4"]["Position"] = UDim2.new(0.5, 0, 0.461, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.Demo.Username.UIGradient
G2L["b5"] = Instance.new("UIGradient", G2L["b4"]);
G2L["b5"]["Rotation"] = 90;
G2L["b5"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.Demo.Username.UIStroke
G2L["b6"] = Instance.new("UIStroke", G2L["b4"]);
G2L["b6"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.Demo.Username.UITextSizeConstraint
G2L["b7"] = Instance.new("UITextSizeConstraint", G2L["b4"]);
G2L["b7"]["MaxTextSize"] = 50;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.Demo.ImageButtonR
G2L["b8"] = Instance.new("ImageButton", G2L["b3"]);
G2L["b8"]["BorderSizePixel"] = 0;
G2L["b8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b8"]["AnchorPoint"] = Vector2.new(0, 0.035);
G2L["b8"]["Image"] = [[rbxassetid://119531777515278]];
G2L["b8"]["Size"] = UDim2.new(0.12996, 0, 0.836, 0);
G2L["b8"]["BackgroundTransparency"] = 1;
G2L["b8"]["Name"] = [[ImageButtonR]];
G2L["b8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b8"]["Position"] = UDim2.new(0.80993, 0, 0.03144, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.Demo.ImageButtonL
G2L["b9"] = Instance.new("ImageButton", G2L["b3"]);
G2L["b9"]["BorderSizePixel"] = 0;
G2L["b9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b9"]["Image"] = [[rbxassetid://119531777515278]];
G2L["b9"]["ImageRectSize"] = Vector2.new(-1024, 1024);
G2L["b9"]["Size"] = UDim2.new(0.12997, 0, 0.836, 0);
G2L["b9"]["BackgroundTransparency"] = 1;
G2L["b9"]["Name"] = [[ImageButtonL]];
G2L["b9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b9"]["ImageRectOffset"] = Vector2.new(1024, 0);
G2L["b9"]["Position"] = UDim2.new(0.05984, 0, 0.03144, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.ButtonHandler
G2L["ba"] = Instance.new("LocalScript", G2L["ac"]);
G2L["ba"]["Name"] = [[ButtonHandler]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target
G2L["bb"] = Instance.new("Folder", G2L["2c"]);
G2L["bb"]["Name"] = [[Target]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.TargetName
G2L["bc"] = Instance.new("TextButton", G2L["bb"]);
G2L["bc"]["TextWrapped"] = true;
G2L["bc"]["BorderSizePixel"] = 0;
G2L["bc"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["bc"]["TextSize"] = 40;
G2L["bc"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["bc"]["TextScaled"] = true;
G2L["bc"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["bc"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["bc"]["Size"] = UDim2.new(0.959, 0, 0.00027, 0);
G2L["bc"]["BackgroundTransparency"] = 1;
G2L["bc"]["Name"] = [[TargetName]];
G2L["bc"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["bc"]["Text"] = [[@Target]];
G2L["bc"]["Position"] = UDim2.new(0, 0, -0.00004, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.TargetName.UITextSizeConstraint
G2L["bd"] = Instance.new("UITextSizeConstraint", G2L["bc"]);
G2L["bd"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.TargetName.UIStroke
G2L["be"] = Instance.new("UIStroke", G2L["bc"]);
G2L["be"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.TargetName.UIGradient
G2L["bf"] = Instance.new("UIGradient", G2L["bc"]);
G2L["bf"]["Rotation"] = 90;
G2L["bf"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.TargetName.Online
G2L["c0"] = Instance.new("TextBox", G2L["bc"]);
G2L["c0"]["Visible"] = false;
G2L["c0"]["Active"] = false;
G2L["c0"]["Name"] = [[Online]];
G2L["c0"]["BorderSizePixel"] = 0;
G2L["c0"]["TextEditable"] = false;
G2L["c0"]["TextWrapped"] = true;
G2L["c0"]["TextSize"] = 14;
G2L["c0"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c0"]["TextScaled"] = true;
G2L["c0"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c0"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["c0"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["c0"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["c0"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["c0"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c0"]["Text"] = [[OFF]];
G2L["c0"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.TargetName.Online.UITextSizeConstraint
G2L["c1"] = Instance.new("UITextSizeConstraint", G2L["c0"]);
G2L["c1"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.TargetName.TextBoxScript
G2L["c2"] = Instance.new("LocalScript", G2L["bc"]);
G2L["c2"]["Name"] = [[TextBoxScript]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Teleport
G2L["c3"] = Instance.new("TextButton", G2L["bb"]);
G2L["c3"]["TextWrapped"] = true;
G2L["c3"]["BorderSizePixel"] = 0;
G2L["c3"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["c3"]["TextSize"] = 40;
G2L["c3"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["c3"]["TextScaled"] = true;
G2L["c3"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c3"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["c3"]["Size"] = UDim2.new(0.959, 0, 0.00027, 0);
G2L["c3"]["BackgroundTransparency"] = 1;
G2L["c3"]["Name"] = [[Teleport]];
G2L["c3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c3"]["Text"] = [[Teleport]];
G2L["c3"]["Position"] = UDim2.new(0, 0, 0.00024, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Teleport.UITextSizeConstraint
G2L["c4"] = Instance.new("UITextSizeConstraint", G2L["c3"]);
G2L["c4"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Teleport.UIStroke
G2L["c5"] = Instance.new("UIStroke", G2L["c3"]);
G2L["c5"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Teleport.UIGradient
G2L["c6"] = Instance.new("UIGradient", G2L["c3"]);
G2L["c6"]["Rotation"] = 90;
G2L["c6"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Teleport.Online
G2L["c7"] = Instance.new("TextBox", G2L["c3"]);
G2L["c7"]["Visible"] = false;
G2L["c7"]["Active"] = false;
G2L["c7"]["Name"] = [[Online]];
G2L["c7"]["BorderSizePixel"] = 0;
G2L["c7"]["TextEditable"] = false;
G2L["c7"]["TextWrapped"] = true;
G2L["c7"]["TextSize"] = 14;
G2L["c7"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c7"]["TextScaled"] = true;
G2L["c7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["c7"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["c7"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["c7"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["c7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c7"]["Text"] = [[OFF]];
G2L["c7"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Teleport.Online.UITextSizeConstraint
G2L["c8"] = Instance.new("UITextSizeConstraint", G2L["c7"]);
G2L["c8"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Teleport.LocalScript
G2L["c9"] = Instance.new("LocalScript", G2L["c3"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Fling
G2L["ca"] = Instance.new("TextButton", G2L["bb"]);
G2L["ca"]["TextWrapped"] = true;
G2L["ca"]["BorderSizePixel"] = 0;
G2L["ca"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["ca"]["TextSize"] = 40;
G2L["ca"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["ca"]["TextScaled"] = true;
G2L["ca"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ca"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["ca"]["Size"] = UDim2.new(0.959, 0, 0.00027, 0);
G2L["ca"]["BackgroundTransparency"] = 1;
G2L["ca"]["Name"] = [[Fling]];
G2L["ca"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ca"]["Text"] = [[Fling]];
G2L["ca"]["Position"] = UDim2.new(0, 0, 0.00051, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Fling.UITextSizeConstraint
G2L["cb"] = Instance.new("UITextSizeConstraint", G2L["ca"]);
G2L["cb"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Fling.UIStroke
G2L["cc"] = Instance.new("UIStroke", G2L["ca"]);
G2L["cc"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Fling.UIGradient
G2L["cd"] = Instance.new("UIGradient", G2L["ca"]);
G2L["cd"]["Rotation"] = 90;
G2L["cd"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Fling.Online
G2L["ce"] = Instance.new("TextBox", G2L["ca"]);
G2L["ce"]["Visible"] = false;
G2L["ce"]["Active"] = false;
G2L["ce"]["Name"] = [[Online]];
G2L["ce"]["BorderSizePixel"] = 0;
G2L["ce"]["TextEditable"] = false;
G2L["ce"]["TextWrapped"] = true;
G2L["ce"]["TextSize"] = 14;
G2L["ce"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ce"]["TextScaled"] = true;
G2L["ce"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ce"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["ce"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["ce"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["ce"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["ce"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ce"]["Text"] = [[OFF]];
G2L["ce"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Fling.Online.UITextSizeConstraint
G2L["cf"] = Instance.new("UITextSizeConstraint", G2L["ce"]);
G2L["cf"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Fling.LocalScript
G2L["d0"] = Instance.new("LocalScript", G2L["ca"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Bang
G2L["d1"] = Instance.new("TextButton", G2L["bb"]);
G2L["d1"]["TextWrapped"] = true;
G2L["d1"]["BorderSizePixel"] = 0;
G2L["d1"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["d1"]["TextSize"] = 40;
G2L["d1"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["d1"]["TextScaled"] = true;
G2L["d1"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d1"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["d1"]["Size"] = UDim2.new(0.959, 0, 0.00027, 0);
G2L["d1"]["BackgroundTransparency"] = 1;
G2L["d1"]["Name"] = [[Bang]];
G2L["d1"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d1"]["Text"] = [[Bang]];
G2L["d1"]["Position"] = UDim2.new(0, 0, 0.00078, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Bang.UITextSizeConstraint
G2L["d2"] = Instance.new("UITextSizeConstraint", G2L["d1"]);
G2L["d2"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Bang.UIStroke
G2L["d3"] = Instance.new("UIStroke", G2L["d1"]);
G2L["d3"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Bang.UIGradient
G2L["d4"] = Instance.new("UIGradient", G2L["d1"]);
G2L["d4"]["Rotation"] = 90;
G2L["d4"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Bang.Online
G2L["d5"] = Instance.new("TextBox", G2L["d1"]);
G2L["d5"]["Visible"] = false;
G2L["d5"]["Active"] = false;
G2L["d5"]["Name"] = [[Online]];
G2L["d5"]["BorderSizePixel"] = 0;
G2L["d5"]["TextEditable"] = false;
G2L["d5"]["TextWrapped"] = true;
G2L["d5"]["TextSize"] = 14;
G2L["d5"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d5"]["TextScaled"] = true;
G2L["d5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["d5"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["d5"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["d5"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["d5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d5"]["Text"] = [[OFF]];
G2L["d5"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Bang.Online.UITextSizeConstraint
G2L["d6"] = Instance.new("UITextSizeConstraint", G2L["d5"]);
G2L["d6"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Bang.LocalScript
G2L["d7"] = Instance.new("LocalScript", G2L["d1"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.ESP
G2L["d8"] = Instance.new("TextButton", G2L["bb"]);
G2L["d8"]["TextWrapped"] = true;
G2L["d8"]["BorderSizePixel"] = 0;
G2L["d8"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["d8"]["TextSize"] = 40;
G2L["d8"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["d8"]["TextScaled"] = true;
G2L["d8"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d8"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["d8"]["Size"] = UDim2.new(0.959, 0, 0.00027, 0);
G2L["d8"]["BackgroundTransparency"] = 1;
G2L["d8"]["Name"] = [[ESP]];
G2L["d8"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d8"]["Text"] = [[ESP]];
G2L["d8"]["Position"] = UDim2.new(0, 0, 0.00105, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.ESP.UITextSizeConstraint
G2L["d9"] = Instance.new("UITextSizeConstraint", G2L["d8"]);
G2L["d9"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.ESP.UIStroke
G2L["da"] = Instance.new("UIStroke", G2L["d8"]);
G2L["da"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.ESP.UIGradient
G2L["db"] = Instance.new("UIGradient", G2L["d8"]);
G2L["db"]["Rotation"] = 90;
G2L["db"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.ESP.Online
G2L["dc"] = Instance.new("TextBox", G2L["d8"]);
G2L["dc"]["Visible"] = false;
G2L["dc"]["Active"] = false;
G2L["dc"]["Name"] = [[Online]];
G2L["dc"]["BorderSizePixel"] = 0;
G2L["dc"]["TextEditable"] = false;
G2L["dc"]["TextWrapped"] = true;
G2L["dc"]["TextSize"] = 14;
G2L["dc"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["dc"]["TextScaled"] = true;
G2L["dc"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["dc"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["dc"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["dc"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["dc"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["dc"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["dc"]["Text"] = [[OFF]];
G2L["dc"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.ESP.Online.UITextSizeConstraint
G2L["dd"] = Instance.new("UITextSizeConstraint", G2L["dc"]);
G2L["dd"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.ButtonHandler
G2L["de"] = Instance.new("LocalScript", G2L["bb"]);
G2L["de"]["Name"] = [[ButtonHandler]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.TextBoxHandler
G2L["df"] = Instance.new("LocalScript", G2L["bb"]);
G2L["df"]["Name"] = [[TextBoxHandler]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.AVA_R
G2L["e0"] = Instance.new("ImageLabel", G2L["bb"]);
G2L["e0"]["BorderSizePixel"] = 0;
G2L["e0"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e0"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["e0"]["Image"] = [[rbxassetid://105494565898698]];
G2L["e0"]["Size"] = UDim2.new(0.31308, 0, 0.00067, 0);
G2L["e0"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e0"]["BackgroundTransparency"] = 1;
G2L["e0"]["Name"] = [[AVA_R]];
G2L["e0"]["Position"] = UDim2.new(0.80717, 0, 0.00084, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.AVA_L
G2L["e1"] = Instance.new("ImageLabel", G2L["bb"]);
G2L["e1"]["BorderSizePixel"] = 0;
G2L["e1"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e1"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["e1"]["Image"] = [[rbxassetid://105494565898698]];
G2L["e1"]["ImageRectSize"] = Vector2.new(-1024, 1024);
G2L["e1"]["Size"] = UDim2.new(0.31308, 0, 0.00067, 0);
G2L["e1"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e1"]["BackgroundTransparency"] = 1;
G2L["e1"]["ImageRectOffset"] = Vector2.new(1024, 0);
G2L["e1"]["Name"] = [[AVA_L]];
G2L["e1"]["Position"] = UDim2.new(0.1475, 0, 0.00084, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.AvatarScript
G2L["e2"] = Instance.new("LocalScript", G2L["bb"]);
G2L["e2"]["Name"] = [[AvatarScript]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.FlingActive
G2L["e3"] = Instance.new("TextBox", G2L["2c"]);
G2L["e3"]["Visible"] = false;
G2L["e3"]["Active"] = false;
G2L["e3"]["Name"] = [[FlingActive]];
G2L["e3"]["BorderSizePixel"] = 0;
G2L["e3"]["TextEditable"] = false;
G2L["e3"]["TextWrapped"] = true;
G2L["e3"]["TextSize"] = 14;
G2L["e3"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e3"]["TextScaled"] = true;
G2L["e3"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e3"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["e3"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["e3"]["Size"] = UDim2.new(0.80661, 0, 1.52531, 0);
G2L["e3"]["Position"] = UDim2.new(28.10648, 0, 148.83604, 0);
G2L["e3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e3"]["Text"] = [[OFF]];
G2L["e3"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.FlingActive.UITextSizeConstraint
G2L["e4"] = Instance.new("UITextSizeConstraint", G2L["e3"]);
G2L["e4"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous
G2L["e5"] = Instance.new("Folder", G2L["2c"]);
G2L["e5"]["Name"] = [[Miscellaneous]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous.ButtonHandler
G2L["e6"] = Instance.new("LocalScript", G2L["e5"]);
G2L["e6"]["Name"] = [[ButtonHandler]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous.Jerk Off
G2L["e7"] = Instance.new("TextButton", G2L["e5"]);
G2L["e7"]["TextWrapped"] = true;
G2L["e7"]["BorderSizePixel"] = 0;
G2L["e7"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["e7"]["TextSize"] = 40;
G2L["e7"]["TextScaled"] = true;
G2L["e7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e7"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["e7"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["e7"]["BackgroundTransparency"] = 1;
G2L["e7"]["Name"] = [[Jerk Off]];
G2L["e7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e7"]["Text"] = [[Jerk Off]];
G2L["e7"]["Visible"] = false;
G2L["e7"]["Position"] = UDim2.new(0, 0, -0.00004, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous.Jerk Off.UIGradient
G2L["e8"] = Instance.new("UIGradient", G2L["e7"]);
G2L["e8"]["Rotation"] = 90;
G2L["e8"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous.Jerk Off.UIStroke
G2L["e9"] = Instance.new("UIStroke", G2L["e7"]);
G2L["e9"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous.Jerk Off.UITextSizeConstraint
G2L["ea"] = Instance.new("UITextSizeConstraint", G2L["e7"]);
G2L["ea"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous.Jerk Off.LocalScript
G2L["eb"] = Instance.new("LocalScript", G2L["e7"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous.Jerk Off.Online
G2L["ec"] = Instance.new("TextBox", G2L["e7"]);
G2L["ec"]["Visible"] = false;
G2L["ec"]["Active"] = false;
G2L["ec"]["Name"] = [[Online]];
G2L["ec"]["BorderSizePixel"] = 0;
G2L["ec"]["TextEditable"] = false;
G2L["ec"]["TextWrapped"] = true;
G2L["ec"]["TextSize"] = 14;
G2L["ec"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ec"]["TextScaled"] = true;
G2L["ec"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ec"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["ec"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["ec"]["Size"] = UDim2.new(0.39997, 0, 0.20484, 0);
G2L["ec"]["Position"] = UDim2.new(0, -59, 69, -30);
G2L["ec"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ec"]["Text"] = [[OFF]];
G2L["ec"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous.Jerk Off.Online.UITextSizeConstraint
G2L["ed"] = Instance.new("UITextSizeConstraint", G2L["ec"]);
G2L["ed"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous.TextBoxHandler
G2L["ee"] = Instance.new("LocalScript", G2L["e5"]);
G2L["ee"]["Name"] = [[TextBoxHandler]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs
G2L["ef"] = Instance.new("Folder", G2L["2c"]);
G2L["ef"]["Name"] = [[Script Hubs]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.ButtonHandler
G2L["f0"] = Instance.new("LocalScript", G2L["ef"]);
G2L["f0"]["Name"] = [[ButtonHandler]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Solara Hub
G2L["f1"] = Instance.new("TextButton", G2L["ef"]);
G2L["f1"]["TextWrapped"] = true;
G2L["f1"]["BorderSizePixel"] = 0;
G2L["f1"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["f1"]["TextSize"] = 40;
G2L["f1"]["TextScaled"] = true;
G2L["f1"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f1"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["f1"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["f1"]["BackgroundTransparency"] = 1;
G2L["f1"]["Name"] = [[Solara Hub]];
G2L["f1"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f1"]["Text"] = [[Solara Hub]];
G2L["f1"]["Visible"] = false;
G2L["f1"]["Position"] = UDim2.new(0, 0, -0.00004, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Solara Hub.UIGradient
G2L["f2"] = Instance.new("UIGradient", G2L["f1"]);
G2L["f2"]["Rotation"] = 90;
G2L["f2"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Solara Hub.UIStroke
G2L["f3"] = Instance.new("UIStroke", G2L["f1"]);
G2L["f3"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Solara Hub.UITextSizeConstraint
G2L["f4"] = Instance.new("UITextSizeConstraint", G2L["f1"]);
G2L["f4"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Solara Hub.LocalScript
G2L["f5"] = Instance.new("LocalScript", G2L["f1"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Solara Hub.Online
G2L["f6"] = Instance.new("TextBox", G2L["f1"]);
G2L["f6"]["Visible"] = false;
G2L["f6"]["Active"] = false;
G2L["f6"]["Name"] = [[Online]];
G2L["f6"]["BorderSizePixel"] = 0;
G2L["f6"]["TextEditable"] = false;
G2L["f6"]["TextWrapped"] = true;
G2L["f6"]["TextSize"] = 14;
G2L["f6"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f6"]["TextScaled"] = true;
G2L["f6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["f6"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["f6"]["Size"] = UDim2.new(0.001, 0, 0.001, 0);
G2L["f6"]["Position"] = UDim2.new(69420, 69, 69420, 69);
G2L["f6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f6"]["Text"] = [[OFF]];
G2L["f6"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Solara Hub.Online.UITextSizeConstraint
G2L["f7"] = Instance.new("UITextSizeConstraint", G2L["f6"]);
G2L["f7"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.TextBoxHandler
G2L["f8"] = Instance.new("LocalScript", G2L["ef"]);
G2L["f8"]["Name"] = [[TextBoxHandler]];


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Sirius
G2L["f9"] = Instance.new("TextButton", G2L["ef"]);
G2L["f9"]["TextWrapped"] = true;
G2L["f9"]["BorderSizePixel"] = 0;
G2L["f9"]["TextColor3"] = Color3.fromRGB(255, 0, 0);
G2L["f9"]["TextSize"] = 40;
G2L["f9"]["TextScaled"] = true;
G2L["f9"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f9"]["FontFace"] = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["f9"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["f9"]["Size"] = UDim2.new(0.95914, 0, 0.00028, 0);
G2L["f9"]["BackgroundTransparency"] = 1;
G2L["f9"]["Name"] = [[Sirius]];
G2L["f9"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["f9"]["Text"] = [[Sirius]];
G2L["f9"]["Visible"] = false;
G2L["f9"]["Position"] = UDim2.new(0.47714, 0, 0.00038, 0);


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Sirius.UIGradient
G2L["fa"] = Instance.new("UIGradient", G2L["f9"]);
G2L["fa"]["Rotation"] = 90;
G2L["fa"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(255, 255, 255)),ColorSequenceKeypoint.new(0.369, Color3.fromRGB(244, 244, 244)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(0, 0, 0))};


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Sirius.UIStroke
G2L["fb"] = Instance.new("UIStroke", G2L["f9"]);
G2L["fb"]["Thickness"] = 3;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Sirius.UITextSizeConstraint
G2L["fc"] = Instance.new("UITextSizeConstraint", G2L["f9"]);
G2L["fc"]["MaxTextSize"] = 69;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Sirius.LocalScript
G2L["fd"] = Instance.new("LocalScript", G2L["f9"]);



-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Sirius.Online
G2L["fe"] = Instance.new("TextBox", G2L["f9"]);
G2L["fe"]["Visible"] = false;
G2L["fe"]["Active"] = false;
G2L["fe"]["Name"] = [[Online]];
G2L["fe"]["BorderSizePixel"] = 0;
G2L["fe"]["TextEditable"] = false;
G2L["fe"]["TextWrapped"] = true;
G2L["fe"]["TextSize"] = 14;
G2L["fe"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["fe"]["TextScaled"] = true;
G2L["fe"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["fe"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["fe"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["fe"]["Size"] = UDim2.new(0.001, 0, 0.001, 0);
G2L["fe"]["Position"] = UDim2.new(69420, 69, 69420, 69);
G2L["fe"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["fe"]["Text"] = [[OFF]];
G2L["fe"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Sirius.Online.UITextSizeConstraint
G2L["ff"] = Instance.new("UITextSizeConstraint", G2L["fe"]);
G2L["ff"]["MaxTextSize"] = 71;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.UIListLayout
G2L["100"] = Instance.new("UIListLayout", G2L["2b"]);
G2L["100"]["Padding"] = UDim.new(0.025, 0);
G2L["100"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrameProperties
G2L["101"] = Instance.new("LocalScript", G2L["29"]);
G2L["101"]["Name"] = [[ScrollingFrameProperties]];


-- StarterGui.DREADED_HUB.WholeThang.Bone
G2L["102"] = Instance.new("Frame", G2L["2"]);
G2L["102"]["BorderSizePixel"] = 0;
G2L["102"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["102"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["102"]["Size"] = UDim2.new(0.292, 0, 0.863, 0);
G2L["102"]["Position"] = UDim2.new(0.146, 0, 0.569, 0);
G2L["102"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["102"]["Name"] = [[Bone]];
G2L["102"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.Bone.UIStroke
G2L["103"] = Instance.new("UIStroke", G2L["102"]);
G2L["103"]["Thickness"] = 5;


-- StarterGui.DREADED_HUB.WholeThang.Tab
G2L["104"] = Instance.new("TextBox", G2L["2"]);
G2L["104"]["Visible"] = false;
G2L["104"]["Name"] = [[Tab]];
G2L["104"]["BorderSizePixel"] = 0;
G2L["104"]["TextWrapped"] = true;
G2L["104"]["TextSize"] = 14;
G2L["104"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["104"]["TextScaled"] = true;
G2L["104"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["104"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["104"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["104"]["Size"] = UDim2.new(0.28565, 0, 0.11902, 0);
G2L["104"]["Position"] = UDim2.new(0, 1, 0, 1);
G2L["104"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["104"]["Text"] = [[Dashboard]];
G2L["104"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.UIAspectRatioConstraint
G2L["105"] = Instance.new("UIAspectRatioConstraint", G2L["1"]);
G2L["105"]["AspectRatio"] = 1.8396;


-- StarterGui.DREADED_HUB.LoadedSound
G2L["106"] = Instance.new("LocalScript", G2L["1"]);
G2L["106"]["Name"] = [[LoadedSound]];


-- StarterGui.DREADED_HUB.KILL_SWITCH
G2L["107"] = Instance.new("LocalScript", G2L["1"]);
G2L["107"]["Name"] = [[KILL_SWITCH]];


-- StarterGui.DREADED_HUB.KILL_SWITCH.KILLING
G2L["108"] = Instance.new("TextBox", G2L["107"]);
G2L["108"]["Visible"] = false;
G2L["108"]["Name"] = [[KILLING]];
G2L["108"]["BorderSizePixel"] = 0;
G2L["108"]["TextWrapped"] = true;
G2L["108"]["TextSize"] = 14;
G2L["108"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["108"]["TextScaled"] = true;
G2L["108"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["108"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["108"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["108"]["Size"] = UDim2.new(0.807, 0, 1.525, 0);
G2L["108"]["Position"] = UDim2.new(28.106, 0, 148.836, 0);
G2L["108"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["108"]["Text"] = [[0]];
G2L["108"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.Cursor
G2L["109"] = Instance.new("ImageLabel", G2L["1"]);
G2L["109"]["ZIndex"] = 999999999;
G2L["109"]["BorderSizePixel"] = 0;
G2L["109"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["109"]["ScaleType"] = Enum.ScaleType.Fit;
G2L["109"]["ImageTransparency"] = 1;
G2L["109"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["109"]["Image"] = [[rbxassetid://76608391243528]];
G2L["109"]["Size"] = UDim2.new(0.03669, 0, 0.0688, 0);
G2L["109"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["109"]["BackgroundTransparency"] = 1;
G2L["109"]["Name"] = [[Cursor]];
G2L["109"]["Position"] = UDim2.new(0.10329, 0, 0.17529, 0);


-- StarterGui.DREADED_HUB.Cursor.CursorScript
G2L["10a"] = Instance.new("LocalScript", G2L["109"]);
G2L["10a"]["Name"] = [[CursorScript]];


-- StarterGui.DREADED_HUB.InventoryHitbox
G2L["10b"] = Instance.new("Frame", G2L["1"]);
G2L["10b"]["Visible"] = false;
G2L["10b"]["BorderSizePixel"] = 0;
G2L["10b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10b"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["10b"]["Size"] = UDim2.new(0.33172, 0, 0.35831, 0);
G2L["10b"]["Position"] = UDim2.new(6999, 1, 0, 1);
G2L["10b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10b"]["Name"] = [[InventoryHitbox]];
G2L["10b"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.HotbarHitbox
G2L["10c"] = Instance.new("Frame", G2L["1"]);
G2L["10c"]["Visible"] = false;
G2L["10c"]["BorderSizePixel"] = 0;
G2L["10c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10c"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["10c"]["Size"] = UDim2.new(0.33172, 0, 0.05881, 0);
G2L["10c"]["Position"] = UDim2.new(6999, 1, 0, 1);
G2L["10c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10c"]["Name"] = [[HotbarHitbox]];
G2L["10c"]["BackgroundTransparency"] = 1;


-- StarterGui.DREADED_HUB.WholeThang.ToggleScript
local function C_3()
local script = G2L["3"];
	local origin = {Size = UDim2.new(0.35, 0, 0.4, 0)}
	local goal = {Size = UDim2.new(0.11, 0, 0.13, 0)}
	local animTime = .085
	local animTime2 = animTime - .025
	local lastTap = 0
	local doubleTapTime = 0.5
	
	local savedPositions = {}
	
	local function tweenCanvasPosition(scrollingFrame, targetPos, duration)
		local start = scrollingFrame.CanvasPosition
		local value = Instance.new("NumberValue")
		value.Value = 0
		value.Parent = scrollingFrame
	
		local tween = game:GetService("TweenService"):Create(value, TweenInfo.new(duration, Enum.EasingStyle.Sine, Enum.EasingDirection.InOut), {Value = 1})
		tween:Play()
	
		local connection
		connection = value:GetPropertyChangedSignal("Value"):Connect(function()
			local alpha = value.Value
			local newPos = start:Lerp(targetPos, alpha)
			scrollingFrame.CanvasPosition = newPos
		end)
	
		tween.Completed:Connect(function()
			connection:Disconnect()
			value:Destroy()
		end)
	end
	
	function PopupGui()
		local player = game:GetService("Players").LocalPlayer
		local playerGui = script.Parent:FindFirstAncestorWhichIsA("PlayerGui")
		if playerGui then
			local dreadedHubs = playerGui:GetChildren()
			local count = 0
	
			for _, descendant in ipairs(dreadedHubs) do
				if descendant.Name == "DREADED_HUB" then
					count += 1
				end
			end
	
			if count == 1 then
				local sound = Instance.new("Sound")
				sound.Volume = .5
				sound.SoundId = "rbxassetid://535716488"
				sound.Name = "Sound"
				sound.Parent = player.Character
				if player.PlayerGui:FindFirstChild("DREADED_HUB") then
					sound:Play()
					task.delay(1, function()
						sound:Destroy()
					end)
				end
			end
		end
	
		if script.Parent.Visible == true then
			for _, scrollingFrame in ipairs(script.Parent:GetDescendants()) do
				if scrollingFrame:IsA("ScrollingFrame") then
					savedPositions[scrollingFrame:GetFullName()] = scrollingFrame.CanvasPosition
				end
			end
	
			game:GetService("TweenService"):Create(script.Parent, TweenInfo.new(animTime, Enum.EasingStyle.Sine, Enum.EasingDirection.Out, 0, false), goal):Play()
			task.delay(animTime2, function()
				script.Parent.Visible = false
			end)
		else
			script.Parent.Visible = true
			game:GetService("TweenService"):Create(script.Parent, TweenInfo.new(animTime, Enum.EasingStyle.Sine, Enum.EasingDirection.In, 0, false), origin):Play()
	
			for _, scrollingFrame in ipairs(script.Parent:GetDescendants()) do
				if scrollingFrame:IsA("ScrollingFrame") then
					local saved = savedPositions[scrollingFrame:GetFullName()]
					if saved then
						tweenCanvasPosition(scrollingFrame, saved, animTime)
					end
				end
			end
		end
	end
	
	game:GetService("UserInputService").InputBegan:Connect(function(input, gameProcessed)
		if input.KeyCode == Enum.KeyCode.LeftAlt and not gameProcessed then
			local currentTime = tick()
			if currentTime - lastTap <= doubleTapTime then
				PopupGui()
				lastTap = 0
			else
				lastTap = currentTime
			end
		end
	end)
	
end;
task.spawn(C_3);
-- StarterGui.DREADED_HUB.WholeThang.Draggot.UIDrag
local function C_d()
local script = G2L["d"];
	-- Made by Real_IceyDev (@lceyDex) --
	-- Simple UI dragger (PC Only/Any device that has a mouse) --
	
	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame.Parent, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Parent.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end;
task.spawn(C_d);
-- StarterGui.DREADED_HUB.WholeThang.ScrollBone.ButtonHandler
local function C_f()
local script = G2L["f"];
	local buttons = script.Parent:GetChildren()
	local isHovering = {}
	
	for _, b in ipairs(buttons) do
		if b:IsA("TextButton") then
			isHovering[b] = false
	
			b.MouseEnter:Connect(function()
				isHovering[b] = true
				local player = game:GetService("Players").LocalPlayer
				local sound = Instance.new("Sound")
				sound.Volume = 0.375
				sound.SoundId = "rbxassetid://421058925"
				sound.Name = "Sound"
				sound.Parent = player.Character
				if script.Parent.Parent.Tab.Text ~= "Dashboard" then
					sound:Play()
				end
				task.delay(1, function()
					sound:Destroy()
				end)
			end)
	
			b.MouseLeave:Connect(function()
				isHovering[b] = false
			end)
	
			b.MouseButton1Click:Connect(function()
				for _, descendant in pairs(script.Parent.Parent:GetDescendants()) do 
					if descendant:IsA("TextButton") then
						descendant.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
					end
				end
	
				local player = game:GetService("Players").LocalPlayer
				local clickSound = Instance.new("Sound")
				clickSound.Volume = 0.5
				clickSound.SoundId = "rbxassetid://535716488"
				clickSound.Name = "Sound"
				clickSound.Parent = player.Character
				clickSound:Play()
				task.delay(1, function()
					clickSound:Destroy()
				end)
	
				b.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
	
				script.Parent.Parent.Tab.Text = b.Name
				script.Parent.Parent.Meat.ScrollingFrame.CanvasPosition = Vector2.new(0, 0)
				script.Parent.Parent.Meat.ScrollingFrame.Holder.Players.Searchbar.Text = "Search..."
			end)
		end
	end
	
	while true do
		for _, b in ipairs(buttons) do
			if b:IsA("TextButton") then
				if isHovering[b] and b.BackgroundColor3 == Color3.fromRGB(0, 0, 0) then
					b.TextColor3 = Color3.new(0.294118, 0, 0)
				else
					b.TextColor3 = Color3.new(1, 0, 0)
				end
			end
		end
		task.wait()
	end
	
end;
task.spawn(C_f);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.ImageLabel.LocalScript
local function C_2f()
local script = G2L["2f"];
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	
	local imageLabel = script.Parent -- assuming this script is a child of the ImageLabel
	
	local userId = player.UserId
	local thumbType = Enum.ThumbnailType.HeadShot
	local thumbSize = Enum.ThumbnailSize.Size420x420
	
	local content, isReady = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)
	
	imageLabel.Image = content
	
end;
task.spawn(C_2f);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.WelcomeText.LocalScript
local function C_34()
local script = G2L["34"];
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	local name = player.Name
	local label = script.Parent
	
	label.TextWrapped = false
	label.TextScaled = false
	label.TextTruncate = Enum.TextTruncate.None
	
	local messages = {
		"Yo NAME, the rebellion starts now.",
		"NAME just dropped in like a boss.",
		"Brace yourselves, NAME has entered the chaos.",
		"Who the hell let NAME in?",
		"NAME’s here. Time to crank the volume.",
		"Lock up your lobbies, NAME’s online.",
		"NAME slid in with zero chill.",
		"Straight outta spawn, it's NAME.",
		"NAME just logged in. Game over.",
		"NAME ain't here to play nice.",
		"Make way. NAME’s riding the thunder.",
		"NAME woke up and chose violence.",
		"Welcome to the anarchy, NAME.",
		"NAME just joined. Hide your damn snacks.",
		"Bow down. NAME has arrived.",
		"NAME's in. Chaos level: Maximum.",
		"Initiate mayhem protocol. NAME’s active.",
		"NAME loaded in with extra spice.",
		"Welcome to the danger zone, NAME.",
		"NAME's here. Mood: unbothered, unhinged.",
		"NAME just landed. Vibe: apocalyptic.",
		"NAME = Maximum overdrive.",
		"Warning: NAME brings the fire.",
		"NAME came in like a wrecking ball.",
		"It’s NAME o’clock. Let’s break some shit.",
		"Sound the alarms. NAME’s back.",
		"NAME’s here. Time to defy physics.",
		"The legend has logged in: NAME.",
		"NAME: stronger than your Wi-Fi signal.",
		"NAME entered the chat with style.",
		"NAME doesn’t need tutorials.",
		"New patch: NAME.exe installed.",
		"Grab your helmets. NAME joined.",
		"NAME just pressed ‘Start’ with authority.",
		"NAME brings the main character energy.",
		"NAME just punk’d the server.",
		"Loading chaos... Done. Welcome NAME.",
		"NAME showed up like a glitch in the Matrix.",
		"Get in, loser. NAME’s driving.",
		"Game just got real. NAME joined.",
		"NAME's cooking. And it ain't food.",
		"This ain’t a drill. NAME has spawned.",
		"NAME’s the plot twist no one expected.",
		"NAME = DLC you can’t f**king afford.",
		"Press F to respect NAME's entrance.",
		"Guess who’s back? Yeah, it’s NAME.",
		"The prophecy foretold NAME’s arrival.",
		"NAME’s not late. Time bent to them.",
		"Hack the system. NAME’s the virus.",
		"NAME’s here. Brace your badass self.",
		"NAME is FUCKING DOMINATING!"
	}
	
	local typewriterSound = Instance.new("Sound")
	typewriterSound.SoundId = "rbxassetid://9120300060"
	typewriterSound.Parent = label
	
	local message = messages[math.random(1, #messages)]
	message = string.gsub(message, "NAME", name)
	
	local function adjustFontSize()
		local minFontSize = 10
		local maxFontSize = 100
		local optimalSize = minFontSize
	
		for size = minFontSize, maxFontSize do
			label.TextSize = size
			if label.TextBounds.X > label.AbsoluteSize.X then
				break
			end
			optimalSize = size
		end
	
		label.TextSize = optimalSize
	end
	
	
	local function adjustSoundProperties()
		local volume = math.clamp(typewriterSound.Volume + 0.025, 0.05, 0.25)
		typewriterSound.Volume = volume
	
		local pitch = math.random(95, 105) / 100
		typewriterSound.Pitch = pitch
	end
	
	local function typewriter(text, delay)
		local playerGui = script.Parent:FindFirstAncestorWhichIsA("PlayerGui")
		if playerGui then
			local dreadedHubs = playerGui:GetChildren()
			local count = 0
	
			for _, descendant in ipairs(dreadedHubs) do
				if descendant.Name == "DREADED_HUB" then
					count += 1
				end
			end
	
			if count == 1 then
				label.Text = ""
				for i = 1, #text do
					label.Text = string.sub(text, 1, i)
					adjustFontSize()
					adjustSoundProperties()
					typewriterSound:Play()
					task.wait(delay)
				end
			end
		end
	end
	
	typewriter(message, 0.035)
	
end;
task.spawn(C_34);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.ServerRegion.ServerRegionScript
local function C_39()
local script = G2L["39"];
	local regionBox = script.Parent
	local LocalizationService = game:GetService("LocalizationService")
	
	local localeMap = {
		["en-us"] = "USA",
		["en-gb"] = "UK",
		["fr-fr"] = "France",
		["de-de"] = "Germany",
		["es-es"] = "Spain",
		["pt-br"] = "Brazil",
		["ja-jp"] = "Japan",
		["ko-kr"] = "South Korea",
		["zh-cn"] = "China",
		["ru-ru"] = "Russia",
		["en-ca"] = "Canada",
		["en-au"] = "Australia"
	}
	
	local function updateServerRegion()
		local localeId = LocalizationService.RobloxLocaleId:lower()
		local regionName = localeMap[localeId]
	
		if regionName then
			regionBox.Text = "Server Region: " .. regionName
		else
			regionBox.Text = "Server Region: " .. localeId
		end
	end
	
	updateServerRegion()
	
end;
task.spawn(C_39);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.PlayerCount.PlayerCountScript
local function C_3e()
local script = G2L["3e"];
	local playerCountBox = script.Parent
	
	local function updatePlayerCount()
		playerCountBox.Text = "Players: " .. tostring(#game.Players:GetPlayers())
	end
	
	updatePlayerCount()
	
	game.Players.PlayerAdded:Connect(updatePlayerCount)
	game.Players.PlayerRemoving:Connect(updatePlayerCount)
	
end;
task.spawn(C_3e);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Dashboard.Time.TimeScript
local function C_43()
local script = G2L["43"];
	local textLabel = script.Parent
	
	while true do
		local currentTime = os.date("*t")
		local hours = currentTime.hour
		local minutes = currentTime.min
		local suffix = "AM"
	
		if hours >= 12 then
			suffix = "PM"
		end
	
		if hours == 0 then
			hours = 12
		elseif hours > 12 then
			hours = hours - 12
		end
	
		if minutes < 10 then
			minutes = "0" .. minutes
		end
	
		textLabel.Text = hours .. ":" .. minutes .. " " .. suffix
		wait(1)
	end
	
end;
task.spawn(C_43);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Infinite Jump.Jump_67fd97
local function C_4b()
local script = G2L["4b"];
	local p = game.Players.LocalPlayer
	while true do
		if script.Parent.Online.Text == "ON" then
			if p.Character then
				local h = p.Character:FindFirstChild("Humanoid")
				if h and h.Jump then
					h:ChangeState(Enum.HumanoidStateType.Jumping)
				end
			end
		end
		task.wait()
	end
end;
task.spawn(C_4b);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Click TP.LocalScript
local function C_50()
local script = G2L["50"];
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	local mouse = player:GetMouse()
	
	local function createTool()
		local tool = Instance.new("Tool")
		tool.RequiresHandle = false
		tool.Name = "Click TP"
		tool.CanBeDropped = false
		tool.Activated:Connect(function()
			local rootPart = player.Character and player.Character:FindFirstChild("HumanoidRootPart")
			if rootPart then
				local targetPosition = mouse.Hit.Position + Vector3.new(0, 2.5, 0)
				local currentLookVector = rootPart.CFrame.LookVector
				local newCFrame = CFrame.new(targetPosition, targetPosition + currentLookVector)
				rootPart.CFrame = newCFrame
				local sound = Instance.new("Sound")
				sound.Volume = 0.1
				sound.SoundId = "rbxassetid://7148585764"
				sound.Name = "Sound"
				sound.Parent = player.Character
				sound:Play()
				task.delay(1, function()
					sound:Destroy()
				end)
			end
		end)
		return tool
	end
	
	local function giveTool()
		if not player.Backpack:FindFirstChild("Click TP") and not player.Character:FindFirstChild("Click TP") then
			local tool = createTool()
			tool.Parent = player.Backpack
		end
	end
	
	local function removeTool()
		for _, tp in pairs(player.Backpack:GetChildren()) do
			if tp.Name == "Click TP" then
				tp:Destroy()
			end
		end
		local toolInChar = player.Character and player.Character:FindFirstChild("Click TP")
		if toolInChar then
			toolInChar:Destroy()
		end
	end
	
	script.Parent.MouseButton1Up:Connect(function()
		if script.Parent.Online.Text == "ON" then
			giveTool()
		else
			removeTool()
		end
	end)
	
	player.CharacterAdded:Connect(function()
		task.wait(1)
		if script.Parent.Online.Text == "ON" then
			giveTool()
		end
	end)
	
end;
task.spawn(C_50);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.ButtonHandler
local function C_53()
local script = G2L["53"];
	local buttons = script.Parent:GetChildren()
	local isHovering = {}
	
	local InvisCD = false
	local InvisCooldownTime = 0.75
	
	for _, b in ipairs(buttons) do
		if b:IsA("TextButton") then
			isHovering[b] = false
	
			b.MouseEnter:Connect(function()
				isHovering[b] = true
				local player = game:GetService("Players").LocalPlayer
				local sound = Instance.new("Sound")
				sound.Volume = 0.375
				sound.SoundId = "rbxassetid://421058925"
				sound.Name = "Sound"
				sound.Parent = player.Character
				if script.Parent.Parent.Parent.Parent.Parent.Tab.Text == script.Parent.Name then
					sound:Play()
				end
				task.delay(1, function()
					sound:Destroy()
				end)
			end)
	
			b.MouseLeave:Connect(function()
				isHovering[b] = false
			end)
	
			b.MouseButton1Click:Connect(function()
				if b.Name == "Invisible" then
					if InvisCD == false then
						InvisCD = true
						task.delay(InvisCooldownTime, function()
							InvisCD = false
						end)
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 0.5
						clickSound.SoundId = "rbxassetid://535716488"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
						if b:FindFirstChild("Online").Text == "OFF" then
							b:FindFirstChild("Online").Text = "ON"
						else
							b:FindFirstChild("Online").Text = "OFF"
						end
					else
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 1
						clickSound.SoundId = "rbxassetid://550209561"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
					end
				elseif b.Name == "Fling" then
					if script.Parent.Parent.FlingActive.Text == "ON" then
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 1
						clickSound.SoundId = "rbxassetid://550209561"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
					else
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 0.5
						clickSound.SoundId = "rbxassetid://535716488"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
						if b:FindFirstChild("Online").Text == "OFF" then
							b:FindFirstChild("Online").Text = "ON"
						else
							b:FindFirstChild("Online").Text = "OFF"
						end
					end
				else
					local player = game:GetService("Players").LocalPlayer
					local clickSound = Instance.new("Sound")
					clickSound.Volume = 0.5
					clickSound.SoundId = "rbxassetid://535716488"
					clickSound.Name = "Sound"
					clickSound.Parent = player.Character
					clickSound:Play()
					task.delay(1, function()
						clickSound:Destroy()
					end)
					if b:FindFirstChild("Online").Text == "OFF" then
						b:FindFirstChild("Online").Text = "ON"
					else
						b:FindFirstChild("Online").Text = "OFF"
					end
				end
			end)
		end
	end
	
	while true do
		for _, b in ipairs(buttons) do
			if b:IsA("TextButton") then
				if isHovering[b] and b:FindFirstChild("Online").Text == "OFF" then
					b.TextColor3 = Color3.new(0.294118, 0, 0)
				elseif isHovering[b] and b:FindFirstChild("Online").Text == "ON" then
					b.TextColor3 = Color3.new(0.196078, 0.196078, 0.215686)
				elseif isHovering[b] == false and b:FindFirstChild("Online").Text == "ON" then
					b.TextColor3 = Color3.new(0.294118, 0.294118, 0.294118)
				else
					b.TextColor3 = Color3.new(1, 0, 0)
				end
			end
		end
		task.wait()
	end
end;
task.spawn(C_53);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.TextBox.TextBoxScript
local function C_5c()
local script = G2L["5c"];
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local player = Players.LocalPlayer
	local textBox = script.Parent
	local ValueBox = script.Parent.Value
	local dreadedHub = script:FindFirstAncestor("DREADED_HUB")
	
	local function roundWhole(n)
		return math.floor(n + 0.5)
	end
	
	local defaultGravity = roundWhole(workspace.Gravity)
	
	local playerGui = script.Parent:FindFirstAncestorWhichIsA("PlayerGui")
	if playerGui then
		local dreadedHubs = playerGui:GetChildren()
		local count = 0
	
		for _, descendant in ipairs(dreadedHubs) do
			if descendant.Name == "DREADED_HUB" then
				count += 1
			end
		end
	
		if count == 1 then
			if script.Gravity.Text == "" then
				script.Gravity.Text = defaultGravity
			end
		end
	end
	
	local humanoid
	local connection
	local tagConnection
	
	local function hasKillingTag()
		return dreadedHub and dreadedHub:FindFirstChild("KILLING...")
	end
	
	local function enforceDefaultGravity()
		workspace.Gravity = defaultGravity
		textBox.Text = tostring(defaultGravity)
		stopUpdatingGravity()
	end
	
	local function startUpdatingGravity()
		if connection then connection:Disconnect() end
		connection = RunService.RenderStepped:Connect(function()
			if hasKillingTag() then
				enforceDefaultGravity()
				return
			end
			local value = tonumber(textBox.Text)
			if value and humanoid and humanoid.Parent then
				workspace.Gravity = roundWhole(value)
			end
		end)
	end
	
	function stopUpdatingGravity()
		if connection then
			connection:Disconnect()
			connection = nil
			script.Enabled = false
		end
	end
	
	local function setupCharacter(character)
		humanoid = character:WaitForChild("Humanoid")
		textBox.Text = tostring(defaultGravity)
		ValueBox.Text = tostring(defaultGravity)
		if hasKillingTag() then
			enforceDefaultGravity()
		else
			stopUpdatingGravity()
		end
	end
	
	textBox:GetPropertyChangedSignal("Text"):Connect(function()
		if hasKillingTag() then
			textBox.Text = tostring(defaultGravity)
			return
		end
		local filtered = textBox.Text:gsub("%D", "")
		if #filtered > 3 then
			filtered = string.sub(filtered, 1, 3)
		end
		if textBox.Text ~= filtered then
			textBox.Text = filtered
		end
	end)
	
	textBox.FocusLost:Connect(function()
		if hasKillingTag() then
			enforceDefaultGravity()
			return
		end
		local value = tonumber(textBox.Text)
		if value then
			workspace.Gravity = roundWhole(value)
			startUpdatingGravity()
		else
			workspace.Gravity = tonumber(ValueBox.Text)
			textBox.Text = tostring(ValueBox.Text)
			stopUpdatingGravity()
		end
	end)
	
	local character = player.Character or player.CharacterAdded:Wait()
	setupCharacter(character)
	
	player.CharacterAdded:Connect(setupCharacter)
	
	if dreadedHub then
		tagConnection = dreadedHub.ChildAdded:Connect(function(child)
			if child.Name == "KILLING..." then
				enforceDefaultGravity()
			end
		end)
	end
	
end;
task.spawn(C_5c);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Jump Height.TextBox.TextBoxScript
local function C_68()
local script = G2L["68"];
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local player = Players.LocalPlayer
	local textBox = script.Parent
	local ValueBox = script.Parent.Value
	
	local function roundWhole(n)
		return math.floor(n + 0.5)
	end
	
	local defaultJumpValue
	local humanoid
	local connection
	local updatingJumpValue = false
	local savedJumpValue = nil
	local useJumpPower = false
	
	local function startUpdatingJumpValue()
		if connection then connection:Disconnect() end
		connection = RunService.RenderStepped:Connect(function()
			local value = tonumber(textBox.Text)
			if value and humanoid and humanoid.Parent then
				if useJumpPower then
					script.Parent.Parent.Text = "Jump Power:"
					humanoid.JumpPower = roundWhole(value)
				else
					script.Parent.Parent.Text = "Jump Height:"
					humanoid.JumpHeight = roundWhole(value)
				end
			end
		end)
		updatingJumpValue = true
	end
	
	local function stopUpdatingJumpValue()
		if connection then
			connection:Disconnect()
			connection = nil
			script.Enabled = false
		end
		updatingJumpValue = false
	end
	
	local function setupCharacter(character)
		humanoid = character:WaitForChild("Humanoid")
		if humanoid.UseJumpPower ~= nil then
			useJumpPower = humanoid.UseJumpPower
		else
			useJumpPower = false
		end
		if useJumpPower then
			script.Parent.Parent.Text = "Jump Power:"
			defaultJumpValue = roundWhole(humanoid.JumpPower)
		else
			script.Parent.Parent.Text = "Jump Height:"
			defaultJumpValue = roundWhole(humanoid.JumpHeight)
		end
		if ValueBox.Text == "" then
			ValueBox.Text = defaultJumpValue
		end
		textBox.Text = tostring(savedJumpValue or defaultJumpValue)
		stopUpdatingJumpValue()
	
		if savedJumpValue then
			if useJumpPower then
				script.Parent.Parent.Text = "Jump Power:"
				humanoid.JumpPower = savedJumpValue
			else
				script.Parent.Parent.Text = "Jump Height:"
				humanoid.JumpHeight = savedJumpValue
			end
		end
	end
	
	textBox:GetPropertyChangedSignal("Text"):Connect(function()
		local filtered = textBox.Text:gsub("%D", "")
		if #filtered > 3 then
			filtered = string.sub(filtered, 1, 3)
		end
		if textBox.Text ~= filtered then
			textBox.Text = filtered
		end
	end)
	
	textBox.FocusLost:Connect(function()
		local value = tonumber(textBox.Text)
		if value and humanoid then
			if useJumpPower then
				script.Parent.Parent.Text = "Jump Power:"
				humanoid.JumpPower = roundWhole(value)
			else
				script.Parent.Parent.Text = "Jump Height:"
				humanoid.JumpHeight = roundWhole(value)
			end
			savedJumpValue = roundWhole(value)
			startUpdatingJumpValue()
		else
			if humanoid then
				if useJumpPower then
					script.Parent.Parent.Text = "Jump Power:"
					humanoid.JumpPower = ValueBox.Text
				else
					script.Parent.Parent.Text = "Jump Height:"
					humanoid.JumpHeight = ValueBox.Text
				end
				textBox.Text = tostring(ValueBox.Text)
			end
			stopUpdatingJumpValue()
		end
	end)
	
	local character = player.Character or player.CharacterAdded:Wait()
	if not script:FindFirstAncestor("DREADED_HUB"):FindFirstChild("KILLING...") then
		setupCharacter(character)
	end
	
	player.CharacterAdded:Connect(function(char)
		if not script:FindFirstAncestor("DREADED_HUB"):FindFirstChild("KILLING...") then
			setupCharacter(char)
		end
	end)
	
end;
task.spawn(C_68);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Walkspeed.TextBox.TextBoxScript
local function C_73()
local script = G2L["73"];
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local player = Players.LocalPlayer
	local textBox = script.Parent
	local ValueBox = script.Parent.Value
	
	local defaultSpeed
	local humanoid
	local connection
	local updatingSpeed = false
	local savedSpeed = nil  -- Store the custom speed set by the player
	
	local function startUpdatingSpeed()
		if connection then connection:Disconnect() end
		connection = RunService.RenderStepped:Connect(function()
			local value = tonumber(textBox.Text)
			if value and humanoid and humanoid.Parent then
				humanoid.WalkSpeed = value
			end
		end)
		updatingSpeed = true
	end
	
	local function stopUpdatingSpeed()
		if connection then
			connection:Disconnect()
			connection = nil
			script.Enabled = false
		end
		updatingSpeed = false
	end
	
	local function setupCharacter(character)
		humanoid = character:WaitForChild("Humanoid")
		defaultSpeed = humanoid.WalkSpeed
		if ValueBox.Text == "" then
			ValueBox.Text = defaultSpeed
		end
		textBox.Text = tostring(savedSpeed or defaultSpeed)
		stopUpdatingSpeed()
	
		-- Apply saved speed after respawn
		if savedSpeed then
			humanoid.WalkSpeed = savedSpeed
		end
	end
	
	textBox:GetPropertyChangedSignal("Text"):Connect(function()
		local filtered = textBox.Text:gsub("%D", "")
		if #filtered > 3 then
			filtered = string.sub(filtered, 1, 3)
		end
		if textBox.Text ~= filtered then
			textBox.Text = filtered
		end
	
		if not updatingSpeed and filtered ~= "" then
			startUpdatingSpeed()
		end
	end)
	
	textBox.FocusLost:Connect(function()
		if textBox.Text == "" and humanoid then
			humanoid.WalkSpeed = ValueBox.Text
			textBox.Text = tostring(ValueBox.Text)
			stopUpdatingSpeed()
		elseif textBox.Text ~= "" then
			savedSpeed = tonumber(textBox.Text)
		end
	end)
	
	local character = player.Character or player.CharacterAdded:Wait()
	if not script:FindFirstAncestor("DREADED_HUB"):FindFirstChild("KILLING...") then
		setupCharacter(character)
	end
	
	player.CharacterAdded:Connect(function(char)
		if not script:FindFirstAncestor("DREADED_HUB"):FindFirstChild("KILLING...") then
			setupCharacter(char)
		end
	end)
	
end;
task.spawn(C_73);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Flight.TextBoxScript
local function C_7e()
local script = G2L["7e"];
	local KEYBIND = "F"
	
	local userInput = game:GetService("UserInputService")
	local player = game.Players.LocalPlayer
	local cam = workspace.CurrentCamera
	local button = script.Parent
	local speedBox = script.Parent.Speed
	local onlineText = script.Parent:WaitForChild("Online")
	
	local flyingConnection
	local bodyVelocity
	local bodyGyro
	local isFlying = false
	local keysDown = {}
	
	local function getNextMovement()
		local move = Vector3.new()
	
		if keysDown[Enum.KeyCode.W] then
			move += Vector3.new(0, 0, -1)
		end
		if keysDown[Enum.KeyCode.S] then
			move += Vector3.new(0, 0, 1)
		end
		if keysDown[Enum.KeyCode.A] then
			move += Vector3.new(-1, 0, 0)
		end
		if keysDown[Enum.KeyCode.D] then
			move += Vector3.new(1, 0, 0)
		end
		if keysDown[Enum.KeyCode.Space] then
			move += Vector3.new(0, 1, 0)
		end
		if keysDown[Enum.KeyCode.LeftControl] then
			move += Vector3.new(0, -1, 0)
		end
	
		local input = tonumber(speedBox.Text)
		local speed = (input and input / 10) or 1
		return move.Magnitude > 0 and move.Unit * speed or Vector3.zero
	end
	
	local function startFlying()
		local character = player.Character or player.CharacterAdded:Wait()
		local humanoid = character:WaitForChild("Humanoid")
		local rootPart = character:WaitForChild("HumanoidRootPart")
		local parts = character:GetChildren()
	
		-- Set up flying (weightlessness)
		humanoid.PlatformStand = true
		humanoid:ChangeState(Enum.HumanoidStateType.Physics)  -- Prevent falling animation
	
		-- Disable collision and gravity by making all parts noclip
		for _, part in ipairs(parts) do
			if part:IsA("BasePart") then
				part.CanCollide = false
			end
		end
	
		-- Create BodyVelocity and BodyGyro to control movement
		bodyVelocity = Instance.new("BodyVelocity")
		bodyVelocity.Name = "FlyVelocity"
		bodyVelocity.MaxForce = Vector3.new(1e9, 1e9, 1e9)
		bodyVelocity.Velocity = Vector3.zero
		bodyVelocity.Parent = rootPart
	
		bodyGyro = Instance.new("BodyGyro")
		bodyGyro.MaxTorque = Vector3.new(400000, 400000, 400000)
		bodyGyro.CFrame = rootPart.CFrame
		bodyGyro.Parent = rootPart
	
		isFlying = true
	
		local animate = character:FindFirstChild("Animate")
		if animate then
			animate.Enabled = false
	
			for _, playingTracks in pairs(humanoid:GetPlayingAnimationTracks()) do
				playingTracks:Stop()
			end
		end
	
		flyingConnection = game:GetService("RunService").Heartbeat:Connect(function()
			if not isFlying then return end
	
			local moveDirection = getNextMovement()
			if moveDirection.Magnitude ~= moveDirection.Magnitude then
				moveDirection = Vector3.zero
			end
	
			local look = (cam.Focus.Position - cam.CFrame.Position).Unit
			local cameraCFrame = CFrame.new(Vector3.zero, look)
			local worldDirection = cameraCFrame:VectorToWorldSpace(moveDirection)
	
			if bodyVelocity then
				bodyVelocity.Velocity = worldDirection * 50
			end
	
			if bodyGyro then
				bodyGyro.CFrame = CFrame.new(rootPart.Position, rootPart.Position + look)
			end
		end)
	end
	
	local function stopFlying()
		isFlying = false
	
		if flyingConnection then
			flyingConnection:Disconnect()
			flyingConnection = nil
		end
	
		local character = player.Character
		local humanoid = character:FindFirstChild("Humanoid")
		local rootPart = character:FindFirstChild("HumanoidRootPart")
	
		if character then
	
			local animate = character:FindFirstChild("Animate")
			if animate then
				animate.Enabled = true
	
				for _, playingTracks in pairs(humanoid:GetPlayingAnimationTracks()) do
					playingTracks:Stop()
				end
			end
	
			local parts = character:GetChildren()
			if humanoid and rootPart then
				humanoid.PlatformStand = false
				humanoid:ChangeState(Enum.HumanoidStateType.GettingUp)  -- Reset state to "getting up" to fix falling animation
	
				-- Reset all parts to normal state
				for _, part in ipairs(parts) do
					if part:IsA("BasePart") then
						part.CanCollide = true
					end
				end
	
				-- Remove velocity and gyro
				if bodyVelocity then
					bodyVelocity:Destroy()
					bodyVelocity = nil
				end
				if bodyGyro then
					bodyGyro:Destroy()
					bodyGyro = nil
				end
	
				rootPart.Velocity = Vector3.zero
				rootPart.RotVelocity = Vector3.zero
			end
		end
	end
	
	local function onFPressed()
		local playerGui = script.Parent:FindFirstAncestorWhichIsA("PlayerGui")
		if playerGui then
			local dreadedHubs = playerGui:GetChildren()
			local count = 0
	
			for _, descendant in ipairs(dreadedHubs) do
				if descendant.Name == "DREADED_HUB" then
					count += 1
				end
			end
	
			if count == 1 then
				local clickSound = Instance.new("Sound")
				clickSound.Volume = 0.5
				clickSound.SoundId = "rbxassetid://535716488"
				clickSound.Name = "Sound"
				clickSound.Parent = player.Character
				if player.PlayerGui:FindFirstChild("DREADED_HUB") then
					clickSound:Play()
					task.delay(1, function()
						clickSound:Destroy()
					end)
				end
			end
		end
	
		if onlineText.Text == "OFF" then
			onlineText.Text = "ON"
		else
			onlineText.Text = "OFF"
		end
	end
	
	onlineText:GetPropertyChangedSignal("Text"):Connect(function()
		if onlineText.Text == "ON" and not script:FindFirstAncestor("DREADED_HUB"):FindFirstChild("KILLING...") then
			startFlying()
		else
			stopFlying()
		end
	end)
	
	player.CharacterAdded:Connect(function(character)
		isFlying = false
		stopFlying()
		onlineText.Text = "OFF"
		
		if onlineText.Text == "ON" and not script:FindFirstAncestor("DREADED_HUB"):FindFirstChild("KILLING...") then
			--startFlying()
		end
	end)
	
	userInput.InputBegan:Connect(function(input, gameProcessed)
		if gameProcessed then return end
		if input.KeyCode == Enum.KeyCode[KEYBIND] then
			onFPressed()
		end
		keysDown[input.KeyCode] = true
	end)
	
	userInput.InputEnded:Connect(function(input)
		keysDown[input.KeyCode] = false
	end)
end;
task.spawn(C_7e);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fly Speed.TextBox.TextBoxScript
local function C_87()
local script = G2L["87"];
	local RunService = game:GetService("RunService")
	local textBox = script.Parent
	local speedText = script.Parent.Parent.Parent:WaitForChild("Flight"):WaitForChild("Speed")
	
	local function roundWhole(n)
		return math.floor(n + 0.5)
	end
	
	local defaultSpeed = roundWhole(tonumber(speedText.Text) or 50)
	local currentSpeed = defaultSpeed
	textBox.Text = tostring(currentSpeed)
	
	local connection
	local updatingSpeed = false
	
	local function startUpdatingSpeed()
		if connection then connection:Disconnect() end
		connection = RunService.RenderStepped:Connect(function()
			local value = tonumber(textBox.Text)
			if value then
				local rounded = roundWhole(value)
				speedText.Text = tostring(rounded)
				currentSpeed = rounded
			end
		end)
		updatingSpeed = true
	end
	
	local function stopUpdatingSpeed()
		if connection then
			connection:Disconnect()
			connection = nil
			script.Enabled = false
		end
		updatingSpeed = false
	end
	
	textBox:GetPropertyChangedSignal("Text"):Connect(function()
		local filtered = textBox.Text:gsub("%D", "")
		if #filtered > 3 then
			filtered = string.sub(filtered, 1, 3)
		end
		if textBox.Text ~= filtered then
			textBox.Text = filtered
		end
	
		if not updatingSpeed and filtered ~= "" then
			startUpdatingSpeed()
		end
	end)
	
	textBox.FocusLost:Connect(function()
		if textBox.Text == "" then
			textBox.Text = tostring(defaultSpeed)
			speedText.Text = tostring(defaultSpeed)
			stopUpdatingSpeed()
			return
		end
	
		local newSpeed = tonumber(textBox.Text)
		if newSpeed then
			local rounded = roundWhole(newSpeed)
			speedText.Text = tostring(rounded)
			currentSpeed = rounded
			textBox.Text = tostring(rounded)
		else
			textBox.Text = tostring(defaultSpeed)
			speedText.Text = tostring(defaultSpeed)
		end
	end)
	
end;
task.spawn(C_87);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.TextBoxHandler
local function C_88()
local script = G2L["88"];
	while true do
		for _, TextBoxScript in pairs(script.Parent:GetDescendants()) do
			if TextBoxScript.Name == "TextBoxScript" and TextBoxScript.Enabled == false then
				TextBoxScript.Enabled = true
			end
		end
		task.wait()
	end
end;
task.spawn(C_88);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Refresh.LocalScript
local function C_8f()
local script = G2L["8f"];
	local button = script.Parent
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	
	button.MouseButton1Click:Connect(function()
		local character = player.Character
		if character and character:FindFirstChild("HumanoidRootPart") then
			local hrpPosition = character.HumanoidRootPart.Position
	
			local spawnConnection
			spawnConnection = player.CharacterAdded:Connect(function(newChar)
				newChar:WaitForChild("HumanoidRootPart").CFrame = CFrame.new(hrpPosition)
				spawnConnection:Disconnect()
			end)
	
			character:BreakJoints()
			task.delay(.05, function()
				script.Parent.Online.Text = "OFF"
			end)
		end
	end)
end;
task.spawn(C_8f);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Invisible.LocalScript
local function C_96()
local script = G2L["96"];
	local invis_on = false
	local RunService = game:GetService("RunService")
	local UserInputService = game:GetService("UserInputService")
	local Camera = workspace.CurrentCamera
	
	
	local function createBillboardGui()
		local gui = Instance.new("BillboardGui")
		gui.Name = "InvisibilityIndicator"
		gui.Size = UDim2.new(3, 0, 1.75, 0)
		gui.StudsOffset = Vector3.new(0, 2, 0)
		gui.AlwaysOnTop = true
		gui.MaxDistance = math.huge
	
		local textLabel = Instance.new("TextLabel")
		textLabel.Size = UDim2.new(1, 0, 1, 0)
		textLabel.BackgroundTransparency = 1
		textLabel.Text = "INVISIBLE"
		textLabel.TextColor3 = Color3.fromRGB(255, 0, 0)
		textLabel.TextStrokeTransparency = 0
		textLabel.TextStrokeColor3 = Color3.new(0, 0, 0)
		textLabel.FontFace = Font.new([[rbxassetid://12187365104]], Enum.FontWeight.Regular, Enum.FontStyle.Normal)
		textLabel.TextScaled = true
		textLabel.Parent = gui
	
		local textStroke = Instance.new("UIStroke")
		textStroke.Thickness = 3
		textStroke.Parent = textLabel
	
		local gradient = Instance.new("UIGradient")
		gradient.Color = ColorSequence.new({
			ColorSequenceKeypoint.new(0, Color3.new(1, 1, 1)),
			ColorSequenceKeypoint.new(1, Color3.new(0, 0, 0))
		})
		gradient.Rotation = 90
		gradient.Parent = textLabel
	
		return gui
	end
	
	local function removeBillboard(character)
		local head = character:FindFirstChild("Head")
		if head and head:FindFirstChild("InvisibilityIndicator") then
			head:FindFirstChild("InvisibilityIndicator"):Destroy()
		end
	end
	
	local function addBillboard(character)
		removeBillboard(character)
		local head = character:FindFirstChild("Head")
		if head then
			createBillboardGui().Parent = head
		end
	end
	
	local rotateConnection
	
	local function startFacingCamera(character)
		local hrp = character:FindFirstChild("HumanoidRootPart")
		if not hrp then return end
	
		rotateConnection = RunService.RenderStepped:Connect(function()
			if not invis_on or not character or not character.Parent then
				if rotateConnection then
					rotateConnection:Disconnect()
					rotateConnection = nil
				end
				return
			end
	
			local isShiftLock = UserInputService.MouseBehavior == Enum.MouseBehavior.LockCenter
				and Camera.CameraSubject == character:FindFirstChild("Humanoid")
				and Camera.CameraType == Enum.CameraType.Custom
	
			if isShiftLock then
				local camDirection = Camera.CFrame.LookVector
				local flatDirection = Vector3.new(-camDirection.X, 0, -camDirection.Z).Unit
				local position = hrp.Position
				hrp.CFrame = CFrame.new(position) * CFrame.Angles(0, math.atan2(flatDirection.X, flatDirection.Z), 0)
			end
		end)
	end
	
	local function stopFacingCamera()
		if rotateConnection then
			rotateConnection:Disconnect()
			rotateConnection = nil
		end
	end
	
	local function toggleInvisibility()
		local character = game.Players.LocalPlayer.Character
		if not character then return end
	
		if invis_on then
			local savedpos = character.HumanoidRootPart.CFrame
			task.wait()
			character:MoveTo(Vector3.new(-25.95, 84, 3537.55))
			task.wait(0.15)
			local Seat = Instance.new('Seat', game.Workspace)
			Seat.Anchored = false
			Seat.CanCollide = false
			Seat.Name = 'invischair'
			Seat.Transparency = 1
			Seat.Position = Vector3.new(-25.95, 84, 3537.55)
			local Weld = Instance.new("Weld", Seat)
			Weld.Part0 = Seat
			Weld.Part1 = character:FindFirstChild("Torso") or character:FindFirstChild("UpperTorso")
			task.wait()
			Seat.CFrame = savedpos
			addBillboard(character)
			startFacingCamera(character)
		else
			stopFacingCamera()
			if workspace:FindFirstChild('invischair') then
				workspace:FindFirstChild('invischair'):Destroy()
			end
			removeBillboard(character)
		end
	end
	
	script.Parent.Online:GetPropertyChangedSignal("Text"):Connect(function()
		if script.Parent.Online.Text == "ON" then
			invis_on = true
			toggleInvisibility()
		elseif script.Parent.Online.Text == "OFF" then
			invis_on = false
			toggleInvisibility()
		end
	end)
	
	local function onCharacterAdded(character)
		if invis_on then
			addBillboard(character)
			startFacingCamera(character)
		end
	
		local humanoid = character:WaitForChild("Humanoid")
		humanoid.Died:Connect(function()
			invis_on = false
			script.Parent.Online.Text = "OFF"
			removeBillboard(character)
			stopFacingCamera()
			if workspace:FindFirstChild("invischair") then
				workspace:FindFirstChild("invischair"):Destroy()
			end
		end)
	end
	
	if game.Players.LocalPlayer.Character then
		onCharacterAdded(game.Players.LocalPlayer.Character)
	end
	
	game.Players.LocalPlayer.CharacterAdded:Connect(onCharacterAdded)
	
end;
task.spawn(C_96);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Noclip.TextBoxScript
local function C_9d()
local script = G2L["9d"];
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	local player = Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local originalCollisionStates = {}
	local onlineButton = script.Parent:WaitForChild("Online")
	
	local function updateCharacterReference()
		character = player.Character or player.CharacterAdded:Wait()
		originalCollisionStates = {}
	
		for _, part in ipairs(character:GetDescendants()) do
			if part:IsA("BasePart") then
				originalCollisionStates[part] = part.CanCollide
			end
		end
	end
	
	local function setCollision(state)
		for part, original in pairs(originalCollisionStates) do
			if part and part:IsDescendantOf(character) then
				part.CanCollide = state and original or false
			end
		end
	end
	
	local function startCollisionLoop()
		RunService.Stepped:Connect(function()
			if onlineButton then
				if onlineButton.Text == "ON" then
					setCollision(false)
				else
					setCollision(true)
				end
			end
		end)
	end
	
	local function handleCharacterAdded()
		updateCharacterReference()
		startCollisionLoop()
	end
	
	player.CharacterAdded:Connect(function()
		task.wait(1)
		handleCharacterAdded()
	end)
	
	handleCharacterAdded()
	
	local function checkAndToggleScript()
		while true do
			task.wait()
			if not script.Enabled then
				script.Enabled = true
			end
		end
	end
	
	spawn(checkAndToggleScript)
	
end;
task.spawn(C_9d);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Dashing.Dash
local function C_a4()
local script = G2L["a4"];
	local KEYBIND = "Q"
	
	local canDash = true
	local cooldown = 0.5
	
	local userInput = game:GetService("UserInputService")
	local player = game.Players.LocalPlayer
	
	local dashTime = 0.1
	
	local moveDirection = Vector3.zero
	
	userInput.InputBegan:Connect(function(input, gameProcessed)
		if gameProcessed then return end
		if input.KeyCode == Enum.KeyCode[KEYBIND] then
	
			local char = player.Character
			local humanoid = char:FindFirstChildOfClass("Humanoid")
			local rootPart = char:FindFirstChild("HumanoidRootPart")
	
			if not humanoid or not rootPart then return end
	
			local state = humanoid:GetState()
	
			if canDash and state ~= Enum.HumanoidStateType.Jumping and script.Parent.Online.Text == "ON" then
				canDash = false
	
				local Sound = Instance.new("Sound")
				Sound.Volume = 0.5
				Sound.SoundId = "rbxassetid://5989939664"
				Sound.Name = "Sound"
				Sound.Parent = player.Character
				Sound:Play()
				task.delay(1, function()
					Sound:Destroy()
				end)
	
				local lookVector = rootPart.CFrame.LookVector
				if userInput.MouseBehavior == Enum.MouseBehavior.LockCenter then
					moveDirection = humanoid.MoveDirection
					if moveDirection.Magnitude > 0 then
						lookVector = moveDirection.Unit
					end
				end
	
				local dash = Instance.new("BodyVelocity")
				dash.MaxForce = Vector3.new(1, 0, 1) * 30000
				dash.Velocity = lookVector * 125
				dash.Parent = rootPart
	
				task.wait(dashTime)
	
				for _ = 1, 8 do
					task.delay(0.1, function()
						dash.Velocity *= 0.25
					end)
				end
	
				dash:Destroy()
	
				task.wait(cooldown)
	
				canDash = true
			end
		end
	end)
	
end;
task.spawn(C_a4);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Player.Fling.LocalScript
local function C_ab()
local script = G2L["ab"];
	local function IIMAWH_fake_script()
		local script = Instance.new('LocalScript', script.Parent)
	
		local ReplicatedStorage = game:GetService("ReplicatedStorage")
		local RunService = game:GetService("RunService")
		local Players = game:GetService("Players")
	
		local toggleButton = script.Parent
		local hiddenfling = false
		local flingThread
		local gui = script:FindFirstAncestorOfClass("ScreenGui")
	
		if not ReplicatedStorage:FindFirstChild("JP_ON_TOP") then
			local detection = Instance.new("Decal")
			detection.Name = "JP_ON_TOP"
			detection.Parent = ReplicatedStorage
		end
	
		local function fling()
			local lp = Players.LocalPlayer
			local c, hrp, vel, movel = nil, nil, nil, 0.1
	
			while hiddenfling do
				if gui and gui:FindFirstChild("KILLING...") then
					hiddenfling = false
					break
				end
	
				RunService.Heartbeat:Wait()
				c = lp.Character
				hrp = c and c:FindFirstChild("HumanoidRootPart")
	
				if hrp then
					vel = hrp.Velocity
					hrp.Velocity = vel * 10000 + Vector3.new(0, 10000, 0)
					RunService.RenderStepped:Wait()
					hrp.Velocity = vel
					RunService.Stepped:Wait()
					hrp.Velocity = vel + Vector3.new(0, movel, 0)
					movel = -movel
				end
			end
		end
	
		toggleButton.MouseButton1Click:Connect(function()
			local flag = script.Parent.Parent.Parent.FlingActive
			if flag and flag.Text == "ON" then
				return
			end
	
			if gui and gui:FindFirstChild("KILLING...") then
				hiddenfling = false
				return
			end
	
			hiddenfling = not hiddenfling
	
			if hiddenfling then
				flingThread = coroutine.create(fling)
				coroutine.resume(flingThread)
			end
		end)
	end
	
	coroutine.wrap(IIMAWH_fake_script)()
end;
task.spawn(C_ab);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.LocalScript
local function C_b2()
local script = G2L["b2"];
	local Players = game:GetService("Players")
	local Teams = game:GetService("Teams")
	local DemoTemplate = script.Parent.Demo
	local ParentFrame = script.Parent
	local TextBox = script.Parent.Searchbar
	
	local localPlayer = Players.LocalPlayer
	
	local function getTeamColor(player)
		if player and player.Team and player.Team.TeamColor then
			local teamColor = player.Team.TeamColor.Color
			if teamColor ~= BrickColor.White().Color then
				return teamColor
			end
		end
		return Color3.fromRGB(255, 0, 0)
	end
	
	local function getSortedPlayers()
		local playerList = Players:GetPlayers()
	
		local function isRealTeam(player)
			return player.Team and player.Team.TeamColor.Color ~= BrickColor.White().Color
		end
	
		table.sort(playerList, function(a, b)
			if a == localPlayer then
				return true
			elseif b == localPlayer then
				return false
			end
	
			local aHasRealTeam = isRealTeam(a)
			local bHasRealTeam = isRealTeam(b)
	
			if aHasRealTeam ~= bHasRealTeam then
				return aHasRealTeam
			end
	
			local aSameTeam = aHasRealTeam and a.Team == localPlayer.Team
			local bSameTeam = bHasRealTeam and b.Team == localPlayer.Team
	
			if aSameTeam ~= bSameTeam then
				return aSameTeam
			end
	
			if aHasRealTeam and bHasRealTeam and a.Team.Name ~= b.Team.Name then
				return a.Team.Name < b.Team.Name
			end
	
			return a.Name:lower() < b.Name:lower()
		end)
	
		return playerList
	end
	
	local function updatePlayerList(searchText)
		searchText = string.lower(searchText)
		for _, child in ipairs(ParentFrame:GetChildren()) do
			if child:IsA("Frame") and child ~= DemoTemplate and child ~= TextBox then
				local username = string.lower(child.Name)
				local displayNameValue = child:FindFirstChild("DisplayName")
				local displayName = displayNameValue and string.lower(displayNameValue.Value) or ""
	
				if searchText == "" or searchText == "search..." or username:find(searchText, 1, true) or displayName:find(searchText, 1, true) then
					child.Visible = true
				else
					child.Visible = false
				end
			end
		end
	end
	
	local function refreshPlayers()
		for _, child in pairs(ParentFrame:GetChildren()) do
			if child:IsA("Frame") and child ~= DemoTemplate and child ~= TextBox then
				child:Destroy()
			end
		end
	
		local sortedPlayers = getSortedPlayers()
	
		for _, player in ipairs(sortedPlayers) do
			local demo = DemoTemplate:Clone()
			demo.Parent = ParentFrame
			demo.Name = player.Name
			demo.Visible = true
			demo.Active = true
			demo.ZIndex = 1
			demo.Username.Text = "@" .. player.Name
			demo.Username.TextColor3 = getTeamColor(player)
	
			local displayNameValue = Instance.new("StringValue")
			displayNameValue.Name = "DisplayName"
			displayNameValue.Value = player.DisplayName
			displayNameValue.Parent = demo
	
			local userId = player.UserId
			local thumbType = Enum.ThumbnailType.HeadShot
			local thumbSize = Enum.ThumbnailSize.Size420x420
			local content, isReady = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)
			demo.ImageButtonL.Image = content
			demo.ImageButtonR.Image = content
	
			player:GetPropertyChangedSignal("Team"):Connect(function()
				refreshPlayers()
				updatePlayerList(TextBox.Text)
			end)
		end
	end
	
	local function updatePlayerListWithDebounce(searchText)
		updatePlayerList(searchText)
	end
	
	local function connectTeamChangedSignals()
		for _, player in ipairs(Players:GetPlayers()) do
			player:GetPropertyChangedSignal("Team"):Connect(function()
				refreshPlayers()
				updatePlayerList(TextBox.Text)
			end)
		end
	end
	
	TextBox:GetPropertyChangedSignal("Text"):Connect(function()
		updatePlayerListWithDebounce(TextBox.Text)
	end)
	
	TextBox.FocusLost:Connect(function()
		if TextBox.Text == "" then
			TextBox.Text = "Search..."
			updatePlayerListWithDebounce("search...")
		end
	end)
	
	TextBox.Focused:Connect(function()
		if TextBox.Text == "Search..." then
			TextBox.Text = ""
		end
	end)
	
	Players.PlayerAdded:Connect(function(player)
		player:GetPropertyChangedSignal("Team"):Connect(function()
			refreshPlayers()
			updatePlayerList(TextBox.Text)
		end)
		refreshPlayers()
		updatePlayerList(TextBox.Text)
	end)
	
	Players.PlayerRemoving:Connect(function()
		refreshPlayers()
		updatePlayerList(TextBox.Text)
	end)
	
	refreshPlayers()
	updatePlayerList("")
	connectTeamChangedSignals()
	
end;
task.spawn(C_b2);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Players.ButtonHandler
local function C_ba()
local script = G2L["ba"];
	local Players = game:GetService("Players")
	local frame = script.Parent
	
	local function darkenColor(color)
		return Color3.new(color.R * 0.5, color.G * 0.5, color.B * 0.5)
	end
	
	local function getTeamColor(player)
		if player and player.Team and player.Team.TeamColor then
			local teamColor = player.Team.TeamColor.Color
			if teamColor ~= BrickColor.White().Color then
				return teamColor
			end
		end
		return Color3.fromRGB(255, 0, 0)
	end
	
	local function applyHoverEffects(targetFrame, hovering)
		local player = Players:FindFirstChild(targetFrame.Name)
		if not player then return end
	
		local color = getTeamColor(player)
		local hoverColor = hovering and darkenColor(color) or color
	
		for _, b in ipairs(targetFrame:GetDescendants()) do
			if b:IsA("TextLabel") and b.Name == "Username" then
				b.TextColor3 = hoverColor
			elseif b:IsA("TextButton") then
				b.TextColor3 = hoverColor
			elseif b:IsA("ImageButton") then
				b.ImageTransparency = hovering and 0.5 or 0
			end
		end
	end
	
	local function connectEvents(container)
		container.MouseEnter:Connect(function()
			applyHoverEffects(container, true)
	
			local player = Players.LocalPlayer
			local sound = Instance.new("Sound")
			sound.Volume = 0.375
			sound.SoundId = "rbxassetid://421058925"
			sound.Name = "Sound"
			sound.Parent = player.Character
			if script.Parent.Parent.Parent.Parent.Parent.Tab.Text == script.Parent.Name then
				sound:Play()
			end
			task.delay(1, function()
				sound:Destroy()
			end)
		end)
	
		container.MouseLeave:Connect(function()
			applyHoverEffects(container, false)
		end)
	
		for _, b in ipairs(container:GetDescendants()) do
			if b:IsA("TextButton") or b:IsA("ImageButton") then
				b.MouseButton1Click:Connect(function()
					local player = Players.LocalPlayer
					local target = Players:FindFirstChild(b.Parent.Name)
					if not target then return end
	
					local clickSound = Instance.new("Sound")
					clickSound.Volume = 0.5
					clickSound.SoundId = "rbxassetid://535716488"
					clickSound.Name = "Sound"
					clickSound.Parent = player.Character
					clickSound:Play()
					task.delay(1, function()
						clickSound:Destroy()
					end)
	
					if target.Name == player.Name then
						script.Parent.Parent.Parent.Parent.Parent.Tab.Text = "Player"
						script.Parent.Parent.Parent.Parent.Parent.Meat.ScrollingFrame.CanvasPosition = Vector2.new(0, 0)
						script.Parent.Parent.Parent.Parent.Parent.ScrollBone.Player.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
						script.Parent.Parent.Parent.Parent.Parent.ScrollBone.Players.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
						script.Parent.Parent.Parent.Parent.Parent.Meat.ScrollingFrame.CanvasSize = UDim2.new(0, 0, 2.5, 0)
					else
						local ScrollingFrame = script.Parent.Parent.Parent.Parent.Parent.Meat.ScrollingFrame
						script.Parent.Parent.Parent.Parent.Parent.Tab.Text = "Target"
						script.Parent.Parent.Target.TargetName.Text = "@" .. target.Name
						ScrollingFrame.ScrollBarThickness = 0
						ScrollingFrame.ScrollingEnabled = false
						ScrollingFrame.ScrollBarImageTransparency = 1
						ScrollingFrame.CanvasSize = UDim2.new(0, 0, 2.5, 0)
						ScrollingFrame.CanvasPosition = Vector2.new(0, 0)
					end
				end)
			end
		end
	end
	
	for _, container in ipairs(frame:GetChildren()) do
		if container:IsA("Frame") then
			container.Active = true
			connectEvents(container)
			applyHoverEffects(container, false)
		end
	end
	
	frame.ChildAdded:Connect(function(child)
		if child:IsA("Frame") then
			child.Active = true
			connectEvents(child)
			applyHoverEffects(child, false)
		end
	end)
	
end;
task.spawn(C_ba);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.TargetName.TextBoxScript
local function C_c2()
local script = G2L["c2"];
	local camera = game.Workspace.CurrentCamera
	local Players = game.Players
	local LocalPlayer = Players.LocalPlayer
	
	local function getHumanoid(player)
		if player and player.Character then
			return player.Character:FindFirstChildOfClass("Humanoid")
		end
	end
	
	while true do
		local username = script.Parent.Text
		if username:sub(1, 1) == "@" then
			username = username:sub(2)
		end
		local targetPlayer = Players:FindFirstChild(username)
	
	
		if script.Parent.Online.Text == "ON" and targetPlayer then
			local targetHumanoid = getHumanoid(targetPlayer)
			if targetHumanoid then
				camera.CameraSubject = targetHumanoid
			end
		else
			local localHumanoid = getHumanoid(LocalPlayer)
			if localHumanoid then
				camera.CameraSubject = localHumanoid
			end
		end
	
		task.wait()
	end
	
end;
task.spawn(C_c2);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Teleport.LocalScript
local function C_c9()
local script = G2L["c9"];
	local button = script.Parent
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	
	button.MouseButton1Click:Connect(function()
		local character = player.Character
		local characterTargetName = script.Parent.Parent.TargetName.Text
	
		-- Remove "@" if it's the first character
		if characterTargetName:sub(1, 1) == "@" then
			characterTargetName = characterTargetName:sub(2)
		end
	
		local targetPlayer = game.Players:FindFirstChild(characterTargetName)
		if targetPlayer then
			local targetCharacter = targetPlayer.Character
			if targetCharacter and targetCharacter:FindFirstChild("HumanoidRootPart") then
				if character and character:FindFirstChild("HumanoidRootPart") then
					character.HumanoidRootPart.CFrame = targetCharacter.HumanoidRootPart.CFrame
	
					task.delay(.05, function()
						script.Parent.Online.Text = "OFF"
					end)
				end
			end
		end
	end)
	
end;
task.spawn(C_c9);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Fling.LocalScript
local function C_d0()
local script = G2L["d0"];
	local button = script.Parent
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local ReplicatedStorage = game:GetService("ReplicatedStorage")
	local player = Players.LocalPlayer
	
	if not ReplicatedStorage:FindFirstChild("JP_ON_TOP") then
		local detection = Instance.new("Decal")
		detection.Name = "JP_ON_TOP"
		detection.Parent = ReplicatedStorage
	end
	
	local activeFlag = script.Parent.Parent.Parent.FlingActive
	local movel = 0.1
	
	task.spawn(function()
		while true do
			if button.Online.Text == "ON" then
				activeFlag.Text = "ON"
				local character = player.Character
				local hrp = character and character:FindFirstChild("HumanoidRootPart")
	
				if hrp then
					local vel = hrp.Velocity
					hrp.Velocity = vel * 10000 + Vector3.new(0, 10000, 0)
					RunService.RenderStepped:Wait()
					hrp.Velocity = vel
					RunService.Stepped:Wait()
					hrp.Velocity = vel + Vector3.new(0, movel, 0)
					movel = -movel
				end
			else
				activeFlag.Text = "OFF"
			end
			RunService.Heartbeat:Wait()
		end
	end)
	
	while true do
		if button.Online.Text == "ON" then
			local character = player.Character
			local characterTargetName = script.Parent.Parent.TargetName.Text
			if characterTargetName:sub(1, 1) == "@" then
				characterTargetName = characterTargetName:sub(2)
			end
	
			local targetPlayer = Players:FindFirstChild(characterTargetName)
			if targetPlayer then
				local targetCharacter = targetPlayer.Character
				if targetCharacter and targetCharacter:FindFirstChild("HumanoidRootPart") then
					if character and character:FindFirstChild("HumanoidRootPart") then
						character.HumanoidRootPart.CFrame = targetCharacter.HumanoidRootPart.CFrame
					end
				end
			end
		end
		task.wait()
	end
end;
task.spawn(C_d0);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.Bang.LocalScript
local function C_d7()
local script = G2L["d7"];
	local player = game.Players.LocalPlayer
	local animationId = ""
	local animationTrack = nil
	local online = script.Parent.Online
	local teleporting = false
	local targetHRP = nil
	local targetPlayer = nil
	
	local function updateTarget()
		local username = script.Parent.Parent.TargetName.Text
		if username:sub(1, 1) == "@" then
			username = username:sub(2)
		end
		local targetPlayer = game.Players:FindFirstChild(username)
	
		if not targetPlayer then return end
	
		local function onTargetCharacter(character)
			local hrp = character:WaitForChild("HumanoidRootPart", 5)
			if hrp then
				targetHRP = hrp
			end
		end
	
		if targetPlayer.Character then
			onTargetCharacter(targetPlayer.Character)
		end
	
		targetPlayer.CharacterAdded:Connect(function(character)
			onTargetCharacter(character)
		end)
	end
	
	local function startTeleporting()
		local character = player.Character or player.CharacterAdded:Wait()
		local humanoid = character:WaitForChild("Humanoid")
		local hrp = character:WaitForChild("HumanoidRootPart")
	
		updateTarget()
		if not targetHRP then return end
	
		if humanoid.RigType == Enum.HumanoidRigType.R6 then
			animationId = "rbxassetid://148840371"
		else
			animationId = "rbxassetid://569145055"
		end
	
		local animation = Instance.new("Animation")
		animation.AnimationId = animationId
		animationTrack = humanoid:LoadAnimation(animation)
	
		animationTrack:Play()
		animationTrack:AdjustSpeed(7.5)
	
		teleporting = true
		coroutine.wrap(function()
			while teleporting and online.Text == "ON" do
				if targetHRP and hrp then
					local behindPosition = targetHRP.CFrame * CFrame.new(0, 0, 1)
					hrp.CFrame = CFrame.new(behindPosition.Position, targetHRP.Position)
				end
				task.wait()
			end
		end)()
	end
	
	online:GetPropertyChangedSignal("Text"):Connect(function()
		if online.Text == "OFF" then
			if animationTrack then
				animationTrack:Stop()
				animationTrack = nil
			end
			teleporting = false
		else
			startTeleporting()
		end
	end)
	
	player.CharacterAdded:Connect(function()
		if animationTrack then
			animationTrack:Stop()
			animationTrack = nil
		end
		if online.Text == "ON" then
			task.defer(startTeleporting)
		end
	end)
	
end;
task.spawn(C_d7);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.ButtonHandler
local function C_de()
local script = G2L["de"];
	local buttons = script.Parent:GetChildren()
	local isHovering = {}
	
	local InvisCD = false
	local InvisCooldownTime = 0.75
	
	for _, b in ipairs(buttons) do
		if b:IsA("TextButton") then
			isHovering[b] = false
	
			b.MouseEnter:Connect(function()
				isHovering[b] = true
				local player = game:GetService("Players").LocalPlayer
				local sound = Instance.new("Sound")
				sound.Volume = 0.375
				sound.SoundId = "rbxassetid://421058925"
				sound.Name = "Sound"
				sound.Parent = player.Character
				if script.Parent.Parent.Parent.Parent.Parent.Tab.Text == script.Parent.Name then
					sound:Play()
				end
				task.delay(1, function()
					sound:Destroy()
				end)
			end)
	
			b.MouseLeave:Connect(function()
				isHovering[b] = false
			end)
	
			b.MouseButton1Click:Connect(function()
				if b.Name == "Invisible" then
					if InvisCD == false then
						InvisCD = true
						task.delay(InvisCooldownTime, function()
							InvisCD = false
						end)
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 0.5
						clickSound.SoundId = "rbxassetid://535716488"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
						if b:FindFirstChild("Online").Text == "OFF" then
							b:FindFirstChild("Online").Text = "ON"
						else
							b:FindFirstChild("Online").Text = "OFF"
						end
					else
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 1
						clickSound.SoundId = "rbxassetid://550209561"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
					end
				elseif b.Name == "Fling" then
					if script.Parent.Parent.Player.Fling.Online.Text == "ON" then
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 1
						clickSound.SoundId = "rbxassetid://550209561"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
					else
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 0.5
						clickSound.SoundId = "rbxassetid://535716488"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
						if b:FindFirstChild("Online").Text == "OFF" then
							b:FindFirstChild("Online").Text = "ON"
						else
							b:FindFirstChild("Online").Text = "OFF"
						end
					end
				else
					local player = game:GetService("Players").LocalPlayer
					local clickSound = Instance.new("Sound")
					clickSound.Volume = 0.5
					clickSound.SoundId = "rbxassetid://535716488"
					clickSound.Name = "Sound"
					clickSound.Parent = player.Character
					clickSound:Play()
					task.delay(1, function()
						clickSound:Destroy()
					end)
					if b:FindFirstChild("Online").Text == "OFF" then
						b:FindFirstChild("Online").Text = "ON"
					else
						b:FindFirstChild("Online").Text = "OFF"
					end
				end
			end)
		end
	end
	
	while true do
		for _, b in ipairs(buttons) do
			if b:IsA("TextButton") then
				if isHovering[b] and b:FindFirstChild("Online").Text == "OFF" then
					b.TextColor3 = Color3.new(0.294118, 0, 0)
				elseif isHovering[b] and b:FindFirstChild("Online").Text == "ON" then
					b.TextColor3 = Color3.new(0.196078, 0.196078, 0.215686)
				elseif isHovering[b] == false and b:FindFirstChild("Online").Text == "ON" then
					b.TextColor3 = Color3.new(0.294118, 0.294118, 0.294118)
				else
					b.TextColor3 = Color3.new(1, 0, 0)
				end
			end
		end
		task.wait()
	end
	
end;
task.spawn(C_de);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.TextBoxHandler
local function C_df()
local script = G2L["df"];
	while true do
		for _, TextBoxScript in pairs(script.Parent:GetDescendants()) do
			if TextBoxScript.Name == "TextBoxScript" and TextBoxScript.Enabled == false then
				TextBoxScript.Enabled = true
			end
		end
		task.wait()
	end
end;
task.spawn(C_df);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Target.AvatarScript
local function C_e2()
local script = G2L["e2"];
	while true do
		local playerName = script.Parent.Parent:FindFirstChild("Target") and script.Parent.Parent.Target:FindFirstChild("TargetName") and script.Parent.Parent.Target.TargetName.Text
		if playerName then
			if playerName:sub(1, 1) == "@" then
				playerName = playerName:sub(2)
			end
	
			local player = game:GetService("Players"):FindFirstChild(playerName)
			if player then
				local success, content
				local thumbType = Enum.ThumbnailType.AvatarThumbnail
				local thumbSize = Enum.ThumbnailSize.Size420x420
				local userId = player.UserId
	
				success, content = pcall(function()
					return game.Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)
				end)
	
				if success and content then
					script.Parent:FindFirstChild("AVA_L").Image = content
					script.Parent:FindFirstChild("AVA_R").Image = content
				end
			end
		end
		task.wait()
	end
	
end;
task.spawn(C_e2);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous.ButtonHandler
local function C_e6()
local script = G2L["e6"];
	local buttons = script.Parent:GetChildren()
	local isHovering = {}
	
	local InvisCD = false
	local InvisCooldownTime = 0.75
	
	for _, b in ipairs(buttons) do
		if b:IsA("TextButton") then
			isHovering[b] = false
	
			b.MouseEnter:Connect(function()
				isHovering[b] = true
				local player = game:GetService("Players").LocalPlayer
				local sound = Instance.new("Sound")
				sound.Volume = 0.375
				sound.SoundId = "rbxassetid://421058925"
				sound.Name = "Sound"
				sound.Parent = player.Character
				if script.Parent.Parent.Parent.Parent.Parent.Tab.Text == script.Parent.Name then
					sound:Play()
				end
				task.delay(1, function()
					sound:Destroy()
				end)
			end)
	
			b.MouseLeave:Connect(function()
				isHovering[b] = false
			end)
	
			b.MouseButton1Click:Connect(function()
				if b.Name == "Invisible" then
					if InvisCD == false then
						InvisCD = true
						task.delay(InvisCooldownTime, function()
							InvisCD = false
						end)
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 0.5
						clickSound.SoundId = "rbxassetid://535716488"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
						if b:FindFirstChild("Online").Text == "OFF" then
							b:FindFirstChild("Online").Text = "ON"
						else
							b:FindFirstChild("Online").Text = "OFF"
						end
					else
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 1
						clickSound.SoundId = "rbxassetid://550209561"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
					end
				elseif b.Name == "Fling" then
					if script.Parent.Parent.FlingActive.Text == "ON" then
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 1
						clickSound.SoundId = "rbxassetid://550209561"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
					else
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 0.5
						clickSound.SoundId = "rbxassetid://535716488"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
						if b:FindFirstChild("Online").Text == "OFF" then
							b:FindFirstChild("Online").Text = "ON"
						else
							b:FindFirstChild("Online").Text = "OFF"
						end
					end
				else
					local player = game:GetService("Players").LocalPlayer
					local clickSound = Instance.new("Sound")
					clickSound.Volume = 0.5
					clickSound.SoundId = "rbxassetid://535716488"
					clickSound.Name = "Sound"
					clickSound.Parent = player.Character
					clickSound:Play()
					task.delay(1, function()
						clickSound:Destroy()
					end)
					if b:FindFirstChild("Online").Text == "OFF" then
						b:FindFirstChild("Online").Text = "ON"
					else
						b:FindFirstChild("Online").Text = "OFF"
					end
				end
			end)
		end
	end
	
	while true do
		for _, b in ipairs(buttons) do
			if b:IsA("TextButton") then
				if isHovering[b] and b:FindFirstChild("Online").Text == "OFF" then
					b.TextColor3 = Color3.new(0.294118, 0, 0)
				elseif isHovering[b] and b:FindFirstChild("Online").Text == "ON" then
					b.TextColor3 = Color3.new(0.196078, 0.196078, 0.215686)
				elseif isHovering[b] == false and b:FindFirstChild("Online").Text == "ON" then
					b.TextColor3 = Color3.new(0.294118, 0.294118, 0.294118)
				else
					b.TextColor3 = Color3.new(1, 0, 0)
				end
			end
		end
		task.wait()
	end
end;
task.spawn(C_e6);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous.Jerk Off.LocalScript
local function C_eb()
local script = G2L["eb"];
	
end;
task.spawn(C_eb);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Miscellaneous.TextBoxHandler
local function C_ee()
local script = G2L["ee"];
	while true do
		for _, TextBoxScript in pairs(script.Parent:GetDescendants()) do
			if TextBoxScript.Name == "TextBoxScript" and TextBoxScript.Enabled == false then
				TextBoxScript.Enabled = true
			end
		end
		task.wait()
	end
end;
task.spawn(C_ee);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.ButtonHandler
local function C_f0()
local script = G2L["f0"];
	local buttons = script.Parent:GetChildren()
	local isHovering = {}
	
	local InvisCD = false
	local InvisCooldownTime = 0.75
	
	for _, b in ipairs(buttons) do
		if b:IsA("TextButton") then
			isHovering[b] = false
	
			b.MouseEnter:Connect(function()
				isHovering[b] = true
				local player = game:GetService("Players").LocalPlayer
				local sound = Instance.new("Sound")
				sound.Volume = 0.375
				sound.SoundId = "rbxassetid://421058925"
				sound.Name = "Sound"
				sound.Parent = player.Character
				if script.Parent.Parent.Parent.Parent.Parent.Tab.Text == script.Parent.Name then
					sound:Play()
				end
				task.delay(1, function()
					sound:Destroy()
				end)
			end)
	
			b.MouseLeave:Connect(function()
				isHovering[b] = false
			end)
	
			b.MouseButton1Click:Connect(function()
				if b.Name == "Invisible" then
					if InvisCD == false then
						InvisCD = true
						task.delay(InvisCooldownTime, function()
							InvisCD = false
						end)
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 0.5
						clickSound.SoundId = "rbxassetid://535716488"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
						if b:FindFirstChild("Online").Text == "OFF" then
							b:FindFirstChild("Online").Text = "ON"
						else
							b:FindFirstChild("Online").Text = "OFF"
						end
					else
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 1
						clickSound.SoundId = "rbxassetid://550209561"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
					end
				elseif b.Name == "Fling" then
					if script.Parent.Parent.FlingActive.Text == "ON" then
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 1
						clickSound.SoundId = "rbxassetid://550209561"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
					else
						local player = game:GetService("Players").LocalPlayer
						local clickSound = Instance.new("Sound")
						clickSound.Volume = 0.5
						clickSound.SoundId = "rbxassetid://535716488"
						clickSound.Name = "Sound"
						clickSound.Parent = player.Character
						clickSound:Play()
						task.delay(1, function()
							clickSound:Destroy()
						end)
						if b:FindFirstChild("Online").Text == "OFF" then
							b:FindFirstChild("Online").Text = "ON"
						else
							b:FindFirstChild("Online").Text = "OFF"
						end
					end
				else
					local player = game:GetService("Players").LocalPlayer
					local clickSound = Instance.new("Sound")
					clickSound.Volume = 0.5
					clickSound.SoundId = "rbxassetid://535716488"
					clickSound.Name = "Sound"
					clickSound.Parent = player.Character
					clickSound:Play()
					task.delay(1, function()
						clickSound:Destroy()
					end)
					if b:FindFirstChild("Online").Text == "OFF" then
						b:FindFirstChild("Online").Text = "ON"
					else
						b:FindFirstChild("Online").Text = "OFF"
					end
				end
			end)
		end
	end
	
	while true do
		for _, b in ipairs(buttons) do
			if b:IsA("TextButton") then
				if isHovering[b] and b:FindFirstChild("Online").Text == "OFF" then
					b.TextColor3 = Color3.new(0.294118, 0, 0)
				elseif isHovering[b] and b:FindFirstChild("Online").Text == "ON" then
					b.TextColor3 = Color3.new(0.196078, 0.196078, 0.215686)
				elseif isHovering[b] == false and b:FindFirstChild("Online").Text == "ON" then
					b.TextColor3 = Color3.new(0.294118, 0.294118, 0.294118)
				else
					b.TextColor3 = Color3.new(1, 0, 0)
				end
			end
		end
		task.wait()
	end
end;
task.spawn(C_f0);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Solara Hub.LocalScript
local function C_f5()
local script = G2L["f5"];
	local button = script.Parent
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	
	button.MouseButton1Click:Connect(function()
		task.delay(.05, function()
			script.Parent.Online.Text = "OFF"
		end)
		loadstring(game:HttpGet("https://raw.githubusercontent.com/samuraa1/Solara-Hub/refs/heads/main/Solara%20Hub.lua"))()
	end)
end;
task.spawn(C_f5);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.TextBoxHandler
local function C_f8()
local script = G2L["f8"];
	while true do
		for _, TextBoxScript in pairs(script.Parent:GetDescendants()) do
			if TextBoxScript.Name == "TextBoxScript" and TextBoxScript.Enabled == false then
				TextBoxScript.Enabled = true
			end
		end
		task.wait()
	end
end;
task.spawn(C_f8);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrame.Holder.Script Hubs.Sirius.LocalScript
local function C_fd()
local script = G2L["fd"];
	local button = script.Parent
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	
	button.MouseButton1Click:Connect(function()
		task.delay(.05, function()
			script.Parent.Online.Text = "OFF"
		end)
		loadstring(game:HttpGet('https://sirius.menu/sirius'))()
	end)
end;
task.spawn(C_fd);
-- StarterGui.DREADED_HUB.WholeThang.Meat.ScrollingFrameProperties
local function C_101()
local script = G2L["101"];
	local Tab = script.Parent.Parent.Tab
	local ScrollingFrame = script.Parent.ScrollingFrame
	local Holder = ScrollingFrame:FindFirstChild("Holder")
	
	local function updateTab()
		local currentTab = Tab.Text
	
		if currentTab == "Dashboard" or currentTab == "Target" then
			ScrollingFrame.ScrollBarThickness = 0
			ScrollingFrame.ScrollingEnabled = false
			ScrollingFrame.ScrollBarImageTransparency = 1
			ScrollingFrame.CanvasSize = UDim2.new(0, 0, 2.5, 0)
		elseif currentTab == "Players" then
			ScrollingFrame.CanvasSize = UDim2.new(0, 0, 23, 0)
			ScrollingFrame.ScrollBarThickness = 12
			ScrollingFrame.ScrollingEnabled = true
			ScrollingFrame.ScrollBarImageTransparency = 0
		else
			ScrollingFrame.ScrollBarThickness = 12
			ScrollingFrame.ScrollingEnabled = true
			ScrollingFrame.ScrollBarImageTransparency = 0
			ScrollingFrame.CanvasSize = UDim2.new(0, 0, 2.5, 0)
		end
	
		for _, folder in pairs(Holder:GetChildren()) do
			if folder:IsA("Folder") then
				local isActive = (folder.Name == currentTab)
	
				for _, uiElement in pairs(folder:GetDescendants()) do
					if uiElement:IsA("GuiObject") and uiElement.Name ~= "Demo" then
						uiElement.Visible = isActive
					end
				end
			end
		end
	end
	
	Tab:GetPropertyChangedSignal("Text"):Connect(function()
		updateTab()
		task.wait()
	end)
	
	Tab.Text = "Dashboard"
	updateTab()
	
end;
task.spawn(C_101);
-- StarterGui.DREADED_HUB.LoadedSound
local function C_106()
local script = G2L["106"];
	local player = game:GetService("Players").LocalPlayer
	local playerGui = script.Parent:FindFirstAncestorWhichIsA("PlayerGui")
	if playerGui then
		local dreadedHubs = playerGui:GetChildren()
		local count = 0
	
		for _, descendant in ipairs(dreadedHubs) do
			if descendant.Name == "DREADED_HUB" then
				count += 1
			end
		end
	
		if count == 1 then
			local sound = Instance.new("Sound")
			sound.Volume = 0.5
			sound.SoundId = "rbxassetid://2483029612"
			sound.Name = "Sound"
			sound.Parent = player.Character
			sound:Play()
			task.delay(1, function()
				sound:Destroy()
				script:Destroy()
			end)
		end
	end
	
	script.Parent.WholeThang.ScrollBone.Player.Text = player.Name
	script.Parent.Name = "A86CYVAUH3J8"
	task.wait()
	if script.Parent.Parent:FindFirstChild("DREADED_HUB") then
		local killSwitch = script.Parent:FindFirstChild("KILL_SWITCH")
		local killingLabel = killSwitch and killSwitch:FindFirstChild("KILLING")
		if killingLabel then
			local current = tonumber(killingLabel.Text) or 0
			killingLabel.Text = tostring(current + 1)
		end
	end
	task.wait()
	script.Parent.Name = "DREADED_HUB"
end;
task.spawn(C_106);
-- StarterGui.DREADED_HUB.KILL_SWITCH
local function C_107()
local script = G2L["107"];
	local UserInputService = game:GetService("UserInputService")
	
	local isJKeyHeld = false
	
	local function mouseKill()
		script.Parent.Cursor.ImageTransparency = 1
		UserInputService.MouseIconEnabled = true
		game:GetService("Players").LocalPlayer:GetMouse().Icon = ""
	end
	
	local function KILLSWITCH()
		script.Parent.Name = "7SDYUH4U2Y7"
		
		local KILL_ON = Instance.new("Frame", script.Parent)
		KILL_ON.Name = "KILLING..."
		KILL_ON.Position = UDim2.new({28.106, 0},{148.836, 0})
		KILL_ON.Size = UDim2.new({0.807, 0},{1.525, 0})
		KILL_ON.Visible = false
	
		workspace.Gravity = script.Parent.WholeThang.Meat.ScrollingFrame.Holder.Player.Gravity.TextBox.TextBoxScript.Gravity.Text
	
		for _, scripts in pairs(script.Parent:GetDescendants()) do
			if scripts:IsA("LocalScript") and scripts.Name ~= script.Name then
				scripts.Enabled = false
				scripts:Destroy()
			end
		end
	
		game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart"):FindFirstChild("Died").Volume = 0
		game.Players.LocalPlayer.Character:BreakJoints()
		local sound = Instance.new("Sound")
		sound.Volume = 0.1
		sound.SoundId = "rbxassetid://7148585764"
		sound.Name = "Sound"
		sound.Parent = game.Players.LocalPlayer.Character
		sound:Play()
		script.Parent.Enabled = false
		mouseKill()
		task.wait(.5)
		mouseKill()
		script.Parent.ResetOnSpawn = true
		game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart"):FindFirstChild("Died").Volume = 0.65
		
		local children = game.Players.LocalPlayer.PlayerGui:GetChildren()
	
		for i = 1, #children do
			if children[i].Name == "DREADED_HUB" then
				children[i]:Destroy()
			end
		end
	end
	
	local function SWAP()
		local KILL_ON = Instance.new("Frame", script.Parent)
		KILL_ON.Name = "KILLING..."
		KILL_ON.Position = UDim2.new({28.106, 0},{148.836, 0})
		KILL_ON.Size = UDim2.new({0.807, 0},{1.525, 0})
		KILL_ON.Visible = false
	
		for _, scripts in pairs(script.Parent:GetDescendants()) do
			if scripts:IsA("LocalScript") and scripts.Name ~= script.Name then
				scripts.Enabled = false
				scripts:Destroy()
			end
		end
	
		script.Parent.Enabled = false
		mouseKill()
		task.wait(.5)
		mouseKill()
		script.Parent.ResetOnSpawn = true
		game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart"):FindFirstChild("Died").Volume = 0.65
		script.Parent:Destroy()
	end
	
	local function onInputBegan(input, gameProcessed)
		if gameProcessed then
			return
		end
	
		if input.KeyCode == Enum.KeyCode.J then
			isJKeyHeld = true
		end
	
		if isJKeyHeld and input.KeyCode == Enum.KeyCode.P then
			KILLSWITCH()
			
		end
	end
	
	local function onInputEnded(input)
		if input.KeyCode == Enum.KeyCode.J then
			isJKeyHeld = false
		end
	end
	
	UserInputService.InputBegan:Connect(onInputBegan)
	UserInputService.InputEnded:Connect(onInputEnded)
	script:WaitForChild("KILLING"):GetPropertyChangedSignal("Text"):Connect(SWAP)
	
end;
task.spawn(C_107);
-- StarterGui.DREADED_HUB.Cursor.CursorScript
local function C_10a()
local script = G2L["10a"];
	local UserInputService = game:GetService("UserInputService")
	local Players = game:GetService("Players")
	local GuiService = game:GetService("GuiService")
	
	local player = Players.LocalPlayer
	local mouse = player:GetMouse()
	
	local guiObject = script.Parent.Parent
	local targetArea = guiObject:WaitForChild("WholeThang")
	
	while true do
		if not script.Parent.Parent:FindFirstChild("KILLING...") then
			local mousePos = UserInputService:GetMouseLocation()
			local topBarInset = GuiService:GetGuiInset()
			local adjustedMousePos = Vector2.new(mousePos.X, mousePos.Y - topBarInset.Y)
	
			script.Parent.Position = UDim2.new(0, mousePos.X, 0, mousePos.Y)
			mouse.Icon = "rbxassetid://81509234559934"
	
			local absPos = targetArea.AbsolutePosition
			local absSize = targetArea.AbsoluteSize
	
			local inBounds = adjustedMousePos.X >= absPos.X and adjustedMousePos.X <= absPos.X + absSize.X and
				adjustedMousePos.Y >= absPos.Y and adjustedMousePos.Y <= absPos.Y + absSize.Y
	
			script.Parent.ImageTransparency = inBounds and 0 or 1
			UserInputService.MouseIconEnabled = not inBounds
		else
			script.Parent.ImageTransparency = 1
			UserInputService.MouseIconEnabled = true
			mouse.Icon = ""
		end
		task.wait()
	end
	
end;
task.spawn(C_10a);

return G2L["1"], require;
