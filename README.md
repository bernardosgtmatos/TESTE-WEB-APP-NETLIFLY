# Chromebook Manager Pro - Sistema de Agendamento

## 🔒 Sistema com Segurança Máxima

### Funcionalidades
- ✅ Autenticação de usuários
- ✅ Controle de acesso por perfil (admin/professor)
- ✅ Limites diários por professor
- ✅ Logs de auditoria completos
- ✅ Proteção contra sobreposição de horários
- ✅ Interface responsiva

### Tecnologias
- Supabase (Auth + Database + RLS)
- Netlify (Hospedagem)
- HTML/CSS/JS Puro

### Configuração de Segurança
- Row Level Security (RLS) ativado
- Políticas restritivas por usuário
- Logs de todas as operações
- Limites configuráveis
- Proteção contra SQL injection

### Variáveis de Ambiente Necessárias
- `SUPABASE_URL`: URL do projeto Supabase
- `SUPABASE_ANON_KEY`: Chave anônima do Supabase

### Deploy
Este projeto está configurado para deploy automático no Netlify.