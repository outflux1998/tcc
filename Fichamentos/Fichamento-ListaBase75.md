# Can ChatGPT Repair Non-Order-Dependent Flaky Tests?

Lyu, H., Liu, J., Zhang, X., & Zhang, Y. (2023). Can ChatGPT Repair Non-Order-Dependent Flaky Tests? In Proceedings of the 32nd ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA 2023). doi: [10.1145/3643656.3643900](https://doi.org/10.1145/3643656.3643900)

## 1. Fichamento de Conteúdo

O artigo analisa se o ChatGPT pode corrigir testes flakey que não dependem da ordem de execução, um problema comum em testes de software. Os autores explicam que testes flakey são aqueles que podem falhar ou passar sem mudanças no código, o que compromete a confiabilidade dos testes automatizados. Para avaliar o desempenho do ChatGPT, o estudo utiliza um conjunto de testes flakey coletados de projetos reais e analisa se o modelo consegue identificar e corrigir corretamente esses testes. Os resultados mostram que, embora o ChatGPT tenha um desempenho promissor na identificação de alguns padrões de falha, ele ainda apresenta dificuldades em corrigir certos testes de maneira confiável, muitas vezes sugerindo alterações superficiais ou incorretas. O artigo discute as limitações do modelo e sugere que ele pode ser útil como uma ferramenta auxiliar, mas que ainda não substitui completamente a revisão humana. A pesquisa destaca a necessidade de melhorias no uso de IA para depuração de testes automatizados, especialmente no que se refere à compreensão contextual do código.

## 2. Fichamento Bibliográfico

* Testes flakey são testes que falham ou passam de forma intermitente sem mudanças no código (página 2).
* O ChatGPT foi avaliado na correção de testes flakey usando um conjunto de testes reais extraídos de projetos open-source (página 4).
* Algumas correções sugeridas pelo ChatGPT eram superficiais e não resolviam a causa raiz do problema (página 6).
* Apesar das limitações, o modelo demonstrou capacidade de identificar padrões de erro em alguns testes (página 7).
* Os autores sugerem que modelos de IA podem complementar o trabalho humano na depuração de testes, mas não substituí-los totalmente (página 8).

## 3. Fichamento de Citações

* _"Flaky tests undermine the reliability of automated testing and can cause significant maintenance overhead."_
* _"ChatGPT shows potential in recognizing some common flaky test patterns but struggles with complex cases."_
* _"Our experiments indicate that while ChatGPT can suggest fixes, they often lack a deep understanding of the root cause."_
* _"Human review is still necessary to validate and refine the suggested repairs."_
* _"Future improvements in AI-assisted debugging may require integrating static and dynamic analysis techniques."_
