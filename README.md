# raphaellaoliveira.github.io
<!doctype html>
<html lang="pt-BR">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Raphaella Oliveira — QA Pleno</title>
<meta name="description" content="Raphaella Oliveira — QA Pleno que adora testar, explorar novos mundos digitais e garantir a melhor experiência. Caçadora de bugs, em evolução aprendendo automação." />


<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Raleway:wght@300;400;600&display=swap" rel="stylesheet">


<style>
:root{
--bg-1: #0b0f14; /* very dark */
--bg-2: #0f1720;
--accent-1: #7c4dff; /* purple */
--accent-2: #34d1ff; /* cyan */
--muted: #98a0aa;
--card: rgba(255,255,255,0.03);
--glass: rgba(255,255,255,0.04);
}
*{box-sizing:border-box}
html,body{height:100%}
body{
margin:0;
font-family: 'Raleway', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
background: radial-gradient(1200px 600px at 10% 10%, rgba(124,77,255,0.06), transparent),
radial-gradient(900px 400px at 90% 90%, rgba(52,209,255,0.04), transparent),
linear-gradient(180deg,var(--bg-1),var(--bg-2));
color:#e6eef6;
-webkit-font-smoothing:antialiased;
-moz-osx-font-smoothing:grayscale;
padding:30px 18px;
}


.container{max-width:1000px;margin:0 auto}


/* Header / Hero */
.hero{
display:grid;
grid-template-columns:1fr 320px;
gap:24px;
align-items:center;
margin-bottom:28px;
}
.card{
background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
border:1px solid rgba(255,255,255,0.04);
padding:22px;
border-radius:14px;
box-shadow: 0 6px 18px rgba(2,6,12,0.6);
}


h1{font-family:'Orbitron', sans-serif;margin:0 0 6px;font-weight:400;font-size:24px}
.subtitle{color:var(--muted);margin:0 0 14px}
.tagline{font-size:15px;line-height:1.4}


.avatar{
height:140px;width:140px;border-radius:12px;overflow:hidden;border:1px solid rgba(255,255,255,0.06);
display:flex;align-items:center;justify-content:center;background:linear-gradient(135deg,var(--accent-1),var(--accent-2));
}
.avatar img{width:100%;height:100%;object-fit:cover}


.meta{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
.pill{background:var(--glass);padding:6px 10px;border-radius:999px;font-size:13px;color:var(--muted)}


/* Sections */
.grid{display:grid;grid-template-columns:1fr 340px;gap:20px}
.about p{color:#dfe9f7}


/* Projects */
.projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:14px;margin-top:12px}
