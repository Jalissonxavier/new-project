# VI

Bem-vindo ao repositório de Cheatsheets para dominar o editor VI! Aqui você encontrará uma coleção de dicas rápidas e úteis para utilizar o editor VI de maneira eficiente e produtiva.

## Funções de procura

```
/<expressão> => começa a procura pelo início do arquivo do termo "expressão"
?<expressão> => começa a procura pelo final do arquivo do termo "expressão"
n => procura a próxima palavra
N => inverte o sentido da procura

```

## Movimentação e inserção de texto

```
:3,9d => apaga as linhas de 3 a 9
:4,7m 11 => move as linhas de 4 a 7 para a linha 11
:2,6t 11 => copia as linhas de 2 a 6 para a linha 11
:2,7w <file> => escreve as linhas de 2 a 7 para o arquivo "file"
:r <file> => lê o arquivo 'file' e insere seu conteúdo no documento atual.

```

## Adicionar/apendar texto

```
a => apendar texto depois do cursor
A => apendar texto no final da linha
i => inserir texto antes do cursor
I => inserir texto no começo da linha

```

## Mudar texto

```
cw => muda uma palavra
3cw => muda 3 palavras
C => muda uma linha
r => sobrescreve um caractere
R => sobrescreve a linha inteira
:%s/<old>/<new>/g => muda todas as ocorrências da expressão "old" para a expressão "new"

```

## Cancelar uma função

```
u => desfazer a última operação
. => repete a última operação

```

## Salvar arquivos e sair

```
:w => salvar da memória (buffer) para o disco (arquivo)
:q => sair do editor
:wq => salvar e sair do editor
:x => salvar e sair do editor
:e! => reeditar, desprezando as mudanças
ZZ => salvar e sair do editor

```

## Movimentação de tela/linha

```
0 => vai direto para o começo da linha
) ou $ => vai direto para o final da linha
g (Linux) => vai para a primeira linha do arquivo
G => vai para a última linha do arquivo
5G => vai para a linha 5

```

## Copiar e inserir textos

```
yy => copia um linha
5yy => copia 5 linhas
p => cola abaixo do cursor
P => cola acima do cursor

```

## Adicionar novas linhas

```
o => abre uma nova linha para edição abaixo do cursor
O => abre uma nova linha para edição acima do cursor

```

## Apagar texto

```
x => apaga um caractere
dw => apaga uma palavra
dd => apaga uma linha
5dd => apaga 5 linhas
dG => apaga do cursor até o final do arquivo

```

## Configurações da sessão

```
:set nu => mostra o número de linhas
:set nonu => desliga o comando acima
:set all => mostra todas as configurações
:set list => mostra os caracteres ocultos
:set paste => ativa

```

## Rolagem do texto

```
CTRL+f => rola uma tela para baixo
CTRL+b => rola uma tela atrás
CTRL+d => rola meia-tela (1/2) para baixo
CTRL+u => rola meia-tela (1/2) atrás

```

[Link Documentação](https://www.vim.org/docs.php)
