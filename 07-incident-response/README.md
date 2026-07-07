# 07 - Incident Response

## Objetivo

Estudar resposta a incidentes em ambientes cloud, com foco em identificação, contenção, erradicação, recuperação e lições aprendidas.

## Conteúdos estudados

- Incident Response
- Preparation
- Identification
- Containment
- Eradication
- Recovery
- Lessons Learned
- Playbooks
- Cloud Security Incidents
- AWS Security Events

## Conceitos principais

Resposta a incidentes é o processo usado para lidar com eventos de segurança de forma organizada.

O objetivo deste módulo é criar playbooks simples para cenários comuns em AWS Cloud Security.

## Playbooks planejados

### 1. Access Key exposta

Cenário: uma access key foi exposta publicamente.

Ações planejadas:

- Identificar a chave afetada
- Desativar a access key
- Criar nova credencial se necessário
- Revisar permissões do usuário
- Verificar atividades suspeitas no CloudTrail
- Ativar MFA
- Documentar o incidente

### 2. Bucket S3 público

Cenário: um bucket S3 foi configurado com acesso público indevido.

Ações planejadas:

- Identificar bucket afetado
- Bloquear acesso público
- Revisar bucket policy
- Ativar criptografia
- Verificar logs de acesso
- Documentar risco e correção

### 3. Instância EC2 exposta

Cenário: uma instância EC2 está com portas sensíveis abertas para a internet.

Ações planejadas:

- Identificar Security Group afetado
- Remover acesso 0.0.0.0/0 quando inadequado
- Restringir portas
- Revisar logs
- Validar necessidade de acesso remoto
- Documentar mitigação

## Evidências

Adicionar aqui prints, diagramas e anotações dos playbooks.

## Aprendizados

Em andamento.

## Vocabulário em espanhol

- incidente
- respuesta a incidentes
- contención
- erradicación
- recuperación
- credencial expuesta
- acceso sospechoso
- investigación
- evidencia
- lecciones aprendidas
