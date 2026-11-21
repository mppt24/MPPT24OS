# Guia de MPPT24OS

**Estado:** Portal público.

Índice dos projetos e apresentação do ESCUDO.

[![MPPT24OS. Índice e estado dos projetos. Actions: documentação. Backup exige prova de restauro.](docs/guia-visual.png)](docs/guia-visual.png)

## Onde começar

Começa pelo [índice](README.md#explorar-os-projetos) e escolhe um projeto publicado ou em evolução.

## Como confirmar

Em **Actions**, abre «Verificar documentação». Confirma o commit e o resultado. O teste confirma as ligações locais e a imagem do ESCUDO.

## Como ler os registos

Em **Actions**, a tarefa «Cópia temporária e restauro» do workflow «Verificar documentação» cria uma cópia temporária do repositório, restaura-a num segundo diretório e compara o commit. O resultado cobre esse ensaio do Git.

### Exemplo fictício

```text
OK · Documentação · Ligações e PNG verificados
```

Lê pela ordem **resultado**, **etapa** e **detalhe**. Para investigar uma falha, confirma primeiro a data e a versão, depois abre o primeiro passo que falhou.

## Cuidados

O ensaio do Git usa ficheiros temporários. O arquivo histórico e as cópias de segurança do ESCUDO têm percursos próprios. A data do infográfico indica quando o estado foi observado.

O [infográfico do ESCUDO](docs/mppt24-escudo-infografico.png) mostra o estado observado na data indicada no README.

## Como ler um registo do ESCUDO

Os exemplos abaixo são fictícios. No servidor, confirma sempre a hora, a origem do evento e a operação a que diz respeito.

| Área | O que procurar | Como interpretar |
| --- | --- | --- |
| Sistema e serviços | Nome do serviço, resultado e hora | Um serviço parado pode estar inativo por configuração. Uma falha é uma execução que terminou com erro. |
| Rede e acesso | Tipo de evento e resultado | Uma tentativa recusada deve ser lida junto com a origem e o contexto antes de tirar uma conclusão. |
| Cópias e recuperação | Resultado da cópia e teste de restauro | Uma cópia concluída e um restauro verificado são provas diferentes. |
| Monitorização e CORE | Estado e dado que o justificou | `OK` indica que a verificação passou. `WARNING` merece atenção. `ERROR` indica falha na verificação. `UNKNOWN` indica dados insuficientes. |

Por exemplo, «AVISO · Rede · Dados de conectividade insuficientes» pede uma verificação da recolha antes de concluir que a rede falhou.

## Guias dos repositórios públicos

| Projeto | Estado | Guia |
| --- | --- | --- |
| AI Hub | Em avaliação | [Abrir guia](https://github.com/mppt24/ai-hub/blob/main/GUIA.md) |
| AI Hub Publish | Em avaliação | [Abrir guia](https://github.com/mppt24/ai-hub-publish/blob/main/GUIA.md) |
| LOIC | Proveniência do fork | [Abrir guia](https://github.com/mppt24/LOIC/blob/master/GUIA.md) |
| MPPT24 | Perfil público | [Abrir guia](https://github.com/mppt24/mppt24/blob/main/GUIA.md) |
| MPPT24 AGI Absoluta | Chat local validado | [Abrir guia](https://github.com/mppt24/mppt24-agi-absoluta/blob/main/GUIA.md) |
| MPPT24 AGI Computer | Conceito publicado | [Abrir guia](https://github.com/mppt24/mppt24-agi-computer/blob/main/GUIA.md) |
| MPPT24 Bootstrap | Em evolução | [Abrir guia](https://github.com/mppt24/mppt24-bootstrap/blob/main/GUIA.md) |
| MPPT24 CORE | Base pública validada | [Abrir guia](https://github.com/mppt24/mppt24-core/blob/main/GUIA.md) |
| Configuração do servidor | Em evolução | [Abrir guia](https://github.com/mppt24/mppt24-server-setup/blob/main/GUIA.md) |
| MPPT24OS | Portal público | [Abrir guia](https://github.com/mppt24/MPPT24OS/blob/main/GUIA.md) |
| MPPT24OS · Arquivo | Arquivo de 9 de agosto de 2025 | [Abrir guia](https://github.com/mppt24/MPPT24OS-Backup-2025-08-09/blob/main/GUIA.md) |
| mpptOS | Registo inicial | [Abrir guia](https://github.com/mppt24/mpptOS/blob/master/GUIA.md) |
| RustLinux MPPT24 | Maquete publicada | [Abrir guia](https://github.com/mppt24/RustLinux-mppt24/blob/main/GUIA.md) |
| Rust no Termux | Em evolução | [Abrir guia](https://github.com/mppt24/rustlinux-termux-installer/blob/main/GUIA.md) |
| Slowloris | Proveniência do fork | [Abrir guia](https://github.com/mppt24/slowloris/blob/master/GUIA.md) |
| Teste SSH | Repositório de teste | [Abrir guia](https://github.com/mppt24/teste-ssh/blob/main/GUIA.md) |

O [catálogo JSON](docs/guias.json) contém as mesmas ligações num formato que outras ferramentas podem ler.
