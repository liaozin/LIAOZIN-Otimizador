# 🦁 LIAOZIN Otimizador

> **Otimização, manutenção, monitoramento, segurança e personalização para Windows 10/11.**

O **LIAOZIN Otimizador** reúne ferramentas que normalmente ficam espalhadas pelo Windows em uma única aplicação, com uma interface própria, leve e personalizável.

O projeto foi desenvolvido para oferecer ao usuário mais controle sobre limpeza, manutenção, monitoramento, privacidade, segurança e desempenho do sistema.

---

## ✨ Principais recursos

### 🧹 Limpeza do sistema

- Limpeza rápida de arquivos temporários
- **Limpeza Pesada** para arquivos e caches adicionais
- Limpeza de caches
- Limpeza da Lixeira
- Limpeza de dados temporários de navegadores
- Limpeza de múltiplos discos
- Remoção de arquivos desnecessários
- Resultado da limpeza apresentado diretamente no aplicativo

---

### 🎮 Modo Gamer

O Modo Gamer reúne ferramentas para preparar e monitorar o sistema durante jogos.

- Monitoramento de FPS
- Overlay configurável
- Monitoramento de CPU
- Monitoramento de RAM
- Monitoramento de GPU
- Monitoramento de temperatura
- Seleção individual das métricas exibidas
- Posição configurável do overlay
- Movimento livre do overlay
- Ajuste automático do tamanho do overlay
- Sessões PresentMon/ETW gerenciadas automaticamente
- Limpeza de sessões anteriores para evitar processos presos
- Otimizações opcionais do Windows para jogos
- Visualização das alterações realizadas pelo Modo Gamer
- Restauração das configurações anteriores ao desativar

O monitoramento permanece desligado até ser iniciado pelo usuário.

---

### ⚙️ Tweaks

Área dedicada aos ajustes do Windows.

- Ajustes de sistema
- Estado atual de cada configuração
- Indicação **Ativado / Padrão**
- Aplicação individual dos ajustes
- Opções reversíveis sempre que possível

---

### 🛠️ Manutenção e reparo do Windows

Ferramentas para verificar e reparar componentes do sistema.

- **SFC /scannow**
- **DISM**
- **CHKDSK**
- Verificação da integridade do Windows
- Verificações adicionais de saúde do sistema
- Windows Update
- Verificação de atualizações
- Atualização de drivers através dos recursos disponíveis do Windows
- WinGet
- Ferramentas nativas do Windows

Os resultados das operações são apresentados dentro do próprio LIAOZIN.

---

### 🛡️ Segurança

Integração com ferramentas de segurança do Windows.

- Microsoft Defender
- Verificações de segurança
- Resultados apresentados diretamente no aplicativo
- Interface própria para os resultados
- Verificação de arquivos através do VirusTotal
- Opção de abrir o VirusTotal diretamente quando necessário
- Avisos quando um arquivo pode não ser adequado para análise direta

> O LIAOZIN não substitui o Microsoft Defender ou outras soluções de segurança.

---

### 🔒 Privacidade

Área dedicada às configurações relacionadas à privacidade do Windows.

Dependendo da versão e configuração do Windows, o LIAOZIN pode disponibilizar controles relacionados a:

- Telemetria
- Diagnóstico do Windows
- ID de publicidade
- Localização
- Delivery Optimization
- Serviços e recursos executados em segundo plano
- Outras configurações relacionadas à privacidade

As opções são apresentadas ao usuário antes da aplicação e devem ser reversíveis sempre que possível.

---

### 🖥️ Monitoramento do sistema

Informações detectadas diretamente do Windows.

- CPU
- GPU
- RAM
- Discos
- Temperatura
- Uso dos recursos em tempo real
- Múltiplos discos
- Informações básicas do sistema

---

### 🏠 Tela inicial

A tela inicial reúne informações importantes e acessos rápidos.

- Informações do PC
- CPU
- GPU
- RAM
- Armazenamento
- Acessos rápidos às principais ferramentas
- Estado de proteção
- Acesso rápido às funções de manutenção

---

### 🔔 Bandeja do sistema

O LIAOZIN pode permanecer ativo em segundo plano através da bandeja do Windows.

- Execução em segundo plano
- Ações rápidas
- Inicialização automática com o Windows
- Inicialização diretamente na bandeja
- Controle do Modo Gamer
- Ações rápidas de manutenção
- Baixo consumo de recursos quando o monitoramento não está sendo utilizado

---

### 🎨 Personalização

O LIAOZIN possui um sistema próprio de personalização.

- Temas
- Aparência do aplicativo
- Temas especiais
- Elementos animados
- Efeitos de fundo
- Personalização da tela inicial
- Preferências salvas
- Animações da interface
- Splash screen adaptada ao tema
- Elementos visuais próprios do LIAOZIN

---

### 🔄 Atualizações automáticas

O aplicativo possui integração com o sistema de Releases do GitHub.

- Verificação automática de novas versões
- Listagem de atualizações
- Informações sobre as alterações da versão
- Atualização pelo próprio aplicativo
- Download da nova versão
- Sem necessidade de reinstalar manualmente cada atualização

---

## 🚀 Primeira execução

Na primeira abertura, o LIAOZIN apresenta opções para configurar o funcionamento do aplicativo.

O usuário pode escolher:

- Inicialização automática com o Windows
- Inicialização na bandeja
- Permissões administrativas automáticas
- Tema e aparência
- Personalização
- Modo Gamer
- Monitoramento

> Nenhum recurso precisa ser ativado obrigatoriamente. O usuário mantém controle sobre as funções utilizadas.

---

## 🎮 Monitoramento de FPS

Para utilizar o monitoramento:

1. Abra o **Modo Gamer**.
2. Ative o monitoramento.
3. Escolha as métricas desejadas:
   - FPS
   - CPU
   - RAM
   - GPU
   - Temperatura
4. Escolha a posição do overlay.
5. Inicie o jogo.

O overlay se adapta automaticamente às métricas selecionadas.

O monitoramento utiliza **PresentMon/ETW**.

Para melhor compatibilidade, recomenda-se utilizar jogos em **janela sem bordas**.

> O monitoramento pode causar um pequeno impacto de desempenho enquanto estiver ativo.

---

## 🔒 Privacidade e controle do usuário

O LIAOZIN foi desenvolvido com a ideia de manter o usuário no controle.

As funções que alteram configurações do Windows devem informar o que será alterado sempre que possível.

O aplicativo não deve realizar alterações silenciosas de configuração sem que o usuário tenha ativado a respectiva função.

---

## 🛡️ Microsoft Defender SmartScreen

O Windows pode exibir um aviso do **Microsoft Defender SmartScreen** ao executar o instalador.

Isso pode ocorrer quando um aplicativo distribuído fora da Microsoft Store ainda não possui assinatura digital ou reputação estabelecida.

O projeto poderá utilizar assinatura de código futuramente para melhorar a experiência de instalação e distribuição.

---

## ⚠️ Observações

- Algumas ferramentas exigem privilégios administrativos.
- SFC, DISM e CHKDSK podem levar alguns minutos.
- Algumas funções dependem dos recursos disponíveis na versão do Windows instalada.
- O monitoramento de FPS permanece desligado até ser ativado.
- Algumas otimizações podem alterar temporariamente configurações ou serviços do Windows.
- Sempre revise as opções antes de aplicar alterações no sistema.
- O LIAOZIN não precisa manter o monitoramento de FPS ativo para funcionar normalmente.

---

## 📦 Instalação

1. Acesse **[Releases](../../releases)**.
2. Baixe o instalador mais recente.
3. Execute o instalador.
4. Abra o **LIAOZIN Otimizador**.
5. Configure as opções desejadas.

O instalador é distribuído como aplicação **self-contained**, não exigindo uma instalação separada do .NET para executar o aplicativo publicado.

---

## 🔄 Sistema de atualização

O LIAOZIN verifica novas versões disponibilizadas no repositório oficial.

Quando uma atualização está disponível, o aplicativo apresenta as informações da nova versão.

O usuário pode iniciar a atualização diretamente pelo LIAOZIN.

As informações da atualização são mantidas através do arquivo `latest.json`.

---

## 📋 Histórico de versões

### 🦁 1.7.5

Principais mudanças:

- Nova área de Privacidade
- Limpeza Pesada
- Melhorias no Modo Gamer
- Melhorias no overlay de FPS
- Ajuste automático do tamanho do overlay
- Melhorias no gerenciamento das sessões PresentMon/ETW
- Melhorias no sistema de manutenção do Windows
- Novas verificações de saúde do sistema
- Melhorias na integração com VirusTotal
- Nova configuração inicial
- Melhorias na personalização
- Mais efeitos animados
- Splash screen adaptada ao tema
- Melhorias nas barras de progresso
- Melhorias nas traduções
- Correções de caracteres
- Melhorias gerais na interface
- Correções de estabilidade

---

## 📦 Versão atual

**LIAOZIN Otimizador 1.7.5**

Acesse **[Releases](../../releases)** para baixar a versão mais recente.

---

## 🦁 Sobre o projeto

O LIAOZIN Otimizador nasceu com uma ideia simples:

> **Reunir ferramentas importantes do Windows em um único lugar.**

O projeto busca oferecer uma experiência:

- Leve
- Prática
- Personalizável
- Transparente
- Fácil de usar

O objetivo é transformar o LIAOZIN em uma central completa de manutenção, otimização, monitoramento e personalização para Windows.

---

## 📄 Licença

Este projeto possui uma licença própria.

Consulte o arquivo [`LICENSE`](LICENSE) para conhecer os termos completos de utilização, modificação e distribuição.

---

## 🦁 LIAOZIN

**Otimize. Monitore. Mantenha. Personalize.**

**Tudo em um só lugar.**
