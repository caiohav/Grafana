# Dashboard de Status do Codex IA

## Passos iniciais

Após importar o primeiro passo será ajustar a variável **$Host** para condizer com os hosts criados no Zabbix.
![Variáveis](https://github.com/caiohav/Grafana/blob/757df01226b9f6fc7a0b78042ab71a668c66a9a7/Codex%20CNJ/img/Vari%C3%A1veis.png)

## Painel "Relatório de disponibilidade..."

Para utilização do gráfico deverá ser criadas árvores de Serviço do Zabbix, organizados de forma parecida os prints abaixo.

Obs.: O nome do(s) serviço(s) **pai** deverá ser igual ao nome do(s) host(s), pois o **IT Service** do painel utilizará a mesma variável dos paineis anteriorires.

![SLA do Codex 1G](https://github.com/caiohav/Grafana/blob/fa200c8432b94159eff0ec2a90540b3e56ecf80b/Codex%20CNJ/img/SLA%20CODEX%201G.png)

![SLA do Codex 2G](https://github.com/caiohav/Grafana/blob/fa200c8432b94159eff0ec2a90540b3e56ecf80b/Codex%20CNJ/img/SLA%20CODEX%202G.png)