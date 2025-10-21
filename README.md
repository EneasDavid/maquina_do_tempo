# Maquina do Tempo

Hoje voce acordou atrasado.  
O despertador tocou, mas o tempo parecia... diferente.

Voce saiu de casa com pressa, pegou sua mochila e, sem perceber, abriu um **portal de commits**.  
Cada escolha que voce fez — virar à esquerda, esperar o onibus, pegar outro caminho — virou uma nova **branch no tempo**.

Agora existem varias versoes de voce espalhadas no espaco-tempo:
- uma que saiu de casa muito cedo,
- outra que tomou o onibus errado,
- e talvez uma que chegou onde devia, no horario exato...

Mas cuidado.  
Algumas dessas linhas temporais nao deveriam continuar existindo.

Para corrigir o rumo da historia, voce vai precisar **limpar o tempo** e **viajar entre commits**.

```bash
# apague as realidades ruins
git branch -d <nome_branch>
## Não vamos apagar commit!

# e entao... mova-se pelo tempo
git switch <hash_do_momento_que_voce_quiser_rever>
#ou 
git commit <nome_branch>
```

Abaixo está sua linha do tempo, você deve manter apenas a linha do tempo [branch] que te faz chegar no mini curso

```bash
* 85977a2 (HEAD -> main) [Bom dia]
* 3e69c1c [inicio do dia]
* 7007085 [indo pro onibus]
|\
| * 5746519 (esquerda) [pela esquerda]
| * c231c12 [panquenca]
* 9fb9408 (direita) [pela direita]
* 67a80c8 [chegou ao ponto do onibus]
|* 972e939 (primeiro_onibus) [entrou no primeiro onibus que passou]
|\
| * fd557dc (segundo_onibus) [pegou o segundo onibus]
|* 8107bdd [fim da linha]
```