# Ferramentas de Monitoramento do Azure

O Azure oferece um conjunto integrado de ferramentas para **monitoramento, diagnóstico e otimização** de recursos em nuvem, híbridos e multicloud. Essas soluções ajudam a garantir **disponibilidade**, desempenho e segurança dos ambientes.  

# 
## 1. Principais Ferramentas de Monitoramento

### 🔹 Azure Monitor  
**O serviço central de monitoramento do Azure**, coleta e analisa:  
✅ **Métricas** (dados de desempenho em tempo real, como CPU, memória).  
✅ **Logs** (dados estruturados via consultas KQL - Kusto Query Language).  
✅ **Application Insights** (monitoramento de aplicações, incluindo traces e dependências).  
✅ **Alertas inteligentes** (notificações baseadas em condições pré-definidas).  

#### Casos de uso:
- Identificar gargalos em aplicações.
- Acompanhar SLAs e métricas de negócio.

# 
### 🔹 Microsoft Defender for Cloud
Foca em **segurança e conformidade**, oferecendo:  
✅ **Recomendações de segurança** baseadas em benchmarks (CIS, NIST).  
✅ **Proteção contra ameaças** (detecção de malware, ataques à rede).  
✅ **Secure Score** (pontuação que mede a postura de segurança do ambiente).  

#### Casos de uso:
- Detectar configurações inseguras em VMs ou bancos de dados.
- Monitorar compliance com regulamentações (GDPR, HIPAA).

# 

### 🔹 Azure Network Watcher
Monitoramento e diagnóstico de **redes virtuais (VNETs)**:  
✅ **Verificação de conectividade** (testes de latência, rotas).  
✅ **Captura de pacotes** (para análise de tráfego suspeito).  
✅ **NSG Flow Logs** (registros de tráfego em Security Groups).  

#### Casos de uso:
- Solucionar problemas de conexão entre VMs.
- Investigar ataques DDoS ou tráfego não autorizado.

### 🔹 Log Analytics (dentro do Azure Monitor)
Armazena e analisa **logs centralizados** de:  
✅ Sistemas operacionais (Windows/Linux).  
✅ Aplicações (via Application Insights).  
✅ Serviços Azure (Azure SQL, Storage, etc.).

#### Recursos:
- Consultas KQL para filtrar e correlacionar dados.
- Workbooks para dashboards personalizados.

#### Casos de uso:
- Investigar falhas em aplicações.
- Auditoria de atividades (ex: "Quem excluiu um recurso?").

### 🔹 Azure Service Health
Monitora o status de serviços Azure globalmente:  
✅ Status atual (interrupções, degradações).  
✅ Manutenções planejadas.  
✅ Alertas personalizados para assinaturas críticas.  

#### Casos de uso:
- Receber notificações sobre falhas regionais.  
- Planejar migrações durante janelas de manutenção.


# 
## 2. Integrações Avançadas
✔ **Grafana e Power BI** – Dashboards visuais personalizados.  
✔ **Azure Sentinel** – SIEM para detecção de ameaças baseada em IA.  
✔ **Splunk e Datadog** – Conectores para ferramentas de terceiros.  

# 
## 3. Melhores Práticas
✅ **Centralize logs** em um workspace do Log Analytics.  
✅ **Configure alertas proativos** (ex: "CPU > 90% por 5 minutos").  
✅ **Use Workbooks** para dashboards operacionais.  
✅ **Aplique Azure Policy** para garantir que recursos enviem logs.  

# 
# Conclusão
As ferramentas de monitoramento do Azure permitem:  
#### 🔹 Detectar problemas antes que afetem usuários.  
#### 🔹 Otimizar desempenho e custos.  
#### 🔹 Garantir segurança e conformidade.  
