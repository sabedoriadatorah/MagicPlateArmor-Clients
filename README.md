# Magic Plate Armor — clientes de teste

Versão atual: **r17 OVH Test**, candidata `2026-10-18-r17`.
Windows, Android e servidor Linux usam a mesma fonte Unity: `1e2e6b9abc87f034c7d17e32f115c5f1ba59f9b5`, protocolo UDP10.

[Página para compartilhar](https://github.com/sabedoriadatorah/MagicPlateArmor-Clients/releases/tag/r17-ovh-test-20261018)

- [Windows ZIP](https://github.com/sabedoriadatorah/MagicPlateArmor-Clients/releases/download/r17-ovh-test-20261018/MagicPlateArmor-Windows-r17-ovh-public.zip)
- [Android APK ARM64](https://github.com/sabedoriadatorah/MagicPlateArmor-Clients/releases/download/r17-ovh-test-20261018/MagicPlateArmor-Android-r17-ovh-public.apk)
- [Identidade e arquivos](https://github.com/sabedoriadatorah/MagicPlateArmor-Clients/releases/download/r17-ovh-test-20261018/DISTRIBUTION.json)
- [SHA256SUMS](https://github.com/sabedoriadatorah/MagicPlateArmor-Clients/releases/download/r17-ovh-test-20261018/SHA256SUMS.txt)

Windows: extraia toda a pasta e execute `MagicPlateArmor.exe`, mantendo as subpastas junto do executável. Android: instale o APK ARM64 e use o aparelho na horizontal. Use sua conta individual e a mesma versão com seus amigos.

Para jogar com amigo e bots: **Preparar partida no servidor**. O treino offline roda localmente. Battle Royale oficial aguarda dez jogadores reais.

Servidor e API atualizados na OVH. Smoke básico passou com dois processos reais do ZIP Windows, tickets individuais HTTPS, DTLS público, início com oito bots, snapshots/movimento e limpeza automática da sala sem reinício. Android físico, UI normal, morte/reconexão/saída confirmada e teste do proprietário continuam pendentes; leia os limites nas notas da release. Esta é uma candidata **Test**, sem aprovação Ready ou regressão completa.

Os clientes públicos contêm somente os arquivos de execução e configuração pública. O commit da tag deste repositório identifica a distribuição; a fonte Unity está identificada separadamente em `DISTRIBUTION.json`. Versões antigas usam protocolo anterior e foram preservadas no histórico.
