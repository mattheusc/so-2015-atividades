======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Matheus Dantas de Carvalho
:Matrícula: 20121144010303
:Data: 01/07/2015

cat
  Exibe o que há dentro de determinado arquivo. Ele é útil quando deseja ler ou exibir um arquivo de texto.
    Ex.: cat TEXTO.txt
      //Exibe o conteúdo do arquivo TEXTO.txt


cd
  Acessa e muda de diretório corrente. Ele é utilizado para a navegação entre as pastas do computador.
  Ex.: cd /home/baixaki/Desktop (vai para o desktop).


cowsay
  Descrição do comando


echo
  Este comando mostra os argumentos na saída padrão seguido por uma nova linha.
    -n :	não adiciona uma nova linha após mostrar os argumentos.
    -e : habilita interpretação dos códigos de escape após barra invetida.
    -E : suprime explicitamente a interpretação de códigos de escape após barra invertida.
      São exemplos de códigos de escape:
          \a :	alerta (Sino).
          \b :	retroceder.
          \c :	suprime próxima saída.
          \e :	caractere de escape.
          \f :	alimentação de página (FF).
          \n :	nova linha (NL).
          \r :	retorno de carro (CR).
          \t :	tabulação horizontal.
          \v :	tabulação vertical.


env
  Exibe as variáveis de ambiente.
    Ex.: env


exit
  Terminar a sessão, ou seja, a shell (mais ajuda digitando man sh ou man csh).
    Ex.: exit


help
  Exibe ajudas (exemplos) de comandos (podem ser específicos).
    Ex.: help
    Ex.: help while


HISTTIMEFORMAT="%d/%m/%y"
  Altera o formato para exibição do histórico. Agora, depois desse comando, o resultado do comando "history" para a ter os dados de data(%d), mês(%m) e ano(%y).
    Ex.: HISTTIMEFORMAT="%d/%m/%y"


hostname
  Exibe o nome da máquina. 
    Ex.: hostname


ifconfig
  Atribuir um endereço a uma interface de rede ou configurar parâmetros de interface de rede. 
    Ex.: ifpconfig


last
  Indica o último login de utilizadores.
    Ex.: last


lastb
  Descrição do comando


ls
  Exibe os arquivos que estão dentro da pasta na qual o usuário está no momento.
    Ex.: ls
    Ex.: ls -F (mostra quem é diretório e quem é arquivo)
    
    
  Ps.: Existem variações, tais como ls -l, com a qual é possível obter informações mais detalhadas sobre os arquivos, como permissões e tamanho. 
    Ex.: ls -l


mkdir
  Enquanto o rmdir remove, este comando cria diretórios.
    Ex.: mkdir DIRETORIO 
      //A pasta DIRETORIO foi criada no local onde o usuário se encontrava.


nome="fulano"
  Descrição do comando


passswd
  Mudar a password do nosso utilizador (usuário logado).
    Ex.: passwd

pwd
  Mostra o diretório onde o usuário está. 
    Ex.: pwd


set
  Define variáveis da sessão, ou seja, da shell, na C shell, na bash ou na ksh.
    Ex.: set


tree
  Descrição do comando


tty
  O nome de terminal onde o usuário está conectado, para iniciar uma conexão local.
    Ex.: tty


vim
 Editor de texto full-screen melhorado (vi improved).
  Ex.: vim


wait
  Descrição do comando


wall
  Envia uma mensagem a todos os usuários do sistema. Este comando faz a leitura de um arquivo ou entrada padrão e escreve o resultado em todos os terminais onde existem usuários conectados. 
  Ex.: wall "mensagem"

wc 
  Conta a quantidade de arquivos/diretórios dentro do diretório.
    EX.: ls /nomedodiretorio/ | wc -l

which
  Busca de arquivos no sistema de forma muito rápida. Busca por executáveis nos PATHs exportados.
    Ex.: 
      which httpd
      resultado: /usr/sbin/httpd 

    Ex.:
    which X 
    resultado: /usr/bin/X11/X 


while
  Executa um bloco de código enquanto sua condição for verdadeira.
    Ex.: 
        while <condição>;do
            bloco de código/ comando...
        done
    
    Ex.: 
         while true;do
           echo "O velho e bom, Hello World!!!"
         done
    
    Ex.: 
        name="Nação Livre"

        while [ "$name" = "Nação Livre" ];do
          echo "Mundo open source !!!"
          echo "Eu adoro programar !!!"
        done


who
  Mostra-nos quem está logado no sistema.
    Ex.: who


whoami
  Mostra o nome do usuário.
    Ex.: whoami

write
  Escrever uma mensagem para um usuário. 
    Ex.: write gabisilva "Mensagem"
    Ex.: echo "mensagem" | write colega
    Ex.: cowsay -f koala "Mensagem" | write colega

