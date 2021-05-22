# TÓM TẮT NỘI DUNG
## I.LINK DOWNLOAD (ĐỐI VỚI SỬ DỤNG OFFLINE)
### 1.Trình soạn thảo LaTeX
   - [TeXstudio](https://www.texstudio.org/)
   - [Texmaker](https://www.xm1math.net/texmaker/)
### 2.Trình biên dịch Latex
   - [TeX Live](https://www.tug.org/texlive/acquire-netinstall.html)
   - [MikTex](https://miktex.org/)
## II.LATEX WEB ONLINE
   - [Overleaf](https://www.overleaf.com/)
   - [Latexbase](https://latexbase.com/)
   - [Papeeria](https://papeeria.com/)
   - [Stackexchange](https://tex.stackexchange.com/)
## III.CÁC ĐỊNH DẠNG THƯỜNG GẶP CỦA LATEX
      *.tex Tập tin nhập liệu của LaTeX (tệp tin nguồn)
      *.sty Gói lệnh thêm vào cho LaTeX. Nó là một tập tin riêng lẽ và bạn có thể kết hợp nó vào tập tin tài liệu của bạn bằng cách sử dụng lệnh \usepackage{}
      *.pdf Tệp tin xuất bản, tệp này sẽ xuất hiện sau khi bạn biên
## IV.CẤU TRÚC FILE LATEX
   ### 1.Phần khai báo cấu trúc trang
         \Documentclass[options]{Loại cấu trúc}
   #### Phân tích:
   Options : Tùy chọn kích cỡ phông chữ cho trang
   Loại cấu trúc : Có nhiều loại nhưng sử dụng chủ yếu là 3 loại sau:
   - *article* phù hợp khi soạn các bài báo trong các tạp chí khoa học, các văn bản trình diễn, các báo cáo ngắn, chương trình hoạt động, thư mời, . . .
   - *report* phù hợp khi soạn các báo cáo gồm nhiều chương, các quyển sáchnhỏ, luận văn,. . .
   - *book* phù hợp khi soạn sách
   ### 2.Phần khai báo cấu các gói thư viện 
         \unpackage[options]{tên gói lệnh}
   #### Phân tích:
   Options: Những tùy chỉnh kèm thêm gói (có thể không bắt buộc)
   Tên gói lệnh: Tùy nhu cầu người sử dụng , có nhiều gói hỗ trợ các tính năng đặc biệt trong latex
   - *vietnam* gói hỗ trợ tiếng việt kèm theo option utf8:  \usepackage[utf8]{vietnam}
   - *ulem* gói hỗ trợ định dạng gạch chân chữ: \usepackage{ulem}
   - *amsmath* gói hỗ trợ viết công thức toán học: \usepackage{amsmath}
   - *graphicx* gói hỗ trợ thêm hình ảnh cho latex: \usepackage{graphicx}
  
       ...
   ### 3. Viết trang latex căn bản với tiêu đề , tác giả và ngày tháng
        
        \title{Nội dung tiêu đề}
        \author{Tên tác giả \ thanks{Nội dung} }
        \date{Nội dung}
        
   ![image](https://user-images.githubusercontent.com/79437149/119212209-0210de80-bae1-11eb-9614-a9ee30964cc1.png)
   
       \documentclass[15pt]{article}
       \usepackage[utf8]{vietnam}
       \title{First document}
       \author{Hubert Farnsworth \thanks{Meomeomeo} }
       \date{February 2021}

       \begin{document}   
       \begin{titlepage} 
       \maketitle
       \end{titlepage}
       \end{document}
   ##### Câu lệnh trong latex được bắt đầu bằng dấu 
       \
   ##### Khai báo cấu trúc trang và font
      \documentclass[15pt]{article}
   ##### Khai báo gói tiếng việt
      \usepackage[utf8]{vietnam}
   ##### Lệnh khai báo tiêu đề trang , tên tác giả , ngày tháng , lời cám ơn có thể thay đổi nội dung trong dấu {} thành nội dung cần thể hiện
      \title{First document}
      \author{Hubert Farnsworth \thanks{Meomeomeo} }
      \date{February 2021}
   ##### Nội dung chính của 1 file văn bản được đặt trong *\begin{document}* và *\end{document}*
      \begin{document}   
      \end{document}
   ##### Đánh đấu bắt đầu và kết thúc của tiêu đề trang   
      \begin{titlepage} 
      \maketitle
      \end{titlepage}
   ### 4. Lệnh ngắt trang
      \newpage
   ### 5.Kiểu trang
      \pagestyle{kiểu}
   - *plain* đánh và xuất số trang ở giữa phần chân ở cuối trang văn bản. Đây là kiểu định dạng mặc định.
   - *headings* xuất tiêu đề của chương hiện tại và số thứ tự của trang văn bản ở vùng tiêu đề của trang; đồng thời, phần chân của trang được để trống.
   - *empty* đặt cả phần tiêu đề và phân chân của trang là rỗng.
   #### HIỆN TÊN CHAPTER TRÊN ĐẦU TRANG (CHỈ ÁP DỤNG ĐƯỢC VỚI KIỂU TRANG LÀ BOOK)
      \pagestyle{headings}

      \begin{document}
         \chapter{tên chaper}
         Nội dung văn bản
      \end{document}
   ![image](https://user-images.githubusercontent.com/79437149/119212602-b4e23c00-bae3-11eb-9b22-008d9beb4d9d.png)
   ![image](https://user-images.githubusercontent.com/79437149/119212609-bad81d00-bae3-11eb-9bbe-d4b2a78a6ac0.png)
   

  

   

      



      
   
         
  

      
   
   

   
   





   

   
   

 


   
    

