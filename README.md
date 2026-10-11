<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Mudabbir | Spidey Dev</title>
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:system-ui;background:#06060a;color:white}
nav{position:fixed;top:0;width:100%;background:#000000cc;backdrop-filter:blur(10px);display:flex;justify-content:space-between;padding:14px 20px;z-index:99;border-bottom:1px solid #222}
nav b{color:#e11d25}
nav span{margin-left:14px;cursor:pointer;opacity:0.7;font-size:14px}
nav span.active{opacity:1;color:#e11d25;font-weight:bold}
.page{display:none;min-height:100vh;padding:90px 20px 40px;animation:fade .4s}
.page.active{display:block}
@keyframes fade{from{opacity:0;transform:translateY(10px)}to{opacity:1}}
.hero{text-align:center;padding-top:30px}
.spidey-img{width:220px;height:220px;margin:0 auto;border-radius:50%;border:5px solid #e11d25;box-shadow:0 0 50px #e11d25;object-fit:cover;transition:.3s}
.spidey-img:hover{transform:scale(1.08) rotate(3deg)}
h1{font-size:42px;margin:15px 0 5px}
h1 b{color:#e11d25}
.card
