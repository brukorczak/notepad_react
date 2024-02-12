# Notepad React

## Descrição
O Notepad React é uma aplicação simples para criar e gerenciar notas. Ele permite que você adicione notas de texto ou grave notas de áudio que são automaticamente convertidas em texto. Este aplicativo é ótimo para manter suas ideias organizadas e acessíveis.

## Funcionalidades
- Adicionar notas de texto
- Gravar notas de áudio e convertê-las em texto
- Excluir notas existentes

## Instalação
1. Clone este repositório:
   ```bash
   git clone https://github.com/bruKorczak/notepad_react.git
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Inicie a aplicação:
   ```bash
   npm start
   ```
## Uso
- Para adicionar uma nova nota, clique no botão "Adicionar nota" e insira o conteúdo da nota no campo de texto. Você também pode gravar uma nota de áudio clicando no botão de gravação.
- Para excluir uma nota existente, clique na nota e, em seguida, clique no botão para apagar a nota.

## Tecnologias Utilizadas
- React
- Tailwind CSS
- Radix UI
- Lucide React
- Date-fns
- Sonner

> **OBS:_** A aplicação utiliza a API de Reconhecimento de Fala para permitir a gravação de notas por voz. No entanto, é importante observar que a disponibilidade dessa API pode variar dependendo do navegador utilizado. Para verificar se o navegador que você está usando suporta a API de Reconhecimento de Fala, você pode consultar o site [Can I Use](https://caniuse.com/) e pesquisar pela "SpeechRecognitionEvent API".

Clique [aqui](https://caniuse.com/?search=SpeechRecognitionEvent%20API) para verificar a compatibilidade da API em diferentes navegadores.
