<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Báo Tường</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Chào Mừng Đến Với Báo Tường</h1>
    </header>
    <main>
        <section class="news">
            <h2>Tin Tức Mới Nhất</h2>
            <article>
                <h3>Tiêu Đề Bài Viết 1</h3>
                <p>Nội dung bài viết 1...</p>
            </article>
            <article>
                <h3>Tiêu Đề Bài Viết 2</h3>
                <p>Nội dung bài viết 2...</p>
            </article>
        </section>
        <section class="submit-news">
            <h2>Gửi Tin Tức</h2>
            <form id="newsForm">
                <label for="title">Tiêu Đề:</label>
                <input type="text" id="title" name="title" required>
                <label for="content">Nội Dung:</label>
                <textarea id="content" name="content" required></textarea>
                <button type="submit">Gửi</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Báo Tường</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>
