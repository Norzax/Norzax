# Norza ( Hi im Luvn )






# My Stats


<script>
  // Kiểm tra xem giao diện của trình duyệt có đang ở chế độ dark không
  const prefersDarkMode = window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches;

  // Điều chỉnh hình ảnh dựa trên giao diện của trình duyệt
  const imagePrefix = prefersDarkMode ? "https://raw.githubusercontent.com/Norzax/Norzax/master/profile-summary-card-output/github_dark/" : "https://raw.githubusercontent.com/Norzax/Norzax/master/profile-summary-card-output/github/";
  
  // Cập nhật hình ảnh trong README
  document.querySelectorAll('img').forEach(img => {
    const src = img.getAttribute('src');
    if (src.startsWith('https://raw.githubusercontent.com/Norzax/Norzax/master/profile-summary-card-output/github')) {
      img.setAttribute('src', imagePrefix + src.split('/').pop());
    }
  });
</script>
