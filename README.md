# Obsidian Pulse

Tema dark para IDEs JetBrains com paleta calibrada para longas sessões de código.

**Compatível com:** IntelliJ IDEA, PyCharm, WebStorm, CLion, GoLand, Rider, PhpStorm, DataGrip, Android Studio (build 231+)

---

## Instalação via Custom Plugin Repository (recomendado)

Dessa forma a IDE avisa automaticamente quando houver atualização.

1. Na IDE, vá em **Settings → Plugins → ⚙️ → Manage Plugin Repositories...**
2. Adicione a URL:
   ```
   https://raw.githubusercontent.com/SEU_USUARIO/obsidian-pulse-theme/main/updatePlugins.xml
   ```
3. Na aba **Marketplace**, pesquise `Obsidian Pulse` e instale
4. Reinicie a IDE
5. **Settings → Appearance → Theme** → selecione **Obsidian Pulse**

---

## Instalação manual (sem atualizações automáticas)

1. Baixe o `.zip` na aba [Releases](../../releases/latest)
2. **Settings → Plugins → ⚙️ → Install Plugin from Disk...**
3. Selecione o `.zip`

---

## Publicar uma atualização

1. Edite os arquivos em `plugin-src/themes/`
2. Atualize a `<version>` em `plugin-src/META-INF/plugin.xml`
3. Faça push para `main` — o GitHub Actions cuida do resto

---

## Paleta de cores

| Papel | Hex |
|---|---|
| Background principal | `#12151A` |
| Surface | `#181C23` |
| Accent (azul) | `#6E9EF5` |
| Keywords (pink) | `#D46B9E` |
| Strings (verde) | `#50C4A1` |
| Numbers (laranja) | `#E8915A` |
| Classes (amarelo) | `#E5C07B` |
| Errors (vermelho) | `#E06C75` |
| Types (roxo) | `#B07ED8` |
