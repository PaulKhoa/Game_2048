# Game 2048

Dự án này xây dựng trò chơi **2048** kèm theo các thuật toán tìm kiếm AI gồm **BFS, DFS, UCS, A star, Greedy**. Mục tiêu là minh họa cách các thuật toán duyệt không gian trạng thái để tìm chuỗi nước đi tốt nhất hoặc tự động chơi trò chơi.

---

## 🎮 Giới thiệu

**2048** là game puzzle trên lưới 4x4, trong đó người chơi trượt các ô theo bốn hướng **Up / Down / Left / Right** để gộp các ô có cùng giá trị.

**Luật chơi chính:**
- Hai ô cùng giá trị khi trượt sẽ hợp thành một ô mới có giá trị gấp đôi.
- Sau mỗi lượt, một ô mới xuất hiện (2 hoặc 4).
- **Trò chơi kết thúc khi:**
  - Không còn nước đi hợp lệ (bảng đầy + không thể gộp), hoặc  
  - Tạo được ô **2048**.

Người chơi có thể chơi bằng tay hoặc để hệ thống tự chơi bằng các thuật toán AI sau:

### 🔹 BFS (Breadth-First Search)
Duyệt theo từng tầng trạng thái. Tìm lời giải ngắn nhất nhưng tốn nhiều bộ nhớ.

### 🔹 DFS (Depth-First Search)
Duyệt sâu theo nhánh. Ít tốn bộ nhớ hơn BFS nhưng không tối ưu.

### 🔹 UCS (Uniform Cost Search)
Chọn đường có tổng chi phí thấp nhất, dựa trên hàm đánh giá chi phí của từng trạng thái.

### 🔹 A* Search
Dựa trên f(n) = g(n) + h(n). Hiệu quả hơn UCS nếu heuristic tốt.

### 🔹 Greedy Best-First Search
Chọn hành động có heuristic tốt nhất ngay lập tức. Chạy nhanh nhưng không tối ưu.

---

## ⚙️ Cài đặt & chạy chương trình

### 1. Clone project
### 2. Cài đặt thư viện
### 3. Chạy file play.py
