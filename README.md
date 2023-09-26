<!DOCTYPE html>
<html>
<head>
  <title>RIZKY EKA HARYADI's Portfolio</title>
  <style>
    /* Tambahkan sedikit gaya untuk membuat tampilan lebih baik */
    button {
      background-color: #007BFF;
      color: #fff;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
    }
    
    ul {
      list-style-type: none;
      padding: 0;
    }
    
    ul li {
      margin-bottom: 5px;
    }
    
    ul ul {
      padding-left: 20px;
    }
  </style>
</head>
<body>
  <h1 align="center">Hi 👋, I'm RIZKY EKA HARYADI</h1>
  <h3 align="center">Software Developer from Indonesia</h3>

  <!-- Tambahkan tombol dropdown -->
  <button onclick="toggleTechStack()">Tech Stack</button>

  <!-- Tambahkan daftar Tech Stack ke dalam div yang dapat di-toggle -->
  <div id="techStackList" style="display: none;">
    <ul>
      <!-- Daftar Tech Stack -->
    </ul>
  </div>

  <!-- Tambahkan bagian GitHub Stats -->
  <h2>📊 GitHub Stats:</h2>
  <img src="https://github-readme-stats.vercel.app/api?username=Rizky28eka&theme=dark&hide_border=false&include_all_commits=true&count_private=true" alt="GitHub Stats">
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Rizky28eka&theme=dark&hide_border=false" alt="GitHub Streak Stats">
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rizky28eka&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact" alt="Top Languages">
  
  <!-- Tambahkan bagian GitHub Trophies -->
  <h2>🏆 GitHub Trophies:</h2>
  <img src="https://github-profile-trophy.vercel.app/?username=Rizky28eka&theme=dark&no-frame=false&no-bg=false&margin-w=4" alt="GitHub Trophies">
  
  <!-- Tambahkan bagian Random Dev Quote -->
  <h2>✍️ Random Dev Quote:</h2>
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="Random Dev Quote">
  
  <!-- Tambahkan bagian Top Contributed Repo -->
  <h2>🔝 Top Contributed Repo:</h2>
  <img src="https://github-contributor-stats.vercel.app/api?username=Rizky28eka&limit=5&theme=dark&combine_all_yearly_contributions=true" alt="Top Contributed Repo">

  <!-- Tambahkan bagian Socials -->
  <h2>🌐 Socials:</h2>
  <a href="https://instagram.com/rzkyhryd._">
    <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white" alt="Instagram Badge">
  </a>
  <a href="https://linkedin.com/in/rizky28eka">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn Badge">
  </a>
  <a href="https://stackoverflow.com/users/12039478">
    <img src="https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white" alt="Stack Overflow Badge">
  </a>
  <a href="https://tiktok.com/@iwillyousomuch">
    <img src="https://img.shields.io/badge/TikTok-%23000000.svg?logo=TikTok&logoColor=white" alt="TikTok Badge">
  </a>
  <a href="https://twitter.com/duaribuempaat">
    <img src="https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white" alt="Twitter Badge">
  </a>
  
  <!-- Tambahkan bagian Visit Count -->
  <br/>
  <a href="https://visitcount.itsvg.in">
    <img src="https://visitcount.itsvg.in/api?id=Rizky28eka&icon=1&color=12" alt="Visit Count">
  </a>

  <script>
    // Fungsi untuk menampilkan atau menyembunyikan daftar Tech Stack
    function toggleTechStack() {
      var techStackList = document.getElementById("techStackList");
      if (techStackList.style.display === "none") {
        techStackList.style.display = "block";
      } else {
        techStackList.style.display = "none";
      }
    }
  </script>

</body>
</html>
