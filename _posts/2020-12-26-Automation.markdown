---
layout: post
title:  "Automação - Remota"
date:   2020-12-26 21:46:32 -0300
categories: automation WIFI
author: Auto
---
<div id="top"></div>
# Automação - Remota #

<img src="/assets/eniac.jpg" alt="Eniac" style="width:100%;height:100%;">

<img src="/assets/abarlavento.png" alt="Abarlavento Icon" style="float:left;width:90px;height:50px;">
**Acreditava-se** que o mundo teria no máximo cinco computadores. Esta frase / profecia foi atribuída a **Thomas Watson**, fundador da IBM, no século passado. De lá pra cá tudo mudou e dispositivos com mais capacidade de processamento e memória como referido na profecia existem aos bilhões.
<img src="/assets/IBM-mainframe.jpg" alt="IBM" style="float:left;width:50%;height:50%;">
No caso da indústria a automação enveredou por esse caminho ao propor, no início dos tempos, um controlador central para toda a planta. Isso era devido ao custo e a economia de escala obtida por uma implantação centralizada.
Com o barateamento dos equipamentos e a acirrada briga por ter a melhor tecnologia fez com que outras arquiteturas fossem escolhidas sem prejuízo de processamento em com uma confiabilidade melhor.

Unidades centrais de processamento foram instaladas de forma distribuída ao longo da linha ou da planta, cada PLC sendo capaz de receber entradas, direcionar status ao PLC principal e acionar saídas.

Novamente os avanços decorrentes da eletrônica, informática e processamento conferiu aos próprios dispositivos capacidades de tratar entradas e saídas de forma independente. Microprocessadores inseridos de forma a cuidar de determinado processo de forma mais rápida e eficiente do que enviar os dados pela rede, processar no PLC principal e receber os dados via rede para então acionar alguma saída ou mesmo parar ou desligar-se.

**Como se não faltasse mais nada**, o PLC pode dispor de inteligência artificial, além de ser simplesmente programado, interpretando corretamente variações ao padrão de controle necessário para funcionamento. Isso tem aplicação em sistemas remotos, operando a energia solar, via rede celular entre a estação remota e a estação base. Nesse caso é fundamental a autossuficiência de processamento em caso perda do link, para operação segura e confiável. Assim, um desvio de trem pode operar independente de a comunicação ter sido perdida. Um sistema de transportadores de motores entre um galpão fabril e outro de montagem pode continuar funcionando e transportando de forma independente.

<img src="/assets/PLC-over-Cell.jpg" alt="Via Celular" style="float:left;width:50%;height:50%;">
A automação remota, seja por qualquer link, ondas de rádio, celular, ou satélite, só funciona de modo seguro com o PLC remoto programado corretamente com rotinas ***fail-safe***. É fundamental algum recurso de inteligência artificial e, conforme for o caso, de um back-up de energia, comunicação e até de outro PLC.

O que define isso é o quanto **é custoso a quebra** operativa, **o deslocamento da equipe de manutenção** e a previsão de **spare-parts** em locais remotos e de difícil acesso.

<img src="/assets/Automated railway transport picture.jpg" alt="Trilhos" style="float:left;width:100%;height:100%;">


<a href="#top">**topo da página**</a>

