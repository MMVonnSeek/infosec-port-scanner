# infosec-port-scanner

# Port Scanner Personalizado com Python

Um port scanner educacional feito em Python, com foco em ensino de redes e segurança da informação. Permite varredura rápida, completa ou personalizada de portas TCP com multithreading.

## Funcionalidades

- Scan básico usando `socket`
- Scan avançado com multithread (`threading`)
- CLI interativa com `argparse`
- Exibição amigável dos resultados (banner, tempo, status)
- Termo de uso ético embutido

## Exemplo de uso

```bash
python scanner.py -t 192.168.0.1 -m full
