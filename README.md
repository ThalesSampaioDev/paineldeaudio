# 🎋 Painel de Som - Festa Junina 🌽

Um painel web simples, leve e intuitivo desenvolvido para centralizar a sonoplastia da Festa Junina da escola. O objetivo principal é facilitar o controle de músicas e efeitos sonoros em tempo real, eliminando a necessidade de gerenciar várias abas abertas no navegador.

## 🚀 Diferenciais do Projeto

* **Tudo em um só lugar:** Músicas principais e efeitos sonoros (Ihaaa, Som de Galinha, Música tema) acionados na mesma tela.
* **100% Offline:** Hospedado localmente no computador da escola, rodando perfeitamente sem depender de conexão com a internet.
* **Interface Limpa:** Criada para que qualquer pessoa consiga operar o som do evento sem confusão.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Para a estruturação dos botões e players de áudio.
* **CSS3:** Para a estilização e organização visual do painel (layout responsivo e intuitivo).

## ⚡ Otimização e Performance (Anti-Travamento)

Para garantir que o painel responda instantaneamente ao clique, sem *delays*, engasgos ou travamentos durante o evento ao vivo, o projeto segue estas diretrizes de otimização:

* **Formatos Leves (`.mp3` ou `.ogg`):** Todos os áudios devem ser convertidos para formatos comprimidos. Evite usar `.wav` (que são arquivos muito pesados), reduzindo o uso de memória RAM do computador da escola.
* **Atributo `preload="auto"`:** No HTML, as tags de áudio utilizam a propriedade `preload="auto"`. Isso força o navegador a carregar todos os sons na memória assim que a página é aberta, garantindo que o som toque *imediatamente* ao ser acionado.
* **Consumo de CPU Zero:** Como o projeto utiliza apenas HTML estático e CSS (sem frameworks pesados ou requisições de rede), o impacto no processador do computador é praticamente nulo, rodando liso até em PCs mais antigos.

## 💻 Como Rodar o Projeto

Como o sistema não precisa de internet, o processo é super simples:

1. Baixe o código do repositório.
2. Certifique-se de que os arquivos de áudio estão na pasta correta.
3. Dê um duplo clique no arquivo `index.html` para abrir o painel no navegador.
