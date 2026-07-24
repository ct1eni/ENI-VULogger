# ENI-VULogger

O ENI‑VULogger é uma aplicação gratuita destinada à participação dos Radioamadores em concursos de VHF e UHF. Desenvolvida com o objetivo de proporcionar uma interface intuitiva e de fácil utilização, disponibiliza as funcionalidades essenciais para a operação e registo de contactos durante os concursos. Embora ainda se encontre em fase de desenvolvimento, o projeto evolui continuamente, tendo como principal objetivo alargar a sua compatibilidade a um número cada vez maior de concursos e incorporar novas funcionalidades que respondam às necessidades da comunidade de radioamadores.

## Funcionalidades

Registo, edição, ordenação e eliminação de QSOs. 
Data/hora automática e apresentação da hora local e da hora UTC configurada. 
Cálculo da distância entre o locator da estação e o locator do correspondente. 
Detecção (com informação visual) de contactos potencialmente duplicados. 
Numeração STX automática por banda e conservação do SRX recebido. 
Pontuação e multiplicadores apresentados por banda e no total. 
Gravação e carregamento de QSOs em JSON. 
Importação e exportação ADIF, EDI e Excel e exportação Cabrillo. 
Tema claro/escuro, janela de estatísticas e manual interno.

## Screenshot

<img width="1238" height="596" alt="image" src="https://github.com/user-attachments/assets/cbdaeb06-cabe-417c-aa26-af654b9c6e50" />

## Compatibilidade

O ENI-VULogger é suportado em:
- Windows 10
- Windows 11
- Sistemas x86 e x64
- Windows ARM64 através de emulação

O Windows 7 não é oficialmente suportado, devido ao fim do suporte do 
Microsoft Edge WebView2 Runtime nesse sistema operativo.

## Instalação e execução

Instruções da versão portable em elaboração.

## Formatos suportados

ADIF, EDI, Cabrillo, Excel e JSON.

## Concursos suportados

Dia de Portugal VHF/UHF — REP
ARAM VHF/UHF - ARAM
Combinado V/UHF — URE
Segóvia EA1RCS V/UHF — URE
Nacional V/UHF — URE
Atlântico V/UHF — URE
Costa del Sol V/UHF — URE
QSL V/UHF — URE
Outro concurso, com fator ×1 em todas as bandas

## Descarregar a aplicação
Aceda à página Releases do ENI‑VULogger no GitHub.
Abra a versão mais recente.
Na secção Assets, descarregue o ficheiro com um nome semelhante a:

ENI-VULogger_v0.25.1.1.zip

Atenção: não descarregue Source code (zip) nem Source code (tar.gz). Esses ficheiros contêm dados do projeto e não correspondem à aplicação pronta a executar.

# Extrair o ficheiro ZIP

Depois de concluir o download:

Abra a pasta Transferências ou a pasta para onde o ficheiro foi gravado.
Clique com o botão direito sobre o ficheiro ZIP.
Seleccione Extrair tudo….
Escolha a pasta de destino.
Clique em Extrair.

Por exemplo:
C:\ENI-VULogger\

Não execute a aplicação diretamente dentro do ficheiro ZIP.

# Executar a aplicação

Abra a pasta extraída e execute:

ENI_VULogger.exe

A pasta poderá conter também bibliotecas, ficheiros de configuração e subpastas necessárias ao funcionamento da aplicação.
Não apague nem mova isoladamente o executável. Mantenha inalterados todos os ficheiros e pastas incluídos que faziam parte
extracção do .zip.

Aviso de segurança do Windows:
Na primeira execução, o Windows poderá apresentar um aviso de segurança por a aplicação ter sido descarregada da Internet.

Se aparecer a janela "O Windows protegeu o PC":
Confirme que descarregou a aplicação do repositório oficial.
Clique em Mais informações.
Clique em Executar mesmo assim.

Em algumas configurações, poderá ser necessário clicar com o botão direito em:
ENI_VULogger.exe
e seleccionar:
Propriedades

Se aparecer a opção Desbloquear:
Marque Desbloquear.
Clique em Aplicar.
Clique em OK.
Execute novamente a aplicação.

## Requisitos

A versão atual destina-se a:

Windows 10;
Windows 11;
sistemas x86 e x64;
Windows ARM64 através de emulação, dependendo da configuração do sistema.

A aplicação utiliza o Microsoft Edge WebView2 Runtime. Se o WebView2 não estiver disponível, a janela da aplicação poderá não abrir corretamente.
O Windows 7 e o Windows 8/8.1 não são oficialmente suportados.

## Primeira utilização

Na primeira execução, preencha os dados de operação:

indicativo;
nome;
QTH Locator;
diferença entre a hora local e UTC;
concurso;
categoria do operador;
potência;
tipo de estação.

Depois, clique em Guardar.

A janela de configuração também pode ser aberta através de:
Botão "Configuração" ou premir a tecla F2

# Criar um atalho

Para criar um atalho no Ambiente de Trabalho:
Clique com o botão direito em ENI_VULogger.exe.
Seleccione "Mostrar mais opções", se necessário.
Escolha "Enviar para".
Seleccione "Ambiente de Trabalho — criar atalho".

Não mova apenas o executável para o Ambiente de Trabalho. Use um atalho para que a aplicação continue a encontrar
todos os ficheiros da pasta da aplicação.

# Atualizar para uma nova versão

Antes de atualizar:
Abra a versão atual.
Use Gravar QSOs para criar uma cópia em formato JSON.
Exporte também a configuração do operador.
Feche a aplicação.
Descarregue a nova versão.
Extraia o ficheiro .zip para uma pasta nova (por exemplo, uma pasta com a nova versão no nome).
Execute a nova versão.
Carregue a configuração e os QSOs anteriormente guardados.

Recomenda-se não substituir imediatamente a pasta antiga. Mantenha-a até confirmar que a nova versão 
funciona e que os dados foram recuperados corretamente.

Actualmente, não está prevista uma distribuição do ENI-VULogger com um instalador tradicional;
comporta-se como uma versão "Portable";
a aplicação funciona a partir da pasta extraída;
os ficheiros necessários são fornecidos no mesmo pacote;
a pasta pode ser copiada para outro computador compatível;
o programa não deve ser executado diretamente dentro do ZIP.

Recomendação: guarde regularmente uma cópia dos QSOs e da configuração. O facto de ser uma versão "Portable" 
facilita a execução e a transferência da aplicação, mas não substitui as cópias de segurança.

## Estado do projeto

Versão em desenvolvimento constante.

## Autor

CT1ENI — José Carlos Valério Ribeiro

## Downloads

[![Downloads](https://img.shields.io/github/downloads/CT1ENI/ENI-VULogger/total?style=for-the-badge&logo=github&label=Downloads)](https://github.com/CT1ENI/ENI-VULogger/releases)
