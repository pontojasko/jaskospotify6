<p align="center"><img src="Resources/Icon@2x.png" width="96" alt="Ícone do JaskoSpotify"></p>

<h1 align="center">JaskoSpotify</h1>

<p align="center"><b>Spotify de volta ao iOS 5 e 6.</b><br>Cliente nativo e independente para iPhone, iPod touch e iPad com jailbreak.</p>

---

O JaskoSpotify traz sua conta Spotify para aparelhos com iOS 5 e 6: biblioteca, playlists, fila e músicas offline. O aplicativo roda no próprio aparelho e usa sua conta existente.

JaskoSpotify é baseado no [Spotify6](https://github.com/iKiWY/Spotify6), que por sua vez é baseado no [riff](https://github.com/SecondTrack/riff), de Second Track. O riff forneceu a conexão com o Spotify e a base de reprodução de áudio; o Spotify6 desenvolveu essa base em um cliente nativo para iOS 5 e 6. Agradecemos aos dois projetos e a seus colaboradores.

<table align="center">
  <tr>
    <td align="center" valign="top"><b>Início</b><br><img src="docs/screenshots/home.png" width="190" alt="Início"></td>
    <td align="center" valign="top"><b>Reprodução</b><br><img src="docs/screenshots/player.png" width="190" alt="Tela de reprodução"></td>
    <td align="center" valign="top"><b>Fila</b><br><img src="docs/screenshots/queue.png" width="190" alt="Fila de reprodução"></td>
    <td align="center" valign="top"><b>Álbum</b><br><img src="docs/screenshots/album.png" width="190" alt="Página de álbum"></td>
  </tr>
  <tr>
    <td align="center" valign="top"><b>Menu da faixa</b><br><img src="docs/screenshots/menu.png" width="190" alt="Menu de faixa"></td>
    <td align="center" valign="top"><b>Busca</b><br><img src="docs/screenshots/search.png" width="190" alt="Busca"></td>
    <td align="center" valign="top"><b>Artista</b><br><img src="docs/screenshots/artist.png" width="190" alt="Página de artista"></td>
    <td align="center" valign="top"><b>Central de Notificações</b><br><img src="docs/screenshots/widget.png" width="190" alt="Widget da Central de Notificações"></td>
  </tr>
</table>

### No iPad

O app é universal. No iPad, há uma interface própria com barra lateral, controles de reprodução na parte inferior e player em tela cheia, tanto na orientação retrato quanto paisagem.

<table align="center">
  <tr>
    <td align="center" valign="top"><b>Início (retrato)</b><br><img src="docs/screenshots/ipad-home-portrait.png" width="300" alt="Início no iPad em retrato"></td>
    <td align="center" valign="top"><b>Início (paisagem)</b><br><img src="docs/screenshots/ipad-home-landscape.png" width="400" alt="Início no iPad em paisagem"></td>
  </tr>
  <tr>
    <td align="center" valign="top"><b>Player (retrato)</b><br><img src="docs/screenshots/ipad-player-portrait.png" width="300" alt="Player no iPad em retrato"></td>
    <td align="center" valign="top"><b>Player e fila (paisagem)</b><br><img src="docs/screenshots/ipad-player-queue-landscape.png" width="400" alt="Player e fila no iPad em paisagem"></td>
  </tr>
  <tr>
    <td align="center" valign="top"><b>Playlist (paisagem)</b><br><img src="docs/screenshots/ipad-playlist-landscape.png" width="400" alt="Playlist no iPad em paisagem"></td>
    <td align="center" valign="top"><b>Álbum (paisagem)</b><br><img src="docs/screenshots/ipad-album-landscape.png" width="400" alt="Álbum no iPad em paisagem"></td>
  </tr>
</table>

### Visual clássico do iOS

Escolha entre o tema escuro inspirado no Spotify e o tema Classic iOS, inspirado nos apps de sistema do iOS 6.

<table align="center">
  <tr>
    <td align="center" valign="top"><b>Início</b><br><img src="docs/screenshots/classic-ios/iphone-home.png" width="190" alt="Tema clássico: início"></td>
    <td align="center" valign="top"><b>Player</b><br><img src="docs/screenshots/classic-ios/iphone-player.png" width="190" alt="Tema clássico: player"></td>
    <td align="center" valign="top"><b>Álbum</b><br><img src="docs/screenshots/classic-ios/iphone-album.png" width="190" alt="Tema clássico: álbum"></td>
  </tr>
</table>

<table align="center">
  <tr>
    <td align="center" valign="top"><b>Início no iPad</b><br><img src="docs/screenshots/classic-ios/ipad-home.png" width="400" alt="Tema clássico: início no iPad"></td>
    <td align="center" valign="top"><b>Playlist no iPad</b><br><img src="docs/screenshots/classic-ios/ipad-playlist.png" width="400" alt="Tema clássico: playlist no iPad"></td>
  </tr>
  <tr>
    <td align="center" valign="top" colspan="2"><b>Player no iPad</b><br><img src="docs/screenshots/classic-ios/ipad-player.png" width="400" alt="Tema clássico: player no iPad"></td>
  </tr>
</table>

> [!IMPORTANT]
> JaskoSpotify é um projeto independente, sem vínculo com o Spotify. O app usa interfaces não documentadas do Spotify com a sua própria conta. Isso pode contrariar os Termos de Uso e pode deixar de funcionar se os serviços mudarem. É necessário Spotify Premium. Use por sua conta e risco.

## Recursos

### Biblioteca e descoberta

- Início com playlists, álbuns, artistas e faixas reproduzidos recentemente, inclusive pelo próprio aparelho.
- Busca de faixas, álbuns, artistas e playlists públicas, com histórico de buscas. A busca exige uma chave própria e gratuita da API de desenvolvedor do Spotify.
- Páginas de artista, álbum e playlist, com capas grandes opcionais.
- Capas oficiais para playlists criadas pelo Spotify, como Blends e Your Top Songs.
- Biblioteca com Liked Songs e playlists; crie playlists, adicione faixas, renomeie as suas e salve ou remova playlists da biblioteca.
- Reprodução de playlists completas, mesmo quando têm mais faixas que a primeira página carregada.

### Player e fila

- Início rápido: a faixa começa a tocar enquanto o restante do áudio continua carregando; uma linha verde indica o progresso.
- Fila com “Próximas na fila” e “A seguir”: reordene por arrastar, adicione ou remova por gesto e escolha se a reprodução deve parar ao final.
- Repetição das faixas adicionadas à fila e reprodução contínua da lista “A seguir” podem ser controladas na tela da fila.
- Mini player com gesto para avançar; player completo que pode ser fechado arrastando para baixo.
- Reprodução gapless, preparando a próxima faixa antes de a atual terminar.
- Equalizador gráfico nativo de 10 bandas, com ajuste por frequência, pré-amplificação e opção de desativar ou zerar as bandas.
- Qualidade configurável separadamente para streaming e downloads em Wi-Fi e rede móvel: 96, 160 ou 320 kbps. Downloads móveis também podem ser desligados.
- Skin escura Spotify ou Classic iOS; layout próprio de iPad em retrato e paisagem; suporte às telas de 4 polegadas do iPhone 5 e iPod touch 5.
- Cover Flow ao girar o iPhone; no iPad, disponível pela barra lateral.

### Offline e downloads

- Salve playlists, álbuns e faixas para ouvir offline. Downloads podem ser retomados e continuam em segundo plano quando essa opção está ligada.
- A tela Downloads mostra o que está na fila e as faixas salvas; é possível pausar, retomar ou cancelar os itens restantes. Faixas já concluídas permanecem no aparelho.
- Downloads podem aguardar uma conexão Wi-Fi quando a qualidade de download móvel está em “Off”.
- Cache de até 500 MB para faixas reproduzidas recentemente, permitindo reproduzi-las novamente sem baixar o áudio outra vez.
- Limpeza de todos os downloads offline e limpeza separada do cache.
- **Experimental — salvar streams móveis em Downloads:** ao ativar a opção em Ajustes, faixas reproduzidas pela rede móvel também entram na fila de downloads, na qualidade móvel configurada para download. Isso consome dados móveis adicionais e espaço no aparelho; deixe a qualidade móvel em “Off” para não salvar automaticamente.
- **Experimental — downloads rotativos de Liked Songs:** o app pode baixar faixas curtidas aleatórias e renovar esse conjunto diariamente, uma faixa por vez. As antigas são removidas conforme novas ficam prontas, preservando faixas baixadas manualmente e as compartilhadas com outros downloads. Configure repetição e limite diário em Ajustes; o limite pode ser ilimitado, mantendo ao menos 256 MB livres, ou definido em 256 MB, 512 MB ou 1 GB.

### Integrações e conta

- Widget opcional da Central de Notificações com capa, faixa, contexto (“Reproduzindo de…”) e controles. Pode ser desligado em Ajustes; widgets não são compatíveis com iPad no iOS 5.
- Integração opcional com Last.fm para enviar reproduções qualificadas ao perfil. Reproduções feitas offline ficam na fila e são enviadas quando a conexão volta.
- Login por código em [spotify.com/pair](https://spotify.com/pair), sem digitar sua senha do Spotify no app. A sessão fica na pasta privada do aplicativo e é renovada automaticamente.
- Ferramenta de diagnóstico em Ajustes para ajudar a identificar problemas de conexão ou reprodução.

## Requisitos

| | Requisito |
|---|---|
| Aparelho | iPhone, iPod touch ou iPad ARMv7 com iOS 5 ou 6 e jailbreak, incluindo iPhone 5 e iPod touch 5. Testado em iPhone 3GS com iOS 6 e em iPad 1 e iPod touch 3G com iOS 5.1.1 em emulador. |
| Instalação | AppSync; o JaskoSpotify é instalado como um app normal. |
| Conta | Spotify Premium. |
| Busca | Chave própria e gratuita de desenvolvedor do Spotify. O app orienta a criação. |
| Last.fm | Opcional. Configure credenciais de API próprias durante o build; veja abaixo. |

## Primeiro acesso

O JaskoSpotify **nunca pede sua senha**. Ao abrir pela primeira vez, ele mostra um código curto. Digite-o em [spotify.com/pair](https://spotify.com/pair) em outro aparelho para autorizar a conta.

## Compilar

É necessário [Theos](https://theos.dev) e o SDK iPhoneOS 9.3. O app tem deployment target iOS 5.0 e é compilado para iOS 5 e 6 com `-Werror`.

```sh
# Baixa a versão oficial do Mbed TLS, valida o SHA-256 e compila para ARMv7
vendor/mbedtls/fetch.sh
vendor/mbedtls/build.sh

# Cria o IPA de release e instala via USB (ideviceinstaller + AppSync)
scripts/install.sh
```

Um `gmake package` normal gera uma build de desenvolvimento com um gancho de teste adicional (`music/App/MMDebug.m`) para controle via SSH. Builds de release não incluem esse gancho.

### Last.fm

Para habilitar o Last.fm, copie `music/Spot/MMLastFMAppConfig.h.example` para `music/Spot/MMLastFMAppConfig.local.h` e preencha sua chave e seu segredo de API do Last.fm. O arquivo local é ignorado pelo Git. Depois, compile o app e conecte sua conta pela seção Last.fm em Ajustes.

### Widget da Central de Notificações

O widget em `widget/` é opcional. Compile com `gmake package FINALPACKAGE=1` dentro da pasta, instale o `.deb` no aparelho com `dpkg -i`, faça respring e ative em Ajustes do iOS → Notificações. O próprio app também permite desativá-lo.

### Verificação de playlists

Consulte o [roteiro de verificação de playlists](docs/playlist-verification.md) para os testes em aparelho: paginação, filas com muitas faixas, biblioteca, falhas de escrita na conta e funcionamento offline.

## Funcionamento

O JaskoSpotify autentica em um ponto de acesso do Spotify de forma semelhante aos clientes oficiais e mantém a conexão aberta para obter metadados e as chaves necessárias à reprodução. A biblioteca usa os mesmos serviços internos dos apps oficiais; somente a busca usa a Web API pública e a chave de desenvolvedor do usuário.

As faixas são recebidas criptografadas da CDN do Spotify, descriptografadas no aparelho e decodificadas por software a partir de Ogg Vorbis. A qualidade depende das opções de streaming e download selecionadas. Como o iOS 5 e 6 não conseguem negociar conexões seguras com alguns serviços atuais, o app inclui Mbed TLS com verificação de certificados para o tráfego HTTPS.

O widget é um plugin pequeno do SpringBoard: lê a reprodução atual do sistema e envia comandos de controle equivalentes aos da tela bloqueada.

## Créditos

O JaskoSpotify é baseado no **[Spotify6](https://github.com/iKiWY/Spotify6)**, que construiu um cliente nativo para iOS 5 e 6 a partir do **[riff](https://github.com/SecondTrack/riff), de Second Track**. O riff tornou possível a reprodução do Spotify no iOS 6 e forneceu o trabalho de protocolo e o pipeline de áudio inicial. Nosso agradecimento aos autores e colaboradores do Spotify6 e do riff por essa fundação.

- [stb_vorbis](https://github.com/nothings/stb), de Sean Barrett: decodificação Ogg Vorbis (domínio público / MIT).
- [Mbed TLS](https://github.com/Mbed-TLS/mbedtls): TLS (Apache 2.0).
- Cifra Shannon, portada do rust-shannon no [librespot](https://github.com/librespot-org/librespot) (MIT).
- A abordagem para o equalizador de áudio foi inspirada no [StreamingKit](https://github.com/tumtumtum/StreamingKit), de Thong Nguyen.
- [Material Icons](https://github.com/google/material-design-icons), ícone `music_note` (Apache 2.0).

Mais detalhes em [NOTICE](NOTICE).

## Licença

GNU GPL v3.0. Consulte [LICENSE](LICENSE).

Spotify é uma marca registrada da Spotify AB. iPhone e iOS são marcas da Apple Inc. JaskoSpotify não é afiliado, patrocinado ou endossado pelo Spotify ou pela Apple.
