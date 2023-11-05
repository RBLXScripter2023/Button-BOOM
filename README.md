#Scripted by BIGGAMES2022YEAR. Before use, create a text button in the UI and name it "BOOM!".
#Thank you for use my script.

local function boom()
	exp = Instance.new("Explosion")
	exp.Position = Workspace.PartExplosion.Position
	exp.Parent = Workspace
end

script.Parent.Activated:Connect(boom)

#Scripted by BIGGAMES2022YEAR. Before use, create a text button in the UI and name it "BOOM!"



