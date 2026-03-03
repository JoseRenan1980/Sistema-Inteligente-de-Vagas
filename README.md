
# Sistema Inteligente de Vagas

Sistema estruturado de inteligência aplicada que analisa, filtra e prioriza oportunidades profissionais com base em critérios técnicos, estratégicos e probabilísticos.

![Status](https://img.shields.io/badge/status-stable-brightgreen)
![Version](https://img.shields.io/badge/version-4.0-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)
![Stage](https://img.shields.io/badge/stage-operational-success)

---

## Visão Geral

O Sistema Inteligente de Vagas é um motor lógico de decisão projetado para simular a análise de um recrutador profissional.  
Ele identifica oportunidades relevantes, elimina vagas de baixa qualidade e prioriza candidaturas com maior probabilidade real de contratação.

---

## Versão Atual
**v4.0 — Estável (Arquitetura Modular Hierárquica)**

---

## Principais Recursos

- Score de compatibilidade ATS
- Classificação automática (Rigoroso / Oportunidade)
- Filtro Rigoroso (Alta Precisão)
- Busca Ampliada (Expansão Geográfica)
- Modo Parcial Inteligente (Expansão Lógica Controlada)
- Priorização regional estratégica
- Análise de concorrência estimada
- Perfil comportamental da vaga
- Scanner de páginas corporativas
- Geração automática de relatório estruturado + Excel (.xlsx)

---

## Arquitetura do Sistema — v4.0

O sistema opera em três camadas sequenciais:

### 1️⃣ Filtro Rigoroso (Alta Precisão)

Critérios obrigatórios:
- Salário ≥ R$ 2000
- VT + VR obrigatórios
- ATS ≥ 70%
- Link obrigatório
- ID da vaga obrigatório
- Exclusão de CNH categoria A
- Exclusão de veículo próprio

Regra especial:
- Benedito Bentes pode aceitar salário mínimo mesmo sem benefícios

---

### 2️⃣ Busca Ampliada (Expansão Geográfica)

Aplicada após o filtro rigoroso.

Regras:
- Fora de Maceió → Salário ≥ R$ 2500 + VR/VA + plano de saúde + seguro de vida
- Fora de Alagoas → Salário ≥ R$ 3000 + pacote completo de benefícios

---

### 3️⃣ Modo Parcial Inteligente (Expansão Controlada)

Aplicado após a busca ampliada.

Núcleo inegociável:
- ATS ≥ 70%
- Salário ≥ R$ 2000

Exclusões absolutas:
- CNH categoria A
- Veículo próprio

Flexibilização:
- Benefícios podem não estar especificados publicamente
- Pode falhar em apenas 1 requisito leve

---

## Classificação de Vagas

| Tipo | Definição |
|------|-----------|
| Rigoroso | Atende 100% dos critérios obrigatórios |
| Oportunidade | Atende núcleo mínimo do modo parcial |

---

## Variáveis Avaliadas

- salário
- benefícios
- localização
- compatibilidade curricular (ATS)
- requisitos técnicos
- concorrência estimada
- tempo de publicação
- perfil comportamental

---

## Estrutura de Saída

O sistema gera:

- tabela analítica completa
- score de compatibilidade
- score de prioridade de candidatura
- nível de concorrência estimado
- classificação da vaga
- benefícios confirmados
- distância e tempo de deslocamento
- arquivo Excel (.xlsx)

---

## Fontes Monitoradas

- portais de emprego
- sites corporativos
- plataformas governamentais
- classificados regionais
- páginas "Trabalhe Conosco"

---

## Status do Projeto

Arquitetura modular concluída  
Versão 4.0 validada  
Modo operacional contínuo ativo  
Sistema replicável e escalável  

---

## Instalação

Clone o repositório:

```bash
git clone https://github.com/SEU-USUARIO/NOME-REPOSITORIO.git
