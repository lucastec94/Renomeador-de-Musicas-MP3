📄 Documentação — Renomeador de Músicas MP3
📌 Visão Geral
Nome da aplicação: Renomeador de Músicas MP3
Versão: 1.0
Desenvolvedor: Lucas Fernando
YouTube: [@lucasfernando_oficial](https://www.youtube.com/@lucasfernando_oficial)
LinkedIn: [linkedin.com/in/lucas-fernando-it](https://www.linkedin.com/in/lucas-fernando-it/)

🎯 Objetivo da Aplicação
O Renomeador de Músicas MP3 foi criado para resolver problemas comuns de compatibilidade em:

Aparelhos de som automotivos antigos

Reprodutores de MP3 básicos

Rádios com leitor USB limitado

Esses dispositivos frequentemente não reconhecem nomes de arquivos com acentos, espaços ou símbolos especiais.

A aplicação:

Extrai o título da música diretamente dos metadados ID3 do arquivo .mp3

Remove acentos, espaços e caracteres especiais

Renomeia o arquivo com base no título limpo

🖥️ Requisitos para Utilização
Para a versão Python (.py)
Python 3.7 ou superior

Biblioteca mutagen instalada via pip

Para a versão executável (.exe)
Nenhum requisito. Basta executar o arquivo

Compatível com Windows 10 ou superior

📦 Formas de Utilização
✅ 1.Executável portátil (RenomeadorMusicas.exe)
Basta clicar duas vezes para executar

Abre um terminal interativo solicitando o caminho da pasta

Não requer instalação nem dependências

💡 Como Usar

Digite o caminho completo da pasta onde estão os arquivos .mp3

Exemplo: C:\Users\Lucas\Downloads\musicas

O aplicativo irá:

Ler os arquivos .mp3

Obter o título a partir dos metadados ID3

Limpar o nome (remover acentos, espaços, símbolos)

Renomear o arquivo fisicamente no disco

Arquivos que já possuem nomes com os mesmos títulos limpos não serão sobrescritos.

🧩 Estrutura do Código
🔹 limpar(texto)
Remove acentos e símbolos usando Unicode Normalization

Mantém apenas letras, números e hífens

🔹 exibir_intro()
Exibe na tela:

Informações sobre o aplicativo

Requisitos

Instruções de uso

Créditos e redes sociais

🔹 renomear_musicas(pasta)
Lista os arquivos .mp3

Lê o metadado "title" de cada música

Renomeia o arquivo com base no título limpo

⚖️ Direitos Autorais
Este software foi desenvolvido por Lucas Fernando com propósito educacional e de uso pessoal.

É responsabilidade do usuário respeitar os direitos autorais dos conteúdos que utilizar.

📞 Contato
Desenvolvedor: Lucas Fernando
📧 LinkedIn https://www.linkedin.com/in/lucas-fernando-it/
▶️ YouTube https://www.youtube.com/@lucasfernando_oficial
