# Introduction-to-Cat-Species
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Trang giới thiệu về các giống mèo phổ biến">
    <title>Thế Giới Mèo - Giới Thiệu Các Giống Mèo</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            color: white;
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        nav {
            background-color: #333;
            padding: 1rem 0;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }
        
        nav li {
            margin: 0 1.5rem;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        nav a:hover {
            color: #ffcc00;
        }
        
        main {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }
        
        section {
            background-color: white;
            border-radius: 8px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        
        h2 {
            color: #2575fc;
            margin-bottom: 1rem;
            border-bottom: 2px solid #f0f0f0;
            padding-bottom: 0.5rem;
        }
        
        .cat-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }
        
        .cat-item {
            background-color: #f8f8f8;
            border-radius: 8px;
            padding: 1.5rem;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .cat-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .cat-item h3 {
            color: #6a11cb;
            margin-bottom: 0.5rem;
        }
        
        .cat-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 6px;
            margin: 1rem 0;
        }
        
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            margin-top: 2rem;
        }
        
        .external-link {
            display: inline-block;
            background-color: #2575fc;
            color: white;
            padding: 0.7rem 1.5rem;
            border-radius: 4px;
            text-decoration: none;
            margin-top: 1rem;
            transition: background-color 0.3s;
        }
        
        .external-link:hover {
            background-color: #6a11cb;
        }
        
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav li {
                margin: 0.5rem 0;
            }
            
            .cat-list {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Thế Giới Mèo</h1>
        <p>Khám phá vẻ đẹp và đặc điểm của các giống mèo phổ biến</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#intro">Giới thiệu</a></li>
            <li><a href="#breeds">Các giống mèo</a></li>
            <li><a href="#care">Chăm sóc</a></li>
        </ul>
    </nav>
    
    <main>
        <section id="intro">
            <h2>Giới thiệu về mèo</h2>
            <p>Mèo là một trong những thú cưng phổ biến nhất trên thế giới. Chúng không chỉ đáng yêu mà còn thông minh, độc lập và có tính cách riêng biệt. Có hàng trăm giống mèo khác nhau, mỗi giống có những đặc điểm ngoại hình và tính cách độc đáo.</p>
            <p>Trang web này sẽ giới thiệu đến bạn một số giống mèo phổ biến và được yêu thích nhất.</p>
        </section>
        
        <section id="breeds">
            <h2>Các giống mèo phổ biến</h2>
            <div class="cat-list">
                <div class="cat-item">
                    <h3>Mèo Ba Tư (Persian)</h3>
                    <img src="https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80" alt="Mèo Ba Tư" class="cat-image">
                    <p>Mèo Ba Tư có bộ lông dài và mượt, khuôn mặt phẳng và đôi mắt to tròn. Chúng có tính cách điềm đạm, thích được vuốt ve và thường thích cuộc sống trong nhà.</p>
                </div>
                
                <div class="cat-item">
                    <h3>Mèo Xiêm (Siamese)</h3>
                    <img src="https://images.unsplash.com/photo-1533738363-b7f9aef128ce?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80" alt="Mèo Xiêm" class="cat-image">
                    <p>Mèo Xiêm có thân hình thon dài, đôi mắt xanh hình quả hạnh và bộ lông ngắn với điểm nhấn màu sẫm ở mặt, tai, chân và đuôi. Chúng rất thông minh, tò mò và thích "trò chuyện" với chủ.</p>
                </div>
                
                <div class="cat-item">
                    <h3>Mèo Maine Coon</h3>
                    <img src="https://images.unsplash.com/photo-1577023311546-cdc07a8454d9?ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=80" alt="Mèo Maine Coon" class="cat-image">
                    <p>Maine Coon là một trong những giống mèo lớn nhất, có bộ lông dày và rậm giúp chống chịu thời tiết lạnh. Chúng thân thiện, hòa đồng và thường được gọi là "người khổng lồ hiền lành" của thế giới mèo.</p>
                </div>
            </div>
        </section>
        
        <section id="care">
            <h2>Cách chăm sóc mèo</h2>
            <p>Để mèo luôn khỏe mạnh và hạnh phúc, bạn cần lưu ý những điểm sau:</p>
            <ul>
                <li>Cho mèo ăn thức ăn chất lượng và phù hợp với độ tuổi</li>
                <li>Cung cấp nước sạch thường xuyên</li>
                <li>Chải lông thường xuyên, đặc biệt với các giống mèo lông dài</li>
                <li>Đưa mèo đi khám thú y định kỳ</li>
                <li>Chơi đùa và tương tác với mèo hàng ngày</li>
            </ul>
            
            <p>Để tìm hiểu thêm về cách chăm sóc mèo, hãy tham khảo:</p>
            <a href="https://www.hillspet.com.vn/cham-soc-thu-cung/cach-cham-soc-meo" class="external-link" target="_blank">Hướng dẫn chăm sóc mèo từ Hill's Pet</a>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 Thế Giới Mèo. Tất cả các quyền được bảo lưu.</p>
        <p>Trang web này được tạo ra cho mục đích học tập và tham khảo.</p>
    </footer>
</body>
</html>
