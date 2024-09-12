using System;

int nota1 =6 ;
int nota2 =8 ;
int nota3 =7 ;

int media = nota1 + nota2 + nota3 / 3 ;

Console.WriteLine($"a média é: {media}");
if(media >= 7)
{
    Console.WriteLine("o aluno foi aprovado!");
}
else
{    
   Console.WriteLine("o aluno foi reprovado!");
}
