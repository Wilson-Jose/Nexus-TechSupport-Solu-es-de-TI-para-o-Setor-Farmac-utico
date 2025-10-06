# Nexus TechSupport: Soluções de TI para o Setor Farmacêutico
📖 Sobre o Projeto
Este repositório contém a documentação do projeto de conclusão de curso (TCC) em Técnico em Manutenção e Suporte em Informática, desenvolvido pela equipe Nexus TechSupport.

O projeto consiste em uma proposta completa para a reestruturação da infraestrutura de tecnologia, implementação de novos serviços e suporte técnico para a Melius Drogaria, uma farmácia fictícia de pequeno porte. O objetivo é modernizar o ambiente de TI da empresa para aumentar a eficiência operacional, a segurança dos dados e a qualidade do atendimento ao cliente.

❗️ O Problema
Após uma análise do cenário da Melius Drogaria, identificamos diversas deficiências tecnológicas que geravam prejuízos financeiros, baixa produtividade e falhas de segurança.

Principais Desafios:
Hardware Obsoleto: Computadores antigos com travamentos frequentes e lentidão (Intel Pentium, 4GB RAM DDR3, HD SATA).

Sistema de Vendas Instável: Falhas constantes no sistema, resultando em perda de registros de vendas e de clientes.

Rede Defasada: Conexão de internet lenta (10 Mbps), sem redundância e com graves vulnerabilidades de segurança (sem firewall dedicado).

Falta de Segurança e Backup: Ausência de uma rotina de backup de dados críticos e de uma infraestrutura mínima de segurança para proteger os dados dos clientes, violando diretrizes da LGPD.

Suporte de TI Inadequado: Longo tempo de resposta para chamados e falta de soluções eficazes.

Topologia de Rede Antiga
A estrutura original era simples e insegura, contando apenas com o roteador da operadora para gerenciar toda a rede.

✨ A Solução Proposta
A Nexus TechSupport desenvolveu uma solução completa, abordando hardware, software, redes e serviços para transformar a infraestrutura de TI da farmácia.

1. Atualização de Hardware
Substituímos todos os computadores por equipamentos modernos, alugados e com suporte incluído, para garantir o máximo desempenho.

Frente de Caixa (2x): Dell OptiPlex 3000 Micro (Core i3-12100T, 8GB RAM, 256GB SSD).

Gerência (1x): Dell OptiPlex 7010 (Core i5-13500, 8GB RAM, 512GB SSD).

Proprietário (1x): Notebook Dell Vostro 3520 (Core i5-1235U, 8GB RAM, 512GB SSD).

2. Reestruturação da Rede
A rede foi completamente redesenhada para ser mais rápida, segura e confiável.

Link de Internet: Upgrade para um link de fibra ótica de 500 Mbps.

Equipamentos Profissionais:

Firewall: Appliance com pfSense para segurança robusta.

Roteador: Ubiquiti EdgeRouter X.

Switch: TP-Link Gigabit de 8 portas.

Acesso Wi-Fi: Access Point Ubiquiti UAP-AC-LITE.

Organização: Montagem dos equipamentos em um rack de parede.

Topologia de Rede Nova
A nova topologia segmenta a rede e implementa camadas de segurança, com um servidor em nuvem para backup e gestão.

3. Software e Serviços em Nuvem
Implementamos soluções em nuvem para otimizar a gestão e a produtividade.

Sistema de Gestão (ERP e CRM): OMIE Basic, uma plataforma completa para gerenciar finanças, vendas, estoque e relacionamento com o cliente.

Suíte de Produtividade: Microsoft 365 Business Basic para e-mail profissional, armazenamento em nuvem (OneDrive) e ferramentas online (Word, Excel).

4. Contrato de Suporte e Serviços (SLA)
Oferecemos um serviço de suporte técnico estruturado com diferentes níveis de atendimento e tempos de resposta garantidos para assegurar a continuidade das operações da farmácia.

🔌 Projetos Complementares (Arduino)
Como parte do estudo, foram desenvolvidos dois protótipos para automatizar e melhorar processos internos da farmácia:

Trava de Acesso com RFID: Um sistema de trava automática para áreas restritas, que registra o acesso dos funcionários em uma planilha.

Monitor de Temperatura e Umidade: Um dispositivo que monitora as condições do estoque de medicamentos e envia alertas por SMS caso os níveis saiam do padrão, garantindo a qualidade dos produtos.

👥 Equipe Nexus TechSupport
Gabriel Bento de Souza

Giovana Luccas Kadomoto

Gustavo de Moraes Ribeiro

José Wilson Freitas Silva Neto

Kaio Rodrigues dos Santos

Vitor Gregorio Macedo Barreto
