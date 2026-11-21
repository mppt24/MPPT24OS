# MPPT24OS

Projetos Linux para proteger uma rede doméstica, acompanhar a saúde de um servidor e experimentar aplicações de IA local.

## Explorar os projetos

### Publicado

- **Ver o software do servidor doméstico.** O infográfico do ESCUDO pode ser visto diretamente nesta página. [Ver o MPPT24 ESCUDO](#mppt24-escudo)
- **Experimentar uma aplicação local.** O AGI Absoluta é um protótipo de chat com calculadora e conversor. O guia indica o que precisas, como abrir a página e o resultado a esperar. [Experimentar o AGI Absoluta](https://github.com/mppt24/mppt24-agi-absoluta#experimentar)
- **Perceber como se observa um sistema Linux.** O CORE tem código, documentação e testes. O instalador público está em preparação. [Primeiros passos no CORE](https://github.com/mppt24/mppt24-core#primeiros-passos)

[Guias dos 16 repositórios públicos](GUIA.md#guias-dos-reposit%C3%B3rios-p%C3%BAblicos) · [Como ler registos e confirmar testes](GUIA.md#como-ler-os-registos)

### Em evolução

- MPPT24 CORE · Empacotamento e instalador público.
- [Configuração do servidor](https://github.com/mppt24/mppt24-server-setup) · Rotinas de configuração e atualização.
- [Rust no Termux](https://github.com/mppt24/rustlinux-termux-installer) · Verificação do ambiente e instalador.
- [MPPT24 Bootstrap](https://github.com/mppt24/mppt24-bootstrap) · Documentação e preparação do arranque dos componentes.

### Em avaliação

O [AI Hub](https://github.com/mppt24/ai-hub-publish#testar-a-api-localmente) é um protótipo. Podes confirmar que o serviço responde localmente. Para experimentar o chat é preciso ligar ao Ollama. As integrações externas do AGI Absoluta continuam em avaliação.

### Critério de publicação

Uma versão entra na lista de entregas publicadas quando está validada e a versão a disponibilizar está identificada. Um projeto com uma base validada pode ter trabalhos em evolução em paralelo. Os ensaios em avaliação só passam a entregas depois de validados. A manutenção destina-se às correções e atualizações de versões já publicadas.

## MPPT24 ESCUDO

O ESCUDO reúne proteção de rede, serviços privados, monitorização e cópias de segurança. O inventário visual mostra Ubuntu Server, Arch Linux e as famílias de software registadas em **21 de novembro de 2026**. Para aprender a interpretar avisos de rede, estados de serviços e resultados de cópias, consulta os [exemplos de registos do ESCUDO](GUIA.md#como-ler-um-registo-do-escudo).

[Consultar a lista de software em texto](#software-do-escudo-em-texto)

[![Infográfico do MPPT24 ESCUDO com Ubuntu Server, Arch Linux e o inventário de software](docs/mppt24-escudo-infografico.png)](docs/mppt24-escudo-infografico.png)

[Ver infográfico em tamanho completo](docs/mppt24-escudo-infografico.png)

### Software do ESCUDO em texto

**Ubuntu Server** é o sistema principal. **Arch Linux** é apresentado como ambiente Linux. O inventário de 21 de novembro de 2026 reúne estes componentes documentados:

- **Rede e segurança.** AdGuard Home, Tailscale, WireGuard, OpenSSH, UFW, Fail2Ban e Suricata.
- **Web e dados.** Nextcloud, Samba, nginx, Apache, PHP-FPM, MySQL e Redis.
- **Monitorização e diagnóstico.** Netdata, Prometheus, Grafana, Glances, Cockpit, TShark e tcpdump.
- **Contentores, IA e aplicações.** Docker, LXD, Ollama, MPPT24IA, Mosquitto, SABnzbd e Wekan.
- **Cópias, observação e tarefas automáticas.** rsync, MPPT24 CORE, systemd, cron e Escudo Check.

O inventário lista os componentes documentados. O estado da imagem refere-se ao conjunto monitorizado nessa data. A cópia de 15 de novembro estava concluída e foram restaurados três ficheiros. O restauro integral ainda estava por validar.

## Materiais antigos neste repositório

As pastas antigas guardam apontamentos, cópias de apresentações e uma maquete. Se chegaste pelo separador **Code** e abriste uma dessas pastas, o guia indica o projeto atual correspondente. [Encontrar o projeto atual a partir de uma pasta antiga](GUIA.md#materiais-antigos)

## Contribuir

Para uma dúvida, sugestão ou erro público, abre um tópico no repositório do componente. Se a dúvida for sobre este índice, usa os [tópicos do MPPT24OS](https://github.com/mppt24/MPPT24OS/issues).

Num erro, indica o que tentaste fazer, o que esperavas e o que aconteceu. Acrescenta a versão e uma mensagem de exemplo quando isso ajudar a reproduzir. Para uma falha de segurança no CORE, usa o [canal indicado na política de segurança](https://github.com/mppt24/mppt24-core/blob/main/SECURITY.md).

## Licenças

O MPPT24OS usa [MIT](LICENSE). O MPPT24 CORE usa [AGPL-3.0](https://github.com/mppt24/mppt24-core/blob/main/LICENSE). Os módulos [Configuração do servidor](https://github.com/mppt24/mppt24-server-setup/blob/main/LICENSE) e [Rust no Termux](https://github.com/mppt24/rustlinux-termux-installer/blob/main/LICENSE) usam MIT. O AI Hub ainda não tem um ficheiro de licença publicado.
