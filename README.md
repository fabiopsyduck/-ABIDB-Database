# 🗄️ ABIDB - Banco de Dados Oficial

**Criado por: Fabiopsyduck**

Este repositório contém a base de dados oficial, em formato CSV, para o projeto **Arena Breakout Infinite - Database Offline (ABIDB)**. 

Aqui você encontra todos os atributos, estatísticas e informações detalhadas sobre os itens do jogo, organizados de forma estruturada para serem lidos pelo aplicativo principal.

> ⚠️ **IMPORTANTE:** Este repositório armazena **APENAS** os arquivos de dados. Se você está procurando o aplicativo (Interface Gráfica) para ler, filtrar e comparar estes itens, acesse o repositório principal:
> 👉 **[Repositório do Aplicativo ABIDB (Motor/GUI)](https://github.com/fabiopsyduck/Arena-Breakout-Infinite-Offline-Database/tree/main)**

## 📦 O que está incluído?

A pasta `Database ABI` contém arquivos cobrindo mais de 19 categorias de itens do Arena Breakout Infinite, incluindo:

* **Armamento:** Armas de fogo, Munições (organizadas por calibre) e Arremessáveis (Granadas).
* **Equipamento de Proteção:** Capacetes, Coletes Balísticos, Rigs Blindados, Máscaras e Fones de Ouvido.
* **Armazenamento:** Mochilas e Rigs Táticos sem blindagem.
* **Saúde & Suprimentos:** Kits Médicos, Kits Cirúrgicos, Analgésicos, Bandagens, Estimulantes, Nebulizadores, Comidas e Bebidas.
* **Tabelas de Relacionamento:** Regras de compatibilidade.

🛑 **AVISO IMPORTANTE: NÃO APAGUE O ARQUIVO `Versao.txt`!**
Este arquivo vem dentro da pasta e contém o número da versão atual. O seu aplicativo ABIDB precisa dele exclusivamente para verificar se existem novas atualizações no GitHub. Se ele for removido ou modificado incorretamente, o seu sistema de atualização mostrará um erro de "Versão Não Encontrada".

## 🛠️ Como Instalar / Atualizar

Se o seu aplicativo ABIDB avisou que há uma nova atualização na base de dados, siga estes passos para aplicar os novos itens:

1. Vá até a seção de **Releases** deste repositório (ou clique no botão verde `<> Code` e selecione *Download ZIP*).
2. Extraia o conteúdo baixado.
3. Copie a pasta **`Database ABI`**.
4. Cole essa pasta no mesmo local onde está o seu arquivo principal `ABIDB.exe` (ou `ABIDB.ps1`), substituindo a pasta antiga.

**Estrutura Correta:**
```text
Sua_Pasta_Do_Jogo/
 ├── ABIDB.exe           (O aplicativo principal)
 └── Database ABI/       <-- (A pasta deste repositório vai aqui)
      ├── Weapons.csv
      ├── Ammo.csv
      └── ...
```

## 📝 Para Contribuidores (Como Editar)

Se você deseja ajudar a manter esta base de dados atualizada ou criar a sua própria versão customizada, sinta-se à vontade! 

**Regras de Formatação dos CSVs:**
* **Separador:** Ponto e vírgula ( `;` ).
* **Codificação:** Estritamente `UTF-8 com BOM` (Isso é essencial para que o aplicativo leia acentos e caracteres especiais corretamente).
* **Aspas:** Os valores textuais estão encapsulados em aspas duplas ( `"Exemplo"` ).

Você também pode usar a aba **"Gerenciador de Base de Dados"** dentro do próprio aplicativo ABIDB para adicionar, editar ou remover itens com uma interface gráfica amigável, sem precisar tocar no código diretamente!

## 📄 Licença

Este banco de dados é disponibilizado sob a Licença MIT. Sinta-se livre para usar, modificar e distribuir, desde que os devidos créditos sejam mantidos.

--- 

Este formato garante que qualquer pessoa que caia acidentalmente no repositório da *Database* perceba imediatamente o que é, como se usa, e o mais importante: receba um "sinal de trânsito" gigante a apontar para o seu repositório principal onde está o glorioso `.exe`! 😎🚀
