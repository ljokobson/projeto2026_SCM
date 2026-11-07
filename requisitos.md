# Requisitos do AgroConecta

Requisitos levantados com o time de Operações da cooperativa.

## Requisitos funcionais

| Código | Requisito | Prioridade |
|--------|-----------|------------|
| RF01 | Cadastrar lavouras e talhões, com área, cultura e datas de plantio e colheita | Alta |
| RF02 | Registrar o uso de insumos (sementes, fertilizantes e defensivos) por safra | Alta |
| RF03 | Funcionar offline e sincronizar os dados quando houver conexão | Alta |
| RF04 | Exibir alertas climáticos para as lavouras cadastradas | Média |
| RF05 | Gerar relatórios de produtividade por safra e por talhão | Média |

## Requisitos não funcionais

| Código | Requisito |
|--------|-----------|
| RNF01 | A interface deve ser simples e legível ao ar livre, para uso no campo |
| RNF02 | O aplicativo deve funcionar em celulares Android e iOS |
| RNF03 | Os dados devem ser protegidos por login e senha de cada usuário |

## Regras de negócio

- Cada talhão pertence a uma única lavoura
- Todo uso de insumo deve estar ligado a uma safra
- Os dados registrados offline não podem ser perdidos na sincronização

## Histórico do documento

| Versão | Descrição |
|--------|-----------|
| 1.0 | Primeira versão dos requisitos |
