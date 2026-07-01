# DESIGN SPECIFICATIONS
## Sistema Visual Completo — João Vitor Oliveira
### Versão 1.0

---

## ÍNDICE

1. [O Símbolo](#o-símbolo)
2. [Paleta de Cores](#paleta-de-cores)
3. [Tipografia](#tipografia)
4. [Geometria & Grid](#geometria--grid)
5. [Ícones & Grafismos](#ícones--grafismos)
6. [Fotografia](#fotografia)
7. [Aplicações](#aplicações)
8. [Princípios de Uso](#princípios-de-uso)

---

## O SÍMBOLO

### Conceito

Representa o processo de transformação através da conexão modular. Cada módulo sozinho é potencial. Conectados, formam estrutura. Evoluindo, geram impacto.

**Princípio:** Conectar para construir. Forjar para transformar. Elevar para deixar legado.

### Evolução do Símbolo

| Estágio | Nome | Descrição |
|---------|------|-----------|
| 01 | POTENCIAL | Módulos soltos, sem conexão |
| 02 | INÍCIO | Primeiras conexões emergindo |
| 03 | ESTRUTURA | Forma definida, parcialmente completa |
| 04 | FORJA | Estrutura consolidada em âmbar |
| 05+ | EVOLUÇÃO | Variações e expansões contínuas |

### Geometria do Símbolo

**Base:** Grid modular 4x4

**Módulo Unitário:**
- Quadrado de 16px
- Linha de 2px
- Proporção 1:1 (sempre quadrado)

**Construção:**
- Linhas externas formam "L" invertido
- Módulos podem conectar-se horizontalmente ou verticalmente
- Nunca diagonal
- Sempre 90 graus

**Proporções:**
```
┌─────────────────────┐
│ 16px (módulo)       │
│ 8px (espaço entre)  │
│ 2px (linha)         │
│ Proporção: 2:1      │
└─────────────────────┘
```

### Versões do Símbolo

#### Principal
- Versão em 4 módulos conectados (forma "S" moderna)
- Largura: 64px
- Altura: 64px
- Uso: Favicon, logo principal

#### Clara
- Versão com espaçamento maior
- 50% de opacidade
- Uso: Fundo, marca d'água

#### Dourada
- Cor âmbar: #E23E3F / #C4842F
- Uso: Destaque, transformação visível

#### Monocromática
- Versão preta sólida
- Versão branca sólida
- Uso: Aplicações restritas

### Área de Proteção

Mínimo de espaço claro ao redor do símbolo:
- Desktop: 20px em todos os lados
- Mobile: 12px em todos os lados
- Impressão: 10mm em todos os lados

Nunca encostado nas bordas. Sempre respirando.

### Tamanho Mínimo

- **Digital:** 32px
- **Impressão:** 15mm
- **Abaixo disso:** Usar versão simplificada

---

## PALETA DE CORES

### Cores Primárias

#### Branco — Clareza
```
HEX:  #FFFFFF
RGB:  255, 255, 255
CMYK: 0%, 0%, 0%, 0%
```
**Uso:** Fundo principal, espaço negativo, respiro visual

#### Grafite — Profundidade
```
HEX:  #2F2F2F
RGB:  47, 47, 47
CMYK: 0%, 0%, 0%, 82%
```
**Uso:** Tipografia primária, estrutura, peso visual

#### Cinza Metálico — Precisão
```
HEX:  #808080
RGB:  128, 128, 128
CMYK: 0%, 0%, 0%, 50%
```
**Uso:** Secundário, divisórias, elementos estruturais

### Cores Secundárias

#### Azul Profundo — Conhecimento
```
HEX:  #1A3A4D
RGB:  26, 58, 77
CMYK: 66%, 25%, 0%, 70%
```
**Uso:** Acento, hover, links, ênfase

#### Âmbar — Forja (Transformação)
```
HEX:  #E23E3F
RGB:  226, 62, 63
CMYK: 0%, 73%, 72%, 11%
```
ou
```
HEX:  #C4842F
RGB:  196, 132, 47
CMYK: 0%, 33%, 76%, 23%
```
**Uso:** Destaque estratégico, chamada de ação, símbolo em transformação

**REGRA:** Âmbar nunca é dominante. Máximo 5-10% da composição. Sempre um detalhe intencional.

### Combinações Recomendadas

| Contexto | Primary | Secondary | Accent |
|----------|---------|-----------|--------|
| Light Mode | Branco | Grafite | Azul |
| Dark Mode | Grafite | Branco | Âmbar |
| Print | Branco | Grafite | Âmbar |
| Digital UI | Branco | Grafite | Azul |

---

## TIPOGRAFIA

### Fonte Primária

**Inter** (Recomendado)

- Limpa e técnica
- Excelente legibilidade em telas
- Suporta múltiplos pesos
- Disponível em Google Fonts

**Alternativas:**
- Geist (GitHub)
- Space Grotesk (Moderna)
- IBM Plex Sans (Corporativa)

### Hierarquia Tipográfica

#### H1 — CLAREZA GERA IMPACTO
```
Font: Inter
Weight: 700 (Bold)
Size: 48px (Desktop) / 32px (Mobile)
Line-height: 1.2
Letter-spacing: -0.02em
```
**Uso:** Títulos principais, seções

#### H2 — Estrutura. Forge. Elevação.
```
Font: Inter
Weight: 600 (SemiBold)
Size: 32px (Desktop) / 24px (Mobile)
Line-height: 1.3
Letter-spacing: -0.01em
```
**Uso:** Subtítulos, seções secundárias

#### H3 — Excelência é um processo
```
Font: Inter
Weight: 600 (SemiBold)
Size: 24px (Desktop) / 18px (Mobile)
Line-height: 1.4
Letter-spacing: 0em
```
**Uso:** Cabeçalhos de cards, destaque

#### Body — Texto Regular
```
Font: Inter
Weight: 400 (Regular)
Size: 16px (Desktop) / 14px (Mobile)
Line-height: 1.6
Letter-spacing: 0em
```
**Uso:** Corpo de texto, descrições

#### Caption — Pequeno
```
Font: Inter
Weight: 400 (Regular)
Size: 12px
Line-height: 1.5
Letter-spacing: 0.01em
```
**Uso:** Legendas, metadata, rodapés

#### Code — Monospace
```
Font: IBM Plex Mono
Weight: 400 (Regular)
Size: 12px
Line-height: 1.6
```
**Uso:** Código, dados técnicos

### Regras Tipográficas

**Nunca:**
- Itálico sem razão funcional
- Mais de 2 fonts na mesma página
- Todas as letras maiúsculas em body text
- Justificar texto

**Sempre:**
- Manter contraste mínimo 4.5:1
- Usar line-height 1.4+ para corpos
- Adicionar tracking em títulos
- Testar legibilidade em mobile

---

## GEOMETRIA & GRID

### Sistema de Grid

**Base:** 8px

```
8px  = 1 unidade
16px = 2 unidades
24px = 3 unidades
32px = 4 unidades
40px = 5 unidades
48px = 6 unidades
64px = 8 unidades
```

### Proporções

**Proporção Áurea:** 1.618

**Módulos:**
- Quadrados (1:1)
- Retângulos (2:1)
- Nunca figuras irregulares

### Espaçamento

**Padding Padrão:**
- Extra small: 8px
- Small: 12px
- Medium: 16px
- Large: 24px
- Extra large: 32px

**Margin Padrão:**
- Seções: 48px (Desktop) / 32px (Mobile)
- Componentes: 24px
- Elementos: 16px

### Alinhamento

- Sempre em grid de 8px
- Nunca números "redondos" arbitrários
- Usar CSS Grid ou Flexbox com gaps de 16px/24px

---

## ÍCONES & GRAFISMOS

### Conceito dos Ícones

Cada ícone representa um estágio do Método Forge:

#### 🔍 OBSERVAR
Representa percepção, visão, descoberta
```
Forma: Lupa + elemento de exploração
Tamanho: 32px / 64px
Peso: 2px stroke
```

#### 🧩 COMPREENDER
Representa conexão, estrutura, relação
```
Forma: Nós conectados
Tamanho: 32px / 64px
Peso: 2px stroke
```

#### 📐 ESTRUTURAR
Representa ordem, grid, organização
```
Forma: Grid + geometria
Tamanho: 32px / 64px
Peso: 2px stroke
```

#### 🔨 FORJAR
Representa construção, transformação, processo
```
Forma: Martelo refinado (não medieval)
Tamanho: 32px / 64px
Peso: 2px stroke
```

#### 🚀 ELEVAR
Representa ascensão, compartilhamento, legado
```
Forma: Ascensão + expansão
Tamanho: 32px / 64px
Peso: 2px stroke
```

### Regras dos Ícones

- Stroke weight: 2px
- Tamanho mínimo: 24px
- Sempre em grid de 8px
- Sem preenchimento, apenas contorno
- Modularidade: podem combinar-se

---

## FOTOGRAFIA

### Direção Artística

**Nunca:**
- Selfies
- Status symbols
- Produtos caros
- Poses forçadas
- Filtros
- HDR exagerado

**Sempre:**
- Documento real
- Processo visível
- Luz natural ou controlada
- Foco no pensamento/ação
- Preto & branco ou cores neutras
- Minimalismo

### Temas Principais

#### Observatório
- Exploração visual
- Céus, estrelas, horizonte
- Curiosidade manifesta

#### Arquitetura
- Linhas, estrutura, proporção
- Concreto, vidro, metal
- Ordem e precisão

#### Forja
- Transformação em processo
- Calor, luz, movimento
- Mãos, ferramenta, detalhe

#### Projeto
- Blueprints, sketches
- Planejamento visível
- Organização em tempo real

#### Legado
- Perspectiva, horizonte
- Pessoas aprendendo
- Impacto compartilhado

### Especificações Técnicas

**Resolução:** 300dpi (print) / 72dpi (web)

**Proporções:**
- 16:9 (landscape)
- 1:1 (quadrado)
- 9:16 (portrait)

**Cor:**
- Escala de cinza predominante
- Âmbar como único destaque (opcional)
- Saturação máxima: 60%

**Contraste:**
- Mínimo 3:1
- Sempre legível

---

## APLICAÇÕES

### Identidade Visual Corporativa

#### Cartão de Visita
```
Frente:
- Nome em H2 (Inter 600)
- Título em Body (Inter 400)
- Símbolo à direita em âmbar

Verso:
- Email em Caption
- LinkedIn em Caption
- Website em Caption
- Símbolo pequeno no canto inferior

Formato: 9cm x 5cm
Material: Papel 300g off-white
Acabamento: Sem brilho
```

#### Letterhead
```
Logo + nome no topo (32px from edge)
Linha grafite 2px na base
Footer: email, telefone, website em Caption
Marca d'água do símbolo em cinza 5% opacidade
```

#### Assinatura de Email
```
JOÃO VITOR OLIVEIRA
Símbolo 24px
Enxergue o potencial. Forje a excelência. Deixe um legado.
email@domain.com
linkedin.com/in/joaovitor
```

### Digital

#### Website
```
Hero: Tipografia H1 + imagem de fundo
Nav: Menu limpo, sem ícones desnecessários
Cards: Padding 24px, border-radius 8px
Footer: Símbolo + contacto

Paleta: Branco + Grafite + Azul acento
Espaçamento: Grid de 8px
```

#### GitHub Profile
```
Bio: "Construtor de potencial. Forge → Impact → Legacy"
Símbolo como avatar
Readme com estrutura clara
Badges mínimos, apenas relevantes
```

#### LinkedIn
```
Foto de perfil: Preto & branco, 400x400px
Banner: Símbolo em âmbar + texto H2
Headline: "Engenheiro | Líder | Construtor de Potencial"
```

### Print

#### Poster / Apresentação
```
Título em H1 (Inter 700)
Símbolo em 256px (canto inferior direito)
Máximo 3 cores: Branco, Grafite, Âmbar
Muito espaço em branco
```

#### Currículo
```
Tipografia: Inter 400 (Body) / 600 (seções)
Símbolo no header (32px)
Linhas de separação em Cinza metálico
Fundo: Branco puro
```

---

## PRINCÍPIOS DE USO

### Regra Fundamental

**Tudo comunica.**

Nenhuma decisão visual é acidental. Cada escolha deve responder:

1. **Isso comunica clareza?**
2. **Isso melhora a compreensão?**
3. **Isso possui um propósito?**

Se a resposta for não, remova.

### O Símbolo Modular

O símbolo nunca é estático. Ele pode:

- ✅ Aparecer completo (marca consolidada)
- ✅ Aparecer parcial (em evolução)
- ✅ Aparecer fragmentado (descoberta)
- ✅ Aparecer conectado (síntese)
- ❌ Nunca mudar de essência

### Uso de Cores

**Hierarquia:**

1. **Branco** — 60% da composição (respiro)
2. **Grafite** — 30% (estrutura)
3. **Azul/Cinza** — 10% (secundário)
4. **Âmbar** — 5-10% máximo (transformação)

**Nunca:**
- Mais de 1 cor "quente" por página
- Fundo colorido + texto colorido
- Âmbar em large areas

### Espaço Negativo

O vazio é tão importante quanto o preenchimento.

- Mínimo 16px entre elementos
- Mínimo 24px entre seções
- Nunca "aperto"

### Consistência ao Longo do Tempo

Esta identidade deve funcionar em:

- ✅ 2026 (hoje)
- ✅ 2031 (5 anos)
- ✅ 2036 (10 anos)
- ✅ 2046 (20 anos)

Nunca será datada porque:
- Não baseada em trends
- Geometria atemporal
- Cores clássicas
- Tipografia neutra

---

## CHECKLIST DE IMPLEMENTAÇÃO

Antes de qualquer aplicação, verificar:

- [ ] Símbolo está em versão correta para contexto?
- [ ] Respeitada área de proteção?
- [ ] Paleta segue proporções 60/30/10/5?
- [ ] Tipografia é legível em 12px?
- [ ] Espaçamento segue múltiplos de 8px?
- [ ] Contraste é 4.5:1 ou superior?
- [ ] Sem efeitos desnecessários?
- [ ] Fotografia segue direção artística?
- [ ] Tudo comunica clareza?

---

## EVOLUÇÃO DO SISTEMA

Este documento será atualizado quando:

- Novas aplicações surgirem
- Feedback real indicar ajustes
- Tecnologia requerer adaptações

Mas os **princípios fundamentais nunca mudarão:**

1. Clareza acima de estética
2. Propósito antes de decoração
3. Evolução sem traição à essência
4. Legado como medida final

---

**DESIGN SPECIFICATIONS v1.0**  
**João Vitor Oliveira**  
**Julho de 2026**

*Este documento é a base técnica do CODEX visual. Consulte-o sempre que tomar uma decisão de design.*
