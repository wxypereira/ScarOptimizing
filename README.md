# 🚀 ScarOptimizing v1.0

> "Performance não é luxo, é otimização."

O **ScarOptimizing** é um conjunto de scripts de otimização de sistema voltado para dispositivos Android, desenhado especialmente para gamers que buscam extrair o máximo do seu hardware sem a necessidade de Root.

---

## 📖 A História por trás do Projeto
Sempre convivi com celulares limitados. No início, a busca por desempenho se resumia a tutoriais genéricos e aplicativos "Game Turbo" que prometiam tudo e entregavam pouco. Frustrado com as mesmas dicas de sempre, comecei a estudar a fundo a documentação e comportamento do Android. 

O ScarOptimizing nasceu da necessidade de transformar hardware "fraco" em uma máquina de jogo, consolidando tudo o que aprendi e testei. Este projeto é minha contribuição para quem, assim como eu, não desiste de jogar por causa de limitações técnicas.

---

## ✨ Features Principais
O script atua em diversas camadas do sistema para garantir estabilidade, diminuir o *input lag* e manter o foco na jogatina:

* **GPU/CPU Boost:** Ajustes dinâmicos de clock e performance.
* **Debloat Inteligente:** Desativação segura de serviços de telemetria e processos de segundo plano que drenam recursos.
* **Gestão de Memória:** Configurações otimizadas de LMK (Low Memory Killer) e ZRAM.
* **Network VIP:** Priorização de latência para jogos online.
* **WebView Acceleration:** Flags de aceleração de hardware para renderização web mais fluida.
* **Touch Latency:** Redução do delay do toque para respostas imediatas (ideal para FPS).

---

## 🛠 Compatibilidade
O script detecta automaticamente o seu hardware e aplica as otimizações específicas para:
* **Fabricantes:** Samsung, Motorola, Xiaomi.
* **SoC:** Snapdragon e MediaTek.

---

## 📥 Como Instalar e Usar

Não é necessário Root. Você pode usar o **Brevent**, **LADB** ou um terminal shell de sua preferência.

1.  **Prepare o ambiente:** Mova a pasta *ScarOptimzing para a pasta `/sdcard` (armazenamento interno).
2.  **Antes de começar a jogar:**
    ```bash
    sh /sdcard/ScarOptimizing/Disable.sh
    ```
3.  **Otimizar um jogo específico:**
    ```bash
    sh /sdcard/ScarOptimizing/ScarGame.sh <package>
    ```
4.  **Pós-gameplay:**
    ```bash
    sh /sdcard/ScarOptimizing/Enable.sh
    ```

---

## ❓ FAQ (Perguntas Frequentes)

**1. Preciso de Root para usar o script?**
Não. O ScarOptimizing foi desenvolvido para funcionar via ADB, utilizando o Brevent, Shizuku ou LADB.

**2. Tem chance de danificar meu celular?**
Não. O script utiliza comandos de otimização de sistema (settings global) que são seguros. Caso o seu dispositivo não suporte algum comando específico, o Android apenas irá ignorá-lo.

**3. Como sei se está em Hz máximo?**
O script é inteligente e identifica automaticamente o limite máximo de refresh rate suportado pelo seu hardware.

**4. Como desfaço as alterações?**
Basta reiniciar o seu celular. A maioria das configurações de *global settings* retorna ao padrão de fábrica após um reboot.

**5. O que acontece com a ZRAM?**
O script detecta a quantidade total de RAM. Dispositivos com menos de 6GB de RAM terão a ZRAM ativada para melhorar a multitarefa; dispositivos com 6GB ou mais terão a ZRAM desativada para priorizar o desempenho.

---

## 👤 Desenvolvedor
* **Discord:** @rei_das_capivarinhas
* Sinta-se à vontade para abrir uma *Issue* caso encontre algum comportamento inesperado no seu dispositivo.

---
*Este projeto foi desenvolvido com foco em performance e aprendizado sobre o ecossistema Android.*
