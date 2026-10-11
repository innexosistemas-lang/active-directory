# ad-lab

> **Active Directory** dos dois lados: administração do dia a dia (suporte) e ataques comuns com suas detecções (segurança).

![Status](https://img.shields.io/badge/status-em%20constru%C3%A7%C3%A3o-yellow?style=flat-square) ![Foco](https://img.shields.io/badge/foco-Suporte%20%2B%20SOC-0d1117?style=flat-square)

## Ambiente

| Componente | Função |
|---|---|
| Windows Server (VM KVM) | Controlador de domínio (AD DS, DNS, DHCP) |
| Windows 11 (VM) | Estação ingressada no domínio |
| Kali Linux | Testes ofensivos controlados |
| Wazuh + Sysmon | Detecção dos eventos |

## Parte 1 — Administração

- [ ] Promover o DC e criar o domínio `lab.local`
- [ ] OUs, usuários e grupos por departamento
- [ ] GPOs: política de senha, bloqueio de conta, mapeamento de unidade
- [ ] Rotina de suporte: reset de senha, desbloqueio, permissões de pasta
- [ ] Scripts PowerShell para tarefas repetitivas

## Parte 2 — Ataque e detecção

- [ ] Password spraying → eventos 4625 / 4771
- [ ] Kerberoasting → evento 4769
- [ ] Enumeração com BloodHound
- [ ] Hardening e mitigação de cada caso

---
<sub>Todos os testes são feitos em ambiente próprio e isolado.</sub>
