📊 Atividade – Tabelas Avançadas e Multimídia
📋 Descrição

Nesta atividade foi desenvolvida uma página HTML utilizando tabelas avançadas e recursos multimídia. O objetivo foi praticar a estruturação de dados em tabelas e a inserção de vídeos e áudios em uma página web.

Também foi utilizado CSS para melhorar a aparência da página, adicionando cores, espaçamentos, bordas, sombras, gradientes e responsividade.

🎯 Objetivos
Criar uma tabela de relatório de vendas.
Utilizar elementos semânticos de tabelas HTML.
Aplicar estilos utilizando CSS.
Inserir um vídeo local na página.
Inserir um vídeo do YouTube.
Inserir um arquivo de áudio.
Utilizar elementos multimídia do HTML5.
Aplicar responsividade para diferentes tamanhos de tela.
🛠️ Tecnologias utilizadas
HTML5
CSS3
YouTube
Arquivos de vídeo e áudio
📁 Estrutura dos arquivos
projeto/
│
├── 08_tab_multimidea.html
├── 08_tab_multimidea.css
│
└── assets/
    ├── limoes-capa.png
    ├── meu-video.mp4
    └── happy-mistake.mp3
📊 Tabela de vendas

Foi criada uma tabela com o título "Vendas por Região - 2025", contendo informações de vendas por trimestre.

Foram utilizados elementos como:

<table>
<caption>
<thead>
<tbody>
<tfoot>
<tr>
<th>
<td>

A tabela também recebeu estilos personalizados através do CSS, incluindo cores, sombras, bordas e alinhamento dos valores numéricos.

🎥 Vídeo local

A página possui um vídeo armazenado localmente no projeto utilizando a tag <video>.

O vídeo possui:

Controles de reprodução.
Imagem de capa.
Arquivo .mp4.
Texto alternativo para navegadores que não suportam HTML5.
▶️ Vídeo do YouTube

Também foi inserido um vídeo externo utilizando a tag <iframe>.

O CSS foi utilizado para adicionar uma borda ao vídeo e melhorar sua apresentação na página.

🎵 Áudio

Foi adicionado um player de áudio utilizando a tag <audio>.

O arquivo utilizado está localizado na pasta assets e possui formato .mp3.

Também foram utilizados controles de reprodução e carregamento de metadados.

🎨 Estilização com CSS

O arquivo CSS foi utilizado para personalizar toda a página.

Foram aplicados:

Cores de fundo.
Gradientes.
Sombras.
Bordas arredondadas.
Espaçamentos.
Alinhamento de elementos.
Fontes personalizadas.
Estilização da tabela.
Estilização dos vídeos.
Estilização do player de áudio.
📱 Responsividade

Foi utilizada uma media query para adaptar o vídeo do YouTube em telas menores:

@media (max-width: 600px) {
    iframe {
        width: 100%;
        height: 250px;
    }
}

Dessa forma, o conteúdo consegue se adaptar melhor a dispositivos com telas pequenas.

🚀 Como executar
Baixe ou clone o projeto.
Mantenha os arquivos HTML e CSS na mesma pasta.
Mantenha os arquivos de mídia dentro da pasta assets.
Abra o arquivo:
08_tab_multimidea.html
Execute o arquivo em um navegador, como Google Chrome, Microsoft Edge ou Firefox.
📚 Conclusão

A atividade permitiu praticar conceitos de HTML5 e CSS3, principalmente a criação de tabelas estruturadas e a utilização de recursos multimídia.

Com o desenvolvimento da página, foi possível compreender como inserir e estilizar tabelas, vídeos locais, vídeos do YouTube e arquivos de áudio, além de aplicar técnicas básicas de responsividade para melhorar a visualização em diferentes dispositivos.
