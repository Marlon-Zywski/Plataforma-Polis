<div align="center">

# 🏛️ Plataforma Pólis

### O ecossistema definitivo para gestão municipal

[![Design System](https://img.shields.io/badge/Design_System-v2.0-2563EB?style=for-the-badge&labelColor=0F172A)](https://marlon-zywski.github.io/Plataforma-Polis/)
[![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-16A34A?style=for-the-badge&labelColor=0F172A)]()
[![Stack](https://img.shields.io/badge/Stack-Django_+_PostgreSQL-0D9488?style=for-the-badge&labelColor=0F172A)]()

---

**Plataforma Pólis** é um sistema de gestão municipal 100% independente que substitui sistemas legados.  
Unifica **Saúde**, **Educação**, **Tributos** e **RH** em uma única base de dados com arquitetura moderna e segura.

[**🔗 Ver Design System ao Vivo →**](https://marlon-zywski.github.io/Plataforma-Polis/)

</div>

---

## 🎯 Visão Geral

A Plataforma Pólis resolve o problema crônico de municípios brasileiros que operam com dezenas de sistemas desconectados, cada um com seu banco de dados, sua interface e seu fornecedor. O resultado é retrabalho, inconsistência de dados e dependência tecnológica.

**Pólis muda isso.** Um ecossistema, uma base, uma interface.

## 🏗️ Arquitetura

```
┌─────────────────────────────────────────────────────────┐
│                    PLATAFORMA PÓLIS                      │
├─────────────┬──────────────┬─────────────┬──────────────┤
│  Prefeitura │    Saúde     │  Educação   │    SAMAE     │
│   #2563EB   │   #0D9488    │   #D97706   │   #0891B2   │
├─────────────┴──────────────┴─────────────┴──────────────┤
│               Módulos Compartilhados                     │
│   RH · Compras · Financeiro · Protocolo · Documentos    │
├─────────────────────────────────────────────────────────┤
│              Django · PostgreSQL · Redis                  │
│              Base de Dados Unificada                     │
└─────────────────────────────────────────────────────────┘
```

## 🎨 Design System

O Design System é a **fonte da verdade visual** de toda a plataforma. Cada entidade possui sua identidade cromática, e a troca de contexto acontece via variáveis CSS — garantindo consistência em todos os módulos.

| Entidade | Cor Base | Classe CSS |
|----------|----------|------------|
| 🔵 Prefeitura | `#2563EB` | `entidade-prefeitura` |
| 🟢 Saúde | `#0D9488` | `entidade-saude` |
| 🟡 Educação | `#D97706` | `entidade-educacao` |
| 🟣 Assist. Social | `#7C3AED` | `entidade-assistencia` |
| 🔷 SAMAE | `#0891B2` | `entidade-samae` |

> **[→ Explorar o Design System ao vivo](https://marlon-zywski.github.io/Plataforma-Polis/)**

## 📦 Módulos

| Módulo | Descrição |
|--------|-----------|
| **Recursos Humanos** | Funcionários, ponto eletrônico, folha de pagamento, férias |
| **Compras** | Licitações, contratos, almoxarifado |
| **Financeiro** | Contabilidade, tesouraria, planejamento |
| **Protocolo** | Tramitação e acompanhamento de processos |
| **Documentos** | Gestão documental centralizada |
| **Obras** | Obras públicas e medições |
| **Frotas** | Gestão de veículos municipais |
| **Tributos** | Arrecadação e fiscalização |

## 🛡️ Stack Tecnológica

| Camada | Tecnologia |
|--------|-----------|
| **Backend** | Django (Python) |
| **Banco de Dados** | PostgreSQL |
| **Cache** | Redis |
| **Frontend** | HTML5, CSS3 (Design System próprio), JavaScript |
| **Tipografia** | Inter (Google Fonts) |
| **Hospedagem** | Infraestrutura própria do município |

## 🔐 Princípios

- **🏠 Independência total** — Sem dependência de fornecedores externos
- **🔒 Segurança by design** — Dados sensíveis ficam na infraestrutura do município
- **🎨 Consistência visual** — Design System como fonte da verdade
- **📊 Base unificada** — Um dado, um lugar, zero retrabalho
- **⚡ Performance** — Arquitetura moderna com cache inteligente

---

<div align="center">

**Plataforma Pólis** · Bal. Rincão/SC · 2027

*Construído com obsessão por excelência.*

</div>
