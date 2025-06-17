# 🔍 Monitoramento de Máquinas Virtuais no Microsoft Azure

## 🧠 Sobre o Desafio

Este projeto foi desenvolvido como parte da formação na DIO, com o objetivo de aplicar na prática os conceitos de monitoramento de recursos no **Microsoft Azure**, especificamente voltado para **máquinas virtuais (VMs)**.

Aqui você encontrará **resumos, anotações e dicas** que compilei durante os estudos, focando na visibilidade, controle e resposta proativa a eventos críticos — como a exclusão de uma VM.

---

## 🎯 Objetivos de Aprendizagem

- Aplicar conceitos aprendidos no ambiente prático do Azure.
- Documentar de forma clara os processos técnicos utilizados.
- Utilizar o GitHub como ferramenta de compartilhamento técnico.

---

## 🧰 Tecnologias e Ferramentas

- [Microsoft Azure](https://azure.microsoft.com/)
- [Azure Monitor](https://learn.microsoft.com/pt-br/azure/azure-monitor/)
- [GitHub](https://github.com/)
- [Markdown](https://www.markdownguide.org/)

---

## ✅ Etapas Realizadas

1. **Criação de uma Máquina Virtual (VM)**
   - Tipo: Windows/Linux
   - Região: Brasil Sul
   

2. **Configuração do Azure Monitor**
   - Ativação de logs e métricas
   - Integração com Log Analytics Workspace
   - Configuração de alertas para eventos críticos

3. **Criação de um Alerta para Exclusão de VM**
   - Alerta baseado em atividade do Azure Activity Log
   - Definição de ação: envio de e-mail para administrador

4. **Visualização de Dados e Alertas**
   - Uso do painel do Azure Monitor
   - Consulta com KQL no Log Analytics

---

## 📝 Anotações e Dicas

- **VMs com Monitoramento Ativo** facilitam a detecção de problemas antes que afetem os usuários.
- O **Log Analytics Workspace** deve ser criado antes de associá-lo ao monitoramento.
- Alertas podem ser configurados para métricas (CPU, disco) ou atividades (como exclusão).
- Utilizar o **Azure Activity Log** é ideal para auditoria e segurança.
- **Tags** nas VMs ajudam na organização e visualização por filtros.

---

## 📷 Capturas de Tela

As imagens estão organizadas na pasta `/images` e mostram:

1. Criação da VM
2. Configuração do Log Analytics
3. Criação do alerta
4. Visualização dos alertas disparados

---

## 📚 Fontes e Materiais de Apoio

- [Microsoft Learn: Monitoramento no Azure](https://learn.microsoft.com/pt-br/training/modules/monitor-azure-resources/)
- [GitHub Docs](https://docs.github.com/)
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)

---

## 🚀 Autor

**Nome:** [Lina Elma Evangelista Carvalho Pereira]  
**GitHub:** [(https://github.com/LynnaLynnaLyh)]

---

## 🔗 Licença

Este projeto está licenciado sob a licença MIT.
