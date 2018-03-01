#include<stdio.h>
#include<stdlib.h>

int const MAXTAM = 1000;

int Pilha[MAXTAM];
int Topo;

void Pilha_Construct(){
    Topo = -1;
	 
}
bool Pilha_Vazia(){
	 if (topo == -1);     //verifica se pilha está vazia
	 return true;
		else 
		return false;
 }
 int tamanho{
 	 return topo+1;
 }
bool Pilha_cheia(){
	 if (topo== MAXTAM-1);     //verifica se pilha está vazia
	 return true;
		else 
		return false;
 } 
 
	 
void Pilha_Push(){
	 if(Pilha cheia() ){  // não consigo iserir valor 
     return false;
	 }else{
         topo++;
         Pilha[topo] =  valor;
          return true;
}
	 }
	 
bool Pilha_Pop(int & valor){  //desempilhar
	 if (Pilha_vazia() ){     //verifica se pilha está vazia
	 return false;
		}else{
			  valor=Pilha[topo];
			  topo--; 
		return true;
  }
	 
} 

bool Pilha_consulta(int & valor) { //só tem o que é do topo da pilha 
	 if(Pilha_vazia() ){
       return false;
	   }else{
	   		 valor=Pilha[topo]
	   		 return true;
}
	 }
int main(){
	
	int valor;
	
	Pilha_Construct();
	Pilha_Push(5);
	Pilha_Push(4);
	Pilha_Push(3);
	Pilha_Push(2);
	Pilha_Push(1);	
	
	
//Pilha_Pop(valor);
//printf("\n %d \n", valor);

//printf("\n\n quantd. itens da pilha: %d \n\n\n", valor);
	
	
}
