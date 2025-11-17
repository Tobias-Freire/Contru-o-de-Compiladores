## Rodando essa atividade
- `python3 ci_compiler.py <entrada.ci> <saida.s>` 
- `as --64 -o <saida.o> <saida.s>`
- `ld -o <saida> <saida.o>`
- `./<saida>`

Exemplo:
```bash
python3 ci_compiler.py p1.ci saida.s
as --64 -o saida.o saida.s
ld -o saida saida.o
./saida
```