--
detect click

local button = script.Parent
button.MouseButton1Click:Connect(function()
    print("Button clicked!")
end)
--

--
get object property

local part = script.Parent

local propertyName = "insert property"

local propertyValue = part:GetAttribute(propertyName)

if propertyValue then
    print("Property value:", propertyValue)
else
    print("Property not found or has no value.")
end
--

