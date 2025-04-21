- 👋 Hi, I’m @Dede-04
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Dede-04/Dede-04 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!-- index.html -->
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Seyyar İçecek Menüsü</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Serinleten İçecekler</h1>
    <p>Cool Lime | Milkshake | Limonata</p>
  </header>
  <main>
    <section class="menu-category">
      <h2>Limonatalar</h2>
      <ul>
        <li>Klasik Limonata</li>
        <li>Naneli Limonata</li>
        <li>Çilekli Limonata</li>
      </ul>
    </section>
    <section class="menu-category">
      <h2>Milkshakeler</h2>
      <ul>
        <li>Çikolatalı Milkshake</li>
        <li>Vanilyalı Milkshake</li>
        <li>Çilekli Milkshake</li>
      </ul>
    </section>
    <section class="menu-category">
      <h2>Cool Lime</h2>
      <ul>
        <li>Cool Lime Classic</li>
        <li>Cool Lime Fesleğen</li>
        <li>Cool Lime Nane</li>
      </ul>
    </section>
  </main>
  <footer>
    <p>Mini Karavan | Tatlı Serinlikler</p>
  </footer>
</body>
</html>



/* styles.css */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: Arial, sans-serif;
  line-height: 1.5;
  color: #333;
  background: #f5f5f5;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
header {
  background: #76c7c0;
  color: #fff;
  text-align: center;
  padding: 1rem;
}
header h1 {
  font-size: 2rem;
  margin-bottom: 0.5rem;
}
main {
  flex: 1;
  padding: 1rem;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
}
.menu-category {
  background: #fff;
  padding: 1rem;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}
.menu-category h2 {
  margin-bottom: 0.75rem;
  color: #76c7c0;
}
.menu-category ul {
  list-style: none;
}
.menu-category li {
  padding: 0.5rem 0;
  border-bottom: 1px solid #eee;
}
.menu-category li:last-child {
  border-bottom: none;
}
footer {
  text-align: center;
  padding: 0.75rem;
  background: #ddd;
}
