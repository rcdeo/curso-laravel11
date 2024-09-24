# TODO

### Composer

Usando o `Composer` para instalar o Laravel no seu sistema.

#### Instalar a versão mais recente

Para instalar a versão mais recente do Laravel, use o seguinte comando:

```shell
composer create-project laravel/laravel example-app
```

Se você deseja instalar uma versão específica, utilize uma das opções a seguir: `laravel/laravel:11.0.x` ou `laravel/laravel:^11.0`, conforme o caso. Além disso, para instalar em um diretório existente, navegue até ele e execute o comando abaixo:

```shell
composer create-project laravel/laravel .
```

#### Instalar a versão mais recente globalmente

Para instalar a versão mais recente do Laravel globalmente, use o seguinte comando:

```shell
composer global require laravel/installer

laravel new example-app
```
