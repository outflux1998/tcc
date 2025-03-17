# Automated Detection of Password Leakage from Public GitHub Repositories

Feng, R., Yan, Z., Peng, S., & Zhang, Y. (2022). Automated Detection of Password Leakage from Public GitHub Repositories. In 44th International Conference on Software Engineering (ICSE). doi: [10.1145/3510003.3510150](https://doi.org/10.1145/3510003.3510150)

## 1. Fichamento de Conteúdo

O artigo aborda o problema do vazamento de senhas em repositórios públicos no GitHub, onde desenvolvedores acidentalmente expõem credenciais sensíveis no código-fonte. Para enfrentar esse problema, os autores propõem o PassFinder, uma abordagem automatizada baseada em redes neurais profundas que detecta senhas levando em consideração tanto suas características textuais quanto o contexto do código onde aparecem. O estudo realizou uma análise em larga escala por 75 dias, inspecionando mais de 1,4 milhão de arquivos públicos e identificando 142.479 vazamentos de senhas em 64.045 repositórios distintos. Os resultados destacam que a maioria das senhas vazadas permanece exposta por longos períodos, apresentando um risco significativo à segurança. O artigo sugere melhorias para a detecção automática de credenciais e recomenda que desenvolvedores adotem práticas mais seguras no armazenamento de senhas.

## 2. Fichamento Bibliográfico

* **PassFinder**: Ferramenta que combina aprendizado de máquina e análise semântica para detectar senhas em código-fonte (página 3).
* **Problema do vazamento de credenciais**: Senhas e chaves de API são frequentemente expostas no GitHub, trazendo riscos de segurança para desenvolvedores e empresas (página 2).
* **Abordagens tradicionais**: Métodos baseados em expressões regulares apresentam baixa precisão para detectar senhas de texto livre (página 4).
* **Análise em larga escala**: Foram inspecionados 1.476.692 arquivos em 539.012 repositórios ao longo de 75 dias (página 6).
* **Impacto do vazamento**: 82,32% das senhas identificadas permaneceram disponíveis por pelo menos 16 dias após a detecção (página 9).

## 3. Fichamento de Citações

* _"Our study reveals that thousands of passwords are leaked daily on GitHub, creating serious security risks."_
* _"PassFinder significantly outperforms traditional regex-based methods in detecting password leaks."_
* _"More than 80% of leaked passwords remain publicly accessible weeks after their exposure."_
* _"Improving automated secret detection tools can help mitigate the risks associated with credential leakage in public repositories."_
# Automated Detection of Password Leakage from Public GitHub Repositories

Feng, R., Yan, Z., Peng, S., & Zhang, Y. (2022). Automated Detection of Password Leakage from Public GitHub Repositories. In 44th International Conference on Software Engineering (ICSE). doi: [10.1145/3510003.3510150](https://doi.org/10.1145/3510003.3510150)

## 1. Fichamento de Conteúdo

O artigo aborda o problema do vazamento de senhas em repositórios públicos no GitHub, onde desenvolvedores acidentalmente expõem credenciais sensíveis no código-fonte. Para enfrentar esse problema, os autores propõem o PassFinder, uma abordagem automatizada baseada em redes neurais profundas que detecta senhas levando em consideração tanto suas características textuais quanto o contexto do código onde aparecem. O estudo realizou uma análise em larga escala por 75 dias, inspecionando mais de 1,4 milhão de arquivos públicos e identificando 142.479 vazamentos de senhas em 64.045 repositórios distintos. Os resultados destacam que a maioria das senhas vazadas permanece exposta por longos períodos, apresentando um risco significativo à segurança. O artigo sugere melhorias para a detecção automática de credenciais e recomenda que desenvolvedores adotem práticas mais seguras no armazenamento de senhas.

## 2. Fichamento Bibliográfico

* **PassFinder**: Ferramenta que combina aprendizado de máquina e análise semântica para detectar senhas em código-fonte (página 3).
* **Problema do vazamento de credenciais**: Senhas e chaves de API são frequentemente expostas no GitHub, trazendo riscos de segurança para desenvolvedores e empresas (página 2).
* **Abordagens tradicionais**: Métodos baseados em expressões regulares apresentam baixa precisão para detectar senhas de texto livre (página 4).
* **Análise em larga escala**: Foram inspecionados 1.476.692 arquivos em 539.012 repositórios ao longo de 75 dias (página 6).
* **Impacto do vazamento**: 82,32% das senhas identificadas permaneceram disponíveis por pelo menos 16 dias após a detecção (página 9).

## 3. Fichamento de Citações

* _"Our study reveals that thousands of passwords are leaked daily on GitHub, creating serious security risks."_
* _"PassFinder significantly outperforms traditional regex-based methods in detecting password leaks."_
* _"More than 80% of leaked passwords remain publicly accessible weeks after their exposure."_
* _"Improving automated secret detection tools can help mitigate the risks associated with credential leakage in public repositories."_
