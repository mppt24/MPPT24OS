# MPPT24OS

Ecossistema de projetos em Linux para observar sistemas, gerir serviços domésticos e experimentar IA local. **MPPT24 ESCUDO** é o servidor doméstico de segurança. **MPPT24 CORE** é o motor de observação, validação e decisão técnica.

## MPPT24 ESCUDO

O ESCUDO reúne proteção de rede, serviços privados, monitorização e cópias de segurança. O infográfico mostra o inventário de software e um retrato do conjunto monitorizado em **21 de novembro de 2026**.

[![Infográfico do MPPT24 ESCUDO com Ubuntu Server, Arch Linux e o inventário de software](docs/mppt24-escudo-infografico.png)](docs/mppt24-escudo-infografico.png)

[Ver infográfico em tamanho completo](docs/mppt24-escudo-infografico.png)

## Explorar os projetos

| Projeto | O que encontras | Estado |
| --- | --- | --- |
| [MPPT24OS](https://github.com/mppt24/MPPT24OS) | Apresentação do ecossistema e documentação pública do ESCUDO. | Portal do projeto |
| [MPPT24 CORE](https://github.com/mppt24/mppt24-core) | Código, arquitetura, contratos e testes para observação e decisão em Linux. | Base operacional publicada. Instalação automatizada em preparação. |
| [AI Hub](https://github.com/mppt24/ai-hub-publish) | Protótipo de uma API para conversar com modelos locais através de Ollama. | Protótipo para teste local |
| [Configuração do servidor](https://github.com/mppt24/mppt24-server-setup) | Esboços dos scripts de configuração e atualização. | Em preparação |
| [Rust no Termux](https://github.com/mppt24/rustlinux-termux-installer) | Esboços dos scripts de verificação e instalação. | Em preparação |

Para explorar o código, começa pelo [README do CORE](https://github.com/mppt24/mppt24-core#readme). Lá encontras os requisitos, a arquitetura e um exemplo de execução dos testes. Para conhecer o ESCUDO, começa pelo infográfico acima.

## Contribuir

Abre uma [issue](https://github.com/mppt24/MPPT24OS/issues) para sugerir uma melhoria nesta página ou para perguntar onde colaborar. Para alterações ao código, usa o repositório do componente. Inclui o contexto necessário para reproduzir o problema e usa dados de exemplo quando a informação vier de um servidor real.

## Licenças

O MPPT24OS usa [MIT](LICENSE). O MPPT24 CORE usa [AGPL-3.0](https://github.com/mppt24/mppt24-core/blob/main/LICENSE). Os módulos [Configuração do servidor](https://github.com/mppt24/mppt24-server-setup/blob/main/LICENSE) e [Rust no Termux](https://github.com/mppt24/rustlinux-termux-installer/blob/main/LICENSE) usam MIT. O AI Hub ainda não tem um ficheiro de licença publicado.
