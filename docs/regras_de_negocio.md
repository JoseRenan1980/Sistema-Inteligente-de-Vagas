# Regras de Negócio — Sistema Inteligente de Vagas v3.0

## 1. Critérios Obrigatórios
- Salário mínimo: ≥ R$2000
- Benefícios obrigatórios: VT + VR
- ATS mínimo: 70%
- Compatibilidade total com currículo

## 2. Localização permitida
Bairros aceitos:
- Benedito Bentes
- Santa Lúcia
- Antares
- Cidade Universitária
- Tabuleiro do Martins
- Santos Dumont

Exceção:
Outros bairros somente se:
- salário ≥ R$2000
- benefícios confirmados

## 3. Tipos de vaga permitidos
- CLT
- Temporário
- Home Office

## 4. Vagas proibidas
Excluir automaticamente:
- vagas que exigem CNH A
- vagas que exigem veículo próprio

## 5. Áreas permitidas
- Segurança do Trabalho (não técnico)
- Administrativo
- Financeiro
- Atendimento
- Vendas
- Logística (sem veículo próprio)
- Tecnologia nível inicial

## 6. Prioridade de listagem
Ordem:
1. Rigorosas (100% match)
2. Oportunidade (Modo Parcial Inteligente)

## 7. Regras do Modo Parcial Inteligente
Se nenhuma vaga atender 100%:
- permitir vagas faltando apenas 1 requisito
- informar qual requisito está faltando

## 8. Colunas obrigatórias das tabelas
Todas as tabelas devem conter:

- Função
- Empresa
- Salário
- Benefícios
- Tipo
- Modalidade
- Bairro
- Distância
- Tempo deslocamento
- ATS Match %
- Palavras-chave
- Data divulgação
- Vagas 24h
- Vagas 72h
- Vagas 7 dias
- Nível concorrência
- Perfil comportamental
- ID vaga
- Link vaga
- Score prioridade
- Classificação (Rigorosa/Oportunidade)

## 9. Regra de exibição
Campos sem informação devem exibir:
"Não informado" ou "Não divulgado"

## 10. Ordem estrutural do sistema
Fluxo de execução:
Entrada → Filtragem → Validação → Classificação → Ordenação → Exibição
