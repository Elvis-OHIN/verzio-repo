# MyBrew Repository

Ce dépôt contient les manifests et releases pour le gestionnaire de paquets **MyBrew**.

## Structure

- `index.json` : catalogue des paquets
- `manifests/*.json` : description des paquets (nom, version, URL, etc.)
- `releases/*.zip` : archives contenant les binaires des applications

## Exemple de paquets

- `mon-app` : exemple d'application CLI
- `hello-cli` : petit binaire "Hello World"

## Utilisation avec MyBrew

Dans le code de ton client, configure la base URL :

```csharp
var baseUrl = "https://toncompte.github.io/mybrew-repo/";
