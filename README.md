# Dev English Quest

Jogo web para praticar o inglês usado no dia a dia de quem trabalha com tecnologia. Foi criado para alunos do curso Técnico em Desenvolvimento de Sistemas da Firjan SENAI Petrópolis e funciona direto no navegador do computador, sem instalação e sem login.

**Jogar:** https://deisesch.github.io/dev-english-quest/

## Como funciona

O aluno entra como estagiário na NovaByte, uma empresa fictícia, e sobe de cargo a cada mundo concluído.

1. Digita o nome completo, escolhe a turma e um robô.
2. Faz um teste de nível com 24 questões. O teste não vale nota e não muda o ponto de partida.
3. Joga as fases em ordem. Cada fase leva de 3 a 5 minutos.
4. Revisa no baralho as palavras que errou.

## Conteúdo

São 6 mundos, 30 fases e 252 atividades.

| Mundo | Tema | O que treina |
|---|---|---|
| 1. Onboarding | Primeiro dia de trabalho | Cumprimentos, equipamentos, botões, arquivos e pastas |
| 2. Error messages | Suporte | Mensagens de erro reais de Python, MySQL, Git e terminal |
| 3. Code and docs | Programação | Nomes de variáveis, documentação, mensagens de commit e comentários |
| 4. Support tickets | Atendimento ao cliente | Passado, relato de bug, perguntas e respostas educadas |
| 5. Team chat | Trabalho em equipe | Reunião diária, pedidos, prazos e e-mails |
| 6. Job ready | Carreira | README, anúncios de vaga, perfil profissional e entrevista |

## Recursos

- Cinco tipos de atividade: múltipla escolha, ligar pares, digitar, ordenar palavras e achar a palavra errada.
- Estrelas, XP, combo de acertos e conquistas.
- Baralho de revisão com as palavras erradas.
- Código de progresso para continuar em outro computador.
- Modo B: letras maiores, sem cronômetro, sem animações e com dicas. O conteúdo e os critérios são os mesmos.
- Navegação por teclado (teclas 1 a 4 e Enter).

## Tecnologias

- HTML, CSS e JavaScript puro, em um único arquivo e sem dependências.
- Ilustrações em SVG, desenhadas no próprio código.
- Google Apps Script e Google Planilhas para receber os resultados.
- GitHub Pages para a hospedagem.

## Estrutura do repositório

| Arquivo | Descrição |
|---|---|
| `index.html` | O jogo completo |
| `Code.gs` | Script da planilha: recebe os dados e monta os relatórios de acompanhamento |
| `GUIA-DE-INSTALACAO.md` | Passo a passo de instalação e uso para o professor |
| `README.md` | Este arquivo |

## Como usar em outra turma

1. Faça um fork deste repositório ou baixe os arquivos.
2. Crie uma planilha Google e publique o `Code.gs` como App da Web.
3. No `index.html`, troque o valor de `ENDPOINT_URL` pela URL do seu App da Web.
4. Ative o GitHub Pages em Settings > Pages.

O passo a passo completo está em `GUIA-DE-INSTALACAO.md`.

## Privacidade

- O jogo envia nome completo, turma e resultados somente para a planilha do professor.
- Nenhum dado de aluno fica neste repositório.
- A planilha deve ter acesso restrito ao professor e à coordenação (LGPD).

## Limitações conhecidas

- As respostas ficam no código-fonte. O teste de nível deve ser aplicado em sala, com acompanhamento.
- O jogo não tem senha: em computador compartilhado, um aluno pode abrir o perfil de outro.
- O teste de nível é um diagnóstico de sala, não um exame certificado.

## Autoria

Desenvolvido por [deisesch](https://github.com/deisesch) para o curso Técnico em Desenvolvimento de Sistemas da Firjan SENAI Petrópolis, com apoio de inteligência artificial (Claude, da Anthropic) na programação e na elaboração das atividades.

## Licença

A definir.
