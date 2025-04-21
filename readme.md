<p align='center'>
  <img src="https://github.com/user-attachments/assets/1788dc39-cd40-4ef1-bd64-d1d4dbec0672">
</p>

<p align='center'>
  Ferramenta de consulta de estatísticas do League of Legends baseada na API LCU
</p>

<div align="center">

  [![Licença](https://img.shields.io/github/license/Zzaphkiel/Seraphine?style=flat&label=License)](https://github.com/Zzaphkiel/Seraphine/blob/main/LICENSE)
  [![Forks](https://img.shields.io/github/forks/Zzaphkiel/Seraphine?style=flat&label=Forks)](https://github.com/Zzaphkiel/Seraphine/forks)
  [![Stars](https://img.shields.io/github/stars/Zzaphkiel/Seraphine?style=flat&label=Stars)](https://github.com/Zzaphkiel/Seraphine/stargazers)
  [![Downloads](https://img.shields.io/github/downloads/Zzaphkiel/Seraphine/total?style=flat&label=Downloads)](https://github.com/Zzaphkiel/Seraphine/releases)

</div>

## Guia Rápido 🤗
### Usando o programa empacotado
Clique [aqui](https://github.com/Miuguel/Seraphine/releases/latest) para acessar a página de lançamento, encontre `Seraphine.7z` nos recursos listados, baixe e extraia para uma pasta, depois clique duas vezes em `Seraphine.exe` para executar.

### Ou construa localmente
Baixe o código-fonte do projeto como um arquivo `zip` e extraia para uma pasta ou use `git`:
```shell
  git clone https://github.com/Zzaphkiel/Seraphine.git
  cd Seraphine
```
Crie e ative um novo ambiente conda:
```shell
  conda create -n seraphine python=3.8
  conda activate seraphine
```
Instale as dependências:
```shell
  pip install -r requirements.txt
```
Execute `main.py` para iniciar:
```shell
  python main.py
```
### Desinstalar Seraphine 😑
Basta excluir a pasta onde o Seraphine está localizado e remover a pasta `%AppData%/Seraphine`.

## Recursos (em constante atualização) 🥰
- Consulta de estatísticas (não suporta Teamfight Tactics)
  - Consulta de estatísticas de invocadores no mesmo servidor ✅
  - Consulta automática das estatísticas dos aliados após entrar no BP ✅
  - Consulta automática das estatísticas dos oponentes após entrar na partida ✅

- Outras funcionalidades auxiliares
  - Automção de B/P
    - Aceita partidas automaticamente ✅
    - Escolhe o campeão automaticamente ✅
    - Bane campeães automaticamente ✅
    - Aceita troca de campeões automaticamente ✅

  - Exibição de dados externos
    - Mostra informações de buffs no ARAM ✅
    - Exibe rankings de campeões do OPGG ✅
    - Exibe builds e runas do OPGG e permite aplicá-las com um clique ✅

  - Funcionalidades do jogo
    - Cria salas de treinamento 5v5 personalizadas ✅
    - Especta jogos ao vivo de jogadores do mesmo servidor ✅
    - Bloqueia configurações do jogo ✅

  - Funcionalidades do cliente
    - Reconecta automaticamente após sair do jogo ✅
    - Corrige bugs de carregamento infinito no pós-jogo ✅
    - Reinicializa o cliente rapidamente ✅

  - Funcionalidades de personalização
    - Altera o fundo do perfil ✅
    - Modifica o status online ✅
    - Modifica a assinatura pessoal ✅
    - Modifica a exibição do elo no cartão de perfil ✅
    - Remove insígnias com um clique ✅
    - Remove molduras de ícones com um clique ✅

## Perguntas Frequentes (FAQ) 🧐
### Q: Posso ser banido por usar Seraphine? 😨
Seraphine usa apenas a API do cliente do LoL e **não modifica** arquivos do jogo ou lê dados da memória. Portanto, é improvável que você seja banido, mas não garantimos que isso não aconteça.

### Q: Fui banido, e agora?
Tente recorrer ou aguarde o desbloqueio 😭

### Q: Por que algumas funções estão inativas ou demoradas?
O Seraphine depende dos dados fornecidos pela API do cliente do LoL. Se houver problemas, geralmente são causados pelo servidor do LoL, não pelo Seraphine.

### Q: Por que o cliente do jogo fecha sozinho?
Suspeitamos que o cliente do jogo é sensível a algumas requisições HTTP.

## Como ajudar a melhorar o Seraphine 😘
Se encontrar bugs ou comportamentos inesperados, relate um [issue](https://github.com/Zzaphkiel/Seraphine/issues). Para novas sugestões, abra um issue ou envie um [PR](https://github.com/Zzaphkiel/Seraphine/pulls)!

## Empacotando um executável 📂
Instale `Pyinstaller` e garanta que o comando `7z` está disponível:
```shell
  pip install pyinstaller==5.13
```
Execute o script `make.ps1` para criar `Seraphine.7z`:
``` shell
  .\make -dest .
```

## Declaração da Riot 📢
Seraphine não é endossado pela Riot Games e não reflete as opiniões da Riot Games. Riot Games e suas propriedades são marcas registradas da Riot Games, Inc.

## Licença ⚖️
- O Seraphine é licenciado sob a [GPLv3](https://github.com/Zzaphkiel/Seraphine/blob/main/LICENSE) para uso não comercial.
- O uso comercial do código e arquivos binários é proibido.

