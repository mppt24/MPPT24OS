# MPPT24OS

Ecossistema de projetos em Linux para observar sistemas, gerir serviços domésticos e experimentar IA local. **MPPT24 ESCUDO** é o servidor doméstico de segurança. **MPPT24 CORE** é o motor de observação, validação e decisão técnica.

## MPPT24 ESCUDO

O ESCUDO reúne proteção de rede, serviços privados, monitorização e cópias de segurança. O infográfico mostra o inventário de software e um retrato do conjunto monitorizado em **21 de novembro de 2026**.

[![Infográfico do MPPT24 ESCUDO com Ubuntu Server, Arch Linux e o inventário de software](docs/mppt24-escudo-infografico.png)](docs/mppt24-escudo-infografico.png)

[Ver infográfico em tamanho completo](docs/mppt24-escudo-infografico.png)

## Explorar os projetos

### Publicado

| Projeto | O que está disponível |
| --- | --- |
| [MPPT24OS](https://github.com/mppt24/MPPT24OS) | Portal e documentação pública do ecossistema. |
| [MPPT24 ESCUDO](#mppt24-escudo) | Infográfico do servidor, com a data da observação indicada acima. |
| [MPPT24 CORE](https://github.com/mppt24/mppt24-core) | Base operacional validada. A [primeira edição pública](https://github.com/mppt24/mppt24-core/commit/643ba1e856ae91cca32a62a33b329c7d947222da) inclui código-fonte, arquitetura, contratos e testes. |
| [MPPT24 AGI Absoluta](https://github.com/mppt24/mppt24-agi-absoluta) | Base de chat local validada, com calculadora, conversões e respostas por temas. |

Para explorar ou testar o código publicado, começa pelo [README do CORE](https://github.com/mppt24/mppt24-core#readme).

### Em evolução

| Projeto | Trabalho em curso |
| --- | --- |
| MPPT24 CORE | Empacotamento e instalador público. |
| [Configuração do servidor](https://github.com/mppt24/mppt24-server-setup) | Rotinas de configuração e atualização. |
| [Rust no Termux](https://github.com/mppt24/rustlinux-termux-installer) | Verificação do ambiente e instalador. |
| [MPPT24 Bootstrap](https://github.com/mppt24/mppt24-bootstrap) | Documentação e preparação do arranque dos componentes. |

### Em avaliação

O AI Hub é um protótipo para testes locais com modelos de IA. As integrações externas do AGI Absoluta continuam em avaliação.

### Critério de publicação

Uma versão entra na lista de entregas publicadas quando está validada e a versão a disponibilizar está identificada. Um projeto com uma base validada pode ter trabalhos em evolução em paralelo. Os ensaios em avaliação só passam a entregas depois de validados. A manutenção destina-se às correções e atualizações de versões já publicadas.

## Contribuir

Abre uma [issue](https://github.com/mppt24/MPPT24OS/issues) para sugerir uma melhoria nesta página ou para perguntar onde colaborar. Para alterações ao código, usa o repositório do componente. Inclui o contexto necessário para reproduzir o problema e usa dados de exemplo quando a informação vier de um servidor real.

## Licenças

O MPPT24OS usa [MIT](LICENSE). O MPPT24 CORE usa [AGPL-3.0](https://github.com/mppt24/mppt24-core/blob/main/LICENSE). Os módulos [Configuração do servidor](https://github.com/mppt24/mppt24-server-setup/blob/main/LICENSE) e [Rust no Termux](https://github.com/mppt24/rustlinux-termux-installer/blob/main/LICENSE) usam MIT. O AI Hub ainda não tem um ficheiro de licença publicado.
