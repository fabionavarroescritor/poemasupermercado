# poemasupermercado
programação para o poema Supermercado

Observação: os parâmetros numéricos aqui foram testados para que a palavra tivesse visualização completa

void setup() {     //cria o fundo fixo
  size (1020, 690); 
  background (#000000);
  PFont fonte;
  fonte = loadFont ("VTCSuperMarketSaleDisplay-48.vlw"); //carrega a fonte e edita o texto base
  textFont (fonte);
  text ("corre", 100, 100, 100, 100); 
  fill (#1E0FCE);
 
}
  
  void keyPressed(){    //ao apertar a tecla muda o fundo 
    if (key == 'b') {
      background (#000000);
    } else if (key == 'r'){
      background (#000000); 
    } else if (key == 'g');
    background (#000000); 
  }
  

  
 void draw(){
   //fill  (random(0,255), random(0,255), random(0,255)); //cria associação com o mouse, ao apertar a tecla do mouse com o teclado
   textSize (15);                                              //muda (nesse caso) a cena
   text ("corre", mouseX, mouseY, 100,100);
   //text (mouseX, mouseY, 50,50); 
 }
      
