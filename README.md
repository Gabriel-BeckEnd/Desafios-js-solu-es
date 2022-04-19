# Desafios-js-solu-es

/*


Faça um programa que coloque o valor lido na primeira posição
de um vetor N[10]. Em cada seguinte, coloque o dobro do valor da posição
posição anterior. Por exemplo, se o valor lido for 1, os valores do vetor devem
ser 1,2,4,8 e assim sucessivamente. Mostre o vetor em seguida.
 


ENTRADA
Uma entrada contém um valor inteiro (V<=50).


SAÍDA
Para cada posição do vetor, escreva "N[i] = X", onde i é a posição do vetor e X
é o valor armazenado na posição i. O primeiro número do vetor N (N[0]) irá receber
o valor de V.
 
*/

importar  java . io . IOException ;
importar  java . útil . Scanner ;

 classe  pública URI  1173 {
	
    public  static  void  main ( String [] args ) lança  IOException {
         Leitor de scanner = novo  Scanner ( System . in );
        int [] N = novo  int [ 10 ];
        N [ 0 ] = leitor . nextInt ();
        for ( int  i = 1 ; i < 10 ; i ++) {
            N [ i ] = N [ i - 1 ]* 2 ;
        }
        for ( int  i = 0 ; i < 10 ; i ++) {
            Sistema . fora . println ( "N[" + i + "] = " + N [ i ]);
        }
    }
	
}
