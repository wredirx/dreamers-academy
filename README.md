<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>The Dreamers Academy | Dr. Saifullah</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Segoe UI,sans-serif}

body{
background:linear-gradient(120deg,#0f2027,#203a43,#2c5364);
color:white;
}

/* TOP NOTICE */
.notice{
position:fixed;top:0;width:100%;
background:linear-gradient(90deg,cyan,#00ffd5);
color:#003;
text-align:center;
padding:12px;
font-weight:bold;
z-index:999;
animation:pulse 1.5s infinite alternate;
}
@keyframes pulse{from{letter-spacing:1px}to{letter-spacing:4px}}

header{
padding:90px 20px 40px;
text-align:center;
}
header h1{font-size:48px;text-shadow:0 0 20px cyan}
header h2{margin-top:10px}
header p{margin-top:6px}

section{padding:50px 8%}
.title{text-align:center;font-size:36px;color:cyan;margin-bottom:30px}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:rgba(255,255,255,0.12);
border-radius:20px;
padding:25px;
box-shadow:0 0 25px rgba(0,255,255,.3);
transition:.4s;
}
.card:hover{transform:scale(1.05);box-shadow:0 0 45px cyan}

.card img{
width:100%;
border-radius:15px;
margin-bottom:15px;
}

.about{text-align:center;font-size:19px;line-height:1.8}

/* FORM */
form{
max-width:600px;margin:auto;
background:rgba(255,255,255,0.12);
padding:30px;border-radius:20px;
}
input,select,textarea{
width:100%;padding:12px;margin:10px 0;border:none;border-radius:10px
}
button{
background:cyan;padding:14px;border:none;
border-radius:30px;font-weight:bold;cursor:pointer
}
button:hover{transform:scale(1.1)}

.location{text-align:center;font-size:20px}

/* WhatsApp Button */
.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:15px 20px;
border-radius:50px;
text-decoration:none;
font-weight:bold;
box-shadow:0 0 20px #25D366;
}

/* Footer */
footer{text-align:center;padding:25px;background:rgba(0,0,0,.3)}

/* Mobile */
@media(max-width:600px){
header h1{font-size:36px}
.title{font-size:28px}
}
</style>
</head>

<body>

<div class="notice">🔥 Admissions Open – The Dreamers Academy 🔥</div>

<header>
<h1>Dr. Saifullah</h1>
<h2>Physics • Chemistry • Biology</h2>
<p>📞 0322-2988936</p>
<p><b>The Dreamers Academy</b></p>
</header>

<section>
<div class="title">About Teacher</div>
<div class="about">
Dr. Saifullah is a dedicated science teacher teaching
Physics, Chemistry & Biology with focus on concept clarity,
board preparation and competitive exams.
</div>
</section>

<section>
<div class="title">Subjects</div>
<div class="cards">

<div class="card">
<img src="https://images.unsplash.com/photo-1581092580497-e0d23cbdf1dc">
<h3>🔬 Physics</h3>
<p>Numericals, Laws, Electricity, Magnetism</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1581093588401-22d8e1c1c3f4">
<h3>⚗ Chemistry</h3>
<p>Organic, Inorganic, Reactions</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1532187863486-abf9dbad1b69">
<h3>🧬 Biology</h3>
<p>Cell, Genetics, Human Systems</p>
</div>

</div>
</section>

<section>
<div class="title">Admission Form</div>
<form>
<input placeholder="Student Name" required>
<input placeholder="Contact Number" required>
<select>
<option>Select Subject</option>
<option>Physics</option>
<option>Chemistry</option>
<option>Biology</option>
</select>
<textarea placeholder="Message"></textarea>
<button>Submit</button>
</form>
</section>

<section>
<div class="title">Location</div>
<div class="location">
📍 Cattle Colony, near behind Magsi PSO<br>
The Dreamers Academy
</div>
</section>

<footer>
Future Admin Panel: Student records, admissions, results (Coming Soon)
</footer>

<a class="whatsapp"
href="https://wa.me/923222988936"
target="_blank">WhatsApp</a>

</body>
</html>
