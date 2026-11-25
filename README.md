<div align="center">

# AJUIZA

### `Gratuito` · `Offline` · `Privado`

[![App](https://img.shields.io/badge/app-abrir_painel-172554?style=for-the-badge&logo=github)](https://ajuiza.github.io/)
[![Site](https://img.shields.io/badge/site-oficial-7C3AED?style=for-the-badge)](https://ajuiza.github.io/)
[![Privacidade](https://img.shields.io/badge/dados-no_seu_dispositivo-059669?style=for-the-badge)](https://ajuiza.github.io/)

</div>

---

## `> whoami`

```bash
$ cat /dev/ajuiza
Nome:   Ajuiza · Advocacia Privada
Foco:   processos · clientes · prazos · honorários
Modo:   offline · armazenamento local · sincronização opcional
Custo:  gratuito
```

O **Ajuiza** é um painel digital para organizar a rotina do escritório. Acompanhe processos, clientes, prazos, audiências, honorários e movimentações financeiras em um só lugar.

Os dados do escritório ficam no armazenamento do seu aparelho. O Ajuiza informa que não tem servidores próprios, não coleta telemetria e não envia processos ou clientes a terceiros. Se quiser usar mais de um aparelho, você pode configurar a sincronização com uma planilha Google da sua própria conta.

---

## `> ls ./recursos`

| Recurso | O que você encontra |
| --- | --- |
| ⚖️ **Painel geral** | Visão principal do escritório e acesso rápido às ações do dia a dia |
| 📁 **Processos** | Cadastro e acompanhamento de processos, com busca por número CNJ, cliente ou prazo |
| 👥 **Clientes** | Área para organizar os clientes do escritório |
| 📅 **Prazos processuais** | Controle de prazos e calculadora de prazo CPC |
| 🏛️ **Audiências e agenda** | Organização de audiências e compromissos |
| 💼 **Honorários** | Registro e acompanhamento de honorários |
| 💰 **Financeiro** | Controle de lançamentos financeiros |
| 🧮 **Calculadoras e recibos** | Ferramentas de apoio disponíveis no painel |
| 💾 **Backup e sincronização** | Exportação e restauração de arquivo JSON, ou sincronização opcional com Google Sheets |

---

## `> cat ./privacidade`

```json
{
  "servidores_proprios": false,
  "telemetria": false,
  "dados_do_escritorio": "armazenados no dispositivo",
  "compartilhamento_com_terceiros": false,
  "backup_local": "arquivo JSON",
  "sincronizacao": "opcional, com Google Sheets da sua conta"
}
```

- **Uso local:** os dados ficam no armazenamento interno do aparelho e o app foi apresentado como offline e privado.

- **Sem servidores próprios ou telemetria:** segundo o próprio Ajuiza, o app não coleta telemetria nem envia processos ou clientes a terceiros.

- **Backup sob seu controle:** exporte um arquivo JSON e guarde a cópia onde preferir; também é possível restaurar os dados a partir de um arquivo ou texto JSON.

- **Nuvem opcional:** para sincronizar entre aparelhos, conecte o app a uma planilha privada no seu Google Drive usando Google Apps Script. Essa configuração usa a sua conta Google.

> [!NOTE]
Backup e sincronização com Google Sheets são ações que precisam de internet. A sincronização é opcional; o app também oferece backup em arquivo local.

---

## `> ./iniciar`

```bash
1. Acesse   ajuiza.github.io
2. Instale  use o botão "Instalar App", quando disponível no navegador
3. Comece   cadastre um cliente ou calcule um prazo processual
4. Proteja  faça um backup JSON ou configure sua sincronização opcional
```

[▶ **Abrir o painel Ajuiza**](https://ajuiza.github.io/)

---

## `> ping apoio`

O Ajuiza apresenta uma opção para apoiar o projeto. O apoio é voluntário e separado do uso do painel.

[**Conhecer o projeto e seu criador**](https://saulomgg.github.io/)

---

## `> ping links`

| Canal | Link |
| --- | --- |
| Ajuiza · Painel | [ajuiza.github.io](https://ajuiza.github.io/) |
| Criador | [saulomgg.github.io](https://saulomgg.github.io/) |
| Instagram | [@saulo_mgg](https://www.instagram.com/saulo_mgg/) |
| Telegram | [S0M9Net](https://t.me/S0M9Net) |
| LinkedIn | [saulomgg](https://www.linkedin.com/in/saulomgg/) |

---

## `> cat ./licença`

Os termos de licença do código-fonte não estão informados na página do Ajuiza. Consulte o repositório ou o autor antes de reutilizar, redistribuir ou incorporar o código em outro projeto.

---

<div align="center">

Desenvolvido por [**Saulo (saulomgg)**](https://saulomgg.github.io/)

```
┌─────────────────────────────────────────────┐
│  [ SYSTEM ]  Ajuiza · gestão jurídica       │
│  [ STATUS ]  Offline · privado · local      │
│  [ BACKUP ]  JSON local · Google Sheets*    │
│  [ * ]       Sincronização opcional          │
└─────────────────────────────────────────────┘
```

</div>
