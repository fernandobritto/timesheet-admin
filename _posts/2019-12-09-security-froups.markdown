---
layout: post
title:  "Grupos de Segurança do EC2"
date:   2019-12-09 21:43:35 -0200
categories: jekyll update
---

# Security Groups

### Grupos de segurança do Amazon EC2 

 - Grupos de Segurança é a firewall do EC2
- Todo trafego é bloqueado por padrão
- É permitido apenas adicionar regras para permitir acesso
- Não é permitido criar regras para bloquear trafego especifico
- Todas as mudanças no **Security Group** têm efeito imediato
- Pode se associar diversos **Security Group** a uma única instância do EC2
- Pode se ter diversas instâncias em um único SG
- **Security Group** são **STATEFUL**: Todo trafego permitido a entrar, a resposta poderá sair automaticamente em outra porta




