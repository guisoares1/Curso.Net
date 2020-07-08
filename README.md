# Curso.Net Feito na digital Innovation One.
O conteúdo de código trata de uma atividade feita pelo professor em aula, onde é criado uma aplicação de console .Net inicial, usando o comando 'dotnet new console -n (nome do projeto)'. Após o passo anterior foi feito uma modificação no arquivo 'Main' do projeto, onde existia uma mensagem de 'hello world' foi adicionado uma estrutura de repetição.
Minha modificação feita foi a criação de um 'While' decrescente, segue um trecho: 
```csharp
using System;

namespace DigitalInnovationOne
{
    class Program
    {
        static void Main(string[] args)
        {
            int nNumVez=5;
            while (nNumVez>=0){
                Console.WriteLine($"Bem vindo ao curso de .NET {nNumVez}");
                nNumVez--;
            }
        }
    }
}
```
