# Calculator
Calculadora simples.
public static void main(String[] args) {
   
Scanner sc=new Scanner(System.in);
System.out.println ("Digite o número 01: ");
double num1=sc.nextDouble();
System.out.println ("Digite o número 02: ");
double num2=sc.nextDouble();
System.out.print("Escolha uma das opções: \n 01: Somar \n 02: Subtrair \n 03: Multiplicar  \n 04: Dividir: \n Opção escolhida: ");
int num3= sc.nextInt();

switch (num3)
{

    case 1:
        resultado = num1+num2;
        break;
    case 2:
        resultado = num1-num2;
        break;
    case 3:
        resultado = num1*num2;
        break;
    case 4:
        resultado = num1/num2;
        break;
        
}
System.out.println("Resultado igual a: "+ resultado);
