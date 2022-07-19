# Nao-entendi-a-logica-

execução do código abaixo irá escrever os números pares contidos na matriz:

programa

{

               inclua biblioteca Util

              

               funcao inicio()

               {

                               inteiro matriz[3][3] = {{1,2,3},{3,4,4},{4,4,4}}

                               para(inteiro x=0;x<Util.numero_linhas(matriz);x++){

                                               para(inteiro y=0;y<Util.numero_colunas(matriz);y++){

                                                               se(x%2==0 e y%2==0){

                                                                              escreva(matriz[x][y])

                                                               }

                                               }

                               }

               }

}
