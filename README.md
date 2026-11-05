....sistema-banco-java

Sistema bancário simples em Java com herança e interface.

- Conta (classe mãe): numero, titular, saldo, depositar, sacar, exibirSaldo
- FechamentoMensal (interface): fecharMes
- ContaCorrente (extends Conta, implements FechamentoMensal): cobra taxa de manutenção de R$ 15,00
- ContaPoupanca (extends Conta, implements FechamentoMensal): paga juros de 1%
- SistemaBanco: método main com os testes

Autor:
Bruno Vieira
Turma: 2º Período Informática - CEFET-MG
