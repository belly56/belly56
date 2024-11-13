/* Reset global */
* {
    
* {
    mar

* {
margin: 0;
    
    padd

   
padding: 0;
    
    box-sizin

    box
box-sizing: border-box;
}

/* Tipografia e fundo */
body {
    
    
font-family: "Chakra Petch", sans-serif;
    
    f
font-size: 16px;
    color: white;
    
    backgrou

    bac

  
background: black;
}

/* Cabeçalho */

heade
header {
    
    borde
border-bottom: 2px solid rgb(42, 122, 228);
    
 
padding: 20px;
    
    fo

  
font-size: 2rem;
    
    col

  
color: rgb(42, 122, 228);
    
    text-al

    te

 
text-align: center;
}


}

/
/* Chamada */
.chamada {
    
    backgro
background: rgb(184, 156, 213);
    
    pa

  
padding: 10% 5%;
    
    
display: flex;
    
    ju
justify-content: center;
    
    align-item

    align

    
align-items: center;
    
    text-alig

    te
text-align: center;
}


}
.chamada-texto {
    
    max-wid

   
max-width: 800px;
}


}
/* Categorias de Vídeos */
.categoria-videos {
    
    d
display: flex;
    
    o

 
overflow-x: auto;
    
    ga
gap: 10px;
    
    align-it
align-items: center;
    
    
padding: 10px;
}

.categoria-videos img {
    
    opaci

   
opacity: 0.5;
    
 
height: 200px;
    
 
flex-shrink: 0;
    
    transit
transition: opacity 0.3s, transform 0.3s, border 0.3s;
}


}
.categoria-videos img:hover {
    
    op
opacity: 1;
    
    bor
border: 3px solid rgb(42, 122, 228);
    
    t
transform: scale(1.05);
}

.categoria h2 {
    
   
color: rgb(42, 122, 228);
}


}
/* Responsividade */
@media (max-width: 1024px) {
    
    .
.categoria-videos img {
        
        he

  
height: 150px;
    }
}

@media (max-width: 768px) {
    body {
        
        fon
font-size: 14px;
    }

    
    }

    

   
header {
        font-size: 1.5rem;
    }

    .categoria-videos {
        
     
flex-direction: column;
    }

    
    }
.chamada-texto {
        
      
font-size: 1.1rem;
    }
}
