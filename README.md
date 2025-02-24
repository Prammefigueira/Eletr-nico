Eletronico - Sistema de Log para Dispositivos Eletrônicos

Este é um projeto simples desenvolvido em Python 3 que simula o funcionamento de dispositivos eletrônicos, como smartphones, com um sistema de log que registra eventos de ligação e desligamento.

Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

eletronico.py: Define a classe base Eletronico e a classe Smartphone, que herda funcionalidades da classe base e do sistema de log.
log.py: Implementa o sistema de logging com as classes Log, LogFileMixin e LogPrintMixin.
main.py: Exemplo de uso do sistema, instanciando e manipulando objetos Smartphone.
log.txt: Arquivo de log gerado pelo sistema.

Instalação

Para utilizar o sistema, siga os passos abaixo:

1. Certifique-se de ter o Python 3 instalado na sua máquina.
2. Clone este repositório ou baixe os arquivos manualmente:

   git clone https://github.com/seuusuario/eletronico.git
   cd eletronico
   
3.Execute o script main.py para testar o funcionamento:
  python main.py

Uso
O código principal de uso está no arquivo main.py. Um exemplo de como utilizar a classe Smartphone:

  from eletronico import Smartphone

  meu_celular = Smartphone("iPhone 14")
  meu_celular.ligar()
  meu_celular.desligar()

Esse código criará um novo objeto Smartphone, ligará e desligará o dispositivo, registrando as ações no log.


