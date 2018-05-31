# _Linguistic Datasets for Portuguese_: conjuntos de dados linguísticos para português (pt-AO, pt-BR pt-MZ e pt-PT)
**Lista de conjuntos de dados linguísticos para
português com licenças flexíveis: banco de dados, lista de palavras, sinônimos,
antônimos, dicionário temático, tesauro, _linked data_, semântica, ontologia e
representação de conhecimento.**

<blockquote><em lang="en">
(English description) List of linguistic datasets for Portuguese
with flexible licenses: database, wordlist, synonyms, antonyms,
thematic dictionaries, thesaurus, linked data, semantic, ontology and
knowledge representation.
</em></blockquote>

---

O objetivo desse projeto, inspirado pelo espírito de [FOSS](https://pt.wikipedia.org/wiki/Software_livre_e_de_c%C3%B3digo_aberto),
é listar fontes de representações de conhecimento que, ao depender da língua
e das culturas locais, não podem ser importadas. Requerem atenção especial, de
caráter multidisciplinar, e que idealmente _já deveria estar prontas e
aceitavelmente validadas_: quando não existem, na melhor das hipóteses, podem
forçar serem feitas por não especialista e prejudicar qualidade, e na pior, até
impedir a produção de tecnologias inovadoras.

<!--

Veja outras [justificativas da pertinência](#justificativa).

-->

<!--
Veja também [termos chave para inspirar pesquisas relacionadas](termos-chave.md).
-->

---

## Lista
Conjuntos de dados linguísticos requerem _muito mais_ atenção e trabalho humano
especializado do que tradicionalmente se vê em dados abertos. Pense em megabytes,
não gigabytes. Boa parte dos conjuntos de dados listados são praticamente
_engenharia reversa_ da representação de conhecimento e que, mesmo sem usar
licença específica mais para datasets 
([PDDL](https://opendatacommons.org/licenses/pddl/),
[CDLA](https://cdla.io/permissive-1-0/),
[ODC](http://opendatacommons.org/licenses/by/), ...) tem uma licença em que
**você pode** usar.

| Conjunto de dados | Data | Licença | Etiquetas | Descrição |
| --- | --- | --- | --- | --- |
| [languagetool-org: regras PT](https://github.com/languagetool-org/languagetool/tree/master/languagetool-language-modules/pt/src/main/resources/org/languagetool/rules/pt) | _ativo_ | LGPLv2.1 |  _(muitas-tags)_, pt-AO, pt-BR pt-MZ e pt-PT | languagetool-org é verificador de estilo e gramática para mais de 25 idiomas |
| [languagetool-org: falsos cognatos](https://github.com/languagetool-org/languagetool/blob/master/languagetool-core/src/main/resources/org/languagetool/rules/false-friends.xml) | _ativo_ | LGPLv2.1 | falsos-cognatos, traducao | Falsos cognatos (Inglês: _false friends_) são termos que parecem uma coisa, mas na verdade, são outra. Muito pertinente na tradução de textos |
| [openWordnet-PT](https://github.com/own-pt/openWordnet-PT) | _ativo_ | CC-BY-4.0 | wordnet, owl, rdf, sparql, pt-BR | OpenWordnet-PT: an open Brazilian Wordnet |
| [Stopwords Portuguese (PT)](https://github.com/stopwords-iso/stopwords-pt/tree/master/raw) | 2016-10-10 | _Várias_ | stopwords, palavras-vazias | Lista de listas de palavras-vazias com [560 termos únicos](https://github.com/stopwords-iso/stopwords-pt/blob/master/stopwords-pt.txt) |
| [VERO-pt-BR](https://github.com/fititnt/VERO-pt-BR_verificador-ortografico-portugues-brasileiro) | 2013-12-17 | LGPLv3, MPL | verificacao-ortografica, verificacao-gramatical, hifenizacao, libreoffice, openoffice, pt-BR | Espelho não-oficial da base de dados do [VERO (VERificador Ortografico do LibreOffice)](https://pt-br.libreoffice.org/projetos/vero) |
| [DicSin pt-BR](https://github.com/fititnt/DicSin-dicionario-sinonimos-portugues-brasileiro) | 2010-05-28 | GPLv2? | dicionario, sinonimo, antonimo, pt-BR | DicSin: Dicionário de sinônimos e antônimos no idioma português brasileiro |
| [br.ispell](https://github.com/fititnt/br.ispell-dicionario-portugues-brasileiro) | 2003-03-25 | GPLv2 | dicionario, verificacao-ortografica, ispell, aspell, myspell, pt-BR | Espelho não-oficial dos dados de [br.ispell](https://www.ime.usp.br/~ueda/br.ispell/) |

Pergunta em aberto: sabendo que conjunto de dados linguísticos são úteis para
todos (principalmente o próprio governo e pequenas e médias empresas e
organizações) o que pode ser feito com os que nem existem ou os que o uso mais
comum implica em pirataria?

## Lista de desejos

> Aviso: a lista a seguir não foi revisada quanto a utilidade e viabilidade.

<!--
Essa abordagem é útil a curto prazo, porém o
pensamento a médio e longo prazo poderia ativamente estimular que governos e
universidades desenvolvam conjunto de dados úteis
-->

| Etiquetas | Inspirações | Descrição |
| --- | --- | --- |
| afinn-111, analise-de-sentimento | [AFINN-111, EN](http://www2.imm.dtu.dk/pubdb/views/publication_details.php?id=6010) | Uma lista de palavras etiquetada com uma valência positiva ou negativa adaptada a um ou mais dialetos da língua portuguesa, que use como inspiração (não necessariamente uma tradução) do artigo [A new ANEW: Evaluation of a word list for sentiment analysis in microblogs](https://arxiv.org/abs/1103.2903) |
| analise-de-sentimento, sarcasmo | [MIT, emojis, bullying](https://www.digitaltrends.com/cool-tech/emojis-mit-algorithm-bullying/) | Considerar a possibilidade de estimular análise de sentimento (ou padrões para identificar sarcasmo) considerando emojis e outros estilos de escrita muito específicos. Potencialmente útil em pesquisas futuras para reduzir falsos positivos de linguagem ofensiva ou discurso de ódio. Um projeto internacional é [deepmoji.mit.edu](https://deepmoji.mit.edu/) / [GitHub do DeepMoji](https://github.com/bfelbo/DeepMoji) |
| termos-ofensivos, palavrao | [Wikipedia](https://pt.wikipedia.org/wiki/Palavra_de_baixo_cal%C3%A3o), [HateBase PT](https://www.hatebase.org/search_results/keywords%3D%7Cfilter_about_ethnicity%3D%7Cfilter_about_nationality%3D%7Cfilter_about_religion%3D%7Cfilter_about_gender%3D%7Cfilter_about_sexual_orientation%3D%7Cfilter_about_disability%3D%7Cfilter_about_class%3D%7Cfilter_archaic%3D%7Cinclude_meaning%3D%7Cfilter_language%3Dpor) | Palavrões, Palavra de baixo calão, termos ofensivos: <ul><li>Preferencialmente com classificações adicionais (por região, tipo de palavrão, intensidade)</li><li>Permitir exportação para lista de palavras simples (útil em filtros de spam)</li><li>Pode exibir uma abordagem colaborativa, atualizável por usuários finais</li><li>Muito útil para gerar outros conjuntos de dados</li></ul> |
| termos-ofensivos, discurso-de-odio | [Wikipedia](https://pt.wikipedia.org/wiki/Discurso_de_%C3%B3dio), [HateBase PT](https://www.hatebase.org/search_results/keywords%3D%7Cfilter_about_ethnicity%3D%7Cfilter_about_nationality%3D%7Cfilter_about_religion%3D%7Cfilter_about_gender%3D%7Cfilter_about_sexual_orientation%3D%7Cfilter_about_disability%3D%7Cfilter_about_class%3D%7Cfilter_archaic%3D%7Cinclude_meaning%3D%7Cfilter_language%3Dpor) | Conjunto de dados que ajudem a identificar especificamente discurso de ódio possui interesse especial dentro de termos ofensivos |
| weasel-word | [languagetool weasel words](https://github.com/languagetool-org/languagetool/blob/master/languagetool-language-modules/pt/src/main/resources/org/languagetool/rules/pt/weaselwords.txt) | Lista de palavras com termos evasivos. Pode ser interessante interessante até para análise de discursos políticos. Veja: [Finding Hedges by Chasing Weasels: Hedge Detection Using Wikipedia Tags and Shallow Linguistic Features](http://www.aclweb.org/anthology/P09-2044) |

<!--

TODO: adicionar <https://github.com/stopwords-iso/stopwords-pt>

-->

<!--
> Nota: a lista de desejos acima não foi revisada nem quanto a utilidade como
quanto a viabilidade. Se você trabalha na área e algo parece absurdo,
provavelmente você está certo. [Entre em contato](#contato). Ajuda de
especialistas ou profissionais experientes para priorizar conjunto de dados é
extremamente valiosa.
-->

## Justificativa
Uma forma de classificar conjunto de dados que se provam úteis separar em duas
categorias:

1. Validados o suficiente para uso como ferramenta em pesquisa acadêmica nível
   internacional
2. Os aceitáveis para uso no dia a dia pela indústria

A coexistência de ambos é boa para sociedade. Como podemos estimular mais ainda?
Um problema a nível internacional é que há baixa interação, mesmo dentro de
universidades, das áreas de computação com as de estudo da língua, psicologia,
sociologia e afins. Será que podemos estimular uma abordagem diferente em
nossos países?

_TODO: adicionar mais informação da justificativa (fititnt, 2018-05-21 03:08 BRT)_

<!--

A [acessibilidade importa](acessibilidade.md): é preciso entender que
disponibilizar alternativas simples como lista de palavras temática, mesmo com
[limitações aceitáveis](limitacoes.md), não só facilita adoção e impacto
positivo como potencialmente reduz abusos de sistemas sem intervenção humana.
-->

## Contato
- Email: Emerson Rocha &#x3C;<rocha@ieee.org>&#x3E;.
- GitHub Issues: <https://github.com/fititnt/linguistic-datasets-portuguese/issues>.

## Licença
[![Public Domain](https://i.creativecommons.org/p/zero/1.0/88x31.png)](UNLICENSE)

Na medida do possível sob a lei, [Emerson Rocha](https://github.com/fititnt)
renunciou todos os direitos autorais e direitos conexos ou vizinhos a este
trabalho para o [domínio público](UNLICENSE).
