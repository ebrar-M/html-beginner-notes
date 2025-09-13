![Stars](https://img.shields.io/github/stars/kullaniciAdi/repositoriAdi?style=flat&logo=github)
![Forks](https://img.shields.io/github/forks/kullaniciAdi/repositoriAdi?style=flat&logo=github)
![Last Commit](https://img.shields.io/github/last-commit/kullaniciAdi/repositoriAdi?color=brightgreen)
![HTML](https://img.shields.io/badge/HTML-5-orange)

**---**

## 🌍 Languages
- 🇹🇷 [Türkçe](#-tr-türkçe)
- 🇬🇧 [English](#-gb-english)

---

## 🇹🇷 TR Türkçe

# 🌐 HTML Temelleri - Yeni Başlayanlar İçin Notlar  

## 1. 📖 HTML Nedir?
- **HTML (HyperText Markup Language)** → Web sayfalarının iskeletidir.  
- Tarayıcıya *“şunu başlık yap, bunu paragraf yap, şu resmi göster”* gibi talimatlar verir.  
- **CSS 🎨** tasarımı, **JavaScript ⚡** etkileşimi ekler ama HTML olmadan ikisi de işe yaramaz.  

---

## 2. 🏗️ HTML Sayfa Yapısı
Her HTML dosyası genelde bu iskeletle başlar:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Benim İlk Sayfam</title>
</head>
<body>
  <h1>Merhaba Dünya!</h1>
  <p>İlk HTML sayfamı yazıyorum 🚀</p>
</body>
</html>
```

📌 Açıklama:
- `<!DOCTYPE html>` → HTML5 kullanıldığını belirtir.  
- `<html>` → Sayfanın kapsayıcısıdır.  
- `<head>` → Ayarlar, meta bilgiler ve başlık içerir.  
- `<body>` → Kullanıcıya görünen içeriktir.  

---

## 3. 🔑 Temel Etiketler

### Başlıklar 🏷️
```html
<h1>En büyük başlık</h1>
<h2>İkinci seviye başlık</h2>
<h6>En küçük başlık</h6>
```

### Paragraflar ✍️
```html
<p>Bu bir paragraf.</p>
```

### Linkler 🔗
```html
<a href="https://github.com/">GitHub'a git</a>
```

### Resimler 🖼️
```html
<img src="resim.jpg" alt="Açıklama metni" width="300">
```

### Listeler 📋
```html
<ul>
  <li>Liste 1</li>
  <li>Liste 2</li>
</ul>

<ol>
  <li>Sıralı liste 1</li>
  <li>Sıralı liste 2</li>
</ol>
```

---

## 4. 🛠️ Önemli HTML Özellikleri (Attributes)
- `href` → link adresi 🔗  
- `src` → resim veya medya yolu 🖼️  
- `alt` → görme engelliler için açıklama ♿  
- `id` → eleman kimliği 🆔  
- `class` → gruplama 🏷️  

---

## 5. 📬 Formlar
Kullanıcıdan bilgi almak için:  

```html
<form action="/gonder" method="POST">
  <label for="isim">İsim:</label>
  <input type="text" id="isim" name="isim">
  
  <label for="sifre">Şifre:</label>
  <input type="password" id="sifre" name="sifre">
  
  <button type="submit">Gönder</button>
</form>
```

---

## 6. 🧩 Semantik HTML
Modern webde **anlamlı etiketler** kullanılır:  

```html
<header>Üst kısım (logo, menü)</header>
<nav>Gezinme menüsü</nav>
<main>Sayfanın ana içeriği</main>
<article>Makale ya da içerik</article>
<section>Kapsayıcı bölümler</section>
<footer>Alt kısım</footer>
```

✨ SEO ve erişilebilirlik için çok önemlidir!  

---

## 7. ⚠️ En Çok Yapılan Hatalar
❌ Kapatılmamış etiketler (`<p>` açıp kapatmamak).  
❌ `alt` yazısı koymadan resim kullanmak.  
❌ Her şeyi `<div>` içine yazmak (semantik HTML’i yok saymak).  
❌ `<br>` ile boşluk bırakmaya çalışmak (CSS kullan).  

---

## 8. 💡 İpuçları & Tavsiyeler
- Kod yazarken **girintilere (indentation)** dikkat et ➡️ düzen önemli.  
- Kodlarını denemek için [CodePen](https://codepen.io/) 🔥 veya [JSFiddle](https://jsfiddle.net/) kullan.  
- Her yeni etiketi öğrenince küçük bir demo yap 👩‍💻.  
- Unutma: HTML bir programlama dili değil, **işaretleme dili**.  

---

## 🎯 Mini Alıştırma
Aşağıdaki kodu yaz, tarayıcıda aç:  

```html
<!DOCTYPE html>
<html>
<head>
  <title>Kişisel Sayfam</title>
</head>
<body>
  <h1>Benim Adım Ebrar 😎</h1>
  <p>Bilgisayar programcılığı okuyorum ve HTML öğreniyorum.</p>
  <img src="profil.jpg" alt="Profil Fotoğrafım" width="200">
  <a href="https://github.com/">GitHub Profilim 🔗</a>
</body>
</html>
```

---

## 📌 Son Söz
HTML öğrenmek LEGO 🧱 oynamak gibidir.  
Parçaları tanıyıp doğru yerlere koyarsan, istediğin web sayfasını inşa edebilirsin.  
CSS 🎨 ve JavaScript ⚡ geldiğinde bu yapı çok daha güçlü hale gelecek.  
Ama temeli sağlam atmak için HTML’i **iyi kavramak şart**. 🚀  

---

## 🇬🇧 GB English

# 🌐 HTML Basics - Notes for Beginners

## 1. 📖 What is HTML?
- **HTML (HyperText Markup Language)** → It's the skeleton of web pages.
- It gives instructions to the browser, such as *"make this a title, make this a paragraph, show this image."*
- **CSS 🎨** adds design, **JavaScript ⚡** adds interactivity, but neither is useful without HTML.

---

## 2. 🏗️ HTML Page Structure
Every HTML file generally begins with this structure:

```html
<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My First Page</title>
</head>
<body>
<h1>Hello World!</h1>
<p>I'm writing my first HTML page 🚀</p>
</body>
</html>
```

📌 Description:
- `<!DOCTYPE html>` → Indicates that HTML5 is used.
- `<html>` → The page container.
- `<head>` → Contains settings, meta information, and the title.
- `<body>` → The content visible to the user.

---

## 3. 🔑 Basic Tags

### Headings 🏷️
```html
<h1>Largest heading</h1>
<h2>Second-level heading</h2>
<h6>Smallest heading</h6>
```

### Paragraphs ✍️
```html
<p>This is a paragraph.</p>
```

### Links 🔗
```html
<a href="https://github.com/">Go to GitHub</a>
```

### Images 🖼️
```html
<img src="picture.jpg" alt="Description text" width="300">
```

### Lists 📋
```html
<ul>
<li>List 1</li>
<li>List 2</li>
</ul>

<ol>
<li>Ordered list 1</li>
<li>Ordered list 2</li>
</ol>
```

---

## 4. 🛠️ Important HTML Attributes
- `href` → link address 🔗
- `src` → image or media path 🖼️
- `alt` → description for the visually impaired ♿
- `id` → element ID 🆔
- `class` → grouping 🏷️

---

## 5. 📬 Forms
To collect information from the user:

```html
<form action="/gonder" method="POST">
<label for="name">Name:</label>
<input type="text" id="name" name="name">

<label for="password">Password:</label>
<input type="password" id="password" name="password">

<button type="submit">Submit</button>
</form>
```

---

## 6. 🧩 Semantic HTML
The modern web uses **meaningful tags**:

```html
<header>Header (logo, menu)</header>
<nav>Navigation menu</nav>
<main>Main content of the page</main>
<article>Article or content</article>
<section>Container sections</section>
<footer>Footer</footer>
```

✨ Crucial for SEO and accessibility!

---

## 7. ⚠️ Most Common Mistakes
❌ Unclosed tags (not opening or closing `<p>`).
❌ Using images without `alt` text.
❌ Writing everything in `<div>` (ignoring semantic HTML).
❌ Trying to space with `<br>` (using CSS).

---

## 8. 💡 Tips & Recommendations
- Pay attention to **indentation** when writing code ➡️ layout is important.
- Use [CodePen](https://codepen.io/) 🔥 or [JSFiddle](https://jsfiddle.net/) to test your code.
- Make a small demo 👩‍💻 after learning each new tag.
- Remember: HTML is not a programming language, it's a **markup language**.

---

## 🎯 Mini Exercise
Type the following code and open it in your browser:

```html
<!DOCTYPE html>
<html>
<head>
<title>My Personal Page</title>
</head>
<body>
<h1>My Name is Ebrar 😎</h1>
<p>I'm studying computer programming and learning HTML.</p>
<img src="profil.jpg" alt="My Profile Photo" width="200">
<a href="https://github.com/">My GitHub Profile 🔗</a>
</body>
</html>
```

---

## 📌 Final Word
Learning HTML is like playing LEGO 🧱.
If you recognize the pieces and put them in the right places, you can build any web page you want.
This structure will become much more powerful when CSS 🎨 and JavaScript ⚡ arrive.
But to lay a solid foundation, a good grasp of HTML is essential. 🚀

---
