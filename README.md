# Projeto de NFT Teste de Pokémon

Este projeto visa criar um teste de criação de Tokens Não Fungíveis (NFTs) para Pokémon, explorando a integração entre contratos inteligentes e armazenamento de ativos digitais.

## Funcionalidades do Contrato `pokeSAD.sol`

O arquivo `pokeSAD.sol` representa o contrato inteligente central que gerencia a lógica dos NFTs do projeto. Ele é responsável por definir as regras e a estrutura para a criação, propriedade e gerenciamento dos tokens Pokémon.

As principais funcionalidades incluem:

1.  **Criação de Tokens:** Define como os novos NFTs Pokémon devem ser criados na blockchain.
2.  **Gerenciamento de Propriedade:** Controla quem possui cada NFT (proprietário).
3.  **Metadados do NFT:** Armazena informações essenciais sobre cada token, como o tipo de Pokémon e referências a seus ativos digitais.

Em resumo, este contrato garante a imutabilidade e a transparência dos ativos digitais no blockchain.

## Armazenamento de Imagens (IPFS)

Para armazenar os ativos visuais (imagens dos Pokémon), sugerimos o uso do protocolo **IPFS (InterPlanetary File System)**.

Ao utilizar o IPFS, as imagens são armazenadas de forma descentralizada na rede P2P e seu hash é registrado na blockchain. Isso permite que o conteúdo visual seja referenciado pela blockchain, garantindo que os NFTs possuam um link seguro para seus ativos, em vez de armazenar os arquivos grandes diretamente na blockchain.

Isso otimiza o uso da blockchain, mantendo apenas as informações cruciais (propriedade e metadados) no registro imutável.