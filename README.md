# Norza ( Hi im Luvn )






# My Stats
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README</title>
    <style>
        /* CSS cho nội dung light mode */
        .light-mode .dark-images {
            display: none;
        }

        /* CSS cho nội dung dark mode */
        .dark-mode .light-images {
            display: none;
        }
    </style>
</head>
<body>
    <!-- Đoạn mã HTML để hiển thị hình ảnh -->
    <div class="light-images">
        <img src="https://raw.githubusercontent.com/Norzax/HiimLuvn/master/profile-summary-card-output/github/0-profile-details.svg" alt="Profile Details">
        <img src="https://raw.githubusercontent.com/Norzax/HiimLuvn/master/profile-summary-card-output/github/1-repos-per-language.svg" alt="Repos per Language">
        <img src="https://raw.githubusercontent.com/Norzax/HiimLuvn/master/profile-summary-card-output/github/2-most-commit-language.svg" alt="Most Commit Language">
        <img src="https://raw.githubusercontent.com/Norzax/HiimLuvn/master/profile-summary-card-output/github/3-stats.svg" alt="Stats">
        <img src="https://raw.githubusercontent.com/Norzax/HiimLuvn/master/profile-summary-card-output/github/4-productive-time.svg" alt="Productive Time">
    </div>
    <div class="dark-images">
        <img src="https://raw.githubusercontent.com/Norzax/HiimLuvn/master/profile-summary-card-output/github_dark/0-profile-details.svg" alt="Profile Details">
        <img src="https://raw.githubusercontent.com/Norzax/HiimLuvn/master/profile-summary-card-output/github_dark/1-repos-per-language.svg" alt="Repos per Language">
        <img src="https://raw.githubusercontent.com/Norzax/HiimLuvn/master/profile-summary-card-output/github_dark/2-most-commit-language.svg" alt="Most Commit Language">
        <img src="https://raw.githubusercontent.com/Norzax/HiimLuvn/master/profile-summary-card-output/github_dark/3-stats.svg" alt="Stats">
        <img src="https://raw.githubusercontent.com/Norzax/HiimLuvn/master/profile-summary-card-output/github_dark/4-productive-time.svg" alt="Productive Time">
    </div>

    <!-- Đoạn mã JavaScript để xác định chế độ giao diện -->
    <script>
        // Kiểm tra nếu chế độ giao diện là dark, thêm class "dark-mode" vào thẻ body
        if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
            document.body.classList.add('dark-mode');
        } else {
            document.body.classList.add('light-mode');
        }
    </script>
</body>
</html>
