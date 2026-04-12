# Relatório - Coelinhos da Páscoa

> [!CAUTION]
> - Lembre-se que você <ins>**não pode utilizar ferramentas de IA para
>   escrever este relatório**</ins>

## Dados do aluno

- **Cartão UFRGS**: <mark>00242318</mark>
- **Nome**: <mark>Leonardo Junqueira</mark>

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

> [!IMPORTANT]
> - Coloque aqui todas as informações necessárias para que alguém
>   (pessoa ou ferramenta de IA) possa reproduzir os seus passos para
>   solucionar o problema
> - Escreva em formato imperativo, como se fosse um *prompt* com as
>   instruções a serem seguidas na solução do problema
> - Seja objetivo e conciso: quanto *menos palavras* você utilizar,
>   melhor
> - Seja técnico e use terminologia adequada: assuma que quem irá ler
>   os seus passos possui conhecimento de Ciência da Computação e
>   Computação Gráfica
> - Caso você queira incluir informações "longas" (como algum *prompt*
>   grande usado com alguma ferramenta de IA), crie arquivos à parte e
>   adicione links no texto (por exemplo, crie o arquivo `PROMPTS.md`
>   e adicione um link markdown `[os prompts detalhados estão
>   aqui](PROMPTS.md)`)
> - Novamente, lembre-se que você *não pode utilizar ferramentas
>   de IA para escrever este relatório*

<mark>- Gere um movimento circular do objeto bunny em torno do eixo Y.
- Gere um movimento de orbita do objeto sphere ao redor do objeto bunny.
- Gere um movimento senoidal do objeto bunny transladando em relação ao eixo Y.
- Faça 1 bunny a cada 4 fazer o movimento de rotação para frente em torno do eixo X.</mark>

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

<mark>Minha maior dificuldade foi fazer os objetos fazerem os movimentos de maneira correra, a sincronização dos pulos e o coelhos que executam a rotação pra frente caírem no chão com os pés para baixo, mas principalmente o movimento senoidal do coelho.</mark>

## Você acha que conseguiu resolver o problema de forma adequada?

<mark>Acredito que a maioria sim, algumas coisas foram na tentativa e erro, daí como funcionou não quis mais alterar.</mark>

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

<mark>Na parte do salto do coelho se colocar a função do seno dentro da função fabs(...) o coelho dá a impressão de estar realmente saltando:
float bunny_jump = fabs(sin(phase)) * 0.6f;</mark>

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

<mark>Nada a sugerir.</mark>
