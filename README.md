# CG-Week9

I implemented a partially transparent glass shader, a UV tiler/scaler shader, a simple shadow shader that supports shadows cast by the model onto itself, a shadow shader that supports a texture and customizable shadow colour and can cast onto other objects, a water shader that scrolls two different textures on each other to give the illusion of flowing water, and a water shader that simulates waves with vertex displacement.

I implemented all of the shaders sucecssfully and had fun tweaking the values and seeing what can be done with them. Some of the shaders had bugs and had to be fixed which took some time, but overall I understood these shaders quickly and most of them implemented smoothly. I really enjoyed seeing how waves can be made with shaders instead of complex C# code. The things I learned in this activity made me more well-prepared for the exam, and I'll be taking a closer look into all of these shaders before the exam.

---

The glass shader applies a texture to an object, some extra effects like light intensity, then modifies the transparency channel with an inspector value.

The UV Tiler/Scaler shader uses a sine function to scale the object's UVs on the x and y axis

The Simple Shadow shader is essentially just diffuse lighting on an object

The Texture/Complex Shadow shader applies a texture, colours the shadow, and can cast onto other objects

The Scrolling Water shader uses 2 textures (one for water, one for foam) and scrolls them in the same direction at different speeds using a _Time variable

The Waves Water shader applies a texture, and uses a sine function to displace the vertices of the object to create waves that move through it using the _Time variable. It can take amplitude, frequency, and speed variables

---

Glass Shader:
<img width="1705" height="680" alt="image" src="https://github.com/user-attachments/assets/7153f191-f8fe-4f0c-bfb1-ef0b0bc277af" />

UV Tiler/Scaler Shader:
<img width="1703" height="693" alt="image" src="https://github.com/user-attachments/assets/e80884a6-7d26-4f0d-9f79-f05a8a7e9100" />

Simple Shadow Shader:
<img width="1703" height="699" alt="image" src="https://github.com/user-attachments/assets/95ae25af-93ed-4b0d-8d72-bc3a350bbde5" />

Texture/Complex Shadow Shader:
<img width="1710" height="685" alt="image" src="https://github.com/user-attachments/assets/150c20c2-904b-4d27-802a-57bc45334b65" />

Scrolling Water Shader:
<img width="1703" height="688" alt="image" src="https://github.com/user-attachments/assets/75cbf29a-87db-4d75-9461-697d27a8a648" />

Waves Water Shader:
<img width="1709" height="690" alt="image" src="https://github.com/user-attachments/assets/eec8e484-020e-43be-9d47-2714e82a6cef" />
