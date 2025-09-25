📊 Modelagem Star Schema - Universidade

Este repositório contém a modelagem dimensional **Star Schema** para análise de dados acadêmicos, focada na entidade **Professor**, desenvolvida a partir de um modelo relacional original.

🎯 Origem do Modelo

O **Star Schema** apresentado foi modelado com base no **modelo relacional original** da universidade, adaptando a estrutura para atender às necessidades de análise e Business Intelligence (BI).

#Modelo Original vs Star Schema:
- **Modelo Relacional**: Estrutura normalizada com múltiplas entidades e relacionamentos complexos
- **Star Schema**: Estrutura desnormalizada otimizada para consultas analíticas

⭐ Características Principais do Star Schema

Componentes do Schema:

**Tabela Fato - Fato_Professor**
- **Função**: Armazena as métricas e medidas analíticas
- **Chaves Estrangeiras**: Ligações com todas as dimensões
- **Métricas**: Quantidade de disciplinas, carga horária, orientações, etc.

#**Tabelas Dimensão** (5 dimensões)
- **Dim_Professor**: Dados dos professores (nome, titulação, status)
- **Dim_Disciplina**: Informações das disciplinas (carga horária, modalidade)
- **Dim_Curso**: Dados dos cursos (tipo, duração)
- **Dim_Data**: Dimensão temporal completa (data, trimestre, semestre)
- **Dim_Local**: Informações de localização (salas, laboratórios)

🚀 Vantagens do Star Schema

✅ **Performance Superior**
- Consultas mais rápidas devido à desnormalização
- Menos joins necessários nas queries analíticas
- Otimizado para agregações e sumarizações

✅ **Simplicidade de Uso**
- Estrutura fácil de entender para usuários de negócio
- Consultas SQL mais simples e intuitivas
- Facilita a criação de relatórios e dashboards

✅ **Flexibilidade Analítica**
- Permite análise multidimensional (slice and dice)
- Suporte a drill-down e roll-up naturalmente
- Ideal para ferramentas de BI (Power BI, Tableau, etc.)

✅ **Manutenção Simplificada**
- Estrutura estável e previsível
- Facilidade na adição de novas dimensões
- Processo de ETL mais straightforward

📈 Diferenças Chave vs Modelo Relacional

| Aspecto | Modelo Relacional | Star Schema |
|---------|-------------------|-------------|
| **Estrutura** | Normalizada (3FN) | Desnormalizada |
| **Foco** | Integridade dos dados | Performance analítica |
| **Joins** | Múltiplos e complexos | Simples e diretos |
| **Consulta** | Transacionais (OLTP) | Analíticas (OLAP) |
| **Usuário** | Desenvolvedores | Analistas de negócio |

🎯 Casos de Uso Recomendados

- **Análise de performance docente**
- **Alocação de recursos por departamento**
- **Planejamento acadêmico semestral**
- **Otimização de uso de espaços físicos**
- **Relatórios gerenciais para diretoria**

---

Desenvolvido como parte da Formação Suzano - Análise de Dados com Power BI - Digital Innovation One
