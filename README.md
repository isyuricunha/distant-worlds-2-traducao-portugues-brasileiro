# Tradução PT-BR para Distant Worlds 2

Este repositório contém arquivos traduzidos para **Português do Brasil (PT-BR)**.

A instalação é feita **substituindo arquivos** dentro da pasta do jogo:

`Distant Worlds 2\data`

Você não precisa instalar programas extras. Basta copiar os arquivos corretamente.

---

## Antes de começar (importante)

- **Feche o jogo** antes de mexer nos arquivos.
- Se você já tinha outra tradução instalada, é recomendado **remover a tradução antiga antes** (veja a seção **Remover / voltar ao original**).
- Faça um **backup** para poder voltar ao original se quiser.

### Como fazer backup

1. Abra a pasta `Distant Worlds 2\data` (instruções abaixo).
2. Crie uma pasta chamada, por exemplo: `Backup_Original`.
3. Copie para esse backup os arquivos que você vai substituir.
   - Dica: você pode copiar a pasta `data` inteira, se tiver espaço.

---

## Onde fica a pasta do jogo (exemplos)

Você precisa encontrar a pasta do jogo e abrir **a pasta `data`**.

### Steam

Caminhos comuns:

- `C:\Program Files (x86)\Steam\steamapps\common\Distant Worlds 2\data`
- `D:\SteamLibrary\steamapps\common\Distant Worlds 2\data`

Dica (Steam):

1. Abra a Steam.
2. Vá em **Biblioteca**.
3. Clique com o botão direito em **Distant Worlds 2**.
4. **Gerenciar** -> **Explorar arquivos locais**.
5. Abra a pasta `data`.

### GOG

Caminhos comuns:

- `C:\GOG Games\Distant Worlds 2\data`
- `C:\Program Files (x86)\GOG Galaxy\Games\Distant Worlds 2\data`

### Epic Games

Caminhos comuns:

- `C:\Program Files\Epic Games\DistantWorlds2\data`
- `D:\Epic Games\DistantWorlds2\data`

### Instalação manual / “portable” / outros

Exemplo comum:

- `C:\Games\Distant Worlds 2\data`

---

## Instalação

### O que você deve copiar

Você deve copiar **apenas os arquivos traduzidos** para dentro de `Distant Worlds 2\data`.

Neste repositório, os arquivos traduzidos ficam na pasta:

- `pt\`

Ou, dependendo de como você baixou, pode existir um pacote compactado:

- `pt.zip`
- `pt.7z`

Se você estiver usando um `.zip` ou `.7z`, primeiro **extraia** o conteúdo.

### Passo a passo (recomendado)

1. Abra a pasta `pt\` (ou extraia o pacote e abra a pasta extraída).
2. **Selecione todos os arquivos** dentro dessa pasta.
3. Copie (`Ctrl+C`).
4. Abra a pasta do jogo: `Distant Worlds 2\data`.
5. Cole (`Ctrl+V`).
6. Quando o Windows perguntar para **substituir arquivos**, escolha:
   - **Substituir os arquivos no destino**

Importante:

- O correto é que os arquivos fiquem **direto dentro de `data`**, por exemplo:
  - `...\Distant Worlds 2\data\GameText.txt`
  - `...\Distant Worlds 2\data\GameEvents.xml`
- Não é para ficar assim:
  - `...\Distant Worlds 2\data\pt\GameText.txt`

---

## Como confirmar que deu certo

- Abra o jogo e verifique se os textos principais (menus, descrições, eventos, etc.) aparecem em **Português**.
- Se o jogo continuar em Inglês, normalmente é um destes motivos:
  - Você copiou os arquivos para a pasta errada.
  - Os arquivos ficaram dentro de uma subpasta (por exemplo, `data\pt\`).
  - O Windows não substituiu os arquivos (faltou aceitar a substituição).

---

## Atualizar a tradução

1. (Recomendado) Faça backup dos arquivos atuais.
2. Copie a versão nova por cima, do mesmo jeito (colando em `Distant Worlds 2\data` e aceitando substituir).

---

## Remover / voltar ao original

Você tem algumas opções.

### Opção A: Restaurar seu backup

- Copie de volta os arquivos que você salvou no `Backup_Original` para `Distant Worlds 2\data`.

### Opção B: Verificar / reparar arquivos do jogo

Isso costuma restaurar automaticamente os arquivos originais.

- Steam: **Propriedades** -> **Arquivos instalados** -> **Verificar integridade dos arquivos do jogo**
- GOG Galaxy: opção de **Repair/Verify** (verificar/reparar) na tela do jogo
- Epic Games: opção **Verify** (verificar) na biblioteca

### Opção C: Reinstalar

Se nada funcionar, reinstalar o jogo também volta ao original.

---

## Observações

- Esta tradução funciona por **substituição de arquivos** na pasta `data`.
- Se o jogo atualizar, pode ser necessário **instalar a tradução novamente**.
