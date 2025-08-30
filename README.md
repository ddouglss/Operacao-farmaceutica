
# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

### **Data:** 29/08/2025

### **Empresa:** Abstergo Industries

### **Responsável:** Douglas Souza


## Introdução

##### Este relatório descreve o processo de implementação de soluções na empresa **Abstergo Industries**, realizado por **Douglas Souza**. Uma distribuidora farmacêutica que atua como centro de distribuição e revenda de produtos para farmácias e outras empresas, conectando-se indiretamente ao cliente final. O objetivo do projeto foi identificar três serviços AWS que possam gerar otimização de processos e redução de custos, considerando que a empresa ainda não utiliza serviços em nuvem.
## Descrição do Projeto

##### O projeto foi dividido em três etapas, cada uma voltada para um serviço específico da AWS, com o objetivo de melhorar a eficiência operacional, segurança de dados e escalabilidade da empresa.

#### **Etapa 1:** Amazon S3

- **Foco da ferramenta:** Armazenamento seguro e escalável de arquivos corporativos e dados logísticos.
- **Descrição de caso de uso:** A Abstergo Industries poderá armazenar relatórios de estoque, pedidos de farmácias e dados de fornecedores de forma centralizada e acessível, garantindo alta durabilidade e segurança sem precisar de servidores físicos.
- **Principal ganho:** Redução de custos com servidores físicos, alta elasticidade para lidar com grandes volumes de dados, e facilidade de acesso e compartilhamento seguro com parceiros.

#### **Etapa 2:** Amazon VPC (Virtual Private Cloud)

- **Foco da ferramenta:** Rede virtual isolada e segura para aplicações e servidores internos.
- **Descrição de caso de uso:** Criar uma infraestrutura de rede privada na nuvem para hospedar sistemas internos, controlar o tráfego entre servidores e manter a comunicação segura com sistemas de farmácias e empresas parceiras, sem exposição desnecessária à internet.
- **Principal ganho:** Segurança e isolamento de rede, permitindo que apenas sistemas autorizados se comuniquem, mantendo conformidade e proteção de dados.

#### **Etapa 3:** AWS Direct Connect

- **Foco da ferramenta:** Conexão dedicada e de baixa latência entre a empresa e a AWS.
- **Descrição de caso de uso:** Estabelecer uma conexão direta e segura do centro de distribuição da Abstergo Industries com os serviços AWS, garantindo transferência rápida de dados, confiabilidade nas integrações com sistemas parceiros e redução de riscos de interrupção de rede.
- **Principal ganho:** Melhora na performance da integração, redução de risco de interrupção, e otimização de custos em comparação com links VPN convencionais.

## Conclusão

##### A implementação dos serviços **Amazon S3**, **VPC** e **Direct Connect** permitirá à **Abstergo Industries** otimizar processos logísticos, melhorar a segurança de dados e reduzir custos com infraestrutura física. Recomenda-se que a empresa continue explorando soluções em nuvem, buscando novas tecnologias que possam aumentar a eficiência e escalabilidade, facilitando o relacionamento com farmácias e clientes finais.
## Arquitetura Cloud e Fluxograma

#### **Descrição da arquitetura:**

1. **Amazon S3** → Armazenamento centralizado de arquivos e backups.
2. **EC2 em sub-redes privadas** → Processamento interno e acesso a dados armazenados no S3.
3. **Sub-redes públicas** → Hospedagem de sistemas web acessíveis por farmácias e parceiros.
4. **VPC** → Isolamento da rede e controle de acesso entre sistemas internos e externos.
5. **Direct Connect** → Conexão dedicada para integração confiável e rápida com parceiros externos.


#### Fluxograma resumido de integração:

![Fluxograma Abstergo](https://github.com/user-attachments/assets/2e4e212f-ef23-4b44-bcfd-456456e934d9)
*Figura 1: Fluxo de integração entre farmácias, parceiros e AWS.*



## Benefícios Gerais

| Benefício       | Descrição |
|-----------------|-----------|
| Redução de custos | Menor investimento em servidores físicos e manutenção. |
| Escalabilidade    | Capacidade de crescer conforme aumento de pedidos e volume de dados. |
| Elasticidade      | Recursos ajustáveis automaticamente conforme demanda. |
| Segurança         | Isolamento de rede, controle de acesso e backups confiáveis. |



## Anexos Documentação de fluxo de integração

- [Manual de Configuração AWS S3, VPC e Direct Connect](https://github.com/user-attachments/files/22056642/Relatorio_ABNT_AWS_Abstergo.docx)


**Assinatura do Responsável pelo Projeto:**
Douglas Souza
- Linkedin : https://www.linkedin.com/in/ddouglss/






