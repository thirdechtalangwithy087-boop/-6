-- สร้างปุ่มผ่านสคริปต์ (Server-side)
local screenGui = Instance.new("ScreenGui", game.Players.LocalPlayer:WaitForChild("PlayerGui"))
local button = Instance.new("TextButton", screenGui)

button.Size = UDim2.new(0, 200, 0, 50)
button.Position = UDim2.new(0.5, -100, 0.5, -25)
button.Text = "กดที่นี่เพื่อเริ่มระบบ"

-- สร้างฟังก์ชันเมื่อมีการกดปุ่ม
button.MouseButton1Click:Connect(function()
    print("ระบบทำงานแล้ว!")
    -- คุณสามารถใส่คำสั่งที่ต้องการให้เกิดผลในเกมของคุณไว้ตรงนี้
end)
