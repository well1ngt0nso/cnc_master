# 🛠️ Impressora 3D como CNC – Layout, Impressão e Isolamento de PCB

Este repositório documenta como adaptar uma **impressora 3D (como a Ender 3 V3 SE)** para executar tarefas típicas de uma máquina CNC leve, **sem remover o cabeçote de impressão original**.

Atualmente, o foco está em **desenhar trilhas com caneta** sobre placas de cobre para posterior corrosão química – uma técnica prática e acessível para isolamento de trilhas de **PCBs caseiras**.

---

## ✅ Objetivos

- Demonstrar o uso de impressoras 3D como CNC leve
- Gerar G-code a partir de layouts PCB (via FlatCAM)
- Realizar **desenhos de trilhas com caneta** sobre placas de cobre
- Proporcionar um guia **didático e funcional** para makers e hobbystas

---

## 🧰 Equipamentos e Materiais

- **Impressora 3D:** Ender 3 V3 SE (ou similares com firmware Marlin)
- **Firmware:** Marlin (sem alterações até o momento, pode ser outro)
- **Ferramenta de escrita:** suporte com caneta (pode ser substituido por laser, spindle)
- **Software G-code:** FlatCAM (geração a partir de arquivos Gerber)
- **Superfície:** placa de cobre ou outras superfícies plana para teste

---

## 📁 Estrutura do Repositório

- `firmware/` – Configurações Marlin (futuras alterações e upgrades CNC, pode ser outro firmware)
- `gcode/` – Exemplos prontos de G-code gerado via FlatCAM
- `pcb_layouts/` – Arquivos Gerber de exemplo (KiCad, EasyEDA, Eagle, etc.)
- `fotos/` – Imagens de testes e resultados
- `suporte_caneta/` – STL do suporte para caneta (quando disponível)
- `documentação/` – Guias passo a passo e tutoriais

---

## 🖊️ Etapas Realizadas

1. Geração do layout no software de PCB Eagle
2. Exportação dos arquivos **Gerber** Eagle
3. Importação no **FlatCAM** e geração de caminhos
4. Exportação do **G-code compatível com Marlin** (meu caso)
5. Execução do G-code na impressora com caneta acoplada

---

## 📌 Status do Projeto

✅ Desenho com caneta  
✅ Suporte para caneta simples  
🚧 Isolamento químico (a ser documentado)  
🚧 Futuro: spindle ou laser para corte/furação  
🚧 Futuro: ajustes de firmware específicos para CNC

---

## 📌 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

