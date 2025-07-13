🎼 Modelagem de Tabelas – Artista, Música e Álbum
📄 Sobre o documento
Este repositório contém um arquivo PDF criado a partir do Google Planilhas no início da unidade curricular de Banco de Dados. O objetivo da atividade foi exercitar a criação e a modelagem de tabelas relacionadas, simulando uma estrutura básica de um sistema de gerenciamento musical.

A proposta envolveu a construção das tabelas Artista, Música e Álbum, representando os principais conceitos de relacionamento entre entidades em um banco de dados relacional.

🧱 Estrutura das Tabelas
👤 Artista
Contém informações sobre os artistas presentes no sistema.

Atributos comuns:

ID do artista (chave primária)

Nome do artista

Gênero musical

País de origem

🎵 Música
Representa as músicas individuais associadas a artistas.

Atributos comuns:

ID da música (chave primária)

Título

Duração

ID do artista (chave estrangeira)

💿 Álbum
Tabela que representa a relação entre músicas e artistas, agrupando-as em um álbum específico.

Atributos comuns:

ID do álbum (chave primária)

Nome do álbum

Ano de lançamento

Lista de músicas (referência cruzada com IDs das músicas)

ID do artista (chave estrangeira)

🔗 Relacionamentos
Um artista pode ter várias músicas.

Um álbum é composto por várias músicas e está vinculado a um artista.

As chaves estrangeiras ajudam a manter a integridade entre as tabelas.

🎯 Objetivo da atividade
Compreender os conceitos de entidade, atributo e relacionamento

Aplicar noções básicas de chave primária e chave estrangeira

Desenvolver a lógica de modelagem relacional desde o início do curso

Criar uma base para consultas SQL futuras (ex: JOIN, GROUP BY, etc.)



👨‍💻 Autor
Leandro – Estudante de Desenvolvimento de Sistemas, interessado em bancos de dados, música e estruturação lógica de sistemas relacionais.
