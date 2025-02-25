# Tổng quan về hệ thống AI (LLM, Compound AI System, Agent)


## LLMs (Large Language Model) 
- Mô hình ngôn ngữ lớn dùng để xử lý ngôn ngữ tự nhiên.

<img width="988" alt="image" src="https://github.com/user-attachments/assets/67912681-2c7c-4f0a-8db5-7355f937726e" />


- **Vector Database:** Lưu trữ embeddings để tra cứu nhanh (embeddings là chuyển đổi dữ liệu (văn bản, hình ảnh, video) thành vector số.).
- **External APIs:** Lấy thông tin từ bên ngoài (Google Search, Wikipedia, v.v.).
- **Fine-Tuned Models:** Các mô hình LLM đã được tinh chỉnh theo mục đích cụ thể.

**Nhược điểm**
- Limited knowledge
- Hard to adapt

## Compound AI System

<img width="988" alt="image" src="https://github.com/user-attachments/assets/0eef9d47-e704-4036-b96c-6cf810cf52c4" />

1. **User Interaction Layer:** Người dùng gửi yêu cầu qua giao diện web/app.  
2. **Orchestration Layer:**  
   - **Router** điều phối yêu cầu từ UI đến các thành phần AI phù hợp.  
   - **Workflow Engine** quyết định cách xử lý yêu cầu.  
   - **Memory & Knowledge Base** lưu trữ dữ liệu để hỗ trợ truy vấn thông minh.  
3. **AI Processing Layer:**  
   - **LLM (Large Language Model):** Xử lý văn bản, tạo nội dung.  
   - **Multi-Modal AI:** Hỗ trợ xử lý đa phương thức (hình ảnh, âm thanh, văn bản).  
   - **Specialized AI Models:** Các mô hình AI chuyên biệt (ví dụ: phân tích tài chính, y tế, NLP).  
4. **Toolset & Integration Layer:**  
   - **Plugins & Extensions:** Mở rộng khả năng của AI bằng các công cụ bổ sung.  
   - **External APIs:** Lấy dữ liệu từ các hệ thống bên ngoài.  
   - **Database:** Lưu trữ và truy xuất dữ liệu cần thiết.  
5. **Infrastructure Layer:**  
   - **Compute (GPU, Cloud, Edge):** Cung cấp tài nguyên xử lý.  
   - **Storage (Vector DB, Cache, File System):** Lưu trữ dữ liệu và truy vấn nhanh.  

## AI Agent

<img width="988" alt="image" src="https://github.com/user-attachments/assets/c01abd33-a3bd-4316-9aa6-1e927d3027a5" />


1. **User Interaction:**  
   - Người dùng gửi yêu cầu qua giao diện (UI).  
2. **AI Agent System:**  
   - **Perception (Nhận thức):** Xử lý đầu vào từ người dùng hoặc môi trường.  
   - **Memory (Bộ nhớ & Ngữ cảnh):** Lưu trữ dữ liệu và thông tin ngữ cảnh.  
   - **Planning (Lập kế hoạch):** Tạo chiến lược thực thi dựa trên thông tin nhận được.  
   - **Execution (Thực thi):** Gửi lệnh đến các hệ thống hoặc thực hiện hành động.  
   - **Feedback Loop (Vòng phản hồi):** Cập nhật thông tin dựa trên kết quả thực thi.  
3. **External Resources:**  
   - **LLM (Large Language Model):** Hỗ trợ xử lý ngôn ngữ tự nhiên.  
   - **Toolset (Plugins, API, Frameworks):** Công cụ hỗ trợ AI thực hiện nhiệm vụ.  
   - **Database:** Lưu trữ dữ liệu cần thiết cho agent.  
   - **External APIs:** Kết nối với hệ thống bên ngoài để lấy dữ liệu hoặc thực hiện tác vụ.  

