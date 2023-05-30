# Linha de comando (básico)

![Wake up, Neo...](./wake-up-neo.jpg)

A linha de comando permite que um usuário navegue no sistema de arquivos de um computador e execute programas internos ou scripts personalizados. No Unix, a interface da linha de comandos é chamada de Bash, e o prompt do shell é o cifrão (`$`).

> **Observação:** Se você utiliza o sistema operacional Windows, será necessário usar o PowerShell para acompanhar os comandos demonstrados abaixo, visto que eles são específicos de sistemas baseados em Unix, tais como Linux e OSX.

## Estrutura do sistema de arquivos

<details>
  <summary>O sistema de arquivos de um computador ...</summary>
    <br>... organiza os dados armazenados no computador para que possam ser facilmente recuperados pelo usuário. Os arquivos são normalmente representados por uma estrutura semelhante a uma árvore, na qual um diretório pai pode ter vários diretórios filhos. O diretório raiz é encontrado na base da árvore.<br>
</details>

<details>
  <summary>Clique para ver um exemplo</summary><br>

  ![Estrutura de arquivos](./estrutura-de-arquivos.png)
</details>

## Comandos

### Listar (`ls`)

<details>
  <summary>O comando shell `ls` ...</summary>
    <br>... é usado para listar o conteúdo dos diretórios. Se nenhum argumento é fornecido, ele listará o conteúdo do diretório de trabalho atual.
</details>

### Opções do comando `ls`

<details>
  <summary>O comando shell `ls` pode ser combinado com as seguintes opções:</summary>
    <br>1. `ls -a` - lista todo o conteúdo do diretório, incluindo arquivos e diretórios escondidos, ou seja, aqueles que começam com um ponto (.)<br>
    2. `ls -l` - lista o conteúdo do diretório com informações adicionais, tais como permissões de execução, leitura e escrita, usuário, grupo, etc.<br>
    3. `ls -t` - lista o conteúdo do diretório por horário modificado (modificado pela última vez primeiro)<br>
    > Além disso, é possível combinar opções, tal como `ls -alt`.
</details>

### Imprimir o diretório de trabalho (`pwd`)

<details>
  <summary>O comando shell `pwd` ...</summary>
    <br>... exibe o caminho do diretório de trabalho atual.
</details>

### Alterar diretório (`cd`)

<details>
  <summary>O comando shell `cd` ...</summary>
    <br>... pode ser usado para se mover pelo sistema de arquivos do computador. Ele aceita uma variedade de argumentos, tais como:<br>
    1. o caminho completo de um determinado diretório<br>
    2. diretórios filhos do diretório atual<br>
    3. `..` para voltar ao diretório pai do diretório atual.
</details>

### Criar diretório (`mkdir`)

<details>
  <summary>O comando shell `mkdir` ...</summary>
    <br>... pode ser usado para criar um novo diretório no sistema de arquivos de acordo com seu argumento. Se um caminho for fornecido, o novo diretório será colocado no final, caso contrário, ele criará um novo diretório no diretório de trabalho atual com o nome fornecido.
</details>

### Criar novo arquivo (`touch`)

<details>
  <summary>O comando shell `touch` ...</summary>
    <br>... cria um novo arquivo no diretório de trabalho atual com o nome fornecido.
</details>

### Copiar (`cp`)

<details>
  <summary>O comando shell `cp` ...</summary>
    <br>... é usado para copiar arquivos e diretórios. Sua estrutura básica é `cp fonte destino`, onde `fonte` é o diretório ou arquivo a ser copiado para o arquivo ou diretório `destino`.
</details>

### Mover (`mv`)

<details>
  <summary>O comando shell `mv` ...</summary>
    <br>... é usado para mover um arquivo para um diretório. Ao utilizar o comando `mv` a primeira opção passada ao comando é o arquivo o qual deseja-se mover e a segunda opção é o diretório para onde queremos o mover (ex.: `mv arquivo.txt diretório-destino/`).
</details>

### Remover (`rm`)

<details>
  <summary>O comando shell `rm` ...</summary>
    <br>... é usado para deletar arquivos e diretórios. É possível passar a opção `-r` para deletar um diretório com todos seus arquivos e sub-diretórios.
</details>

### Manual (`man`)

<details>
  <summary>O comando shell `man` ...</summary>
    <br>... pode ser utilizado passando como opção outro comando qualquer (ex.: `man ls` ou `man mkdir`), para imprimir o manual completo de tal comando.
</details>

___

Feito com ❤️ por [Walmyr](https://walmyrfilho.com).
