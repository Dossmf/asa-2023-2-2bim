# SMB

O Samba é uma implementação do protocolo SMB/CIFS para sistemas operacionais Unix/Linux, permitindo a interoperabilidade com sistemas Windows.

**Uso Comum:**

Amplamente utilizado em ambientes corporativos para facilitar a colaboração entre sistemas Linux e Windows, permitindo o compartilhamento de recursos.
O Samba desempenha um papel essencial em ambientes heterogêneos, promovendo a comunicação e o compartilhamento de recursos entre sistemas Linux e Windows.


## Instalação

Abra o terminal:

Vá até o menu e procure por "Terminal" ou pressione Ctrl + Alt + T para abrir o terminal.
Atualize a lista de pacotes:

Antes de instalar qualquer coisa, é uma boa prática atualizar a lista de pacotes disponíveis. Digite o seguinte comando e pressione Enter:


```
sudo apt update

```

Depois você vai digitar o comando de instalação.

```
sudo apt install samba

```

Editar o arquivo smb.conf:

```
sudo nano /etc/samba/smb.conf
```

Adicionar Configurações:

Adicione as seguintes configurações ao final do arquivo smb.conf:

## Configuração

Incluir o(s) nome(s) e o conteúdo do(s) arquivo(s) de configuração.

1. Criar 2 grupos para dois de seus sobrenomes;
2. Criar 4 usuários, dois para cada um dos sobrenomes;
3. Compartilhar duas pastas com dois de seus sobrenome, compartilhado para o grupo com o sobrenome correspondente.

## Teste


