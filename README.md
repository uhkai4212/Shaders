# **Shaders for Roblox**

## 🌟 **Introduction**  
Shaders in Roblox improve game visuals by adding realistic lighting, textures, and effects such as dynamic sunlight, reflections, and depth of field.

---

## 📦 **Types of Shaders**
1. **Surface Shaders**: Modify how light interacts with objects (e.g., metallic surfaces).  
2. **Post-Processing Effects**: Enhance the overall scene (e.g., bloom, blur).  
3. **Screen Space Shaders**: Apply effects like motion blur globally.

---

## 🛠️ **How to Add Shaders**
1. Open **Roblox Studio**.  
2. Go to the **Lighting** section in Explorer.  
3. Add effects like:  
   - **BloomEffect**: Adds glow.  
   - **BlurEffect**: Creates blur.  
   - **ColorCorrectionEffect**: Adjusts brightness/contrast.  

---

## 🔧 **Code Example**
Here’s a simple script to add a BloomEffect:
```lua
local Lighting = game:GetService("Lighting")

local bloom = Instance.new("BloomEffect")
bloom.Intensity = 1.5
bloom.Size = 24
bloom.Threshold = 0.8
bloom.Parent = Lighting
