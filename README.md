# Direitos da Pessoa com Deficiência: instruções de busca e validação para IA

Repositório aberto de **instruções, protocolos e base normativa** para que assistentes de inteligência artificial (Claude, ChatGPT, Gemini, Copilot e outros) pesquisem, validem e expliquem com segurança os **direitos da pessoa com deficiência no Brasil**, na União, nos Estados e nos Municípios.

O foco não é substituir a pesquisa, e sim **dirigi-la**: dizer à IA onde buscar, como conferir vigência e redação atual, como distinguir tese vinculante de precedente isolado e como declarar, com honestidade, o que foi e o que não foi confirmado.

> Última verificação geral da base: **24/09/2026**. Normas mudam. Toda citação deve ser reconferida na fonte oficial antes de uso profissional.

## Para que serve

- Orientar atendimentos, consultas e peças envolvendo pessoas com deficiência.
- Mapear direitos por área: trabalho (CLT, servidor efetivo, comissionado, empregado público), previdência, BPC, tributário, veículos, consumidor, saúde suplementar, transporte aéreo e terrestre, educação, habitação, cultura, civil, família e curatela, crimes.
- Aplicar o **modelo social e de direitos humanos** da Convenção da ONU (CDPD), com equivalência de emenda constitucional, e os **Comentários Gerais** do Comitê CRPD.
- Buscar benefícios **estaduais e municipais** com um roteiro reproduzível para qualquer UF e município.

## Como usar

| Ferramenta | Como usar |
|---|---|
| **Claude (Skill)** | Baixe o repositório em ZIP e envie em *Configurações > Capacidades > Skills*. O arquivo [`SKILL.md`](SKILL.md) na raiz faz do repositório uma Skill. |
| **Claude (Projeto)** | Crie um Projeto e anexe os arquivos de `protocolo/` e `modulos/` como conhecimento; cole [`PROMPT-UNIVERSAL.md`](PROMPT-UNIVERSAL.md) nas instruções. |
| **Claude Code / Cowork** | Clone o repositório; o [`CLAUDE.md`](CLAUDE.md) é lido automaticamente. |
| **ChatGPT, Gemini, Copilot etc.** | Cole o conteúdo de [`PROMPT-UNIVERSAL.md`](PROMPT-UNIVERSAL.md) nas instruções personalizadas (GPT, Gem, agente) e anexe os módulos relevantes. |
| **Agentes de código (Codex, Cursor etc.)** | Usam o [`AGENTS.md`](AGENTS.md). |

## Estrutura

```
SKILL.md                 Skill para Claude (ponto de entrada)
CLAUDE.md / AGENTS.md    Instruções de repositório para agentes
PROMPT-UNIVERSAL.md      Prompt de sistema para qualquer IA
protocolo/
  01-metodo-de-busca.md       Onde e como buscar
  02-protocolo-de-validacao.md Como validar (vigência, redação, tese)
  03-formato-de-resposta.md    Como responder e declarar incertezas
  04-triagem-do-caso.md        Perguntas para enquadrar o caso
modulos/
  00-fundamentos.md            Conceito, avaliação biopsicossocial, CF
  01-internacional-cdpd.md     CDPD, Comentários Gerais, tratados
  02-lbi-acessibilidade-atendimento.md
  03-trabalho-clt-e-cotas.md
  04-servidores-e-concursos.md
  05-previdencia.md
  06-bpc-e-assistencia.md
  07-tributario-e-veiculos.md
  08-consumidor-saude-bancos-telecom.md
  09-transporte-aereo-e-terrestre.md
  10-educacao.md
  11-civil-familia-curatela.md
  12-penal-e-tutela-coletiva.md
  13-habitacao-cultura-lazer-cidadania.md
  14-estados-e-municipios-metodo.md
  15-goias-e-goiania.md
fontes/
  fontes-oficiais.md           Catálogo de fontes por tipo
  registro-de-verificacao.md   O que foi conferido, quando e onde
```

## Legenda de status usada nos módulos

| Marca | Significado |
|---|---|
| **V** | Verificado em fonte oficial na data indicada. |
| **S** | Conferido em fonte secundária confiável (site oficial bloqueou a leitura automatizada). Reconferir na fonte oficial. |
| **C** | A conferir: citação conhecida, ainda não validada nesta base, ou com detalhe pendente. Nunca usar sem checar. |

## Aviso

Material informativo e de apoio à pesquisa. Não constitui parecer jurídico. A responsabilidade pela citação em peças e orientações é de quem a utiliza, após conferência na fonte oficial.

## Autoria e contribuições

Idealização e curadoria: **Hebert Batista Alves**, advogado (Batista & Vaz Advocacia, Goiânia-GO), ativista da pauta da pessoa com deficiência.

Contribuições são bem-vindas, especialmente de legislação estadual e municipal. Veja [`CONTRIBUTING.md`](CONTRIBUTING.md).

Licença: [CC BY 4.0](LICENSE.md). Pode copiar, adaptar e redistribuir, inclusive comercialmente, com atribuição.
