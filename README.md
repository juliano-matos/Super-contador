# <! DOCTYPE html >
< html  lang = " pt-BR " >
< cabeça >
    < meta  charset = " UTF-8 " >
    < meta  name = " viewport " content = " width = device-width, initial-scale = 1.0 " >
    < title > Super Contador </ title >
    < link  rel = " stylesheet " href = " estilo.css " >
</ head >
< corpo > 
    < cabeçalho >
        < h1 > Vamos contar! </ h1 >
    </ header >
    < seção >
< div  id = " dados " >
< p > início: < input  type = " number " name = " inicio " id = " txti " > </ p >
< p > Fim: < input  type = " number " name = " fim " id = " txtf " > </ p >
< p > Passo: < input  type = " number " name = " passo " id = " txtp " >   </ p >
< p >  < input  type = " button " value = " Contar " onclick = " contar () " > </ p >
</ div >
< div  id = " res " >
Preparando a contagem ...
</ div >
</ seção >
< rodapé >
        < p > & copy; CursoemVídeo </ p >
    </ rodapé >
    < script  src = " script.js " > </ script >
</ body >
</ html >
