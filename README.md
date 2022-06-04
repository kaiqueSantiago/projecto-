# projecto-
Atividade 1
import java.util.Scanner;

public class Prova_Ex1{
    public static void main (String[] args){
        Scanner scan = new Scanner(System.in);
           int  Valor,Mínimo,Maximo;
              System.out.println("Coloque o valor = ");
              Valor= scan.nextInt();
              System.out.println("Coloque o valor maximo = ");
              Maximo= scan.nextInt();
              System.out.println("Coloque o valor minimo = ");
              Mínimo= scan.nextInt();
      
              System.out.println(Clamp(Valor,Mínimo,Maximo));
      
          }
          public static int Clamp(int Valor, int Mínimo, int Maximo){
      
          if (Valor<Mínimo){
            return Mínimo;
            }
              else if (Valor>Maximo){
            return Maximo;
              }
              else{
            return Valor;
            }
      
          }
      
      }
