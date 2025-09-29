# Spec: Portal de Inscrição de Projetos de IA — Comunidade de Servidores Públicos

> Local: `/specify/spec.md`

## 1) Título curto
Portal de Inovação em IA — Inscrições para Prêmio / Banco de Projetos

## 2) Resumo (Elevator pitch)
Um portal comunitário voltado a servidores públicos para coletar, exibir e indexar projetos de IA implantados com sucesso no setor público. O objetivo é facilitar o compartilhamento de casos de sucesso (com evidências) e alimentar um prêmio/banco de dados que reconheça práticas replicáveis.

## 3) Por quê (motivo e contexto)
Servidores publicos raramente têm canais centralizados para divulgar projetos aplicados de IA com evidência de produção. O portal reduz barreiras para divulgar, avaliar e replicar soluções, promovendo transparência, aprendizado e incentivo através de reconhecimento (prêmio) e observabilidade técnica.

## 4) Objetivos principais
- Receber inscrições de projetos de IA já implantados em produção no setor público.
- Permitir busca, filtro e navegação por setor, tecnologia, nível de maturidade e evidência.
- Suportar avaliação/curadoria (meta: facilitar seleção para prêmio).
- Exportar lista de inscritos para avaliação e relatório.

## 5) Não-objetivos (escopo fora)
- Não vamos hospedar modelos/artefatos pesados (ex.: checkpoints ML) — apenas links e metadados.
- Não vamos integrar pagamento/contratos no MVP.

## 6) Sucesso (metrics de aceitação)
- Especificação `spec.md` completa e versionada em `/specify` no repo.
- Formulário de inscrição funcional (envia dados e confirma ao usuário).
- Página de listagem com filtros básicos (setor, estado, tecnologia, ano de implantação).
- Admin/curador consegue ver submissões pendentes e exportar CSV.

## 7) Usuários e personas
- Pessoa 1: Servidor(a) que implementou projeto de IA (inscritor) — quer divulgar e concorrer.
- Pessoa 2: Avaliador/curador — revisa inscrições, marca aprovadas para prêmio.
- Pessoa 3: Visitante/gestor público — busca projetos replicáveis.

## 8) Histórias de usuário (high-level)
- Como servidor, eu quero submeter meu projeto com evidências, para que ele seja considerado para o prêmio.
- Como curador, eu quero aprovar/rejeitar submissões e exportar uma lista, para organizar a avaliação.
- Como visitante, eu quero filtrar projetos por área e tecnologia, para achar exemplos relevantes.

## 9) Fluxo UX e telas principais
1. Home / Landing — explicação, CTA “Submeter projeto”, link para regras do prêmio.
2. Formulário de inscrição — campos obrigatórios e upload de evidência (PDF / link externo).
3. Página de confirmação — número de protocolo e e-mail de contato.
4. Listagem pública — cards com informações resumidas + filtros.
5. Página detalhe do projeto — descri

