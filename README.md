# Magic Plate Armor — teste com amigos no OVH

Clientes Windows 64 bits e Android ARM64 da distribuição **r15 OVH**. Use sua conta individual.

| Plataforma | Download | Como instalar |
| --- | --- | --- |
| Windows 64 bits | [Baixar ZIP](https://github.com/sabedoriadatorah/MagicPlateArmor-Clients/releases/download/r15-ovh-test-20261016/MagicPlateArmor-Windows-r15-ovh-public.zip) | Extraia a pasta inteira e abra `MagicPlateArmor.exe` por duplo clique, mantendo todas as subpastas junto dele. |
| Android ARM64 | [Baixar APK único](https://github.com/sabedoriadatorah/MagicPlateArmor-Clients/releases/download/r15-ovh-test-20261016/MagicPlateArmor-Android-r15-ovh-public.apk) | Transfira e instale somente este APK. Jogue com o aparelho deitado, em landscape. |

Esta distribuição atualiza a configuração pública da API para `https://51.81.80.245` e o destino de conexão de jogo para o VPS OVH. Os clientes conservam o código, gameplay e mapas dos binários r15. Nenhuma credencial compartilhada de bootstrap está incluída. O APK mantém o certificado de assinatura original e o alinhamento de 16 KiB.

O empacotamento passou nas verificações locais de integridade, assinatura e limites exatos das alterações de configuração. Os demais payloads de jogo foram preservados. O teste manual do proprietário e o teste em aparelho Android físico continuam pendentes. Esta distribuição não tem aprovação Ready.

As capturas de Home, Ranking, World Trade e LAND são imagens anteriores do Editor r15 com dados DEMO; elas apresentam as telas e não comprovam uma partida completa em aparelho físico.

[Abrir release](https://github.com/sabedoriadatorah/MagicPlateArmor-Clients/releases/tag/r15-ovh-test-20261016) · [Checksums](https://github.com/sabedoriadatorah/MagicPlateArmor-Clients/releases/download/r15-ovh-test-20261016/SHA256SUMS.txt) · [Proveniência](https://github.com/sabedoriadatorah/MagicPlateArmor-Clients/releases/download/r15-ovh-test-20261016/DISTRIBUTION.json)

A tag `r15-ovh-test-20261016` identifica uma derivação de configuração, sem nova compilação nativa. Fonte Unity: `8db9526a2ae75f5869e12ee06b100200ec9c02c9`; protocolo 9 e esquema de backend 15. Mantenha cada distribuição em sua própria pasta; pacotes e drafts anteriores permanecem preservados.
