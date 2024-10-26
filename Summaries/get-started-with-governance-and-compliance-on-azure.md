# **Primeiros Passos com Governança e Conformidade na Azure**

<br><br>

A governança e a conformidade são elementos essenciais para garantir que uma organização mantenha controle sobre seus recursos de TI, garantindo segurança, conformidade regulatória e eficiência na gestão de custos. No Microsoft Azure, ferramentas como Azure Policy, bloqueios de recursos e o Microsoft Purview ajudam empresas a manter operações seguras e alinhadas às melhores práticas. Este artigo explora como o Azure facilita a governança e a conformidade com padrões organizacionais, destacando também o Portal de Confiança do Serviço, que oferece transparência sobre a segurança e conformidade da plataforma.

<br><br><br>

---

## **Governança e Azure Policy**

O Azure Policy é uma ferramenta que permite a criação e a aplicação de políticas organizacionais para gerenciar recursos e garantir conformidade em larga escala.

- **Finalidade**:
    - Impor padrões internos e garantir que todos os recursos sigam diretrizes organizacionais.
    - Monitorar conformidade regulatória para atender a normas como GDPR e ISO 27001.

- **Funcionalidades**:
    - Avaliação contínua dos recursos para verificar se estão em conformidade com as políticas definidas.
    - Oferece uma coleção de iniciativas integradas, categorizadas em áreas como armazenamento, rede e segurança.
    - Aplicação automatizada de políticas para garantir que nenhum recurso seja configurado fora dos padrões definidos.

> **Exemplo**: Uma política pode exigir que todo armazenamento no Azure seja criptografado ou que nenhuma máquina virtual seja criada em uma região não aprovada.

<br><br><br>

---

## **Bloqueios de Recursos**

Os bloqueios de recursos protegem recursos críticos de exclusões ou modificações acidentais.

- **Níveis de Aplicação**:
    - **Assinatura**: Bloqueia a exclusão de todos os recursos sob uma assinatura específica.
    - **Grupo de Recursos**: Aplica-se a grupos de recursos inteiros.
    - **Recursos Individuais**: Protege recursos específicos, como VMs ou bancos de dados.

Existem dois tipos principais de bloqueios:

- **ReadOnly**: Restringe a modificação de recursos, permitindo apenas operações de leitura.

- **Excluir**: Impede a exclusão, mas permite alterações na configuração.

> **Dica**: O uso de bloqueios é essencial para evitar que mudanças inadvertidas comprometam a continuidade de serviços essenciais.

<br><br><br>

---

## **Microsoft Purview**

O Microsoft Purview é uma solução abrangente de **governança**, **risco** e **conformidade** de dados que oferece uma visão unificada dos dados de uma organização, independentemente de estarem armazenados no local ou na nuvem.

- **Funcionalidades**:
    - **Descoberta Automatizada de Dados**: Identifica dados onde quer que estejam armazenados.
    - **Classificação de Dados Confidenciais**: Detecta informações sensíveis, como dados pessoais ou financeiros.
    - **Linhagem de Dados**: Acompanhe o ciclo de vida dos dados, desde sua criação até o uso final, garantindo rastreabilidade.

- **Benefícios**:
    - Facilita a conformidade com normas como GDPR e HIPAA.
    - Oferece uma visão integrada para monitorar e auditar dados em várias plataformas, incluindo multinuvem.

<br><br><br>

---

## **Portal de Confiança do Serviço**

O Portal de Confiança do Serviço fornece transparência sobre como o Azure lida com segurança e conformidade.

- **Recursos Disponíveis**:
    - Documentação sobre certificações e auditorias realizadas pela plataforma, incluindo relatórios de conformidade ISO e SOC.
    - Informações sobre boas práticas de segurança e privacidade adotadas pelo Azure.

- **Uso**:
    - Empresas podem consultar o portal para verificar se os serviços utilizados estão em conformidade com normas de governança e regulamentações específicas.
    - Facilita auditorias internas e externas, fornecendo evidências documentais de conformidade.

<br><br><br>

---

## **Conclusão**

A governança e a conformidade são essenciais para que as empresas mantenham operações seguras e eficientes na nuvem. O Azure Policy garante que todos os recursos sejam configurados de acordo com diretrizes organizacionais e normativas. Os bloqueios de recursos impedem alterações acidentais em serviços críticos, enquanto o Microsoft Purview oferece visibilidade completa sobre dados e facilita a conformidade regulatória. Além disso, o Portal de Confiança do Serviço garante transparência e apoio para auditorias e relatórios. Ao integrar essas ferramentas e práticas, as organizações podem maximizar a eficiência operacional e garantir que seus ambientes de TI estejam sempre em conformidade com padrões rigorosos.