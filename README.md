# LG 29WK600 - Dump da flash (GD25Q32)

Dump da memória flash SPI da placa principal do monitor **LG 29WK600**.
Útil para quem está com o firmware corrompido.

- **Placa:** LM83B / 29WK600 / 34WK650 - EAX68884702 (1.0) - 2019.06.21
- **Chip:** GD25Q32 (4 MiB / 4.194.304 bytes)
- **CRC32:** `0x61FAF599`
- **SHA-256:** `708C96C7AA9AC130DD0E8E87466AB81ACA1E5668B7ED05325F3785B0A9568B7D`

Testado em duas placas, funcionou normalmente.

Gravado com CH341 (3,3 V) + AsProgrammer dregmod v5:  
Desproteger -> Programar -> Verificar -> ler de novo e conferir o CRC32.

## Aviso

Este arquivo é apenas um dump compartilhado, sem garantia. Use por sua conta e risco. Faça backup da sua flash original antes de gravar. Não me responsabilizo por qualquer dano. O firmware pertence à LG; não tenho vínculo com a empresa.

------

LG# LG 29WK600 - Flash Dump (GD25Q32)

SPI flash memory dump from the main board of the **LG 29WK600** monitor.
Useful for cases involving corrupted firmware.

- **Board:** LM83B / 29WK600 / 34WK650 - EAX68884702 (1.0) - 2019.06.21
- **Chip:** GD25Q32 (4 MiB / 4,194,304 bytes)
- **CRC32:** `0x61FAF599`
- **SHA-256:** `708C96C7AA9AC130DD0E8E87466AB81ACA1E5668B7ED05325F3785B0A9568B7D`

Tested on two boards; worked as expected.

Flashed using a CH341 (3.3V) programmer and AsProgrammer (dregmod v5):
Unprotect -> Program -> Verify -> Read back and check the CRC32.

## Disclaimer

This file is provided as-is, without any guarantees. Use it at your own risk. Please back up your original flash content before writing to the chip. I am not responsible for any damage that may occur. The firmware is the property of LG; I have no affiliation with the company.
