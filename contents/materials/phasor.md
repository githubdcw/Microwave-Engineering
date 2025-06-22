[$`\footnotesize \copyright \: \text {Denchai Worasawate}`$](https://www.researchgate.net/profile/Denchai-Worasawate)  
| [หน้าหลัก](/README.md) | [Contents](../contents/contents.md) |  
| ---------- | ---------- |    

# Phasor
Phasor เป็นการวิเคราะห์สัญญาณที่ละความถี่  
ปกติสัญญาณจะเป็นฟังก์ชันของเวลาเช็น $` s(t) `$ เป็นฟังก์ชันอะไรก็ได้  
ถ้าเราสมมุติให้สัญญาณมีความถี่เดียวคือ $`f`$ จะได้ว่า  
```math
s_{real}(t) = A \cos(2 \pi f t + \phi)  
```
เมื่อ $`A`$ เป็น แอมปริจูดของสัญญาณ $`f`$ เป็นความถี่ และ $`\phi`$ เป็นเฟสเริ่มต้นของสัญญาณเมื่อเวลา $`t=0`$  
เราเพิ่มสัญญาณที่คล้ายกันแต่มีเฟสเลื่อนไป 90 องศา และให้เป็นค่าจิตภาพคือ  
```math
s_{imag}(t) = j A \sin(2 \pi f t + \phi) 
```  
สัญญาณที่เราจะใช้ในการวิเคราะห์จะประกอบด้วยสัญญาณจริงและสัญญาณที่เพิ่มเข้าไปคือ  
```math
s(t) = s_{real}(t)+ s_{imag}(t) = A \left( \cos(2 \pi f t + \phi) + j\sin(2 \pi f t + \phi) \right)   
```  
```math
s(t) = A e^{j(2 \pi f t + \phi)}
```  
```math
s(t) = A e^{j(\omega t + \phi)}
```  
```math
s(t) = A e^{j\phi} e^{j\omega t}
```  

เมื่อ $`\omega = 2 \pi f t `$  
