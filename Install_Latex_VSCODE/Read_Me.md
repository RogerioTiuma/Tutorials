# 1. instalação do Latex

## Baixando o Tex Live

É recomendável a instalação do Tex Live para que não ocorra erros. É possível usar o MikTex ou TinyTex, mas esses versionadores podem causar erros. Se você tentar instalar outros ou tentar reaproveitar algum outro versionador de Latex terá problemas!

Site para instalação do Tex Live: https://www.tug.org/texlive/

![alt text](Imagens/image-3.png)


![alt text](Imagens/image-4.png)

## Instalação do Tex Live

1. Se certifique que qualquer bloqueador (como antivirus ou TinyWall) ou firewall não bloqueie o acesso a internet desse arquivo.

2. Execute o arquivo baixado como administrador, clique em next e depois install. É muito importante que esteja com acesso a internet!

![alt text](Imagens/Executar_Live_Tex.png)

![alt text](Imagens/image-1.png)


3. Escolha onde deve ficar instalados os pacotes, eles podem ocupar bastante espaço. Essa etapa é bem demorada e pode levar horas para que os pacotes básicos sejam baixados.

# 2. Instalação do Anaconda

Essa etapa serve para instalar o VS Code, ele já pode estar instalado no seu computador mas a Anaconda trás várias outras ferramentas que podem ser úteis, por isso recomendo essa instalação.

1. Acesse o site: https://anaconda.com/app/
2. Crie uma conta, essa etapa é bem rápida se usar sua conta google e clicar em "skip" nas opções após criar a conta.
3. Clique no Anaconda Dristribution. 

![alt text](Imagens/Anaconda1.png)

4. Baixe o instalador do Anaconda, esse download pode demorar.
![alt text](Imagens/Download_Anaconda.png)

5. Execute o instalador como administrador.

6. Escolha o diretório para realizar a instalação do Anaconda. Ele ocupa bastante espaço, então escolha com sabedoria. 
NÃO USE UM CAMINHO DE ARQUIVO COM ESPAÇO OU CARACTÉRES ESPECIAIS!!!!

![alt text](Imagens/Dir_Conda.png)

7. Selecione todas as caixas de texto aqui e instale, essa instalação também pode demorar algumas horas.

![alt text](Imagens/Config_Conda_Install.png)

8. A primeira execução pode demorar bastante.

# 3. Instalação do Latex no VS Code

1. Abra o Anaconda Navigator como administrador.

2. Clique no VS Code 
![alt text](Imagens/Vs_Code_Open.png)

3. Vá em extensões onde é indicado pelo número 1 na imagem, procure por Latex Workshop (Numeração 2) e instale a extensão (Numeração 3).

![alt text](Imagens/Install_LatexWorkshop.png)

4. Deve aparecer o ícone "Tex" no canto esquerdo, caso não apareça feche o VS Code e abra novamente.

![alt text](Imagens/Verificação.png)


# 4. Verificando se o latex está funcionando corretamente

Para essa etapa baixe o arquivo chamado "Modelo".

1. Abra o Tex Live Manager como administrador

![alt text](Imagens/open_Tex_Live.png)

2. Procure pelo pacote Abntex2 (Numeração 1 na imagem), marque (Numeração 2) e instale (Numeração 3) na imagem. Guarde bem esse caminho para que no futuro você possa instalar outros pacotes que precise. Se ele já estiver instalado, ignore essa etapa e vá para o item abaixo.

![alt text](Imagens/Install_Abntex2.png)

3. Abra a pasta do modelo baixado com o VS Code.

![alt text](Imagens/Abrir_VS_Code.png)

4. Clique no arquivo "abntex2-modelo-trabalho-academico.tex"

![alt text](Imagens/Executanto_Modelo.png)

5. Clique em TEX no canto esquerdo do VS Code, depois clique em Receita pdflatex + bibtex + pdflatex x2 e espere. Quando terminar, clique na janela indicada na imagem na numeração 2. Se você conseguir visualizar o PDF, está funcionando.


![alt text](Imagens/abrindo_Main.png)