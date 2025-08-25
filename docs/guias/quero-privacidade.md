# 🪶 ➜ Guia de Privacidade para Paranoicos

:::info Essa página ainda é um esboço. Feito com base nas recomendações do [orchestralblend](https://github.com/orchestralblend) / [orchestralblend@systemli.org](mailto:orchestralblend@systemli.org)
:::

## O básico para privacidade

- Privacidade no Firefox: Betterfox ou Arkenfox
- uBlock Origin: Javascript sempre desativado em sites novos
- Navegador baseado em Chromium: Cromite
- Não cruzar nomes em logins: sempre use nomes diferentes em todas as redes sociais, de preferência palavras aleatórias
- Colocar uma senha na BIOS do computador e trocar a senha do wi-fi/roteador (cole seu endereço IP na barra de URL do navegador)
- Criar passwords com espaços e caracteres próprios da língua portuguesa: como `ç`, `~`, `'`
- Atente-se ao [OPSEC](https://pt.m.wikipedia.org/wiki/OPSEC): **Jamais** salve senhas pelo navegador, você pode ser vítima de infostealers, utilize um gerenciador como Bitwarden ou KeePassXC
- Sempre que possìvel usar um email temporário em sites que não sejam importantes: use de um provedor como o emailnator.com ou guerrilla mail
- Caixa postal: melhor opção para receber entregas pois em caso de vazamento, o seu endereço pode ser utilizado para “doxxing”, ameaças e outros tipos de crimes. Mande entregar na sua academia ou em outro lugar que você costuma frequentar bastante e peça para alguém receber a encomenda, também é bom passar a usar codinomes em vez do seu nome real
-  Fotos, vídeos e outros arquivos: remover metadados (informações adicionais que revelam sua localização) com o exiftool ou online com o metadata2go
- Verifique a procedência de URLs suspeitas: Confira o tempo de registro, selo SSL e certifique-se de que o CNPJ/CPF fornecido na página bate com o que é repassado por sites como [registro.br](https://registro.br/tecnologia/ferramentas/), siteconfiavel.com.br ou [invertexto.com](https://www.invertexto.com/whois).

## O intermediário para privacidade

- Configurar o navegador para excluir todos os dados sempre que você for fechá-lo (histórico, cookies, senhas, etc.): isso diminui a possibilidade de ter as contas invadidas e você não precisa se preocupar em caso de acesso não autorizado ao seu dispositivo
- VPN: IVPN com Multihop ou Mullvad
- Email: systemli.org, mailbox.org + systemli.org com Thunderbird + uBlock Origin ou Cock.li (Servidor XMPP) + TailOS
- Encriptação de Email: GnuPG, GPG4WIN no Windows ou OpenKeychain no Android
- Armazenamento: HD ou SSD com Veracrypt
- Criptografia: Cryptomator e Veracrypt (AES-128-GCM, XChaCha20-Poly1305)
- Nuvem: systemli.org, NextCloud (chaves PGP, backup e armazenar KeePassXC)
- Navegador: Firefox + uBlock Origin + oisd.nl + Containers + arkenfox.js
- Chat: Lemmy, SimpleX, Mastodon, XMPP e systemli.org
- Android: GrapheneOS ou LineageOS
- Desktop: Linux com LUKS
- Provedor de dominio: Njalla, Sarek Oy, Porkbun, Cloudflare ou BasedFlare
- Meet: systemli.org, Jitsi
- Moeda digital: Monero 
- Hospedagem: Servers.guru ou Njalla
- Pesquisa: DuckDuckGo.com
- Roteador: Qualquer um com OpenWRT, recomendo Raspberry Pi 4/5 + Pi-hole com lista do oisd.nl

## O avançado para privacidade

- Onde comprar monero: [Bisq](https://github.com/bisq-network/bisq), [Cake Wallet](https://github.com/cake-tech/cake_wallet/), [Monerujo](https://github.com/m2049r/xmrwallet/), [Telegram](https://t.me/MoneroPagamentosBot?start=ref_e5874ba0587c9630), [Trocador](https://trocador.app/pt/) ou qualquer lugar que não precise de identidade (KYC).
- É possível comprar outra moeda e fazer exchange para Monero, esse tipo de troca deixa rastros insignificantes. 
Melhor caminho: **p2p** ➜ **BRL** ➜ **BTC** ➜ **XMR** ➜ [**Cold Wallet**](https://www.getmonero.org/pt-br/downloads/index.html) (sempre receber numa wallet disposable e transferir para a sua).
- Cobrar e receber por serviços: pessoalmente ou através de plataformas de escrow como o [FairTrade](http://fairfffoxrgxgi6tkcaxhxre2hpwiuf6autt75ianjkvmcn65dxxydad.onion/escrow) por exemplo.
- **O IDEAL É RODAR MONERO [LOCALMENTE](https://sethforprivacy.com/guides/run-a-monero-node/) NO SEU PRÓPRIO NODE PARA NÃO CORRER O RISCO DE SER RASTREADO.**
Mas caso você esteja usando um dispositivo móvel, uma abordagem interessante é filtrar e usar nodes conectados à rede TOR (via [ORBOT](https://github.com/guardianproject/orbot-android)) deste site aqui: https://www.ditatompel.com/monero/remote-node. [[1]](https://pirataria.link/guias/quero-privacidade#creditos)


:::warning O projeto pirataria se compromete em recomendar apenas o que na nossa visão é seguro e confiável.
:::

‎ 
‎ 
### Créditos:
- [1] [Dread (endereço onion)](https://dreadytofatroptsdj6io7l3xptbet6onoyno2yv7jicoxknyazubrad.onion/d/Monero/wiki?id=0d4cc7df)
- [OpSec Guide](https://raw.githubusercontent.com/whos-zycher/opsec-guide/refs/heads/main/guide.md)
‎ 
---
