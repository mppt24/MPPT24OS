# MPPT24OS

Projetos Linux para proteger uma rede doméstica, acompanhar a saúde de um servidor e experimentar aplicações de IA local.

## Explorar os projetos

### Publicado

- **Ver o software do servidor doméstico.** O infográfico do ESCUDO pode ser visto diretamente nesta página. [Ver o MPPT24 ESCUDO](#mppt24-escudo)
- **Experimentar uma aplicação local.** O AGI Absoluta é um protótipo de chat com calculadora e conversor. O guia indica o que precisas, como abrir a página e o resultado a esperar. [Experimentar o AGI Absoluta](https://github.com/mppt24/mppt24-agi-absoluta#experimentar)
- **Perceber como se observa um sistema Linux.** O CORE tem código, documentação e testes. O instalador público está em preparação. [Primeiros passos no CORE](https://github.com/mppt24/mppt24-core#primeiros-passos)

[Guias dos 16 repositórios públicos](GUIA.md#guias-dos-reposit%C3%B3rios-p%C3%BAblicos) · [Como ler registos e confirmar testes](GUIA.md#como-ler-os-registos)

## MPPT24 ESCUDO

O ESCUDO reúne proteção de rede, serviços privados, monitorização e cópias de segurança. O inventário visual mostra Ubuntu Server, Arch Linux e as famílias de software registadas em **21 de novembro de 2026**. Para aprender a interpretar avisos de rede, estados de serviços e resultados de cópias, consulta os [exemplos de registos do ESCUDO](GUIA.md#como-ler-um-registo-do-escudo).

[![Infográfico do MPPT24 ESCUDO com Ubuntu Server, Arch Linux e o inventário de software](docs/mppt24-escudo-infografico.png)](docs/mppt24-escudo-infografico.png)

[Ver infográfico em tamanho completo](docs/mppt24-escudo-infografico.png)

### Em evolução

| Projeto | Trabalho em curso |
| --- | --- |
| MPPT24 CORE | Empacotamento e instalador público. |
| [Configuração do servidor](https://github.com/mppt24/mppt24-server-setup) | Rotinas de configuração e atualização. |
| [Rust no Termux](https://github.com/mppt24/rustlinux-termux-installer) | Verificação do ambiente e instalador. |
| [MPPT24 Bootstrap](https://github.com/mppt24/mppt24-bootstrap) | Documentação e preparação do arranque dos componentes. |

### Em avaliação

O [AI Hub](https://github.com/mppt24/ai-hub-publish#testar-a-api-localmente) é um protótipo. Podes confirmar que o serviço responde localmente. Para experimentar o chat é preciso ligar ao Ollama. As integrações externas do AGI Absoluta continuam em avaliação.

### Critério de publicação

Uma versão entra na lista de entregas publicadas quando está validada e a versão a disponibilizar está identificada. Um projeto com uma base validada pode ter trabalhos em evolução em paralelo. Os ensaios em avaliação só passam a entregas depois de validados. A manutenção destina-se às correções e atualizações de versões já publicadas.

## Contribuir

Abre uma [issue](https://github.com/mppt24/MPPT24OS/issues) para sugerir uma melhoria nesta página ou para perguntar onde colaborar. Para alterações ao código, usa o repositório do componente. Inclui o contexto necessário para reproduzir o problema e usa dados de exemplo quando a informação vier de um servidor real.

## Licenças

O MPPT24OS usa [MIT](LICENSE). O MPPT24 CORE usa [AGPL-3.0](https://github.com/mppt24/mppt24-core/blob/main/LICENSE). Os módulos [Configuração do servidor](https://github.com/mppt24/mppt24-server-setup/blob/main/LICENSE) e [Rust no Termux](https://github.com/mppt24/rustlinux-termux-installer/blob/main/LICENSE) usam MIT. O AI Hub ainda não tem um ficheiro de licença publicado.
