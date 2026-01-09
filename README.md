# 📚 sr.Biblius — Design Tokens

Este repositório reúne os **Design Tokens oficiais do ecossistema sr.Biblius**, servindo como base visual e técnica para interfaces digitais, protótipos no Figma e futuras implementações em código.

Os tokens aqui definidos garantem **consistência visual**, **escalabilidade** e **fidelidade conceitual** à identidade da família **sr.**, inspirada no universo editorial, bibliográfico e clássico.

---

## 📃 Arquivo principal

- **Arquivo:** `sr-biblius.tokens.json`
- **Origem:** Tokens Studio for Figma
- **Formato:** Design Tokens (JSON)

> ⚠️ Este arquivo foi gerado e estruturado pelo **Tokens Studio**, seguindo seus padrões internos de tipagem e referências. Alterações manuais devem ser feitas com cautela.

---

## ✒️ Tipografia

### Font Families

- **highlight**
  - Fonte: *DM Serif Display*
  - Uso: Títulos, headings e identidade visual
  - Observação: Possui apenas peso **Regular**

- **default**
  - Fonte: *Crimson Text*
  - Uso: Textos corridos, UI, formulários, botões e elementos auxiliares
  - Estilo editorial, remetendo a livros e máquinas de escrita

---

### Font Weights

- `regular`
- `semiBold`

> Para textos, há suporte a versões *italic*.  
> Para títulos (highlight), utiliza-se apenas o peso Regular, respeitando a limitação da fonte. O uso de itálico é permitido de forma pontual para ênfase.

---

### Font Sizes (escala base)

| Token | Tamanho |
|-----|--------|
| xs | 0.75rem (12px) |
| sm | 0.875rem (14px) |
| md | 1rem (16px) |
| lg | 1.25rem (20px) |
| xl | 1.5rem (24px) |
| 2xl | 2rem (32px) |
| 3xl | 3rem (48px) |
| 4xl | 4rem (64px) |

---

### Line Heights

| Token | Valor |
|----|------|
| shorter | 120% |
| short | 140% |
| tall | 160% |
| taller | 180% |

---

### Letter Spacing

- **default:** `0`

> A decisão por `0` mantém a naturalidade tipográfica das fontes serifadas, evitando distorções visuais, especialmente em textos longos.

---

## Estilos Tipográficos

### Headings
- `h1` → `h6`
- Fonte: **highlight**
- Escala progressiva de `4xl` até `md`
- Line-height mais curto para impacto visual

### Body
- Texto padrão
- Versões: regular, semibold, italic e italic semibold
- Line-height: `tall` (160%)

### Auxiliary
- Small, caption e variações em itálico
- Ideal para legendas, metadados e informações secundárias

### UI
- Button
- Label
- Helper

**Helper text** é utilizado para:
- Textos de apoio em formulários
- Mensagens abaixo de inputs
- Dicas, validações e instruções breves

---

## 🎨 Cores

### Paleta principal — `colorBiblius`
Escala de tons quentes e terrosos, inspirados em papel, couro e livros antigos.

- 50 → tons claros de fundo
- 500 → tom base
- 900 → tom mais profundo e contrastante

### Estados semânticos
- `colorError`
- `colorWarning`
- `colorSuccess`

Cada conjunto possui:
- background
- base
- text
- dark

---

## Bordas

### Border Widths
- thin (1)
- mid (2)
- thick (4)

### Border Radius
- xs → lg
- pill (9999px)

### Bordas de componentes
- Botões: default, hover, focus, error, warning, success, disabled
- Inputs: default, focus, error, warning, success, disabled

---

## Sombras (Box Shadow)

As sombras seguem uma estética **sutil, editorial e elegante**, evitando efeitos modernos exagerados.

### Tipo
- Apenas **dropShadow**
- Não há uso de `inset`, respeitando as limitações do Tokens Studio

### Escalas disponíveis
- field
- xs
- sm
- md
- lg

### Características
- Direção vertical leve (`y`)
- Blur progressivo
- Spread controlado
- Cor baseada em `{colorBiblius.800}` com baixa intensidade perceptiva

---

## 📐 Espaçamentos e Sizing

### Spacing
Escala consistente para margens, paddings e gaps, de `0` até `40`.

### Sizing
Utilizado para alturas, larguras e dimensões de componentes.

---

## Opacity

- `disabled`: 0.4
- `overlay`: 0.6

---

## Tokens Numéricos

### Scale
- base: 1
- tight: 0.9
- loose: 1.2

Usado para variações de densidade visual e ajustes finos de layout.

---

## 🧠 Boas práticas

- Não alterar valores diretamente no JSON sem validação no Tokens Studio
- Sempre reutilizar tokens ao invés de valores fixos no Figma
- Manter consistência entre protótipo e implementação

---

## Sobre o sr.Biblius

O **sr.Biblius** é o guardião da organização, da memória e da estética editorial dentro da família **sr.**  
Este Design System reflete esses valores através de escolhas tipográficas clássicas, cores quentes e uma hierarquia visual clara.

**Este Design System é utilizado em todo o arquipélago da família sr., garantindo familiarização, padronização e consistência visual entre produtos e plataformas.**

---

