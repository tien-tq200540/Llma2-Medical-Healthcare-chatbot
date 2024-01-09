# Llma2-Medical-Healthcare-chatbot
# BTL Nhập môn Học máy và Khai phá dữ liệu
•	Hướng dẫn cài đặt:
-	Bước 1: Clone repo về theo link: git clone link_github
-	Bước 2: Mở terminal, cài đặt các thư viện: pip install –r requirement.txt
-	Bước 3: Tải model học máy về theo link: https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q8_0.bin
-	Bước 4: Chuyển model học máy vào project. Trong file ingest.py, thay các đường dẫn trong DATA_PATH và DB_FAISS_PATH cho phù hợp.
-	Bước 4: Vào folder chính của project, chạy python ingest.py cơ sở dữ liệu vector
-	Bước 5: chạy project bằng lệnh chainlit run model.py
