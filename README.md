<a id="readme-top"></a>

[![Contribuidores](https://img.shields.io/github/contributors/wxypereira/ScarOptimizing.svg?style=for-the-badge)](https://github.com/wxypereira/ScarOptimizing/graphs/contributors)
[![Forks](https://img.shields.io/github/forks/wxypereira/ScarOptimizing.svg?style=for-the-badge)](https://github.com/wxypereira/Optimizing/network/members)
[![Estrelas](https://img.shields.io/github/stars/wxypereira/ScarOptimizing.svg?style=for-the-badge)](https://github.com/wxypereira/ScarOptimizing/stargazers)
[![Issues](https://img.shields.io/github/issues/wxypereira/ScarOptimizing.svg?style=for-the-badge)](https://github.com/wxypereira/ScarOptimizing/issues)
[![License: GPL-3.0](https://img.shields.io/badge/License-GPL_3.0-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)

<br />
<div align="center">
  <img width="1797" height="576" alt="scaroptimizing" src="https://github.com/user-attachments/assets/9632185d-38c4-400e-a0e7-7bface950326" />

  <h3 align="center">ScarOptimizing</h3>

  <p align="center">
    Performance não é luxo, é otimização. Otimize seu Android para jogos sem Root.
    <br />
    <a href="https://github.com/wxypereira/ScarOptimizing"><strong>Explore a documentação »</strong></a>
    <br />
    <br />
    <a href="https://github.com/wxypereira/ScarOptimizing/issues/new?labels=bug&template=bug-report---.md">Reportar Bug</a>
    &middot;
    <a href="https://github.com/wxyperiera/ScarOptimizing/issues/new?labels=enhancement&template=feature-request---.md">Requisitar Funcionalidade</a>
  </p>
</div>

<details>
  <summary>Índice</summary>
  <ol>
    <li>
      <a href="#sobre-o-projeto">Sobre o projeto</a>
      <ul>
        <li><a href="#tecnologias-usadas">Tecnologias Usadas</a></li>
      </ul>
    </li>
    <li>
      <a href="#instalação">instalação</a>
      <ul>
        <li><a href="#pré-requisitos">Pré-Requisitos</a></li>
        <li><a href="#instalando">Instalando</a></li>
      </ul>
    </li>
    <li><a href="#como-usar-o-scaroptimizing">Como usar o ScarOptimizing</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contribuição">Contribuição</a></li>
    <li><a href="#licença">Licença</a></li>
    <li><a href="#agradecimentos">Agradecimentos</a></li>
  </ol>
</details>

## Sobre o projeto

O **ScarOptimizing** é um conjunto de scripts de otimização de sistema voltado para dispositivos Android, projetado para extrair o máximo do hardware, especialmente em dispositivos de entrada ou com recursos limitados, sem a necessidade de acesso Root.

Este projeto nasceu da necessidade de superar limitações técnicas. Em vez de recorrer a aplicativos "milagrosos" que não entregam resultados, o ScarOptimizing atua diretamente na camada de `global settings` e `system runtime`, limpando telemetria, gerenciando processos em segundo plano e ajustando o comportamento de CPU/GPU para garantir FPS estável e menor latência.

* **Foco:** Performance extrema para jogos.
* **Segurança:** Scripts baseados em comandos nativos do Android.
* **Inteligência:** Detecta automaticamente o fabricante e SoC para aplicar ajustes ideais.

### Tecnologias usadas

[![Shell](https://img.shields.io/badge/Shell-444444?style=for-the-badge&logo=gnu-bash)](https://en.wikipedia.org/wiki/Shell_script)
[![ADB](https://img.shields.io/badge/ADB-3DDC84?style=for-the-badge&logo=android)](https://developer.android.com/tools/adb)
[![Linux Shell Scripting](https://img.shields.io/badge/Linux_Shell_Scripting-FCC624?style=for-the-badge&logo=linux)](https://www.gnu.org/software/bash/)

## Instalação

Para utilizar o ScarOptimizing, você precisará de uma maneira de executar comandos via terminal no seu Android.

### Pré-requisitos

Você precisará de um dos aplicativos abaixo para executar os scripts:
* [Shizuku](https://shizuku.rikka.app/)
* [Brevent](https://brevent.jianyu.io/)
* [LADB](https://github.com/tytydraco/LADB)
* Ou outro executar de shell de sua preferência.

### Instalando

1. Clone o repositório ou baixe o arquivo `.zip`:
   ```sh
   git clone https://github.com/wxypereira/ScarOptimizing```

2. Mova a pasta ScarOptimizing para a raiz do seu armazenamento interno: /sdcard/.

### Como usar o ScarOptimizing
Antes de jogar (Desabilitar bloatware):
```sh /sdcard/ScarOptimizing/Disable.sh```

Aplicar otimização de jogo:
```sh /sdcard/ScarOptimizing/ScarGame.sh <package>```

Pós-jogo:
```sh /sdcard/ScarOptimizing/Enable.sh```

### Roadmap
 - [x] Otimização de CPU/GPU e Debloat
 - [X] Gestão de Memória e ZRAM Inteligente
 - [ ] Transformar o projeto de script shell para um Aplicativo Nativo.
 - [ ] Interface Gráfica intuitiva.
 - [ ] Sistema de backup automático e restauração de configurações originais.
 - [ ] Integração de perfis para nível de otimização.
 - [ ] Monitoramento em tempo real de FPS e Temperatura dentro do App.

Veja os issues propostas de features.

### Contribuição
Contribuições são bem-vindas. Se tiver sugestões ou melhorias:

1. Fork the Project
2. Create your Feature Branch
3. Commit your Changes
4. Push to the Branch
5. Open a Pull Request

## Agradecimentos

Este projeto não seria possível sem o suporte de ferramentas incríveis e a base de conhecimento da comunidade Android. Agradecimentos especiais a:

* [Android Developers](https://developer.android.com/) - Pela documentação técnica fundamental para compreensão do sistema Android.
* [Shizuku](https://shizuku.rikka.app/) - Pela API essencial para execução de comandos sem root.
* [Brevent](https://brevent.sh/) - Pela referência técnica em gerenciamento de processos.
* Todos os contribuidores que testaram e reportaram bugs.

### Licença
Distribuído sob a licença **GPL-3.0**. Veja o arquivo `LICENSE` no repositório para mais detalhes.

<p align="right">(<a href="#readme-top">Volte ao topo</a>)</p>
