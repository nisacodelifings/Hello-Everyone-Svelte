

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono&display=swap');
:root {
  --pink: #FF7591;
  --ungu: #BE9EDF;
}
html, body {
    margin: 0;
    padding: 0;
    font-family: 'Roboto Mono', monospace;
}
p::selection, a::selection, h1::selection {
    background: var(--ungu);
}
nav{
    margin: 0;
    padding: 0;
    color: #fff;
    padding: 20px;
    display: flex;
    justify-content: center;
    flex-direction: row;
    background: var(--pink);    
}
nav > img{
    width: auto;
    height: 180px;
}
.main{
    background: var(--ungu); 
}
.kanan{
    display: flex;
    flex-direction: column;
}

</style>

<nav>
        <div class="kanan">
            <h1>Hi, Simpleazy!</h1>
        <p>Aku adalah Asisten Bendahara Sekolah mu, yang siap bantuin kamu di Segala bentuk pencatatan atau pembungkuan keuangan kelas.. &#128176;</p>
        </div>        
        <img src="https://res.cloudinary.com/codelifings/image/upload/v1596531968/ice-cream_tv7wto.png">
        </nav>
				<nav class="main">
          <div class="kanan">
              <h1>Hi, Simpleazy!</h1>
          <p>Aku adalah Asisten Bendahara Sekolah mu, yang siap bantuin kamu di Segala bentuk pencatatan atau pembungkuan keuangan kelas.. &#128176;</p>
          </div>        
          <img src="https://res.cloudinary.com/codelifings/image/upload/v1596531968/ice-cream_tv7wto.png">
        </nav>