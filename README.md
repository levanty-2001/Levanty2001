# 🚀 Giới thiệu về tôi  

Xin chào! Tôi là [LÊ VĂN TÝ],  Tôi luôn tìm kiếm cơ hội để học hỏi và xây dựng các sản phẩm sáng tạo.                  
## 🌱 Đang học hỏi  
Hiện tại, tôi đang tìm hiểu sâu hơn về **hiệu suất trong game mobile** và **tối ưu hóa giao diện web**.  

## 📫 Liên hệ với tôi  
- 📧 Email: [tylevan613@gmail.com]  
- 🔗 LinkedIn: [https://www.facebook.com/share/1BXVa8UXaX/]  
import numpy as np
import matplotlib.pyplot as plt

t = np.linspace(0, 2 * np.pi, 1000)

# Công thức parametric của trái tim
x = 16 * np.sin(t)**3
y = 13 * np.cos(t) - 5 * np.cos(2*t) - 2 * np.cos(3*t) - np.cos(4*t)

plt.figure(figsize=(6, 6))
plt.plot(x, y, 'r')  # Vẽ đường viền trái tim màu đỏ
plt.fill(x, y, 'red', alpha=0.6)  # Tô màu đỏ
plt.axis("equal")  # Đảm bảo tỷ lệ trục bằng nhau
plt.axis("off")  # Ẩn trục tọa độ
plt.title("💖 Trái Tim 💖", fontsize=14)
plt.show()