#   
<!DOCTYPE html>  
<html lang="pt-BR">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>VCF HOLDING CAPITAL FINANCEIRO S/A - Cinemático</title>  
<style>  
/* Reset e básico */  
* { margin:0; padding:0; box-sizing:border-box; font-family: Arial, sans-serif; scroll-behavior: smooth;}  
body { background:#2b2b2b; color:#000; overflow-x:hidden; }  
  
/* Cabeçalho */  
header {  
  position: sticky; top:0; width:100%;  
  display:flex; justify-content: space-between; align-items:center;  
  padding:20px 50px; background: rgba(51,51,51,0.95);  
  z-index:1000; transition: all 0.3s ease;  
}  
header h1 { font-family:'Georgia', serif; font-size:28px; }  
nav a { color:#000; margin-left:20px; text-decoration:none; transition: all 0.3s ease; }  
nav a:hover { color:#555; }  
  
/* Hero Cinemático */  
.hero {  
  height:100vh; display:flex; flex-direction:column; justify-content:center; align-items:center;  
  text-align:center; position: relative; overflow:hidden;  
  background:#2b2b2b url('https://images.unsplash.com/photo-1581092795360-70b819e5b073?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=1080') no-repeat center/cover;  
}  
.hero::after {  
  content:''; position:absolute; top:0; left:0; width:100%; height:100%;  
  background: rgba(0,0,0,0.25);  
}  
.hero h2, .hero p, .hero button { position:relative; z-index:1; color:#fff; }  
  
/* Efeito typing do título */  
.hero h2 { font-size:3em; margin-bottom:20px; overflow:hidden; border-right:0.15em solid #fff; white-space:nowrap; animation: typing 3s steps(40) 1s forwards, blink 0.75s step-end infinite;}  
@keyframes typing { from { width:0; } to { width:100%; } }  
@keyframes blink { 50% { border-color: transparent; } }  
  
/* Hero texto e botão */  
.hero p { font-size:1.2em; margin-bottom:30px; animation: fadeInUp 2s ease forwards; opacity:0; }  
.hero button {  
  padding:15px 30px; font-size:1em; border:none; cursor:pointer;  
  background:#000; color:#fff; transition: all 0  
