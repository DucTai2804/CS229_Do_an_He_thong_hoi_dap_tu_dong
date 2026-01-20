# Đồ án CS229: Hệ thống Hỏi đáp Ngữ nghĩa (Computational Semantics)

## 📌 Giới thiệu
Đồ án xây dựng một hệ thống hỏi đáp tự động (QA System) cho miền dữ liệu hẹp (thông tin công ty, nhân viên, sở thích...). Hệ thống minh hoạ sự khác biệt giữa hai phương pháp tiếp cận:
1.  **Logical Pipeline (Prolog):** Chuyển đổi ngôn ngữ tự nhiên sang cấu trúc ngữ nghĩa (DRS) và Logic bậc nhất (FOL).
2.  **LLM (Large Language Model):** Sử dụng mô hình Llama-3 qua API Groq để suy luận trực tiếp.

## 🚀 Tính năng chính
* **Xử lý ngữ nghĩa:** Phân tích câu hỏi tiếng Việt không dấu/có dấu.
* **Giao diện:** Tương tác trực quan qua Web UI (Gradio).

## 📂 Cấu trúc file
* `Demo_do_an_CS229 (2).ipynb`: File Notebook chính chứa toàn bộ mã nguồn (Python + Prolog).
    * Tự động cài đặt môi trường (SWI-Prolog, Gradio).
    * Tự động sinh các file `grammar.pl`, `facts.pl`, `engine.pl`.

## 🛠️ Cài đặt và Chạy
Cách đơn giản nhất là chạy trên **Google Colab**:
1.  Tải file `.ipynb` về máy.
2.  Upload lên Google Colab.
3.  Chạy lần lượt các cell (Start runtime -> Run all).
4.  Truy cập link Gradio (ví dụ: `https://xxxx.gradio.live`) được tạo ra ở cell cuối cùng.
