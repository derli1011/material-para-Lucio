# material-para-Lucio
material em css atributos

Usar visual studio code:



<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
   
    <title>Document</title>

<style>

body{
    /*
    background-color: tomato;
    background-image: url("download.jfif");
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: right top;*/

    /* Observação: as cinco linhas de background acima podem ser criados para atribuir a página 
    cor, url(anexar imagem a página bastando abrir e fechar parentese e aspas que ja aparece 
    as imagens salvas). A linha abaxo é mesma coisa so que resumido em uma linha*/

    background: url("download.jfif") tomato no-repeat fixed right top;

}
</style>
<p></p>
S



</head>
<body>
    
</body>
</html>

.........................................................................

atributo cores:


<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
 
    <title>exemplo</title>
<style>

p{
color: tomato;


}
.corAzul{
color: blue;

}
#marcaTexto{
    background-color: yellow;
    color: black;

}


</style>


</head>
<body>

<h1>Exemplos de propriedades color</h1>
<p>
imsun.loremimsun.loremimsun.loremimsun.loremimsun.loremimsun.
loremimsun.loremimsun.loremimsun.loremimsun.lorem

imsun.loremimsun.loremimsun.loremimsun.loremimsun.lore
</p>

<p class="corAzul">
    imsun.loremimsun.loremimsun.loremimsun.loremimsun.loremimsun.
    loremimsun.loremimsun.loremimsun.loremimsun.lorem
    
    imsun.loremimsun.loremimsun.loremimsun.loremimsun.lore
    </p>
    
    
    <p id="marcaTexto">
        imsun.loremimsun.loremimsun.loremimsun.loremimsun.loremimsun.
        loremimsun.loremimsun.loremimsun.loremimsun.lorem
        
        imsun.loremimsun.loremimsun.loremimsun.loremimsun.lore
  </p>
        
        
           
    
</body>
</html>

.................................................

atributo fonte usando links:

<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
       <title>Exemplos de fontes</title>

       <link rel="preconnect" href="https://fonts.googleapis.com">
       <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
       <link href="https://fonts.googleapis.com/css2?family=Square+Peg&display=swap" rel="stylesheet">


       <style>
.textoA{

font-style: italic;

}
.negrito{
    font-weight: bold;

}
 .smallcaps{
font-variant: small-caps;

 }
 .familiaFonte{
font-family: 'courier New' , courier, monospace;

 }
/*Tamanho em píxel mesmo*/
 #pixel{
font-size: 20px;


 }
 /*tem o tamanho de 16 pixel cada EM*/
 #em{
font-size: 2 em;
 }
/*tamanho do display*/
 #vw{
     font-size: 10vw;

 }
 .fontGoogle{

font-family: 'Square Peg', cursive;
font-size:40px;

 }




       </style>
</head>
<body>

    <h1>Exemplos de fontes</h1>
    <p>Tamanho em pixel</p>
    <p>Tamanho em EM</p>
    <p>Tamanho em Viewport</p>





<p >
ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem

</p>

   
<p calss="italic">
    ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
    ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
    ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
    ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
    
    </p>
    
    

   
    <p class="smallcaps" >
        ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
        ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
        ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
        ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
        
        </p>
        
        
        <p font-family>
            ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
            ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
            ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
            ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
            
            </p>
            <p >
                ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
                ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
                ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
                ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
                
                </p>
                            
                <p  fontGoogle>
                    ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
                    ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
                    ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
                    ipsum.loremipsum.loremipsum.loremipsum.loremipsum.loremipsum.lorem
                    
                    </p>
              
</body>
</html>

............................................................................
Usando link

<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
  
    <title>Document</title>

<style>
a:link{
color: darkgreen;
text-decoration: none;
}
a:hover{
background-color: yellowgreen;
color: blanchedalmond;
}
a:active{
    background-color: tomato;   
    text-decoration: uppercase;
    color: blanchedalmond;
}

a:visited{

color: darkgreen;
text-decoration: none;


}

</style>

</head>
<body>
    
<h1>Exemplos de estilos para links</h1>

<a href="#">Ir para a páginan principal</a>

<a href="#">Ir para a páginan principal</a>


</body>
</html>

..............................................................
tabela :

<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    
    <title>Document</title>
    <style>
        table, th, td{
    
    border: solid 1px;
    border-collapse: collapse;
        }
    
    table{
    width: 400px;
    height: 50px;
    
    }
    th{
        height: 10px;
        text-align: left;
        vertical-align: middle;
    }
    td{
    
    }
    .tabelaZebrada th{
        text-align: left;
        vertical-align: middle;
        background-color: rgb(32, 178, 124)
        color : #FFFFFF;
    }

.tabelaZebrada td{
    borderr:solid silver 1px;

}

.tabelaZebrada tr:hover{
backgroud-color: tomato;




}
.zebra{
    background-color: rgb(212, 212,212);
    
}


    
    </style>







</head>
<body>
    
    <div style="overflow-x: auto;">
        <table class="tabelaZebrada">
       
       <tr>
       
       <th>Company</th>
       <th>Contact</th>
       <th>Country</th>
       
       </tr>
       <tr class="zebra">
       
        <th>Company</th>
        <th>Contact</th>
        <th>Country</th>
        
        </tr>
       <tr>
       <td>alfreds Futterkisle</td>
       <td>Maria Anders</td>
       <td>Germany</td>
    
       </tr>
       
           </table>
       
       </div>

</body>
</html>




















