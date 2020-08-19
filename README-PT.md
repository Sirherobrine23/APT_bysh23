# Uma explicação

Por que não publicar um repositorio APT (debian package repositorio) no Github Pages já que podemos criei esse workflows para publicar no Pages de forma rapida a unica coisa é colocar os pacotes .deb nas pasta:

```txt
package/main
package/contrib
package/non-free
```
# Configurando

## Github

No Repositorio basta clicar no `Use this template` e modificar os seguintes arquivos:

[Modifique o arquivo de distribuição para publicar os pacotes](/public/conf/distributions)

[Modifique o Workflow para que possamos publicar os pacotes](/.github/workflows/apt.yml)

e adicione uma secrets com o nome `PASSWORD` e adicione sua senha caso tenho nas chaves para ser desbloqueadas
