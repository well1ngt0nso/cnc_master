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

## 📁 Estrutura do Repositório

- `firmware/` – Configurações Marlin (futuras alterações e upgrades CNC, pode ser outro firmware)
- `gcode/` – Exemplos prontos de G-code gerado via FlatCAM
- `pcb_layouts/` – Arquivos Gerber de exemplo (KiCad, EasyEDA, Eagle, etc.)
- `fotos/` – Imagens de testes e resultados
- `suporte_caneta/` – STL do suporte para caneta (quando disponível)
- `documentação/` – Guias passo a passo e tutoriais

---

## 📌 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

